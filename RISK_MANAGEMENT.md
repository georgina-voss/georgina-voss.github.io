## ⚠️ Risikomatrix (MVP-Phase)

Zur Sicherung der Projekt-Timeline und der Datenintegrität werden potenzielle Risiken systematisch nach Eintrittswahrscheinlichkeit (EW) und Auswirkung (AW) klassifiziert und proaktiv gesteuert.

| Risiko | EW | AW | Priorität | Präventivmaßnahme / Mitigation |
| :--- | :---: | :---: | :---: | :--- |
| **Veraltete Geodaten / GIS-Layer** <br>*(Säule: Wissenschaft/Technik)* | 🔴 *Hoch* | 🔴 *Kritisch* | **Sehr Hoch** | Implementierung eines automatisierten Validierungs-Frameworks im Frontend (Abfangen fehlerhafter Uploads siehe Issue #1). |
| **Mangelnde Barrierefreiheit (A11y)** <br>*(Säule: Bildung/Didaktik)* | 🟡 *Mittel* | 🔴 *Hoch* | **Hoch** | Kontinuierliche Barrierefreiheits-Audits nach WCAG-Richtlinien vor jedem Teil-Release (siehe Issue #2). |
| **Scope Creep / Detailverluste** <br>*(Säule: Freie Wirtschaft/PM)* | 🔴 *Hoch* | 🟡 *Mittel* | **Mittel** | Radikale Reduktion auf die Kernfunktionen des MVP. Optionale Features wandern direkt ins Product Backlog für Phase 2 (siehe Issue #4). |
| **DSGVO-Verstöße beim Tracking** <br>*(Säule: Compliance/Wirtschaft)* | 🟢 *Gering* | 🔴 *Kritisch* | **Mittel** | Verzicht auf Google Analytics. Einsatz eines komplett cookielosen, europäischen Tracking-Tools (siehe Issue #3). |

*Legende: 🔴 Kritisch/Hoch | 🟡 Mittel | 🟢 Gering*
