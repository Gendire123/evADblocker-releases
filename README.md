<div align="center">

# 🛡️ evADblocker
**Evade ads and costly ad blockers — 100% Free, Private, On-Device Android Ad Blocker**

[![Release](https://img.shields.io/github/v/release/Gendire123/evADblocker-releases?color=00E5FF&style=for-the-badge&logo=android)](https://github.com/Gendire123/evADblocker-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Gendire123/evADblocker-releases/total?color=7C4DFF&style=for-the-badge)](https://github.com/Gendire123/evADblocker-releases/releases)
[![Android](https://img.shields.io/badge/Android-8.0%2B%20(API%2026%2B)-3DDC84.svg?style=for-the-badge&logo=android)](https://www.android.com)
[![Zero Logs](https://img.shields.io/badge/Privacy-100%25%20On--Device%20(Zero%20Logs)-00E676.svg?style=for-the-badge)](https://github.com/Gendire123/evADblocker-releases)
[![License](https://img.shields.io/badge/License-Freeware-FF6D00.svg?style=for-the-badge)](LICENSE)

<br/>

<a href="https://github.com/Gendire123/evADblocker-releases/releases/latest/download/evADblocker.apk">
  <img src="https://img.shields.io/badge/⬇️_DOWNLOAD_evADblocker.apk-v1.0.0-00E5FF?style=for-the-badge&labelColor=0a0e1a" height="48" alt="Download evADblocker.apk" />
</a>

<br/>
<br/>

</div>

---

## 📖 About evADblocker

**evADblocker** is an ultra-fast, system-wide Android ad and tracker blocker designed from the ground up to protect your privacy and reclaim your mobile device's speed.

Unlike traditional cloud-based blockers or costly subscription services, evADblocker performs **100% of its DNS filtering and packet inspection locally on your device** via Android's native `VpnService` interface.

- **No Remote Proxies:** Your network traffic never leaves your phone.
- **Zero Tracking:** No user accounts, no analytics tracking, no server telemetry.
- **Microsecond Speed:** Hybrid domain indexing evaluated in ~30 nanoseconds per query.

---

## ✨ Features at a Glance

### 🛡️ System-Wide Ad & Tracker Neutralization
- **Local DNS Interception:** Blocks banners, video ads, tracking beacons, and malware domains before connections are established.
- **TLS SNI Inspection:** Deep inspection for HTTPS connections without breaking SSL encryption or requiring root.
- **Curated Rule Sets:** Bundled with industry standard lists (*AdGuard Base, EasyList, EasyPrivacy, Peter Lowe's*) plus automatic background updates.

### 🔒 Uncompromising Privacy
- **Encrypted DNS (DoH):** Switch seamlessly between secure upstreams (*Cloudflare, Quad9, AdGuard, custom DoH endpoints*).
- **Zero Cloud Logging:** Completely offline rule evaluation.

### ⚙️ Deep Customization & Control
- **Quick Pause Sheet:** Temporarily pause filtering (5m, 15m, 30m, 1h, or custom slider) with live countdown shield.
- **Per-App Firewall & Exclusions:** Exclude specific apps (e.g., banking or media) from filtering, or restrict apps to Wi-Fi/Cellular only.
- **Built-in Rule Tester:** Instant diagnosis tool to check why a specific domain was blocked and allow it with 1 tap.
- **Custom Allow/Deny Lists:** Manage personal whitelists and custom block rules on the fly.

### 📱 Seamless Android Integration
- **Quick Settings Tile:** 1-tap protection toggle right from your notification shade.
- **Home Screen Widgets:**
  - `4x1 Bar`: Real-time block counter & toggle.
  - `2x1 Compact`: Minimalist quick toggle.
  - `4x4 Premium Dashboard`: Complete live analytics, top categories, and control center.
- **Multi-Language UI:** Native support for **English** and **French** (*Français*).

---

## 📲 How to Install

```
1. Download evADblocker.apk from the latest release.
2. Tap the downloaded APK to install.
3. Follow the 3-step setup wizard (Grant VPN & set Battery to Unrestricted).
4. Enjoy a fast, clean, ad-free experience!
```

### Step-by-Step Installation:
1. **Download:** Grab the latest [`evADblocker.apk`](https://github.com/Gendire123/evADblocker-releases/releases/latest/download/evADblocker.apk).
2. **Allow Unknown Sources:** If prompted by Android, tap **Settings** and enable *"Allow from this source"*.
3. **Install & Launch:** Tap **Install**, then open **evADblocker**.
4. **Onboarding Wizard:**
   - **Step 1:** Welcome overview.
   - **Step 2 (VPN Permission):** Tap *Enable Protection* and confirm Android's connection request *(This allows evADblocker to inspect DNS locally — no data is sent outside your device)*.
   - **Step 3 (Battery Optimization):** Select **"Unrestricted"** so Android OS doesn't sleep the filter service when your screen locks.

---

## 📦 Release Asset & Security Verification

| Attribute | Specification |
|:---|:---|
| **Package Name** | `com.adblock.android` |
| **Version** | `v1.0.0` (Build `1`) |
| **Direct Download** | [`evADblocker.apk`](https://github.com/Gendire123/evADblocker-releases/releases/latest/download/evADblocker.apk) |
| **File Size** | `~2.73 MB` |
| **Minimum OS** | Android 8.0 Oreo (API 26+) |
| **Target OS** | Android 15 / 16 (API 36) |
| **SHA-256 Checksum** | `BEE80C3F259FC8E9AD11B64093BA9F116F78EF5281238176460C82643CEFCA53` |

### Verifying Checksum (Windows PowerShell):
```powershell
Get-FileHash evADblocker.apk -Algorithm SHA256
```

---

## 💬 Support & Bug Reports

Found an issue or have a feature request?
- Please open an issue in the [GitHub Issues](https://github.com/Gendire123/evADblocker-releases/issues) tracker.

---

<div align="center">
  <sub>Built with ❤️ for privacy and user control.</sub>
</div>
