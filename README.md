# Skynthesis releases

Disk images and the update feed for **Skynthesis**, the Serum 2 skin editor
for macOS. Nothing else lives here.

- Each release carries `Skynthesis-<version>.dmg` (notarized, stapled) and
  `latest.json`, the feed the app reads from the release tagged *latest*.
- The app checks the feed from its own menu ("Check for Updates…") and, when
  the checkbox is on, once a day.
- The DMG's SHA-256 is in `latest.json`; the app verifies it before installing.
