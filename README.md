# yt-dlp Android (Maintained)

[![Release](https://jitpack.io/v/android-development-tools/youtubedl-android-maintained.svg)](https://jitpack.io/#android-development-tools/youtubedl-android-maintained)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Android API](https://img.shields.io/badge/API-21%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=21)
[![Kotlin](https://img.shields.io/badge/Kotlin-Compatible-orange.svg)](https://kotlinlang.org/)

> **Notice:** This is an actively maintained fork of the original `youtubedl-android` project. It provides a robust, up-to-date Android wrapper for the [yt-dlp](https://github.com/yt-dlp/yt-dlp) executable, ensuring compatibility with modern Android architectures and the latest YouTube changes.

---

## 📖 Table of Contents
- [Features](#-features)
- [Installation](#-installation)
- [Configuration](#%EF%B8%8F-configuration)
- [Usage](#-usage)
- [Advanced Options](#-advanced-options)
- [Credits & Acknowledgments](#-credits--acknowledgments)
- [License](#-license)

---

## ✨ Features
* **Bundled Execution:** Includes Python 3.8 and the latest `yt-dlp` executable.
* **Modern Architecture:** Built for modern Android development with full Kotlin support.
* **Asynchronous Processing:** Built-in callback system for progress tracking and ETA.
* **Optional Modules:** Support for FFmpeg (media conversion) and Aria2c (faster downloads).

---

## 📦 Installation

This library is distributed via [JitPack](https://jitpack.io).

### Step 1: Add the JitPack Repository
Add the repository to your root `settings.gradle.kts` (or project-level `build.gradle`):

```kotlin
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        maven { url = uri("[https://jitpack.io](https://jitpack.io)") }
    }
}
