# Häufig gestellte Fragen

## :material-file-code: Über Gerätespezifikationen

!!! question "Was sind die absolut maximalen Eingangsfrequenzen?"
    Beide Kanäle können sicher mit Frequenzen bis zu 150 kHz verwendet werden, was das Maximum ist, das unsere Volumensensoren unterstützen. Theoretisch ist jeder Kanal in der Lage, Frequenzen bis zu 1 MHz zu messen.

!!! question "Was bedeutet 'interner Boost-Converter'?"
    Der interne Boost-Converter ermöglicht es dem Benutzer, eine stabile 24V-Ausgangsspannung für die Versorgung der Volumensensoren zu erzeugen, indem er nur den USB-Anschluss verwendet (und keine DC-Buchse!). Es handelt sich um eine Schaltung, die die 5V-Busspannung auf 24V transformiert, allerdings mit einer geringeren Stromstärke. Daher ist es ratsam, nur Volumensensoren mit einem Gesamtstromverbrauch $I<50 \textrm{ mA}$ an den Cal.flow anzuschließen, wenn Sie den Konverter verwenden. Andernfalls wird der interne Schaltkreis überhitzt und kann keine konstante Stromversorgung erzeugen.

    Der interne Aufwärtswandler ist praktisch für die Verwendung mit mobilen Geräten/Notebooks, bei denen keine externe Stromversorgung verfügbar ist.

    Als Referenz: Ein TB2-Impulsgenerator von testbox verbraucht $30 \textrm{ mA}$, während ein VSI+-Vorverstärker etwa $36 \textrm{ mA}$ verbraucht.

## :material-chat-question: Allgemeine Probleme
!!! question "Warum startet die Messung nicht, obwohl der Durchfluss richtig eingestellt ist?"
    Versuchen Sie, die `minimale Durchflußhysterese` höher oder die `Durchfluss-Stetigkeits-Zeit` niedriger einzustellen, damit die Stetigkeitsprüfung erfolgreich abgeschlossen werden kann. Beobachten Sie das Diagramm - liegt die Hauptdurchflussmenge innerhalb der Hystereselinien?

    Ein weiterer Grund könnte sein, dass die Kalibrierungszustandsmaschine nicht läuft: Der Kalibrierungsprozess muss **immer** über die Schaltfläche `Kalibrierungsvorgang starten` auf der Seite `Kalibrierungseinrichtung` gestartet werden.

!!! question "Das Live-Diagramm zeigt Null an, obwohl ein Durchfluss vorhanden ist und der M12-Stecker eingesteckt ist"
    1. Prüfen Sie, ob die Anschlusskonfiguration für beide Volumensensoren (1/2-Kanal) richtig eingestellt ist.

    2. Prüfen Sie, ob die Master-Linearisierungstabelle gefüllt und gültig ist.

    3. Prüfen Sie, ob ein nominaler K-Faktor für den Prüfling ausgewählt ist.

    4. Wenn alles andere fehlschlägt, versuchen Sie, den Cal.flow erneut anzuschließen.