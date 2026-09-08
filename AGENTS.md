# AxisFI documentation instructions

## Project

- This is the Mintlify site for the AxisFI public API.
- Configuration lives in `docs.json`.
- Versioned OpenAPI specifications live in `openapi/`.
- Run `mint validate` and `mint broken-links` before publishing.

## Terminology and style

- Write the product name as `AxisFI`.
- Use active voice and address the reader as "you".
- Keep headings in sentence case.
- Format field names, paths, headers, and commands as code.
- Use `recipient` for the party receiving a payout.
- Use `source amount` for the total amount deducted and `target amount` for the net amount received.

## Content boundaries

- Document public Gateway APIs only.
- Do not include internal admin operations, credentials, private addresses, or production secrets.
- Keep examples aligned with the API version that contains them.
