# parla! – neue Lernversion

Mobile Italienisch-Lernapp für das Leben auf Sardinien. Enthält einen aus den bereitgestellten Screenshots kuratierten Wortschatz, Hinweise zum Sprachregister, Eselsbrücken und interaktive Aufgaben (Wortpaare, Lücken, Schreiben, Leseverständnis).

## Veröffentlichung auf GitHub Pages

Alle fünf Dateien (`index.html`, `icon.svg`, `manifest.webmanifest`, `sw.js`, `README.md`) im Hauptverzeichnis des bestehenden Repositories **ersetzen**. In GitHub unter Settings → Pages: Deploy from a branch, `main`, `/(root)`. Dann die bisherige GitHub-Pages-Adresse öffnen.

## Daten und Grenzen

Fortschritt wird lokal im Browser gespeichert (localStorage). Die App hat keine Nutzerkonten und keinen Cloud-Sync. Die Aussprache nutzt die auf dem Gerät vorhandene italienische Sprachausgabe. Die Texte sind didaktisch neu formuliert. Umgangssprache und Übersetzungen sind kontextabhängig. Für iOS kann das Cache-Verhalten des Service Workers eine Aktualisierung verzögern.
