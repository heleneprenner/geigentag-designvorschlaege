# Geigentag — interaktive Designstudie

Drei eigenständige Gestaltungsrichtungen für geigentag.at mit einer gemeinsamen Übersicht:

- **Blaudruck**: Indigo, Leinen und florale Druckmuster.
- **Vulkanland**: freie Interpretation mit Holunder, Beere und Wiesengrün; keine verbindliche Wiedergabe offizieller Trachtenfarben.
- **Saite & Strich**: große gestapelte Schrift und eine illustrierte Geige.

## Öffnen

`index.html` direkt in einem Browser öffnen. Bilder, Schriftdateien, Stile und JavaScript sind in dieser einzelnen Datei enthalten; es werden keine Pakete oder externen Ressourcen benötigt.

Alternativ aus dem vorhandenen Checkout `/workspace/GPT` starten:

```sh
python -m http.server 3000 --bind 0.0.0.0
```

Der Server dient zur internen Prüfung. Ein lokal laufender Server ist kein öffentlich zugänglicher Weblink. Für eine öffentliche Vorschau muss die Datei über einen dafür vorgesehenen Dienst veröffentlicht werden. Die bestehende Website geigentag.at wurde nicht verändert.

## Funktionen

- Übersicht mit drei anklickbaren Entwürfen; Wechsel auch über die obere Leiste.
- Fünf Jahresfarben wirken auf die Illustrationen, Buttons und Akzente aller Varianten.
- Favorit und Jahresfarbe werden ausschließlich im Browser gespeichert, sofern der Browser lokale Speicherung erlaubt.
- Programm, Rückblick, Anreise und aufklappbare Besuchsinformationen.
- Direkte Links per Hash: `#blaudruck`, `#vulkanland`, `#plakat`; zusätzlich z. B. `#blaudruck/programm`.
- Responsive Darstellung und mobiles Menü.

## Inhalt und Herkunft

Der von der Nutzerin bereitgestellte Claude-PDF-Entwurf und die Geigentag-Plakate dienen als gestalterische Referenz. Die eingebundenen Veranstaltungsfotos stammen von der bestehenden Website:

- https://www.geigentag.at/wp-content/uploads/2026/03/25-Die-Paradeiser-15.6-1024x768.jpg
- https://www.geigentag.at/wp-content/uploads/2026/06/IMG_3856-scaled.jpg
- https://www.geigentag.at/wp-content/uploads/2026/06/IMG_3864-scaled.jpg

Die SVG-Geige ist eine neue Platzhalterillustration und kann später durch die jeweilige Original-Jahresgeige ersetzt werden. Termine und konkrete Programmzusagen sind bewusst offen. Der Entwurf ist keine veröffentlichungsfertige Veranstaltungsankündigung.

Schriften: DM Sans, Fraunces und Space Grotesk (Google Fonts; SIL Open Font License). Schriftdateien sind eingebettet. Vor einer endgültigen Veröffentlichung sollten Fotoverwendung, finale Inhalte und Rechtstexte geprüft werden.
