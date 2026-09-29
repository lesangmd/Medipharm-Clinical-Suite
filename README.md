# MEDIPHARM Clinical Suite — Android Native Shell

- App: Clinical Suite
- Package: `com.medipharm.clinicalsuite`
- Minimum Android: 12 / API 31
- WebApp: https://www.sachyhoc.com/medipharm-clinical-suite/
- Account login: https://www.sachyhoc.com/dang-nhap/
- Registration: https://www.sachyhoc.com/dangky/
- Update source: https://github.com/lesangmd/Medipharm-Clinical-Suite
- Update APK pattern: `MEDIPHARM-Clinical-Suite-vX.Y.Z.apk`

Android integration hides Web/PWA install and fullscreen actions, adds Login / Register / Check for updates in the mobile menu, and returns to Clinical Suite after a valid WordPress login cookie is detected.


## Android v1.0.1 UI corrections
- Launcher icon is derived directly from the canonical WebApp icon asset.
- Hides the “Về Trang chủ” row only inside the Android native shell.
- Dark-mode control keeps the button/label but removes the “Toàn website” summary annotation on Android.
- Package ID and signing lineage remain unchanged for in-place update from v1.0.0.
