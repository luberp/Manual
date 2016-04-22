Der Daten-Import/Export gehört zu den wichtigsten Funktionen von xpectoPro. Anwendung finden diese Funktionen z.B. beim Import von Bankbewegungen oder beim Import von Vermittler-, Vertrags- oder Kundenbeständen aus andere Systemen.

Bei einigen der beschriebenen Import-Funktionen werden unter anderem Buchungsdaten importiert. Hierbei entstehen Erfassungen, die danach noch in einem weiteren Arbeitsschritt bearbeitet werden können.


## Tabellen synchronisieren

Eine Eingenschaft von xpectoPro ist die Mehrstandortfähigkeit. Das Synchronisations-Modul dient dem Export von Datensätzen an den xpecto Webserver sowie dem Import von Daten an anderen Standorten über den xpecto Webserver.

Welche Tabellen Sie synchronisieren wollen, kann durch die Optionen die der Filter anbietet, gesteuert werden.

![](http://xpecto.github.io/docs/img/img_1421748051531.png).

Für die Synchronisierung können Profile angelegt werden in denen nur bestimmte Tabellen für die Synchronisierung ausgewählt werden. So werden dann z.B. nicht alle sondern nur ein paar der Tabellen synchronisiert. Dies ist praktisch, wenn beispielsweise die Weboberflächen für Kunden- bzw. Vermittlerportal angepasst werden. In diesem Fall müssen schließlich nicht alle Tabellen übertragen werden, sondern es reichen ein paar bestimmte Tabellen.

## Scanmanager

xpectoPro bietet Ihnen ein Dokumentenmanagementsystem (DMS),  um Ihre Dokumente zu digitalisieren,  archivieren und strukturiert zuzuweisen.

Mit dem xpecto ScanManager haben Sie die Möglichkeit eingescannte Dokumente manuell oder automatisch zuzuweisen. 
Starten sie den *ScanManager* über Menüleisten *Import/Export → Scanmanager*. In dem Reiter *Scans* können Sie eine Scanquelle auswählen. Geben Sie hier die Scanquelle an, wo die gescannte Dokumente gespeichert sind. Dieser Pfad kann über *Extras → Einstellungen* geändert werden.

![](http://xpecto.github.io/docs/img/img_1441965444877.png)

Falls auf dem eingescannten Dokument kein Barcode vorhanden ist, über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441970891993.png), kann der Barcode manuell eingegeben werden.

![](http://xpecto.github.io/docs/img/img_1421750317812.png)

Klicken Sie auf *Start* um automatisch die Dokumente zuzuweisen. Die Dokumente können automatisch über den Barcode erkannt und anhand der eingelesenen ID im Barcode automatisch dem entsprechenden Ereignis zugewiesen werden. Dabei wird das versendete Dokument, wenn es über xpectoPro wurde, durch das eingescannte Dokument ersetzt. Wurde nur ein Barcodelabel registriert bzw. gedruckt und auf das Dokument (vor dem einscannen) aufgeklebt, so wird hier beim Ereignis ebenfalls die Datei zugeordnet.

Über dem Reiter Zuweisung können Sie die Dokumente die kein Barcode enthalten zuweisen.

![](http://xpecto.github.io/docs/img/img_1441965548893.png)


**Ausdruck von Barcode-Aufkleber**
Zum Ausdrucken eines Barcodes über einen Labeldrucker (z. B. DymoLabel Writer) wählen Sie in der Hauptmaske von xpectoPro einen Datensatz aus für den Sie einen Barcode ausdrucken möchten, z. B. einen Vertrag. Klicken Sie anschließend in der Symbolleiste auf dasSymbol ![](http://xpecto.github.io/docs/img/img_1443802699735.png). Wählen Sie danach eine (Ereignis-)art aus und bestätigen diese durch einen klicken Sie auf *OK.* 

![](http://xpecto.github.io/docs/img/img_1441971165729.png)

Anschließend wird der Barcode ausgedruckt und Sie können diesen auf Ihr Dokument aufkleben. Anschließend können Sie über den Scanmanager das Dokument einscannen und diesem Datensatz zuordnen.

## Kontodaten importieren

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

Bestätigen Sie obige Meldung mit *Weiter zu Kontodaten zuweisen*. Die Bankbewegungen/Importdaten sind nun erfolgreich in die temporäre Tabelle importiert worden. 

Achtung: Der Import der Buchungen ist an dieser Stelle noch nicht vollständig. Daten, die importiert wurden, aber noch nicht übernommen wurden, werden bei Berechnungen noch nicht berücksichtigt. Die importierten Daten werden hier lediglich in eine temporäre Tabelle geschrieben, sie müssen später noch über das Modul *Kontodaten zuweisen* in die Buchungstabelle übertragen werden (siehe nachfolgenden Menüpunkt: *Kontodaten zuweisen*).


## Kontodaten zuweisen

In diesem Modul werden aus der vorher in eine temporäre Tabelle, importierten Buchungen/Bankbewegungen Buchnungssätze erzeugt und den korrekten Verträgen/Beteiligungen/Produkten zugewiesen. Dabei müssen Buchungen die noch nicht automatisch einem Vertrag zugewiesen wurden, manuell zugewiesen werden.

Starten Sie den Dialog *importierte Buchungen zuweisen* über Menü *Import/Export → Kontodaten zuweisen*.

![](http://xpecto.github.io/docs/img/img_1442306438835.png)

In der untere Hälfte sehen Sie die Liste der Buchungen mit der Vorschlag wie die Buchungen verbucht werden sollen. Mit einem Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442307719407.png) werden aus allen Bankbewegungen, die beim Import bereits einem Vertrag zugewiesen wurden, automatisch Buchungssätze erzeugt und gespeichert. Dazu muss zu dem jeweiligen Produkt hinterlegt sein, welche Kontierung hier verwendet werden soll. Das zu verwendende Konto wird auf der Produktmaske (*Datei → Produkte*) auf dem Reiter *Allgemein* unter *Konto RZ* eingetragen. 

Neben der Möglichkeit eine neue Buchung anzulegen können Sie die Kontobewegungen über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442404114905.png) direkt bei der Bank abfragen.  Der folgende Dialog informiert über den Anzahl der importierten Buchungen. Die werden dann in der Liste der Buchungen die noch nicht verbucht sind, eingefügt. 

![](http://xpecto.github.io/docs/img/img_1442408739054.png)

Hier können Sie direkt durch Buchungen blättern ![](http://xpecto.github.io/docs/img/img_1442309271825.png).

Mit einem Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442404617262.png) werden Sie zu dem Stapelbuchungsdialog weitergeleitet (siehe *Bearbeiten → Stapelbuchung*). 

In der Feldgruppe *Buchung* sehen Sie den Zahlungspflichtigen/Kontoinhaber/Absender, den Verwendungszweck und die Details der Buchung.

![](http://xpecto.github.io/docs/img/img_1442410642193.png)
 
Mit einem Doppelklick auf einzelne Wörter wird das Wort als Suchkriterium verwendet. 

 Klicken Sie mit der Maus auf Teile der Buchungsdaten wie z.B. Name um alle Verträge mit Vertragsbezeichner zu erhalten. Ordnen Sie nun anhand der Zahlungsdaten die importierten Buchungsdaten ihrem zugehörigen Vertrag zu. Die Zuordnung geschieht durch Selektieren eines Vertrags in der angezeigten Vertrags- und Beteiligungsliste.
 
![](http://xpecto.github.io/docs/img/img_1442410773367.png)

Im Bereich unten kann das Konto für den zu erzeugenden Buchungssatz ausgewählt werden. Werden hier mehrere Zeilen eingetragen, so wird die Bankbuchung in mehrere Buchungssätze gesplittet. Die Aufteilung der Beträge muss dabei manuell eingetragen werden. Der Buchungstext kann per Hand angepasst werden.

Über die Schaltfläche *Sammelauftrag auflösen* können Sie aus einem Zahlungsauftrag mehrere Einzelaufträge wie Überweisungen oder Lastschriften erstellen. 

![](http://xpecto.github.io/docs/img/img_1442411007721.png)

Markierte Buchungen, die nicht gespeichert werden sollen, können mit der Schaltfläche![](http://xpecto.github.io/docs/img/img_1442237227264.png) gelöscht werden.

*Buchungen aufteilen* teilt die Buchung in 2 Buchungen auf. Der Aufteilungsbetrag kann eingegeben werden. Die so entstandene Buchungen können dann wieder verbucht werden.

*Buchungen übertragen* damit werden die Buchungen von anderen Fonds auf einen anderen übertragen. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442406481698.png), werden die Buchungen für spätere Verbuchungen zugänglich gemacht. Die werden dann sichtbar unter dem Reiter *geparkte Buchungen anzeigen.*

Um den Vorgang einem Prozess zuzuweisen, setzen Sie in der Checkbox *Prozess starten* ein Häkchen. Der Prozess wird dann in der Wiedervorlage-Liste, bei der verantwortlichen Person angezeigt.

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442236615351.png), speichern Sie die zum Vertrag zugewiesenen Buchungen (das Speichern ist nur möglich, wenn die Summe der eingegebenen Split-Beträge exakt den Buchungsbetrag ergibt). Nach erfolgreichen Speichern wird die nächste Import-Buchung angezeigt. 
Alle gespeicherten Buchungen werden in die interne Buchhaltung aufgenommen ( siehe *Bearbeiten → Stapelbuchung* und unter Vertrag Reiter *Buchungsdaten* angezeigt.

Eine falsch importierte Buchung kann im Nachhinein gelöscht werden, und zwar in dem Dialog *Stapelbuchung*. Der Dialog kann über *Bearbeiten → Stapelbuchung* oder über *Bearbeiten → Beteiligungs-/Vertragsbuchungen* geöffnet werden. Markieren Sie hier die gewünschte Buchung und klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442912298087.png). 

## Kunden- und Vertragsdaten importieren

Dieses Modul dient dem Import von Verträgen einschließlich Kundenstammdaten.

Wählen Sie das Produkt bzw. den Fonds, zu dem die Kundendaten importiert werden sollen. Enthält die zu importierende Datei bereits eine Produktspalte, setzen Sie in dem Checkbox  *Datei enthält Produktspalte* ein Häkchen. Hierdurch entfällt die Auswahl des Produkts. Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441889824466.png) um die zu importierende Datei auszuwählen.

Je nach Dateiformat der zu importierenden Daten müssen das Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung derAuswahlfelder entspricht dem Import einer Datei im CSV Format. Unter *Prozedur* wird die zur Verarbeitung der Daten zu verwendende Import-Prozedur ausgewählt. Import-Prozeduren müssen vorher vom xpecto Kundensupport hinterlegt werden. Enthalten die zu importierenden Daten Datensätze, die sich bereits in der verwendeten Datenbank befinden, so setzen Sie ein Häkchen bei	*vorhandene Kunden und Verträge aktualisieren*. Dies verhindert die doppelte Anlage bereits vorhandener Datensätze (bereits vorhandene Datensätze werden durch einen Abgleich-Algorithmus erkannt und aktualisiert). Unter *Schritt 2: Importparameter festlegen* kann angegeben werden, dass fehlende Verträge, Kunden oder Vermittler angelegt werden sollen. Andernfalls werden nur bestehende Datensätze aktualisiert.

![](http://xpecto.github.io/docs/img/img_1441889791683.png)

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441889857529.png) werden die Importdaten (bei Verwendung der richtigen Trennzeichen bzw. Textzeichen) als Tabelle angezeigt. Weisen sie nun die Spalten der Importdatei den passenden Spalten der Datenbank zu. Nachdem alle Spalten zugewiesen sind, starten Sie den Import durch die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441889884609.png).

Der erfolgreiche Import der Kundendaten und Vertragsdaten wird durch eine Meldung unter Angabe der Anzahl der importierten Kunden und Verträge bestätigt. Bei Fehlschlagen des Imports eines oder mehrerer Datensätze (z.B. aufgrund fehlerhafter Daten) wird eine entsprechende Meldung angezeigt, und der komplette Import abgebrochen. Prüfen Sie in diesem Fall die zu importierende Datei auf Korrektheit, oder wenden Sie sich an den xpecto Kundensupport.


## Allgemeiner Import

Dieses Modul dient dem Import beliebiger Datentabellen. Bei diesem Import ist bei der Konfiguration der Parameter sowie bei der Zuordnung der Spalten analog zum Kunden- und Vertragsdaten-Import (siehe vorstehendes Kapitel Menüpunkt: *Import/Export → Kunden- und Vertragsdaten importieren*) zu verfahren.

![](http://xpecto.github.io/docs/img/img_1441981332988.png)

 Um den allgemeinen Import verwenden zu können, kann vorher vom xpecto Kundensupport eine Verarbeitungsprozedur zur Verarbeitung der importierten Daten hinterlegt werden.
Sie können Ihre Einstellungen speichern, indem Sie mit ![](http://xpecto.github.io/docs/img/img_1441981434180.png) eine neue Einstellung erstellen, dafür einen Namen vergeben und dann speichern. 

Um den Editor zu schließe, klickenSie auf das Symbol![](http://xpecto.github.io/docs/img/img_1441981584845.png).

## Buchungsexport

Dieser Menüpunkt führt direkt zur *Buchungen exportieren*-Maske auf dem Stapelbuchungs-Dialog (Siehe "Menüpunkt: *Bearbeiten → Stapelbuchung*, Funktionsbereich: *Buchungen exportieren*).

Die Export-Funktion dient der Übergabe von Buchungssätzen an das Buchhaltungssystem des Fonds bzw. eines Steuerberaters. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden nur die Buchungen angezeigt, die bereits festgeschrieben sind. Dadurch ist sichergestellt, dass keine Buchungssätze, die sich noch nicht im Buchungsjournal befinden, an externe Buchhaltungssysteme übergeben werden können. Über weitere Filter können die zu exportierenden Buchungen ausgewählt werden. Nach dem Aufruf des Dialogs ist der Filter *nicht exportiert* aktiv. Dadurch werden nur Buchungssätze exportiert, die vorher noch nicht exportiert wurden. Soll ein bereits erfolgter Buchungsexport wiederholt werden, so muss der Filter dementsprechend angepasst werden. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441979438373.png) wird eine Datei im CSV-Format erzeugt, die die aufgelisteten Buchungssätze enthält. Dabei wird automatisch der Exportzeitpunkt und der auszuführende Benutzer in die betroffenen Buchungsdatensätze eingetragen. Über ![](http://xpecto.github.io/docs/img/img_1441979482669.png) wird dieselbe Export-Datei erzeugt, jedoch ohne Verarbeitungsinfos in den Buchungsdatensatz einzutragen.