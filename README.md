# Better-Lyrics

Better-Lyrics is a library for parsing and managing TTML lyrics, including word-by-word synchronization support, used in the N-Zik project.

> **Note:** This project is a fork of the Better Lyrics implementation originally created by **[MetroList](https://github.com/MetrolistGroup/Metrolist)**. 

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
