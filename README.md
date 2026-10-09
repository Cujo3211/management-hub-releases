# Management Hub Windows releases

This repository contains Windows binaries and update metadata only. Application source remains private.

Use **Management Hub Setup.exe** for the normal per-user installation. Portable builds do not install automatic updates. Current internal builds are unsigned; Windows may display “Unknown publisher”.

The stable application checks `releases/latest/download/latest.yml` without credentials. A release is published only after the private Windows workflow passes source checks, unit/integration tests, Electron tests, installer/portable validation, actual upgrade/restore checks and a real updater test.
