# SEO & AI Discoverability — korolev.kiev.ua

## Wikidata

**Item:** https://www.wikidata.org/wiki/Q141108548

Created 2026-08-17. Statements still needed (add via "+ add statement"):

| Property | Value |
|---|---|
| P31 (instance of) | Q5 (human) |
| P106 (occupation) | Q49757 (poet) |
| P106 (occupation) | Q36180 (writer) |
| P27 (country of citizenship) | Q212 (Ukraine) |
| P569 (date of birth) | 1973 |
| P856 (official website) | https://korolev.kiev.ua/ |
| P407 (language of work) | Q7737 (Russian) |
| P1412 (languages spoken/written) | Q7737 (Russian) |

Labels still needed (click "edit" in "In more languages"):
- Russian: **Дмитрий Королёв**
- Ukrainian: **Дмитро Корольов**

Aliases (English, already added): Dmitry Korolev, Дмитрий Королёв, Korolyov

---

## Search Engine Webmaster Tools

### Google Search Console
- Property: `https://korolev.kiev.ua/` (URL prefix)
- Verified via HTML meta tag
- Sitemap submitted: `https://korolev.kiev.ua/sitemap.xml` (223 pages found)
- Account: dmitry@korolev.kiev.ua

### Bing Webmaster Tools
- Imported from Google Search Console (no separate verification needed)
- Sitemap imported automatically
- Account: dmitry@korolev.kiev.ua (Google auth)

### Yandex Webmaster
- Site: `https://korolev.kiev.ua`
- Verified via meta tag `<meta name="yandex-verification" content="7c89236c9f2a5e24">`
- Sitemap already added
- Account: mov.ax.cx (Yandex ID)

---

## IndexNow

- Key: `8f4d2a9b1e6c3f7e`
- Key file: `https://korolev.kiev.ua/8f4d2a9b1e6c3f7e.txt`
- Submitted to: api.indexnow.org, bing.com, yandex.com (all returned 202)
- To re-submit after new content, POST to `https://api.indexnow.org/indexnow`:

```json
{
  "host": "korolev.kiev.ua",
  "key": "8f4d2a9b1e6c3f7e",
  "keyLocation": "https://korolev.kiev.ua/8f4d2a9b1e6c3f7e.txt",
  "urlList": [
    "https://korolev.kiev.ua/",
    "https://korolev.kiev.ua/poetry.htm"
  ]
}
```

---

## Verification Files in Repo

| File | Purpose |
|---|---|
| `8f4d2a9b1e6c3f7e.txt` | IndexNow key |
| `yandex_7c89236c9f2a5e24.html` | Yandex file verification (backup; meta tag is primary) |

---

## Meta Tags Added to index.htm

```html
<meta name="google-site-verification" content="QFUhhznJ9Va7_vlm9J8RDYAqNSGkze2hZR4mYMtc5tA" />
<meta name="yandex-verification" content="7c89236c9f2a5e24" />
```

---

## AI Discoverability Files

- `llms.txt` — AI-readable site description at `https://korolev.kiev.ua/llms.txt`
- `ROBOTS.TXT` — includes `Sitemap:` and `LLMs:` directives
- `index.htm` — JSON-LD schemas: `Person` + `WebSite`

### Author name variants (for searches/disambiguation)
- Дмитрий Королёв
- Дмитрий Владимирович Королёв
- Dmytro Korolov (official Ukrainian name)
- Dmitry Korolev
- Korolyov

---

## CSS Cache Version

Current version: `?v=3` in `sub.css` and `article.css` imports.
Bump to `?v=4` next time CSS changes aren't showing in production.
