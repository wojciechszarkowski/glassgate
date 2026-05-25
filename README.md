# GlassGate — Vercel Deployment

Single-page HTML deployment of GlassGate, hostowane na Vercel,
osadzane jako iframe w SharePoint `nsg.sharepoint.com/sites/IFSCloud`.

## Pliki

- `index.html` — pełna aplikacja GlassGate (standalone, wszystko inline)
- `vercel.json` — nagłówki HTTP (CSP zezwalający na iframe z *.sharepoint.com)

## Aktualizacja zawartości

1. Edytuj `index.html` w GitHub (przycisk ołówka)
2. Commit → Vercel automatycznie zdeployuje nową wersję w ~30 sekund
