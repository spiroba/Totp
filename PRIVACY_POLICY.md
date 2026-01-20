# Privacy Policy

**Last updated: January 20, 2026**

## Introduction

TOTP Authenticator ("we", "our", or "the App") is committed to protecting your privacy. This Privacy Policy explains how we handle your information when you use our iOS application.

## Information We Collect

### Data Stored Locally on Your Device

The App stores the following data locally on your device:

- **Account metadata**: Service names (issuers), account names/emails, algorithm settings
- **TOTP secrets**: Encrypted and stored securely in the iOS Keychain
- **App preferences**: Biometric lock settings, app state

### iCloud Sync

If you have iCloud enabled:
- **Account metadata only** is synced via CloudKit to your other devices
- **TOTP secrets are NEVER synced** - they remain only in your device's secure Keychain
- Sync data is protected by your Apple ID and iCloud encryption

## Information We Do NOT Collect

We want to be clear about what we **do not** collect:

- We do not collect personal identification information
- We do not collect usage analytics or tracking data
- We do not have access to your TOTP secrets
- We do not transmit your data to external servers
- We do not use third-party analytics services
- We do not share any data with third parties

## Data Security

Your security is our top priority:

- **TOTP secrets** are stored exclusively in the iOS Keychain with `kSecAttrAccessibleWhenUnlockedThisDeviceOnly` protection
- **Biometric authentication** (Face ID / Touch ID) can be enabled for additional security
- All data remains on your device or in your personal iCloud account
- We use Apple's native security frameworks

## Third-Party Services

The App uses the following Apple services:

- **iCloud/CloudKit**: For optional sync of account metadata between your devices
- **StoreKit**: For in-app purchases and subscriptions
- **App Store**: For app distribution and reviews

These services are governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## Children's Privacy

The App does not knowingly collect information from children under 13. The App is a utility tool that does not require or collect personal information.

## Data Retention

- All data is stored locally on your device
- Deleted accounts are moved to trash and permanently removed after 30 days
- Uninstalling the App removes all local data
- iCloud data can be managed through your iCloud settings

## Your Rights

You have full control over your data:

- **Access**: View all stored accounts within the App
- **Delete**: Remove any account at any time
- **Export**: Your TOTP secrets remain accessible only to you
- **Disable Sync**: Turn off iCloud sync in your device settings

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by updating the "Last updated" date.

## Contact Us

If you have questions about this Privacy Policy, please contact us:

- **Email**: support@spiro.dev
- **GitHub**: [github.com/borisspiro](https://github.com/borisspiro)

## Open Source

TOTP Authenticator generates codes according to RFC 6238 (TOTP) and RFC 4226 (HOTP) standards. The TOTP algorithm is an open standard.

---

*This Privacy Policy applies to TOTP Authenticator for iOS, iPadOS, watchOS, and related extensions.*
