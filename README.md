# Alluno — All Your Devices in One

This repository contains the official installers and update files for [**Alluno**](https://alluno.io).

## About

Alluno is a high-performance, hardware-accelerated remote desktop platform built with Rust.

### Platform Support (v0.5.1)

| Platform | Capture | Hardware Encoding | Input |
|----------|---------|-------------------|-------|
| **Windows** | DXGI Desktop Duplication | NVENC, Quick Sync, AMF | Keyboard, Mouse, Gamepad |
| **Linux** | PipeWire + DMA-BUF (Wayland/X11) | VAAPI, NVENC | Keyboard, Mouse, Gamepad |
| **macOS** | ScreenCaptureKit | VideoToolbox | Keyboard, Mouse |

## Downloads

Find the latest installers in the [Releases](https://github.com/alluno-io/alluno/releases) section.

- **Windows**: `.msi` and `.exe` installers
- **Linux**: `.deb` and `.AppImage` packages
- **macOS**: `.dmg` installer

## Updates

The app includes an automatic updater that fetches new versions from this repository's Releases page.

## FFmpeg License Information

This application uses [FFmpeg](https://ffmpeg.org/) 8.0.1, which is licensed under the LGPLv2.1.

FFmpeg is a free software project that provides tools for handling multimedia data. You can find the source code at the [FFmpeg Official Website](https://www.ffmpeg.org/).

The FFmpeg libraries used in this application are dynamically linked, and users may replace them with a different compatible version if desired.

If you need a copy of the source code for FFmpeg or have any questions about it, feel free to visit the FFmpeg repository. 

The FFmpeg DLL used in this application is dynamically linked, and users may replace it with a different version if desired.
