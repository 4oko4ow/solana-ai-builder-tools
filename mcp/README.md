# MCP Servers for Solana Development

MCP makes AI outputs more reliable by grounding agents in real tools/docs.

## Included

- `solana-official.mdx` — official Solana docs MCP
- `phantom-wallet.mdx` — Phantom wallet actions MCP
- `phantom-docs.mdx` — Phantom docs MCP endpoint

## Recommended Setup Order

1. Add Solana official docs MCP
2. Add Phantom docs MCP
3. Add Phantom wallet MCP only for workflows that require wallet actions

## Safety Rules

- Never expose private keys/secrets in prompts
- Use test wallets/devnet while iterating
- Treat all agent-generated actions as reviewable proposals first
