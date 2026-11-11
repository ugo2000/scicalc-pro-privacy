# SciCalc Pro — Privacy Policy (GitHub Pages)

Public privacy policy for **SciCalc Pro** (`com.scicalcpro.app`) on Google Play,
operated by Beijing Zhuao Science And Technology Co., Ltd.

## Live URLs

| Purpose | URL |
| --- | --- |
| English (use this in Play Console) | https://ugo2000.github.io/scicalc-pro-privacy/ |
| English, explicit path | https://ugo2000.github.io/scicalc-pro-privacy/privacy-policy.html |
| Chinese / 中文 | https://ugo2000.github.io/scicalc-pro-privacy/zh.html |

Play Console → Policy → App content → Privacy policy: paste the English URL.
The URL must be publicly reachable without login — do not use a private repo.

## Files

- `index.html` — English policy (canonical source)
- `privacy-policy.html` — byte-identical copy of `index.html`, kept as an explicit path alias
- `zh.html` — Chinese translation, same structure and meaning
- `.nojekyll` — bypass Jekyll processing on GitHub Pages

All pages are single-file HTML with inline CSS and no external dependencies.
`prefers-color-scheme: light` is supported for readability.

## Content rules (keep these true)

- The app has **no accounts, no registration, no analytics SDK**; settings, favourites and history stay on-device.
- The **only** third-party SDK is **Google AdMob** (banner + interstitial). It needs `android.permission.INTERNET` and may process Advertising ID, device info, approximate location and ad interaction data.
- The app is **not directed to children under 13** — do not claim COPPA certification or "no data collected at all".
- Contact: `info@zhuaotech.com` / https://zhuaotech.com — do not use `privacy@scicalc.app` or `scicalc.app` (those are from an obsolete draft).
- If the app later adds login, in-app purchases, UGC, social sharing or location, the IARC questionnaire must be refilled and this policy updated.

## Updating

Edit `index.html` and `zh.html` in `scicalc-store/pages/`, then either `git push` to `main`
or re-upload the files through the GitHub contents API. GitHub Pages rebuilds automatically.
Remember to bump the "Effective date" in both files.
