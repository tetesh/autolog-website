# AutoLog website (landing + privacy)

Static pages for store listings and legal compliance.

## Contents

| File | URL (when hosted) |
|---|---|
| `index.html` | `/` — landing (RU) |
| `en.html` | `/en.html` — landing (EN) |
| `privacy/ru.html` | `/privacy/ru.html` |
| `privacy/en.html` | `/privacy/en.html` |
| `subscription/ru.html` | `/subscription/ru.html` — how to cancel Pro (RU / YooKassa; cancel in-app) |
| `subscription/en.html` | `/subscription/en.html` |

## Live site

**https://tetesh.github.io/autolog-website/**

## Before publish

1. Support contact: **autolog1.support@gmail.com**
2. Keep Pro feature list in sync with the app (incl. **AI Scan + AI Voice** — shared quota Pro 80 / Business 600; cloud Gemini; **Drive sync** — Pro multi-device merge).
3. Privacy/terms payments section must mention **Google Play** and **YooKassa (RU/BY) + Yandex ID**.
4. Update `AppInfo.WEBSITE_URL` in the app if the domain changes

## Distribution (2026-07)

**Google Play** — единственный канал первого релиза.  
В России/Беларуси подписка Pro/Business через **ЮKassa** (Яндекс ID для restore); вне РФ/BY — Google Play Billing.  
RuStore — отложен.

## Source of truth

Full policy text: `docs/legal/privacy-policy-ru.md`, `privacy-policy-en.md`.  
Website HTML is a shorter public version — keep in sync on material changes.

## Deploy

```bash
cd website
git add -A
git commit -m "docs(website): YooKassa/Yandex payments in privacy, terms, subscription"
git push
```

GitHub Pages updates in 1–2 minutes.
