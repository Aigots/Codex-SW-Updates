# Codex SW

Codex SW is a Windows desktop switcher for Codex Desktop. It manages saved
official OAuth accounts and relay configurations, tests relay availability,
and applies reversible Provider Profile switches.

## Current Status

The public update repository is ready. No public binary release has been
published yet.

## Downloads

Stable installers and their SHA-256 checksums will be published here after
release validation. Codex SW also verifies the signed Stable update feed and
the downloaded package hash before an update can be applied.

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
