# Testing Checklist

The project was tested around functional behavior, routing, and privacy boundaries.

## Knowledge / RAG

- [x] Upload a company knowledge document through Workflow 01.
- [x] Confirm document chunks are stored in Supabase.
- [x] Ask a question covered by the Nike knowledge base.
- [x] Confirm Workflow 02 retrieves context before answering.
- [x] Ask an unsupported question and confirm a safe fallback.

## Shopify order lookup

- [x] Valid test order + matching checkout email returns order details.
- [x] Valid order + wrong email returns no private order fields.
- [x] Missing order number is rejected safely.
- [x] Missing/invalid email is rejected safely.
- [x] Unknown order returns a generic verification failure.
- [x] Shopify/API failure produces a user-safe unavailable response.

## Main router

- [x] General Nike question routes to RAG.
- [x] Personal order/tracking request routes to Shopify when required fields are present.
- [x] Missing order/email fields trigger a local prompt rather than an unnecessary backend call.
- [x] Greeting-only input returns a local conversational response.
- [x] Website webhook receives and returns JSON successfully.

## Frontend integration

- [x] WordPress chatbot reaches the n8n webhook through HTTPS.
- [x] Verified order responses render as structured order information.
- [x] RAG responses render as normal assistant messages.
- [x] Failed verification does not render protected order details.
