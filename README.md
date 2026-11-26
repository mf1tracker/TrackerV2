# NutriGlass PWA – GitHub Pages Setup

Dein persönlicher Makro-, Ballaststoff-, Mikronährstoff- & Supplement-Tracker als installierbare Progressive Web App (PWA).

## Enthalten im Paket
- `index.html` – Komplette App inkl. Glassmorphism-UI, vorbefüllter Lebensmitteldatenbank, 1-Klick-Mahlzeiten-Editor, HPN-Supplement-Stack & Open Food Facts Barcode-Scanner
- `manifest.json` – Web App Manifest für Vollbild-Installation auf Android & iOS
- `sw.js` – Service Worker für Offline-Fähigkeit und schnelles Laden
- `icon-192.png`, `icon-512.png`, `icon.svg` – App-Icons für den Startbildschirm

## Installation auf GitHub Pages
1. Neues Repository auf [github.com/new](https://github.com/new) erstellen (z. B. `nutriglass`, Sichtbarkeit **Public**).
2. Alle Dateien aus dem entpackten Ordner (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `icon-192.png`, `icon-512.png`) ins Hauptverzeichnis (`root`) hochladen und committen.
3. Unter **Settings -> Pages** bei *Branch* `main` und `/ (root)` wählen und speichern.
4. Die erzeugte `https://<dein-username>.github.io/nutriglass/`-URL am Smartphone öffnen und über das Browser-Menü **„Zum Startbildschirm hinzufügen“** installieren.
