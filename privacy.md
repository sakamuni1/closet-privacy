# BooKlip Privacy Policy

**Last updated: November 11, 2026**

BooKlip is a macOS app for collecting and organizing clipboard items and other content. This policy explains what information the app processes, where it is stored, and when it may be shared with other services.

## Information BooKlip Processes

Depending on the features you use and the permissions you grant, BooKlip may process:

- **Clipboard content:** Text, links, images, and other content when clipboard monitoring is enabled, or when you use a paste or import action in the app.
- **Downloads folder information:** The app checks the Downloads folder for new files and may add file entries to the current tab. This can involve file names, paths, sizes, and modification dates.
- **Voice memo recordings and transcripts:** Audio captured when you start a voice memo, and its transcript when speech recognition is used.
- **App preferences and organization data:** Settings, tabs, item labels, and related information needed to operate the app.
- **Deleted-item recovery data:** Local copies retained to support restoring items you deleted in the app.

## How Information Is Used

BooKlip uses this information to capture and organize items, show previews, search your collection, restore deleted items, and provide voice memo features. BooKlip does not operate a remote service that stores your clipboard history.

## Storage and Services

### Storage on your Mac

App data is stored in BooKlip’s local data folders on your Mac. Certain sensitive text is encrypted before local storage, but this does not mean that every item or file handled by the app is encrypted. Anyone with access to your macOS account or files may be able to access locally stored information.

### Speech recognition

Voice transcription uses Apple’s Speech framework. Depending on the recognizer, language, and system configuration, audio may be sent to Apple for processing. Apple’s handling of that audio is subject to Apple’s terms and privacy practices. See Apple’s documentation on [requesting permission for speech recognition](https://developer.apple.com/documentation/speech/asking-permission-to-use-speech-recognition) and [on-device recognition](https://developer.apple.com/documentation/speech/sfspeechrecognitionrequest/requiresondevicerecognition).

### Link icons

To display a website icon for a link, BooKlip may request a favicon from the website or from Google’s favicon service. Those requests can reveal the website domain to the service receiving the request. This applies to the icon lookup, not to the clipboard history as a whole.

### Local network sharing

If you choose to use the sharing feature, BooKlip starts a web server on your local network and provides a link for selected items. People who can reach that address may be able to view the shared items while the sharing server is running. The connection uses HTTP and is not encrypted in transit. Share links only with people you trust and on networks you trust. BooKlip does not use a cloud relay for this feature.

### Purchases

In-app purchases are handled by Apple through StoreKit. Apple processes transaction information under its own terms and privacy policy.

BooKlip does not include advertising or analytics SDKs.

## Your Choices

- You can control clipboard monitoring in the app’s privacy settings and use manual paste or import actions instead.
- Voice memo recording begins only when you start the feature. macOS may ask separately for microphone and speech-recognition permission.
- You can delete items and use the app’s data-management controls to clear app data or manage deleted-item recovery.
- You can stop local network sharing by stopping the sharing feature or quitting the app.

The app monitors the Downloads folder for new files and may add entries to the current tab. Items added this way refer to files in your Downloads folder; deleting an entry from BooKlip does not necessarily delete the original file.

## Retention and Deletion

Information remains in BooKlip’s local storage until you delete it or clear the app’s data. BooKlip may keep local recovery copies of deleted items so that you can restore them; the app limits the number of these copies and removes older recovery data as needed. Deleting an item from BooKlip does not necessarily remove an original file stored elsewhere on your Mac.

## Security

BooKlip uses local storage and encrypts certain sensitive text, but no method of storage or transmission is completely secure. The local network sharing feature uses unencrypted HTTP, as described above. Keep your Mac and account protected, and use care when sharing links.

## Changes to This Policy

This policy may be updated when BooKlip’s features or data practices change. The date at the top of this document indicates when it was last revised.

## Contact

For questions about this policy or BooKlip’s privacy practices, contact the developer through the project’s support channel or issue tracker.
