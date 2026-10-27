# 🚀 Yamato Desktop 1.2 — Release Notes & Roadmap

Version 1.2 brings high-performance controls, low-level audio routing, interactive physics, and clean telemetry for Windows 10/11.

---

## ⚡ Performance & Optimization

- **Performance Profiles:** Choose between *Maximum Efficiency*, *Balanced*, and *Full Fidelity ("As Before")*.
- **Built-In Stress Test:** 4-stage automated benchmark (GPU/CPU) with 1-click fixes for bottlenecks.
- **Real-Time Telemetry:** Live monitoring for RAM, SSD space, active core usage, GPU, and network throughput.
- **Smart Autostart:** Elevated process priority (`AboveNormal`) for instant launch without starving system resources.

---

## 🎵 Media & Windows Integration

- **App-Specific Volume Mixer:** Route audio for individual apps or browsers via WASAPI without changing master volume.
- **SMTC Sync:** Full bi-directional track tracking, metadata, and album art extraction.
- **Global Hotkeys:**
  - `Ctrl + Alt + E` — Fullscreen / Edit workspace
  - `Ctrl + Alt + M` — Play / Pause toggle
  - `Ctrl + Alt + D` — Boss key (Quick-hide)
  - `Ctrl + Alt + R` — Random theme generator
  - `Ctrl + Alt + A` — AI Copilot workspace
- **Smart HUD:** Top-edge navigation remains hidden off-screen, dropping down only when the cursor hits the top boundary.

---

## 💥 Chaos Physics & Interactive Dynamics

- **Destruction Sandbox:** Smash and fragment widgets, clocks, and text containers in real-time.
- **Destruction Tools:** Impact hammers, directional saws, and explosive AOE payloads.
- **Debris & Restoration:** Physics-based trajectories, collision handling, damage counters, and 1-click restore.
- **Materials:** Authentic wood finishes (Oak, Walnut, Pine, Ebony), Glass, Neon, and Minimal themes.

---

## 🎨 Visual Fidelity & Polish

- **Interpolated Cursor Trails:** Catmull-Rom spline curves eliminate visual tearing during fast mouse movement.
- **High-DPI Adaptability:** Sub-pixel alignment and layout scaling for mixed multi-monitor setups.
- **Architecture Hardening:** Cleared out obsolete clock code and secured WebView IPC channels.

---

## 🗺️ Product Roadmap

### 1. Custom Media & Wallpapers
- Native hardware acceleration for local videos (MP4, WebM), live web URLs, and Wallpaper Engine compatibility.

### 2. Productivity Utilities
- Built-in image conversion (PNG, JPEG, WebP, ICO), resizing, and cropping directly from the desktop.
- **On-Screen OCR Translator:** Screen-region selection for instant cross-language machine translation.

### 3. Advanced Widgets & Controls
- **Multi-Widget Container:** Tabbed, stackable multi-widget docking frames.
- **Volume Mixer Widget:** Dedicated multi-channel desktop mixer with independent gain controls.
- **Notification & Launchpad Center:** Windows notification feed and quick app/link launcher.
- **Embedded CLI:** Integrated terminal drawer for PowerShell and CMD.

### 4. Developer Platform
- **Public JS/TS API:** Open SDK for building and distributing custom desktop widgets and plugins.
- **Granular Configs:** Deep customization files for layouts, themes, and sensor integrations.
