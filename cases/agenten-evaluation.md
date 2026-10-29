# Entwicklung und Evaluation wissensbasierter KI-Agenten

[Zur Portfolio-Übersicht](../README.md)

**Status:** praktisch umgesetzt und getestet; umfasst unter anderem Übungs- und Praxisfälle.

## Ausgangslage und Ziel

Fachassistenten sollten aktuelle Falldaten, verlässliches Wissen und Stilvorlagen richtig gewichten. Unbelegte Ergänzungen und Rückschritte nach Prompt-Änderungen sollten gezielt erkannt werden.

## Umsetzung und mein Beitrag

Ich habe spezialisierte Agenten konzipiert, Quellenprioritäten definiert und die Ausgaben iterativ geprüft. Aktuelle Fakten, dynamische Wissensdaten und historische Beispiele wurden getrennt.

Normalfälle, Grenzfälle und unerwartete Eingaben dienten zur Evaluation. Nach Änderungen wurden frühere Fälle erneut ausgeführt. Zu den eingesetzten Prüfregeln gehören Quellenprüfung, Fakten-Whitelists, Kennzeichnung fehlender Informationen und Validierung vor der Ausgabe.

## Dokumentierte Ergebnisse

Mehrere Fachassistenten wurden über Testfälle stabilisiert. Dabei wurde praktisch sichtbar, dass eine Prompt-Verbesserung bereits bestandene Fälle wieder verschlechtern kann. Wiederholte Prüfung früherer Fälle wurde deshalb Teil der Arbeitsweise.

Der [Angebots-Assistent](angebots-assistent.md) ist ein konkretes verwandtes Beispiel; diese Seite beschreibt die übergreifende Evaluationspraxis und zählt dessen Ergebnisse nicht als zusätzliches unabhängiges Projekt.

## Grenzen und Learnings

Ein bestandener Einzeltest beweist keine Gesamtstabilität. Es liegen hier keine veröffentlichte Benchmark-Suite, vollständige Fehlerquote oder allgemeine Sicherheitszertifizierung vor. Übungsfälle werden nicht als Kundenimplementierungen ausgegeben.
