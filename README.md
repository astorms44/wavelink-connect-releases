# Wavelink Connect — Releases

Signed, notarized installers for **Wavelink Connect**, the Mac app that links Macs for low-latency multichannel audio.

**[Download the latest release →](https://github.com/astorms44/wavelink-connect-releases/releases/latest)**

This repository distributes build artifacts only: each release's `.pkg` and the `manifest.json` that the app's software update reads. The Wavelink Connect source is not public.

## Requirements

- macOS 15 or later
- An administrator password (the installer sets up the scheduled-reboot helper)
- An audio device for the links, such as [Dante Virtual Soundcard](https://www.audinate.com/products/software/dante-virtual-soundcard)

## Installing

Open the `.pkg` and follow the installer. It places **Wavelink Connect.app** in `/Applications` and installs the helper for the optional scheduled reboot. After that, Settings ▸ Software Update keeps it current.
