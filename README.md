# Codex SW

Codex SW is a Windows desktop switcher for Codex Desktop. It manages saved
official OAuth accounts and relay configurations, tests relay availability,
and applies reversible Provider Profile switches.

## Current Status

Codex SW `0.1.6` is the current Stable release.

## Downloads

- [Download Codex SW 0.1.6 Setup](https://github.com/Aigots/Codex-SW-Updates/releases/download/v0.1.6/CodexSW-stable-Setup.exe)
- [View the v0.1.6 release](https://github.com/Aigots/Codex-SW-Updates/releases/tag/v0.1.6)

Setup SHA-256:

```text
E6F484B159C9F7EBB6F6CB7C30E13262C950854EA5EDC87729944C7CCCD46977
```

Codex SW also verifies the signed Stable update feed and the downloaded package
hash before an update can be applied.

## Updates

Use **Check for updates** in Codex SW to query the Stable feed. When a new
version is available, the app shows its version and release notes before any
download. Installation requires explicit confirmation and is not performed
silently at startup.

## Privacy

Codex SW operates locally. It does not upload Codex configuration, OAuth
tokens, API keys, cookies, task content, or session databases to the update
service.

## Windows Warning

Installers without Windows Authenticode signing can show a SmartScreen
warning. The updater's Ed25519 signature is a separate feed and package
integrity check; it is not a Microsoft publisher certificate.

## Support

When reporting an issue, include the Codex SW version and visible error text.
Do not include credentials, OAuth data, task content, or complete configuration
files.
