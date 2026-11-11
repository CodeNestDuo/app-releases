# 📦 CodeNest Duo App Releases

Official distribution hub and release registry for applications published by **CodeNest Duo**.

This repository hosts version descriptor manifests (`.json`) for in-app updates and provides links to Google Play Store listings and directly downloadable, pre-compiled, signed Android application packages (`.apk`).

---

## 📱 Active Releases & Downloads

| Application | Package ID | Release Tag | Google Play Store | Direct APK Download | Update Manifest |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Alauna** | `com.app.alauna` | `alauna-latest` | [Play Store](https://play.google.com/store/apps/details?id=com.app.alauna) | [Download APK](https://github.com/CodeNestDuo/app-releases/releases/download/alauna-latest/alauna-release.apk) | [`manifests/alauna.json`](manifests/alauna.json) |
| **Aurelia** | `com.app.aurelia` | `aurelia-latest` | [Play Store](https://play.google.com/store/apps/details?id=com.app.aurelia) | [Download APK](https://github.com/CodeNestDuo/app-releases/releases/download/aurelia-latest/aurelia-release.apk) | [`manifests/aurelia.json`](manifests/aurelia.json) |
| **AureliaTV** | `com.app.aureliatv` | `aureliatv-latest` | [Play Store](https://play.google.com/store/apps/details?id=com.app.aureliatv) | [Download APK](https://github.com/CodeNestDuo/app-releases/releases/download/aureliatv-latest/aureliatv-release.apk) | [`manifests/aurelia-tv.json`](manifests/aurelia-tv.json) |

---

## 🗂 Repository Structure

```text
app-releases/
├── manifests/
│   ├── alauna.json       # Alauna version metadata and download endpoints
│   ├── aurelia.json      # Aurelia version metadata and download endpoints
│   └── aurelia-tv.json   # AureliaTV version metadata and download endpoints
└── README.md             # Repository release registry index
