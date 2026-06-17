# Eyrest — Downloads

**Eyrest** is an evidence-based eye-break reminder that lives in your menu bar /
system tray. Every so often it gently takes over the screen and asks you to
**look far away** — out a window if you can — because resting your eyes means
looking *off* the screen, into the distance, not at it. Based on the widely
recommended 20-20-20 idea (general wellbeing guidance, not medical advice).

This repo hosts the **installers** only. (The source code lives elsewhere.)

## Download

Get the latest build for your OS from **[Releases »](../../releases/latest)**.

| OS | File |
|----|------|
| macOS (Apple Silicon) | `Eyrest-<version>-mac-<arch>.dmg` |
| Windows | `Eyrest-<version>-win-<arch>.exe` |
| Linux | `Eyrest-<version>-linux-<arch>.AppImage` or `.deb` |

## Install

The app isn't signed with a paid developer certificate, so each OS shows a
one-time "unverified developer" prompt. Here's how to get past it.

### macOS
1. Open the `.dmg` and drag **Eyrest** into **Applications**.
2. First launch: **right-click (Control-click) Eyrest → Open → Open**.
   (Double-clicking shows a dead-end "can't be opened" dialog; right-click → Open gives you the Open button.)
3. Eyrest lives in the **menu bar** (top-right). There's no Dock icon — that's intentional.

### Windows
1. Run the `.exe`. If SmartScreen warns, click **More info → Run anyway**.
2. Eyrest sits in the **system tray** (bottom-right; check the "show hidden icons" chevron).

### Linux
- **AppImage:** `chmod +x Eyrest-*.AppImage`, then run it.
- **Debian/Ubuntu:** `sudo apt install ./Eyrest-*.deb`.

## Using it

Click the tray icon for the menu — **Take a break now**, **Pause**, **Settings…**.
The icon itself fills like a clock toward your next break; on a break it shows an
eye, and a pause glyph when paused.
