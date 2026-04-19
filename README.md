<h1 align="center">
  <a href="https://alluno.io"><img src="https://alluno.io/logo-dark.svg" alt="" width="32" height="32" style="vertical-align: middle;" /></a>&nbsp;Alluno
</h1>

<p align="center">
  <strong>All your devices in one.</strong><br/>
  Hardware-accelerated remote desktop built with Rust.
</p>

<p align="center">
  <a href="https://discord.gg/YkwJmwHCBR"><img src="https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://youtube.com/@alluno-io"><img src="https://img.shields.io/badge/YouTube-FF0000?logo=youtube&logoColor=white" alt="YouTube" /></a>
  <a href="https://x.com/alluno_io"><img src="https://img.shields.io/badge/X-000000?logo=x&logoColor=white" alt="X" /></a>
  <a href="https://instagram.com/alluno.io"><img src="https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="https://tiktok.com/@alluno.io"><img src="https://img.shields.io/badge/TikTok-000000?logo=tiktok&logoColor=white" alt="TikTok" /></a>
  <a href="https://twitch.tv/alluno_io"><img src="https://img.shields.io/badge/Twitch-9146FF?logo=twitch&logoColor=white" alt="Twitch" /></a>
  <a href="https://github.com/alluno-io/alluno/releases"><img src="https://img.shields.io/github/v/release/alluno-io/alluno?label=Download&color=brightgreen" alt="Latest Release" /></a>
</p>

<p align="center">
  <a href="https://github.com/alluno-io/alluno/releases">Download</a> &middot;
  <a href="https://alluno.io/getting-started">Docs</a>
</p>

---

## What is Alluno?

Alluno lets you access and control any of your devices from a browser with the performance of a native app. Built from the ground up in Rust, it uses hardware-accelerated capture and encoding to deliver ultra-low-latency streaming across Windows, macOS, and Linux.

No port forwarding. No complicated setup. Just install on host and connect from anywhere.

## See It in Action

### Productivity
> 3D modeling, video editing, design work, interact as if you're sitting in front of the machine.



https://github.com/user-attachments/assets/9fe86778-6206-41dc-aeef-182d90f7b325



### FPS Gaming
> Low-latency input and smooth, high frame rates tuned for fast-paced action.



https://github.com/user-attachments/assets/3004e1d5-0cb9-43be-ab45-421d43a34a9d



### Watch Party
> Invite friends and enjoy synced video playback together.



https://github.com/user-attachments/assets/c22e58f5-1199-4c45-8664-ff5c0896ea96




### RTS Games
> Crisp visuals and precise cursor control for careful micro.



https://github.com/user-attachments/assets/dc15c531-2dbc-4bae-8345-6da8cfaacd30


### Handheld Gaming
> Play your games from your phone, portable gaming anywhere.



https://github.com/user-attachments/assets/37e9466f-fba8-415c-8b6e-abe3c7720741



### Cross-Platform
> Windows, macOS, and Linux — access any host from any device.



https://github.com/user-attachments/assets/543d22fd-0389-4c21-b46c-bf22030896c4



### Couch Gaming
> Invite friends and enjoy trash talking on a couch competitive games.



https://github.com/user-attachments/assets/5adb55a1-615a-4cc9-b7cf-768178dfb2de





## Features

- **Hardware-Accelerated Encoding** — NVENC, Quick Sync, AMF, VAAPI, VideoToolbox
- **Zero-Copy Pipelines** — Windows Graphics Capture, ScreenCaptureKit, KMS/DRM + DMA-BUF
- **Ultra Low Latency** — WebRTC, QUIC/WebTransport coming soon
- **Cross-Platform** — Windows, macOS, and Linux host support
- **Browser Access** — Connect from any device with a modern browser
- **Full Input** — Keyboard, mouse, gamepad, and pen/tablet passthrough (pressure & tilt)
- **Multi-Codec** — H.264, H.265, AV1 with automatic negotiation
- **HDR & High Bit Depth** — 10-bit (P010) capture and encoding, YUV 4:4:4 for crisp text
- **Virtual Display** (Windows) — Bundled IddCx driver for headless hosts and custom resolutions
- **Encrypted** — All connections secured with DTLS/SRTP and QUIC
- **Auto Updates** — Built-in updater keeps your host app current

## Platform Support

| Platform | Capture | Hardware Encoding | Input |
|----------|---------|-------------------|-------|
| **Windows** | Windows Graphics Capture | NVENC, Quick Sync, AMF | Keyboard, Mouse, Gamepad |
| **Linux** | KMS/DRM + DMA-BUF (Wayland/X11) | VAAPI, NVENC | Keyboard, Mouse, Gamepad |
| **macOS** | ScreenCaptureKit | VideoToolbox | Keyboard, Mouse |

## Download

Get the latest version from [Releases](https://github.com/alluno-io/alluno/releases), or visit **[alluno.io](https://alluno.io/download)** to get started.

### Windows

| OS | Architecture | Download |
|---|---|---|
| Windows 10 (1809+) / Windows 11 | x86_64 | `.exe` (NSIS installer) |

- Tested up to 4K 120FPS
- [ViGEmBus](https://github.com/ViGEm/ViGEmBus/releases) required for gamepad support

### macOS

| OS | Architecture | Download |
|---|---|---|
| macOS 12.3 (Monterey) or later | Apple Silicon (arm64) | `.dmg` (macos-arm) |
| macOS 12.3 (Monterey) or later | Intel (x86_64) | `.dmg` (macos-intel) |

- Screen Recording permission required on first launch

### Linux

Requires glibc ≥ 2.35. Pick the package for your distro:

| Distro | Recommended | Install |
|---|---|---|
| Ubuntu 22.04+ / Mint / Pop!_OS / Zorin | `.deb` | `sudo apt install ./Alluno_*.deb` |
| Debian 12+ | `.deb` | `sudo apt install ./Alluno_*.deb` |
| Fedora 38+ / Nobara / Ultramarine | `.rpm` | `sudo dnf install ./Alluno-*.rpm` |
| RHEL 10 / Rocky 10 / AlmaLinux 10 | `.rpm` | `sudo dnf install ./Alluno-*.rpm` (CRB repo enabled by default) |
| Arch / Manjaro / EndeavourOS / CachyOS | AppImage | `chmod +x *.AppImage && ./Alluno_*.AppImage` |
| openSUSE Tumbleweed / Leap 15.5+ | AppImage | `chmod +x *.AppImage && ./Alluno_*.AppImage` |
| Bazzite / Fedora Atomic / other immutable | AppImage | `chmod +x *.AppImage && ./Alluno_*.AppImage` |

- FFmpeg libraries are bundled with all package formats
- PulseAudio or PipeWire required for audio
- X11 or Wayland session required

## Questions

For bugs, feature requests, or questions — open an [issue](https://github.com/alluno-io/alluno/issues) or ask in [Discord](https://discord.gg/YkwJmwHCBR).

## FFmpeg License

This application uses [FFmpeg](https://ffmpeg.org/) 8.1, licensed under LGPLv2.1. FFmpeg libraries are dynamically linked and may be replaced by the end user with a compatible version. See the [FFmpeg website](https://www.ffmpeg.org/) for source code and details.

## License

Copyright (c) 2025-2026 Alluno. All Rights Reserved. See [LICENSE](LICENSE.md) for details.
