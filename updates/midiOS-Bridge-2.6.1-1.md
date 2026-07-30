<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# midiOS Bridge 2.6.1 (1)

- Aligns the Bridge version with midiOS 2.6.1.
- Adds explicit, authenticated one-to-one pairing with the intended midiOS
  iPhone, including visible Add Device, Switch Device, and Forget Device
  controls.
- Preserves the paired connection through normal app suspension, foreground
  return, USB/Wi-Fi transitions, and Bridge reconnects without silently
  selecting a different phone.
- Hardens Performance Control delivery with bounded controller backpressure,
  transport-aware replay, and safer reconnect behavior.
- Recognizes the Music Professor Performance Mode and Secondary Pathways in
  transferred layout previews.
- Retains compatibility with older midiOS layouts and the existing Ableton
  Integration package.
- Requires macOS 15.6 or later.
