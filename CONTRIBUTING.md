# Contributing

This repository is for practical AI-assisted Solana development.

Contributions should make the repo more useful for both:
- Vibecoders (fast path with guardrails)
- Developers (deterministic, testable, production-grade path)

## What to Contribute

Good contributions include:
- New workflows in `/workflows`
- Better onboarding paths in `/pathways`
- MCP integration docs in `/mcp`
- Architecture guidance in `/architecture`
- Security checklists in `/security`
- Skill patterns in `/skills`

## Contribution Rules

Every new doc should include:
- Problem it solves
- Required inputs
- Output format
- Validation checklist
- Failure modes / caveats

Keep content:
- Concrete and execution-focused
- Solana-specific where possible
- Safe by default (no secret handling anti-patterns)

## File Templates

## 1) Workflow Template (`/workflows/*.md`)

````md
# Workflow: <Name>

## Inputs

- <input 1>
- <input 2>

## Prompt Template

```text
<copy/paste prompt with explicit output sections>
```

## Validation Checklist

- <check 1>
- <check 2>

## Failure Modes / Caveats

- <risk 1>
- <risk 2>
````

## 2) Pathway Template (`/pathways/*.md`)

```md
# Path: <Audience>

Goal: <one sentence>

## Workflow

1. <step>
2. <step>

## Guardrails

- <rule>
- <rule>

## Definition of Done

- <outcome>
- <outcome>
```

## 3) MCP Doc Template (`/mcp/*.mdx`)

````md
# <MCP Name>

## What it is

<short description>

## Why it matters

- <benefit>
- <benefit>

## Setup

```json
<config example>
```

## Safety Notes

- Never expose private keys/secrets
- Prefer devnet/test wallets during iteration
````

## Pull Request Checklist

Before opening a PR:
- [ ] Content follows repository structure and naming
- [ ] Instructions are copy/paste usable
- [ ] Solana assumptions are explicit (network, signer model, accounts)
- [ ] Security implications are called out
- [ ] Failure cases are documented
- [ ] Existing docs are linked where relevant (avoid duplication)

## PR Quality Bar

A contribution is merge-ready when:
- It improves execution speed without reducing safety
- A user can run it with minimal interpretation
- It is specific enough to reduce hallucinations and ambiguity

## Style Guide

- Prefer short sections and explicit bullets
- Use deterministic language ("do X", "output Y")
- Avoid vague advice without actionable steps
- Keep examples realistic and Solana-relevant

## Local Validation

For doc-only changes:
- Verify paths and filenames exist
- Verify code blocks render correctly
- Verify internal links are valid

## Licensing

By contributing, you agree your changes are provided under this repository's license.
