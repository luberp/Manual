In diesem Modul werden aus der vorher importierten Buchungen/Bankbewegungen Buchnungssätze erzeugt und den korrekten Verträgen/Beteiligungen/Produkten zugewiesen. Dabei müssen Buchungen die noch nicht automatisch einem Vertrag zugewiesen wurden, manuell zugewiesen werden.

In der modernen Menü-Ansicht starten Sie den Dialog *importierte Buchungen zuweisen* über Menü *Import/Export → Kontodaten zuweisen*.

In der klassischen Menü-Ansicht wird der Dialog über Registerkarte *Buchhaltung* Gruppe *Kontodaten* Funktion *Verbuchung* gestartet.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Kontodaten_Menue.png)

Klicken  Sie auf die Funktion Verbuchung um mit der Zuweisung der Kontodaten zu beginnen.

Im Dialog *Buchungen zuweisen* wird die Liste der Produkte mit offenen sowie geparkte Buchungen angezeigt.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Buchungen_zuweisen.png)

Die Schaltfläche Rundruf starten ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Rundruf_starten.png) dient dazu die Kontobewegungen für das markierte Produkt bei der Bank abzufragen. 


----------


![](http://xpecto.github.io/docs/xpecto/Grafiken/gr_gluehbirne.jpg)Ein Rundruf für alle Produkte kann über die Registerkarte *Buchhaltung* Gruppe *Kontodaten* Funktion *Rundruf* gestartet werden.


![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Rundruf_Menue.png)


----------


Durch einen Klick auf  *OK* werden Sie zum Dialog *importierte Buchungen zuweisen* weitergeleitet. 
Der Dialog *importierte Buchungen zuweisen* enthält die Reiter *Buchungen anzeigen* und *geparkte Buchungen anzeigen* 
![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Geparkte_Buchungen.png).

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Buchungen_zuweise_Main.png)

Unter dem Reiter *Buchungen anzeigen* werden Details der Buchungen und in der Mitte die Navigation angezeigt, mit den Pfeiltasten oben in der Menüleiste können Sie durch die Buchungen blättern. 
In der Feldgruppe *Buchung* sehen Sie:

 - den Zahlungspflichtigen
 - Kontoinhaber
 - Absender
 - Verwendungszweck
 - Details zur Buchung

Mit einem Doppelklick auf einzelne Wörter wird das Wort als Suchkriterium verwendet. Klicken Sie mit der Maus auf Teile der Buchungsdaten wie z.B. die Vertragsnummer, diese wird dann als Suchkriterium verwendet.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Buchung_Suche.png)

Mit einem Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442307719407.png) werden aus allen Bankbewegungen, die beim Import bereits einem Vertrag zugewiesen wurden, automatisch Buchungssätze erzeugt und gespeichert. Dazu muss zu dem jeweiligen Produkt hinterlegt sein, welche Kontierung hier verwendet werden soll. 

Das zu verwendende Konto wird in der Produktmaske in der klassischen Ansicht unter (*Datei → Produkte*) auf dem Reiter *Allgemein* unter *Konto RZ* eingetragen. 

In der modernen Menüansicht erreichen Sie diese Funktion unter *Stammdaten -> Produkte -> Allgemein -> Buchhaltung / Konten -> Konto RZ*.
![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Produkte_Menue.png) -> ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Konto_RZ.png)

Neben der Möglichkeit eine neue Buchung anzulegen können Sie die Kontobewegungen über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461923451087.png) direkt bei der Bank abfragen.  Es wird ein Kontorundruf durchgeführt. Die gefundene Buchungen werden von der Bank dann abgeholt und in der Liste eingefügt.

Mit einem Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442404617262.png) werden Sie zu dem Stapelbuchungsdialog weitergeleitet (siehe Handbuch *Bearbeiten → Stapelbuchung*). 

In der untere Hälfte des Dialogs *importierte Daten zuweisen* sehen Sie die Liste der Buchungen mit dem Vorschlag wie die Buchungen verbucht werden soll. 

![](http://xpecto.github.io/docs/img/img_1461924691118.png)

Im Bereich unten kann das Konto für den zu erzeugenden Buchungssatz ausgewählt werden. Werden hier mehrere Zeilen eingetragen, so wird die Bankbuchung in mehrere Buchungssätze gesplittet. Die Aufteilung der Beträge muss dabei manuell eingetragen werden. Der Buchungstext kann per Hand angepasst werden.

Die Schaltfläche *offene Posten abfragen* dient dazu um offene Posten für diesen Vertrag anzuzeigen und die Schaltfläche *Rückbuchung zuordnen* dient dazu die geschlossene Posten für den markierter Vertrag anzuzeigen.

Über die Schaltfläche *Sammelauftrag auflösen* können Sie aus einem Zahlungsauftrag mehrere Einzelaufträge wie Überweisungen oder Lastschriften erstellen. 

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Zahlungsverkehr_auswaehlen.png)

Buttons der Funktionsleiste:

|  Schaltfläche         |    Funktion     |  
| ------------- |:-------------| 
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Button_offene_Posten_abfragen.png)     |  Offene Posten für diesen Vertrag anzuzeigen |
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Button_Rückbuchung_zuordnen.png)|Die markierte Position einem geschlossenen Posten zuordnen  | 
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Button_Sammelauftrag_aufloesen.png)| Zahlungsverkehr einzeln abarbeiten | 
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Button_Buchung_loeschen.png)  | Selektierte Buchung(en) löschen | 
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Button_Buchung_aufteilen.png)  | Selektierte Buchung splitten | 
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Button_Buchung_uebertragen.png)  |Überträgt die Buchung auf einen differenten Fond| 
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Button_Buchung_parken.png)   | Die selektierte Buchung wird geparkt und kann über den Reiter *geparkte Buchungen anzeigen* abgearbeitet werden. | 

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Prozess_starten.png)
Um den Vorgang einem Prozess zuzuweisen, setzen Sie in der Checkbox *Prozess starten* ein Häkchen. Der Prozess wird dann in der Wiedervorlage-Liste, bei der verantwortlichen Person angezeigt.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Speichern.png)

Mit der Schaltfläche *Speichern*, speichern Sie die zum Vertrag zugewiesenen Buchungen. Nach erfolgreichen Speichern wird die nächste Import-Buchung angezeigt. 

----------
![](http://xpecto.github.io/docs/xpecto/Grafiken/gr_gluehbirne.jpg)Ein Speichern ist nur möglich, wenn die Summe der gesplitteten Beträge exakt dem Buchungsbetrag entspricht.

----------

Alle gespeicherten Buchungen werden in die interne Buchhaltung aufgenommen (siehe Handbuch *Bearbeiten → Stapelbuchung* oder *Buchhaltung -> Buchungsdaten -> Stapel* angezeigt.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Buchung_loeschen.png)

Eine falsch importierte Buchung kann im Nachhinein gelöscht werden, und zwar in dem Dialog *Stapelbuchung*. Der Dialog kann über *Bearbeiten → Stapelbuchung* oder über *Bearbeiten → Beteiligungs-/Vertragsbuchungen* geöffnet werden. Markieren Sie hier die gewünschte Buchung und klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/xpecto/Import_Export/Kontodaten_zuweisen/Buchung_loeschen_.png). 