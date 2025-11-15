# MACAN MEDIA SUITE
<img width="1860" height="2742" alt="macan-media-suite-github" src="https://github.com/user-attachments/assets/b790b88b-ee65-477a-a3df-0b8b67cbe16d" />

**Macan Media Suite** is a comprehensive, integrated software package designed to deliver a complete digital media experience. This suite provides a robust set of tools for high-fidelity audio playback, sophisticated video management, seamless online streaming, and efficient content downloading, all housed within a cohesive and user-friendly ecosystem.

---

## 🧰 Suite Components

This suite comprises five core applications, each engineered for a specific media purpose:

* ### 1. Macan Audio Player
    A feature-rich application for high-fidelity audio playback. Manage your complete music library, build custom playlists, and enjoy a premium, uninterrupted listening experience.

* ### 2. Macan Movie Pro
    A sophisticated video gallery, management solution, and Online TV. Organize your entire movie and video collection with a visually appealing, easy-to-navigate library interface.

* ### 3. Macan Video Downloader
    A powerful utility for capturing video content from various online sources. Save videos for offline viewing, with support for multiple formats and quality configurations.

* ### 4. Macan Video Player
    A sleek, robust, and lightweight standalone player for all your local video files and online streaming. It is optimized for smooth, high-definition playback of a wide variety of video codecs and formats.

* ### 5. Macan Vision
    Your gateway to global online entertainment. Stream live radio stations and watch online TV channels directly from your desktop, browse by genre, or find your local favorites.

---
## 📝 Changelog v2.7.0
1. Macan Audio Player v7.5.0 - 7.8.0
Fixes & Enhancements
Playlist Insertion Logic: Fixed an issue where new tracks added via the "Add File(s)" button or drag-and-drop were always appended to the end of the list. New files are now inserted directly below the currently playing track for improved queue management.
Playlist Multi-Selection: Enabled extended selection (Shift + Ctrl) in the playlist widget, allowing users to select and manage multiple tracks simultaneously.

2. Macan Vision v2.4.1 - 2.5.0
🚀 Major Improvements (The Fix)
[FIX] Fixed a freeze or "Not Responding" bug that occurred when the app tried to play a TV or Radio stream that was dead, had an error, or was otherwise inaccessible.

[IMPROVEMENT] Completely overhauled error handling logic:

PREVIOUSLY: Displayed a QMessageBox dialog when a stream had an error. This apparently caused a deadlock (the app crashed) because it was called from the wrong thread.

NOW: If a stream error is detected, the app will not display any dialog. Instead, it will automatically try to play the next channel in the list (auto-next channel).

💻 Technical Changes (Behind the Scenes)
[REFACTOR] Implemented the Qt Signals & Slots mechanism for all VLC player events (LibVLC).

[NEW] Added a new VlcEventSignals class. This class acts as a safe bridge for sending "messages" (such as playerError, playerPlaying, etc.) from the VLC thread to the main GUI thread.

[REFACTOR] Separated the VLC event handler logic into two parts to ensure thread safety:

Handlers (on_vlc_..._handler): These functions run on the VLC thread and are now ONLY responsible for emitting signals (sending messages).

Slots (on_player_..._slot): These functions run on the main GUI thread after receiving a signal. All UI logic (changing status labels, changing icons, visualizers) and auto-next logic (in on_player_error_slot) have been moved here.

---
## 🚀 Getting Started & Installation

This repository provides pre-compiled binaries for direct use. No cloning or source code compilation is required.

1.  Navigate to the [**Releases**](https://github.com/danx123/macan-media-suite/releases) section of this repository.
2.  Download the latest version of the **Macan Media Suite** installer.
3.  Extract the archive (if necessary) and run the installer or the primary application executable to begin.

---

## 📋 System Requirements

* **Operating System:** Windows 10 / 11
* **Processor:** 1.2 GHz or faster
* **RAM:** 4 GB (8 GB recommended)

---

## 🐞 Feedback and Support

For all bug reports, technical issues, or feature requests, please open an [**Issue**](https://github.com/danx123/macan-media-suite
---

## ⚖️ License MIT

Copyright © 2025 - Danx Exodus - Macan Angkasa. All Rights Reserved.

This software is distributed as freeware. It is provided "as is" without warranty of any kind, express or implied. The user assumes all risk associated with the use of this software.
