# Path: Developer

Goal: increase throughput with AI while preserving deterministic engineering quality.

## Recommended Sequence

1. Define constraints (accounts, signer model, compute budget, failure domains).
2. Use `/workflows/ship-feature.md` for implementation planning.
3. Use `/workflows/debug-transaction.md` for simulation and RPC-level diagnosis.
4. Run `/workflows/security-review.md` before PR/merge.

## Operating Pattern

- Treat AI output as draft design, not authority.
- Demand explicit invariants and state transition tables.
- Require tests for both success and adversarial cases.
- Prefer primary sources via MCP-backed docs.

## Merge Criteria

- Invariants documented
- Tests cover critical state transitions
- RPC/simulation errors mapped to concrete fixes
- Security checklist completed
