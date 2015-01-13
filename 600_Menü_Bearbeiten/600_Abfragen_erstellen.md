
xpectoPro bietet einen anwenderfreundlichen Abfrageeditor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt, eigene Datenbankabfragen bzw. Auswertungen zu erstellen.

Sie erreichen den Abfrageeditor über den Menüpunkt *Bearbeiten → Abfrage erstellen*.

Nach dem öffnen des Abfrageeditors wird der Bedingungs-Assistent mit einem Bedingungsblock angezeigt, der bereits eine Bedingung enthält. Bewegen Sie die Maus über Teile des Bedingungsblocks, um Tipps zu erhalten. Eine Bedingungszeile ist definiert durch einen Feldnamen (links), einen Bedingungstyp (mitte) und einem vom Anwender einzugebende Vergleichswert. 

![](http://xpecto.github.io/docs/img/img_1419329260261.png)

Bedingungszeilen sind in Blöcken zusammengefasst. Am oberen Rand eines Blocks wird der verwendete Gruppierungstyp angezeigt. Mögliche Typen sind:

 - jede der Bedingungen trifft zu (AND)   
 - eine oder mehrere Bedingungen treffen zu (OR)


Über die Schaltfläche “*Feld hinzufügen*” wird einem Block eine Bedingung hinzugefügt. Über die Schaltfläche “*Block hinzufügen*” wird einem Block ein Unterblock hinzugefügt. Auf diese Weise kann für einen Teil der Bedingungen ein anderer Gruppierungstyp verwendet werden.

Die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1419329462773.png) löscht eine Bedingungszeile.

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

![](http://xpecto.github.io/docs/img/img_1419332163233.png)

Legen Sie über “*Feld hinzufügen*” zwei weitere Bedingungszeilen an, wählen Sie mit der oben beschriebenen Methode die Felder Produktname und Abschlussdatum und tragen Sie die entsprechenden Werte in die zugehörigen Eingabefelder ein.

Klicken sie nun auf *Weiter*. Auf der nächsten Seite können die Datenbankfelder, die in der Anzeige des Abfrageergebnisses ausgegeben werden sollen, durch anhaken ausgewählt werden.

![](http://xpecto.github.io/docs/img/img_1419341604703.png)

In diesem Beispiel sind Adresse, Bezeichner, Kundennummer des Kunden, Adresse und Bezeichner des Vertriebspartners ausgewählt.

Klicken sie nun erneut auf *Weiter*, um zur Anzeige des Abfrageergebnisses zu gelangen. In der Ergebnisanzeige wird im oberen Bereich die anhand der vorher definierten Parameter automatisch generierte Datenbankabfrage angezeigt. Darunter erscheint eine Liste mit dem Ergebnis der Abfrage.


![](http://xpecto.github.io/docs/img/img_1421155722737.png)


Die dargestellten Datensätze können über Betätigung der entsprechenden Schaltflächen  CSV, SQL oder Excel weitergegeben werden.  
Die Weitergabe der Daten ist  einfach. Ein Klick auf “Excel” oder “CSV” öffnet die ermittelten Daten direkt in Excel und Sie können die Daten dann dort weiterverarbeiten. 
Die Daten können auch direkt an eine Kampagne übergeben werden. Über die Schaltfläche Kampagne kann eine Kapagne gestartet werden (siehe Kampagne).  
Über SQL Schaltfläche können Sie Insert Statement erstellen, Daten in Importdialog laden oder Aktion abbrechen. 
Mit Hilfe von Insert Statements werden neue Datensätze in eine Tabelle eingefügt. 

![](http://xpecto.github.io/docs/img/img_1419342669871.png)

Über dem Importdialog können Sie z.B. Datensätze importieren, Tabellen importieren in der Datenbank oder zwischen Datenbanken. 

![](http://xpecto.github.io/docs/img/img_1419345799957.png)

Wählen Sie das Produkt aus, zu dem die Datensätze importiert werden sollen. 

![](http://xpecto.github.io/docs/img/img_1421152862771.png)

um die zu importierende Datei auszuwählen. 
Je nach Dateiformat der zu importierenden Daten müssen die Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format.  
Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. Mit der Schaltfläche (Bild) werden die Importdaten als Tabelle angezeigt. 
Starten sie den Import durch die Schaltfläche.

![](http://xpecto.github.io/docs/img/img_1419345799957.png)

Beenden Sie den Abfrageeditor mit ![](http://xpecto.github.io/docs/img/img_1419346860827.png).

Der Abfrageeditor bietet Anwendern ohne SQL-Kenntnisse die Möglichkeit, Datenbankabfragen mittlerer Komplexität selbständig zu erstellen.  
Falls Sie Auswertungen benötigen, die mit den beschriebenen Methoden nicht abbildbar sind, wenden Sie sich an den xpecto Kundensupport.