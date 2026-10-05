# Better-Lyrics

Better-Lyrics is a library for parsing and managing TTML lyrics, including word-by-word synchronization support, used in the N-Zik project.

> **Note:** This project is a fork of the Better Lyrics implementation originally created by **[MetroList](https://github.com/MetrolistGroup/Metrolist)**. 

[![License: GPL v3](https://img.shields.io/github/license/N-Zik-Group/Better-Lyrics?color=blue)](https://www.gnu.org/licenses/gpl-3.0) [![CodeFactor](https://www.codefactor.io/repository/github/n-zik-group/better-lyrics/badge)](https://www.codefactor.io/repository/github/n-zik-group/better-lyrics)

## Features
- Parses TTML (Timed Text Markup Language) lyrics
- Built in Kotlin

## Integration
This library is designed to be added as a submodule in Android projects.

```groovy
// settings.gradle.kts
include(":betterlyrics")

// build.gradle.kts (app)
implementation(projects.betterlyrics)
```
