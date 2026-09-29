# Build Chrona APK from your Android phone

You do not need a PC. The included GitHub Actions workflow builds the APK in the cloud.

## Phone-only steps
1. Create/sign in to a GitHub account in Chrome.
2. Create a new repository, for example `ChronaAndroid`.
3. Upload **all files and folders** from this project to the repository. Make sure `.github/workflows/build-apk.yml` is included.
4. Open the repository → **Actions** → **Build Chrona APK** → **Run workflow**.
5. Wait for the workflow to finish with a green check.
6. Open the completed workflow run and scroll to **Artifacts**.
7. Download `Chrona-debug-apk` on your phone and extract it.
8. Tap `app-debug.apk` and allow Chrome/Files to install unknown apps if Android asks.
9. Install and open **Chrona**.

## Important
This is a debug APK for personal testing, not a Play Store release build. For Play Store publishing, create a signed release build and add a privacy policy, app icon, package details, and production features.
