# Privacy Policy for Clackey – Typewriter Keyboard

**Effective Date:** October 10, 2026  
**Application:** Clackey – Typewriter Keyboard (`com.clackey.keyboard`)  
**Developer:** Clackey Team  
**Contact:** fari.dev.contact@gmail.com 

---

## 1. Our Privacy Promise to You

At Clackey, we believe that typing on your phone is deeply personal. Your thoughts, private conversations, passwords, notes, and dictation belong solely to you.

We built Clackey with a fundamental commitment: **complete on-device privacy**. Clackey does not collect, record, track, transmit, or monetize your keystrokes, voice recordings, personal messages, passwords, or personal data. 

---

## 2. What We Never Collect or Store

We maintain a strict zero-collection standard across all typing and dictation features:

- **No Keystroke Recording:** We never record, log, or store the letters, words, or numbers you type. When you press a key, the character is passed directly to the active app via Android's InputConnection and is never saved by Clackey.
- **No Voice or Audio Recording Storage:** Voice dictation streams audio directly and ephemerally to your device's built-in speech recognition service. Clackey never saves, logs, or uploads your voice, speech transcripts, or audio samples to any external servers.
- **No Personal Identifiers:** We do not collect your name, email address, phone number, location, or device identifiers. Clackey requires no account creation, sign-in, or user registration.
- **No Tracking or Analytics:** Clackey contains zero background analytics SDKs, diagnostic telemetry beacons, or user tracking code. We do not monitor how fast you type, what words you write, or how often you use the keyboard.
- **No Advertising or Profiling:** We do not display ads, sell data, or build behavioral advertising profiles based on your activity.

---

## 3. How Your Data Stays on Your Device

All personalizations, layout preferences, and typing conveniences exist solely on your phone:

### A. Your Personal Dictionary
- Custom words and shorthand expansions you add are saved locally in private app storage.
- Your personal dictionary never leaves your device and is never synced to any remote servers. You can view, edit, or delete words anytime in Clackey Settings.

### B. Clipboard History & Auto-Clear
- If you use Clackey's optional clipboard feature, recently copied text items and smart chips (such as phone numbers or URLs) are stored strictly inside the app on your phone.
- **Automatic Privacy Clearing:** You can configure copied items to automatically erase after 30 seconds, 1 minute, or 5 minutes so sensitive information (such as two-factor verification codes) does not linger in clipboard history.
- You can clear your clipboard history at any time with a single tap.

### C. Passwords, PINs & Sensitive Fields
- When you type into password fields, PIN entries, credit card boxes, or incognito browsing tabs, Clackey automatically suppresses word predictions and clipboard suggestions to keep your private credentials completely protected.

### D. 100% Offline Local Backup & Restore
- Clackey offers a complete, offline Backup & Restore utility using Android's Storage Access Framework (SAF).
- Backup archives (`.json`) are created only when you explicitly export them to a file location of your choice on your device or personal storage.
- Clackey never uploads backups to the cloud, has no access to external cloud accounts, and processes restores completely offline with schema validation.

---

## 4. Voice Typing & On-Device Speech Dictation

Clackey includes a mechanical-themed voice dictation interface:

- **On-Device Speech Recognition Priority:** Dictation prioritizes on-device speech recognition models (`EXTRA_PREFER_OFFLINE`) provided by your Android operating system.
- **Direct Ephemeral Audio Stream:** Microphone audio is routed directly to Android's system `SpeechRecognizer` API during an active recording session. Clackey does not buffer, retain, or store voice data on disk or in memory after the dictation session concludes.
- **Explicit User Control:** The microphone is only accessed when you deliberately tap the microphone key or toolbar voice action, accompanied by visual recording feedback.

---

## 5. Offline Multi-Language Packs & Layouts

Clackey supports 8 localized layouts (English QWERTY, French AZERTY, German QWERTZ, Spanish with dedicated Ñ, Italian, Portuguese, Dutch, and Hindi Devanagari):

- All layout matrix definitions, accent mappings, and dictionary engines are 100% bundled locally within the application package.
- Switching languages or cycling layouts requires zero internet connectivity and downloads zero external assets.

---

## 6. Optional Internet Features

Clackey is designed to operate 100% offline. The only optional features that utilize internet connectivity are:

### A. Expressive GIF Search (GIPHY)
- An internet connection is used exclusively when you actively open the GIF panel and enter a search query.
- Only the specific search term you type into the GIF search box is sent to fetch animations. Your normal typing, messages, clipboard history, and identity are never transmitted.
- Use of GIF search is subject to [GIPHY's Privacy Policy](https://giphy.com/privacy).

### B. Community Feedback & Roadmap (Fedo)
- An optional in-app feedback and feature-voting board in Settings powered by [Fedo](https://getfedo.com).
- Only contacts the network when you deliberately open **Settings → Feedback & Community Roadmap** or submit a suggestion from **Help & Support**.
- Only the feedback text (title, description, optional contact details) and anonymous vote counts you choose to submit are transmitted. The feedback module has zero access to your keyboard typing or keystrokes.

---

## 7. In-App Purchases & Google Play Billing

- Clackey offers an optional one-time purchase ("Collector's Starter Pack") for exclusive themes and mechanical sound profiles.
- Transactions are handled exclusively via the official **Google Play In-App Billing** service (`com.android.billingclient`).
- Clackey never handles, processes, accesses, or stores your credit card details, banking information, or billing address. All payment details are managed securely by Google according to the [Google Play Terms of Service](https://play.google.com/intl/en_us/about/play-terms/).
- Entitlements are cached locally on your device with cryptographic HMAC validation to verify unlocked status offline.

---

## 8. Device Permissions Explained

Android requires keyboard apps to request certain permissions to function. Here is why Clackey requests them:

| Permission | What It Does for You | Requirement |
|---|---|---|
| **Input Method Service** | Allows Android to use Clackey as your active keyboard across all your apps. | Required for all keyboards |
| **Microphone (`RECORD_AUDIO`)** | Used exclusively for real-time speech dictation when you tap the Voice button. Audio is streamed directly to the system speech recognizer and is never saved. | Optional (Only when Voice Typing is used) |
| **Internet Access (`INTERNET`)** | Used only to fetch animated GIFs when you search in the GIF tab and for user-initiated feedback via Fedo. Normal typing is 100% offline. | Optional (Typing works 100% offline) |
| **Photos & Media (`READ_MEDIA_IMAGES` / `READ_EXTERNAL_STORAGE`)** | Only used if you turn on the optional feature to preview recently copied screenshots in your clipboard bar. Photos never leave your device. | Optional (Off by default) |
| **Storage Access Framework (SAF)** | Allows you to select a local folder to export or import your offline JSON backup archives. Clackey accesses only the file you explicitly select. | Optional (Only when backing up or restoring) |

---

## 9. Your Rights & Data Control

You are in total control of your data at all times:

- **Delete Your Data:** You can delete your custom dictionary words or wipe your clipboard history directly from Clackey Settings.
- **Export & Import:** You can export all your preferences, custom dictionary words, and pinned clips into a local JSON backup file anytime, or restore it onto another device.
- **Full App Reset:** Clearing Clackey's storage in your Android System Settings permanently erases all local settings, words, and history.
- **No Cloud Account:** Because we do not store your data on external servers, there are no remote accounts or server profiles to delete.

---

## 10. Children's Privacy

Clackey does not collect personal information from any user, including children under 13 (or applicable age in your jurisdiction). The application is family-friendly, ad-free, and safe for typists of all ages.

---

## 11. Policy Updates

If we update this Privacy Policy, the revised version will be accessible directly within the app under **Settings → About & Legal → Privacy Policy** and reflected in this repository with an updated effective date.

---

## 12. Contact Us

If you have questions, suggestions, or feedback about Clackey's privacy protections, we would love to hear from you:

**Clackey Privacy Team**  
Email: fari.dev.contact@gmail.com  
GitHub: [Hadi99K/clackey-typewriter-keyboard-app](https://github.com/Hadi99K/clackey-typewriter-keyboard-app)
