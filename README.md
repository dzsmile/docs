# AxisFI API documentation

This repository contains the Mintlify documentation for the AxisFI public API.

## Local preview

```powershell
npm install -g mint
mint dev
```

Open `http://localhost:3000` after the development server starts.

## Validate

```powershell
mint validate
mint broken-links
```

## Refresh OpenAPI specifications

Start `axisfi-gateway` on port `8083`, open these URLs in a browser, and save the responses to the matching files under `openapi/`:

- `http://127.0.0.1:8083/v3/api-docs/2024-12-01`
- `http://127.0.0.1:8083/v3/api-docs/2026-08-31`
