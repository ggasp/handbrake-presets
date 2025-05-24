# Handbrake Preset for Miyoo Mini Plus

A HandBrake preset optimized for converting videos to be watched on the Miyoo Mini Plus handheld console.

## Features

- **Optimized for 640x480 displays**: Perfect for the Miyoo Mini Plus screen resolution
- **Minimal file size**: Efficient compression while maintaining visual quality
- **Mono audio**: Optimized for single-speaker handheld devices with 64kbps Opus encoding
- **Embedded subtitles**: Foreign audio search enabled with optimal burn-in settings for small screens
- **H.264 video encoding**: High compatibility with portable devices using x264 encoder
- **Quality-focused**: Uses CRF 19 with "veryslow" preset for best compression efficiency

## Installation

1. Download the `handbrake-preset-miyoo.json` file
2. Open HandBrake
3. Go to **Presets** → **Import From File**
4. Select the downloaded JSON file
5. The "Miyoo Mini Plus" preset will appear in your presets list

## Technical Specifications

- **Video**: H.264, CRF 19, High Profile Level 3.2
- **Audio**: Opus mono, 64kbps
- **Resolution**: 640x480 (maintains aspect ratio)
- **Container**: MP4
- **Subtitles**: Foreign audio search with burn-in for non-native language content

## Compatible Devices

While designed for the Miyoo Mini Plus, this preset works well with other handheld consoles featuring:
- 640x480 displays
- Single/mono speaker systems
- Limited storage capacity
- Examples: RG-35XX, similar retro handhelds

## Usage

Simply select the "Miyoo Mini Plus" preset when encoding your videos in HandBrake. The preset handles all optimization automatically for the best balance of file size and quality on small screens.