eAgentur bietet einen anwenderfreundlichen Abfrageeditor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt,
eigene Datenbankabfragen bzw. Auswertungen zu erstellen.

Sie erreichen den Abfrageeditor über den Menüpunkt _Bearbeiten-&gt;"Abfrage erstellen"_.

Nach dem öffnen des Abfrageeditors wird der Bedingungs-Assistent mit einem Bedingungsblock angezeigt, der bereits eine Bedingung enthält. Bewegen
Sie die Maus über Teile des Bedingungsblocks, um Tipps zu erhalten. Eine Bedingungszeile ist definiert durch einen Feldnamen (links), einen
Bedingungstyp (mitte) und einem vom Anwender einzugebende Vergleichswert.

![](http://xpecto.github.io/docs/img/img051.png)

Bedingungszeilen sind in Blöcken zusammengefasst. Am oberen Rand eines Blocks wird der verwendete Gruppierungstyp angezeigt. Mögliche Typen sind:

*   Jede der Bedingungen trifft zu (AND)
*   Eine oder mehrere Bedingungen treffen zu (OR)
*   Keine der Bedingungen trifft zu (NOT OR)

Über die Schaltfläche "Feld hinzufügen" wird einem Block eine Bedingung hinzugefügt. Über die Schaltfläche "Block
hinzufügen" wird einem Block ein Unterblock hinzugefügt. Auf diese Weise kann für einen Teil der Bedingungen ein anderer Gruppierungstyp
verwendet werden.

Die Schaltfläche
![](http://xpecto.github.io/docs/img/img052.png)
löschet eine Bedingungszeile.

Durch Klick auf den Feldnamen oder den Bedingungstyp kann eine Bedingung angepasst werden. Ein Klick auf den Feldnamen öffnet ein Kontextmenü zur
Auswahl des gewünschten Feldnamens. Per Klick auf den Bedingungstyp kann der Typ ausgewählt werden. Folgende Bedingungstypen stehen zur
Verfügung:

*   Ist kleiner/früher oder entspricht folgendem Wert
*   Ist größer/später oder entspricht folgendem Wert
*   Ist leer
*   Entspricht einem der folgenden Werte
*   Liegt zwischen den folgenden Werten
*   Beginnt mit folgendem Text
*   Enthält folgenden Text

Schließlich werden in den Eingabefeldern die Vergleichswerte der jeweiligen Bedingung eingetragen.

Betrachten wir folgendes <u>Beispiel</u>:

Sie wollen wissen, welche Kunden des Vermittlers B00004 im Zeitraum 05.06.2007 bis 12.05.2008 Verträge des Produkts "Solar Power I" gezeichnet
haben.

Starten Sie den Abfrageeditor und passen Sie die vorgegebene Bedingungszeile folgendermaßen an: Klicken Sie auf den Feldnamen Vertrags-Nr und
wählen im darauf folgenden Kontextmenü das Feld Vermittler-Nr. Tragen Sie in das Eingabefeld die Vermittlernummer ein.

![](http://xpecto.github.io/docs/img/img053.png)
![](http://xpecto.github.io/docs/img/img055.png)

Legen Sie über "Feld hinzufügen" zwei weitere Bedingungszeilen an, wählen Sie mit der oben beschriebenen Methode die Felder
Produktname und Abschlussdatum und tragen Sie die entsprechenden Werte in die zugehörigen Eingabefelder ein.

![](http://xpecto.github.io/docs/img/img056.png)
![](http://xpecto.github.io/docs/img/img058.png)

Klicken sie nun auf
![](http://xpecto.github.io/docs/img/img060.png)
. Auf der nächsten Seite können die Datenbankfelder, die in der Anzeige des Abfrageergebnisses ausgegeben werden sollen, durch anhaken
ausgewählt werden.

![](http://xpecto.github.io/docs/img/img062.png)

In diesem Beispiel sind Kundennummer, Name, Vorname und Wohnort des Kunden ausgewählt.

Klicken sie nun erneut auf
![](http://xpecto.github.io/docs/img/img060.png)
, um zur Anzeige des Abfrageergebnisses zu gelangen. In der Ergebnisanzeige wird im oberen Bereich die anhand der vorher definierten Parameter automatisch
generierte Datenbankabfrage angezeigt. Darunter erscheint eine Liste mit dem Ergebnis der Abfrage.

![](http://xpecto.github.io/docs/img/img064.png)

Die dargestellten Datensätze können über Betätigung der entsprechenden Schaltflächen _PDF_, _SQL _oder _CSV_
als PDF-, SQL-Insert- oder CSV-Datei exportiert werden.

Beenden Sie den Abfrageeditor mit
![](http://xpecto.github.io/docs/img/img066.png)
.

Der Abfrageeditor bietet Anwendern ohne SQL-Kenntnisse die Möglichkeit, Datenbankabfragen mittlerer Komplexität selbständig zu erstellen.
Falls Sie Auswertungen benötigen, die mit den beschriebenen Methoden nicht abbildbar sind, wenden Sie sich an den xpecto Kundensupport.
