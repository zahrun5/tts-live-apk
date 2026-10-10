# TTS-Live APK

Native Android wrapper for [TTS-Live v2](https://github.com/zahrun5/harungamingtools) (TikTok Live interactive game platform).

Built with Flutter (Material 3) → APK ARM64. CI build via GitHub Actions.

## Build

APK is built automatically on push to `main`. Download from:
**Actions → Build APK → latest run → Artifacts → tts-live-apk**

## Local dev

```bash
flutter pub get
flutter run -d <device>
flutter build apk --release
```

## Roadmap

- [x] Hello world Flutter app
- [ ] Login screen (REST API to tts-live-v2 server)
- [ ] Dashboard with room list
- [ ] Native game overlay (replaces OBS browser source — 10x lighter)
- [ ] Socket.IO real-time client
- [ ] TikTok integration
