STORE VISIT & TRAVELLING EXPENSE TRACKER

Android project folder: android/

Automated APK build (no Android Studio needed):
1. Create/sign in to a GitHub account.
2. Create a new repository, e.g. store-visit-tracker.
3. Upload the CONTENTS of this project folder to the repository (the .github folder must be included).
4. Open the repository on GitHub and select the Actions tab.
5. Choose "Build Android APK" and click "Run workflow" (or push to main/master).
6. Wait for the workflow to finish successfully.
7. Open the completed workflow run, scroll to Artifacts, and download
   "Store-Visit-Tracker-APK". Extract it to get app-debug.apk.
8. Transfer app-debug.apk to your Android phone and open it to install.
   If Android asks, allow installation from that source.

The workflow builds a DEBUG APK for testing/personal use. It is not a signed
Play Store release. Keep the GitHub repository private if you do not want the
source code to be public.

The app stores its visit records locally on the device. Uninstalling the app
or clearing its app data may erase locally stored records; export backups regularly.
