Der Daten-Import/Export gehört zu den wichtigsten Funktionen von xpectoPro. Anwendung finden diese Funktionen z.B. beim Import von Bankbewegungen oder beim Import von Vermittler-, Vertrags- oder Kundenbeständen aus andere Systemen.

Bei einigen der beschriebenen Import-Funktionen werden unter anderem Buchungsdaten importiert. Hierbei entstehen Erfassungen, die danach noch in einem weiteren Arbeitsschritt bearbeitet werden können.


## Tabellen synchronisieren

Eine Eingenschaft von xpectoPro ist die Mehrstandortfähigkeit. Das Synchronisation-Modul dient dem Export von Datensätzen an den xpecto Webserver sowie dem Import von Daten an anderen Standorten über den xpecto Webserver.

In der klassischen Menü-Ansicht ist die Funktion unter Menü *Import/Export → Tabellen synchronisieren* zu finden.

In den modernen Menü-Ansicht ist die Funktion Synchronisieren unter dem Karteireiter *Datenbearbeitung* Gruppe *Import / Export*.

![](http://xpecto.github.io/docs/img/img_1461833593791.png)

Nachdem starten wird in dem  Dialog *Synchronisation* eine Liste aller Tabellen angezeigt.

![](http://xpecto.github.io/docs/img/img_1421748051531.png).

Welche Tabellen Sie synchronisieren wollen, kann durch die Optionen die der Filter anbietet, gesteuert werden.
Über den Filter kann eingestellt werden 

|  Filter         |    Beschreibung     |  
| ------------- |:-------------| 
| Alles       | Es wird alles synchronisiert| 
| Definitionen   | Definitionen die unter Extras → Einstellungen → Feldgruppe Synchronisation eingestellt würden werden synchronisiert | 
| Löschungen     | Löschungen werden synchronisiert | 
| Änd.abholen     | Änderungen werden von Server abgeholt| 
|Änd.übermitteln| Änderungen werden zum Server geschickt|


![](http://xpecto.github.io/docs/img/img_1461912454219.png)

Für die Synchronisierung können Profile angelegt werden in denen nur bestimmte Tabellen für die Synchronisierung ausgewählt werden. So werden dann z.B. nicht alle sondern nur ein paar der Tabellen synchronisiert. Dies ist praktisch, wenn beispielsweise die Weboberflächen für Kunden- bzw. Vermittlerportal angepasst werden. In diesem Fall müssen schließlich nicht alle Tabellen übertragen werden, sondern es reichen ein paar bestimmte Tabellen.


## Scanmanager

xpectoPro bietet Ihnen ein Dokumentenmanagementsystem (DMS),  um Ihre Dokumente zu digitalisieren,  archivieren und strukturiert zuzuweisen.
Um die Möglichkeit zur Aufnahme von Dokumenten in der Software und deren Verwaltung übernimmt xpectoPro Dokumentenmanagement Aufgaben um die Arbeitseffizienz zu steigern.

Mit dem xpecto Scanmanager haben Sie die Möglichkeit eingescannte Dokumente manuell oder automatisch zuzuweisen. 

In der klassischen Menü-Ansicht kann der Scanmanager über Menüleisten *Import/Export → Scanmanager*. 

In der modernen Menü-Ansicht kann der Scanmanager über die Registerkarte *Datenbearbeitung* Gruppe *Import / Export* erreicht werden.

![](http://xpecto.github.io/docs/img/img_1461914112391.png)

Starten Sie der Scanmanamger und wählen unter dem Reiter *Scans* die Quelle wo die einscannten Dateien abgelegt sind. Klicken Sie dann auf *Start*. Dieser Pfad kann über Menü *Extras → Einstellungen → Feldgruppe Pfade* geändert werden.

![](http://xpecto.github.io/docs/img/img_1461837469559.png)

Falls auf dem eingescannten Dokument kein Barcode vorhanden ist, über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441970891993.png), kann der Barcode manuell eingegeben werden.

![](http://xpecto.github.io/docs/img/img_1421750317812.png)

Wechseln Sie dann in dem Reiter *Zuweisung*. 

Mit einem Doppelklick auf den gewünschten *Kunde, Vertrag, Vermittler, Interessenten, Ereignisse Verträge* wird der für die Zuweisung bestimmter Speicherort gewählt.

![](http://xpecto.github.io/docs/img/img_1461914187639.png)

Durch die Betätigung der Schaltfläche *Speichern* wird das ausgewählte Dokument der Speicherort zugewiesen.

Das Dokument dann bei *Kunde, Vertrag, Vermittler, Interessenten, Ereignisse Verträge* in der Hauptmaske unter dem Reiter *Ereignisse* angezeigt.


**Ausdruck von Barcode-Aufkleber**

Die Dokumente können automatisch über den Barcode erkannt und anhand der eingelesenen ID im Barcode automatisch dem entsprechenden Ereignis zugewiesen werden. Dabei wird das versendete Dokument, wenn es über xpectoPro wurde, durch das eingescannte Dokument ersetzt. Wurde nur ein Barcodelabel registriert bzw. gedruckt und auf das Dokument (vor dem einscannen) aufgeklebt, so wird hier beim Ereignis ebenfalls die Datei zugeordnet.
Zum Ausdrucken eines Barcodes über einen Labeldrucker (z. B. DymoLabel Writer) wählen Sie in der Hauptmaske von xpectoPro einen Datensatz aus für den Sie einen Barcode ausdrucken möchten, z. B. einen Vertrag. 
In der klassischen Menü-Ansicht klicken Sie in der Symbolleiste auf dasSymbol ![](http://xpecto.github.io/docs/img/img_1443802699735.png). 

In der modernen Menü-Ansicht kann der Barcode-Aufkleber über die Registerkarte *Schnellzugriff* Gruppe *Schnelldruck*  betätigt werden.

![](http://xpecto.github.io/docs/img/img_1461915015500.png)

Wählen Sie danach eine (Ereignis-)art aus und bestätigen diese durch einen klicken Sie auf *OK.* 

Anschließend wird der Barcode ausgedruckt und Sie können diesen auf Ihr Dokument aufkleben. Danach können Sie über den Scanmanager das Dokument einscannen und diesem Datensatz zuordnen.

## Kontodaten importieren

Dieses Modul dient dem Import von Bankbewegungsdaten mittels Export-Dateien aus E-Banking-Programmen. Der Import von Bankbewegungen geschieht in zwei Schritten. Im ersten Schritt (siehe diesen Menüpunkt) werden die Bewegungsdaten in eine temporäre Tabelle importiert. Im zweiten Schritt (siehe nachfolgendes Menüpunkt: *Kontodaten zuweisen*), werden aus den Datensätzen der temporären Tabelle Buchungssätze erzeugt.

In der klassischen Menü-Ansicht ist der Import über Menü *Import/Export → Kontodaten importieren*.

In der modernen Menü-Ansicht ist diese Funktion über die Registerkarte *Buchhaltung* Gruppe *Kontodaten* zu finden.

![](http://xpecto.github.io/docs/img/img_1461915546419.png)

Starten Sie den Dialog *Buchungsdaten importieren* und wählen Sie das Produkt aus, zu dem die Kontodaten importiert werden sollen, die Datei die die Bankbewegungen enthält sowie das Importkonto (Bankkonto), von dem die Buchungen stammen.

Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441983048557.png) um die zu importierende Datei auszuwählen.

![](http://xpecto.github.io/docs/img/img_1461916837261.png)

Je nach Dateiformat der zu importierenden Daten müssen das Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. Enthalten die zu importierenden Daten Datensätze, die sich bereits in der verwendeten Datenbank befinden, so setzen Sie ein Häkchen bei *Datei enthält alte Daten*. Dies verhindert die doppelte Anlage bereits vorhandener Datensätze (bereits vorhandene Datensätze werden durch einen Abgleich-Algorithmus erkannt und übersprungen). Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. 
Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442233708499.png) werden die Importdaten (bei Verwendung der richtigen Trennzeichen bzw. Textzeichen) als Tabelle angezeigt. 
*Schritt 2: Importparameter festlegen* hier muss das Umsatzkonto festgelegt werden. Das ist das Gegenkonto für die Umsätze die importiert werden.
Weisen sie nun die Spalten der Importdatei den passenden Spalten der Datenbank zu - *Schritt 3: Spalten zuweisen*. Bei Dateien im  MT940 Bankformat wird die Spaltenzuordnung automatisch vorgeschlagen.
Nachdem alle Spalten zugewiesen sind, starten Sie den Import durch die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442233746695.png). 
Bankbewegungen, die im Verwendungszweck eine Vertragsnummer enthalten, werden dabei automatisch dem angegebenen Vertrag zugewiesen.

![](http://xpecto.github.io/docs/img/img_1441983215647.png)

Bestätigen Sie obige Meldung mit *Weiter zu Kontodaten zuweisen*. Die Bankbewegungen/Importdaten sind nun erfolgreich in die temporäre Tabelle importiert worden. 

Achtung: Der Import der Buchungen ist an dieser Stelle noch nicht vollständig. Daten, die importiert wurden, aber noch nicht übernommen wurden, werden bei Berechnungen noch nicht berücksichtigt. Die importierten Daten werden hier lediglich in eine temporäre Tabelle geschrieben, sie müssen später noch über das Modul *Kontodaten zuweisen* in die Buchungstabelle übertragen werden (siehe nachfolgenden Menüpunkt: *Kontodaten zuweisen*).


## Kontodaten zuweisen

In diesem Modul werden aus der vorher in eine temporäre Tabelle, importierten Buchungen/Bankbewegungen Buchnungssätze erzeugt und den korrekten Verträgen/Beteiligungen/Produkten zugewiesen. Dabei müssen Buchungen die noch nicht automatisch einem Vertrag zugewiesen wurden, manuell zugewiesen werden.

In der modernen Menü-Ansicht starten Sie den Dialog *importierte Buchungen zuweisen* über Menü *Import/Export → Kontodaten zuweisen*.

In der klassischen Menü-Ansicht wird der Dialog über Registerkarte *Buchhaltung* Gruppe *Kontodaten* Funktion *Verbuchung* gestartet.

![](http://xpecto.github.io/docs/img/img_1461921052626.png)

Klicken  Sie auf die Funktion Verbuchung um mit der Kontodaten zuweisen anzufangen.

In dem Dialog *Buchungen zuweisen* wird die Liste der Produkte mit ihre offenen und geparkte Buchungen angezeigt.

![](http://xpecto.github.io/docs/img/img_1461921347593.png)

Die Schaltfläche Rundruf starten ![](http://xpecto.github.io/docs/img/img_1461922190992.png) dient dazu die Kontobewegungen für den markierten Produkt bei der Bank abzufragen. 

Ein Rundruf für alle Produkte kann über die Registerkarte *Buchhaltung* Gruppe *Kontodaten* Funktion *Rundruf* gestartet werden.

![](http://xpecto.github.io/docs/img/img_1461922444175.png)


Durch einen Klick auf  *OK* werden Sie zum Dialog *importierte Buchungen zuweisen* weitergeleitet. 
Der Dialog *importierte Buchungen zuweisen* enthält die Reiter *Buchungen anzeigen* und *geparkte Buchungen anzeigen*.

![](http://xpecto.github.io/docs/img/img_1461924039863.png)

Unter dem Reiter *Buchungen anzeigen* werden die Details der Buchung und in der Mitte die Navigation, mit der Pfeilen können Sie durch die Buchungen blättern. 
In der Feldgruppe *Buchung* sehen Sie den Zahlungspflichtigen/Kontoinhaber/Absender, den Verwendungszweck und die Details der Buchung. Mit einem Doppelklick auf einzelne Wörter wird das Wort als Suchkriterium verwendet. Klicken Sie mit der Maus auf Teile der Buchungsdaten wie z.B. Name um alle Verträge mit Vertragsbezeichner zu erhalten. 

![](http://xpecto.github.io/docs/img/img_1461923077386.png)

Mit einem Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442307719407.png) werden aus allen Bankbewegungen, die beim Import bereits einem Vertrag zugewiesen wurden, automatisch Buchungssätze erzeugt und gespeichert. Dazu muss zu dem jeweiligen Produkt hinterlegt sein, welche Kontierung hier verwendet werden soll. 
Das zu verwendende Konto wird in der Produktmaske (*Datei → Produkte*) auf dem Reiter *Allgemein* unter *Konto RZ* eingetragen. 

![](http://xpecto.github.io/docs/img/img_1461923339214.png)

Neben der Möglichkeit eine neue Buchung anzulegen können Sie die Kontobewegungen über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461923451087.png) direkt bei der Bank abfragen.  Es wird ein Kontorundruf durchgeführt. Die gefundene Buchungen werden von der Bank dann abgeholt und in der Liste eingefügt.

Mit einem Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442404617262.png) werden Sie zu dem Stapelbuchungsdialog weitergeleitet (siehe Handbuch *Bearbeiten → Stapelbuchung*). 

In der untere Hälfte des Dialogs *importierte Daten zuweisen* sehen Sie die Liste der Buchungen mit der Vorschlag wie die Buchungen verbucht werden sollen. 

![](http://xpecto.github.io/docs/img/img_1461924691118.png)

Im Bereich unten kann das Konto für den zu erzeugenden Buchungssatz ausgewählt werden. Werden hier mehrere Zeilen eingetragen, so wird die Bankbuchung in mehrere Buchungssätze gesplittet. Die Aufteilung der Beträge muss dabei manuell eingetragen werden. Der Buchungstext kann per Hand angepasst werden.

Die Schaltfläche *offene Posten abfragen* dient dazu um offene Posten für diesen Vertrag anzuzeigen und die Schaltfläche *Rückbuchung zuordnen* dient dazu die geschlossene Posten für den markierter Vertrag anzuzeigen.

Über die Schaltfläche *Sammelauftrag auflösen* können Sie aus einem Zahlungsauftrag mehrere Einzelaufträge wie Überweisungen oder Lastschriften erstellen. 

![](http://xpecto.github.io/docs/img/img_1442411007721.png)

Markierte Buchungen, die nicht gespeichert werden sollen, können mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461925093310.png) gelöscht werden.

*Buchungen aufteilen* teilt die Buchung in 2 Buchungen auf. Der Aufteilungsbetrag kann eingegeben werden. Die so entstandene Buchungen können dann wieder verbucht werden.

*Buchungen übertragen* damit werden die Buchungen von anderen Fonds auf einen anderen übertragen. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442406481698.png), werden die Buchungen für spätere Verbuchungen zugänglich gemacht. Die werden dann sichtbar unter dem Reiter *geparkte Buchungen anzeigen.*

Um den Vorgang einem Prozess zuzuweisen, setzen Sie in der Checkbox *Prozess starten* ein Häkchen. Der Prozess wird dann in der Wiedervorlage-Liste, bei der verantwortlichen Person angezeigt.

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442236615351.png), speichern Sie die zum Vertrag zugewiesenen Buchungen (das Speichern ist nur möglich, wenn die Summe der eingegebenen Split-Beträge exakt den Buchungsbetrag ergibt). Nach erfolgreichen Speichern wird die nächste Import-Buchung angezeigt. 
Alle gespeicherten Buchungen werden in die interne Buchhaltung aufgenommen (siehe Hanbuch *Bearbeiten → Stapelbuchung* und unter Vertragsmaske Reiter *Buchungsdaten* angezeigt.

Eine falsch importierte Buchung kann im Nachhinein gelöscht werden, und zwar in dem Dialog *Stapelbuchung*. Der Dialog kann über *Bearbeiten → Stapelbuchung* oder über *Bearbeiten → Beteiligungs-/Vertragsbuchungen* geöffnet werden. Markieren Sie hier die gewünschte Buchung und klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442912298087.png). 

## Kunden- und Vertragsdaten importieren

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


## Allgemeiner Import

Dieses Modul dient dem Import beliebiger Datentabellen. Bei diesem Import ist bei der Konfiguration der Parameter sowie bei der Zuordnung der Spalten analog zum Kunden- und Vertragsdaten-Import (siehe vorstehendes Kapitel Handbuch *Import/Export → Kunden- und Vertragsdaten importieren*) zu verfahren.

![](http://xpecto.github.io/docs/img/img_1461928458647.png)

In der klassischen Menü-Ansicht kann der Dialog beliebige Tabellen importieren über Menü Import/Export → Allgemeiner Import gestartet werden.

In der modernen Menü-Ansicht kann der Dialog über die Registerkarte *Datenbearbeitung* Gruppe *Import / Export* Funktion *Datenimport* gestartet werden.

![](http://xpecto.github.io/docs/img/img_1461928879950.png)


Die in dem Dialog eingegebene  Einstellungen können gespeichert werden und wieder verwendet werden.
Mit einem Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441981434180.png) kann der Name für eine neue Einstellung angegeben. Geben Sie für den Dialog nötigen Parameter und dann speichern. 

![](http://xpecto.github.io/docs/img/img_1461929772812.png)

Der Import kann durch einen Klick auf die Schaltfläche *Import starten* gestartet werden.

## Buchungsexport

Dieser Menüpunkt führt direkt zur *Buchungen exportieren*-Maske auf dem Stapelbuchungs-Dialog (siehe Handbuch *Bearbeiten → Stapelbuchung Reiter Buchungen exportieren*).

Diese Funktion kann unter der klassischen Menü-Ansicht Import/Export → Buchungsexport gestartet werden.

In der modernen Menü-Ansicht ist die Funktion unter Karteireiter *Buchhaltung* Gruppe *Buchungsdaten* Funktion *Export* zu finden.

![](http://xpecto.github.io/docs/img/img_1461930653231.png)

Der Reiter *Buchungen exportieren* dient der Übergabe von Buchungssätze an das Buchhaltungssystem des Fonds bzw. eines Steuerberaters. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden nur Buchungen angezeigt, die bereits festgeschrieben sind. Dadurch ist sichergestellt, dass keine Buchungssätze die sich noch nicht im Buchungsjournal befinden, an externe Buchhaltungssysteme übergeben werden können. 

![](http://xpecto.github.io/docs/img/img_1461685921010.png)

Nach dem Aufruf des Dialogs ist der Radiobutton in der Feldgruppe *nicht exportiert* aktiv. Dadurch werden nur Buchungssätze exportiert, die vorher noch nicht exportiert wurden. Soll ein bereits erfolgter Buchungsexport wiederholt werden so muss der Filter *Exportiert* dementsprechend angepasst werden. 
Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439892039334.png) wird eine Datei im CSV-Format erzeugt, die die aufgelisteten Buchungssätze enthält. Dabei wird automatisch der Exportzeitpunkt und der auszuführende Benutzer in die betroffenen Buchungsdatensätze eingetragen. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439894313567.png) wird dieselbe Export-Datei erzeugt, jedoch ohne Informationen in den Buchungsdatensatz einzutragen.


