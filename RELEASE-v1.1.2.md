# MEDIPHARM Clinical Suite Android v1.1.2 — Inline Offline Bootstrap Hotfix

Corrects the Android offline startup deadlock seen in v1.1.0 and v1.1.1.

- Critical startup JavaScript is embedded directly in the offline HTML.
- The 1,505-tool catalog is embedded and no longer fetched during startup.
- No external JavaScript request is required to complete the initial page load.
- Full 19 MB runtime hydration is disabled in the background and is loaded only when a tool is opened.
- Android native-asset bridge provides a deterministic fallback for local JSON reads.
- Clinical content remains v16.7.7.
- versionName 1.1.2; versionCode 6.
- APK SHA-256: e76ceafb29b6516de88d9c952bef96b7aacb3149c619b2715e0231ba71aa16bc
