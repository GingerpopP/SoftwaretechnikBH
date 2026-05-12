# feature-einkaufsliste.md – Iteration 1

## Feature: Automatische Einkaufsliste

---

## Beschreibung
Basierend auf dem aktuellen Wochenplan generiert die App automatisch eine vollständige Einkaufsliste. Gleiche Zutaten werden summiert und nach Kategorien gruppiert. Optional kann die Liste gedruckt oder als PDF exportiert werden.

---

## Verknüpfte Requirements

| REQ | Beschreibung |
|---|---|
| REQ-003 | Einkaufsliste generieren |
| REQ-008 | Liste drucken / exportieren |
| REQ-007 | Responsive Design |
| REQ-006 | Keine Datenspeicherung (DSGVO) |

---

## User Story
> Als Nutzer möchte ich nach der Planung sofort eine fertige Einkaufsliste sehen, damit ich einfach einkaufen gehen kann ohne etwas vergessen.

---

## Akzeptanzkriterien

| # | Kriterium | Testmethode |
|---|---|---|
| 1 | Alle Zutaten der 7 Gerichte sind enthalten | Manuelle Prüfung |
| 2 | Doppelte Zutaten korrekt summiert (z.B. 200g + 300g = 500g) | Vergleichstest |
| 3 | Liste ist nach Kategorien gruppiert (Gemüse, Fleisch, etc.) | Sichtprüfung |
| 4 | Druck-Vorschau zeigt nur die Liste ohne UI-Elemente | Druckvorschau |
| 5 | Keine Nutzerdaten werden übertragen | Netzwerkanalyse DevTools |

---

## UI-Beschreibung
- Liste erscheint unterhalb oder neben dem Wochenplan
- Gruppiert nach Kategorien (z.B. 🥦 Gemüse, 🥩 Fleisch, 🍝 Trockenwaren)
- Jede Zeile: Zutatname + Menge + Einheit
- Button: "Drucken" / "Als PDF speichern"

---

## Validierung
- [ ] Einkaufsliste wird korrekt generiert
- [ ] Mengen werden summiert
- [ ] Kategorien vorhanden
- [ ] Druckfunktion getestet
- [ ] Keine Daten übertragen (DevTools geprüft)

---

## Iteration
Iteration 1 – MVP

## Erstellt
Pham Dinh Gia Cuong · 12.05.2026  
*Erstellt im Q&A-Verfahren mit Claude (Anthropic)*
