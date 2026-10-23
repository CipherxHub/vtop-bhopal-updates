# Privacy Policy — V Bhopal

**Last updated: 23 October 2026**

V Bhopal is an independent, unofficial Android client for the VTOP portal operated by
VIT Bhopal. It is not made, endorsed, or supported by VIT Bhopal. This policy explains
what the app does with data.

## The short version

Your VTOP data — attendance, marks, timetable, profile — stays on your phone. Your
password is sent only to VTOP when you sign in, and is stored nowhere unless you
switch on biometric unlock. We have no account for you, and no server of ours holds
any of it. The one thing we do keep is an anonymous install identifier and the app
version, stored so we can count how many installs are active. You can switch that off.

## What the app sends

Three kinds of request leave your phone. Only the first carries anything about you.

1. **VTOP** (`vtop.vitbhopal.ac.in`) — your registration number and password, so VTOP
   can authenticate you, and then the requests that load your attendance, marks,
   timetable, exams, fees, leave and profile. This is the only place your credentials
   ever go. They are never sent to us, and we have no way to read them.
2. **Our install counter** — one anonymous ping a day, described under *What we
   collect* below. Switchable off.
3. **GitHub's public releases API** — "is there a newer version than the one I am
   running?". The request carries the app version and nothing else about you; GitHub
   sees it like any other web request, and we receive nothing from it. On the Play
   build, Google Play performs updates instead and this check is not used to download
   anything. No request leaves the app before you accept the first-launch agreement.

## What we collect

| Data | Why | Where it goes |
|---|---|---|
| A random install identifier (a UUID generated on your device) | To count distinct installs | Our own server, alongside the app version |
| The app version | To see which versions are in use | Same |

The install identifier is generated on your device, is not tied to you, and is not
linked to your name, registration number, email address, or any VTOP data. It is
regenerated if you clear the app's data or reinstall.

You can turn this off at any time in **More → Anonymous usage stats**. With it off,
the app makes no request to us at all.

The identifier and the version are kept in a database used only for that count. They
are never joined to your name, registration number, marks, or any other record, and
the app sends nothing that identifies you. Because the identifier is random there is
nothing to look up by name, so there is no per-person record to retrieve: switching
the setting off stops collection immediately, and clearing the app's data or
reinstalling mints a new identifier that cannot be linked to the previous one.

## What stays on your device

- **Your VTOP password**, if you turn on *Biometric unlock*. It is stored in an
  Android encrypted vault (AES-256, keys held in the Android keystore) on this
  device only, and it never leaves the device.
- **Cached VTOP records** — attendance (including the per-course breakdown), marks,
  grades, timetable, exams, fees, calendar days, and your profile — so the app opens
  instantly. These are deleted when you log out or tap **Forget saved login**, and
  they are wiped from the app's storage when you uninstall.
- **Files you save** — if you tap to save a syllabus or any other PDF, it is written
  to your device's Downloads folder, outside the app. It stays there until you delete
  it, and the app does not read it back. (On Android 7–9 it goes to the app's own
  Documents folder instead, which uninstalling removes.)
- **Your chat history** (Ask VTOP), kept on the phone under your registration number so
  you can reopen past questions. Delete a chat, or **Clear all chats**, from the Ask
  screen's History view.
- **Your VTOP session cookie**, held by Android's own cookie store.

None of this is transmitted to us or to anyone else.

## Third parties

- **VIT Bhopal (VTOP)** — the portal this app is a client for. Your credentials and
  session go there, and their privacy policy governs that data.
- **GitHub** — the app asks GitHub's public API whether a newer release exists, and
  downloads release notes so the "what's new" sheet works offline. GitHub sees that
  request; it carries nothing about your VTOP account.
- **Google Play** — if you installed from Google Play, Google handles the install,
  the app listing, and its own diagnostics.

There are no advertising networks, no analytics SDKs, and no third-party trackers in
this app.

## Children

This app is intended for students of VIT Bhopal and is not directed at children under
13. We do not knowingly collect personal information from anyone, of any age.

## Liability

This is an unofficial tool provided as-is. It is not affiliated with VIT Bhopal, and
we are not responsible for the availability of VTOP, for the accuracy of the data it
returns, or for any consequence of your use of this app. You are responsible for
complying with VIT Bhopal's terms of use.

## Changes

If this policy changes, the app will ask you to accept the new version before you
continue using it. The version number is shown on the agreement screen.

## Contact

Questions: **cipherxhub@users.noreply.github.com**
Source and issue tracker: <https://github.com/CipherxHub/vtop-bhopal-updates>
