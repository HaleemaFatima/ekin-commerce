# n8n Workflows

Import the workflows in numerical order.

| # | File | Responsibility |
|---|---|---|
| 01 | `01-company-knowledge-ingestion.json` | Uploads company documents, chunks text, generates Gemini embeddings, and writes them to Supabase. |
| 02 | `02-nike-rag-chatbot.json` | Retrieves relevant Nike knowledge from Supabase and generates grounded answers. |
| 03 | `03-shopify-order-lookup.json` | Validates order input, queries Shopify test orders, verifies the checkout email, and returns a privacy-safe order response. |
| 04 | `04-ekin-main-chatbot-router.json` | Receives website requests and routes them to RAG, Shopify, or a local response path. |

## After import

1. Create/select the Supabase credential in Workflows 01 and 02.
2. Create/select the Google Gemini credential in Workflows 01 and 02.
3. In Workflow 03, configure the Shopify store domain and private app credentials. Do **not** hard-code real secrets in a public export.
4. In Workflow 04, re-select Workflows 02 and 03 in the two **Execute Workflow** nodes.
5. Activate child workflows before enabling the router.
6. Use test orders only for the portfolio demonstration.

All public workflow exports in this repository have credentials and instance-specific identifiers removed or neutralized.
