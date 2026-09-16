# youtubedl-android-maintained

> **Note:** This is an actively maintained archive/fork of the original `youtubedl-android` library. Since the original projects were abandoned, this repository aims to keep the library alive, updated, and accessible for the Android open-source community.

Android library wrapper for [yt-dlp](https://github.com/yt-dlp/yt-dlp) executable.

[![](https://jitpack.io/v/android-development-tools/youtubedl-android-maintained.svg)](https://jitpack.io/#android-development-tools/youtubedl-android-maintained)

## Credits
* [youtubedl-java](https://github.com/sapher/youtubedl-java) by sapher
* Original Android wrapper by [yausername](https://github.com/yausername) and [JunkFood02](https://github.com/JunkFood02). 
* This repository continues their great work by providing up-to-date binaries and maintenance.

<br/>

## Installation (via JitPack)

**Step 1:** Add the JitPack repository to your build file.
In your `settings.gradle.kts` (or project level `build.gradle`):
```kotlin
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        maven { url = uri("[https://jitpack.io](https://jitpack.io)") }
    }
}
