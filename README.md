# V Bhopal — downloads & issue tracker

An unofficial Android client for VIT Bhopal's VTOP portal — attendance, timetable, marks, exams, calendar, fees, hostel leave, and profile in a clean native-feeling app.

> **Unofficial.** V Bhopal is an independent third-party client. It is not made, endorsed, or supported by VIT Bhopal, and it is not affiliated with them in any way. You are responsible for complying with VIT Bhopal's terms of use.

## Download

Get the latest APK from [**Releases**](https://github.com/CipherxHub/vtop-bhopal-updates/releases). The app also notifies you in-app when a new version is out and can download + install it directly.

> Allowed: install and use the APK on your own device.
> Not allowed: copying, modifying, redistributing, or re-uploading the APK or any part of the app. The source code is proprietary and is not published here.

## Google Play

A Play Store release is in preparation. The Play build does not self-update — Play handles distribution — so sideloaded and Play installs are separate apps and cannot update one another.

## Report an issue

Open an issue with:

- App version (More → Check for updates shows it)
- Android version + device model
- What you did, what you expected, what happened instead
- Screenshots (please hide your registration number / personal details)

## Privacy

Full detail is in the [privacy policy](PRIVACY.md).

Your VTOP credentials go only to `vtop.vit.bhopal.ac.in` over your device's own connection. They are **never** sent to us, and we have no backend, no account, and no server-side store of anything.

What does stay on your device: if you turn on biometric unlock, your password is kept in an Android encrypted vault (AES-256, key in the Android keystore) on that phone only. Attendance, marks, and your profile are cached locally so the app opens instantly. Both are wiped when you log out or tap **Forget saved login**.

Install counts (v2.0+): the app sends one anonymous ping per day (a random install ID plus the app version — no identity, no usage data). Turn it off anytime in More → Anonymous usage stats.
