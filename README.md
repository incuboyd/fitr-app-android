Description
-----------

A pet project to explore technologies including Android, support libraries and the Google Fitness APIs.
Also to explore the best practices in Android, material design and software design patterns for Android projects.

Technologies
------------

- Android (23)
- Support libraries (24.0.0) - design, appcompat
- Play services (9.2.0)
- Dagger
- RXJava (1.1.6)
- MPAndroidChart

Patterns
----------
- Model-View-Presenter
- Observables
- Dependency Injection

Layouts
-------
- DrawerLayout
- TabLayout
- SwipeRefreshLayout
- MPCharts layouts

Setup
-----

1. Goto the Google API console (https://console.developers.google.com/apis/library)

2. Create a new project (Fitr)

3. Enable the Google Fit APIs

4. Create new OAuth client ID credentials with Application type: Android

5. Find your debug keystore fingerprint:

    keytool -list -v -keystore ~/.android/debug.keystore -alias androiddebugkey -storepass android -keypass android

Obviously, you can you another keystore e.g. if you are creating an app release.

6. Add the SHA1 to the OAuth client ID credentials

Run
---

Run directly from Android Studio to a device of emulator.