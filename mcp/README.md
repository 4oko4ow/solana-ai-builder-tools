# MCP Servers for Solana Development

This directory contains Model Context Protocol (MCP) servers 
relevant to Solana builders.

MCP servers allow AI agents to interact with structured tools, 
documentation, wallets, and other development layers 
in a reliable and deterministic way.

---

## Why MCP matters

Without MCP:
AI assistants rely on raw text and can hallucinate.

With MCP:
AI assistants access structured endpoints and verified sources.

This improves:
- Documentation accuracy
- Wallet interaction safety
- Development speed
- Agent-based workflows

---

## Categories

### Documentation MCP
Provides structured access to official documentation.

### Wallet MCP
Enables agent-based wallet operations such as:
- Signing transactions
- Managing addresses
- Executing swaps

### Tooling MCP
Allows interaction with development infrastructure 
(RPC, simulations, testing layers).

---

## Included Servers

- Solana Official MCP
- Phantom MCP (Wallet Actions)
- Phantom MCP (Docs Access)

---

## Notes

MCP increases capability but also increases responsibility.

Always:
- Verify generated code
- Use test wallets when possible
- Never expose private keys to AI prompts