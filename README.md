TinyApp - Minimal Android "Hello" app

This repository contains a minimal Android project (Kotlin + AppCompat) with a single activity that displays a greeting in Arabic.

How to build & run:

1. Open in Android Studio: File → Open → select this project folder.
2. Or from command line:
   - Generate Gradle wrapper if you don't have it: `gradle wrapper --gradle-version 7.5.1`
   - Build: `./gradlew assembleDebug`
   - Install on device: `adb install -r app/build/outputs/apk/debug/app-debug.apk`

