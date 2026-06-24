# Company Data Security

## Principle
Do not automatically store raw company emails, contracts, legal memos, API keys, customer data, or confidential financial data.

## Safer Pattern
- Store short summaries only.
- Mark source and confidence.
- Require Jay approval for sensitive memory.
- Keep API keys out of memory files.
- Never store raw credentials.

## Sensitivity Rules
- Public news: low
- Business strategy summary: medium
- Legal memo summary: high
- Contract original text: do not store
- API key or password: never store
