# Miracast — Screen Mirroring · Privacy Policy

Public privacy policy for the Android app **Miracast — Screen Mirroring**
(`harix.screen.miracast.mirroring`), published on Google Play.

**Live URL:** https://hashtaghk.github.io/miracast-privacy/

This is the URL to enter in the Play Console under *Policy → App content → Privacy
policy*, and it is the URL the app opens from *Settings → Privacy Policy*
(`R.string.privacy_policy_url`).

## Editing

`index.html` is a single self-contained page — no build step, no dependencies.
Edit it and push to `main`; GitHub Pages redeploys automatically.

When the app's data handling changes, update the policy **and** the "Last updated"
date in the masthead before shipping the release that makes the change.

## Keeping it accurate

The policy makes specific factual claims about the app. If any of these change,
the policy is wrong and must be updated:

- Browser Mirroring is local-only — no STUN/TURN server is configured, so the
  stream cannot leave the local network.
- No account, and no server operated by the developer receives any data.
- `android:allowBackup="false"`, so app data is excluded from Android backup.
- Permissions are limited to `INTERNET`, `ACCESS_NETWORK_STATE`,
  `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_MEDIA_PROJECTION`,
  `POST_NOTIFICATIONS` and `WAKE_LOCK`, plus `AD_ID` from the Google Mobile Ads SDK.
- Files are opened through Android's system pickers, so the app holds no camera
  or storage permission.
- Third parties are Google only: AdMob, Firebase Analytics, Firebase Crashlytics.
