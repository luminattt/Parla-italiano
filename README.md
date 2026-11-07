# parla! 🇮🇹

Mobile-first, kostenloser Italienischkurs für deutschsprachige A0-Lernende auf Sardinien.

## Veröffentlichen mit GitHub Pages

1. Diese **vier Dateien** (`index.html`, `manifest.webmanifest`, `icon.svg`, `sw.js`) in das Stammverzeichnis des Repositories hochladen. Die `README.md` darf ersetzt werden.
2. Repository auf **Public** stellen, falls GitHub Pages mit deinem Plan für private Repositories nicht verfügbar ist. Öffentliche Repositories sind für alle einsehbar.
3. Unter **Settings → Pages → Build and deployment** als Quelle **Deploy from a branch** auswählen, Branch **main**, Ordner **/(root)**, dann **Save**.
4. Nach der Bereitstellung: `https://luminattt.github.io/Parla-italiano/` öffnen.
5. Auf iPhone in Safari: Teilen → **Zum Home-Bildschirm**.

## Funktionen

10 vollständig beschriebene A0-Lernmissionen mit je neun Lernschritten, Audioausgabe, interaktivem Satzbau, eigenständiger Texteingabe, Auswahltests, Dialogen, einem Konjugationslabor, zeitlich geplanter Wiederholung, Lernjournal und JSON-Import/Export. Der Lernstand wird lokal im Browser gespeichert.

## Einschränkungen

- Spracherkennung wird nicht von jedem iOS-Browser unterstützt und misst nur Wortübereinstimmung, **nicht** die phonetische Aussprachequalität.
- Text-to-Speech verwendet die auf dem Gerät verfügbaren Stimmen; Audio ist nicht vollständig offline garantiert.
- Schriftarten werden bei Online-Verbindung von Google Fonts geladen, offline werden Systemschriften verwendet.
- Ohne Konto werden Lernstände nicht geräteübergreifend synchronisiert. Nutze den JSON-Export als Sicherung.
- Die Wiederholungslogik ist eine einfache adaptive Intervallplanung, **keine** FSRS-Implementierung.
- A1–B2 sind noch **nicht** als vollständige Lektionen implementiert.
