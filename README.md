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
## 📝 Changelog v2.5.0
1. Macan Video Downloader - Premium Edition v6.5.0 - 6.6.0
    - Fix stylesheet checkbox
    - Update Engine (macan-engine)

2. Macan Audio Player v7.2.0 - 7.5.0
   🚀 New Features
Add File(s) Functionality
A new "Add File(s)" button and corresponding icon (add-file) have been added to the main control panel.
This allows users to select and add one or more individual audio files (e.g., .mp3, .flac) via a file dialog, supplementing the existing "Add Folder" capability.
Windows File Association
A "Register format" option has been added to the main options menu.
This feature allows users on Windows to associate supported audio formats (.mp3, .m4a, .ogg, .flac, .wav) with the Macan Audio Player.
The system now includes helper functions (is_admin, run_as_admin, perform_windows_registration) to check for administrator privileges, request UAC elevation, and safely modify the Windows Registry.
Code & Refactoring
Custom PlaylistWidget Class
The standard QListWidget for the playlist has been refactored into a new custom class, PlaylistWidget.
This change encapsulates the playlist's setup logic (e.g., drag/drop modes) and prepares the codebase for more advanced, playlist-specific features in the future.
Preparatory Code
Added a (currently unused) handle_playlist_drop method, indicating future work on enhancing drag-and-drop functionality directly onto the playlist widget.
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
