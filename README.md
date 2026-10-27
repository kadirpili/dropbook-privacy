# Privacy Policy

**App Name:** DropBook: PDF to Audiobook (Package ID: `app.dropbook.reader`)  
**Developer:** Kadi Narmamatov (DropBook)  
**Contact Email:** kadirpili@gmail.com  
**Effective Date:** October 27, 2026

## 1. Overview
DropBook ("we", "our", or "the App") is a minimalist audiobook player for Android that converts user-selected document files (.PDF, .EPUB, .TXT) into spoken audio. DropBook does not require user registration, login accounts, names, emails, or phone numbers.

## 2. Information We Access and Collect

### A. User-Selected Document Files (Local Processing & Transient TTS Synthesis)
* **How it works:** When you select a `.pdf`, `.epub`, or `.txt` file using the Android system file picker, the file is read and cleaned locally on your device.
* **Text-to-Speech (TTS) Processing:** Extracted text paragraphs are transmitted securely over HTTPS to cloud Text-to-Speech services (Google Cloud Vertex AI / Gemini API and our dedicated TTS synthesis servers) solely to generate spoken audio streams for playback. We do not permanently store your personal documents or link book contents to your personal identity.

### B. Device Identifiers & Advertising (Google AdMob)
DropBook is offered for free and supported by rewarded video advertisements provided by **Google AdMob** (`com.google.android.gms:play-services-ads`).
* **Data Collected by AdMob:** Google AdMob automatically accesses and collects your device's **Google Advertising ID (`AD_ID`)**, approximate location (derived from IP address), device diagnostics, and ad interaction events (such as video ad views and reward completions).
* **Purpose:** This data is used for serving rewarded ads, measuring ad performance (analytics), and preventing ad fraud.
* **Third-Party Sharing:** Data collected by the Google Mobile Ads SDK is processed by Google in accordance with the [Google Privacy & Terms](https://policies.google.com/privacy).

### C. Anonymous App Functionality & Security (Block Store & App Check)
* **Google Play Services Block Store:** DropBook stores an encrypted, anonymous listening-time token on your device via Google Block Store solely to preserve your remaining free listening minutes across app reinstalls.
* **Firebase App Check (Google Play Integrity):** DropBook uses hardware attestation tokens via Google Play Integrity to verify that audio synthesis requests originate from an authentic Android device and an unmodified version of the App, preventing automated bot abuse.

## 3. Data Security
All network communications between the App and cloud TTS/advertising endpoints are encrypted in transit using industry-standard HTTPS/TLS protocols.

## 4. Data Retention and Deletion Policy
* **No User Accounts:** Because DropBook does not create user accounts or collect personal profile data (such as emails or names), there is no personal account record to delete.
* **Clearing Local Data:** All locally cached audio files (`.wav` / `.m4a`) and reading progress are stored inside the App's local sandbox on your device. You can delete this data at any time by going to **Android Settings -> Apps -> DropBook -> Storage -> Clear Storage / Clear Cache**, or by uninstalling the App.
* **Resetting Your Advertising ID:** You can reset or delete your Google Advertising ID at any time by going to **Android Settings -> Google -> All services -> Ads -> Reset advertising ID / Delete advertising ID**.

## 5. Children's Privacy
DropBook is intended for general audiences aged 13 and older and does not knowingly collect personal information from children under the age of 13.

## 6. Contact Us
If you have any questions about this Privacy Policy or our data practices, please contact us at:  
**Email:** kadirpili@gmail.com
