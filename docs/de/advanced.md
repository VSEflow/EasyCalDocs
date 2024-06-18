# Erweiterte Funktionen

## :material-professional-hexagon:  Unabhängige Frequenzmessung

![screenshot_adv_measure](img/screenadv.png)

## Was ist das?

Unter der Registerkarte `Erweitert` finden Sie den Modus **Unabhängige Frequenzmessung**. Dieser Modus ermöglicht es Ihnen, die Frequenz eines Eingangskanals unabhängig vom Messobjektkanal und ohne weitere Flussratenberechnungen zu messen. Im Gegensatz zum sofortigen Frequenzwert, der in der Live-Grafik angezeigt wird, kann in diesem Modus die Anzahl der Impulse oder ein Zeitlimit ausgewählt werden. 

Dieser Modus kann verwendet werden, um die Wiederholbarkeit der Frequenzwerte oder des Volumensensors zu messen.

!!! info "Nur Master"
    Um diesen Modus zu verwenden, schließen Sie den Volumensensor oder den Geschwindigkeitssensor an den Master-Eingang an. Der Eingang des Prüflings wird hier _nicht_ verwendet.


### Verwendung

Um diesen Modus einzurichten, müssen Sie zunächst den Anschluss so konfigurieren, dass er dem Signaltyp entspricht, der am Master-Eingang anliegt. Sie können zwischen einem "Zweikanal (Quadratur)"-Eingang oder einem "Einkanal"-Eingang wählen.

Im nächsten Schritt müssen Sie die Impulsgrenze angeben, die die Messung stoppt. Dieser Grenzwert stoppt die Messung, nachdem die angegebene Anzahl von Impulsen gemessen wurde. Wird alternativ die Zeitbegrenzung gewählt, stoppt die Messung ungefähr nach der angegebenen Zeit. 

!!! example "Zeitbegrenzung (interne Arbeitsweise)"
    Die Anzahl der erwarteten Impulse wird intern anhand der Frequenz zu Beginn der Messung berechnet und auf die gleiche Weise wie die Impulsgrenze verwendet. 

Starten Sie die Messung durch Drücken der Taste `START`. 

Nach Beendigung der Messung wird das Ergebnis im Ergebnisfeld angezeigt und auch in die Verlaufstabelle aufgenommen. Die Tabelle kann später auf Wunsch in eine Excel-Tabelle exportiert werden.