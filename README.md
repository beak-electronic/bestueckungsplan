# Bestückungsplan

Browser-basierte Bestückhilfe für manuelles PCB-Bestücken (Pick-and-Place-Tracking).  
Version **V1.73**.  
**Unabhängige Neuentwicklung** (keine offizielle Eiger-App). Lizenz: **GPLv3**.

**Live (GitHub Pages):** https://beak-electronic.github.io/bestueckungsplan/

## Starten

Voraussetzung: Node.js 18+ (getestet mit 20).

```bash
npm install
npm run dev          # Entwicklung: http://localhost:5173
npm run build        # Produktion → dist/
npm run preview -- --host 0.0.0.0 --port 4173
```

Vite ist für GitHub Pages konfiguriert (`base: './'`, PWA `id`/`start_url`/`scope`: `/bestueckungsplan/`).

Optional: Inhalt von `dist/` per Netlify Drop hochladen (kein ZIP nötig).

## Schnelltest (Demo)

1. App öffnen → **Demo laden**
2. Lage **TOP** ist vorkalibriert (FID1/FID2)
3. Bauteil wählen → Marker auf dem Board → **Bestücken** (oder Enter)
4. Menü → **Pick-Liste exportieren** / **Projekt speichern**

## Lizenz

GPLv3 — siehe `LICENSE`.
