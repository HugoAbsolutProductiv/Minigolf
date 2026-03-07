# ⛳ Minigolf Score Tracker

Eine progressive Web App (PWA) für Minigolf-Gruppen — läuft direkt im Browser, funktioniert offline und kann auf dem iPhone wie eine native App installiert werden.

## Features

- 🏌️ Bis zu 6 Spieler
- ⛳ 18 Bahnen mit Par-Werten
- 📊 Power BI-style Dashboard mit Gruppenbalkendiagramm, kumulativem Line Chart und Score-Matrix
- ⚡ Auto-Advance zur nächsten Bahn wenn alle Spieler eingetragen haben
- 💾 Automatische Speicherung (localStorage) — Spiel fortsetzen nach App-Neustart
- 📤 Export als CSV, Text (Share-Sheet auf iOS) oder PDF
- 📱 Installierbar als PWA auf iPhone / Android

## Live Demo

👉 **https://[dein-username].github.io/minigolf-score**

## Installation auf iPhone

1. Safari öffnen → zur App-URL navigieren
2. Teilen-Button → **„Zum Home-Bildschirm"**
3. Fertig — läuft wie eine native App, auch offline!

## Lokal starten

```bash
# Einfach index.html im Browser öffnen
open index.html

# Oder mit lokalem Server (für PWA-Features):
npx serve .
```

## Deployment (GitHub Pages)

1. Dieses Repo forken oder klonen
2. Unter **Settings → Pages** → Source: `main` Branch, `/` (root)
3. Nach ~60 Sekunden live unter `https://[username].github.io/[repo-name]`

## Tech Stack

- Vanilla HTML/CSS/JS — keine Dependencies
- PWA mit Service Worker (Offline-Support)
- localStorage für Datenpersistenz
