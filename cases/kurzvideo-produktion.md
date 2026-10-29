# KI-gestützte Kurzvideo-Produktion

[Zur Portfolio-Übersicht](../README.md)

**Status:** umgesetzt, wiederholt getestet und persönlich freigegeben.  
**Schwerpunkte:** AI Implementation, Content Operations, lokale Toolintegration und Qualitätskontrolle.

## Ausgangslage und Ziel

Die Bearbeitung von Sprachvideos umfasst viele wiederkehrende Schritte: Transkription, Schnitt, Untertitel, Grafiken, Audio und Export. Diese Schritte sollten in einem nachvollziehbaren lokalen Workflow zusammenarbeiten, während die gestalterische und inhaltliche Abnahme beim Menschen bleibt.

## Umsetzung

Der Workflow verbindet lokale Transkription mit Wortzeitstempeln, Schnittplanung, synchronisierten Untertiteln, zeitgesteuerten Motion Graphics sowie technischer und visueller Qualitätskontrolle.

FFmpeg/FFprobe, lokale Apple-Medien- und Sprachtechnik, Python-basierte Werkzeuge sowie HTML-basierte Videokomposition mit HyperFrames/GSAP wurden mit Claude Code integriert und iterativ verbessert.

Eine ergänzende Google-Sheets-Anbindung arbeitet mit einem vorab definierten Schreibplan, einer Revisionsprüfung vor dem Schreiben und anschließendem Rücklesevergleich. Produktionsstatus und Veröffentlichungsfreigabe bleiben getrennt.

## Mein Beitrag

Prozessdesign, Anforderungen, Toolauswahl, Steuerung der KI-gestützten Implementierung, Sicht- und Hörprüfungen, Fehlerfeedback und finale Abnahme.

## Dokumentierte Ergebnisse und Prüfung

- Eine Referenz und mindestens sechs Serienvideos wurden produziert, persönlich geprüft und final freigegeben.
- Die technische Prüfung umfasst unter anderem Exportparameter und Abspielbarkeit; Sicht- und Hörprüfungen ergänzen die automatisierten Kontrollen.
- Nach einer Optimierung der lokalen Video-Engine wurde ein bereits freigegebenes Video erneut produziert und mit der Referenz verglichen. Dokumentiert sind bitgleicher Ton und eine persönliche Sichtprüfung ohne erkennbare Unterschiede.
- Die Tabellenanbindung wurde an einer Kopie getestet und anschließend für eine reale Finalisierung eingesetzt. Die vorgesehenen Zellen wurden zurückgelesen und abgeglichen; übrige Zellen blieben im dokumentierten Vergleich unverändert.

## Grenzen und Learnings

Automatische Transkription und Schnittplanung benötigen Qualitätskontrolle. Technisch erfolgreiche Exporte ersetzen keine visuelle Abnahme. Der dokumentierte Revisionscheck ist keine atomare Absicherung gegen gleichzeitige Schreibzugriffe.

Die Engine-Prüfung bezieht sich auf einen konkreten lokalen Test; sie belegt keine allgemeine Hardwarekompatibilität oder bitgenaue Reproduzierbarkeit jedes Endrenders. Aus der Produktion allein sind keine Reichweiten-, Umsatz- oder allgemeinen Einsparungswerte belegt.

Die Darstellung beruht auf intern dokumentierten Produktions- und Testnachweisen. Originalmedien, interne Pfade und Quellcode bleiben vertraulich.
