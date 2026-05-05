# Lingo Flow — Legal pages

Public legal pages for the [Lingo Flow](https://github.com/MouradKlinsmann/lingo_flow) Android app.

Hosted via GitHub Pages at: **https://mouradklinsmann.github.io/lingo-flow-legal/**

## Files

- `index.html` — landing page with links to the policies
- `privacy.html` — Privacy Policy (FR)
- `privacy.en.html` — Privacy Policy (EN)
- `style.css` — minimal shared styles (mobile-first, dark mode aware)

## Updating

Edit the HTML files, commit, push. GitHub Pages re-deploys automatically (~1-2 min). Keep the FR and EN versions in sync.

The `PRIVACY_POLICY_URL` constant in the app's [SettingsFragment](https://github.com/MouradKlinsmann/lingo_flow/blob/master/app/src/main/java/com/moura/lingoflow/ui/main/SettingsFragment.kt) points to `privacy.html` of this repo.
