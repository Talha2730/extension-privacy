# Privacy Policy — Urdu Phonetic Writer & Copy-Paste

**Last updated:** 28 October 2026

This Privacy Policy applies to the Chrome extension **Urdu Phonetic Writer & Copy-Paste** (Chrome Web Store item ID: `bhimiceacddndhjdbnmnoklecpoojmkc`), developed by Talha Kalwal (GitHub: [Talha2730](https://github.com/Talha2730)).

## What information the extension handles

The extension handles the text that you choose to type or paste into its own popup editor. This text can include personal information if you enter it. The extension also reads text from your device's clipboard **only when you click the Paste button** and writes the editor's text to the clipboard **only when you click Copy**.

It does not automatically monitor your clipboard or read text from websites you visit. It has no website host permissions or content scripts.

## How information is used

- **Urdu phonetic typing:** Convert keys you type in the popup into Urdu characters.
- **Copy and paste:** Copy your editor text to your system clipboard or insert text that you choose to paste from the clipboard.
- **Automatic draft saving:** Save the current editor text locally so it can be restored when you reopen the popup.

The draft is saved using `chrome.storage.local`, with an additional local `localStorage` copy. Both are local to your browser profile/device; this version of the extension does not use `chrome.storage.sync`.

## Sharing and transfers

The reviewed extension code does **not** transmit typed text, saved drafts, or clipboard content to the developer or to any external server. It does not use analytics, advertising trackers, or third-party APIs, and it does not sell or share user data with third parties.

When you click **Copy**, the text is placed on your device's system clipboard, where it may be available to other applications according to your device's clipboard controls. If you choose to paste the copied text into a website or another application, that recipient's own privacy practices apply.

## Retention and deletion

Your draft remains in local browser extension storage until you overwrite or clear it or remove the extension and its data. Clicking **Clear All** clears the editor and its saved draft. You can also remove the extension through Chrome's extension settings to delete its extension data, subject to Chrome's normal storage behavior.

Text placed on the system clipboard is controlled by your operating system, not by this extension; clearing the draft does not necessarily clear the system clipboard.

## Permissions

- **storage:** Save and restore the draft in the popup.
- **clipboardRead:** Read clipboard text when the user selects Paste.
- **clipboardWrite:** Copy editor text when the user selects Copy.

The extension requests these permissions only to provide its user-facing typing and copy/paste features.

## Security

The extension operates locally and does not send editor contents over the internet. Local draft storage is not represented as encrypted by this extension. Avoid entering confidential information on a shared or untrusted computer.

## Changes to this policy

This policy will be updated if the extension's data practices materially change. Users should review the current policy following extension updates.

## Contact

For privacy-related questions or deletion guidance, contact the developer through [GitHub Issues for the Urdu Phonetic extension](https://github.com/Talha2730/urdu-phonetic-chrome-extension/issues).
