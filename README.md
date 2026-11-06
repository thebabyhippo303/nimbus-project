# The Nimbus Recompilation Project (TNRP)

**TNRP** (The Nimbus Recompilation Project, formerly The Nimbus Project) is a free fan project by Animorph Allocations.

Native ports of Dragon Ball Z: Budokai, Budokai 2 and Sagas (NTSC-U GameCube), Supersonic Warriors and Taiketsu (USA Game Boy Advance), and Tenkaichi Tag Team (USA PSP, ULUS10537) — six games in one launcher on Linux, Windows and Android, with online play and full 3-platform crossplay across 16 global server instances.

**Official website:** [nimbusrecomp.org](https://nimbusrecomp.org/)

This repository holds the finished release distros only. Grab them from [Releases](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases).

## Current version: Alpha 1.6 (Nov 6, 2026)

| Platform | File | SHA-256 |
|---|---|---|
| Linux x86_64 (Ubuntu 26.04) | [`Nimbus-Alpha-1.6-Linux-x86_64.run`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.6/Nimbus-Alpha-1.6-Linux-x86_64.run) | `1cd7414d4c091e77f4dfb6618144ecadcfb64b681623236f386d66e1bae01ab6` |
| Windows x64 (Windows 11, Vulkan or D3D12 GPU) | [`Nimbus-Alpha-1.6-Windows-x64.zip`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.6/Nimbus-Alpha-1.6-Windows-x64.zip) | `f0c5437f2a17dffc6d5c0dae0794cd0bb223c84bc630c1f7c9d9fb53b1a84bab` |
| Android arm64 (Android 13+) | [`Nimbus-Alpha-1.6-Android-arm64.apk`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.6/Nimbus-Alpha-1.6-Android-arm64.apk) | `7dfba5a6cc204029881218048feab7ca4ffc1f989adb0a8578cd3688a8dc62cd` |

Also mirrored on the CDN: [R2 builds/alpha-1.6](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-1.6/SHA256SUMS).

Check your download against `SHA256SUMS` (`sha256sum -c SHA256SUMS`). Release notes: [Alpha 1.6](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.6). HD texture packs (including Tenkaichi Tag Team, Taiketsu and Supersonic Warriors) are on the [website](https://nimbusrecomp.org/#downloads). Separate module downloads (host, renderer and game cores) are on the [website](https://nimbusrecomp.org/#modules).

Previous releases: [Alpha 1.5](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.5) (Nov 5, 2026) · [Alpha 1.4](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.4) (Nov 3, 2026) · [Alpha 1.3](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.3) (Nov 2, 2026) · [Alpha 1.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.2) (Nov 2, 2026) · [Alpha 1.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.1) (Nov 2, 2026) · [Alpha 1.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.0) (Nov 1, 2026).

You need your own NTSC-U discs, your own Supersonic Warriors (USA) and Taiketsu (USA) ROMs, and your own Tenkaichi Tag Team (USA, ULUS10537) ISO or CSO. The runtime components for all six games are bundled; no original disc images, ROMs or ISOs are included.

## What's new in Alpha 1.6

- **Dragon Ball Z: Budokai Tenkaichi Tag Team** (PSP, ULUS10537) joins as a native recompilation — the sixth game — with 1v1 and 4-player 2v2 Tag Team online & local multiplayer, Quick Match, live Classic ↔ Remastered toggle, up to 6× internal scale, cel/ink outlines, enhanced shadows, and HD texture packs (PC 4× / 3× / 2× + Android). 60 fps support and further refinements are coming soon.
- **Friends, Party & Voice Chat** built into the launcher, plus an **Android Touch Control Overhaul** across all six games.
- **16 global server instances + Online Lobby** across five regions (Americas, Europe, Middle East & Africa, Asia-Pacific).
- Full **3-platform crossplay** (Linux · Windows · Android).
- **Next up (Alpha 1.7):** Dragon Ball Z: Shin Budokai – Another Road.

## How TNRP works

TNRP runs on a hybrid core that sits between recompilation and decompilation. Each game has its own native core, running on a shared Nimbus host and renderer. There's no emulator and no interpreter emulating the hardware. Every game can be played in Original or Remastered mode. Detailed architecture notes will be posted on the website later.

## Source

The Nimbus Recompilation Project is closed source for now, while server hosting, networking and cross-platform compatibility get sorted out, and to keep development focused. Open source is planned, along with a mature toolset. Everything is free, and we don't take donations. Third-party licenses and notices are included inside each download.

Contact: TheNimbusProject@yahoo.com

Made with AI assistance.
