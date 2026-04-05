# FamilyFlow

> **The all-in-one family organizer — offline-first, no account required.**

[![Download APK](https://img.shields.io/badge/Download-APK%20v0.9.6--beta-brightgreen?style=for-the-badge&logo=android)](https://family-hub-armypewe.replit.app/api/download/familyflow.apk)
[![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-blue?style=flat-square&logo=android)](https://github.com/Castiel-Biz/FamilyFlow-APK/releases/latest)
[![Beta](https://img.shields.io/badge/Status-Beta-orange?style=flat-square)](https://github.com/Castiel-Biz/FamilyFlow-APK/releases)
[![Version](https://img.shields.io/badge/Version-0.9.6--beta-informational?style=flat-square)](https://github.com/Castiel-Biz/FamilyFlow-APK/releases/tag/v0.9.6-beta)

---

## What is FamilyFlow?

FamilyFlow is a private family organizer app for Android that keeps your household running smoothly — no cloud account, no subscription, no data sharing required. Everything lives on your device. From shared grocery lists and a family calendar to a group chat, budgeting tool, and an AI assistant, FamilyFlow brings the tools your family actually uses into one clean, fast app.

### Features

| Feature | Description |
|---|---|
| 📅 **Calendar** | Shared family calendar with events, reminders, and due-date alerts |
| ✅ **Tasks** | Family task list with assignees, priorities, and completion tracking |
| 🛒 **Grocery** | Shared shopping list with category grouping |
| 💬 **Chat** | Private group chat for the whole family |
| 💰 **Finance** | Income and expense tracker with recurring entries and projections |
| 📝 **Notes** | Full-text searchable notes and memos |
| 🤖 **AI Assistant** | Voice and text AI assistant powered by OpenAI — speaks back with on-device TTS |
| 🎨 **Themes** | 8 built-in color themes (default: Patriot — red & navy) |

---

## Download & Install

**Permanent download link (always the latest version):**

```
https://family-hub-armypewe.replit.app/api/download/familyflow.apk
```

### Step-by-step installation

> APKs are Android app files installed directly — this is called "sideloading." It is safe when you trust the source.

1. **Tap the download link above** on your Android device — or tap the `familyflow.apk` asset in the [latest release](https://github.com/Castiel-Biz/FamilyFlow-APK/releases/latest).
2. Once the file downloads, open it. You may see a prompt saying the file type is not allowed.
3. Tap **Settings** (or "Allow from this source") when prompted.
4. Enable **Install unknown apps** for your browser or file manager.
5. Go back and tap the downloaded file again.
6. Tap **Install** on the confirmation screen.
7. Once installed, tap **Open** to launch FamilyFlow.

> **Tip:** Starting with v0.9.6, FamilyFlow can detect and install updates automatically from inside the app — you only need to sideload manually for the very first install.

> **Tip:** After installing, you can turn off "Install unknown apps" again in your Android settings.

### Requirements

| | |
|---|---|
| **Android version** | 8.0 (Oreo) or higher — API level 26+ |
| **Storage** | ~104 MB for the app |
| **Internet** | Only required for the AI assistant — everything else works fully offline |

---

## Permissions & Why

FamilyFlow requests the following permissions. Here is exactly what each one does and why the app needs it:

| Permission | Plain-English Reason |
|---|---|
| 🎤 **Microphone** (`RECORD_AUDIO`) | Lets you speak to the AI assistant using your voice instead of typing. Only active while you hold the mic button. |
| ⚙️ **Audio Mode** (`MODIFY_AUDIO_SETTINGS`) | Required by Android to switch the device into recording mode when voice input starts. Not used for anything else. |
| 📳 **Vibration** (`VIBRATE`) | Powers haptic feedback — the gentle tap you feel when pressing buttons or receiving alerts. |
| 🔔 **Exact Alarms** (`USE_EXACT_ALARM`, `SCHEDULE_EXACT_ALARM`) | Allows the app to fire reminders at the precise time you set for calendar events and task due dates. Android requires this permission for time-sensitive notifications. |
| 🔄 **Boot Receiver** (`RECEIVE_BOOT_COMPLETED`) | When your phone restarts, Android clears all scheduled reminders. This permission lets FamilyFlow restore your upcoming reminders automatically after a reboot so you never miss one. |
| 📦 **Install Packages** (`REQUEST_INSTALL_PACKAGES`) | Allows the in-app updater to prompt you to install a downloaded APK update without leaving the app. Only used when you tap "Install Update." |

No other permissions are requested or used. FamilyFlow does not access your contacts, location, camera, files, or any other sensitive resource.

---

## Privacy

FamilyFlow is built privacy-first:

- **No account required.** You can use every feature without signing up. Family groups are optional.
- **All data stays on your device.** Your calendar, tasks, grocery lists, notes, finances, and chat are stored locally. Nothing is uploaded to a server.
- **Anonymous analytics only.** We collect anonymous, aggregate usage signals via Firebase Analytics (e.g., "the AI assistant was used today") to understand which features matter most. No personal data, no identifiers, no account linking. You can read the full privacy disclosure inside the app under Profile → Privacy.
- **AI assistant.** Messages you send to the AI assistant are routed through a secure relay to OpenAI for processing. They are not stored by FamilyFlow. Review [OpenAI's privacy policy](https://openai.com/privacy) for details on how OpenAI handles prompts.
- **Crash reporting.** If the app crashes, an anonymous crash report is sent via Firebase Crashlytics so we can identify and fix bugs. No personal information is included.

---

## Beta Disclaimer

FamilyFlow is currently in **public beta**. This means:

- The app is fully functional and safe to use, but you may encounter occasional bugs or rough edges.
- Data is stored locally — please do not rely on it as your only copy of critical information yet.
- Cloud sync is not yet available. Data does not transfer between devices.
- iOS support is planned but not available in this beta.
- Features and design may change between releases.

We appreciate your patience and feedback as we work toward a stable v1.0 release.

---

## Version History

| Version | Date | Highlights |
|---|---|---|
| [v0.9.6-beta](https://github.com/Castiel-Biz/FamilyFlow-APK/releases/tag/v0.9.6-beta) | Apr 2026 | In-app APK updater with progress bar; Android 8+ unknown-sources gate with Open Settings + Try Again flow |
| [v0.9.5-beta](https://github.com/Castiel-Biz/FamilyFlow-APK/releases/tag/v0.9.5-beta) | Apr 2026 | On-device speech recognition (no internet needed for voice); 3-way voice routing; symmetric 3+AI+3 tab bar layout |
| [v0.9.4-beta](https://github.com/Castiel-Biz/FamilyFlow-APK/releases/tag/v0.9.4-beta) | Apr 2026 | Analytics patch — all events correctly wired, voice attribution fix, update banner guard |
| [v0.9.3-beta](https://github.com/Castiel-Biz/FamilyFlow-APK/releases/tag/v0.9.3-beta) | Apr 2026 | Firebase Analytics + Crashlytics, Expo OTA updates, in-app APK update banner |
| [v0.9.2-beta](https://github.com/Castiel-Biz/FamilyFlow-APK/releases/tag/v0.9.2-beta) | Apr 2026 | Account security (change password, delete account), About & Permissions section in Profile |
| [v0.9.1-beta](https://github.com/Castiel-Biz/FamilyFlow-APK/releases/tag/v0.9.1-beta) | Apr 2026 | Voice input fix on Android, mic button layout fix |
| [v0.9.0-beta](https://github.com/Castiel-Biz/FamilyFlow-APK/releases/tag/v0.9.0-beta) | Apr 2026 | First official beta release — all core features |

[View all releases →](https://github.com/Castiel-Biz/FamilyFlow-APK/releases)

---

## Support & Feedback

Found a bug? Have a suggestion? We want to hear from you.

- **Email:** [support@familyflow.app](mailto:support@familyflow.app)
- **GitHub Issues:** [Open an issue](https://github.com/Castiel-Biz/FamilyFlow-APK/issues) on this repo

---

## Package Info

| | |
|---|---|
| **Package name** | `com.familyflow.app` |
| **Current version** | 0.9.6-beta (versionCode 9) |
| **Min Android** | 8.0 (API 26) |
| **Architecture** | arm64-v8a, armeabi-v7a |
| **Size** | ~104 MB |

---

*FamilyFlow is independent software, not affiliated with any platform or app store.*
