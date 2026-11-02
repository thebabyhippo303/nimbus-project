# The Nimbus Project

Native ports of Dragon Ball Z: Budokai, Budokai 2 and Sagas (NTSC-U GameCube), all in one launcher on Linux, Windows (Vulkan) and Android, with online play and crossplay.

**Website:** https://nimbus-project.pages.dev

This repository holds the finished release distros only. Grab them from [Releases](https://github.com/thebabyhippo303/nimbus-project/releases).

## Alpha 1.0 (Nov 1, 2026)

| Platform | File |
|---|---|
| Linux x86_64 (Ubuntu 26.04) | `Nimbus-Alpha-1.0-Linux-x86_64.run` |
| Windows x64 (Vulkan only) | `Nimbus-Alpha-1.0-Windows-x64.zip` |
| Android arm64 (Android 13+) | `Nimbus-Alpha-1.0-Android-arm64.apk` |

Check your download against `SHA256SUMS` (`sha256sum -c SHA256SUMS`).

You need your own NTSC-U discs. No original disc images are included.

## How it works

Nimbus runs on a hybrid core that sits between recompilation and decompilation. Each game has its own native core, running on a shared Nimbus host and renderer. There's no emulator and no interpreter emulating the hardware. Every game can be played in Original or Remastered mode. Detailed architecture notes will be posted on the website later.

## Source

The Nimbus Project is closed source for now, while server hosting, networking and cross-platform compatibility get sorted out, and to keep development focused. Open source is planned, along with a mature toolset. Third-party licenses and notices are included inside each download.

Made with AI assistance.
