# Halati Updates

This repository is the public update manifest used by Halati's in-app updater.

Current release:
- Version: 2.1.0
- Build: 2007
- APK: GitHub Release asset from `abw3laa/halati_app`
- Manifest: `update.json`

The Android client polls:

`https://raw.githubusercontent.com/abw3laa/halati_updates/main/update.json`

The manifest supports an optional SHA-256 checksum. Halati 2.1.0 will verify the checksum whenever the `sha256` field is populated.
