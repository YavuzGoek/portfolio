# Wissensbasierter Angebots-Assistent

[Zur Portfolio-Übersicht](../README.md)

**Status:** umgesetzt und in drei realitätsnahen Angebotsfällen getestet und validiert.  
**Schwerpunkte:** wissensbasierte Assistenten, Quellenpriorität, Dokumentenautomatisierung und menschliche Freigabe.

## Ausgangslage und Ziel

Beratungsnotizen sollten in strukturierte Angebote überführt werden. Dabei mussten aktuelle Preise, fallbezogene Angaben und die gewünschte Dokumentgestaltung sauber voneinander getrennt bleiben.

## Umsetzung

Ein Assistent in einem Claude Project verarbeitet die Notizen nach definierten Regeln:

- Aktuelle Beratungsnotizen liefern die Angaben zum jeweiligen Fall.
- Eine separate Preisliste liefert die verbindliche Preis- und Berechnungslogik.
- Musterangebote dienen ausschließlich als Referenz für Tonalität, Struktur und Word-Layout.

Vor der finalen Dokumenterstellung ist eine menschliche Freigabe vorgesehen. Die finale Kundendatei enthält das Angebot, nicht die interne Prüfung. Fehlende preisrelevante Angaben sollen die Erstellung stoppen, statt durch erfundene Werte ergänzt zu werden.

## Mein Beitrag

Anforderungen und Quellenlogik, Prompt- und Workflow-Design, iterative Tests, Fehlerkorrekturen und Prüfung der Dokumentausgabe.

## Dokumentierte Ergebnisse und Prüfung

Drei realitätsnahe Testfälle mit unterschiedlichen Leistungsumfängen und Berechnungsbedingungen wurden geprüft. Dokumentiert sind fachlich und rechnerisch korrekte Ergebnisse in diesen Fällen.

Eine finale Word-Datei wurde erfolgreich im vorgesehenen Musterlayout auf einer DIN-A4-Seite erzeugt. Die Quellenpriorität wurde so definiert, dass historische Muster keine aktuellen Preise oder Falldaten vorgeben dürfen.

## Grenzen und Learnings

Die Validierung bezieht sich auf die drei dokumentierten Testfälle. Sie belegt keinen darüber hinausgehenden Kundeneinsatz oder allgemeine Fehlerfreiheit.

Die Qualität hängt von vollständigen Eingangsdaten und gepflegten Wissensquellen ab. Eine menschliche Prüfung bleibt erforderlich. Gemessene Zeitersparnis und kommerzielle Wirkungskennzahlen sind nicht belegt.

Originalangebote, Preisdaten, Testfallidentitäten und interne Prompts werden nicht veröffentlicht.
