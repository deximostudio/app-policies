# Privacy Policy for Soloclip

**Last updated:** October 1, 2026  
**Developer:** Deximostudio  
**App:** Soloclip (`studio.deximo.soloclip` on Android)

## Overview

Soloclip is a local-first clipboard history app for Android. We do not operate servers that store your clips. Clipboard text stays on your device unless you choose to export or share it.

## Information we collect

**We do not collect, sell, or share your clipboard contents.**

Soloclip does not use advertising, analytics, or crash-reporting SDKs. We do not receive your clips, pins, search queries, or settings on our servers. There is no Soloclip account.

## How capture works

Soloclip records **text only**, and only in these cases:

- You use the Soloclip keyboard
- You bring the Soloclip app into focus
- You share text into the app
- You add a clip yourself

It does **not** sniff the clipboard in the background. It does **not** use Accessibility to capture clipboard contents.

The Soloclip keyboard is an insert panel for clips you already saved. It is not a keylogger of other keyboards.

## Information stored on your device

The app stores the following locally on your device:

- Clipboard history (plain text clips, source, timestamps)
- Pins, snippet folders, and related labels you create
- App settings (retention, language, keyboard / Quick Settings / tray preferences)
- A local cache of Soloclip unlock purchase status (for offline use)

Android Auto Backup is turned off for this app (`allowBackup` is false). Uninstalling still removes local app data, subject to any other copies you made (for example an export).

## Sensitive clips

Onboarding and Settings disclose this behavior:

- One-time codes (OTP-like 4–8 digit tokens) can be excluded from history (default) or kept only briefly
- Password-like text that is stored expires after at most 5 minutes
- On Android 13+, clips the system flags as sensitive are not captured

This filtering runs on the device. It is best-effort (heuristics, plus Android’s own sensitive flag). It is not a guarantee that every secret will be detected.

Unpinned clips auto-clear after a retention period you can change (default 30 days). Pinned clips are not auto-cleared. You can wipe all local data in Settings.

## Permissions you may grant

Soloclip only uses permissions and system features needed for the functions you choose:

- **Notifications** — if you enable the optional notification tray of recent clips
- **Input method (keyboard)** — if you enable the Soloclip keyboard in system settings, so you can insert clips
- **Quick Settings tile** — if you add the Soloclip tile yourself
- **Network** — for purchase / restore with Google Play (see below), and if you open a link you choose (for example this policy)

You can deny notifications and skip the keyboard, tile, or tray; core in-app history still works.

## Purchases (Soloclip unlock)

Unlimited history, pins, the keyboard insert panel, and the Quick Settings pinned strip are unlocked with a one-time in-app purchase processed by Google Play Billing.

When you purchase or restore:

- Google processes the payment
- Google may receive purchase / entitlement information needed to unlock the app on that Play account
- Your clipboard contents are not sent to Deximostudio as part of purchase

Google’s privacy policy applies to store transactions. Deximostudio does not store your payment card details.

## Optional network use

Clipboard history works offline. The app may use the network when you:

- Purchase or restore the unlock
- Open a link you choose (for example this privacy policy)

Those requests do not upload your clips to Deximostudio.

## Sharing and export

Export (JSON or CSV) and share-in are **user-initiated**. Files you export leave the app only through the system share sheet or paths you choose. Deximostudio does not receive those files.

Sensitive and short-TTL clips are excluded from export.

## Data deletion

You can wipe all clips, pins, and folders in Settings. Uninstalling the app also removes local app data from your device. There is no Soloclip cloud account to delete because we do not host your clipboard.

See [Delete your data](delete-data.md) for Play Data safety details.

## Children’s privacy

Soloclip is not directed at children under 13, and we do not knowingly collect personal information from anyone.

## Changes

We may update this policy. The “Last updated” date at the top will change when we do.

## Contact

Questions about this policy: [GitHub Issues](https://github.com/deximostudio/holdplain/issues)
