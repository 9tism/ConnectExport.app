# ConnectExport

**A local macOS app that exports all of your own Garmin Connect data** —
activities as **FIT** files, health data as **JSON**. You operate it through a
local web interface launched from the macOS menu bar. Your data stays on your
own machine.

## Download & installation

Get the app from **[Releases](../../releases/latest)**:

1. Download `ConnectExport-<version>-macos-arm64.zip` and unpack it.
2. Drag `ConnectExport.app` into your **Applications** folder and launch it.

Built for Apple Silicon (arm64). The app is signed with a Developer ID
certificate and notarized by Apple, so it starts without a Gatekeeper warning —
no right-click → "Open" workaround needed.

## Usage

Double-click `ConnectExport.app`. A menu bar icon appears, a local server
starts, and your browser opens the interface automatically at
`http://127.0.0.1:8765`. If that port is taken, the app moves to a free one in
the range 8765–8775. Quit via the menu bar icon → "Quit".

In the interface: sign in to Garmin Connect, choose your export options and
follow the progress. Interface and menu bar follow your macOS system language
(German/English).

Your credentials are used locally only. If you tick "Stay signed in", the login
token is stored encrypted in the macOS keychain — your password itself is never
stored.

The export is incremental and resumable: it keeps a manifest, skips what it
already has and picks up where it left off. Depending on how much history your
account holds, the first run can take several hours, because requests are
throttled deliberately.

## License

© 2026 Tim Stegmann. All rights reserved.

ConnectExport is **proprietary software** — not open source. It is free to use
for private, non-commercial purposes; redistribution, modification, reverse
engineering and commercial exploitation are not permitted without written
consent. See the `LICENSE` file included with the download for the full terms
(German and English).

Bundled third-party libraries are covered by their own licenses; see
`THIRD-PARTY-NOTICES.md` in the download.

## Notes

This software has been tested but is still **beta**. No liability is accepted
for data loss or other damages — use at your own risk, and keep your own
backups.

Garmin offers no official public export API; the app uses the unofficial web
interface. It is intended solely for exporting **your own** account data and
throttles its requests conservatively. Use at your own risk with respect to
Garmin's terms of service.

"Garmin" and "Garmin Connect" are registered trademarks of Garmin Ltd. or its
subsidiaries. The FIT file format is also owned by Garmin Ltd. ConnectExport
and its author are not affiliated with Garmin.

---

Tim Stegmann · <studio@tim-stegmann.de>
