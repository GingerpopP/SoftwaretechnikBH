# feature-wochenplan.md – Iteration 1

## Feature: Wöchentlicher Menüplan

---

## Beschreibung
Der Nutzer sieht beim Öffnen der App sofort einen vollständigen Wochenplan (Montag bis Sonntag) mit je einem vorgeschlagenen Hauptgericht pro Tag. Per Knopfdruck kann ein neuer zufälliger Plan generiert werden.

---

## Verknüpfte Requirements

| REQ | Beschreibung |
|---|---|
| No.1 | Wochenplan anzeigen |
| No.2 | Rezeptdatenbank |
| REQ-004 | Zufallsgenerator |
| REQ-005 | Ladezeit < 3 Sekunden |
| REQ-007 | Responsive Design |

---

## User Story
> Als Nutzer möchte ich beim Öffnen der App sofort sehen was ich diese Woche koche, damit ich nicht selbst nachdenken muss.

---

## Akzeptanzkriterien

| # | Kriterium | Testmethode |
|---|---|---|
| 1 | Plan zeigt exakt 7 Tage (Mo–So) | Manueller Test |
| 2 | Kein Gericht erscheint doppelt | Sichtprüfung |
| 3 | "Neu generieren" Button ändert den Plan | Klicktest |
| 4 | Ladezeit unter 3 Sekunden | Browser DevTools |
| 5 | Darstellung korrekt auf 375px | Chrome DevTools |

---

## UI-Beschreibung
- Wochenplan als Karten oder Tabelle (Mo–So)
- Jede Karte zeigt: Wochentag, Gerichtname, optional Kategorie
- Button: "Neuen Plan generieren" (prominent platziert)

---

## Validierung
- [ ] Alle 7 Tage angezeigt
- [ ] Keine Wiederholungen im Plan
- [ ] Neugenerierung funktioniert
- [ ] Responsive auf Mobile getestet
- [ ] Ladezeit gemessen und dokumentiert

---

## Iteration
Iteration 1 – MVP

## Erstellt
Pham Dinh Gia Cuong · 12.05.2026  
*Erstellt im Q&A-Verfahren mit Claude (Anthropic)*
