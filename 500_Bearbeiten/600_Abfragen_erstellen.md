xpectoPro bietet einen anwenderfreundlichen Abfrageeditor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt, eigene Datenbankabfragen bzw. Auswertungen zu erstellen.
Sie erreichen den Abfrageeditor über den Menüpunkt *Bearbeiten → Abfragen erstellen*.

Nach dem öffnen des Abfrageeditors wird der Bedingungs-Assistent mit einem Bedingungsblock angezeigt, der bereits eine Bedingung enthält. Bewegen Sie die Maus über Teile des Bedingungsblocks, um Tipps zu erhalten. Eine Bedingung ist definiert durch einen Feldnamen (links), einen Bedingungstyp (mitte) und einem vom Anwender einzugebende Vergleichswert. 

![](http://xpecto.github.io/docs/img/img_1433862305916.png)

Bedingungszeilen sind in Blöcken zusammengefasst. Am oberen Rand eines Blocks wird der verwendete Gruppierungstyp angezeigt. Mögliche Typen sind:

 - jede der Bedingungen trifft zu (AND)  
 - eine oder mehrere Bedingungen treffen zu (OR)
 
 ![](http://xpecto.github.io/docs/img/img_1419329260261.png) 

Über die Schaltfläche “*Feld hinzufügen*” wird einem Block eine Bedingung hinzugefügt. Über die Schaltfläche “*Block hinzufügen*” wird einem Block ein Unterblock hinzugefügt. Auf diese Weise kann für einen Teil der Bedingungen ein anderer Gruppierungstyp verwendet werden.

Die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1419329462773.png) löscht eine Bedingungszeile oder .

Durch Klick auf den Feldnamen oder den Bedingungstyp kann eine Bedingung angepasst werden. Ein Klick auf den Feldnamen öffnet ein Kontextmenü zur Auswahl des gewünschten Feldnamens. Per Klick auf den Bedingungstyp kann der Typ ausgewählt werden. Folgende Bedingungstypen stehen zur  Verfügung:


 - entspricht einem der folgenden Werte 
 - endet mit 
 - beginnt mit 
 - ist leer
 - ist nicht leer


Schließlich werden in den Eingabefeldern die Vergleichswerte der jeweiligen Bedingung eingetragen.

Betrachten wir folgendes Beispiel: 
Sie wollen wissen, welche Kunden des Vermittlers VP0001 im Zeitraum 01.12.2014 bis 31.12.2014 Verträge des Produkts “TRI1, Top Return Invest I” abgeschlossen hat.

Starten Sie den Abfrageeditor und passen Sie die vorgegebene Bedingungszeile folgendermaßen an: Klicken Sie auf den Feldnamen Vertrags-Nr und wählen im darauf folgenden Kontextmenü das Feld Vertriebspartner Betreuer-Nr. Tragen Sie in das Eingabefeld die Vermittlernummer ein.

![](http://xpecto.github.io/docs/img/img_1431932441285.png)

Legen Sie über “*Feld hinzufügen*” zwei weitere Bedingungszeilen an, wählen Sie mit der oben beschriebenen Methode die Felder Produkte Produktname und Vertragsdaten  Abschlussdatum und tragen Sie die entsprechenden Werte in die zugehörigen Eingabefelder ein.

Klicken sie nun auf Weiter. Auf der nächsten Seite können die Datenbankfelder, die in der Anzeige des Abfrageergebnisses ausgegeben werden sollen, durch anhaken ausgewählt werden.


![](http://xpecto.github.io/docs/img/img_1431933240955.png)

In diesem Beispiel sind Adresse, Bezeichner, Kundennummer des Kunden, Adresse und Bezeichner des Vertriebspartners ausgewählt.

Klicken sie nun erneut auf *Weiter*, um zur Anzeige des Abfrageergebnisses zu gelangen. In der Ergebnisanzeige wird im oberen Bereich die anhand der vorher definierten Parameter automatisch generierte Datenbankabfrage angezeigt. Darunter erscheint eine Liste mit dem Ergebnis der Abfrage.

![](http://xpecto.github.io/docs/img/img_1431932658461.png)

Die dargestellten Datensätze können über Betätigung der entsprechenden Schaltflächen  CSV, SQL oder Excel weitergegeben werden. 
Die Weitergabe der Daten ist  einfach. Ein Klick auf “*Excel*” oder “*CSV*” öffnet die ermittelten Daten direkt in Excel und Sie können die Daten dann dort weiterverarbeiten.  
Die Daten können auch direkt an eine Kampagne übergeben werden. Über die Schaltfläche Kampagne kann eine Kampagne gestartet werden (siehe *Bearbeiten → Kampagnen*). 
Über SQL Schaltfläche können Sie Insert Statement erstellen, Daten in Importdialog laden oder Aktion abbrechen.  
Mit Hilfe von Insert Statements werden neue Datensätze in eine Tabelle eingefügt. 

![](http://xpecto.github.io/docs/img/img_1431933091869.png)


Über dem Importdialog können Sie z.B. Datensätze importieren, Tabellen importieren in der Datenbank oder zwischen Datenbanken. 

![](http://xpecto.github.io/docs/img/img_1431932842038.png)

Wählen Sie das Produkt aus, zu dem die Datensätze importiert werden sollen. 

Klicken Sie auf die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1421152862771.png) um die zu importierende Datei auszuwählen.

Je nach Dateiformat der zu importierenden Daten müssen die Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. 
Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1421159835110.png) werden die Importdaten als Tabelle angezeigt.  
Starten sie den Import durch die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1421159892128.png).

Nachdem Sie die folgende Meldung mit *OK* bestätigt haben sind die angezeigten Daten importiert. 

![](http://xpecto.github.io/docs/img/img_1421160002075.png)

Durch Betätigung von ![](http://xpecto.github.io/docs/img/img_1431935009760.png)  können Sie den Abfrageeditor beenden.
