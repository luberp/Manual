xpectoPro bietet einen anwenderfreundlichen Abfrage-Editor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt, eigene Datenbankabfragen bzw. Auswertungen zu erstellen.

In der klassischen Menü-Ansicht erreichen Sie den Abfrage-Editor über den Menüpunkt *Bearbeiten → Abfragen erstellen*.

In der modernen Menü-Ansicht ist die Funktion *Abfragen / Verteiler* unter der Registerkarte *Werkzeuge* Gruppe *Erstellung.*

![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Abfrage_erstellen/Abfragen_erstellen_Menue.png)

Klicken Sie auf die Funktion *Abfragen / Verteiler* um den Editor *Abfragen und Listen* zu öffnen.

Nach dem Öffnen des *Abfragen und Liste* Editors wird der Assistent mit einem Bedingungsblock angezeigt, der bereits eine Bedingung enthält. Eine Bedingung ist definiert durch einen Feldnamen (links), einen Bedingungstyp (Mitte) und einem vom Anwender einzugebenden Vergleichswert. 

![](http://xpecto.github.io/docs/img/img_1461660884744.png)

Bedingungszeilen sind in Blöcken zusammengefasst. Am oberen Rand eines Blocks wird der verwendete Gruppierungstyp angezeigt. Mögliche Typen sind:

 - jede der Bedingungen trifft zu (AND)  
 - eine oder mehrere Bedingungen treffen zu (OR)
 
![](http://xpecto.github.io/docs/img/img_1461661044973.png)

Über die Schaltfläche “*Feld hinzufügen*” wird einem Block eine Bedingung hinzugefügt. Über die Schaltfläche “*Block hinzufügen*” wird einem Block ein Unterblock hinzugefügt. Auf diese Weise kann für einen Teil der Bedingungen ein anderer Gruppierungstyp verwendet werden.

Die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1461661108624.png) löscht eine Bedingungszeile.

Durch Klick auf den Feldnamen oder den Bedingungstyp kann eine Bedingung angepasst werden. Ein Klick auf den Feldnamen öffnet ein Kontextmenü zur Auswahl des gewünschten Feldnamens. Per Klick auf den Bedingungstyp kann der Typ ausgewählt werden. Folgende Bedingungstypen stehen zur  Verfügung:

|  Bedingungstypen           | 
| ------------- |
|   entspricht einem der folgenden Werte     | 
|enthält|
|    endet mit   | 
|beginnt mit|
|ist leer|
|entspricht keinem der folgenden Werte|
|enthält nicht|
|endet nicht mit |
|beginnt nicht mit|
|ist nicht leer|
|entspricht einem der folgenden Tage|
|ist von - bis|
|ist kleiner/früher oder entspricht folgendem Wert|
|ist größer/später oder entspricht folgendem Wert|
|entspricht keinem der folgenden Tage|
|ist nicht von - bis|

Schließlich werden in den Eingabefeldern die Vergleichswerte der jeweiligen Bedingung eingetragen.

Beispiel: Sie wollen wissen, welche Kunden der Vermittler VP0001 und VP0002 im Zeitraum 01.01.2001 bis 01.04.2016 Verträge des Produkts *TRI1, Top Return Invest I* abgeschlossen haben.
 
Starten Sie den Abfrage-Editor und passen Sie die vorgegebene Bedingungszeile folgendermaßen an: klicken Sie auf den Feldnamen *Vertrags-Nr* wählen im darauffolgenden Kontextmenü das Feld *Vertriebspartner → Betreuer-Nr.* Tragen Sie in das Eingabefeld die Vermittlernummer ein. Sie haben hier die Möglichkeit nach einem Feld zu suchen. 

![](http://xpecto.github.io/docs/img/img_1461661794519.png)

Legen Sie über “*Feld hinzufügen*” zwei weitere Bedingungszeilen an, wählen Sie mit der oben beschriebenen Methode die Felder: *Produkte → Produktname* und *Vertragsdaten → Abschlussdatum* und tragen Sie die entsprechenden Werte in die zugehörigen Eingabefelder ein.

![](http://xpecto.github.io/docs/img/img_1461663211041.png)

Klicken sie nun auf *Weiter*. Auf der nächsten Seite können Datenbankfelder die zusätzlich zu den bereits gewünschten Daten ausgegeben werden sollen, durch Anhaken ausgewählt werden.

![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Abfrage_erstellen/Abfragen_erstellen_Datenbankfelder.png)

In diesem Beispiel sind *Bezeichner, Kundennummer, Abschlussdatum, Produkt, Tarif, Vertragsnummer, Betreuernummer, Produktname* ausgewählt.

Klicken sie nun erneut auf *weiter*, um zur Anzeige des Abfrageergebnisses zu gelangen. In der Ergebnisanzeige wird im oberen Bereich die, anhand der vorher definierten Parameter automatisch generierte Datenbankabfrage angezeigt. Darunter erscheint eine Liste mit dem Ergebnis der Abfrage.

Die dargestellten Datensätze können über Betätigung der entsprechenden Schaltflächen  *CSV*, *SQL* *Excel* und *Kampagne* weitergegeben werden. Ein Klick auf *Excel* oder *CSV* öffnet die ermittelten Daten direkt in Excel und Sie können die Daten dann dort weiterverarbeiten.  

![](http://xpecto.github.io/docs/img/img_1461663524234.png)

Die Daten können auch direkt an eine Kampagne übergeben werden. Über die Schaltfläche *Kampagne* kann eine Kampagne gestartet werden (siehe  Handbuch *Bearbeiten → Kampagnen*). 

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461663694281.png) können Sie *Insert Statements erstellen*, Daten in *Importdialog laden* oder die *Aktion abbrechen*.  Die Insert-Operationen werden dann im Editor angezeigt.

Um die Daten zu importieren, klicken Sie auf die Schaltfläche *Daten in Importdialog laden*.

![](http://xpecto.github.io/docs/img/img_1461663786302.png)

Im Importdialog können Sie z.B. Datensätze / Tabellen in der Datenbank importieren (siehe Handbuch *Import/Export → Allgemeiner Import*). 

![](http://xpecto.github.io/docs/img/img_1461664576287.png)

Um Datensätze zu importieren, in denen das Produkt nicht in einer Spalte vorhanden ist, muss das Produkt ausgewählt werden.

Durch Betätigung der Schaltfläche *Vorschau* werden die vorbereitete Daten angezeigt.
Wenn bereits Datensätze mit derselbe ID in der Datenbank vorhanden sind, dann werden diese nur aktualisiert, falls die Checkbox *vorhandene Daten aktualisiert* markiert ist.

Wenn Sie Tabellen aus einer Datei, in der Datenbank importieren wollen, dann klicken Sie auf die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1421152862771.png) neben das Feld Datei, um die zu importierende Datei auszuwählen.

Je nach Dateiformat der zu importierenden Daten müssen die Trennzeichen, sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. 
Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. 
Durch betätigen von *Vorschau* werden die Importdaten als Tabelle angezeigt.
 Um den Import zu starten, klicken Sie auf die Schaltfläche: ![](http://xpecto.github.io/docs/img/img_1421159892128.png).

Nachdem Sie die folgende Meldung mit *OK* bestätigt haben, werden die angezeigten Daten importiert. 

![](http://xpecto.github.io/docs/img/img_1421160002075.png)

Durch Betätigung von ![](http://xpecto.github.io/docs/img/img_1431935009760.png)  wird der Abfrage-Editor beendet. 
