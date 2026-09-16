# Codex SW Changelog

## 0.1.6 - 2026-09-16

- Published the first Stable Codex SW installer.
- Added independent per-account standard or HTTP transport preferences for
  official accounts.
- Preserved legacy official-account HTTP preferences during catalog upgrades.
- Kept `openai` and `chatgpt_http` as distinct effective Provider identities so
  required cross-transport session synchronization is retained.
- Added concurrent-change detection and byte-exact rollback for the official
  account Profile catalog.
- Added a signed Stable update feed with explicit user-confirmed installation.
