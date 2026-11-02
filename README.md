# The Nimbus Project

Native ports of Dragon Ball Z: Budokai, Budokai 2 and Sagas (NTSC-U GameCube), all in one launcher on Linux, Windows (Vulkan) and Android, with online play and crossplay.

**Website:** https://nimbus-project.pages.dev

This repository holds the finished release distros only. Grab them from [Releases](https://github.com/thebabyhippo303/nimbus-project/releases).

## Current version: Alpha 1.3 (Nov 2, 2026)

| Platform | File |
|---|---|
| Linux x86_64 (Ubuntu 26.04) | [`Nimbus-Alpha-1.3-Linux-x86_64.run`](https://github.com/thebabyhippo303/nimbus-project/releases/download/alpha-1.3/Nimbus-Alpha-1.3-Linux-x86_64.run) |
| Windows x64 (Windows 11, AVX2, Vulkan only) | [`Nimbus-Alpha-1.3-Windows-x64.zip`](https://github.com/thebabyhippo303/nimbus-project/releases/download/alpha-1.3/Nimbus-Alpha-1.3-Windows-x64.zip) |
| Android arm64 (Android 13+) | [`Nimbus-Alpha-1.3-Android-arm64.apk`](https://github.com/thebabyhippo303/nimbus-project/releases/download/alpha-1.3/Nimbus-Alpha-1.3-Android-arm64.apk) |

Check your download against `SHA256SUMS` (`sha256sum -c SHA256SUMS`). Release notes: [Alpha 1.3](https://github.com/thebabyhippo303/nimbus-project/releases/tag/alpha-1.3). Separate module downloads (host, renderer and game cores) are on the [website](https://nimbus-project.pages.dev/#modules).

Previous releases: [Alpha 1.2](https://github.com/thebabyhippo303/nimbus-project/releases/tag/alpha-1.2) (Nov 2, 2026) · [Alpha 1.1](https://github.com/thebabyhippo303/nimbus-project/releases/tag/alpha-1.1) (Nov 2, 2026) · [Alpha 1.0](https://github.com/thebabyhippo303/nimbus-project/releases/tag/alpha-1.0) (Nov 1, 2026).

You need your own NTSC-U discs. The three games' runtime components are bundled; no original disc images are included.

## How it works

Nimbus runs on a hybrid core that sits between recompilation and decompilation. Each game has its own native core, running on a shared Nimbus host and renderer. There's no emulator and no interpreter emulating the hardware. Every game can be played in Original or Remastered mode. Detailed architecture notes will be posted on the website later.

## Source

The Nimbus Project is closed source for now, while server hosting, networking and cross-platform compatibility get sorted out, and to keep development focused. Open source is planned, along with a mature toolset. Everything is free, and we don't take donations. Third-party licenses and notices are included inside each download.

Contact: TheNimbusProject@yahoo.com

Made with AI assistance.
