# AR Marker Test mit A-Frame und AR.js

Dieses Projekt ist ein einfacher WebAR-Test, der mit [A-Frame](https://aframe.io) und [AR.js](https://github.com/jeromeetienne/ar.js) umgesetzt wurde. Es zeigt, wie markerbasierte Augmented Reality mit einer Webcam im Browser funktioniert.

## Vorschau

Beim Öffnen der Seite mit einer aktiven Webcam wird ein AR-Marker (Hiro-Marker) erkannt, auf dem dann Bilder (einschließlich animierter Notensymbole) dargestellt werden.

## Demo-Inhalte

- **A-Frame**: 3D-Rendering in WebVR/WebAR
- **AR.js**: Marker-Erkennung über Webcam
- **Bilder**: Ein zentrales Bild (`559.jpg`) und zwei Musiknoten-Icons mit Animationen

## Voraussetzungen

- Eine Webcam
- Ein Hiro-Marker ([PDF zum Ausdrucken hier](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/HIRO.jpg))
- Lokaler oder online Webserver (z. B. Live Server in VS Code oder GitHub Pages)

## Verwendung

1. Repository klonen oder Dateien herunterladen.
2. Stelle sicher, dass sich die Bilddateien (`559.jpg`, `music_notes_PNG68.png`, `music_notes_PNG99.png`) im gleichen Verzeichnis befinden.
3. Öffne die `index.html` über einen Webserver.
4. Halte den Hiro-Marker vor deine Webcam.

## Struktur

```plaintext
/
├── index.html
├── 559.jpg
├── pngimg.com - music_notes_PNG68.png
└── pngimg.com - music_notes_PNG99.png
