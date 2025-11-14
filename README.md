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
## 📝 Changelog v2.6.0
1. Macan Video Downloader - Premium Edition v6.6.1 - 7.0.0
✨ Added
CLI (Command-Line Interface) Mode:
A new "CLI Mode" checkbox has been added to the main interface.
When enabled, this mode switches the queue to a raw text log, displaying all output directly from the macan-engine.
Adding URLs in this mode bypasses thumbnail and metadata fetching, allowing for rapid-fire queuing and immediate download.
Queue Context Menu & Multi-Select:
The download table now supports multi-selection of items.
A new right-click context menu has been implemented, providing the following actions:
Play: Opens the completed video or audio file.
Remove from List: Removes selected items from the queue (does not delete the file).
Delete from Disk: Permanently deletes the downloaded file from your computer (a confirmation prompt is shown).
🐞 Fixed
"Stop Download" Button Logic:
Resolved a major bug where the "Stop Download" button would not correctly terminate the download queue.
The button now immediately kills the active download process, marks the stopped item as "Error," and reliably prevents the next item in the queue from starting automatically.
File Path Parsing:
Fixed a critical error where file paths containing quotes or trailing spaces were not parsed correctly. This ensures that files are found and can be played after a successful download.
Asset Path Portability:
Corrected the pathing logic for icons and assets. The application will now correctly load all icons regardless of the directory it is run from, improving portability.
🛠️ Changed / Improved
Translation Engine:
The internal internationalization (i18n) function has been upgraded to be more robust, improving support for default text and formatted strings.
UI Refactoring:
Refactored the logic for updating and rebuilding the queue table, resulting in more stable performance, especially when removing items from the list.
Styling:
Updated the application's stylesheet to support the new CLI view, table selection colors, and the context menu for a consistent dark-mode experience.

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
