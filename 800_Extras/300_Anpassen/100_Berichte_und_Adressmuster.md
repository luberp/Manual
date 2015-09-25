Alle Ausdrucke, die mit xpecto erstellt werden (wie z. B. Provisionsabrechnungen, Kundenanschreiben), basieren auf gespeicherten Vorlagen, die entweder über die integrierte Berichtserstellungs-Komponente ActiveReports, oder über den Word-Editor erstellt werden. Die Vorlagen für Ausdrucke und Schreiben werden deshalb im folgenden (und auch bei der Kommunikation mit dem xpecto Kundensupport) als Berichte bezeichnet. Jeder Bericht besteht aus einem Layout, einer Datenbankabfrage sowie einigen Konfigurationsparametern. 

Neben Berichte können Sie auch Adressmuster, Textbausteine und individuelle Schreiben erstellen.

Über die Symbolleiste ![](http://xpecto.github.io/docs/img/img_1442245724286.png) oder über Menü *Extras → Anpassen → Berichte und Adressmuster* starten Sie den *xpectoPro Berichte und Textbausteine* -Dialog.

Berichte werden über Namen unterschieden, und thematisch in Gruppen verwaltet. Klicken Sie auf das Symbol ![](http://xpecto.github.io/docs/img/img_1424086630188.png) um eine neue Gruppe anzulegen. 

![](http://xpecto.github.io/docs/img/img_1424086718173.png)

Geben Sie den Namen für die neue Gruppe an und bestätigen Sie mit *OK*.

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1424086982407.png) wird ein neuer Bericht angelegt. Gleichzeitig können Sie auch eine neue Gruppe anlegen, durch anklicken des Checkboxes *neue Gruppe anlegen.* 

![](http://xpecto.github.io/docs/img/img_1442415998478.png)

Ein neuer Bericht kann entweder als ein leerer Bericht, eine Kopie eines bestehenden Berichts, ein tabellarischer Bericht oder eine xpecto Vorlage angelegt werden. 
In jedem Fall muss der Name für den neuen Bericht, die Gruppe in die der Bericht eingegliedert werden soll und die Datenbasis, angegeben werden. 
Bei Auswahl einer Datenbasis wird automatisch eine entsprechende Datenbankanfrage generiert und im Bericht hinterlegt. 

| Bericht Art           |    Beschreibung     |  
| ------------- |:-------------| 
| Microsoft Word      | Word-Bericht| 
| integrierter Berichtsgenerator  |ActiveReports:  webbasierter Format| 
| Datenexport     | Excel-Bericht in Tabellenform | 
| HTML Mail    | HTML Format | 
| PDF Formular     | PDF Format | 
| Meta-Bericht     | Fasst mehrere Berichte zusammen | 
| Einfaches RTF oder Docx    | RTF oder Docx Format| 
| Festes Seiten Layout    | Seiten Layout vorgegeben| 

Die Art des Berichts kann nachträglich nicht mehr geändert werden! Durch Klick auf *OK* wird der Bericht angelegt.

![](http://xpecto.github.io/docs/img/img_1442317569556.png)

Unter dem Reiter *Allgemein* können der Name und die Gruppe des Berichts geändert werden. Außerdem besteht die Möglichkeit, eine Beschreibung einzugeben.

Unter dem Reiter *Entwurf* wird das Layout des Berichts erstellt. Je nach dem, ob es sich um einen Word-Bericht oder um einen ActiveReports-Bericht handelt, erscheint hier ein Word-Editor oder der Berichtseditor von Data Dynamics zur Bearbeitung des Layouts. Die Funktionsweise des Word-Editors ist angelehnt an die Grundfunktionen von Microsoft-Word. Der Editor sollte nur von Benutzer mit Erfahrung in Microsoft-Word verwendet werden, die Bedienung ist dann selbsterklärend.  Hilfe zur Bedienung des Layout-Editors von Data Dynamics erhalten Sie im Internet unter der Adresse http://www.componentone.com/ oder vom xpecto Kundensupport.

Unter dem Reiter *Abfrage* kann die dem Bericht zugrunde liegende Datenbankabfrage bearbeitet werden. 
Benutzer benötigen hierzu Grundkenntnisse in SQL. Das Eingabefeld *Filter Field-IDs* zeigt der zuletzt ausgewählten Wert in eine Tabelle an, und kann in der WHERE-Bedingung eingebaut werden.

Unter dem Reiter *Zusatzdaten* kann jeweils ein anderen Bericht als Kopfzeile bzw. Fußzeile, Briefpapier ausgewählt werden. So kann auf einfache Weise ein einheitlicher Briefkopf für mehrere Berichte verwendet werden. Änderungen am Briefkopf müssen dann zentral an einer Stelle durchgeführt werden, und nicht in jedem einzelnen Bericht. Als Kopf-, Fußzeile, oder Briefpapier können nur die Berichte verwendet die entsprechend kategorisiert sind. Unter dem Reiter *Kategorien*  Feldgruppe *Unterbericht* können die Einstellungen festgelegt.

Unter dem Reiter *Kategorien* kann der bearbeitete Bericht kategorisiert werden. 

![](http://xpecto.github.io/docs/img/img_1442317999574.png)

Mit den Optionen unter der Feldgruppe *Allgemeiner Bericht* kann festgelegt werden, unter welchen Umständen der Bericht in den Berichts-Favoriten auf der Symbol- und Funktionsleiste des Hauptfensters angezeigt werden soll. Dies ist sinnvoll für häufig verwendete Berichte, da diese dann direkt von der Hauptmaske aus gedruckt werden können.

 Unter der Feldgruppe *Unterbericht* kann festgelegt werden, dass es sich bei dem Bericht um eine Kopfzeile Fußzeile oder Briefpapier handelt. Der Bericht kann dann in anderen Berichten als Kopfzeile bzw. Fußzeile ausgewählt werden. 

Die Optionen unter *Beleg* geben die Möglichkeit ein Bericht als Beleg zu archivieren, dazu muss ein Belegtyp angegeben werden.

 Die Optionen unter *Spezieller Bericht* haben keine direkte Auswirkung, sie sind für weitere geplante Funktionen vorgesehen. Wenn z.B. Verteiler für Kampagnen ausgewählt ist, dann wird der Bericht in der Kampagnen unter Feldgruppe *Datenquelle wählen* zu Auswahl stehen.

Unter dem Reiter *Versandoptionen* werden die Parameter für die Online-Zustellung von Ausdrucken, Archiv-Einstellungen und Exportformat definiert. Z.B. *eBrief Sofortdruck* hat eine Schnittstelle zu Software damit wird die PDF Datei zur Versandzentrum geschickt und für Versand vorbereitet, oder *eService Upload* in VP-Portal und Kundenportal.

![](http://xpecto.github.io/docs/img/img_1442570315303.png)

In dem Dialog *xpectoPro Berichte und Textbausteine* über die Symbolleiste, kann der aktuell selektierte Bericht gelöscht, exportiert oder importiert. 

*Adressmuster* ist eine SQL-Abfrage die nur ein einziges Feld und eine einzige Zeile zurück liefern darf.

*Textbausteine* sind Textsegmente, die in einen individuellen Schreiben eingebaut werden können. 

*Individuelle Schreiben* können Dokument die aus Texbausteine und statische Elemente gebaut werden können.