# YTDashboard

Ein einfaches, clientseitiges Dashboard zum Überblick über neue Videos von YouTube-Kanälen.

- Läuft als einzelne HTML-Datei direkt im Browser (kein Server/Backend nötig)
- Nutzt die YouTube Data API v3 (eigener API-Schlüssel wird lokal im Browser gespeichert)
- Kanäle per Link oder Kanal-ID hinzufügen, Anzahl der Videos pro Kanal einstellbar
- Einstellungen und abgerufene Daten werden im `localStorage` des Browsers gehalten

## Nutzung

1. Eine der `.html`-Dateien im Browser öffnen
2. Unter „Einstellungen" den eigenen YouTube Data API v3 Key hinterlegen
3. Kanäle hinzufügen und Videos abrufen
