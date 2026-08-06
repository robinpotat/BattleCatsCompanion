# Battle Cats Companion

Portable desktop companion for Battle Cats (save viewer, upgrades, combos, orbs, seed tracker).

## What's here

- `BattleCatsCompanion.zip` — the portable app (install by extracting and running `Setup.bat`).
- `version.json` — update manifest consumed by the app's built-in updater.

## How updates work

The app checks `version.json` and, when a newer version is published, downloads the new zip,
extracts it over its own folder, and preserves your save database and settings.

To publish an update: bump `cats_app/version.txt`, upload the new zip here, and update
`version.json` (keep the zip under GitHub's 100 MB file limit).
