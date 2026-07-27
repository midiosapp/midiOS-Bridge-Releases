<!-- sparkle-sign-warning:
IMPORTANT: This file was signed by Sparkle. Any modifications to this file requires updating signatures in appcasts that reference this file! This will involve re-running generate_appcast or sign_update.
-->
# midiOS Bridge 1.0.0 (43)

- Improves Bridge-to-iPhone reliability under sustained traffic by serializing
  outbound writes and applying backpressure.
- Cancels in-flight retry and pacing sleeps promptly when a connection closes or
  Bridge shuts down, preventing stale outbound work from continuing.
- Requires macOS 15.6 or later.
