# Dotsquares AI — downloads

Installers for **Dotsquares AI**, a desktop GUI for Claude Code.

This repository only distributes the app. Every build is published under
[Releases](../../releases), and the download page is served from this repo's
`gh-pages` branch. The application source lives in a separate, private
repository.

## Install

Take the file for your platform from the
[latest release](../../releases/latest):

| Platform                | File                          |
| ----------------------- | ----------------------------- |
| macOS (Apple Silicon)   | `.dmg`                        |
| Windows                 | `-setup.exe`                  |
| Linux                   | `.AppImage`, `.deb` or `.rpm` |

There is no Intel macOS build — the app is built for Apple Silicon only.

After installing, the app updates itself: on every launch it checks
`latest.json` in the newest release here. The `.deb` and `.rpm` packages are
the exception, since the updater cannot drive a distro package manager —
update those the way you installed them.
