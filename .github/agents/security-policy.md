---
name: Security Policy
description: >
  Outbound access and security constraints for all agents in the 40k_notes vault.
---

## Allowed Outbound Domains

All agents have outbound access to the following domains:

### Primary Data Sources
- `https://*.lexicanum.com/` — Warhammer 40K Lexicanum (primary source for lore)
- `https://warhammer40k.fandom.com/` — Warhammer 40K Wiki (secondary source)

## Agent Constraints

All agents (Leader, Reader, Reviewer) adhere to these outbound access rules and must not attempt to access domains outside of the allowed list above.
