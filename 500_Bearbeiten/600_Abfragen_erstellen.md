xpectoPro bietet einen anwenderfreundlichen Abfrage-Editor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt, eigene Datenbankabfragen bzw. Auswertungen zu erstellen.
Sie erreichen den Abfrage-Editor über den Menüpunkt *Bearbeiten → Abfragen erstellen*.

Nach dem öffnen des *Abfragen und Liste* Editors wird der Bedingungsassistent mit einem Bedingungsblock angezeigt, der bereits eine Bedingung enthält. Eine Bedingung ist definiert durch einen Feldnamen (links), einen Bedingungstyp (mitte) und einem vom Anwender einzugebende Vergleichswert. 

![](http://xpecto.github.io/docs/img/img_1439279198546.png)

Bedingungszeilen sind in Blöcken zusammengefasst. Am oberen Rand eines Blocks wird der verwendete Gruppierungstyp angezeigt. Mögliche Typen sind:

 - jede der Bedingungen trifft zu (AND)  
 - eine oder mehrere Bedingungen treffen zu (OR)
 
![](http://xpecto.github.io/docs/img/img_1439278901176.png)

Über die Schaltfläche “*Feld hinzufügen*” wird einem Block eine Bedingung hinzugefügt. Über die Schaltfläche “*Block hinzufügen*” wird einem Block ein Unterblock hinzugefügt. Auf diese Weise kann für einen Teil der Bedingungen ein anderer Gruppierungstyp verwendet werden.

Die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1419329462773.png) löscht eine Bedingungszeile oder einen Block.

Durch Klick auf den Feldnamen oder den Bedingungstyp kann eine Bedingung angepasst werden. Ein Klick auf der Feldnamen öffnet ein Kontextmenü zur Auswahl des gewünschten Feldnamens. Per Klick auf den Bedingungstyp kann der Typ ausgewählt werden. Folgende Bedingungstypen stehen zur  Verfügung:

|  Bedingungstypen           | 
| ------------- |
|   entspricht einem der folgenden Werte     | 
|    endet mit   | 
|beginnt mit|
|ist leer|
|entspricht keinem der folgenden Werte|
|enthält nicht|
|endet nicht mit |
|beginnt nicht mit|
|ist nicht leer|

Schließlich werden in den Eingabefeldern die Vergleichswerte der jeweiligen Bedingung eingetragen.

Beispiel: Sie wollen wissen, welche Kunden des Vermittlers VP0001 im Zeitraum 01.12.2014 bis 01.01.2015 Verträge des Produkts *TRI1, Top Return Invest I* abgeschlossen hat.
 
Starten Sie den Abfrage-Editor und passen Sie die vorgegebene Bedingungszeile folgendermaßen an: klicken Sie auf den Feldnamen *Vertrags-Nr* und wählen im darauf folgenden Kontextmenü das Feld *Vertriebspartner → Betreuer-Nr.* Tragen Sie in das Eingabefeld die Vermittlernummer ein.

![](http://xpecto.github.io/docs/img/img_1431932441285.png)

Legen Sie über “*Feld hinzufügen*” zwei weitere Bedingungszeilen an, wählen Sie mit der oben beschriebenen Methode die Felder: *Produkte → Produktname* und *Vertragsdaten → Abschlussdatum* und tragen Sie die entsprechenden Werte in die zugehörigen Eingabefelder ein.

Klicken sie nun auf *Weiter*. Auf der nächsten Seite können die Datenbankfelder, die in der Anzeige des Abfrageergebnisses ausgegeben werden sollen, durch anhaken ausgewählt werden.

![](http://xpecto.github.io/docs/img/img_1431933240955.png)

In diesem Beispiel sind *Bezeichner, Kundennummer, Abschlussdatum, Produkt, Tarif, Vertragsnummer, Betreuernummer, Produktname* ausgewählt.

Klicken sie nun erneut auf *Weiter*, um zur Anzeige des Abfrageergebnisses zu gelangen. In der Ergebnisanzeige wird im oberen Bereich die anhand der vorher definierten Parameter automatisch generierte Datenbankabfrage angezeigt. Darunter erscheint eine Liste mit dem Ergebnis der Abfrage.

![](http://xpecto.github.io/docs/img/img_1439281607237.png)

Die dargestellten Datensätze können über Betätigung der entsprechenden Schaltflächen  *CSV*, *SQL* oder *Excel* weitergegeben werden. Ein Klick auf *Excel* oder *CSV* öffnet die ermittelten Daten direkt in Excel und Sie können die Daten dann dort weiterverarbeiten.  

Die Daten können auch direkt an eine Kampagne übergeben werden. Über die Schaltfläche *Kampagne* kann eine Kampagne gestartet werden (siehe  Menüleiste *Bearbeiten → Kampagnen*). 

Über die *SQL* Schaltfläche können Sie *Insert Statements erstellen*, Daten in *Importdialog laden* oder die *Aktion abbrechen*. 

![](http://xpecto.github.io/docs/img/img_1431933091869.png)

In dem Importdialog können Sie z.B. Datensätze importieren, Tabellen importieren in der Datenbank (siehe *Import/Export → Allgemeiner Import*). 

![](http://xpecto.github.io/docs/img/img_1439282833536.png)

Um Datensätze zu importieren, wählen Sie das Produkt aus, zu dem die Datensätze importiert werden sollen. 

Wenn Sie Tabellen aus einer Datei, in der Datenbank importieren wollen, dann klicken Sie auf die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1421152862771.png) um die zu importierende Datei auszuwählen.

Je nach Dateiformat der zu importierenden Daten müssen die Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. 
Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. 
Durch betätigen von *Vorschau* werden die Importdaten als Tabelle angezeigt.
 Um den Import zu starten klicken Sie auf die Schaltfläche: ![](http://xpecto.github.io/docs/img/img_1421159892128.png).

Nachdem Sie die folgende Meldung mit *OK* bestätigt haben sind die angezeigten Daten importiert. 

![](http://xpecto.github.io/docs/img/img_1421160002075.png)

Durch Betätigung von ![](http://xpecto.github.io/docs/img/img_1431935009760.png)  wird der Abfrage-Editor beendet.
