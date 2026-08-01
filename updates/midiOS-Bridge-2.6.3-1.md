<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# midiOS Bridge 2.6.3 (1)

- Hardens Marketplace downloads with package identity, checksum, size,
  extraction, path traversal, and symlink validation.
- Keeps Layout Library identity stable across reloads and renames, normalizes
  imported layout names, and protects Marketplace-installed layouts from
  accidental overwrite.
- Preserves complete Marketplace compatibility and installation metadata and
  verifies the deployed Marketplace database schema before loading catalog
  content.
- Adds versioned layout transfer compatibility between midiOS and Bridge while
  continuing to accept existing version 1 layouts.
- Retains authenticated pairing, USB/Wi-Fi reconnect behavior, MIDI timing,
  exact note-off ownership, and the existing Ableton Integration package.
- Requires macOS 15.6 or later.
