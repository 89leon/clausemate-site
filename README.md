# clausemate-site

Static marketing, privacy, and support site for the Clausemate iPhone app.

- **index.html** — landing
- **privacy.html** — privacy policy (referenced from App Store Connect → App Privacy)
- **support.html** — support page (referenced from App Store Connect → Support URL)

Served via GitHub Pages from the `main` branch at the repo root.

## Deploy

1. GitHub → Settings → Pages → Source: *Deploy from a branch* → **main** / **(root)** → Save.
2. Wait ~60 seconds.
3. Site lives at `https://<username>.github.io/clausemate-site/`.

Paste `https://<username>.github.io/clausemate-site/privacy.html` into App Store Connect.

## Files

Pure HTML/CSS. No build step, no dependencies. Fonts: EB Garamond + Inter via Google Fonts.
