# chmod-Rechner

Interaktiver Rechner für Linux-Dateirechte, im Terminal-Look von [Lumio Studios](https://lumio-studios.de).

   **Live:** https://lumiostudios.github.io/chmod-rechner/

## Funktionen

- Umrechnung zwischen Oktal (`755`), symbolisch (`rwxr-xr-x`) und Checkbox-Matrix, alle Richtungen live
- Spezialbits: SetUID, SetGID, Sticky-Bit (`4755`, `rwsr-xr-x`, `1777` …)
- Fertiger `chmod`-Befehl mit eigenem Dateinamen und Kopieren-Button
- Schnellwahl für typische Werte (644, 755, 600, 700, 640, 1777)
- Erklärung in Klartext und Warnung bei riskanten Rechten (z. B. `o+w`)
- Keine Abhängigkeiten, kein Tracking, reines HTML/CSS/JS

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | Eigenständige Seite (für GitHub Pages) |
| `wordpress-snippet.html` | Zum Einfügen in WordPress (Block „Individuelles HTML“) |

## In WordPress einbinden

Inhalt von `wordpress-snippet.html` komplett in einen Block **„Individuelles HTML“** kopieren. Alle Styles sind unter `#lumio-chmod` gekapselt und beeinflussen das Theme nicht.

## Lizenz

MIT, siehe [LICENSE](LICENSE).
