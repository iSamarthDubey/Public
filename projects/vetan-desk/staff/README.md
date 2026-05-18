# Vetan Desk -- Staff App

Staff-facing mobile application for individual employees. Provides self-service access to attendance, leave, payslips, and shift information.

> Source code is maintained in a private repository. This page covers installation, updates, and usage only.

---

## Download

All APK builds are published on the [Releases](https://github.com/iSamarthDubey/Public/releases?q=staff-v) page. Look for releases tagged `staff-v*`.

| Artifact | Description |
|----------|-------------|
| `*-universal.apk` | **Recommended** -- works on all Android devices |
| `*-arm64.apk` | Smaller download, optimized for modern phones (ARM64) |
| `*-arm32.apk` | For older 32-bit ARM devices |

If you are unsure which build to use, download the `universal` APK.

---

## Installation

1. Download the latest `universal` APK from the [Releases](https://github.com/iSamarthDubey/Public/releases?q=staff-v) page.
2. Open the downloaded `.apk` file on your Android device.
3. If prompted, allow installation from unknown sources in your device settings.
4. Launch the app and sign in with the credentials provided by your organization administrator.

---

## In-App Updates

The app automatically checks this repository for new versions on launch. When an update is available, a prompt will appear with instructions to download and install the latest build.

No manual version checking is required after the initial installation.

---

## Requirements

| Requirement | Minimum |
|-------------|---------|
| Android version | 7.0 (API level 24) |
| Camera | Required (biometric face attendance) |
| Location services | Required (on-site attendance tracking) |
| Internet | Required for login, sync, and updates |
| Storage | Approximately 50 MB |

---

## Features

- **Biometric attendance** -- Punch in and out using face recognition via the device camera.
- **Leave management** -- Apply for leave, view balances, and track approval status.
- **Payslips** -- Access and download monthly payslip documents.
- **Shift tracking** -- View assigned shifts, current shift status, and daily schedule.
- **On-site attendance** -- GPS-verified check-ins for field or remote work locations.
- **Offline support** -- Attendance punches are queued locally and synced automatically when connectivity is restored.
- **App lock** -- Optional biometric or device PIN lock to secure the app when not in use.

---

## Security

- APKs are signed with the official Vetan Desk release keystore.
- Builds are produced exclusively through the project's CI/CD pipeline and mirrored to this repository automatically.
- No user data or telemetry is collected through this distribution channel.

---

## Changelog

Release notes are included with each GitHub Release. View the full changelog for any version on the [Staff App Releases](https://github.com/iSamarthDubey/Public/releases?q=staff-v) page.

---

## Support

This repository is a distribution channel and does not accept issues or pull requests. If you encounter a problem with the app, contact your organization's Vetan Desk administrator.

---

[Back to Vetan Desk](../README.md) | [Back to Project Index](../../../README.md)
