# OBS Alert User Policy And Agreement

Last updated: April 19, 2026

This document explains the intended use of OBS Alert, how the app handles local data, what network connections it makes, and what responsibilities stay with the user.

By installing, launching, logging into Telegram, or using OBS Alert, you agree to the terms below.

## 1. What OBS Alert Is

OBS Alert is a desktop application that helps users route Telegram donation events into OBS browser sources and overlay widgets.

Main feature groups include:
- Donation Alert Box templates and display pages
- Donation Goal templates and display pages
- Donation List templates for donation leaders, recent donations, and daily top donations
- Local donation management tools
- Desktop updater and release-check tools

OBS Alert is designed to work mainly on the user's own machine and with the user's own configured services.

## 2. Local-First App Policy

OBS Alert is designed as a local-first application.

Important points:
- The database is managed by each user. The developer does not provide or manage a shared admin database for your app data.
- The app does not include a remote admin-control service operated by the developer.
- Data, uploaded files, configuration, and Telegram login session files are stored locally on the user's device or in the user's own configured database/storage path.
- The developer does not operate a hidden data collection or telemetry system inside the app.

## 3. Network Communication

OBS Alert does not use a developer-operated control server for normal app usage.

The app may communicate only with services that are part of its normal function, such as:
- Telegram official API, when you log in and use Telegram-based features
- Your own MongoDB server or database endpoint, based on the connection string you configure
- OpenAI API, only if you enable or configure features that use it
- Local HTTP and WebSocket endpoints used by the app and OBS browser sources
- The official public update feed and release download location, when checking for or downloading updates

Except for these feature-related connections, OBS Alert is not intended to send your data to a developer-managed backend.

## 4. Data Storage And Security Notice

Please understand the following before using the app:
- Local files can still be lost, deleted, corrupted, copied, or leaked if your computer or storage is compromised.
- The developer cannot guarantee recovery of your local files, database records, uploaded assets, or Telegram session files.
- The developer is not responsible for losses caused by malware, device theft, weak passwords, unsafe backups, public file sharing, misconfiguration, or unauthorized access to your system.
- You are responsible for protecting your computer, database, storage folders, backups, and login session files.

Recommended user actions:
- Use the app only on devices you trust
- Keep your operating system and antivirus/security tools up to date
- Protect your local user account and database credentials
- Back up important data regularly
- Do not share session files, database dumps, or private config files with unknown people

## 5. Privacy Statement

OBS Alert is intended to avoid developer-side tracking.

The app does not include:
- ad tracking
- analytics dashboards controlled by the developer
- background remote screen monitoring
- hidden data export to a developer-owned admin server

However, privacy still depends on your own setup.

Examples:
- If you connect the app to Telegram, Telegram's own platform policies and network behavior apply
- If you use MongoDB on a remote server, that server operator and its security settings matter
- If you use OpenAI-powered features, requests sent to OpenAI follow the settings and policies of that service

## 6. Official Builds, Updates, And Verification

For safety, only use official builds and official update announcements.

Official public release and announcement source:
- https://github.com/meassamrong/obs-alert-updates/tree/main/news/official_hash.text

Before logging into Telegram or using production data, users should verify:
- version number
- release notes
- file hash, if provided
- download source

Best practice:
- keep OBS Alert updated to the latest official version for security fixes, bug fixes, and feature improvements
- avoid using unofficial mirrors, repacks, cracked builds, or modified releases

## 7. Modified, Cracked, Or Repacked Versions

Official support applies only to official builds from the official release/update source.

If you use a modified, cracked, repacked, decompiled, or unofficial build:
- you use it at your own risk
- the developer is not responsible for any security issue, data leak, account misuse, malware behavior, or app instability caused by that version
- the developer may refuse support for issues that cannot be reproduced on an official build

## 8. Telegram Login Policy

The Telegram login helper is provided for legitimate user authentication through Telegram's official API.

Before using Telegram login, please understand:
- Telegram login requires a real Telegram user account that you own or are authorized to use
- The phone number must be entered in full international format, for example `+85512345678`
- The OTP code and 2FA password may be shown in plain text in the login helper window
- Do not stream, record, or share your screen during login unless you fully trust the audience or participants
- The Telegram session file is stored locally on your device
- If the session file is copied, leaked, or stolen, another person may be able to use or monitor the app's Telegram session
- Starting a new Telegram login may replace the existing local session used by OBS Alert

User responsibility:
- keep the device secure
- do not share Telegram OTP codes or 2FA passwords
- do not send session files to unknown people
- use only accounts that you legally and personally control or are permitted to manage

## 9. Fair Use And Responsible Use

OBS Alert is provided as a creator tool. Users are expected to use it responsibly.

You agree not to use the app to:
- impersonate people or organizations
- access Telegram accounts without permission
- distribute modified builds as if they were official releases
- mislead users about update authenticity, version status, or security
- intentionally bypass security expectations of the app or connected services

## 10. Support Scope And Limitation Of Responsibility

The developer will try to improve the app, fix issues, and publish official updates, but cannot guarantee:
- uninterrupted service
- compatibility with every environment
- recovery of local data after damage or loss
- support for unofficial or modified builds

The developer is not responsible for:
- damage caused by unofficial builds
- compromised local machines or stolen session files
- unsafe user configuration
- leaked credentials or leaked database access
- issues caused by third-party services or policy changes outside the app

## 11. Free App Notice

OBS Alert may be distributed as a free app, but free access does not mean unlimited liability, warranty, or managed hosting.

Users remain responsible for:
- their own device security
- their own Telegram account security
- their own database and backup management
- verifying official builds before use

## 12. Credits

Developer:
- Real Name: Meas SAMRONG
- Telegram: https://t.me/jcorp_369
- Discord: `jcorp_`
- Discord ID: `853305433746178089`

Feature ideas and suggestion team:
- Mr Kmav
- YouTube: https://www.youtube.com/@MrKmav
- Facebook Page: https://www.facebook.com/MrKmav
- Tos Leng - តោះលេង
- YouTube: https://www.youtube.com/@teamtosleng
- Facebook: https://www.facebook.com/teamtosleng

## 13. Final Reminder

For the safest use of OBS Alert:
- use official builds only
- keep the app updated
- protect your local files and Telegram session
- verify official announcements before installing updates
- avoid logging in on untrusted devices or while sharing your screen

If you do not agree with this policy, do not use the app.
