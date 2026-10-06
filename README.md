# NEOS — Downloads & Feedback

**NEOS is closed source, and this repository is not the application.** It is the public
hub for its downloads, release notes and issue tracker.

If you got here through a release's **“Source code (zip / tar.gz)”** link: those two
archives are attached automatically by GitHub to every release, they are archives of
*this* repository, and they contain nothing but the file you are reading. There is no
way to remove them from a release, so this note is the next best thing. The application
source lives in a private repository.

NEOS is a native macOS network workbench: SSH terminals & tunnels, FortiGate / UniFi /
MikroTik management, network tools, Wi‑Fi survey, packet capture & analysis, remote
desktop, and more.

## Download
Get the latest `.dmg` from the [**Releases**](../../releases/latest) page.
Requires a Mac with **Apple silicon** and **macOS 15 (Sequoia)** or later. Builds are
signed and notarized, so they open without a Gatekeeper warning.

## Report a bug / request a feature
Open an [**issue**](../../issues/new). In the app, *Help → Feedback / Report a Problem…*
(in German: *Feedback / Fehler melden …*) files here with your version pre-filled.

## Updates
When it starts, NEOS looks here for a new release. If there is one, it downloads it in
the background and checks it before offering it: the signature must be intact and the
NEOS developer's, and the app inside must be the version the release announces.
Installing then takes one click — NEOS never restarts behind your back. Both the check
and the download can be switched off under *NEOS → Check for Updates…*.
