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