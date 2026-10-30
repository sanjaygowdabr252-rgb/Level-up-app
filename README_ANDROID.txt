LEVEL UP — Premium Black & Gold Android project starter

WHAT IS INCLUDED
- www/index.html: habit tracker prototype with premium black/gold theme
- manifest.webmanifest and sw.js: installable/offline-capable web app support
- package.json and capacitor.config.json: Capacitor Android wrapper configuration

IMPORTANT LIMITATION
This is an Android-ready project starter, not a compiled APK. An APK must be built using
Node.js, Capacitor, Android Studio and the Android SDK on a computer.

BUILD STEPS (on a computer)
1. Install Node.js LTS and Android Studio (including Android SDK).
2. Extract this ZIP and open a terminal in the extracted folder.
3. Run: npm install
4. Run: npx cap add android
5. Run: npx cap sync android
6. Run: npx cap open android
7. In Android Studio, wait for Gradle sync, then Build > Build Bundle(s) / APK(s) > Build APK(s).

DATA NOTE
The current prototype saves to browser/device local storage. This is not cloud sync.
Export a JSON backup before clearing app/browser storage.
