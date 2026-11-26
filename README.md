# AB Kids Fun Games

A colourful, offline-first Android learning game for children aged 3–7.

## Included in version 1
- Animal Memory Match
- Alphabet Adventure
- Number Fun
- Shape Puzzle

## Privacy and child safety
- No advertising SDKs.
- No accounts or sign-in.
- No analytics or tracking SDKs.
- No internet permission is requested by the app.
- No location, contacts, camera, microphone, or storage permissions are requested.
- Game progress is not uploaded to a server.

Review `PRIVACY_POLICY.md` and replace the contact placeholder before publishing. Complete the Google Play Families, Data safety, content rating, and target audience declarations accurately. This project is a starter release and must be tested on physical devices before publication.

## Build an APK
This repository includes a GitHub Actions workflow at `.github/workflows/android.yml`.
After uploading the project to GitHub, open the **Actions** tab and run or wait for **Build Android APK**. Download the `AB-Kids-Fun-Games-debug-apk` artifact from the successful workflow run.

The build uses Java 17, Android Gradle Plugin 8.10.1, Gradle 8.11.1, and Android SDK 36.

## Package
`com.abkidsfungames`
