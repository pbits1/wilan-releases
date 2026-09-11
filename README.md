# WiLan Releases

Official release and download repository for **WiLan** — blazing-fast, secure, and private peer-to-peer file transfer over your local Wi-Fi network.

No internet required. No cloud uploads. No size limits.

---

## 🚀 Downloads

Download the latest version directly from the [**Latest Releases**](https://github.com/pbits1/wilan-releases/releases/latest) page:

| Platform | Format | System Requirements | Direct Download |
| :--- | :--- | :--- | :--- |
| **Android** | `.apk` | Android 11.0+ (API 30+) | [Download Android APK](https://github.com/pbits1/wilan-releases/releases/latest) |
| **Windows** | `.msi` / `.exe` | Windows 10 & 11 (64-bit) | [Download Windows Installer](https://github.com/pbits1/wilan-releases/releases/latest) |
| **Linux** | `.deb` | Ubuntu / Debian / Mint (x86_64) | [Download Linux .deb](https://github.com/pbits1/wilan-releases/releases/latest) |
| **iOS / macOS / Other** | WebLink Browser | Any modern web browser | *No install needed — connect via WebLink* |

---

## 📦 Installation Guide

### Android
1. Download the latest `WiLan-*-android.apk` on your device.
2. Open the downloaded file from your browser or file manager.
3. If prompted by Android, allow installation from this source.
4. Launch **WiLan** and grant the required local network / storage permissions.

### Windows
1. Download `WiLan-*-windows.msi` (or `.exe`).
2. Double-click the installer and follow the setup wizard.
3. Launch **WiLan** from your Start Menu or desktop shortcut.
   > *Note: Java is fully self-contained and bundled inside the installer. No external Java installation is required.*

### Linux (Ubuntu / Debian / Linux Mint)
1. Download `WiLan-*-linux.deb`.
2. Open your terminal in the download folder and run:
   ```bash
   sudo apt install ./WiLan-*-linux.deb
   ```
   *(Or simply double-click the `.deb` file in your desktop file manager to install via Software Center).*
3. Launch **WiLan** from your application app launcher.

---

## ✨ Features

- **Blazing Fast Transfer (Wi-Fi 6+ Optimized)**: Engineered with a 4 MB pipelined streaming window and zero-copy Netty networking for gigabit local transfers.
- **100% Offline & Private**: Files transfer directly between your devices over your local router or mobile hotspot. Nothing touches the cloud or external servers.
- **Smart Receiver Protection**: Checks disk space before receiving large files. If your drive is almost full, WiLan gives you a 1-click option to switch storage drives without breaking transfers.
- **Categorized Downloads**: Automatically organizes incoming files into dedicated folders (`Videos`, `Images`, `Audio`, `Documents`, `Apps`, `Archives`).
- **WebLink (Cross-Platform Browser Sharing)**: Transfer files to and from iPhones, iPads, Macs, and Chromebooks using any web browser with 4-digit PIN authentication.
- **End-to-End Cryptographic Pinning**: Peer-to-peer data channels use TLS encryption with certificate fingerprint pinning to prevent tampering and eavesdropping.

---

## 🔒 Verification & Integrity

Every official release includes a `SHA256SUMS.txt` file on the [Releases](https://github.com/pbits1/wilan-releases/releases) page. You can verify your download with:

```bash
sha256sum -c SHA256SUMS.txt
```

---

## 💬 Feedback & Issues

Encountered a bug or have a feature suggestion?
Please open an issue on the [Issue Tracker](https://github.com/pbits1/wilan-releases/issues).

---

© 2026 WiLan Project. All rights reserved.
