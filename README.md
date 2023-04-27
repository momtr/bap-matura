> 🚀 Contribute: PR or commit as author

# BAP-Matura

## Testing
- Mutation tests 
- Automated UI Testing – cypress, selenium – e2e
- Load testing
- (Testing portfolio)

## Source Code Management
- Distributed source code management => mehrere Server
- Was gab es davor? Verwendet jeder distributed source code management? => Trend heute ist ein zentrales Server Repository
- Internals von Git Erklären (sehr technisch => Frage noch unklar ob kommt)
- Wie arbeitet kann mit Git (clonen, feature branch, rebase, PR, etc.)

## Software Metrics
- Source code test coverage => wird nur für getestete Klassen angegeben
- Source code Metriken als Einzelwerte unaussagekräftig => Verlauf/Trends anschauen (zB geht Code Coverage rauf?) => zB wenn coverage runter geht, Alerts schicken

## Monitoring / Tracing / Logging
- Wieso, Wie – logging und monitoring
- Frameworks für Monitoring
- Wie erfasse ich Metriken (über einen Zeitraum)
- Darstellung in Percentilen (Ausreißer, Normalbereich) => Trends erkennen: warum gibt es zB immer um 8:00 Uhr 10 Ausreißer
- Datastores für logging monitoring:
- Logging: full text retrieval 
- Monitoring: time series Datenbanken
- Wie macht man log testing?
- Metriken = Messpunkte mit einem Wert (zB CPU Verbrauch eines Prozesses), der über die Zeit erfasst wird und dann in Diagramm mit Zeitverlauf oder Percentile Darstellung dargestellt wird  um Aussagen treffen zu können: zB mehre CPUs werden gebraucht
