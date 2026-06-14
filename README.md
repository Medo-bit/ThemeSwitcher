> [!IMPORTANT]
>If you are experiencing issues with automatic updates, you may be using an outdated version of the app. Please download the **latest version** directly from the [Releases](https://github.com/Medo-bit/ThemeSwitcher/releases/latest) page.
>
> Older versions contained a bug that prevented them from checking for updates automatically, requiring a manual check. Upgrading to the latest version completely resolves this issue and activates the secure encryption system (RSA).


### 🔔 How to Get Notified for Future Updates?
To ensure you receive an immediate email notification from GitHub whenever a new update or security patch is released, please enable the repository tracking feature:
1. Scroll to the **very top of this page**.
2. Click the **Watch** button (with the eye icon 👁️).
3. Select **Custom**, check the **Releases** box, and click **Apply**.
4. *(Optional)* Click the ⭐ **Star** button to support the project^_^
---
# ThemeSwitcher

![.NET](https://img.shields.io/badge/.NET-10.0-512BD4?style=for-the-badge&logo=dotnet)
![C#](https://img.shields.io/badge/Language-C%23-blue?style=for-the-badge&logo=csharp)
![Windows](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078d4?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

🌐 [Arabic Version](README.ar.md)

A blazing-fast, self-contained Windows utility that seamlessly transitions your system theme between Light and Dark modes based on precise local sunrise and sunset times. 

Engineered for performance and elegance, ThemeSwitcher integrates deeply with Windows to provide a native-like experience without the bloat.

## 🚀 Key Features

* **🌅 Smart Solar Sync & Hybrid Operations:** Automatically calculates your local solar times. It fetches data only once at the start of the day and operates 100% offline via smart caching.
* **🛡️ Theme State Enforcement & Anti-Tampering:** Automatically locks and secures your system's registry theme keys. It instantly rolls back any unauthorized external modifications or tweaks, with a flexible suspend option via the system tray icon, just click on "Disable ThemeSwitcher" or close it.
* **📦 Fully Self-Contained (.NET 10):** No need to install external runtimes! Everything the app needs is built right in. Just download and run.
* **⚡ Zero-Latency UI & GPU Acceleration:** Features a pre-rendered system tray menu with hardware-accelerated animations (Mica/Acrylic), adapting flawlessly to high refresh rate monitors (120Hz/144Hz+).
* **🧠 Hyper-Optimized Performance:** Aggressively manages memory and utilizes native Windows APIs, resulting in near-zero CPU usage, minimal RAM footprint, and extreme battery efficiency.
* **🔄 Instant & Silent Boot:** Applies your correct theme instantly upon system startup, completely eliminating screen flickering and delays.
* **📡 Smart Network Detection:** Built-in NCSI integration detects internet connectivity changes instantly to update data without freezing the UI.

## 💻 System Requirements
* **OS:** Windows 10 (Version 2004 or later) / Windows 11
* **Architecture:** x64
