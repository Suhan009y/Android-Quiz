# Paper Key Offline Android

This is an Android project with the bundled question bank and local-only quiz assets.

## Build APK

The repository includes a GitHub Actions workflow at `.github/workflows/build-apk.yml`.
After pushing the project to a GitHub repository, open **Actions → Build Paper Key APK → Run workflow** (or push to `main`). When the workflow succeeds, open its run and download the `PaperKey-debug-apk` artifact. Extract it on your phone to get `app-debug.apk`, then install it and approve installation from your browser/files app if Android asks.

The first build requires internet access. The installed app is designed to use bundled assets and does not require internet for quiz use.
