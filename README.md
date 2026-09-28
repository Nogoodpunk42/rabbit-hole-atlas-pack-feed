# Rabbit Hole Atlas public pack feed

This repository distributes the free base archive used by Rabbit Hole Atlas's in-app updater.

- `base-archive-update.json` is the small update catalog read by the Android app.
- `packs/` contains immutable, versioned base-archive ZIP files.
- The catalog pins each download by byte length and SHA-256 digest.

This feed intentionally contains no subscriber-only fuller-story packs, purchase data, credentials, or application source code. Premium story delivery belongs behind the app's authenticated subscription service.

The Android app keeps manual file import as an advanced recovery path, but ordinary users should only need **Packs → Get the full free archive** or **Check for archive update**.
