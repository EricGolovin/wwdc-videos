# WWDC Video Downloader

This repository contains a curated list of Apple WWDC session video links along with scripts to help you download them efficiently using [`yt-dlp`](https://github.com/yt-dlp/yt-dlp) and [`aria2`](https://github.com/aria2/aria2).

## Contents

- ✅ WWDC 2025 video session list
- ✅ High-speed batch download script
- ✅ Format-optimized commands (4K video, English audio, no audio descriptions)

## Overview

- 📁 `scripts/` — Contains executable scripts for downloading videos in bulk (e.g. `wwdc2025.sh`)
- 📁 `list/` — Contains plain-text or markdown-formatted lists of available WWDC session video links

## Before You Begin

Ensure you have the following installed:

- `yt-dlp`
- `aria2c`

To install on macOS via Homebrew:

```sh
brew install yt-dlp aria2
```

## Usage

Run the full download script for WWDC 2025 sessions:

```sh
chmod +x scripts/wwdc2025.sh
./scripts/wwdc2025.sh
```

This script downloads all listed WWDC 2025 videos in the best available quality (4K HEVC video + stereo AAC audio) using multiple connections for faster performance.

## Custom Downloads

Each video has its own individual `yt-dlp` command.

You can:
- Manually run the specific command for a session
- Copy-paste from `scripts/wwdc2025.sh`
- Build your own custom script based on the entries in `list/`

## License

This repository is maintained by [@EricGolovin](https://github.com/EricGolovin).  
All video content referenced belongs to Apple Inc.

> ⚠️ This repository does not host or redistribute any video files. It only provides publicly accessible URLs and automation scripts for educational and archival purposes.
