Dieses Modul dient dem Import von Verträgen einschließlich Kundenstammdaten. Diese Funktion ist erreichbar in der klassischen Menü-Ansicht unter *Import/Export  → Kunden- und Vertragsdaten importieren*.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kunden_und_Vertragsdaten_importieren/Datenimport_Menue.png)

In der modernen Menü-Ansicht erreichen Sie diese Funktion über: *Werkzeuge -> Import Export -> Datenimport*.


Starten Sie den Dialog *Kunden- und Vertragsdaten importieren*. Der Dialog enthält drei Schritte:

 - Schritt 1: Dateiparameter feslegen
 - Schritt 2: Importparameter festlegen (nur in der klassischen Ansicht verfügbar)
 - Schritt 3: Spalten zuweisen

Wählen Sie in dem ersten Schritt das Produkt bzw. den Fonds, zu dem die Kundendaten importiert werden sollen. Enthält die zu importierende Datei bereits eine Produktspalte, setzen Sie in dem Checkbox  *Datei enthält Produktspalte* ein Häkchen. Hierdurch entfällt die Auswahl des Produkts und klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kunden_und_Vertragsdaten_importieren/Button_Dateiauswahl.png) um die zu importierende Datei auszuwählen.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kunden_und_Vertragsdaten_importieren/Daten_importieren_Main.png)

Je nach Dateiformat der zu importierenden Daten müssen das Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. 
Unter *Prozedur* wird die zur Verarbeitung der Daten zu verwendende Import-Prozedur ausgewählt. Import-Prozeduren müssen vorher vom xpecto Kundensupport hinterlegt werden. 
Enthalten die zu importierenden Daten Datensätze, die sich bereits in der verwendeten Datenbank befinden, so setzen Sie ein Häkchen bei	*vorhandene Kunden und Verträge aktualisieren*. Dies verhindert die doppelte Anlage bereits vorhandener Datensätze (bereits vorhandene Datensätze werden durch einen Abgleich-Algorithmus erkannt und aktualisiert). 


----------


|  Schaltfläche         |    Funktion in der Applikation    |  
| ------------- |:-------------| 
| Produkt     |  Produkt auswählen |
| Datei     |Importdatei auswählen | 
| Vorschau    | Vorschau der Importdatei mit selektiertem Wert | 
| Datei enthält Produktspalte     | Beim Import werden Kundendaten automatisch dem richtigen Produkt zugewiesen | 
| Trennzeichen    | Der gewählte Wert trennt Spalten innerhalb der Importdatei | 
| Textzeichen     |Der gewählte Wert importiert den Wert innerhalb des Textzeichens als Text| 
| Vorhandene Daten aktualisieren | Es wird beim Import geprüft ob der Datensatz bereits vorhanden ist, wenn ja wird dieser aktualisiert | 
| Datei enthält Kopfzeile  | Beim Import wird die erste Zeile der Datei ignoriert da diese die Felddefinitionen der Import-Datei enthält | 
| Start    | Es werden nur die Datensätze importiert die im Wert "Z/S" fesgelegt wurden| 
| Prozedur    | Hier muss die passende Prozedur gewählt werden | 


----------


Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441889857529.png) werden die Importdaten (bei Verwendung der richtigen Trennzeichen bzw. Textzeichen) als Tabelle angezeigt. 


----------


| ![](http://xpecto.github.io/docs/xpecto/Grafiken/gr_gluehbirne.jpg) Vorschau der Importdatei       |       |  
| ------------- |:-------------| 
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kunden_und_Vertragsdaten_importieren/Prefiew_right.png)     |  richtig |
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kunden_und_Vertragsdaten_importieren/Prefiew_wrong.png)  |falsch | 


----------


Unter *Schritt 2: Importparameter festlegen* kann angegeben werden, dass fehlende Verträge, Kunden oder Vermittler angelegt werden sollen. Andernfalls werden nur bestehende Datensätze aktualisiert.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kunden_und_Vertragsdaten_importieren/Auswahl_DB_Felder.png)

Weisen sie nun die Spalten der Importdatei den passenden Spalten der Datenbank zu. Über das Symbol ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kunden_und_Vertragsdaten_importieren/Lupe.png) erhalten Sie eine Übersicht aller verfügbarer Datenbankfelder der Datenbank. Nachdem alle Spalten zugewiesen sind, starten Sie den Import durch die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441889884609.png).

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kunden_und_Vertragsdaten_importieren/Import_response.png)

Der erfolgreiche Import der Kundendaten und Vertragsdaten wird durch eine Meldung unter Angabe der Anzahl der importierten Kunden und Verträge bestätigt. Bei Fehlschlagen des Imports eines oder mehrerer Datensätze (z.B. aufgrund fehlerhafter Daten) wird eine entsprechende Meldung angezeigt, und der komplette Import abgebrochen. Prüfen Sie in diesem Fall die zu importierende Datei auf Korrektheit, oder wenden Sie sich an den xpecto Kundensupport.
