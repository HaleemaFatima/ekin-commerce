# Knowledge Base

Workflow 01 ingests company documents into Supabase and converts them into vector-searchable chunks.

For the EKIN demo, the RAG corpus is the **Nike Public Knowledge Base**, built from publicly available official Nike sources and clearly marked as an unofficial educational portfolio resource.

## Included corpus

- [`Nike_Public_Knowledge_Base_RAG.md`](Nike_Public_Knowledge_Base_RAG.md) — GitHub-readable version of the project knowledge base used for RAG ingestion and testing.

The original project source was a DOCX document. A Markdown copy is versioned here because it is directly inspectable, searchable, and diffable in GitHub while preserving the same knowledge-base structure, source tags, grounding rules, regional-policy warnings, and official source register.

## RAG usage

1. Import Workflow 01.
2. Configure the Supabase and Gemini credentials.
3. Upload the knowledge corpus through the ingestion form.
4. Confirm chunks are inserted into `public.documents` with 3072-dimensional embeddings.
5. Use Workflow 02 to retrieve relevant chunks through `match_documents` before answering.

Do not place customer data, private company records, access credentials, or private order information in this public knowledge corpus.
