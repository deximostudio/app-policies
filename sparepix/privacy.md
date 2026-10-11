# Privacy Policy for SparePix

**Last updated:** October 11, 2026  
**Developer:** Deximostudio  
**App:** SparePix (`com.deximoapps.sparepix` on Android and iOS)

## Overview

SparePix is a local-first photo similar and screenshot-sweep app for Android and iPhone. We do not operate servers that store your photos. Scan, grouping, review, and delete run on your device. Photos stay on this phone unless you choose to share or delete them through Android or iOS.

## Information we collect

**We do not collect, sell, or share your photo library.**

SparePix does not use advertising, analytics, or crash-reporting SDKs. We do not receive your photos, hashes, group lists, search of your library, or settings on our servers. There is no SparePix account.

## How scanning works

- **Photo access** — SparePix only looks at photos you grant. That may be the full library (Photos / media permission) or a set you pick (Android Photo Picker / selected photos, or Limited Access on iPhone). If access is partial, the app scans only that set and says so in the UI.
- **On-device similar groups** — Lookalikes and duplicates are found on this phone using perceptual hashes and related metadata. Pixels are not uploaded to Deximostudio to be compared.
- **Screenshot sweep** — Screenshots are grouped on the device: on Android from MediaStore paths and heuristics (for example the Screenshots album), on iPhone from the screenshot flag the Photos library already holds.
- **Not-on-device originals** — If a photo’s pixels are not available locally (for example an undownloaded cloud original, including iCloud Photos originals that are not on the iPhone), SparePix skips it or tells you it needs the photo on this phone. That is not the same as uploading to our cloud. We do not operate a Deximostudio image server.

On Android, a scan can run in the background with a foreground notification while it is in progress. On iPhone, a scan runs while the app is open and nothing is downloaded from iCloud.

## Information stored on your device

The app stores the following locally on your device:

- A local index of granted photos (ids, display names, dates, sizes, album paths)
- On-device hashes used to find similar groups
- Similar groups, screenshot-month stacks, and your keep / delete marks
- Scan progress and access mode
- A local cache of lifetime unlock and free-delete counts (for offline use)

The original photo files stay in your Android gallery or iPhone Photos library. SparePix does not copy your library to Deximostudio.

## Permissions you may grant

SparePix only uses permissions and system features needed for the functions you choose:

- **Photos / media** (and older storage permissions on older Android) — to scan photos you grant
- **Selected photos / Photo Picker** — if you grant only some photos
- **Notifications** — to show scan progress
- **Foreground service** — so a scan can finish while the app is in the background
- **Network** — for purchase / restore with Google Play (see below), and if you open a link you choose (for example this policy)

On iPhone the only permission is **Photos** (full or limited access). SparePix asks for no notification, location, camera, contacts or tracking permission.

You can deny notifications; you can still scan and review in the app. If you deny photo access, SparePix cannot scan.

## Purchases (SparePix lifetime unlock)

Unlimited deletes and the full screenshot sweep are unlocked with a one-time in-app purchase processed by Google Play Billing on Android or by Apple's App Store on iPhone (`similarplain_lifetime`). There is no subscription.

When you purchase or restore:

- Google (Android) or Apple (iPhone) processes the payment
- The store may receive purchase / entitlement information needed to unlock SparePix on that Play account or Apple Account
- Your photos are not sent to Deximostudio as part of purchase

Google’s or Apple’s privacy policy applies to store transactions. Deximostudio does not store your payment card details.

## Optional network use

Scan and review work offline once photos are on this phone. The app may use the network when you:

- Purchase or restore the lifetime unlock
- Open a link you choose (for example this privacy policy)

Those requests do not upload your library to Deximostudio.

## Delete, Trash, and sharing

Deletes are **user-confirmed**. SparePix does not silent-delete. Confirmed items go to Android Trash / Recents when the system supports it, or are deleted with a clear confirm on older paths. You can restore from Trash / Recents while Android still keeps those items. On iPhone, iOS asks you to confirm each delete and moves the photos to Recently Deleted, where they can be recovered for 30 days. If iCloud Photos is on, iOS removes them from your other devices too.

SparePix does not upload photos you delete. Copies that already live in other apps, chats, or cloud galleries are not deleted by SparePix.

## Device backup

On Android, app data may be included in your device’s backup if backup is enabled (`allowBackup` is on). Backup content is managed by Google or your device manufacturer, not by Deximostudio. That backup would be the local index and settings — not a Deximostudio cloud library. On iPhone the local index is excluded from iCloud and computer backups.

## Data deletion

You can delete photos you marked after review (Trash / Recents or confirmed delete). Uninstalling SparePix removes the local index and app data from that device. It does not uninstall your gallery. There is no SparePix cloud account to delete because we do not host your photos.

See [Delete your data](delete-data.md) for Play Data safety details.

## Children’s privacy

SparePix is not directed at children under 13, and we do not knowingly collect personal information from anyone.

## Changes

We may update this policy. The “Last updated” date at the top will change when we do.

## Contact

Questions about this policy: [info@deximoapps.com](mailto:info@deximoapps.com)
