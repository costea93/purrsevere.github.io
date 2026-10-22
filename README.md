# Purrsevere Privacy Policy

This repository hosts the public privacy policy for the current local-only Purrsevere iOS and Android release. The complete page is in `index.html`; it has no build step, cookies, or external assets. A short inline script displays the current copyright year.

## Publish with GitHub Pages

In this repository on GitHub, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. After GitHub Pages reports that the site is live, open the URL in a private browser window and verify the policy and email link.

This repository is owned by `costea93`, so its default project-site URL should be:

`https://costea93.github.io/purrsevere.github.io/`

The repository name alone does not make `https://purrsevere.github.io/` available. That address would require the `purrsevere` GitHub account or an independently configured domain.

## Use the live URL in the release

- Set `EXPO_PUBLIC_PRIVACY_POLICY_URL` to the live HTTPS URL in the Expo **production** environment before building the app.
- Enter exactly the same URL in **App Store Connect → App Privacy → Privacy Policy** and **Google Play Console → App content → Privacy Policy**.
- Open the policy link in Settings on installed iOS and Android release builds.
- Review the final signed builds and included SDKs before answering Apple's App Privacy and Google's Data safety questions. The policy describes the current local-only release; update it before enabling accounts, cloud sync, analytics, or other data flows.

The support mailbox in the policy, `purrsevere.app@gmail.com`, should be verified by the release owner before submission.
