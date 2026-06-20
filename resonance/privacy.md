# Privacy Policy for Resonance

**Last updated:** June 20, 2026  
**Developer:** Deximostudio  
**App:** Resonance (`com.deximostudio.resonance`)

## Overview

Resonance is a local-first audiobook player for Android and iOS. We do not operate servers that collect your personal data. Your library, listening progress, and settings are stored on your device.

## Information we collect

**We do not collect, sell, or share your personal information.**

Resonance does not use analytics, advertising, crash reporting, or other tracking services. We do not receive your audiobook library, listening history, or account credentials on our servers.

## Information stored on your device

The app stores the following locally on your device:

- Audiobook metadata (title, author, narrator, cover art references)
- Listening progress, bookmarks, and collections
- App settings (e.g. playback speed, Wi‑Fi-only downloads)
- Downloaded audiobook files (if you choose to download)
- Server connection details you enter (server URL, username)

## Credentials and security

If you connect to Jellyfin or Audiobookshelf, your password or API token is stored using platform security:

- **Android:** Android Keystore with EncryptedSharedPreferences
- **iOS:** Keychain

Credentials are used only to connect to servers you configure. They are not sent to Deximostudio.

## Optional connections to your servers

If you add a Jellyfin or Audiobookshelf source, the app communicates directly with **your** server to:

- Sync your library and metadata
- Stream or download audiobooks
- Sync playback progress (when enabled)
- Load cover art

That data goes between your device and your server. We do not access or store it.

## Local file import

If you import audiobooks from your device, the app reads files you select through the system file picker. Those files remain under your control.

## Notifications

The app may show a media playback notification and, with your permission, other notifications related to playback and downloads. No personal data is sent to us through notifications.

## Android backup

On Android, app data may be included in your device's backup if backup is enabled. Backup content is managed by Google or your device manufacturer, not by Deximostudio.

## Data deletion

Uninstalling the app removes local app data from your device. Data on your Jellyfin or Audiobookshelf server is not deleted by uninstalling Resonance.

## Children's privacy

Resonance is not directed at children under 13, and we do not knowingly collect personal information from anyone.

## Changes

We may update this policy. The "Last updated" date at the top will change when we do.

## Contact

Questions about this policy: [GitHub Issues](https://github.com/deximostudio/resonance/issues)
