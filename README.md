# Lüneburg lernen

Interaktives Quiz zum Lernen von Straßennamen und bekannten Orten in der Lüneburger Altstadt.

## Spielprinzip

- Bezeichnungen aus der Seitenleiste per **Drag & Drop** auf die Karte ziehen
- Landet man an der richtigen Stelle: +10 Punkte und der Name rastet ein
- Landet man daneben: Meldung mit dem genauen Abstand in Metern
- **Lernmodus**: Alle Orte werden vorab auf der Karte angezeigt
- **Zielzonen**: Zeigt für 8 Sekunden die erlaubten Ablagebereiche

## Inhalt

- 10 Straßen rund um die St. Johanniskirche
- 8 markante Orte (Kirchen, Plätze, Gaststätten, Wahrzeichen)

## Aufruf

Die App besteht aus einer einzigen HTML-Datei und benötigt keinen Server oder Build-Schritt.

### Direkt im Browser öffnen

```bash
# Linux / macOS
xdg-open index.html        # Linux
open index.html            # macOS

# oder den Dateipfad direkt in die Adressleiste des Browsers kopieren:
# file:///home/user/Learn_Lueneburg-/index.html
```

### Mit einem lokalen HTTP-Server (empfohlen)

```bash
# Python 3 (überall verfügbar)
python3 -m http.server 8080
# Aufruf: http://localhost:8080

# Python 2
python -m SimpleHTTPServer 8080
# Aufruf: http://localhost:8080

# Node.js (npx, kein Install nötig)
npx serve .
# Aufruf: http://localhost:3000

# VS Code: Erweiterung "Live Server" installieren → Rechtsklick auf index.html → "Open with Live Server"
```

### Über GitHub Pages

Wenn das Repository auf GitHub liegt, kann die App kostenlos gehostet werden:

1. Repository-Einstellungen öffnen → **Pages**
2. Branch `main` (oder den Feature-Branch), Root `/` wählen
3. Aufruf: `https://<nutzername>.github.io/<repository-name>/`

## Voraussetzungen

- Moderner Browser (Chrome, Firefox, Edge, Safari)
- Internetverbindung (für die OpenStreetMap-Kartenkacheln)
- Keine Installation, kein Framework, keine Abhängigkeiten
