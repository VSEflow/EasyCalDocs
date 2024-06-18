# 
<img src="img/easycal_header.svg" alt="header" width="400"/>

## Was ist VSE EasyCal?

#### Motivation
Die EasyCal-Software wurde in Verbindung mit Cal.flow entwickelt, um Volumensensor-Kalibrierungen mit hoher Genauigkeit durchzuführen. Das Hauptaugenmerk dieses Systems liegt darauf, die Kalibrierungseinrichtung und -prozedur für den Endbenutzer so einfach wie möglich zu halten. 

#### VSE Cal.flow
Das Cal.flow ist ein externes USB-Gerät, das an einen PC angeschlossen wird, um Signalmessungen und Berechnungen von zwei angeschlossenen Volumensensoren durchzuführen. Die Hardware-Spezifikationen des Geräts finden Sie [hier](calflow.md).

#### Hauptmerkmale
EasyCal bietet die folgenden Hauptmerkmale:

* Hochgenaue Durchfluss-/Frequenzmessung von zwei Volumensensoren (Ratio-Counting-Verfahren)
* Kalibrierung von DUT (device under test) Volumensensoren nach dem Referenzprinzip
* Automatische Berechnung von Fehler und Reproduzierbarkeit
* Erstellung von PDF-Kalibrierprotokollen mit vollständiger Dokumentation und Kundenlogo
* Export der Ergebnisse als Excel-Tabelle für höchste Wertgenauigkeit bei weiteren Berechnungen
* Geführte Durchflusseinstellung mit Gleichmäßigkeitsprüfung
* Live-Diagramm der Durchflussmenge für beide Volumensensoren
* Master-Linearisierung mit bis zu 24 Punkten
* Modulare und voreingestellte Konfiguration des Kalibrierverfahrens
* Integration von VSE-Durchflusssensoren für die schnelle Suche nach Werten
* Generator für Kalibrierpunktvorlagen
* Erweiterte Einstellungen wie Kalibrierzeit und Hysteresegrenzen

## Struktur

Diese Dokumentation gliedert sich in die folgenden Hauptkapitel:

* [Grundlagen](basics.md) für den korrekten Anschluss der Hardware und die Funktionsweise der Software
* [Calibration setup](program.md) beschreibt, wie eine Kalibrierung konfiguriert wird
* [Kalibrierverfahren](procedure.md) zeigt, wie das Kalibrierverfahren durchgeführt wird 
* [Cal.flow](calflow.md) erläutert die Hardware-Funktionen und Spezifikationen des Cal.flow
* [FAQs](faqs.md) zeigt, wie man häufig gestellte Fragen und Probleme löst

## Hardware-Anforderungen

Der PC, auf dem die EasyCal-Software läuft, sollte die folgenden Mindestanforderungen an die Hardware erfüllen:

* 2 GHz Prozessor (x64) oder schneller
* 64-Bit-Windows-Installation
* 512 MB RAM oder mehr
* Grafikkarte mit DirectX11-Unterstützung
* 100 MB freier Speicherplatz auf der Festplatte
* Bildschirmauflösung: mindestens 1440x900 px
* USB 2.0 Schnittstelle oder besser
* Optionale Internetverbindung für Update-Check

## Lizenzinformationen

Haftungsausschlüsse und Lizenzinformationen zu den verwendeten Softwarekomponenten finden Sie im Abschnitt [About](about.md).