---
date_created: 2026-05-10
type: changelog
tags:
  - flagdrill
  - changelog
---

# v1.0.6 — German aliases, random drill order, sticky focus (2026-05-10)

- Deutsche Ländernamen als Aliases ergänzt für alle Länder mit abweichendem deutschen Namen (Kroatien, Ägypten, Tschechien, Griechenland, Norwegen, Schweden, Finnland, Ungarn, Rumänien, Bulgarien, Serbien, Slowakei, Slowenien, Albanien, Nordmazedonien, Bosnien und Herzegowina, Kap Verde, Kamerun, Äthiopien, Vereinigte Arabische Emirate, Vereinigtes Königreich, Vereinigte Staaten, Philippinen, Jemen, Jordanien, Libanon, Syrien, Irak, Aserbaidschan, Kasachstan, Kirgisistan, Tadschikistan, Osttimor u.v.m. — insgesamt ~80 Länder)
- Drill-Reihenfolge ist jetzt zufällig (shuffled `drillOrder` Array) statt alphabetisch; die Flaggenliste bleibt alphabetisch sortiert
- `drill-focus` (große Flagge + Eingabefeld) ist jetzt `position: sticky; top: 0` — bleibt beim Scrollen oben stehen, die Flaggenliste scrollt darunter durch
- `scrollIntoView` beim Flaggenwechsel entfernt — aktive Zeile wird nur visuell hervorgehoben, kein automatisches Scrollen
