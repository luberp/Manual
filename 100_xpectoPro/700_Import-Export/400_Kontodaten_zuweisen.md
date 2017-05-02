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