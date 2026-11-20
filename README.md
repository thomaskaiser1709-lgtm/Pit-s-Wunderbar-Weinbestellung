# Pits WunderBar – Weinbestellung

Statische Webseite (eine einzige Datei: `index.html`), kein Server nötig.

## Auf GitHub Pages veröffentlichen
1. Neues Repository auf GitHub anlegen (z. B. `wunderbar-weine`).
2. `index.html` hochladen (Add file → Upload files) und committen.
3. Settings → Pages → Source: **Deploy from a branch**, Branch `main`, Ordner `/ (root)` → Save.
4. Nach ca. 1 Minute ist die Seite erreichbar unter `https://<benutzername>.github.io/<repository>/`.

## Weine aktualisieren
1. Seite mit Zusatz `#admin` öffnen: `https://<benutzername>.github.io/<repository>/#admin`
2. Excel-Datei (.xls/.xlsx) hochladen oder Weine einzeln bearbeiten.
   Spalten: Produzent, Wein, Weinart, Land, Besonderheit, Menge, Preis, Wein-Beschreibung.
3. „index.html herunterladen“ klicken und die Datei im Repository ersetzen.

Hinweis: Der Admin-Bereich ist nicht passwortgeschützt, speichert aber nichts auf dem Server.
Änderungen werden erst wirksam, wenn die neue `index.html` im Repository liegt.

Bestellungen gehen per E-Mail an Thomas.Kaiser1709@live.com (Konstante `TO` im Skript).
