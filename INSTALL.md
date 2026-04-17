# Message Scheduler - Installation & Setup Guide

Message Scheduler allows you to schedule SMS messages to be sent automatically at a later time or on a recurring basis.

## Installation Instructions

1. **Download the Release**:
   - Go to the **Releases** page of this repository on GitHub.
   - Download the latest `message_scheduler_release.apk` from the **Assets** section of the latest release.

2. **Install on Android Device**:
   - Transfer the `app-release.apk` file to your Android device.
   - On your device, open your File Manager and tap the APK file to install it.
   - If prompted, allow installation from "Unknown Sources".

## Enabling SMS Permissions (Restricted Settings)

On newer versions of Android (Android 13+), some permissions (like SMS) are considered "Restricted Settings" when an app is side-loaded (installed via APK instead of Play Store). You must manually allow these restricted settings before the app can request the SMS permission.

### Step 1: Allow Restricted Settings
1. Open **Settings** on your Android device.
2. Go to **Apps** (or **Manage Apps**).
3. Find and tap on **Message Scheduler** in the list.
4. Look for the **three dots (⋮)** in the top-right corner of the App Info screen.
5. Tap on **Allow restricted settings**.
6. Confirm with your device PIN, pattern, or fingerprint.

### Step 2: Enable App Permissions
1. Once restricted settings are allowed, stay on the **App Info** screen for Message Scheduler.
2. Tap on **Permissions**.
3. Tap on **SMS** and select **Allow**.
4. (Optional) Also tap on **Contacts** and select **Allow** if you want to pick recipients from your contact list.

## Usage Guide
1. **Schedule a Message**:
   - Open the app and navigate to the **Schedule** tab.
   - Enter a phone number or pick a contact using the icon.
   - Type your message body.
   - Select the date and time.
   - (Optional) Set a recurring interval (Daily, Weekly, etc.).
   - Tap **Schedule Message**.

2. **Manage Messages**:
   - View pending or paused messages in the **Scheduled** tab.
   - Use the **Pause/Play** icon to temporarily stop or resume a message.
   - Use the **Edit** (pencil) icon to modify a message.
   - Use the **Delete** (trash) icon to remove a message.

3. **History**:
   - View previously sent or failed messages in the **History** tab.

---
**Note**: Ensure your phone has an active SIM card and enough credit/SMS allowance to send messages. The app must remain installed for scheduled messages to be sent.
