# Architecture

```mermaid
flowchart LR
    U[Website / WordPress User] --> R[Workflow 04<br/>EKIN Router]

    R -->|Company question| K[Workflow 02<br/>Nike RAG Chatbot]
    K --> E[Gemini Query Embedding]
    E --> S[(Supabase documents)]
    S --> M[match_documents RPC]
    M --> A[Gemini Grounded Answer]
    A --> R

    R -->|Order request| O[Workflow 03<br/>Shopify Order Lookup]
    O --> V[Validate order + email]
    V --> SH[Shopify Admin GraphQL]
    SH --> P[Exact email verification]
    P --> R

    D[Workflow 01<br/>Knowledge Ingestion] --> C[Chunk document]
    C --> GE[Gemini Embeddings]
    GE --> S

    R --> U
```

## Design decisions

### Separation of concerns
The project uses four workflows instead of one oversized automation. Ingestion, knowledge retrieval, commerce lookup, and routing can be tested independently.

### Grounded knowledge path
Nike-related factual questions are routed to a RAG workflow. The language model is instructed to use the Supabase retrieval tool before answering and to fall back when the stored corpus does not contain the answer.

### Verified order path
Order details are treated as private data. Workflow 03 requires both an order identifier and the checkout email. A valid order number alone is not enough to disclose order fields.

### Router as control plane
The main webhook accepts several frontend-friendly field names, normalizes them, detects personal-order intent, gathers missing fields when necessary, and invokes only the required child workflow.
