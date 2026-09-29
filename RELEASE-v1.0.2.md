# MEDIPHARM Clinical Suite Android v1.0.2

Android-only UI and release-metadata correction.

- Rewrites **Giới thiệu Ứng dụng** to describe Clinical Suite capabilities: clinical calculators/scores, clinical algorithms, specialty/topic lookup, contextual interpretation and personalization.
- Replaces WebApp/plugin version labels in Android-visible app chrome with **Android v1.0.2**.
- Simplifies the update action to **Kiểm tra phiên bản mới**; repository implementation details are not shown in the user-facing menu.
- Update dialogs no longer mention GitHub.
- Keeps the canonical WebApp launcher logo, package `com.medipharm.clinicalsuite`, and the established Android signing lineage.
- The build pipeline is self-contained: canonical launcher icon is stored in source and SHA-256 verified before Gradle build.
