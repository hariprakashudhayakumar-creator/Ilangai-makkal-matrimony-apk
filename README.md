# Ilangai Makkal Matrimony Android APK

A basic Android WebView app that opens https://ilangaimakkalmatrimony.com/.

## Build the APK from an Android phone using GitHub Actions (free tier)

1. Download and extract this ZIP on your Android phone.
2. In Chrome, sign in to GitHub and create a **new public repository** named `ilangai-makkal-matrimony-app`.
3. Upload the extracted project files and folders to the repository, preserving the folder structure. Make sure `.github/workflows/build-apk.yml` is included.
4. Open the repository's **Actions** tab. If asked, enable GitHub Actions.
5. Choose **Build Ilangai Makkal Matrimony APK** on the left, then tap **Run workflow**. (A push to `main` also starts a build.)
6. Wait for the workflow to finish with a green check.
7. Open the completed workflow run, scroll to **Artifacts**, and download `Ilangai-Makkal-Matrimony-APK`.
8. Extract the downloaded artifact ZIP to get `app-debug.apk`. Tap it to install. Android may ask you to allow Chrome/Files to install unknown apps; only allow this for the file you intentionally built.

## Notes
- This is a debug APK suitable for testing and direct sharing, not a Play Store release.
- The app requires internet and displays the existing website; it does not copy the website or its database into the APK.
- GitHub Actions usage is subject to GitHub account limits and policies. No payment is required for the basic public-repository workflow.
- Do not upload passwords, signing keys, private API keys, or personal data to the repository.
