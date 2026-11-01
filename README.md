# SmartPSS Lite

Client software for configuring and managing Dahua devices: IP cameras, recorders (NVR/XVR), access control, attendance and video intercom.

[![Version](https://img.shields.io/badge/version-1.006.0000000.1-blue)](https://github.com/kaashifhamid/smartpss-lite/releases/tag/v1.006)
[![Platform](https://img.shields.io/badge/platform-Windows%207%20%7C%208%20%7C%2010%20%7C%2011%20(64--bit)-lightgrey)](#system-requirements)

---

## Download

| Item | Details |
|---|---|
| **Version** | V1.006.0000000.1 (build R.260305) |
| **Installer** | [`General_SmartPSSLite_MultiLang_Win64-Install_IS_V1.006.0000000.1.R.260305.exe`](https://github.com/kaashifhamid/smartpss-lite/releases/download/v1.006/General_SmartPSSLite_MultiLang_Win64-Install_IS_V1.006.0000000.1.R.260305.exe) |
| **Platform** | Windows 64-bit |
| **Languages** | Multi-language (see [Supported Languages](#supported-languages)) |
| **Release page** | [v1.006](https://github.com/kaashifhamid/smartpss-lite/releases/tag/v1.006) |

### Verify the download (optional)

Run in PowerShell and compare with the checksum below:

```powershell
Get-FileHash ".\General_SmartPSSLite_MultiLang_Win64-Install_IS_V1.006.0000000.1.R.260305.exe" -Algorithm SHA256
```

```
SHA-256: <PASTE-HASH-HERE>
```

> **Note:** The installer is not code-signed by this repository. Windows SmartScreen or antivirus software may show a warning on first run.

---

## Features

| Area | Highlights |
|---|---|
| **Video** | Customizable live view with priority windows, remote device control (including two-way talk), one-click manual recording for evidence |
| **Access Control** | Remote door unlock, area monitoring, advanced authentication rules for classified areas, complete access activity records |
| **Attendance** | Working-hours tracking, absence and leave management, cross-day attendance, detailed reports for appraisal and wage calculation |
| **Video Intercom** | Unified management of intercom devices, two-way communication, remote access control, call and emergency report handling, group notices to indoor monitors |
| **Event** | Alarm monitoring and processing, live statistics, predefined alarm types, manual snapshots, email notifications |

Additional functions: smart search and playback, unified personnel management, multi-period attendance, first card unlock, multi-card unlock, anti-passback and inter-door lock.

---

## System Requirements

Recommended values for smooth operation:

| Component | Requirement |
|---|---|
| **CPU** | Intel Core i5-6500 @ 3.20 GHz |
| **Memory** | 8 GB |
| **Storage** | 256 GB |
| **Operating System** | Windows 7, 8, 10 or 11 (64-bit) |
| **Display Resolution** | 1280 × 800 or higher |

---

## Supported Devices

| Category | Models |
|---|---|
| **Cameras** | Network camera (fixed-focal, vari-focal, fisheye), PTZ camera, thermal camera |
| **Recorders** | Network Recorder (NVR), HDCVI Recorder (XVR) |
| **Access control** | Turnstile (ASG), Access Standalone (ASI), Access Controller (ASC), Access Reader (ASR), Fingerprint Enrollment Reader (ASM) |
| **Attendance** | Time & Attendance Terminal (ASA) |
| **Video intercom** | Apartment and villa door station (VTO), Indoor Monitor (VTH), Master Station (VTS) |

---

## Specifications

### General

| Item | Capacity |
|---|---|
| Time attendance and doors | 64 |
| Persons | 1,000 |
| Cards | 5,000 |
| Fingerprints | 3,000 |
| Face pictures | 2,000 |

### Video

| Item | Specification |
|---|---|
| Video channels | 64 |
| Resolution | 8 MP, 4 MP, 3 MP, 1080p, 720p, D1 |
| Decoding capability | 64-channel D1 (720 × 576) |
| Multi-channel live view | Arbitrary split, up to 64 channels |
| Multi-channel playback | 32-channel D1 (720 × 576) |
| Recording mode | General, alarm, motion detection, intelligent |

### Access Control

| Item | Limit |
|---|---|
| Area | 40 |
| Holiday template | 128 |
| Permission rule | 128 |
| Weekly plan | 128 |
| Max time periods per day | 4 |
| Holiday | 128 |
| Anti-passback group list | 64 |
| Global anti-passback group list | 16 |
| First card unlock record | 64 |
| Multi-card unlock record | 64 |
| Inter-door lock record | 64 |
| Real-time event display | 100 |

### Attendance Management

| Item | Limit |
|---|---|
| Report type | 19 |
| Attendance period | 32 |
| Attendance shift | 32 |
| Shift schedule | 32 |
| Holiday | 32 |
| Rest periods in a single attendance period | 7 |

### Video Intercom

| Item | Limit |
|---|---|
| VTO / VTH / VTS | 512 |

### Supported Events

| Type | Events |
|---|---|
| **Intelligent** | Tripwire, Intrusion, Scene Change, Abandoned Object, Missing Object, Wander, Crowd Gathering Estimation, Fast-Moving, Illegal Parking, Face Detection |
| **Device** | No Disk, Disk Fault, Disk Full, Invalid Access, Device Offline, Voltage Alarm (Low) |
| **Alarm** | Video Loss, Video Tampering, Motion Detect, SMD, Audio Abnormal, Mutation Detection, Defocus Detection, IPC Offline |
| **Access control** | Intrusion Alarm, Door Unclosed Alarm, Duress Alarm, Blocklist Alarm, Trailing Alarm, Stay Alarm |
| **Sensors** | Vandal-proof Alarm, Door Sensor Alarm, Heat Alarm, Duress Password Unlock Alarm, Infrared, Gas, Smoke Sensor, Urgency Button, Stolen Alarm, Perimeter Alarm |

### Supported Languages

English, Spanish (European), Spanish (Latin American), French, Italian, Portuguese (European), Portuguese (Brazilian), Russian, Thai, Turkish, Korean, Traditional Chinese, Japanese, Arabic, Hungarian, Indonesian, Polish, Hebrew, Czech, Slovak, Ukrainian, Vietnamese, German, Malay, Bulgarian

---

## Installation

1. Download the installer from the [Release page](https://github.com/kaashifhamid/smartpss-lite/releases/tag/v1.006).
2. Run the `.exe` as administrator and follow the setup wizard.
3. Launch **SmartPSS Lite** and add your devices.

---

## Disclaimer

SmartPSS Lite is software developed by **Dahua**. All trademarks, product names and copyrights belong to their respective owners. Specifications are taken from the Dahua datasheet (Rev 002.000, 2026) and are subject to change without notice. For official downloads and support, visit [www.dahuasecurity.com](https://www.dahuasecurity.com).
