# GENO Wellness App Downloads

This repository tracks download documentation for the GENO Wellness mobile application.
Large APKs, especially debug builds, should be published as GitHub Release assets instead of being updated in `downloads/`.

## Download Latest Build

### Android Debug Build

- Direct download: [genowellness-debug.apk](https://github.com/GENO-Wellness/geno-downloads/releases/latest/download/genowellness-debug.apk)
- Release page: [Latest release assets](https://github.com/GENO-Wellness/geno-downloads/releases/latest)

> Use the release asset for the debug APK. The current local debug file is large and should not be the primary distribution path.

### Android Release Builds

Choose the APK for your device architecture:

| Architecture | Download | Size | Device Type |
| ------------ | -------- | ---- | ----------- |
| **ARM64** | [⬇️ Download](https://github.com/GENO-Wellness/geno-downloads/releases/download/v1.1.2/geno-wellness-arm64.apk) | 43 MB | Modern phones (2016+) |
| **ARM32** | [⬇️ Download](https://github.com/GENO-Wellness/geno-downloads/releases/download/v1.1.2/geno-wellness-armeabi.apk) | 35 MB | Older phones |
| **x86_64** | [⬇️ Download](https://github.com/GENO-Wellness/geno-downloads/releases/download/v1.1.2/geno-wellness-x86_64.apk) | 48 MB | Emulators/Chromebooks |

**Recommended**: Most modern Android phones use **ARM64** (arm64-v8a).

> APK files are hosted as GitHub Release assets to avoid repository size limits.

## How To Update The Debug APK

1. Build or copy the new debug APK locally as `genowellness-debug.apk`.
2. Upload it to a GitHub Release in `GENO-Wellness/geno-downloads`.
3. Keep the asset filename exactly `genowellness-debug.apk` so the stable link above keeps working.
4. Do not commit the new large debug APK into `downloads/`.

If you need a versioned release URL instead of the stable latest URL, use:

`https://github.com/GENO-Wellness/geno-downloads/releases/download/<tag>/genowellness-debug.apk`

## Archived Small Builds

These smaller builds can remain in `downloads/`:

| File | Size | Type |
| ---- | ---- | ---- |
| [geno_wellness_hub.apk](downloads/geno_wellness_hub.apk) | 67 MB | Universal |
| [app-arm64-v8a-release.apk](downloads/app-arm64-v8a-release.apk) | 43 MB | Release ARM64 |
| [app-armeabi-v7a-release.apk](downloads/app-armeabi-v7a-release.apk) | 35 MB | Release ARM32 |
| [app-x86_64-release.apk](downloads/app-x86_64-release.apk) | 48 MB | Release x86_64 |
| [app-arm64-v8a-profile.apk](downloads/app-arm64-v8a-profile.apk) | 33 MB | Profile ARM64 |
| [app-armeabi-v7a-profile.apk](downloads/app-armeabi-v7a-profile.apk) | 31 MB | Profile ARM32 |
| [app-x86_64-profile.apk](downloads/app-x86_64-profile.apk) | 35 MB | Profile x86_64 |
| [app-profile.apk](downloads/app-profile.apk) | 31 MB | Profile Universal |

## Installation Instructions

### Android

1. Download the appropriate APK file for your device
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to **Settings > Security > Unknown Sources** (varies by device)
   - Or when prompted, tap "Settings" and enable for your browser
3. Open the downloaded APK file
4. Follow the installation prompts

## How to Check Your Device Architecture

1. Download a free app like "CPU-Z" from Play Store
2. Or check Settings > About Phone > Processor

## Version History

| Version | Date | Changes |
| ------- | ---- | ------- |
| 1.1.0 | Mar 7, 2026 | Redesigned wellness cards, improved My Wellness screen |
| 1.0.0 | Mar 4, 2026 | Initial debug build with Daily.co video calls |

## Security

APK files are built from verified source code in the GENO mobile app repository.

## Support

For issues or questions, please contact support.
