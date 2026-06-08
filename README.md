# Rekko — support

Static GitHub Pages site for the [Rekko](https://github.com/jib63/Rekko) iOS app.

## Live URLs

- Landing: <https://jib63.github.io/Rekko-support/>
- Privacy (EN): <https://jib63.github.io/Rekko-support/en/privacy.html>
- Privacy (FR): <https://jib63.github.io/Rekko-support/fr/privacy.html>

## Structure

```
.
├── index.html         # landing — links to the legal pages
├── assets/style.css   # shared dark-purple stylesheet
├── en/privacy.html    # English privacy policy
└── fr/privacy.html    # French privacy policy
```

No build step. Edit the HTML / CSS directly, push to `main`, GitHub
Pages rebuilds within ~30 s.

## Placeholders to replace before launch

- `privacy@rekko.app` and `contact@rekko.app` are used as contact
  addresses. Swap them with the address that actually receives mail
  before publishing the app to the App Store.
- The "Last updated" date in each `privacy.html` should match the date
  the policy was last reviewed.
