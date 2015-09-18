Alle Ausdrucke, die mit xpecto erstellt werden (wie z. B. Provisionsabrechnungen, Kundenanschreiben,c.), basieren auf gespeicherten Vorlagen, die entweder über die integrierte Berichtserstellungs-Komponente ActiveReports, oder über den Word-Editor erstellt werden. Die Vorlagen für Ausdrucke und Schreiben werden deshalb im folgenden (und auch bei der Kommunikation mit dem xpecto Kundensupport) als Berichte bezeichnet. Jeder Bericht besteht aus einem Layout, einer Datenbankabfrage sowie einigen Konfigurationsparametern. 

Neben Berichte können Sie auch Adressmuster, Textbausteine und individuelle Schreiben erstellen.

Über die Symbolleiste ![](http://xpecto.github.io/docs/img/img_1442245724286.png) oder über Menü *Extras → Anpassen → Berichte und Adressmuster* starten Sie den *xpectoPro Berichte und Textbausteine* -Dialog.

Berichte werden über Namen unterschieden, und thematisch in Gruppen verwaltet. Klicken Sie auf das Symbol ![](http://xpecto.github.io/docs/img/img_1424086630188.png) um eine neue Gruppe anzulegen. 

![](http://xpecto.github.io/docs/img/img_1424086718173.png)

Geben Sie den Namen für die neue Gruppe an und bestätigen Sie mit *OK*.

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1424086982407.png) wird ein neuer Bericht angelegt. Gleichzeitig können Sie auch eine neue Gruppe anlegen. durch Auswählen des Checkboxes *neue Gruppe anlegen.* 

![](http://xpecto.github.io/docs/img/img_1442415998478.png)

Ein neuer Bericht kann entweder ein leerer Bericht, eine Kopie eines bestehenden Berichts, ein tabellarischer Bericht oder eine xpecto Vorlage angelegt werden. 
In jedem Fall muss der Name für den neuen Bericht, die Gruppe in die der Bericht eingegliedert werden soll und die Datenbasis, angegeben werden. 
Bei Auswahl einer Datenbasis wird automatisch eine entsprechende Datenbankanfrage generiert und im Bericht hinterlegt. 

| Bericht Art           |    Beschreibung     |  
| ------------- |:-------------| 
| Microsoft Word      | Word-Bericht| 
| integrierter Berichtsgenerator  | Active Reports. ActiveReports ist sind Komponenten für Forms- und Webanwendungen um Daten in Dokumente und web basierte Formate anzuzeigen.| 
| Datenexport     | Excel-Bericht in Tabellenform | 
| HTML Mail    | HTML Format | 
| PDF Formular     | PDF Format | 
| Meta-Bericht     | Fasst mehrere Berichte zusammen | 
| Einfaches RTF oder Docx    | RTF oder Docx Format| 
| Festes Seiten Layout    | Seiten Layout vorgegeben| 

Die Art des Berichts kann nachträglich nicht mehr geändert werden! Durch Klick auf *OK* wird der Bericht angelegt.

![](http://xpecto.github.io/docs/img/img_1442317569556.png)

Unter dem Reiter *Allgemein* können der Name und die Gruppe des Berichts geändert werden. Außerdem besteht die Möglichkeit, eine Beschreibung einzugeben.

Unter dem Reiter *Entwurf* wird das Layout des Berichts erstellt. Je nach dem, ob es sich um einen Word-Bericht oder um einen ActiveReports-Bericht handelt, erscheint hier ein Word-Editor oder der Berichtseditor von Data Dynamics zur Bearbeitung des Layouts. Die Funktionsweise des Word-Editors ist angelehnt an die Grundfunktionen von Microsoft-Word. Der Editor sollte nur von Benutzer mit Erfahrung in Microsoft-Word verwendet werden, die Bedienung ist dann selbsterklärend. 
Hilfe zur Bedienung des Layout-Editors von Data Dynamics erhalten Sie im Internet unter der Adresse http://www.componentone.com/ oder vom xpecto Kundensupport.

Unter dem Reiter *Abfrage* kann die dem Bericht zugrunde liegende Datenbankabfrage bearbeitet werden. 
Benutzer benötigen hierzu Grundkenntnisse SQL. Das Eingabefeld *Filter Field-IDs* zeigt der zuletzt ausgewählten Wert in eine Tabelle an, und kann in der WHERE-Bedingung eingebaut werden.

Unter dem Reiter *Zusatzdaten* kann jeweils ein anderen Bericht als Kopfzeile bzw. Fußzeile, Briefpapier ausgewählt werden. So kann auf einfache Weise ein einheitlicher Briefkopf für mehrere Berichte verwendet werden. Änderungen am Briefkopf müssen dann zentral an einer Stelle durchgeführt werden, und nicht in jedem einzelnen Bericht. Als Kopf-, Fußzeile, oder Briefpapier können nur die Berichte verwendet die entsprechend kategorisiert sind.

![](http://xpecto.github.io/docs/img/img_1442317999574.png)
 
*Kategorien* sind die Einstellungen für das Hauptfenster. Mit den Optionen unter *Allgemeiner Bericht* kann festgelegt werden, unter welchen Umständen der Bericht in den Berichts-Favoriten auf der Werkzeugleiste der Hauptmaske angezeigt werden soll. Dies ist sinnvoll für häufig verwendete Berichte, da diese dann direkt von der Hauptmaske aus gedruckt werden können.

![](http://xpecto.github.io/docs/img/img_1442415899299.png)

Unter Unterbericht kann festgelegt werden, dass es sich bei dem Bericht um eine Kopfzeile, Fußzeile oder einen Briefpapier handelt. Der Bericht kann dann in anderen Berichten ausgewählt und verwendet werden.

Die Optionen unter Beleg geben die Möglichkeit ein Bericht als Beleg zu archivieren, dazu muss ein Belegtyp angegeben werden.

Beleg, Spezieller Bericht, Erweiterte Berechtigungen Drucksystem.
Die Optionen unter spezieller Bericht sind für weitere geplante Funktionen vorgesehen.
Erweiterte Berechtigungen Drucksystem.

*Versandoptionen* sind SMS  E-Mail eBrief.  EBrief hat eine Schnittstelle zu Software damit wird die PDF Datei zur Versandzentrum geschickt und für Versand vorbereitet. Text für Archiv Bestätigung per E-Mail dient für das E-Service Upload in VP-Portal und Kundenportal.

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1424865740751.png)  wird der aktuell selektierte Bericht gelöscht. Bestätigen Sie danach der Dialog mit *Ja* ![](http://xpecto.github.io/docs/img/img_1424865976218.png).

*Adressmuster* ist eine SQL-Abfrage die nur ein einziges Feld und eine einzige Zeile zürück liefern darf.
, Textbausteine, Individuelle Schreiben
Individuelle Schreiben können aus Textbausteine gebaut werden.

Anpasssen: Berichte und Adressmuster → Berichte, Adressmuster, Textbausteine, individuelle Schreiben
Symbolleiste: Speichern, Berichtsgruppen neu anlegen, Berichte neu anlegen, Adressmuster neu anlegen, Textbausteine neu anlegen, Individuelle Schreiben neu anlegen, Aktuellen Datensatz löschen, Bericht importieren, Bericht exportieren.
Symbol: Bericht erzeugen: generiert nur den Bericht.
Symbol: Bericht bearbeiten: generiert die Vorlage die man danach bearbeiten kann.
