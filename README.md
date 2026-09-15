# Emilios Wochenplan

Mobiler Wochenplan als installierbare Web-App. Die vorhandenen Termine, Aufgaben und festen Schulzeiten aus `Emilios_Wochenplan_clean_v8(1).xlsx` sind als Startdaten enthalten.

## Funktionen

- Wochenansicht mit Schule, Terminen, Wettkämpfen und Aufgaben
- Neue Termine sowie Aufgaben/Tests eintragen
- Aufgaben als erledigt markieren
- Mobile Installation als PWA und Offline-Start
- Speicherung lokal im Browser (ohne Benutzerkonto)

## Lokal starten

```bash
python -m http.server 8000
```

Danach `http://localhost:8000` öffnen.

## GitHub Pages

Unter **Settings → Pages** als Quelle **Deploy from a branch** auswählen und den Ordner `/ (root)` des `main`-Branches veröffentlichen. Die App ist danach unter `https://emeraichen.github.io/weekplaner/` erreichbar.

> Hinweis: Das Repository ist aktuell privat. GitHub Pages aus privaten Repositories hängt vom verwendeten GitHub-Tarif ab. Alternativ kann das Repository öffentlich gestellt oder ein externer Hosting-Dienst verbunden werden.
