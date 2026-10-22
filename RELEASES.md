# GSLens test releases

Download the Android test APK from this repository's [Releases page](https://github.com/TayGuangSheng/gslens/releases).

## 0.1.0 — first phone test build

- Native Android camera with six original cinematic looks, adjustable intensity, and Rec.709 3D `.cube` LUT import.
- Requests 4K at 30 fps in SDR, with grading applied to preview and saved video.
- Supports portrait/landscape composition, tap-to-focus, zoom, and optional microphone audio.
- Saves clips to **Movies/GSLens**. Requires Android 10 or later.

Download the APK using your phone's browser, open the downloaded file to install it, then launch **GSLens** and grant Camera access. Microphone access is optional.

This is a development-signed prerelease. The APK build, 13 LUT unit tests, software shader checks, lint, and APK signature verification passed. Camera recording, actual frame rate, image quality, audio sync, and heat have not yet been verified on a Samsung handset. HDR/log capture, 8K, and 60 fps are not implemented.

The first phone check should be a short clip. Confirm saved colour, orientation, audio, and 4K file dimensions before longer recordings. Keeping 4K dimensions does not guarantee identical results to Samsung Camera's proprietary processing.
