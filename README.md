# PDF & Image Tools - public site

Static pages for the app's store listings (GitHub Pages).

- `/` landing page
- `/privacy/` privacy policy (use this URL in App Store Connect and Play Console)
- `/app-ads.txt` AdMob seller verification

## Before publishing
1. Enable GitHub Pages (Settings -> Pages -> Deploy from branch `main`, folder `/`).

`app-ads.txt` is only verified when served from the domain root. A project repo is served at
`user.github.io/repo/`, so for app-ads.txt name the repo `<username>.github.io` or attach a custom domain.
