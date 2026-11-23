# M2 StageView – PWA

Enthält die responsive V76-App als installierbare Progressive Web App.

## Online bereitstellen
1. Den gesamten Ordner `M2StageView_PWA` unverändert auf einen Webserver hochladen.
2. Die App über HTTPS öffnen (z. B. `https://deine-domain.at/`).
3. Die `index.html` muss unter derselben Adresse wie `manifest.webmanifest` und `sw.js` liegen.

## Auf dem iPad installieren
1. In Safari die HTTPS-Adresse der App öffnen.
2. Teilen antippen.
3. „Zum Home-Bildschirm“ wählen und hinzufügen.
4. Die App anschließend über das neue Home-Bildschirm-Symbol starten.

## Offline
Beim ersten Online-Aufruf wird die App-Oberfläche lokal zwischengespeichert. Danach kann sie auch ohne Internetverbindung gestartet werden. Für die erstmalige Installation und den ersten Cache-Aufbau ist eine Internetverbindung erforderlich.

Hinweis: Service Worker funktionieren nur über HTTPS oder lokal auf `localhost`. Die PWA speichert App-Dateien offline; Songdaten bleiben weiterhin nach der vorhandenen Speicherlogik der HTML-App gespeichert.
