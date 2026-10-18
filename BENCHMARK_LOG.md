# Benchmark-Protokoll

Dieses Protokoll gehört zur **Messung**, nicht zur Spielaufgabe. Es ist nicht die geheime Bewertungsmatrix. Beide eigenständigen Challenger und der Hybrid werden nach denselben Regeln protokolliert.

## Messregeln

- Ein Challenger darf die vier Phasen **Planung → MVP → Nacharbeit → Integrität** direkt nacheinander ausführen, sofern keine separate Phasenfreigabe verlangt wird.
- Vor **Beginn** und nach **Ende** jeder Phase Datum und Uhrzeit mit Zeitzone (möglichst `Europe/Berlin`), den **verbleibenden Anteil des Pro-100-Wochenkontingents** und die Datenquelle notieren.
- **Keine Werte schätzen oder erfinden.** Falls die Kontingentanzeige nicht direkt zugänglich ist: `n. v. (vom Betreiber nachzutragen)`. Der Betreiber kann Messwerte aus der Codex-Oberfläche ergänzen.
- Zwischen den Messungen dürfen keine unbeobachteten Fremdaufträge laufen. Hintergrundverbrauch, Kontingentreset oder Anzeigelatenz separat vermerken. Negative Verbrauchsdifferenzen durch Resets nicht als „Ersparnis“ werten.
- Phasenbudgets und Zeitlimits stehen im gesonderten Phasenauftrag. Für die aktuelle Planung gelten **bis zu 4 Wochen-Prozentpunkte pro Challenger insgesamt**, nominell **1 Prozentpunkt pro Phase**, nicht genutztes Budget ist übertragbar. Die Anzeigen sind keine präzise automatische Stoppsperre.
- Am Ende jeder Phase den **reproduzierbaren Git-Checkpoint** (vollständiger Commit-SHA und idealerweise Tag) sowie den Arbeitsstand sichern, auch wenn unvollständig. **Kein Merge ohne ausdrückliche Freigabe.**
- Verbrauch aller eingesetzten Modelle und Subagents zählt zur jeweiligen Phase. Beim **Hybrid** zählt Astras Planung zusammen mit dem Verbrauch des ausführenden Pi Harness zum Gesamtbudget.
- Den anderen Challenger, seine Repositories, Tickets und Zwischenstände nicht konsultieren.
- Fehlende Messwerte nicht rückwirkend aus Vermutungen ausfüllen; im Zweifel im Protokoll als „nicht messbar“ belassen.

## Verbrauch und Fortschritt

| Phase | Beginn (Berlin) | Ende (Berlin) | Wochenrest vorher (%) | Wochenrest nachher (%) | Verbrauch (Prozentpunkte) | Messquelle | Git-Checkpoint (SHA/Tag) |
|---|---|---|---:|---:|---:|---|---|
| 1. Planung | — | — | n. v. | n. v. | n. v. | — | — |
| 2. MVP | — | — | n. v. | n. v. | n. v. | — | — |
| 3. Nacharbeit | — | — | n. v. | n. v. | n. v. | — | — |
| 4. Integrität | — | — | n. v. | n. v. | n. v. | — | — |

*Berechnung (nur ohne Reset/Fremdverbrauch und bei verlässlicher Anzeige): Verbrauch in Prozentpunkten = Wochenrest vorher − Wochenrest nachher. Nicht auf Prozent relativ zur Restmenge umrechnen.*

## Phasenberichte

### 1. Planung
- Beteiligte Modelle / Agents:
- Kurzresultat:
- Offene Punkte:
- Zeit- oder Kontingentabweichung:

### 2. MVP
- Beteiligte Modelle / Agents:
- Kurzresultat:
- Ausgeführte Tests / Ergebnis:
- Offene Punkte:
- Zeit- oder Kontingentabweichung:

### 3. Nacharbeit
- Beteiligte Modelle / Agents:
- Verbesserungen und Regressionen:
- Ausgeführte Tests / Ergebnis:
- Offene Punkte:
- Zeit- oder Kontingentabweichung:

### 4. Integrität
- Beteiligte Modelle / Agents:
- Gefundene Manipulationswege:
- Durchgeführte Gegenmaßnahmen und Gegenprüfungen:
- Rest-Risiken / Grenzen:
- Zeit- oder Kontingentabweichung:

## Abschluss
- Finaler Git-Commit:
- Startanleitung / reproduzierbarer Teststand:
- Noch laufende Prozesse oder Worktrees:
- Offene Branches / Pull Requests:
- Besondere externe Einflüsse (Resets, Ausfälle, andere Kontingentverbraucher):
