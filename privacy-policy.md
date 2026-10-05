# PDF Anchor — Privacy Policy

**Effective date:** 5 October 2026
**Developer:** Waqar Amjad
**Contact:** waqaramjad.apps@gmail.com

## The short version

PDF Anchor does not collect, store, transmit or share any personal data. The app contains no networking code, so your files and everything the app does with them stay on your device. There is no account, no analytics, no crash reporting, no advertising and no third-party software of any kind inside the app. This is why the App Store privacy label for PDF Anchor reads **Data Not Collected**.

The rest of this document explains that in detail, including what the app keeps on your device so you can decide whether to keep it.

## Scope

This policy covers the PDF Anchor app for iPhone and iPad, its Action extension (the “PDF Anchor” option in the iOS share sheet), and its Shortcuts actions. All three are part of the same app bundle and follow the same rules.

## Your files

**Everything runs on your device.** Compressing, merging, extracting pages, rotating, adding or removing passwords, scanning, text recognition, converting other documents to PDF, signing, annotating, redacting and watermarking are all performed by the app on your iPhone or iPad. No file, page, image or text is ever sent to us or to anyone else.

**Files are opened where they live.** When you choose a PDF from Files, iCloud Drive or another storage provider, iOS grants the app temporary access to that one file. The app reads it in place and does not keep a copy. If the file is in a cloud service, that service’s own policy governs the storage of the file; PDF Anchor has no cloud storage of its own.

**Working copies are temporary.** While you are editing, the app may write working files to its own private temporary folder on your device. These are deleted when you finish, when you tap “Clear temporary files” in Settings, and automatically when the app starts.

**You choose where results go.** Every result is saved or shared only where you direct it, using the standard iOS save and share sheets. If you share a file to another app or service, that app or service receives it under its own privacy policy.

**Share-sheet handoff.** When you send a PDF to PDF Anchor from another app, the extension places a copy in a private container shared only between the extension and the app. The app takes that copy the next time it opens and deletes it from the container. Copies you never open are cleared automatically.

## What the app stores on your device

Nothing below ever leaves your device. Each item can be deleted from inside the app, and deleting the app removes all of it.

| Item | What it contains | Where it lives | How to remove it |
|---|---|---|---|
| Recents | For each recently opened PDF: its filename, page count, file size, the date you opened it, and a system bookmark that lets the app find the file again. **Not the file itself.** | The app’s preferences on your device | Touch and hold an entry and choose “Remove from Recents”; turn off “Keep recents” in Settings to clear all and stop recording |
| Saved signatures | Signatures you chose to save when signing a document | The app’s private storage on your device, excluded from iCloud and device backups, never synced | Settings → Saved signatures → Delete |
| Settings | Your default compression preset, the “Marks on export” and “Keep recents” switches, your appearance choice (system, light or dark), the page-dimming level in the viewer, and whether you have seen the welcome screens | The app’s preferences | Change them in Settings, or delete the app |
| Purchase status | Whether this device is entitled to the “Pro Pack”, so features work when you are offline | The app’s preferences; refreshed from the App Store on each launch | Delete the app. Your purchases remain with your Apple Account and can be restored |

The app’s preferences are part of your device backup if you have backups enabled. Saved signatures are deliberately excluded from backups.

## Camera and photos

**Camera.** The app asks for camera access only when you scan. Capture and page detection use Apple’s built-in document scanner, and the resulting images are processed on your device. Nothing is uploaded. You can revoke camera access at any time in iOS Settings → Privacy & Security → Camera.

**Photos.** The app never requests access to your photo library. When you import images to scan, the system photo picker runs outside the app and hands over only the images you select.

## Text recognition

Turning a scan into a searchable PDF or a text document uses Apple’s on-device text recognition (the Vision framework) in every language your device supports. Recognition happens entirely on your device. No image or recognised text is transmitted anywhere.

## Converting documents to PDF

Images, plain text, Markdown and CSV files are turned into PDFs by the app's own code on your device.

Word, PowerPoint, Pages, Keynote, rich text and HTML files are rendered to PDF using the web-content engine built into iOS (WebKit), also on your device. Before each conversion the app installs a content rule that blocks every request to a remote address, so a document that references images, fonts or scripts on the internet is rendered without fetching them. Nothing in the document is uploaded, and the conversion works in Airplane Mode.

## Purchases

The “Pro Pack” is a one-time purchase made through Apple’s App Store using Apple’s StoreKit. Apple processes the payment. We do not receive your name, email address, Apple Account, payment details or address. The only information the app receives from Apple is whether the purchase is owned, which it stores on your device (see above) so features keep working offline. Apple’s handling of purchase data is described in Apple’s Privacy Policy at apple.com/legal/privacy. Purchases support Family Sharing and can be restored on any device signed into the same Apple Account.

## Siri and Shortcuts

The Compress, Merge and Page count actions run in the app on your device. When you build a Shortcut, you decide which other actions receive the resulting file; those actions and apps are governed by their own policies.

## No analytics, tracking or third parties

The app includes no analytics, crash-reporting, advertising or attribution software, and no third-party code libraries at all. It does not use tracking as defined by Apple’s App Tracking Transparency framework and has no tracking domains. The app’s privacy manifest declares no collected data types. Automated checks in the app’s build process fail the build if any networking code, web address or third-party analytics SDK is introduced, so this policy is enforced by the software, not only by intention.

## Network use

PDF Anchor contains no networking code and works fully in Airplane Mode. The document converter's web-content engine is configured to block remote requests, as described above. The only network activity associated with the app is performed by iOS itself: communicating with the App Store for purchases and restores, and opening the links to this policy and the Terms of Use in your browser.

## Children

PDF Anchor does not collect personal information from anyone, including children. The app is a general-purpose utility and is not directed at children.

## Your rights

Because PDF Anchor does not collect or hold any personal data, there is nothing for us to access, correct, export or delete on your behalf. Everything the app stores is on your device and under your control, as described above. If you have a question or believe this policy is inaccurate, contact us at the address below and we will respond.

## Changes to this policy

If the app’s behaviour changes in a way that affects your privacy, this policy will be updated and the effective date above will change. The current version is always available at https://github.com/waqaramjad/pdf-anchor-legal/blob/main/privacy-policy.md, and inside the app under Settings.

## Contact

Waqar Amjad
waqaramjad.apps@gmail.com
