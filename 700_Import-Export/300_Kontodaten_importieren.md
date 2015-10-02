Dieses Modul dient dem Import von Bankbewegungsdaten mittels Export-Dateien aus E-Banking-Programmen. Der Import von Bankbewegungen geschieht in zwei Schritten. Im ersten Schritt (siehe diesen Menüpunkt) werden die Bewegungsdaten in eine temporäre Tabelle importiert. Im zweiten Schritt (siehe nachfolgendes Menüpunkt: *Kontodaten zuweisen*), werden aus den Datensätzen der temporären Tabelle Buchungssätze erzeugt.

Wählen Sie das Produkt aus, zu dem die Kontodaten importiert werden sollen, sowie das Importkonto (Bankkonto), von dem die Buchungen stammen.

Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441983048557.png) um die zu importierende Datei auszuwählen.

![](http://xpecto.github.io/docs/img/img_1441982998218.png)

Je nach Dateiformat der zu importierenden Daten müssen das Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. Enthalten die zu importierenden Daten Datensätze, die sich bereits in der verwendeten Datenbank befinden, so setzen Sie ein Häkchen bei *Datei enthält alte Daten*. Dies verhindert die doppelte Anlage bereits vorhandener Datensätze (bereits vorhandene Datensätze werden durch einen Abgleich-Algorithmus erkannt und übersprungen). Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. 
Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442233708499.png) werden die Importdaten (bei Verwendung der richtigen Trennzeichen bzw. Textzeichen) als Tabelle angezeigt. 
Weisen sie nun die Spalten der Importdatei den passenden Spalten der Datenbank zu - *Schritt 3: Spalten zuweisen*. Bei Dateien im  MT940 Bankformat wird die Spaltenzuordnung automatisch vorgeschlagen.
Nachdem alle Spalten zugewiesen sind, starten Sie den Import durch die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442233746695.png). 
Bankbewegungen, die im Verwendungszweck eine Vertragsnummer enthalten, werden dabei automatisch dem angegebenen Vertrag zugewiesen.

![](http://xpecto.github.io/docs/img/img_1441983215647.png)

Bestätigen Sie obige Meldung mit *Weiter zu Kontodaten zuweisen*. Die Importdaten sind nun erfolgreich in die Importtabelle Ihrer Buchungsdaten importiert werden. 

Achtung: Der Import der Buchungen ist an dieser Stelle noch nicht vollständig. Daten, die importiert wurden, aber noch nicht übernommen wurden, werden bei Berechnungen noch nicht berücksichtigt. Die importierten Daten werden hier lediglich in eine Temporärtabelle geschrieben, sie müssen später noch über das Modul *Kontodaten zuweisen* in die Buchungstabelle übertragen werden (siehe nachfolgenden Menüpunkt: *Kontodaten zuweisen*).
