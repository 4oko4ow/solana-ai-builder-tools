# Path: Vibecoder

Goal: ship useful Solana features quickly without skipping safety-critical checks.

## Workflow

1. Start from `/workflows/ship-feature.md`.
2. Keep scope tiny (one user action + one on-chain flow).
3. Use MCP docs to reduce hallucinations:
   - Solana docs MCP
   - Phantom docs MCP
4. Before merge, run `/workflows/security-review.md`.

## Guardrails

- Never paste private keys into prompts.
- Prefer devnet/test wallets while iterating.
- Ask AI for assumptions and edge cases explicitly.
- Require a final "unknowns" section in every AI output.

## Definition of Done

- Happy path works on devnet
- At least one failure path tested
- Risks and assumptions are documented
