# Resonance Local
Android local-media player published by Northcom LTD.

This edition has no page-link downloader, web-stream extractor or embedded web player. Local playback, video files, recording, conversion, lyrics, playlists, themes and vocal/instrumental separation remain available.

## Build
Use JDK 21, Android SDK 36, build-tools 36.0.0, NDK 29.0.14206865 and CMake 3.22.1. Set JAVA_HOME and ANDROID_HOME for your own machine.

Run `./gradlew :app:testDebugUnitTest :app:assembleDebug` (Windows: `gradlew.bat`).
Run `./gradlew -PgoogleMonetization=true :app:assembleDebug` for the Google test integration.
The default build is SDK-free. Release signing keys are deliberately excluded.
The Google production gate remains until live account/ad-unit IDs, billing and privacy configuration are verified.

Separation and MP3 native libraries build directly from the included source. The unchanged ONNX runtime inputs are included with hashes and source provenance. See docs/SOURCE_RELEASE_README.txt.

## Licences and source
Original code is GPL-3.0-or-later with GOOGLE-LINKING-PERMISSION.txt. Third-party terms remain unchanged. See LICENSE, LICENSING.txt and the in-app licence catalogue.

Download matching source archives from [Releases](https://github.com/alanrasc/resonance-local/releases). Use the attached named source package, not an automatically generated archive of this landing-page repository.

Support: northcom@northcomtech.com

