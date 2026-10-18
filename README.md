# Boundary Cricket — Android Studio project

## What is included
- Android WebView app shell (Java)
- International match home screen with Live / Results filters
- Sample match cards
- Manual scoring controls: 0, 1, 2, 3, 4, 6, wide, no-ball, bye, wicket
- Undo, swap batters, reset, batting order, bowling figures and full scorecard
- Responsive HTML/CSS/JavaScript UI

## Open and build
1. Install Android Studio.
2. Choose **Open** and select this `BoundaryAndroid` folder.
3. Let Gradle sync complete (Android SDK Platform 35 and a compatible JDK may be requested).
4. Use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Install the generated APK on your Android device.

## Important live-data note
This version uses sample match cards and manual scoring. It does not connect to a verified live cricket data provider yet. A cricket API key and an API integration are required for real international scores. Do not put private API keys in client-side JavaScript in a production app; use a backend proxy.
