# Solana AI Builder Tools

Practical AI tooling for building on Solana.

This repo is organized for two audiences:
- **Vibecoders**: want to ship quickly with guided prompts and safe defaults.
- **Developers**: want deterministic workflows, stronger validation, and production rigor.

## Quick Navigation

- [Start Here](#start-here)
- [Choose Your Path](#choose-your-path)
- [Repository Layout](#repository-layout)
- [Quick Wins](#quick-wins)
- [Reference Docs](#reference-docs)
- [Contributing](#contributing)

## Start Here

1. Pick your path:
   - [Vibecoder Path](./pathways/vibecoder.md)
   - [Developer Path](./pathways/developer.md)
2. Connect MCP servers in [MCP docs](./mcp/README.md).
3. Run a workflow from [Workflows](./workflows/README.md).
4. Apply architecture/security checks before shipping.

## Choose Your Path

### Vibecoder

- Start here: [Vibecoder Path](./pathways/vibecoder.md)
- Build first feature: [Ship Feature Workflow](./workflows/ship-feature.md)
- Run risk pass: [Security Review Workflow](./workflows/security-review.md)

### Developer

- Start here: [Developer Path](./pathways/developer.md)
- Debug fast: [Debug Transaction Workflow](./workflows/debug-transaction.md)
- Enforce quality: [Security Review Workflow](./workflows/security-review.md)

## Repository Layout

- [pathways](./pathways) - role-based onboarding flows
- [workflows](./workflows) - reusable prompt + checklist workflows
- [mcp](./mcp) - Solana/Phantom MCP integration docs
- [skills](./skills) - skill patterns for Codex, Claude Code, Cursor, and agent workflows
- [architecture](./architecture) - Solana system design guidance
- [security](./security) - threat modeling and review checklists

## Quick Wins

- Ship a first feature: [workflows/ship-feature.md](./workflows/ship-feature.md)
- Debug failed transactions: [workflows/debug-transaction.md](./workflows/debug-transaction.md)
- Run pre-merge risk checks: [workflows/security-review.md](./workflows/security-review.md)

## Reference Docs

- Solana `LLMs.txt` (LLM-optimized docs corpus): [https://solana.com/llms.txt](https://solana.com/llms.txt)
- Solana official `SKILL.md`: [https://solana.com/SKILL.md](https://solana.com/SKILL.md)
- Local repository skill playbook: [SKILL.md](./SKILL.md)

## Contributing

Use [CONTRIBUTING.md](./CONTRIBUTING.md) to add new workflows, pathways, MCP docs, and quality checks in a consistent format.

## Contribution Standard

Each new item should include:
- What it solves
- Inputs required
- Output format
- Validation checklist
- Failure modes / caveats

AI can accelerate delivery, but correctness still comes from testable engineering decisions.
