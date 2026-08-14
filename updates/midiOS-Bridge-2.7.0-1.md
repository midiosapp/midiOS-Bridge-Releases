<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# midiOS Bridge 2.7.0 (1)

- Adds the Bridge-managed Offline Instrument library and authenticated transfer
  of instrument assignments, sampler assets, and canonical instrument packages
  from midiOS.
- Introduces the canonical Marketplace Instrument Package format with validated
  authoring, distribution, installation, receipts, recovery, and compatibility
  handling for existing layouts and packages.
- Adds stable ecosystem installation identity and generation-aware projection
  storage so reconnects and replacement transfers cannot publish stale
  instrument state.
- Hardens CoreMIDI feedback delivery by copying immutable events at ingress and
  delivering ordered batches on the main actor.
- Reduces Bridge transport, framing, and diagnostic overhead while preserving
  immediate MIDI delivery, authenticated pairing, reconnect behavior, exact
  note-off ownership, and the existing Ableton Integration package.
- Requires macOS 15.6 or later.
