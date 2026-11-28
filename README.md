# NeoTheOne public documents

Static GitHub Pages site for public product, support, privacy, safety, and
technical documentation.

## Stable store and support URLs

Industrial Alarm Messenger documentation covers both Android and approved iOS deployments.

- Industrial Alarm Messenger privacy:
  `https://frtrev.github.io/apps/industrial-alarm-messenger/privacy/`
- Industrial Alarm Messenger support:
  `https://frtrev.github.io/apps/industrial-alarm-messenger/support/`
- Arthropod Invasion privacy:
  `https://frtrev.github.io/apps/arthropod-invasion/privacy/`
- Brick Breaker privacy:
  `https://frtrev.github.io/apps/brick-breaker/privacy/`
- NeoTheOne copyright:
  `https://frtrev.github.io/copyright/`

The legacy Arthropod Invasion Markdown policy remains at
`/privacy/privacy-policy.md` for backward compatibility.

## LandO

- Product: `https://frtrev.github.io/apps/lando/`
- Privacy (Play Console and App Store): `https://frtrev.github.io/apps/lando/privacy/`
- Support: `https://frtrev.github.io/apps/lando/support/`
- Account and local-data deletion help: `https://frtrev.github.io/apps/lando/support/#delete-data`
- Planning limitations: `https://frtrev.github.io/apps/lando/safety/`

These are static pages with no embedded forms, analytics or remote fonts. The
screenshots use a synthetic example property, not user data. No store badge or
live download claim is shown until the corresponding Play or App Store listing is available.

The LandO pages describe build 3 (1.0.0), with Android/iPhone/iPad support,
Firebase email/password accounts, Free/Pro demo plans, managed Gemini AI,
account-level AI consent, account-specific local storage, backups, temporary
ruler measurements, tap-to-insert points and individually dismissible hints.
The public policy is synchronized with the bundled app policy effective
November 26, 2026. Legacy-provider policy links are retained for older versions.
Account-deletion requests use the support email at
`/apps/lando/support/#delete-account`; signing out does not delete an account.
The gallery now contains 15 native simulator/emulator captures taken November
27, 2026: five each for iPhone (1320 × 2868), iPad (2064 × 2752) and Android
(1080 × 1920). They show the light map, saved layers, temporary ruler, updated
sign-in and dark map. Originals are in `assets/lando/screenshots/`, grouped by
device. The support page includes visual examples beside the relevant help.
Images use synthetic property data, retain map attribution, and open at full
resolution. The earlier `/assets/lando/property-map.png` and
`/assets/lando/saved-layers.png` URLs now serve the refreshed Android captures.

The policy describes the current FormSubmit reporting integration.
The owner approved a Google Form replacement, but its responder URL is still
needed. Update both the bundled app policy and this public policy when that
integration changes. Website email support does not replace in-app AI reporting.

Publishing: commit and push the reviewed site changes through the existing
GitHub Pages workflow, then confirm each public URL loads without a login before
using it in Play Console. Local files alone do not establish that hosting is live.

## LandO Password AutoFill

`/.well-known/apple-app-site-association` associates this domain with the
iOS app `C2M32YF6V7.app.neotheone.lando` for shared web credentials.
`_config.yml` includes the hidden directory in GitHub Pages output.

The app must include `webcredentials:frtrev.github.io` in its signed Associated
Domains entitlement. Enable Associated Domains for the app identifier in Apple
Developer and regenerate provisioning profiles if signing requires it. Install
a newly signed build after the file is live; Apple may cache association files.
Set the website on the saved LandO login in 1Password to
`https://frtrev.github.io`. This association does not enable universal links
or change authentication.
