
# Fitness- und Ernährungsberater

Persönliches Projekt zur Erstellung und Verwaltung von Ernährungsplänen, Rezepten, Meal-Prep-Plänen und Einkaufslisten.

## Ziele

Das Projekt soll bei folgenden Aufgaben unterstützen:

- individuelle Ernährungsplanung
- Erstellung von Wochenplänen
- Entwicklung und Optimierung von Rezepten
- Berechnung von Kalorien und Makronährstoffen
- Meal-Prep-Planung
- automatische Erstellung von Einkaufslisten
- Berücksichtigung mehrerer Personen
- effiziente Nutzung vorhandener Küchengeräte

## Projektstruktur

Das Repository verwendet folgende Struktur:

- `profiles/` – persönliche Ziele, Vorlieben und Einschränkungen
- `recipes/` – standardisierte Rezepte mit Nährwerten und Portionsaufteilung
- `meal-plans/` – Wochenpläne und Meal-Prep-Abläufe
- `shopping-lists/` – aus Wochenplänen abgeleitete Einkaufslisten
- `pantry/` – aktueller Vorrat und Mindestbestände
- `check-ins/` – freiwillige Wochenrückblicke und Anpassungen
- `docs/` – Fachregeln, Datenmodell und Arbeitsablauf

In jedem Fachordner liegt eine `_template.md`, die für neue Einträge kopiert
werden kann. Dateinamen werden klein und mit Bindestrichen geschrieben, zum
Beispiel `haehnchen-gemuese-bowl.md` oder `2026-kw-33.md`.

## Schnellstart

1. Personenprofile unter `profiles/` vervollständigen.
2. Vorhandene Lebensmittel in `pantry/current-stock.md` erfassen.
3. Rezepte aus `recipes/_template.md` anlegen.
4. Einen Wochenplan aus `meal-plans/_template.md` erstellen.
5. Daraus eine Einkaufsliste mit `shopping-lists/_template.md` ableiten.
6. Optional am Wochenende einen kurzen Check-in dokumentieren.

Der vollständige Ablauf steht in `docs/workflow.md`.

## Status

🚧 Das Projekt befindet sich im Aufbau.

## Arbeitsweise

Das Repository ist die zentrale Quelle für alle Projektinformationen.

Änderungen werden über Git dokumentiert und schrittweise weiterentwickelt.
