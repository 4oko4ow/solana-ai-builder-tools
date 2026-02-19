# Workflow: Debug Transaction Failure

## Inputs

- Transaction signature (or simulated instruction set)
- RPC error/logs
- Expected behavior

## Prompt Template

```text
Analyze this Solana transaction failure and provide deterministic debugging steps.

Expected behavior:
<expected>

Observed error/logs:
<paste logs>

Output exactly:
1) Most likely root causes ranked
2) Log lines that support each cause
3) Next 5 debugging commands/checks
4) Minimal fix options with tradeoffs
5) Regression test to prevent recurrence
```

## Debug Checklist

- Validate account order and mutability
- Validate signer set
- Check PDA derivations/seeds/bump
- Confirm program IDs and network alignment
- Re-run simulation after each fix
