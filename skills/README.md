# Skills

This section defines patterns for agent skills used in Solana development workflows.

## What belongs here

- Skill blueprints (what task, inputs, outputs, constraints)
- Example prompts/tools for repeatable workflows
- Integration notes for Codex, Claude Code, Cursor, and other agent environments
- Upstream references:
  - Solana `LLMs.txt`: https://solana.com/llms.txt
  - Solana `SKILL.md`: https://solana.com/SKILL.md

## Suggested skill modules

- `anchor-scaffold` — bootstrap a new Anchor instruction/test skeleton
- `solana-rpc-debugger` — parse and classify transaction failures
- `idl-auditor` — check account/instruction compatibility risks
- `wallet-integration-checker` — verify Phantom/Solana wallet flow correctness

Keep each skill small, deterministic, and testable.
