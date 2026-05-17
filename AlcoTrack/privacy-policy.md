# Privacy Policy — AlcoTrack

**Last updated:** 17 May 2026  
**Developer:** Dion Campbell  
**Contact:** dion.campbell@me.com

---

## Overview

AlcoTrack is a personal alcohol tracking app. Your drink log is stored on your device and, if you are signed in to iCloud, synced privately through Apple's CloudKit infrastructure. AlcoTrack does not run its own servers, does not collect analytics, and does not share your data with third parties.

---

## Data AlcoTrack Collects

### Drink log entries
Each entry you log includes the date, time, drink name, volume, and alcohol percentage. If you enable location recording in Settings, entries also include GPS coordinates. This data is stored on your device using Apple's SwiftData framework and synced to iCloud if you are signed in.

### Health data (optional)
If you enable BAC estimation and choose "From Apple Health" as the data source, AlcoTrack reads your **weight, height, date of birth, and biological sex** from Apple Health. This data is used only to calculate your estimated blood alcohol content within the app and is never stored outside Apple's frameworks or transmitted anywhere.

If you enable "Write drinks to Apple Health", each drink entry is written to your Apple Health database as an alcohol consumption record.

### Age verification
During onboarding you enter your date of birth to confirm you are 18 or older. This date is used only to verify your age at that moment and is **not stored** by AlcoTrack. Only the fact that age verification was completed is saved.

---

## Data AlcoTrack Does Not Collect

- Advertising identifiers or device fingerprints
- Crash reports or analytics (no third-party SDKs)
- Account credentials or personal identifiers beyond what you enter
- Any data from other apps

---

## iCloud Sync

When iCloud is available, your drink log syncs privately through Apple's CloudKit. Apple's privacy policy governs how CloudKit data is handled. You can disable iCloud sync for AlcoTrack at any time in **Settings → [Your Name] → iCloud → AlcoTrack**. Disabling sync does not delete existing data from your device.

---

## HealthKit

AlcoTrack's use of HealthKit data is limited to the features you explicitly enable:

- **Reading** weight, height, date of birth, and biological sex — only for on-device BAC estimation, only when you select "From Apple Health" as your data source.
- **Writing** drink entries — only when you enable "Write drinks to Apple Health".

HealthKit data is never used for advertising or shared with third parties.

---

## Data Sharing

AlcoTrack does not sell, rent, or share your personal data with third parties. The only external system that ever holds your data is Apple (iCloud / HealthKit), under Apple's own privacy policy.

---

## Data Deletion

You can delete all your drink data at any time from **Settings → Delete All My Data**. This removes every entry from your device and from iCloud. It does not affect data already written to Apple Health — to remove that, use the Health app.

Uninstalling AlcoTrack removes the app's local database. If iCloud sync is active, the iCloud copy remains until deleted via the Health app or iCloud settings.

---

## Children

AlcoTrack is an alcohol-related application rated 17+ and is not intended for use by anyone under the legal drinking age in their jurisdiction. We do not knowingly collect data from minors.

---

## Changes to This Policy

If this policy changes materially, the updated version will be published at the same URL with a revised "Last updated" date. Continued use of the app after a change constitutes acceptance of the updated policy.

---

## Contact

Questions or requests regarding your data:

**Dion Campbell**  
dion.campbell@me.com
