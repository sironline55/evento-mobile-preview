# Evento Mobile Web Preview

Static Expo Web export of the [Evento mobile app](https://github.com/sironline55/evento/tree/main/apps/mobile).

**Live URL**: https://sironline55.github.io/evento-mobile-preview/

## What this is

A preview of the mobile app (`apps/mobile`) rendered via `react-native-web` for browser viewing on iPhone Safari, Android Chrome, or desktop.

## Limitations

- QR scanner won't work (no Camera API in web runtime)
- Face ID / Touch ID won't work (no biometric API on web)
- Push notifications won't work
- All UI, navigation, picker, tab bar — fully functional

## Regenerating

This is a build artifact. Source lives in `sironline55/evento` (private). Each rebuild is a `git push --force` to this repo's `main` branch containing a fresh `dist/` output.
