# The Nimbus Recompilation Project (TNRP)

**TNRP** (The Nimbus Recompilation Project, formerly The Nimbus Project) is a free fan project by Animorph Allocations.

Native ports of Dragon Ball Z: Budokai, Budokai 2 and Sagas (NTSC-U GameCube), plus Supersonic Warriors and Taiketsu (USA Game Boy Advance), all in one launcher on Linux, Windows and Android, with online play and crossplay.

**Official website:** [nimbus-recompilation-project.pages.dev](https://nimbus-recompilation-project.pages.dev/)

This repository holds the finished release distros only. Grab them from [Releases](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases).

## Current version: Alpha 1.5 (Nov 5, 2026)

| Platform | File |
|---|---|
| Linux x86_64 (Ubuntu 26.04) | [`Nimbus-Alpha-1.5-Linux-x86_64.run`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.5/Nimbus-Alpha-1.5-Linux-x86_64.run) |
| Windows x64 (Windows 11, Vulkan or D3D12 GPU) | [`Nimbus-Alpha-1.5-Windows-x64.zip`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.5/Nimbus-Alpha-1.5-Windows-x64.zip) |
| Android arm64 (Android 13+) | [`Nimbus-Alpha-1.5-Android-arm64.apk`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.5/Nimbus-Alpha-1.5-Android-arm64.apk) |

Check your download against `SHA256SUMS` (`sha256sum -c SHA256SUMS`). Release notes: [Alpha 1.5](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.5). HD texture packs (including Taiketsu and Supersonic Warriors) are on the [website](https://nimbus-recompilation-project.pages.dev/#downloads). Separate module downloads (host, renderer and game cores) are on the [website](https://nimbus-recompilation-project.pages.dev/#modules).

Previous releases: [Alpha 1.4](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.4) (Nov 3, 2026) · [Alpha 1.3](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.3) (Nov 2, 2026) · [Alpha 1.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.2) (Nov 2, 2026) · [Alpha 1.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.1) (Nov 2, 2026) · [Alpha 1.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.0) (Nov 1, 2026).

You need your own NTSC-U discs and your own Supersonic Warriors (USA) and Taiketsu (USA) ROMs. The runtime components for all five games are bundled; no original disc images or ROMs are included.

## How TNRP works

TNRP runs on a hybrid core that sits between recompilation and decompilation. Each game has its own native core, running on a shared Nimbus host and renderer. There's no emulator and no interpreter emulating the hardware. Every game can be played in Original or Remastered mode. Detailed architecture notes will be posted on the website later.

## Source

The Nimbus Recompilation Project is closed source for now, while server hosting, networking and cross-platform compatibility get sorted out, and to keep development focused. Open source is planned, along with a mature toolset. Everything is free, and we don't take donations. Third-party licenses and notices are included inside each download.

Contact: TheNimbusProject@yahoo.com

Made with AI assistance.
