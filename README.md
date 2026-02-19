# Solana AI Builder Tools

Practical AI tooling for building on Solana.

This repo is organized for two audiences:
- **Vibecoders**: want to ship quickly with guided prompts and safe defaults.
- **Developers**: want deterministic workflows, stronger validation, and production rigor.

## Start Here

1. Pick your path:
   - `/pathways/vibecoder.md`
   - `/pathways/developer.md`
2. Connect MCP servers in `/mcp`.
3. Run a workflow from `/workflows`.
4. Apply architecture/security checks before shipping.

## Repository Layout

- `/pathways` — role-based onboarding flows
- `/workflows` — reusable prompt+checklist workflows
- `/mcp` — Solana/Phantom MCP integration docs
- `/skills` — skill patterns for Codex/agent workflows
- `/architecture` — Solana system design guidance
- `/security` — threat modeling and review checklists

## Quick Wins

- Ship a first feature: `/workflows/ship-feature.md`
- Debug failed transactions: `/workflows/debug-transaction.md`
- Run pre-merge risk checks: `/workflows/security-review.md`

## Contribution Standard

Each new item should include:
- What it solves
- Inputs required
- Output format
- Validation checklist
- Failure modes / caveats

AI can accelerate delivery, but correctness still comes from testable engineering decisions.
