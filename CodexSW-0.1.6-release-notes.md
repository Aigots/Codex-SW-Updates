# Codex SW 0.1.6

- Saves the standard or HTTP transport preference independently for each official account.
- Preserves the observed HTTP preference when upgrading legacy official account records.
- Uses `openai` and `chatgpt_http` as distinct effective Provider identities so cross-transport switches retain required session synchronization.
- Protects the official account Profile catalog with concurrent-change detection and byte-exact rollback.
- Reports same-Provider switches accurately without claiming that session synchronization ran.
