# Security

EKIN is an educational portfolio/internship project, but its commerce path was designed with production-style privacy boundaries.

## Implemented controls

- **Exact email verification:** order data is returned only after the checkout email matches the Shopify order.
- **Generic verification failure:** the same failure shape is used for missing orders and email mismatches to reduce information leakage.
- **Input normalization:** order numbers and emails are normalized before lookup.
- **Test-order restriction:** the Shopify search is limited to test orders in the provided workflow.
- **Server-side secrets:** Supabase, Gemini, and Shopify credentials belong in n8n/server-side secret storage.
- **RAG grounding:** company answers are constrained to retrieved knowledge rather than unrestricted model memory.
- **Defense in depth:** Workflow 04 checks the `verified` flag again before returning order fields.

## Public-repository hardening

The workflow exports in this repository have real credentials removed. The Shopify configuration contains placeholders only.

Before deploying outside a demo environment:

1. Store Shopify credentials in n8n credentials/secret management instead of a Code node.
2. Restrict Workflow 04 CORS `allowedOrigins` to the actual frontend origin instead of `*`.
3. Keep the Supabase `service_role` key server-side only.
4. Add rate limiting / abuse protection to public webhook endpoints.
5. Review returned shipping/order fields and minimize PII to the exact business need.
6. Rotate any credential that has ever been pasted into chat, logs, screenshots, or an exported workflow.
