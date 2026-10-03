# AI Business V1 — Commercial Project Watch

A minimal first-sale system for a $25 research product.

## Goal
Sell one verified, filtered Oklahoma City commercial-project research report to a sign company.

## Workflow
Prospect -> AI-assisted discovery call -> research -> human verification -> $25 checkout -> deliver report -> revenue ledger.

## Important
- Do not put API keys in source code.
- The caller must truthfully identify itself as an AI assistant.
- No payment is taken automatically until the merchant/payment account is configured and authorized by the owner.
- This starter does not place phone calls yet; it provides the business logic and configuration needed for the telephony layer.

## Suggested stack
- Voice: OpenAI Realtime/GPT-Live
- Telephony: SIP/Twilio/Telnyx-compatible layer
- Backend: Node.js/Express
- Payments: Stripe Checkout + Cash App Pay where eligible
- Data: SQLite initially; upgrade only after the first repeat buyer

## First test
Price: $25
Deliverable: a short list of newly filed OKC commercial projects with source evidence, relevance rationale, and fact/inference separation.
