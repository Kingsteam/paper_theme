# Herkunft und Lizenzen / Origin and licenses

**HW18 Papier** ist ein abgeleitetes Werk des **Graphite Theme** von Tilman Griesel.

- Vorlage: [TilmanGriesel/graphite](https://github.com/TilmanGriesel/graphite), Version 2.7.6, Variante „Graphite E-ink Light/Dark“
- Lizenz der Vorlage: MIT, Copyright (c) 2022 Tilman Griesel
- Lizenz dieses Themes: MIT (siehe `LICENSE`), mit dem Copyright-Hinweis der Vorlage

## Was übernommen wurde
- Der Aufbau der E-ink-Varianten: flache Flächen ohne Weichzeichner, 2 px Kartenrahmen, Kartenradius 8 px, Navigationsleiste 56 px, Systemschriften.
- Die Idee, alle Farben über Theme-Variablen zentral zu steuern.

## Was neu bzw. geändert ist
- Eigene Theme-Datei (`themes/hw18-papier.yaml`), kein Kopieren der Graphite-Datei.
- Hell: warmes Papier (`#FFFCF6`) mit statischer SVG-Textur (Korn und Faserwolken), warmgraue Rahmen, dezente warme Kartenschatten.
- Dunkel („Schiefer“): blaugraue Flächen und Rahmen, gedämpfte Schrift, dunkler Schatten mit heller Oberkante.
- Farbgruppen für Symbole (statt der Graustufen von Graphite E-ink) und Pastellfarben auf ungenutzten Home-Assistant-Farbnamen.

Graphite selbst wird nicht verändert und kann parallel installiert bleiben.

---

**HW18 Papier** is a derivative of the **Graphite Theme** by Tilman Griesel (MIT, © 2022). It reuses the layout ideas of Graphite E-ink (flat surfaces, 2 px card borders, 8 px radius) and adds a warm paper background with a static texture, a slate dark mode and colour groups for icons. The theme file is written from scratch. Licensed under MIT, see `LICENSE`.
