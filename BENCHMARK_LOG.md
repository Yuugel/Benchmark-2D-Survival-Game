# Benchmark-Protokoll

Dieses Protokoll gehört zur **Messung**, nicht zur Spielaufgabe. Es ist nicht die geheime Bewertungsmatrix. Beide eigenständigen Challenger und der Hybrid werden nach denselben Regeln protokolliert.

## Messregeln

- Ein Challenger darf die vier Phasen **Planung → MVP → Nacharbeit → Integrität** direkt nacheinander ausführen, sofern keine separate Phasenfreigabe verlangt wird.
- Vor **Beginn** und nach **Ende** jeder Phase Datum und Uhrzeit mit Zeitzone (möglichst `Europe/Berlin`), den **verbleibenden Anteil des Pro-100-Wochenkontingents** und die Datenquelle notieren. Die Anzeige kann auch vom menschlichen Betreiber unmittelbar an den Phasengrenzen erfasst werden; automatische Kontingentmessung wird nicht vorausgesetzt.
- **Keine Werte schätzen oder erfinden.** Falls die Kontingentanzeige nicht direkt zugänglich ist: `n. v. (vom Betreiber nachzutragen)`. Der Betreiber kann Messwerte aus der Codex-Oberfläche ergänzen.
- Zwischen den Messungen dürfen keine unbeobachteten Fremdaufträge laufen. Hintergrundverbrauch, Kontingentreset oder Anzeigelatenz separat vermerken. Negative Verbrauchsdifferenzen durch Resets nicht als „Ersparnis“ werten.
- Phasenbudgets und Zeitlimits stehen im gesonderten Phasenauftrag: **max. 15/30/30/15 Minuten** (Planung/MVP/Nacharbeit/Integrität), **bis zu 4 Wochen-Prozentpunkte pro Challenger insgesamt**, nominell **1 Prozentpunkt je Phase**, Restbudget übertragbar. Keine neue große Arbeit beginnen, wenn **3,5 pp Gesamtverbrauch** erreicht wurden; bei spätestens **4 pp** geordnet stoppen. Prozentanzeigen sind keine präzise automatische Stoppsperre. Wenn der Agent die Anzeige nicht selbst lesen kann, muss der menschliche Betreiber die Phasengrenzen steuern.
- Am Ende jeder Phase einen **reproduzierbaren, committeten Git-Checkpoint** sichern (Tag-Namen: `benchmark/plan`, `benchmark/mvp`, `benchmark/refinement`, `benchmark/integrity`) und den Git-Stand nachweisen. SHA und Tag dürfen auch extern im Bewertungsbogen festgehalten werden; vermeide selbstreferenzielle Log-Commits. Auch unfertige Stände sichern. **Kein Merge ohne ausdrückliche Freigabe.**
- Verbrauch aller eingesetzten Modelle und Subagents zählt zur jeweiligen Phase. Beim **Hybrid** zählt Astras Planung zusammen mit dem Verbrauch des ausführenden Pi Harness zum Gesamtbudget. Nur bei separatem, dokumentiertem Lauf starten. Alle Worker und Testprozesse an den Phasengrenzen beenden oder gezielt zum Checkpoint zuordnen.
- Den anderen Challenger, seine Repositories, Tickets und Zwischenstände nicht konsultieren.
- Fehlende Messwerte nicht rückwirkend aus Vermutungen ausfüllen; im Zweifel im Protokoll als „nicht messbar“ belassen.

- **Kein automatisches Weiterarbeiten über eine unbeobachtete Budgetgrenze:** Phasen dürfen direkt nacheinander ausgeführt werden, wenn Start-/Endwerte und Stoppschwellen zuverlässig erfasst werden. Sonst muss der menschliche Betreiber zwischen den Phasen das Weiterlaufen freigeben.
- **Keine Bewertungshinweise:** Der Challenger bekommt keine Teilpunktzahlen oder Testergebnisse des neutralen Bewerters. Normales Eigenreview und Selbsttests sind erlaubt.
- **Umgebung:** Gleiche Python-/Pygame-Version und identische Plattform für alle; lokale Installation und Systemzugriff vor Start kontrollieren. Unbeabsichtigte Paketinstallationen und Tools außerhalb des zugelassenen Scope dokumentieren.
- **Menschliche Eingriffe:** Rückfragen, Hilfen und Stopps dokumentieren. Freigaben an Budget-Grenzen sind neutrale Messhandlungen, keine Qualitätsabzüge.

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
