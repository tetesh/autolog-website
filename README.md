# AutoLog website (landing + privacy)

Static pages for store listings and legal compliance.

## Contents

| File | URL (when hosted) |
|---|---|
| `index.html` | `/` — landing (RU) |
| `en.html` | `/en.html` — landing (EN) |
| `privacy/ru.html` | `/privacy/ru.html` |
| `privacy/en.html` | `/privacy/en.html` |

## Live site

**https://tetesh.github.io/autolog-website/**

## Before publish

1. Support contact: **autolog1.support@gmail.com**
2. Replace `[Your name]` in `docs/legal/privacy-policy-*.md` (source of truth lives next to the app docs).
3. Keep Pro feature list in sync with the app (incl. **AI Scan** — cloud Gemini; **Drive sync** — Pro multi-device merge).
4. Update `AppInfo.WEBSITE_URL` in the app if the domain changes

## Distribution (2026-07)

**Google Play** — единственный канал первого релиза.  
RuStore и AppGallery — отложены.

## Source of truth

Full policy text: `docs/legal/privacy-policy-ru.md`, `privacy-policy-en.md`.  
Website HTML is a shorter public version — keep in sync on material changes.

## Deploy

```bash
cd website
git add index.html en.html privacy/ README.md
git commit -m "Update site for Google Play launch"
git push
```

GitHub Pages updates in 1–2 minutes.
