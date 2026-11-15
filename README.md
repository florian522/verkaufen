# Spielzeug-Verkauf

Kleine Web-App zum Erfassen von Spielzeug für Kleinanzeigen (Artikel + Fotos, optional Text & Preis per ChatGPT, ZIP-Export).
Daten liegen in PocketBase (`inventar-db.kraus-kalbach.de`, Collection `verkauf_artikel`).

## Dateien
- `index.html` – die App
- `manifest.webmanifest`, `icon-*.png`, `apple-touch-icon.png`, `favicon.svg` – App-Icon / „Zum Startbildschirm hinzufügen“
- `logo.png` – bitte aus dem Inventar-Repo hierher kopieren (wird oben links angezeigt)

## Hinweise
- Der ChatGPT-API-Schlüssel steht **nicht** im Code. Er wird in der App unter ⚙︎ eingetragen und nur im jeweiligen Browser gespeichert.
- Login = derselbe PocketBase-Benutzer wie beim Inventar.
