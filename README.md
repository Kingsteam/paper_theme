# HW18 Papier

Home-Assistant-Theme mit zwei Modi:

- **Hell:** E-Paper-Aufbau (2 px Rahmen, Radius 8), warmgraue Rahmen, helles Papier mit feinem Korn und Faserstruktur, Kacheln mit dezentem warmem Schatten.
- **Dunkel („Schiefer“):** dunkles Blaugrau, gedämpfte Schrift, blaugraue Rahmen, Schatten mit feiner heller Oberkante.
- **Symbole:** Farbgruppen, inaktiv pastellig, aktiv kräftig.

Abgeleitet vom [Graphite Theme](https://github.com/TilmanGriesel/graphite) von Tilman Griesel (MIT). Herkunft und Änderungen: [`NOTICE.md`](NOTICE.md).

## Farbnamen für Kacheln (`color:`)

| Gruppe | aktiv | fest/inaktiv |
|---|---|---|
| Licht | `amber` | `lime` |
| Wärme/Küche | `orange` | `brown` |
| Schlösser | `green` | `light-green` |
| Schlafen/Szenen | `purple` | `indigo` |
| Wasser/Fenster | `blue` | `light-blue` |
| Studio | `pink` | `blue-grey` |
| Alarm/Haus | `teal` | `cyan` |

## Installation

Marketplace (HACS) → benutzerdefiniertes Repository, Kategorie „Theme“. Voraussetzung in `configuration.yaml`: `frontend: themes: !include_dir_merge_named themes`.

## Auswahl

- **Für alle:** Einstellungen → Profil → Theme bzw. als Standard über `frontend.set_theme` (`name: HW18 Papier`, `mode: light` und `mode: dark`).
- Hell oder dunkel folgt der Einstellung des Geräts (oder bei Tablets mit browser_mod einer Automation).

## Hinweise

- Die Papiertextur liegt nur auf dem Seitenhintergrund (`lovelace-background`), nicht auf den Karten.
- Ein Theme unterscheidet nicht zwischen Buttons und Anzeigen. Alle Karten bekommen denselben leichten Schatten.
- Ungenutzte Farbnamen (`lime`, `brown`, `indigo`, `blue-grey`, `light-blue`, `light-green`, `cyan`) sind auf Pastelltöne umgelegt. Wer diese Namen anderswo für kräftige Farben nutzt, sieht dort Pastell.

## Lizenz

MIT, siehe [`LICENSE`](LICENSE). Enthält den Copyright-Hinweis von Graphite (© 2022 Tilman Griesel).

## Änderungen

Siehe [`CHANGELOG.md`](CHANGELOG.md).
