<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# midiOS Bridge 2.6.2 (1)

- Keeps all notes in a played chord aligned by disabling delayed small-write
  coalescing on the live midiOS performance connection.
- Preserves authenticated pairing, USB/Wi-Fi reconnect behavior, bounded
  outbound writes, and exact MIDI note-off ownership.
- Retains compatibility with existing layouts, the Ableton Integration
  package, and earlier midiOS Bridge update feeds.
- Requires macOS 15.6 or later.
