# solana-dev Skill

End-to-end Solana development skill from Solana Foundation.

Repository: [https://github.com/solana-foundation/solana-dev-skill](https://github.com/solana-foundation/solana-dev-skill)
Official source (main branch): [https://github.com/solana-foundation/solana-dev-skill/tree/main](https://github.com/solana-foundation/solana-dev-skill/tree/main)

## Installation

### Quick install

```bash
npx skills add https://github.com/solana-foundation/solana-dev-skill
```

### Manual install

```bash
git clone https://github.com/solana-foundation/solana-dev-skill
cd solana-dev-skill
./install.sh
```

## Skill Structure

```text
skill/
├── SKILL.md                    # Main skill definition (required)
├── frontend-framework-kit.md   # UI patterns with framework-kit
├── kit-web3-interop.md         # Kit <-> web3.js boundary patterns
├── programs-anchor.md          # Anchor program development
├── programs-pinocchio.md       # Pinocchio (high-performance native)
├── testing.md                  # Testing (LiteSVM/Mollusk/Surfpool)
├── idl-codegen.md              # IDL and client generation
├── payments.md                 # Payments with Commerce Kit
├── security.md                 # Security vulnerabilities and prevention
└── resources.md                # Curated reference links
```
