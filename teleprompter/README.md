# Teleprompter updates

The Teleprompter Android app checks `version.json` in this folder when you tap **Check for update**.
If the version number is higher than what's installed, it downloads the files in `web/`, verifies their
SHA-256 checksums and switches to them — no reinstall needed.

- `version.json` — current update version, release notes, minimum app build required
- `web/index.html` — the app's interface
- `Teleprompter.apk` — latest full app (only needed when `minApp` goes up)
