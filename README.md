# Idle PT Champ — Legal Pages

Static GitHub Pages package for:

- App: **Idle PT Champ**
- Package: **com.threechickens.ptchamp**
- Publisher label: **Three Chickens Studio**
- Legal entity: **Ultimate Index Joint Stock Company**

## Before publishing

1. Confirm that these inboxes exist and can receive mail:
   - `privacy@ultimateindex.asia`
   - `support@ultimateindex.asia`
2. Confirm the uploaded Android App Bundle matches the policy:
   - no advertising SDK;
   - no third-party analytics SDK;
   - no account creation;
   - no cloud save or backend collection;
   - local progress/settings only.
3. If the AAB contains Firebase Analytics, Crashlytics, AdMob, Meta SDK,
   AppLovin, Unity Analytics, sign-in, cloud save, multiplayer, or any other SDK
   that transmits user/device data, update both the Privacy Policy and the
   Google Play Data safety form before submitting.
4. Add a visible **Privacy Policy** link inside the app, typically under
   `Settings > Privacy Policy`.
5. Do not claim “no data collected” in Play Console unless the complete AAB,
   including all SDKs, supports that statement.

## Publish with GitHub Pages

1. Create a public GitHub repository, for example `idle-pt-champ-legal`.
2. Upload the **contents of this folder** to the repository root.
3. Open `Settings > Pages`.
4. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Save and wait for deployment.

The URL will normally be:

`https://YOUR_GITHUB_USERNAME.github.io/idle-pt-champ-legal/`

Use the root URL as the Google Play Privacy Policy URL.

## Suggested Play Console URLs

- Privacy policy:
  `https://YOUR_GITHUB_USERNAME.github.io/idle-pt-champ-legal/`
- Support:
  `https://YOUR_GITHUB_USERNAME.github.io/idle-pt-champ-legal/support.html`
- Data deletion:
  `https://YOUR_GITHUB_USERNAME.github.io/idle-pt-champ-legal/data-deletion.html`

## Important

This package is prepared for the described Lite release and is not a substitute
for advice from a qualified lawyer. Google Play declarations must match the
actual behavior of the submitted AAB.
