Dieses Modul dient dem Import von Bankbewegungsdaten mittels Export-Dateien aus E-Banking-Programmen. Der Import von Bankbewegungen geschieht in zwei Schritten. Im ersten Schritt (siehe diesen Menüpunkt) werden die Bewegungsdaten importiert, Im zweiten Schritt (siehe nachfolgendes Menüpunkt: *Kontodaten zuweisen*), werden aus den Datensätzen Buchungssätze erzeugt.

In der klassischen Menü-Ansicht ist der Import über Menü *Import/Export → Kontodaten importieren*,

In der modernen Menü-Ansicht ist diese Funktion über die Registerkarte *Buchhaltung* Gruppe *Kontodaten* zu finden.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_importieren/Import_Menue.png)

Starten Sie den Dialog *Buchungsdaten importieren* und wählen Sie das Produkt aus zu dem die Kontodaten importiert werden sollen, die Datei die die Bankbewegungen enthält sowie das Importkonto (Bankkonto), von dem die Buchungen stammen.

Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_importieren/Datei_auswaehlen.png) um die zu importierende Datei auszuwählen.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_importieren/Kontodaten_Auswahl.png)

Je nach Dateiformat der zu importierenden Daten müssen das Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. Enthalten die zu importierenden Daten Datensätze, die sich bereits in der Datenbank befinden, so setzen Sie ein Häkchen bei *Datei enthält alte Daten*. Dies verhindert die doppelte Anlage bereits vorhandener Datensätze (bereits vorhandene Datensätze werden durch einen Abgleich-Algorithmus erkannt und übersprungen). Wahlweise können die Kopfzeile sowie leeren Spalten angezeigt werden. 
Mit der Schaltfläche ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_importieren/Vorschau.png) werden die Importdaten als Tabelle angezeigt. 

|  Schaltfläche         |    Funktion in der Applikation    |  
| ------------- |:-------------| 
| Produkt     |  Produkt auswählen |
| Datei     |Importdatei auswählen | 
| Vorschau    | Vorschau der Importdatei mit selektiertem Wert | 
| Datei enthält Produktspalte     | Beim Import werden Kontodaten automatisch dem richtigen Produkt zugewiesen | 
| Trennzeichen    | Der gewählte Wert trennt Spalten innerhalb der Importdatei | 
| Textzeichen     |Der gewählte Wert importiert den Wert innerhalb des Textzeichens als Text| 
| Datei enthält alte Daten    | Es wird beim Import geprüft ob der Datensatz bereits vorhanden ist, wenn ja wird dieser übersprungen | 
| Datei enthält Kopfzeile  | Beim Import wird die erste Zeile der Datei ignoriert da dieses die Felddefinitionen enthält | 
| Start    | Es werden nur die Datensätze importiert die im Wert "Z/S" fesgelegt wurden| 
| Prozedur    | Hier muss die passende Prozedur gewählt werden.| 
*Schritt 2: Importparameter festlegen*. Hier muss das Umsatzkonto festgelegt werden. Das ist das Gegenkonto für die Umsätze die importiert werden.
Weisen sie nun die Spalten der Importdatei den passenden Spalten der Datenbank zu - *Schritt 3: Spalten zuweisen*. Bei Dateien im  MT940 Bankformat wird die Spaltenzuordnung automatisch vorgeschlagen.
Nachdem alle Spalten zugewiesen sind, starten Sie den Import durch die Schaltfläche ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_importieren/Import_starten.png). 
Bankbewegungen, die im Verwendungszweck eine Vertragsnummer enthalten, werden dabei automatisch dem angegebenen Vertrag zugewiesen.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_importieren/Kontodaten_zuweisen.png)

Bestätigen Sie obige Meldung mit *Weiter zu Kontodaten zuweisen*. Die Bankbewegungen/Importdaten sind nun erfolgreich in die temporäre Tabelle importiert worden. 

Achtung: Der Import der Buchungen ist an dieser Stelle noch nicht vollständig. Daten, die importiert wurden, aber noch nicht übernommen wurden, werden bei Berechnungen noch nicht berücksichtigt. Die importierten Daten werden hier lediglich in eine temporäre Tabelle geschrieben, sie müssen später noch über das Modul *Kontodaten zuweisen* in die Buchungstabelle übertragen werden (siehe nachfolgenden Menüpunkt: *Kontodaten zuweisen*).
