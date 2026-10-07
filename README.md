# ThemeSwitcher

![.NET](https://img.shields.io/badge/.NET-10.0-512BD4?style=for-the-badge&logo=dotnet)
![C#](https://img.shields.io/badge/Language-C%23-blue?style=for-the-badge&logo=csharp)
![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078d4?style=for-the-badge&logo=windows)
![Architecture](https://img.shields.io/badge/Architecture-x64-success?style=for-the-badge)

### 🌓 A modern, ultra-lightweight Auto Dark Mode scheduler & 4K wallpaper gallery for Windows 10/11

🌐 [Arabic Version](README.ar.md)

A blazing-fast, self-contained Windows utility that seamlessly transitions your system theme between Light and Dark modes based on precise astronomical sunrise and sunset times.

Engineered for performance and visual elegance, ThemeSwitcher integrates directly with native Windows APIs to deliver an instant, system-level experience without background services or resources consumption.

---

<p align="center">
  <img src="assets/preview.png" alt="ThemeSwitcher Preview" width="100%">
</p>


## 🚀 Key Features

* **🌅 Smart Solar Sync & Offline-First:** Automatically calculates precise local sunrise and sunset times. It synchronizes solar data once per day and operates 100% offline via encrypted, resilient local caching.
* **⚡ Instant Theme Engine (FastSwitch):** Switches instantly upon system startup, sleep wake, or screen unlock—minimizing screen flicker to the absolute minimum for an ultra-smooth transition, applying the target theme before the Windows desktop even finishes loading. Seamlessly updates all open and compatible Windows applications in real time, replicating the official Windows Settings behavior.
* **🖼️ Up to 4K Wallpaper Gallery:** Discover, customize, and apply stunning high-resolution wallpapers (1080p, 2K, and up to 4K) tailored for Light and Dark modes, featuring instant (0ms) local browsing and atomic multi-monitor synchronization.
* **🔋 True Zero-Impact (0% CPU on Idle):** Built with an event-driven architecture that drops CPU usage strictly to 0% during idle, preserving battery life and leaving system resources completely untouched.
* **🛡️ Theme State Enforcement & Anti-Tampering:** Safeguards your system registry theme keys, rolling back unauthorized external overrides while offering instant suspension right from the tray menu.
* **📦 Fully Self-Contained (.NET 10):** Ready to run right out of the box with zero runtime dependencies. Everything the app needs is built-in—just download and launch.
* **⚡ Zero-Latency Fluent UI:** A hardware-accelerated tray interface built with modern Windows materials (Mica/Acrylic), flawlessly tuned for high-refresh-rate displays (120Hz/144Hz+).
* **📶 Resilient Network & Auto-Recovery:** Integrates smart three-way network sensing (NCSI/Checkpoints) to distinguish real internet access from local routing, safely scheduling background tasks without UI freezes.
* **🔄 Built-in In-App Updater:** Check and install new releases seamlessly from inside the app without opening an external browser.

## 📦 Installation & Updates

You can install or upgrade ThemeSwitcher instantly using **winget** in Windows Terminal (or PowerShell):

# Install
```powershell
winget install --id Medoo.ThemeSwitcher
```
# Update to the latest version
```powershell
winget upgrade --id Medoo.ThemeSwitcher
```
> 💡 **Prefer manual installation?** Download the latest standalone installer directly from [GitHub Releases](https://github.com/Medo-bit/ThemeSwitcher/releases/latest).

## 💻 System Requirements
* **OS:** Windows 10 (Version 2004 or later) / Windows 11
* **Architecture:** x64
* **Privileges:** Standard User (No Administrator rights required for daily operation)
