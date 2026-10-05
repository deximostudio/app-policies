# Privacy Policy for Filetray

**Last updated:** October 5, 2026  
**Developer:** Deximostudio  
**App:** Filetray (`com.deximoapps.filetray` on Android)

## Overview

Filetray is a local-first OCR PDF scanner for Android. We do not operate servers that store your scans, PDFs, or recognized text. Camera capture, gallery import, folders, tags, search, and OCR run on your device. Papers stay on this phone unless you choose to share or save them.

## Information we collect

**We do not collect, sell, or share your documents.**

Filetray does not use advertising, analytics, or crash-reporting SDKs. We do not receive your page images, PDFs, titles, tags, folders, search queries, or OCR text on our servers. There is no Filetray account.

## How scanning and OCR work

- **Camera / gallery** — Filetray only sees photos you capture in the scanner or import from the picker. It does not browse your photo library in the background.
- **On-device OCR** — Text recognition uses Google ML Kit on this device (Latin text model). Page images are not uploaded to Deximostudio to be read. Play services may download the recognition model onto the device at install or first use.
- **Searchable PDF** — When a PDF is assembled, it is written in Filetray’s private app storage on this phone.

OCR on the free library is limited (one try). Filetray Lifetime unlocks OCR for the whole library. That entitlement is a Play purchase (see below), not a cloud account.

## Information stored on your device

The app stores the following locally on your device:

- Scanned and imported page images
- Multi-page PDFs you generate
- Document titles, folders, tags, and timestamps
- On-device OCR text and a local search index
- App settings (including first-run onboarding)
- A local cache of Filetray Lifetime purchase status (for offline use)

Android Auto Backup is turned off for this app (`allowBackup` is false). Uninstalling still removes local app data, subject to any other copies you made (for example a PDF you saved or shared).

## Permissions you may grant

Filetray only uses permissions and system features needed for the functions you choose:

- **Camera** — to scan pages (optional; you can import photos instead)
- **Photos / media** — to import images you select
- **Network** — for purchase / restore with Google Play (see below), optional download of the on-device OCR model and UI fonts via Google Play services, and if you open a link you choose (for example this policy)

You can deny the camera and still import from the gallery where the platform allows.

## Purchases (Filetray Lifetime)

Unlimited documents and OCR for the whole library are unlocked with a one-time in-app purchase processed by Google Play Billing (`filetray_lifetime`). There is no subscription.

When you purchase or restore:

- Google processes the payment
- Google may receive purchase / entitlement information needed to unlock Filetray Lifetime on that Play account
- Your documents are not sent to Deximostudio as part of purchase

Google’s privacy policy applies to store transactions. Deximostudio does not store your payment card details.

## Optional network use

The document library works offline. The app may use the network when you:

- Purchase or restore Filetray Lifetime
- Download the on-device OCR model or UI fonts through Google Play services
- Open a link you choose (for example this privacy policy)

Those requests do not upload your papers to Deximostudio.

## Sharing and export

Share PDF and Save to Files are **user-initiated**. Files you export leave the app only through the system share sheet or paths you choose. Deximostudio does not receive those files.

Free and Lifetime exports are not watermarked.

## Data deletion

You can delete individual documents in the app. Uninstalling Filetray removes the local library from that device. There is no Filetray cloud account to delete because we do not host your papers.

See [Delete your data](delete-data.md) for Play Data safety details.

## Children’s privacy

Filetray is not directed at children under 13, and we do not knowingly collect personal information from anyone.

## Changes

We may update this policy. The “Last updated” date at the top will change when we do.

## Contact

Questions about this policy: [GitHub Issues](https://github.com/deximostudio/scanstack/issues)
