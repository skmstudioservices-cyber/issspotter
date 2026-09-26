# issspotter

ISS Spotter — track the International Space Station live: position, altitude, speed, and whether it's over India right now. Data: wheretheiss.at.

**Live:** https://issspotter.pages.dev

Static single-page site on Cloudflare Pages (free tier). Live data is fetched client-side from free, keyless public APIs — no server, no Workers quota, no secrets.

## Files
- index.html — the whole site (Leaflet + OpenStreetMap, with attribution)
- robots.txt — AI-bot blocked, sitemap referenced
- sitemap.xml — homepage URL

Security: GSC verification tag pre-pasted (account-wide token); no secrets, no tracking, no PII collected.
