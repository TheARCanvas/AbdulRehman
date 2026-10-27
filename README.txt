STAY HERE! — APK BUILD PACKAGE

WHAT THIS IS
This project builds an Android Trusted Web Activity wrapper for:
https://stayhere.base44.app/

The APK loads the live website and requires an internet connection. It is not an offline/native rewrite. The separate 40-test report covers the web app, not the Android APK.

BUILD
Open the repository's Actions tab and select “Build APK”. The workflow starts on pushes to main and can also be run manually. When it finishes, download the “StayHere-APK” artifact, extract it, and install app-debug.apk on an Android phone.

IMPORTANT
- This is a DEBUG APK for testing, not a Play Store release build.
- Website features such as sign-in, uploads, microphone/camera, notifications, and calling depend on site configuration and Android/browser permissions.
- Full-screen Trusted Web Activity presentation may require Digital Asset Links for the domain and signing certificate; otherwise Chrome may show browser UI.
- Do not commit passwords, API keys, signing keys, or tokens.
