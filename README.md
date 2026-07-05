# AutoLog website (landing + privacy)

Static pages for store listings and legal compliance.

## Contents

| File | URL (when hosted) |
|---|---|
| `index.html` | `/` — landing (RU) |
| `en.html` | `/en.html` — landing (EN) |
| `privacy/ru.html` | `/privacy/ru.html` |
| `privacy/en.html` | `/privacy/en.html` |

## Before publish

1. Replace `support@autolog.app` with your real email.
2. Replace `[Your name]` in `docs/legal/privacy-policy-*.md`.
3. Register domain (e.g. `autolog.app`) or use **GitHub Pages** / Cloudflare Pages.
4. Update `AppInfo.WEBSITE_URL` and privacy URLs in the app if the domain differs.
5. Activate RuStore / Play links after apps are live.

## GitHub Pages (free)

1. Create repo `autolog-website`, push `website/` contents to root or `/docs`.
2. Settings → Pages → deploy from branch.
3. Custom domain optional.

## Source of truth

Full policy text: `docs/legal/privacy-policy-ru.md`, `privacy-policy-en.md`.
