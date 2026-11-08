Skin Tone Fix - Android project

1. On a PC, install Android Studio (free) from developer.android.com/studio.
2. Unzip this folder. In Android Studio choose File > Open and select the SkinToneFix folder.
3. Wait for Gradle to sync. If it asks about Gradle or the JDK, accept the defaults.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. When it finishes, the APK is at app/build/outputs/apk/debug/app-debug.apk.
6. Copy that file to your phone, open it, and allow installing from this source.

Requires Android 10 (API 29) or newer.
The tool itself is app/src/main/assets/index.html. To change the tool, edit that file and rebuild.
The package name is com.example.skintonefix. Change applicationId in app/build.gradle if you want your own.

No PC? Build the APK in the cloud with GitHub Actions:
1. Create a free account at github.com and a new repository.
2. Upload the contents of this folder (not the folder itself) to the repository root, including the hidden .github folder.
3. Open the repository's Actions tab, choose "Build APK", and press "Run workflow".
4. When the run finishes, download the "skin-tone-fix-apk" artifact. It contains app-debug.apk.
