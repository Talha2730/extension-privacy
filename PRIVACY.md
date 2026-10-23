# Privacy Policy — 2FA Authenticator

Last updated: 23 October 2026

This policy describes version 11.0.1 (NoCookies) of 2FA Authenticator, maintained by Muhammad Talha (GitHub: Talha2730).

## Information handled and purpose

The extension stores authenticator account names, issuers, TOTP secret keys and settings to generate verification codes. It handles imported QR images and backup files. It accesses webpage fields and QR images for OTP autofill and QR scanning; region selection processes a screenshot of the visible tab. Chrome profile email and connected Dropbox account information identify backup accounts. Dropbox OAuth access and refresh tokens authorize backup and restore.

## Storage and sharing

Accounts and settings are stored using Chrome extension local storage. The current version also performs automatic Chrome storage synchronization and creates a dedicated bookmark backup folder. Chrome sync and bookmark sync may transfer these records through Google when browser synchronization is enabled. Bookmark backups can contain authenticator secrets and Dropbox tokens encoded as Base64; Base64 is not encryption. These backups should be treated as sensitive credentials.

If Dropbox is connected, account backup data is uploaded to and retrieved from the user's Dropbox account through Dropbox APIs. Google endpoints are contacted for signed-in account detection and clock synchronization. Network providers receive the request information ordinarily necessary to provide their services. Google and Dropbox handle information under their own policies. The extension does not operate a separate developer-hosted account database.

The NoCookies version does not create or read cookie-based authenticator backups. Requests to Google account pages may still use the browser's existing sign-in session. Removing the cookies permission does not remove cookies written by older versions.

## Limited use

User data is used for authentication, account management, QR import/export, clock correction, backup and restore. It is not sold, used for advertising, used for unrelated purposes, or used to determine creditworthiness or lending eligibility. Transfers to service providers are limited to providing these features. The extension does not maintain a browsing-history database or record general browsing activity for analytics.

## Retention and deletion

Local data remains until deleted or the extension is removed. Synced records, bookmark backups, downloaded exports and Dropbox backups can remain separately after uninstalling. Remove those copies separately through Chrome sync settings, the dedicated bookmark folder, the device's file manager and Dropbox. Disconnecting Dropbox does not automatically delete existing backup files; access can also be revoked in Dropbox connected-app settings. Older cookie backups can be removed through Chrome site-data settings for Google; clearing that site data may also sign you out of Google.

## Security

TOTP secrets and backup tokens grant sensitive access. Local, synchronized and exported copies are not guaranteed to be encrypted by this extension; Base64 encoding is not encryption. Protect the browser profile, device and backup accounts, and do not share backup URLs or files. No storage or transmission method is completely secure.

## Changes and contact

This policy will be updated when data practices change. For privacy requests, contact the maintainer through https://github.com/Talha2730/extension-privacy/issues or the support contact on the Chrome Web Store listing.
