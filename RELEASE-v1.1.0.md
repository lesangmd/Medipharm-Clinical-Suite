# MEDIPHARM Clinical Suite Android v1.1.0 — Offline-First Core

Production Android release.

- Android version: 1.1.0 (versionCode 4)
- Package: com.medipharm.clinicalsuite
- Offline WebApp content: MEDIPHARM Clinical Suite v16.7.7
- Offline catalog: 1,505 clinical tools
- Offline payload: 52 locked files, 28,244,140 bytes
- Default runtime: local APK assets via appassets.androidplatform.net
- Network is required only for MEDIPHARM account authentication, Android update checks, and user-opened external references.
- Build gate: locked source SHA-256 + 52-file offline payload verification + Gradle assembleRelease + zipalign.
- Release APK is signed with the established Clinical Suite release certificate used by v1.0.x.
- Signing certificate SHA-256: 6fe0ff13fa55e8a1805468a939fd0eefc3cbe7b0c83f2bf89fac45ec2c209c5b
- APK SHA-256: 3015858b4781eab363631dda63c75f6416f1f2ce26e9392973ea4972ba71629c
- Source ZIP SHA-256: ae29b4c8c3e66e924349739646b22f216e1a0a32c83d54eacafb02e865641d8f

Production build record: GitHub Actions run #19 (run ID 36547375483) completed successfully.
