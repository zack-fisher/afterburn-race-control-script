# Turbine Dragster: Afterburn v2026 - Game Script Utility 2026

> **Browser racing helper for Turbine Dragster: Afterburn.** Designed for play in a web browser, it emphasizes camera-led controls, gesture input, and fast, short race sessions.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zack-fisher/afterburn-race-control-script?style=flat-square)](https://github.com/zack-fisher/afterburn-race-control-script)

---

<p align="center">
  <a href="https://zack-fisher.github.io/afterburn-race-control-script/">
    <img src="https://img.shields.io/badge/Download-Turbine%20Dragster%3A%20Afterburn%20Script-brightgreen?style=for-the-badge" alt="Download Turbine Dragster: Afterburn Script">
  </a>
</p>

> **[Direct Download - Turbine Dragster: Afterburn](https://zack-fisher.github.io/afterburn-race-control-script/)**

---

[Download Latest Build](https://zack-fisher.github.io/afterburn-race-control-script/)

---

## Overview

Turbine Dragster: Afterburn is a browser-first racing game that maps camera input and gestures to in-game control. MediaPipe, WebGL, and Three.js work together to interpret face orientation and hand placement as steering and throttle signals, so the game can run straight in the browser with no separate installer.

The experience is tuned for compact 30-second race heats and includes heat handling with an overheat mechanic, along with TTS-based voice narration. Because it is packaged as a single HTML file, it is easy to load, share, and refresh through GitHub Pages.

## Script Features

- Gesture-driven gameplay for browser sessions
- Face-tracking steering based on direction of the head
- Throttle control mapped to hand height
- Heat and overheat mechanics for race pacing
- 30-second rounds for quick play sessions
- TTS voice narration support
- Rendering path built on WebGL and Three.js
- Single-file HTML delivery with no installation step

## Setup

1. Download the latest build from the project page.
2. Open the HTML file in a modern web browser.
3. Allow camera access if you want gesture control to work.
4. Keep the file in a local folder or host it through GitHub Pages if you prefer browser access.

Basic use example:

- Open the page
- Enable camera input
- Turn your face to steer
- Raise or lower your hand to adjust throttle

## Options

| Setting | Purpose | Notes |
| --- | --- | --- |
| Camera access | Enables gesture control | Required for face and hand tracking |
| Steering input | Uses face direction | Adjusts left/right movement |
| Throttle input | Uses hand height | Controls acceleration level |
| Round length | Defines race duration | Set around 30 seconds |
| Audio narration | Enables TTS voice prompts | Optional browser audio support |
| Render mode | WebGL / Three.js display path | Depends on browser graphics support |

Example configuration idea:

- `camera: on`
- `gestureControl: on`
- `tts: on`
- `roundTimer: 30s`

## Compatibility

Turbine Dragster: Afterburn is meant for current web browsers that support HTML5, WebGL, camera permissions, and the browser APIs required by MediaPipe and TTS. Since the app depends on live video capture, results can vary depending on the device, webcam quality, and browser configuration.

Known limitations include:
- Camera permission is needed for gesture features
- Tracking behavior may differ across browsers
- Lower-end devices may show reduced rendering performance
- WebGL support is required for the main visual experience

## FAQ

**How do I start?**  
Open the HTML file in a compatible browser and grant camera access if you want gesture control.

**Can I host it online?**  
Yes, the project is suitable for GitHub Pages or another static host.

**Does it require installation?**  
No. It is a single-file HTML app that runs in the browser.

**What controls does it use?**  
Face direction handles steering, and hand height affects throttle.

**Can I change the gameplay feel?**  
Yes. You can adjust timing, input behavior, and narration settings in the app configuration.

**What if tracking is inconsistent?**  
Try a different browser, improve lighting, check camera permissions, or use a stronger webcam.

**Where are updates delivered?**  
Use the latest build link to pick up changes and refinements.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
