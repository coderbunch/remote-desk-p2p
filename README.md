# Remote Desk P2P (Redesk)

<div align="center">

> **Fast, secure, peer-to-peer remote desktop assistance and screen sharing built with Rust and WebRTC.**

[![Official Product Page](https://img.shields.io/badge/Coderbunch-Official_Product_Page-123b32?style=for-the-badge&logo=googlechrome)](https://coderbunch.com/apps/redesk)
[![Download on Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Get_It_Here-0078D4?style=for-the-badge&logo=microsoft)](https://apps.microsoft.com/detail/9NVQ2JDRS7DJ)
[![GitHub Releases](https://img.shields.io/github/v/release/coderbunch/remote-desk-p2p?style=for-the-badge&logo=github&color=indigo)](https://github.com/coderbunch/remote-desk-p2p/releases)
[![Platform Support](https://img.shields.io/badge/Platforms-Ubuntu_%7C_Linux_%7C_Windows-orange?style=for-the-badge)](https://github.com/coderbunch/remote-desk-p2p/releases)

</div>

---

## 🚀 Downloads

Download the latest version for your platform from the [**Releases Page**](https://github.com/coderbunch/remote-desk-p2p/releases):

| Operating System | Package Type | Download Link | Notes |
| :--- | :--- | :--- | :--- |
| **Ubuntu / Debian / Mint** | `.deb` | [Download `.deb`](https://github.com/coderbunch/remote-desk-p2p/releases/latest) | Recommended for Ubuntu & Debian |
| **Universal Linux** | `.AppImage` | [Download `.AppImage`](https://github.com/coderbunch/remote-desk-p2p/releases/latest) | Runs on any Linux distribution without installation |
| **Windows 10 / 11** | `.exe` Setup | [Download `.exe`](https://github.com/coderbunch/remote-desk-p2p/releases/latest) | Standalone desktop installer |
| **Windows 10 / 11** | `.msi` | [Download `.msi`](https://github.com/coderbunch/remote-desk-p2p/releases/latest) | Windows Installer package |
| **Windows Store** | Microsoft Store | [Get from Store](https://apps.microsoft.com/detail/9NVQ2JDRS7DJ) | Automatic updates via Microsoft Store |

---

## 🐧 Linux Installation Guide

### Ubuntu, Debian, Linux Mint (.deb)

1. Download the `.deb` file from the [Releases](https://github.com/coderbunch/remote-desk-p2p/releases) tab.
2. Open a terminal in your Downloads folder and run:
   ```bash
   sudo apt-get update
   sudo apt-get install ./Remote_Desk_P2P_*_amd64.deb
   ```
   *(Alternatively, double-click the `.deb` file in your file manager to install via Ubuntu Software).*
3. Launch **Remote Desk P2P** from your Application menu or run:
   ```bash
   remote-desk-p2p
   ```

### Universal Linux (.AppImage)

The AppImage package requires no installation and runs on Ubuntu, Fedora, Arch, openSUSE, and Manjaro:

1. Download the `.AppImage` file from [Releases](https://github.com/coderbunch/remote-desk-p2p/releases).
2. Make it executable:
   ```bash
   chmod +x Remote_Desk_P2P_*_amd64.AppImage
   ```
3. Run the application:
   ```bash
   ./Remote_Desk_P2P_*_amd64.AppImage
   ```

---

### ⚠️ Important Linux Runtime Note: X11 vs. Wayland

For **Host Mode** (sharing your screen and allowing your partner to control your mouse/keyboard):
- Modern Linux distributions (such as Ubuntu 22.04 and 24.04) default to the Wayland display protocol.
- Global screen capture and remote input simulation require an **X11 session**.
- **How to select X11:** On the Ubuntu login screen, click your username, then click the **gear icon (⚙️)** in the bottom-right corner and select **"Ubuntu on Xorg"** before logging in.
- For **Guest Mode** (viewing and controlling another PC), the app works seamlessly out-of-the-box on both Wayland and X11!

---

## ✨ Features

- ⚡ **Fluid 60 FPS Remote Screen Streaming** — Hardware-accelerated desktop capture with adjustable JPEG compression quality (Fast, Balanced, HD).
- 🔒 **Dual-Channel Architecture (P2P + Port 443 WSS Relay)** — Automatic direct peer-to-peer WebRTC connection. If a corporate firewall or symmetric NAT blocks UDP, it automatically fails over to an encrypted WebSocket cloud relay on standard HTTPS port 443.
- 📋 **Native Clipboard Synchronization** — Instant bidirectional clipboard sync between host and guest.
- 📁 **High-Speed Chunked File Transfers** — Drag-and-drop any file directly into the session with visual transfer progress.
- 🖥️ **Multi-Monitor Display Switching** — Easily switch between multiple screens on multi-monitor host setups on the fly.
- 💬 **Integrated In-Session Live Chat** — Instant encrypted messaging with unread notification badges.
- 🛡️ **Zero Setup & Secure** — Simple 6-digit session codes with optional session password protection.

---

## 🪟 Windows Installation

1. Download `Remote Desk P2P_0.1.0_x64-setup.exe` or `Remote Desk P2P_0.1.0_x64_en-US.msi`.
2. Double-click the installer and follow the prompt.
3. Launch **Remote Desk P2P** from your desktop or Start Menu.

---

## 📄 Privacy & Terms

- **Privacy Policy**: [https://coderbunch.com/apps/redesk/privacy](https://coderbunch.com/apps/redesk/privacy)
- **Publisher**: Pinetech IT Solutions Private Limited / Coderbunch
- **Support & Issues**: Please report any issues or feature requests on the [GitHub Issues](https://github.com/coderbunch/remote-desk-p2p/issues) tab.
