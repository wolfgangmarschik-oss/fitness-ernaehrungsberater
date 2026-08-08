# Datenmodell und Konventionen

## Beziehungen

1. Ein Profil beschreibt eine Person.
2. Ein Rezept definiert Zutaten, Zubereitung, Nährwerte und Portionen.
3. Ein Wochenplan verweist auf Profile und Rezepte.
4. Eine Einkaufsliste wird aus Wochenplan, Rezepten und Vorrat berechnet.
5. Ein Check-in liefert Hinweise für den nächsten Wochenplan.

## Dateinamen

- ausschließlich Kleinbuchstaben, Ziffern und Bindestriche
- Umlaute umschreiben: `ä` → `ae`, `ö` → `oe`, `ü` → `ue`, `ß` → `ss`
- Wochenbezogene Dateien: `JJJJ-kw-NN.md`
- keine Leerzeichen in Dateinamen

## Einheiten

- Gewicht: g oder kg
- Flüssigkeit: ml oder l
- Energie: kcal
- Makronährstoffe: g
- Küchenpraxis zusätzlich als Stück, Scheiben, TL oder EL, wenn sinnvoll

Für Berechnungen wird eine einheitliche Basiseinheit verwendet. Praktische
Einheiten sind Zusatzangaben und ersetzen die Berechnungsgrundlage nicht.

## Nährwertqualität

- Quelle und Bezugsgröße dokumentieren.
- Rohes und gegartes Gewicht nicht vermischen.
- Rundungen erst am Ende der Berechnung durchführen.
- Fehlende Werte nicht als null interpretieren.
- Schätzungen deutlich kennzeichnen.
