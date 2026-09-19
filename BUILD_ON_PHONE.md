STORYTOK APK BUILD — PHONE METHOD

1. Create/sign in to a GitHub account.
2. Create a new repository named StoryTok.
3. Upload ALL files/folders from this project ZIP into the repository.
4. Open the Actions tab.
5. Choose "Build StoryTok APK".
6. Tap "Run workflow".
7. Wait for the green check.
8. Open the completed workflow run.
9. Under Artifacts, download "StoryTok-debug-apk".
10. Extract it and install app-debug.apk on your Android phone.

The workflow uses GitHub Actions + Gradle to build the APK in the cloud.
This debug APK is for testing; a Play Store release needs a properly signed release build/AAB.

The project is still a prototype: online accounts, cloud video storage, real moderation,
notifications and payments are not implemented yet.
