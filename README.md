# Kumix Studio — Downloads

[![Latest release](https://img.shields.io/github/v/release/kumixio/kumix-studio-downloader?label=latest)](https://github.com/kumixio/kumix-studio-downloader/releases/latest)

Kumix Studio is a set of lightweight desktop tools for video and audio, powered by bundled FFmpeg — **Generator**, **Loop**, **Compress** (including official YouTube Live targets), and **Extract Audio**. FFmpeg and FFprobe ship inside every build, so there is nothing else to install.

This repository hosts the official installers and update packages. The application source lives in a private repository.

## Download

Grab the file for your platform from the [latest release](https://github.com/kumixio/kumix-studio-downloader/releases/latest):

| Platform | File | Notes |
| --- | --- | --- |
| Windows | `Kumix-Studio-*-windows-x64-setup.exe` | Installer — recommended, auto-updates |
| Windows | `Kumix-Studio-*-windows-x64-portable.zip` | Extract **all** files into one folder, run `kumix-studio.exe` |
| macOS (Apple Silicon) | `Kumix-Studio-*-macos-arm64.dmg` | |
| macOS (Intel) | `Kumix-Studio-*-macos-x64.dmg` | |
| Linux | `Kumix-Studio-*-linux-amd64.AppImage` | `chmod +x` the file, then run it |
| Linux | `Kumix-Studio-*-linux-amd64.deb` | `sudo apt install ./Kumix-Studio-<version>-linux-amd64.deb` |

Files ending in `.sig` and the `latest.json` manifest are used by the built-in updater — no need to download them manually. The `*.app.tar.gz` files are macOS update packages; for a fresh install use the `.dmg`.

## Notes

- **macOS builds are not notarized.** On first launch, right-click the app and choose **Open** (or System Settings → Privacy & Security → Open Anyway).
- **Windows portable** requires the [Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/microsoft-edge/webview2/); the installer handles it automatically.
- **Updates** — installed builds check for updates on launch and install them from the Settings affordance in the header. The Windows portable build and the Linux `.deb` are updated manually by downloading a newer package.

## Links

- Website — [kumix.io](https://kumix.io)
- Issues — [issue tracker](https://github.com/kumixio/kumix-studio-downloader/issues)

© Kumix Labs
