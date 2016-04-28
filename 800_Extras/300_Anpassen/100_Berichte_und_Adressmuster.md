Alle Ausdrucke, die mit xpectoPro erstellt werden (wie z. B. Provisionsabrechnungen, Kundenanschreiben) basieren auf gespeicherten Vorlagen. Diese können über die verschiedenen Berichtsgeneratoren erstellt und mit Daten befüllt werden. Die Vorlagen für Ausdrucke und Schreiben werden deshalb im folgenden (und auch bei der Kommunikation mit dem xpecto Kundensupport) als Berichte bezeichnet. Jeder Bericht besteht aus einem Layout, einer Datenbankabfrage sowie einigen Konfigurationsparametern. 

Neben Berichten können Sie auch Adressmuster, Textbausteine und individuelle Schreiben erstellen.

Über die Symbolleiste ![](http://xpecto.github.io/docs/img/img_1442245724286.png) oder über Menü *Extras → Anpassen → Berichte und Adressmuster* starten Sie den *xpectoPro Berichte und Textbausteine* -Dialog.

Berichte werden über Namen unterschieden und thematisch in Gruppen verwaltet. Klicken Sie auf das Symbol ![](http://xpecto.github.io/docs/img/img_1424086630188.png) um eine neue Berichtsgruppe anzulegen. 

![](http://xpecto.github.io/docs/img/img_1424086718173.png)

Geben Sie den Namen für die neue Gruppe an und bestätigen Sie mit *OK*.

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1424086982407.png) wird ein neuer Bericht angelegt. Gleichzeitig können Sie durch anklicken des Checkboxes *neue Gruppe anlegen* auch eine neue Gruppe anlegen.

![](http://xpecto.github.io/docs/img/img_1442415998478.png)

Ein neuer Bericht kann entweder als ein *leerer Bericht*, *Kopie eines bestehenden Berichts*, *ein tabellarischer Bericht* oder aus einer *xpecto Vorlage* angelegt werden. 
In jedem Fall muss der Name für den neuen Bericht, die Gruppe in die der Bericht eingegliedert werden soll und die Datenbasis, angegeben werden. 
Bei Auswahl einer Datenbasis wird automatisch eine entsprechende Datenbankabfrage generiert und im Bericht hinterlegt. 

| Bericht Art           |    Beschreibung     |  
| ------------- |:-------------| 
| Microsoft Word      | Word-Bericht| 
| integrierter Berichtsgenerator  |ActiveReports:  webbasiertes Format| 
| Datenexport     | Excel-Bericht in Tabellenform | 
| HTML Mail    | HTML Format | 
| PDF Formular     | PDF Format | 
| Meta-Bericht     | Fasst mehrere Berichte zu einem Bericht zusammen | 
| Einfaches RTF oder Docx    | RTF oder Docx Format| 
| Festes Seiten Layout    | Seiten Layout vorgegeben| 

Die Art des Berichts kann nachträglich nicht mehr geändert werden! Durch Klick auf *OK* wird der Bericht angelegt.

![](http://xpecto.github.io/docs/img/img_1442317569556.png)

Unter dem Reiter *Allgemein* können der Name und die Gruppe des Berichts geändert werden. Außerdem besteht die Möglichkeit, eine Beschreibung einzugeben.

Unter dem Reiter *Entwurf* wird das Layout des Berichts erstellt. Je nach dem, ob es sich um einen Word-Bericht oder um einen ActiveReports-Bericht handelt, erscheint hier ein Word-Editor oder der Berichtseditor zur Bearbeitung des Layouts. Die Funktionsweise des Word-Editors ist angelehnt an die Grundfunktionen von Microsoft-Word.
ActiveReports sind Komponenten für Forms- und Webanwendungen um Daten in Dokumente und in web basierte Formate anzuzeigen. Hilfe zur Bedienung des Layout-Editors, um ein ActiveReports-Bericht zu erstellen, erhalten Sie im Internet unter der Adresse http://activereports.grapecity.com, oder vom xpecto Kundensupport.

Unter dem Reiter *Abfrage* kann die, dem Bericht zugrunde liegende Datenbankabfrage bearbeitet werden. 
Benutzer benötigen hierzu Grundkenntnisse in SQL. 
Das Eingabefeld *Filter Field-IDs* schränkt die abzufragenden Daten der SQL-Abfrage über den in der Software aktuell selektierten Datensatz automatisch ein. Die Eintragung in diesem Feld beeinflusst auch die Archivierung des Berichts. Die möglichen Angaben in diesem Feld können von xpecto Kundensupport erfragen, da diese eine Eigenentwicklung seitens xpecto sind.

Im unteren Bereich des Reiters *Abfrage* gibt es einen Button um die oben eingetragene Abfrage inklusive der im Feld *Filter Field-IDs* eingetragenen Einschränkungen für den aktuell im Hauptfenster selektierten Datensatz zu testen. Im Fenster darunter wird Ihnen dann die ausgeführte SQL-Abfrage samt Ergebnis angezeigt.

Unter dem Reiter *Zusatzdaten* kann jeweils ein anderen Bericht als Kopfzeile bzw. Fußzeile, Briefpapier ausgewählt werden. So kann auf einfache Weise ein einheitlicher Briefkopf für mehrere Berichte verwendet werden. Änderungen am Briefkopf müssen dann zentral an einer Stelle durchgeführt werden, und nicht in jedem einzelnen Bericht. Als Kopf-, Fußzeile oder Briefpapier können nur die Berichte verwendet die entsprechend kategorisiert sind. Unter dem Reiter *Kategorien* Feldgruppe *Unterbericht* kann diese Kategorisierung/Festlegung durchgeführt werden.

Unter dem Reiter *Kategorien* kann der bearbeitete Bericht kategorisiert werden. 

![](http://xpecto.github.io/docs/img/img_1442317999574.png)

Mit den Optionen unter der Feldgruppe *Allgemeiner Bericht* kann festgelegt werden, unter welchen Umständen der Bericht in den Berichts-Favoriten auf der Symbol- und Funktionsleiste des Hauptfensters angezeigt werden soll. Dies ist sinnvoll für häufig verwendete Berichte, da diese dann direkt von der Hauptmaske aus gedruckt werden können.

 Unter der Feldgruppe *Unterbericht* kann festgelegt werden, dass es sich bei dem Bericht um eine Kopfzeile Fußzeile oder Briefpapier handelt. Der Bericht kann dann in anderen Berichten als Kopfzeile bzw. Fußzeile ausgewählt werden. 

Die Optionen unter der Feldgruppe *Beleg* geben die Möglichkeit ein Bericht als Beleg zu archivieren, dazu muss ein Belegtyp angegeben werden.

 Die Optionen unter *Spezieller Bericht* haben keine direkte Auswirkung, sie sind für weitere geplante Funktionen vorgesehen. Wenn z.B. Verteiler für Kampagnen ausgewählt ist, dann wird der Bericht in der Kampagnen unter Feldgruppe *Datenquelle wählen* zu Auswahl stehen.

Unter dem Reiter *Versandoptionen* werden die Parameter für die Online-Zustellung von Ausdrucken, Archiv-Einstellungen und Exportformat definiert. Z.B. *eBrief Sofortdruck* hat eine Schnittstelle zu Software damit wird die PDF Datei zur Versandzentrum geschickt und für Versand vorbereitet, oder *eService Upload* in VP-Portal und Kundenportal.

![](http://xpecto.github.io/docs/img/img_1442570315303.png)

In dem Dialog *xpectoPro Berichte und Textbausteine* über die Symbolleiste, kann der aktuell selektierte Bericht gelöscht, exportiert oder importiert werden. 

Ein*Adressmuster* ist eine SQL-Abfrage die nur ein einziges Feld und eine einzige Zeile zurück liefern darf.

*Textbausteine* sind Textsegmente, die in ein individuelles Schreiben eingebaut werden können. 

*Individuelle Schreiben* sind Dokumente die aus Textbausteine und statische Elemente gebaut werden können.