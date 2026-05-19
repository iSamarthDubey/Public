# Vetan Desk -- Lens Kiosk

Tablet-based kiosk application deployed at physical entry points for face-recognition attendance. Designed for unattended, always-on operation on dedicated Android tablets.

> This application is not intended for general public use. It is deployed and managed by organizational administrators on designated kiosk hardware.
> Source code is maintained in a private repository.

---

## Download

Lens Kiosk builds are published on the [Releases](https://github.com/iSamarthDubey/Public/releases?q=lens-v) page when available. Look for releases tagged `lens-v*`.

| Artifact | Description |
|----------|-------------|
| `*-universal.apk` | **Recommended** -- works on all Android tablet devices |
| `*-arm64.apk` | Optimized for modern ARM64 tablets |

---

## Deployment

Lens is not a self-service application. Deployment is handled by the organization's IT administrator:

1. Download the latest APK from the [Releases](https://github.com/iSamarthDubey/Public/releases?q=lens-v) page.
2. Sideload the APK onto the designated kiosk tablet.
3. Configure the device with the organization's backend URL and kiosk authentication PIN.
4. Enable Android kiosk mode or a device management profile to lock the tablet to the Lens application.

---

## Requirements

| Requirement | Minimum |
|-------------|---------|
| Android version | 7.0 (API level 24) |
| Device type | Tablet (7" or larger recommended) |
| Camera | Required (front-facing, for face recognition) |
| Internet | Required for attendance sync and model updates |
| Storage | Approximately 100 MB (includes ML model cache) |

---

## Features

- **Face recognition attendance** -- Identifies staff members using on-device ML inference and syncs attendance events to the backend.
- **Offline resilience** -- Queues attendance events locally with UUID-based idempotency when connectivity is lost, and syncs automatically on reconnection.
- **Text-to-speech feedback** -- Audible confirmation of successful or failed attendance scans.
- **Admin PIN access** -- Configuration and administrative functions are protected behind a PIN-authenticated interface.

---

## Security

- APKs are signed with the official Vetan Desk release keystore.
- Face embeddings are processed on-device and transmitted only to the organization's private backend.
- No biometric data is stored on or transmitted through this repository.

---

## Changelog

Release notes are included with each GitHub Release. View the full changelog for any version on the [Lens Kiosk Releases](https://github.com/iSamarthDubey/Public/releases?q=lens-v) page.

---

## Support

For deployment assistance or technical issues, contact your organization's Vetan Desk administrator or the development team directly.

---

[Back to Vetan Desk](../README.md) | [Back to Project Index](../../../README.md)
