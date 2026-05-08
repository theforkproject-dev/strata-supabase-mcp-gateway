# Strata Supabase MCP Gateway Tinfoil Config

Public verifier-facing Tinfoil config for the Strata Supabase MCP governance proxy pilot.

The gateway exposes a curated Strata MCP surface for Supabase actions and is intentionally configured with:

- `SUPABASE_PROJECT_REF=ghmfczkhbwfftvpsrghy`
- `SUPABASE_MCP_READ_ONLY=true`
- `SUPABASE_MCP_FEATURES=database,docs`
- `SUPABASE_ENABLE_UPSTREAM_CALLS=false` until the Supabase organization OAuth app is installed

Callback URL for the Supabase organization OAuth app:

```text
https://strata-supabase-mcp-gateway.amotivv.containers.tinfoil.dev/connectors/supabase/oauth/callback
```
