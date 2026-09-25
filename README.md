# Veranna website

Public company website for Veranna, LLC at https://veranna.com.

This repository contains only public website content. It contains no enrollment application,
customer records, credentials, or private company documents.

The site is plain HTML and CSS, with no JavaScript, forms, analytics, external fonts, or build step.
GitHub Pages publishes `/docs` from `main`. Site changes go through a reviewed pull request.

Local preview:

```sh
python3 -m http.server 8766 --bind 127.0.0.1 --directory docs
```

Public pages: `/`, `/privacy/`, and `/terms/`.

Initial publishing: enable GitHub Pages for `main` and `/docs`, associate `veranna.com` in Pages
settings, then add GitHub Pages DNS records and enable HTTPS after the certificate is issued.
Keep all existing mail and domain-verification records intact.
