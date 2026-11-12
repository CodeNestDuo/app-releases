# 📦 CodeNest Duo App Releases

Official distribution hub and release registry for applications published by **CodeNest Duo**.

This repository hosts version descriptor manifests (`.json`) for in-app updates and provides links to Google Play Store listings and directly downloadable, pre-compiled, signed Android application packages (`.apk`).

It also serves as the central issue tracker for bug reports, feature requests and feedback across all CodeNest Duo applications.

---

## 📱 Active Releases & Downloads

| Application | Package ID | Release Tag | Google Play Store | Direct APK Download | Update Manifest |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Alauna** | `com.app.alauna` | `alauna-latest` | [Play Store](https://play.google.com/store/apps/details?id=com.app.alauna) | [Download APK](https://github.com/CodeNestDuo/app-releases/releases/download/alauna-latest/alauna-release.apk) | [`manifests/alauna.json`](manifests/alauna.json) |
| **Aurelia** | `com.app.aurelia` | `aurelia-latest` | [Play Store](https://play.google.com/store/apps/details?id=com.app.aurelia) | [Download APK](https://github.com/CodeNestDuo/app-releases/releases/download/aurelia-latest/aurelia-release.apk) | [`manifests/aurelia.json`](manifests/aurelia.json) |
| **Aurelia TV** | `com.app.aureliatv` | `aureliatv-latest` | [Play Store](https://play.google.com/store/apps/details?id=com.app.aureliatv) | [Download APK](https://github.com/CodeNestDuo/app-releases/releases/download/aureliatv-latest/aureliatv-release.apk) | [`manifests/aurelia-tv.json`](manifests/aurelia-tv.json) |

---

## 🐛 Bug Reports & Feature Requests

Found a bug, experienced unexpected behaviour or have an idea for an improvement? We'd love to hear about it!

**[Open the CodeNest Duo Issue Tracker](https://github.com/CodeNestDuo/app-releases/issues/new/choose)**

Choose the appropriate submission form:

| Application | Issue Form |
| :--- | :--- |
| Aurelia (Mobile & Tablet) | [Report a Bug](https://github.com/CodeNestDuo/app-releases/issues/new?template=aurelia-mobile.yml) |
| Aurelia TV (Android TV & Google TV) | [Report a Bug](https://github.com/CodeNestDuo/app-releases/issues/new?template=aurelia-tv.yml) |
| Alauna (Android Music Player) | [Report a Bug](https://github.com/CodeNestDuo/app-releases/issues/new?template=alauna.yml) |
| All Applications | [Feature Request](https://github.com/CodeNestDuo/app-releases/issues/new?template=feature-request.yml) |

### Before submitting an issue

- Check existing open and closed issues to avoid duplicates.
- Select the correct application when submitting a report.
- Include your app version, device model and Android version.
- Describe the problem and provide clear steps to reproduce it.
- Attach relevant logs, screenshots or recordings whenever possible.
- Never include passwords, authentication tokens, private server credentials or other sensitive information in public reports.

We encourage testers to keep using the applications over an extended period and report bugs as they encounter them. Detailed reports help us investigate, reproduce and resolve issues more effectively.

### Other ways to reach us

- **Email:** codenestduo@proton.me
- **Discord:** [Join our community](https://discord.gg/AeMUp4aftg)
- **Twitter/X:** [@CodeNestDuo](https://twitter.com/CodeNestDuo)

---

## 🗂 Repository Structure

```text
app-releases/
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── aurelia-mobile.yml
│       ├── aurelia-tv.yml
│       ├── alauna.yml
│       ├── feature-request.yml
│       └── config.yml
├── manifests/
│   ├── alauna.json
│   ├── aurelia.json
│   └── aurelia-tv.json
└── README.md
```

- **manifests/** — Version metadata and download endpoints for application updates.
- **.github/ISSUE_TEMPLATE/** — Structured issue forms for bug reports and feature requests.
- **README.md** — Release registry and project information.

---

## 🔗 Official Links

- **Website:** https://codenestduo.com
- **GitHub:** https://github.com/CodeNestDuo
- **Discord:** https://discord.gg/AeMUp4aftg
- **Twitter/X:** https://twitter.com/CodeNestDuo
- **Support:** codenestduo@proton.me

---

**CodeNest Duo** — Independent Android applications, built with care.
