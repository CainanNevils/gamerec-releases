# gamerec

A lightweight game recorder for Windows 10/11: records your screen or a game
with game audio and your microphone on separate tracks, using the graphics
card's video encoder so games keep their frame rate.

## Install

1. Go to **[Releases → latest](https://github.com/CainanNevils/gamerec-releases/releases/latest)**
   and download `gamerec-<version>-win64.zip`.
2. Unzip it and double-click **`Install.cmd`**.
   Windows may show "Windows protected your PC" because the app isn't
   code-signed: click **More info → Run anyway** (first install only).
3. gamerec opens and adds Desktop and Start Menu shortcuts. No admin rights needed.

Press **Ctrl+Alt+R** anywhere, even in a game, to start and stop recording.
Recordings go to `Videos\gamerec`.

## Updates

Automatic. gamerec downloads new versions in the background and installs them
by itself the next time it starts (or right away while it's idle in the tray).
Never during a recording.

## Uninstall

Settings → Apps → gamerec → Uninstall. Your recordings and settings are kept.
