# On Duty APK - Clean GitHub Build

This package is a clean Android WebView wrapper for the On Duty HTML project.

## Upload to GitHub
Upload the contents of this folder to the root of your repository.

Important files/folders:
- `.github/workflows/android.yml`
- `app/`
- `build.gradle`
- `settings.gradle`
- `gradle.properties`

## If `.github` does not show on your computer
Create this file directly in GitHub:
- `.github/workflows/android.yml`

Then copy the content from:
- `WORKFLOW_COPY_IF_GITHUB_HIDDEN.txt`

## Build
Open **Actions** in GitHub and run **Build Android APK**.

The output artifact contains `app-debug.apk`.
