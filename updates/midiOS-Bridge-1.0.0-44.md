<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# midiOS Bridge 1.0.0 (44)

- Adds full Bridge support for midiOS 2.6 Performance Control layouts,
  including profile-aware previews and shared layout compatibility.
- Improves connection lifecycle diagnostics and recovery visibility across USB,
  Wi-Fi, sleep, shutdown, and reconnect transitions.
- Hardens inbound MIDI validation and outbound connection handling to prevent
  malformed or stale messages from reaching active MIDI routes.
- Expands Ableton integration diagnostics and Marketplace package compatibility
  for the midiOS 2.6 release.
- Requires macOS 15.6 or later.
