# GSLens test releases

[Download GSLens 0.2.0 test APK](https://github.com/TayGuangSheng/gslens/raw/refs/heads/main/downloads/GSLens-0.2.0-debug.apk). Open this link in your phone's browser. Release notes are on the [Releases page](https://github.com/TayGuangSheng/gslens/releases).

## 0.2.0 — camera interface update

- iPhone Camera–inspired layout with a red record control, white vector buttons, yellow VIDEO indicator, and a larger viewfinder.
- The three-circle button opens the filter and intensity tray.
- Latest-clip thumbnail, focus brackets, and a recording timer.
- Responsive portrait and landscape layouts. Turn the phone before recording; orientation locks for each clip. Rotation also handles 180-degree turns while idle.
- Same application ID and development signing key as 0.1.0, with a higher version code for an in-place update.

Build, 13 LUT tests, lint (no errors), and matching APK signature checks passed. Physical Samsung UI and recording checks remain outstanding.

## 0.1.0 — first phone test build

- Native Android camera with six original cinematic looks, adjustable intensity, and Rec.709 3D `.cube` LUT import.
- Requests 4K at 30 fps in SDR, with grading applied to preview and saved video.
- Supports portrait/landscape composition, tap-to-focus, zoom, and optional microphone audio.
- Saves clips to **Movies/GSLens**. Requires Android 10 or later.

Download the APK using your phone's browser, open the downloaded file to install it, then launch **GSLens** and grant Camera access. Microphone access is optional.

This is a development-signed prerelease. The APK build, 13 LUT unit tests, software shader checks, lint, and APK signature verification passed. Camera recording, actual frame rate, image quality, audio sync, and heat have not yet been verified on a Samsung handset. HDR/log capture, 8K, and 60 fps are not implemented.

The first phone check should be a short clip. Confirm saved colour, orientation, audio, and 4K file dimensions before longer recordings. Keeping 4K dimensions does not guarantee identical results to Samsung Camera's proprietary processing.
