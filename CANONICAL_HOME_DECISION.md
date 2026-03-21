# Canonical Home Decision

## Decision

Canonical home: `persona-object-protocol`

## Why

- The POP repo already carries the LangChain integration tree.
- Protocol semantics belong with the persona layer, not with a standalone adapter package.
- Keeping two public surfaces is acceptable only if this repo is explicitly reduced to a wrapper role.

## Wrapper posture

- standalone install surface remains available
- README points users back to the POP repo
- future deprecation or archival remains open
