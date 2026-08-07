# AGENTS.md

## Zweck des Projekts

Dieses Repository bildet die zentrale Grundlage für einen persönlichen Fitness- und Ernährungsberater.

Das System soll bei folgenden Aufgaben unterstützen:

- individuelle Ernährungsplanung
- Erstellung von Wochenplänen
- Entwicklung und Optimierung von Rezepten
- Berechnung von Kalorien und Makronährstoffen
- Meal Prep
- Einkaufsplanung
- Resteverwertung
- effiziente Küchenorganisation
- Berücksichtigung mehrerer Personen

## Grundprinzipien

Bei allen Änderungen gelten folgende Regeln:

1. Bestehende Anforderungen und Regeln nicht ohne Grund verändern.
2. Änderungen möglichst klein, nachvollziehbar und strukturiert durchführen.
3. Keine vorhandenen Inhalte löschen, wenn dies nicht ausdrücklich erforderlich ist.
4. Neue Funktionen und Regeln sinnvoll in die bestehende Projektstruktur einordnen.
5. Berechnungen für Kalorien und Makronährstoffe nachvollziehbar durchführen.
6. Bei unklaren Anforderungen nachfragen, bevor grundlegende Annahmen getroffen werden.
7. Alltagstauglichkeit, Geschmack, Gesundheit und Zeitaufwand gemeinsam berücksichtigen.

## Personen

Das Projekt berücksichtigt mehrere Personen.

Personenspezifische Informationen werden unter:

`profiles/`

verwaltet.

Rezepte und Wochenpläne sollen die jeweiligen Profile berücksichtigen.

## Rezepte

Rezepte werden unter:

`recipes/`

verwaltet.

Jedes Rezept soll möglichst enthalten:

- Rezeptname
- Anzahl Portionen
- Zutaten
- Mengen
- Zubereitung
- Zubereitungszeit
- Kalorien
- Protein
- Kohlenhydrate
- Fett
- Gesamtmenge des fertigen Gerichts
- sinnvolle Aufteilung des fertigen Gerichts auf die Personen

## Mengenangaben

Zusätzlich zu Gramm- und Milliliterangaben sollen praxisgerechte Einheiten verwendet werden.

Beispiele:

- Eier Größe M zusätzlich in Stück
- Brot zusätzlich in Scheiben
- Wraps zusätzlich in Stück
- geeignetes Obst zusätzlich in Stück
- Öl bei sinnvoller Verwendung zusätzlich in TL oder EL
- Erdnussmus bei sinnvoller Verwendung zusätzlich in TL oder EL
- Teriyaki-Sauce bei sinnvoller Verwendung zusätzlich in TL oder EL

TL und EL nur verwenden, wenn dies in der Küche praktisch sinnvoll ist.

Diese Regeln gelten auch für Einkaufslisten.

## Küchengeräte

Bei der Planung sollen vorhandene Küchengeräte sinnvoll berücksichtigt werden.

Insbesondere:

- Philips Airfryer Dual Basket 3000 Series
- zwei getrennte Garkörbe
- parallele Zubereitung zur Zeitoptimierung
- AEG Multidampfgarer / Kombidampfgarer
- Herd

Wenn sinnvoll, sollen mehrere Geräte parallel eingesetzt werden.

## Vorhandene Zutaten

Bei geeigneten Rezepten können insbesondere berücksichtigt werden:

- Eier
- flüssiges Eiweiß
- Eiweißpulver / Whey

## Wochenpläne

Wochenpläne werden unter:

`meal-plans/`

gespeichert.

Sie sollen möglichst enthalten:

- Montag bis Sonntag
- Frühstück
- Mittagessen
- Abendessen
- gegebenenfalls Snacks
- Personenaufteilung
- Meal-Prep-Hinweise
- benötigte Rezepte
- Einkaufsgrundlage

## Einkaufslisten

Einkaufslisten werden unter:

`shopping-lists/`

gespeichert.

Sie sollen:

- auf dem jeweiligen Wochenplan basieren
- Mengen zusammenfassen
- Doppelungen vermeiden
- Stück-, Scheiben-, TL- und EL-Angaben ergänzen, wenn sinnvoll
- übersichtlich nach Lebensmittelgruppen strukturiert sein

## Dokumentation

Übergreifende Anforderungen und Fachregeln werden unter:

`docs/`

gespeichert.

Die README beschreibt das Projekt auf hoher Ebene.

Die AGENTS.md enthält die grundlegenden Arbeitsregeln.

Detailregeln sollen möglichst nicht mehrfach gepflegt werden.

## Git-Arbeitsweise

Änderungen sollen durch verständliche Commits dokumentiert werden.

Beispiele:

- `Personenprofile ergänzen`
- `Rezeptregeln erweitern`
- `Wochenplan Woche 1 hinzufügen`
- `Einkaufslistenformat verbessern`

Größere Änderungen sollen später über eigene Branches und Pull Requests durchgeführt werden.
