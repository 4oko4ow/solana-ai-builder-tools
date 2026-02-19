# Workflow: Ship Feature

## Inputs

- Feature goal
- User action flow
- Programs/accounts touched
- Network target (localnet/devnet/mainnet)

## Prompt Template

```text
You are assisting with a Solana feature implementation.

Feature:
<describe feature>

Constraints:
- Network: <network>
- Program(s): <programs>
- Wallet UX: <wallet constraints>
- Non-goals: <what we are not building>

Output exactly:
1) Minimal architecture (components and account model)
2) Step-by-step implementation plan
3) Test plan (happy path + failure paths)
4) Risks/unknowns
5) Definition of done
```

## Validation Checklist

- Account ownership and signer requirements are explicit
- Error handling covers insufficient funds, invalid accounts, stale state
- Compute/size assumptions are stated
- Test plan includes failure scenarios
