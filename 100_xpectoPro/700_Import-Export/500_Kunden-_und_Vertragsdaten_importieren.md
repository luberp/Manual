Dieses Modul dient dem Import von Verträgen einschließlich Kundenstammdaten. Diese Funktion ist erreichbar in der klassischen Menü-Ansicht unter *Import/Export  → Kunden- und Vertragsdaten importieren*.

Starten Sie den Dialog *Kunden- und Vertragsdaten importieren*. Der Dialog enthält drei Schritte:

 - Schritt 1: Dateiparameter feslegen
 - Schritt 2: Importparameter festlegen
 - Schritt 3: Spalten zuweisen

Wählen Sie in dem ersten Schritt das Produkt bzw. den Fonds, zu dem die Kundendaten importiert werden sollen. Enthält die zu importierende Datei bereits eine Produktspalte, setzen Sie in dem Checkbox  *Datei enthält Produktspalte* ein Häkchen. Hierdurch entfällt die Auswahl des Produkts und klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441889824466.png) um die zu importierende Datei auszuwählen.

![](http://xpecto.github.io/docs/img/img_1461927960630.png)

Je nach Dateiformat der zu importierenden Daten müssen das Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung derAuswahlfelder entspricht dem Import einer Datei im CSV Format. 
Unter *Prozedur* wird die zur Verarbeitung der Daten zu verwendende Import-Prozedur ausgewählt. Import-Prozeduren müssen vorher vom xpecto Kundensupport hinterlegt werden. 
Enthalten die zu importierenden Daten Datensätze, die sich bereits in der verwendeten Datenbank befinden, so setzen Sie ein Häkchen bei	*vorhandene Kunden und Verträge aktualisieren*. Dies verhindert die doppelte Anlage bereits vorhandener Datensätze (bereits vorhandene Datensätze werden durch einen Abgleich-Algorithmus erkannt und aktualisiert). 

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441889857529.png) werden die Importdaten (bei Verwendung der richtigen Trennzeichen bzw. Textzeichen) als Tabelle angezeigt. 

Unter *Schritt 2: Importparameter festlegen* kann angegeben werden, dass fehlende Verträge, Kunden oder Vermittler angelegt werden sollen. Andernfalls werden nur bestehende Datensätze aktualisiert.

Weisen sie nun die Spalten der Importdatei den passenden Spalten der Datenbank zu. Nachdem alle Spalten zugewiesen sind, starten Sie den Import durch die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441889884609.png).

Der erfolgreiche Import der Kundendaten und Vertragsdaten wird durch eine Meldung unter Angabe der Anzahl der importierten Kunden und Verträge bestätigt. Bei Fehlschlagen des Imports eines oder mehrerer Datensätze (z.B. aufgrund fehlerhafter Daten) wird eine entsprechende Meldung angezeigt, und der komplette Import abgebrochen. Prüfen Sie in diesem Fall die zu importierende Datei auf Korrektheit, oder wenden Sie sich an den xpecto Kundensupport.