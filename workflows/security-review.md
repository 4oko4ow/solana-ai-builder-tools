# Workflow: Security Review

## Inputs

- PR diff / changed files
- Program instruction list
- Privileged roles and signer model

## Prompt Template

```text
Perform a Solana-focused security review of these changes.

Scope:
<files or summary>

Output exactly:
1) Critical findings (with exploit path)
2) High/medium findings
3) Missing tests and why they matter
4) Suggested fixes
5) Residual risks after fixes
```

## Review Focus

- Authorization and signer validation
- Account ownership checks
- Replay/idempotency concerns
- Integer/precision handling
- CPI trust boundaries
- Upgrade authority and admin controls

## Exit Criteria

- No unresolved critical findings
- High-risk findings either fixed or explicitly accepted
- Security-relevant tests added
