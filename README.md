# Safety Replay Gate MCP

Replay safety evals before agent releases move forward.

Paid remote MCP for AI agent safety replay checks, policy gates, eval receipts, control-fix suggestions, and release evidence exports.

## Public Endpoints

- Website: https://safetyreplay.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://safetyreplay.clauxel.com/mcp
- Server card: https://safetyreplay.clauxel.com/server-card.json
- Registry name: `com.clauxel.safetyreplay/safetyreplay-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `run_safety_replay`
- `check_policy_gate`
- `record_eval_receipt`
- `suggest_control_fix`
- `export_release_evidence`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://safetyreplay.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://safetyreplay.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://safetyreplay.clauxel.com/server-card.json
- MCP endpoint: https://safetyreplay.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
