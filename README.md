# HW18 Papier

Home-Assistant-Theme mit zwei Modi:

- **Hell:** E-Paper-Aufbau (2 px Rahmen, Radius 8), warmgraue Rahmen, helles Papier mit feinem Korn und Faserstruktur, Kacheln mit dezentem warmem Schatten.
- **Dunkel („Schiefer“):** dunkles Blaugrau, gedämpfte Schrift, blaugraue Rahmen, Schatten mit feiner heller Oberkante.
- **Symbole:** Farbgruppen, inaktiv pastellig, aktiv kräftig.

Aufbau angelehnt an Graphite E-ink von Tilman Griesel.

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
