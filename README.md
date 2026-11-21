# lithuania-driving-test-# Lithuania Driving Test – KET (Android starter with 300-question bank)

## Included
- Native Kotlin + Jetpack Compose Android project.
- 300 original English Category B practice question entries, each with four answer choices, correct answer index, and explanation.
- Practice and random 30-question mock-test flow.
- Mock-test pass threshold: 24/30.
- Session mistake tracking and basic progress screen.
- Language selector for English, Hindi and Punjabi. The 300-question bank is currently English; the existing UI falls back to English for untranslated bank entries. Hindi and Punjabi translation/review is a required next step.

## Build
1. Install Android Studio on Windows, macOS or Linux.
2. Extract the ZIP and open this folder in Android Studio.
3. Allow Gradle sync to complete.
4. Connect the Motorola Moto G05 with USB debugging enabled, or use an emulator.
5. Press Run.

This is source code, not an APK or a Play Store release. It has not been compiled or device-tested in this environment.

## Content and legal note
The questions are original study prompts; they are not official Regitra questions and are not copied from ARV or another commercial question bank. The subject coverage follows the published theory-exam syllabus and public road-traffic rules. The questions are a learning draft and must be checked against the current Lithuanian legal text by a qualified reviewer before publication. This app is independent and is not affiliated with Regitra or any Lithuanian government authority.

Official references:
- Lithuanian Road Traffic Rules, consolidated version from 1 January 2026: https://sumin.lrv.lt/public/canonical/1776407758/16319/Road%20Traffic%20Rules%20%28Consolidated%20version%20from%201%20JANUARY%202026%29.pdf
- Official theory-question composition scheme in the Lithuanian legal acts register: https://www.e-tar.lt/rs/actualedition/aea13330783211eb9601893677bfd7d8/lOWMaOgNNr/

## Build an APK for free with GitHub Actions

This project includes `.github/workflows/build-apk.yml`. To create a downloadable debug APK without installing Android Studio locally:

1. Create a free account at GitHub and create a **public** repository.
2. Upload the complete contents of this project folder to the repository (the `.github/workflows` folder must be included).
3. Open the repository's **Actions** tab. Select **Build Android APK** and choose **Run workflow** (or wait for the first push build to finish).
4. Open the completed workflow run and download the artifact named **Lithuania-Driving-Test-KET-debug-apk**.
5. Extract the downloaded artifact ZIP; it contains the `.apk` file. Transfer it to the Android phone and install it. Android may ask you to allow installation from that source.

The workflow builds a debug APK for testing. It is not a Play Store release build and is not a permanent public download URL. GitHub Actions artifacts are temporary (30-day retention in this workflow). For a permanent public APK link, publish a tested release through the repository's **Releases** page. Keep any future release-signing keystore and passwords private; never commit them to a public repository.
