# CVP Document Management — Android

Android WebView wrapper for the existing CVP Document Management Streamlit application.

## Live app URL
https://cvp-document-management-web-b6ulgpzy72njfwgs3jmpge.streamlit.app/

## Build APK on GitHub
1. Upload the CONTENTS of this folder to the root of the Android GitHub repository.
2. Open **Actions**.
3. Open **Build CVP Android APK**.
4. Choose **Run workflow** (or wait for the automatic push build).
5. After the run turns green, open it and download **CVP-Document-Management-APK** from Artifacts.
6. Extract it to get `CVP_Document_Management.apk`.

The APK is a debug-signed installable APK intended for internal testing/company distribution. Google Play production publishing should use a signed release AAB.
