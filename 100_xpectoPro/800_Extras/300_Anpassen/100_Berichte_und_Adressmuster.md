Alle Ausdrucke, die mit xpectoPro erstellt werden (wie z. B. Provisionsabrechnungen, Kundenanschreiben) basieren auf gespeicherten Vorlagen. 
Diese können über die verschiedenen Berichtsgeneratoren erstellt und mit Daten befüllt werden. Die Vorlagen für Ausdrucke und Schreiben werden deshalb im folgenden (und auch bei der Kommunikation mit dem xpecto Kundensupport) als Berichte bezeichnet. Jeder Bericht besteht aus einem Layout, einer Datenbankabfrage sowie einigen Konfigurationsparametern. 

Neben Berichten können Sie auch Adressmuster, Textbausteine und individuelle Schreiben erstellen.

In der klassischen Menü-Ansicht kann die Maske *Berichte und Textbausteine*  über die Symbolleiste ![](http://xpecto.github.io/docs/img/img_1442245724286.png) oder über Menü *Extras → Anpassen → Berichte und Adressmuster* gestartet werden.

In der modernen Menü-Ansicht kann die Maske über Registerkarte *System* Gruppe *Anpassungen* Funktion *Berichte* gestartet werden.

![](http://xpecto.github.io/docs/img/img_1461933940294.png)


![](http://xpecto.github.io/docs/img/img_1461934806060.png)

Die Maske enthält ihre eigene Symbolleiste mit folgende Symbole:

| Symbol          |    Beschreibung     |  
| ------------- |:-------------| 
| ![](http://xpecto.github.io/docs/img/img_1461935229842.png)  | Speichern| 
| ![](http://xpecto.github.io/docs/img/img_1461935188197.png)  |Berichtsgruppen neu anlegen| 
| ![](http://xpecto.github.io/docs/img/img_1461935251084.png)    | Berichte neu anlegen | 
| ![](http://xpecto.github.io/docs/img/img_1461935295787.png)   | Adressmuster neu anlegen | 
| ![](http://xpecto.github.io/docs/img/img_1461935335008.png)    | Textbausteine neu anlegen | 
| ![](http://xpecto.github.io/docs/img/img_1461935370018.png)   | Individuelle Schreiben neu anlegen | 
| ![](http://xpecto.github.io/docs/img/img_1461935407107.png)   | Aktuellen Datensatz löschen| 
| ![](http://xpecto.github.io/docs/img/img_1461935451257.png)   | Bericht importieren|
|![](http://xpecto.github.io/docs/img/img_1461935507991.png)| Bericht exportieren| 

Berichte werden über Namen unterschieden und thematisch in Gruppen verwaltet. Klicken Sie auf das Symbol ![](http://xpecto.github.io/docs/img/img_1461935188197.png) um eine neue Berichtsgruppe anzulegen. 

Geben Sie den Namen für die neue Gruppe an und bestätigen Sie mit *OK*. Die neue Gruppe wird dann in der Maske unter der Berichte-Ansicht angezeigt.

Um einen neuen Bericht anzulegen klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461935251084.png)
 Gleichzeitig können Sie durch anklicken des Checkboxes *neue Gruppe anlegen* auch eine neue Gruppe anlegen.

![](http://xpecto.github.io/docs/img/img_1461936920549.png)

Ein neuer Bericht kann entweder als ein *leerer Bericht*, *Kopie eines bestehenden Berichts*, *ein tabellarischer Bericht* oder aus einer *xpecto Vorlage* erstellt werden. 
In jedem Fall muss der Name für den neuen Bericht, die Gruppe in die der Bericht eingegliedert werden soll und die Datenbasis, angegeben werden. Bei Auswahl einer Datenbasis wird automatisch eine entsprechende Datenbankabfrage generiert und im Bericht hinterlegt. 

Die Art des Berichts kann nachträglich nicht mehr geändert werden! Durch Klick auf *OK* wird der Bericht angelegt.

![](http://xpecto.github.io/docs/img/img_1462783085803.png)

Unter dem Reiter *Allgemein* können der Name, die Gruppe und Adressverwendung *Melde* oder *Post* des Berichts geändert werden. Wenn z.B für ein Bericht die Adressverwendung *Post* gewählt würde dann werden aus dem Bericht erzeugte Ausdrucke an die Post-Adresse geschickt. Die Post-Adresse kann unter dem Reiter *Allgemein* gesetzt werden (siehe Handbuch *Kunde → Adresse→  Allgemein*).
Außerdem besteht die Möglichkeit, eine Beschreibung einzugeben. 

Unter dem Reiter *Entwurf* wird das Layout des Berichts erstellt. Sie können hier z.B. aus dem vorher ausgewählten Datenbasis Felder einfügen.
Dieser Entwurf kann dann als Bericht erzeugt und für mehrere Datensätze als Vorlage dienen (siehe Handbuch *Bearbeiten → Berichte erzeugen*). Die Funktionsweise des Word-Editors ist angelehnt an die Grundfunktionen von Microsoft-Word.

![](http://xpecto.github.io/docs/img/img_1461937239234.png)

ActiveReports sind Komponenten für Forms- und Webanwendungen um Daten in Dokumente und in web basierte Formate anzuzeigen. Hilfe zur Bedienung des Layout-Editors, um ein ActiveReports-Bericht zu erstellen, erhalten Sie im Internet unter der Adresse http://activereports.grapecity.com, oder vom xpecto Kundensupport.

Unter dem Reiter *Abfrage* kann die, dem Bericht zugrunde liegende Datenbankabfrage bearbeitet werden. 
Benutzer benötigen hierzu Grundkenntnisse in SQL. 

Das Eingabefeld *Filter Field-IDs* schränkt die abzufragenden Daten der SQL-Abfrage über den in der Software aktuell selektierten Datensatz automatisch ein. Die Eintragung in diesem Feld beeinflusst auch die Archivierung des Berichts. Die möglichen Angaben in diesem Feld können von xpecto Kundensupport erfragen, da diese eine Eigenentwicklung seitens xpecto sind.

Im oberen Bereich des Reiters *Abfrage* gibt es einen Button *Testen* um die oben eingetragene Abfrage inklusive der im Feld *Filter Field-IDs* eingetragenen Einschränkungen für den aktuell im Hauptfenster selektierten Datensatz zu testen. Im Fenster darunter wird Ihnen dann die ausgeführte SQL-Abfrage samt Ergebnis angezeigt.

Unter dem Reiter *Zusatzdaten* kann jeweils ein anderen Bericht als Kopfzeile bzw. Fußzeile, Briefpapier ausgewählt werden. So kann auf einfache Weise ein einheitlicher Briefkopf für mehrere Berichte verwendet werden. Änderungen am Briefkopf müssen dann zentral an einer Stelle durchgeführt werden, und nicht in jedem einzelnen Bericht. Als Kopf-, Fußzeile oder Briefpapier können nur die Berichte verwendet die entsprechend kategorisiert sind. Unter dem Reiter *Kategorien* Feldgruppe *Unterbericht* kann diese Kategorisierung/Festlegung durchgeführt werden.

Unter dem Reiter *Kategorien* kann der bearbeitete Bericht kategorisiert werden. 

![](http://xpecto.github.io/docs/img/img_1461939783950.png)

Mit den Optionen unter der Feldgruppe *Allgemeiner Bericht* kann festgelegt werden, unter welchen Umständen der Bericht in den Berichts-Favoriten auf der Symbolleiste des Hauptfensters angezeigt werden soll siehe Handbuch *Bearbeiten → Berichte erzeugen*). Dies ist sinnvoll für häufig verwendete Berichte, da diese dann direkt von der Hauptmaske aus gedruckt werden können.

 Unter der Feldgruppe *Unterbericht* kann festgelegt werden, dass es sich bei dem Bericht um eine Kopfzeile Fußzeile oder Briefpapier handelt. Der Bericht kann dann in anderen Berichten als Kopfzeile bzw. Fußzeile ausgewählt werden. 

Die Optionen unter der Feldgruppe *Beleg* geben die Möglichkeit ein Bericht als Beleg zu archivieren, dazu muss ein Belegtyp angegeben werden.

 Die Optionen unter *Spezieller Bericht* sind für Berechnungen vorgesehen (siehe *Berechnungen → Berechnungen und Transaktionen Bereich Druck und Ausgabe*). 

In der Feldgruppe *Erweiterte Berechtigung Drucksystem* können die Optionen gewählt 
 wie z.B. *Verwendung für Massendruck*. Dann wird der Bericht in der Kampagnen unter Feldgruppe *Aktion wählen* zu Auswahl stehen siehe Handbuch *Bearbeiten → Kampagnen*).

Unter dem Reiter *Versandoptionen* werden die Parameter für die Online-Zustellung von Ausdrucken, Archiv-Einstellungen und Exportformat definiert. Z.B. *eBrief Sofortdruck* hat eine Schnittstelle zu Software damit wird die PDF Datei zur Versandzentrum geschickt und für Versand vorbereitet.
![](http://xpecto.github.io/docs/img/img_1461942065798.png)

In der *Berichte und Texbausteine* Maske gibt neben der Berichte drei andere Ansichten für  Adressmuster, Textbausteine und individuelle Schreiben.

Die *Adressmuster* Funktion kann auch über die Registerkarte *System* Gruppe *Anpassungen* erreicht werden.
Ein Adressmuster ist ein Feld der im Hintergrund eine Datenbankabfrage hat und wird in  Berichte verwendet.
Ein*Adressmuster* ist eine SQL-Abfrage die nur ein einziges Feld und eine einzige Zeile zurück liefern darf.

![](http://xpecto.github.io/docs/img/img_1461942683009.png)

*Textbausteine* sind Textsegmente, die in ein individuelles Schreiben eingebaut werden können. 

*Individuelle Schreiben* sind Dokumente die aus Textbausteine und statische Elemente gebaut werden können.