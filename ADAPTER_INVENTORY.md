# Adapter Inventory

## Repo role

Standalone LangChain adapter package for POP persona objects.

## Current retained surfaces

- package code under `src/langchain_pop/`
- examples under `examples/`
- tests under `tests/`
- docs drafts under `docs/`

## Duplicate surface audit

- equivalent adapter tree exists in `persona-object-protocol/integrations/langchain-pop`
- equivalent POP integration surface also exists in `persona-object-protocol/src/pop/integrations/langchain`

## Boundary decision

Keep this repo as a deprecated standalone wrapper for packaging continuity while treating the parent POP repo as canonical.
