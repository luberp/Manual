Alle Ausdrucke, die mit xpectoPro erstellt werden (wie z. B. Provisionsabrechnungen, Kundenanschreiben usw.) basieren auf gespeicherten Vorlagen. 
Diese können über verschiedene Berichtsgeneratoren erstellt und mit Daten befüllt werden. Die Vorlagen für Ausdrucke und Schreiben werden deshalb im folgenden (und auch in Kommunikation mit dem xpecto Kundensupport) als Berichte bezeichnet. Jeder Bericht besteht aus einem Layout, einer Datenbankabfrage sowie einigen Konfigurationsparametern. 

Neben Berichten können Sie auch Adressmuster, Textbausteine und individuelle Schreiben erstellen.

In der klassischen Menü-Ansicht kann die Maske *Berichte und Textbausteine* über Menü *Extras → Anpassen → Berichte und Adressmuster* gestartet werden.

In der modernen Menü-Ansicht kann die Maske über Registerkarte *Aktionen* Gruppe *Berichte* gestartet werden.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Berichte_Menue.png)

Hauptmaske Berichte und Textbausteine.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Berichte_Main.png)

Die Hauptmaske *Berichte und Textbausteine* enthält ihre eigene Symbolleiste mit folgende Symbolen und Funktionen:

| Symbol          |    Beschreibung     |  
| ------------- |:-------------| 
| ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Speichern.png)  | Speichern| 
| ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Berichtsgruppe_anlegen.png)  |Berichtsgruppen neu anlegen| 
| ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Bericht_anlegen.png)  | Berichte neu anlegen | 
| ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Adressmuster_anlegen.png)  | Adressmuster neu anlegen | 
| ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Textbaustein_anlegen.png)  | Textbausteine neu anlegen | 
| ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Individuelles_Schreiben_anlegen.png)  | Individuelle Schreiben neu anlegen | 
| ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Datensatz_loeschen.png)  | Datensatz löschen| 
| ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Bericht_importieren.png)  | Bericht importieren|
|![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Bericht_exportieren.png)   | Bericht exportieren| 

Berichte werden über Namen unterschieden und thematisch in Gruppen verwaltet. Klicken Sie auf das Symbol ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Berichtsgruppe_anlegen.png) um eine neue Berichtsgruppe anzulegen. 

Geben Sie den Namen für die neue Gruppe an und bestätigen Sie mit *OK*. Die neue Gruppe wird dann in der Maske unter der Berichte-Ansicht angezeigt.

 ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Berichtsgruppe.png)

Um einen neuen Bericht anzulegen klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Bericht_anlegen.png)
 Gleichzeitig können Sie durch anklicken der Checkbox *neue Gruppe anlegen* auch eine neue Gruppe erzeugen.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Bericht_Gruppe.png)

Ein neuer Bericht kann entweder als ein *leerer Bericht*, *Kopie eines bestehenden Berichts*, *tabellarischer Bericht* oder aus einer *xpecto Vorlage* erstellt werden. 
In jedem Fall muss der Name für den neuen Bericht, die Gruppe in die der Bericht eingegliedert werden soll und die Datenbasis angegeben werden. Bei Auswahl einer Datenbasis wird automatisch eine entsprechende Datenbankabfrage generiert und im Bericht hinterlegt. 

Die Art des Berichts kann nachträglich nicht mehr geändert werden! Durch Klick auf *OK* wird der Bericht angelegt.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Bericht_neu.png)

Unter dem Reiter *Allgemein* können der Name, die Gruppe und Adressverwendung *Melde* oder *Post* des Berichts geändert werden. Wenn z.B für ein Bericht die Adressverwendung *Post* gewählt wird werden aus dem Bericht erzeugte Ausdrucke an die Post-Adresse des Kunden versandt. 

Unter dem Reiter *Entwurf* wird das Layout des Berichts erstellt. Sie können hier z.B. aus der vorher gewählten Datenbasis Felder einfügen.
Dieser Entwurf kann als Bericht erzeugt und für mehrere Datensätze als Vorlage dienen (siehe Handbuch *Bearbeiten → Berichte erzeugen*). Die Funktionsweise des Word-Editors ist angelehnt an die Grundfunktionen von Microsoft-Word.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Bericht_Entwurf.png)

ActiveReports sind Komponenten für Forms- und Webanwendungen um Daten in Dokumente und in web basierte Formate anzuzeigen. Hilfe zur Bedienung des Layout-Editors, um ein ActiveReports-Bericht zu erstellen, erhalten Sie im Internet unter der Adresse http://activereports.grapecity.com, oder über den xpecto Kundensupport.

Unter dem Reiter *Abfrage* kann die, dem Bericht zugrunde liegende Datenbankabfrage bearbeitet werden. 
Benutzer benötigen hierzu Kenntnisse der SQL Programmierung. 

Das Eingabefeld *Filter Field-IDs* schränkt die abzufragenden Daten der SQL-Abfrage über den in der Software aktuell selektierten Datensatz automatisch ein. Die Eintragung in diesem Feld beeinflusst auch die Archivierung des Berichts. Die möglichen Angaben in diesem Feld können von xpecto Kundensupport erfragen, da diese eine Eigenentwicklung seitens xpecto sind.

Im oberen Bereich des Reiters *Abfrage* gibt es einen Button *Testen* um die oben eingetragene Abfrage inklusive der im Feld *Filter Field-IDs* eingetragenen Einschränkungen für den aktuell im Hauptfenster selektierten Datensatz zu testen. Im Fenster darunter wird Ihnen dann die ausgeführte SQL-Abfrage samt Ergebnis angezeigt.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Filter_Field_ID.png)

Unter dem Reiter *Zusatzdaten* kann jeweils ein anderen Bericht als Kopfzeile bzw. Fußzeile, Briefpapier ausgewählt werden. So kann auf einfache Weise ein einheitlicher Briefkopf für mehrere Berichte verwendet werden. Änderungen am Briefkopf müssen dann zentral an einer Stelle durchgeführt werden, und nicht in jedem einzelnen Bericht. Als Kopf- / Fußzeile oder Briefpapier können nur Berichte verwendet werden die bereits kategorisiert sind, im Reiter *Kategorien* Feldgruppe *Unterbericht* kann diese Kategorisierung/Festlegung durchgeführt werden.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Zusatzdaten.png)

Mit den Optionen unter *Allgemeiner Bericht* kann festgelegt werden, unter welchen Voraussetzungen der Bericht unter *Favoriten* im der Hauptmaske der Applikation gelistet werden soll. Siehe Handbuch *Bearbeiten → Berichte erzeugen*). Dies ist sinnvoll für häufig verwendete Berichte, da diese dann direkt von der Hauptmaske aus gedruckt werden können.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Bericht_Kategorien.png)

Unter der Feldgruppe *Unterbericht* kann festgelegt werden, dass es sich bei dem Bericht um eine Kopfzeile Fußzeile oder Briefpapier handelt. Der Bericht kann dann in anderen Berichten als Kopfzeile bzw. Fußzeile ausgewählt werden. 

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Unterbericht.png)

Die Optionen unter der Feldgruppe *Beleg* geben die Möglichkeit ein Bericht als Beleg zu archivieren, dazu muss ein Belegtyp angegeben werden.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Beleg.png)

 Die Optionen unter *Spezieller Bericht* sind für Berechnungen vorgesehen (siehe *Berechnungen → Berechnungen und Transaktionen Bereich Druck und Ausgabe*). 
 
![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Spezieller_Bericht.png)

In der Feldgruppe *Erweiterte Berechtigung Drucksystem* können die Optionen gewählt 
 wie z.B. *Verwendung für Massendruck*. Dann wird der Bericht in der Kampagnen unter Feldgruppe *Aktion wählen* zu Auswahl stehen siehe Handbuch *Bearbeiten → Kampagnen*).

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Erweiterte_Berechtigungen.png)

Unter dem Reiter *Versandoptionen* werden die Parameter für die Online-Zustellung von Ausdrucken, Archiv-Einstellungen und Exportformat definiert. z.B. *eBrief Sofortdruck* , damit wird die Ausgabedatei zum Versandzentrum geschickt und für den Versand vorbereitet.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Berichte_Versandoptionen.png)

In der *Berichte und Texbausteine* Maske gibt neben dem Reiter *Berichte* drei weitere Kategorien:  Adressmuster, Textbausteine und individuelle Schreiben.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Berichte_Reiter.png)


Die *Adressmuster* Funktion kann auch über die Registerkarte *System* Gruppe *Anpassungen* erreicht werden.
Ein Adressmuster ist ein Feld das im Hintergrund eine Datenbankabfrage erzeugt und wird in Berichten verwendet.
Ein *Adressmuster* ist eine SQL-Abfrage die nur ein einziges Feld und eine einzige Zeile zurück liefern darf.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Berichte_Adressmuster.png)

*Textbausteine* sind Textblöcke die zentral unter Textbausteine gepflegt und in allen Berichten verwendet werden können. 

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Berichte_Textbausteine.png)

*Individuelle Schreiben* sind Dokumente die aus Textbausteine und statische Elemente gebaut werden können.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Berichte_und_Adressmuster/Individuelles_Schreiben.png)