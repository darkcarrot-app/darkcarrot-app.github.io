# darkcarrot-app.github.io

Root site for the `darkcarrot-app` account, served by GitHub Pages at
`https://darkcarrot-app.github.io/`.

| Path | Purpose |
|---|---|
| `/app-ads.txt` | Authorised digital sellers file. Must stay at the domain root or AdMob cannot read it. |
| `/privacy/` | Privacy policy shared by every Dark Carrot application. Use this URL in every Play Console listing. |
| `/index.html` | Minimal landing page. |

## Publishing

The repository name must be exactly `darkcarrot-app.github.io` — that is what makes GitHub serve it at the
domain root. Settings -> Pages -> Deploy from a branch -> `main` / `(root)`.

## When a new app is released

1. Add a row to the table in section 1 of `privacy/index.html` (both the English and the Turkish table).
2. Update the "Last updated" date in both languages.
3. Point the new app's Play Console privacy policy field at `https://darkcarrot-app.github.io/privacy/`.

## app-ads.txt

The publisher ID in `app-ads.txt` must match the AdMob account that owns the ad units used in the apps.
If the AdMob account changes, update this file, and make sure the "Website" field of each Play Store listing
points at `https://darkcarrot-app.github.io` so that crawlers can find it.
