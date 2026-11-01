# Vantage for Android

Official Android downloads for Vantage. This repository contains installation documentation and release files; the application source is maintained separately.

**No production APK has been published yet.** Signed APKs will appear on the [Releases page](https://github.com/vaatun/vantage-downloads/releases).

## Installation

1. Download `vantage.apk` from a published release on your Android phone.
2. Allow installation from your browser when Android prompts you, then install the APK. You can disable that browser permission afterwards.
3. Open your Vantage website and choose **Already installed? Open it**, or enter your organisation's HTTPS Vantage address in the app.
4. Sign in with your existing Vantage account.

Updates are installed by downloading a newer APK. Updates must retain the same application signing certificate. Each release includes SHA-256 checksums.

## Optional SMS integration

When enabled for your organisation, open **Integrations → SMS** in the Android app and follow the connection prompt. Android asks for permission to receive SMS.

Connecting forwards **all new incoming SMS**, including personal messages and verification codes, to your organisation's Vantage server. Existing inbox messages are not imported. The app does not save SMS messages or retry failed uploads; messages received while offline or during an upload failure are lost to Vantage. The server keeps successfully uploaded messages temporarily, for up to 15 minutes. The phone stores its connection credential securely.

Disconnect through Integrations → SMS or revoke the SMS permission in Android settings. Contact your organisation's Vantage administrator for access and data-handling questions. Do not post SMS contents, credentials or customer data in public issues.
