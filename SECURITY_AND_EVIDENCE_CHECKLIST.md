# Security and evidence checklist

## Never publish

- API tokens, bearer headers, webhook secrets, passwords, OAuth refresh tokens, session cookies, private credentials or `.env` files.
- Customer names, phone numbers, emails, chats, billing details, card data or private incident records.
- Employer-owned workflow exports or internal documents without authorization.

## Before publishing a workflow export

1. Work from a copy using synthetic test data.
2. Inspect node parameters, headers, URLs, credential references, pinned data, notes and logs.
3. Remove secrets and replace sensitive identifiers with placeholders.
4. Confirm externally visible URLs contain no private endpoints.
5. Document requirements, setup steps and one successful and one failure-handling test.
6. Describe status accurately: proposal, prototype, tested workflow or deployed workflow.
7. Sanitize screenshots and exports.

## Strong portfolio evidence

A secret-free workflow diagram or export, synthetic input/output examples, clear README, reproducible tests and brief demo.
