# Own Chat Android APK

Android WebView wrapper for `https://own.akhlas.net/`.

## Build on GitHub
1. Create a GitHub repository.
2. Upload this project to the repository's `main` branch.
3. Open **Actions → Build Own Chat APK → Run workflow**.
4. Download the `own-chat-debug-apk` artifact.

The APK requests camera, microphone and notification permissions so the web app can use media features where supported by the website.

## Important
The PHP/MySQL backend remains on `own.akhlas.net`; this Android project is only the mobile client. The website must be HTTPS and its upload/audio endpoints must work correctly on mobile browsers/WebView.
