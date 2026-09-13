# 🐝 Leuchtkäfer

Sammlung kleiner HTML/JS-Minispiele zum Üben von Klicken, Reaktion und Feinmotorik für kleine Kinder – ohne Werbung, ohne Tracking, direkt im Browser spielbar.

Einfach die jeweilige `.html`-Datei herunterladen und im Browser öffnen – es wird kein Server, keine Installation und keine Internetverbindung benötigt. Die Schriftart ([Baloo 2](https://fonts.google.com/specimen/Baloo+2), SIL Open Font License) liegt lokal unter [`fonts/`](./fonts) und wird nicht von Google-Servern nachgeladen – dadurch wird beim Öffnen der Seiten auch keine IP-Adresse an Dritte übertragen.

## 🎮 Die Spiele

### ⚡ Leuchtkäfer-Blitz
Datei: [`leuchtkaefer-blitz.html`](./leuchtkaefer-blitz.html)

Ein Raster aus Kästchen leuchtet abwechselnd an zufälliger Stelle auf – tippt oder klickt das Kind auf das leuchtende Kästchen, gibt es einen Punkt und einen kleinen Funken-Effekt. Über das Zahnrad-Menü lässt sich die Rastergröße (Spalten/Zeilen) anpassen, damit die Übung mit dem Kind mitwachsen kann.

**Trainiert:** gezieltes Tippen, visuelle Reaktion, Auge-Hand-Koordination.

▶️ [Direkt ausprobieren](https://htmlpreview.github.io/?https://github.com/pjanfred/Leuchtkaefer/blob/feature/initial_checkin/leuchtkaefer-blitz.html)

### 🌙 Leuchtkäfer-Jagd
Datei: [`leuchtkaefer-jagd.html`](./leuchtkaefer-jagd.html)

Ein einzelner Leuchtkäfer fliegt frei über den nächtlichen Bildschirm und prallt wie ein DVD-Logo von den Rändern ab. Fängt das Kind ihn per Klick/Tipp, gibt es Sternchen-Punkte und eine kleine Funkenanimation, danach fliegt der Käfer an neuer Stelle weiter. Im Einstellungs-Menü lassen sich Flugtempo (Schieberegler) und ein kurviger Flugmodus einstellen.

**Trainiert:** Verfolgen bewegter Ziele, Timing, Feinmotorik.

▶️ [Direkt ausprobieren](https://htmlpreview.github.io/?https://github.com/pjanfred/Leuchtkaefer/blob/feature/initial_checkin/leuchtkaefer-jagd.html)

> Die Vorschau-Links laden die Seiten live über [htmlpreview.github.io](https://htmlpreview.github.io) direkt aus diesem Branch. GitHub Pages ist für `main` bereits aktiviert – sobald dieser Branch dorthin gemerged ist, sollten die Links durch die dauerhaften Pages-URLs ersetzt werden (z. B. `https://pjanfred.github.io/Leuchtkaefer/leuchtkaefer-blitz.html`, siehe Ideen unten).

## ☕ Unterstützen

Wenn dir die Spiele gefallen und du das Projekt unterstützen möchtest:

<a href="https://www.buymeacoffee.com/pjanfred" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 45px !important;"></a>

[https://www.buymeacoffee.com/pjanfred](https://www.buymeacoffee.com/pjanfred)

## 💡 Ideen zur Vervollständigung des Repos

- **Diesen Branch nach `main` mergen**: GitHub Pages ist für `main` bereits aktiviert, aber `main` hat aktuell noch keine HTML-Dateien – erst nach dem Merge sind die Spiele über die dauerhafte Pages-URL (z. B. `https://pjanfred.github.io/Leuchtkaefer/leuchtkaefer-blitz.html`) statt der htmlpreview-Links oben erreichbar.
- **Startseite/Übersicht (`index.html`)**: Eine kleine Landingpage mit Links/Vorschaubildern zu allen Spielen, damit man nicht die Dateinamen kennen muss.
- **Screenshots/GIFs** der Spiele in der README, damit man auf einen Blick sieht, wie sie aussehen.
- **Lizenz** ergänzen (z. B. MIT), falls das Projekt frei nutzbar/weiterverwendbar sein soll.
- **Favicon** für einen runderen Eindruck beim Öffnen im Browser/Tab.
- **Sound-Feedback** (optional, abschaltbar) beim Treffer – viele Kinder mögen akustisches Feedback zusätzlich zur Animation.
- **Weitere Minispiele** nach demselben Muster (eigene HTML-Datei, Zahnrad-Einstellungen, Punktestand) – die README-Struktur oben ist so angelegt, dass neue Spiele einfach als weiterer Abschnitt ergänzt werden können.
- **CONTRIBUTING-Hinweis**, falls Beiträge von anderen erwünscht sind.
