

### Berichte und Adressmuster

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

### Oberflaechen und Nachschlagslisten

Im folgenden Abschnitt ist die Anpassung und Erweiterbarkeit von Formulare bzw. Masken der xpectoPro beschrieben.

In der klassischen Menü-Ansicht kann die Maske *Oberflächen und Nachschlagslisten* über Menü *Extras → Anpassen → Oberflächen und Nachschlagslisten* oder durch Drücken der F12-Taste.

In der modernen Menü-Ansicht kann die Maske über die Registerkarte *System* Gruppe Anpassungen Funktion *Oberflächen* und Funktion *Nachschlagslisten* oder durch Drücken der F12-Taste.

![](http://xpecto.github.io/docs/img/img_1462178525763.png)

**Oberflächen**

In xpectoPro sind viele Eingabenmasken individuell anpassbar. Dies bezieht sich nicht nur auf das Layout der Masken, sondern erstreckt sich auch auf die damit verknüpfte Funktionalitäten. Während das Layout (Anzahl, Anordnung und Beschriftung der Eingabefelder) durchaus von erfahrenen Benutzern geändert werden kann, sollten Änderungen an der Funktionalität nur vom xpecto Kundensupport durchgeführt werden. 

![](http://xpecto.github.io/docs/img/img_1462174447372.png)

Auf dem Reiter *Vorschau* wird eine Vorschau von der Oberfläche dargestellt, auch ohne die Änderungen vorher zu speichern. Sie haben hier die Möglichkeit die Felder mit verschiedene Daten zu testen.

Über die Schaltfläche *Mustervorlage* ![](http://xpecto.github.io/docs/img/img_1424264077326.png) wird die Mustervorlage für Standard-Positionen und -Größen angezeigt. 

![](http://xpecto.github.io/docs/img/img_1462174005141.png)


Auf dem Reiter *Designer* befindet sich ein grafischer Editor zum Bearbeiten des Layouts der selektierten Oberfläche. Eingabefelder, Auswahllisten sowie Buttons etc. können mit Hilfe des Designers problemlos verschoben werden und somit das Gesamtbild nach Ihren Wünschen angepasst werden. 

![](http://xpecto.github.io/docs/img/img_1462174170782.png)

Um ein bereits bestehendes Label oder Eingabefeld zu verschieben, markieren Sie es durch einen Klick mit der linken Maustaste und ziehen es mit gedrückter Maustaste an die gewünschten Position. 
Zum Einfügen eines neuen Eingabefeldes wählen Sie in der Liste im rechten oberen Bereich die entsprechende Datenbanktabelle und darunter die gewünschte Datenbankspalte aus, mit der das Feld verknüpft werden soll. Durch Klick auf das  Icon ![](http://xpecto.github.io/docs/img/img_1442578074569.png) in der Werkzeugleiste wird das Eingabefeld eingefügt. Speichern Sie die veränderte Oberfläche mit dem Symbol ![](http://xpecto.github.io/docs/img/img_1442578440840.png) . 

Reichen in einer Tabelle die vorhandene Felder nicht aus, so können weitere Felder angelegt werden. Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442580597049.png) wird ein neues Datenbankfeld angelegt.

![](http://xpecto.github.io/docs/img/img_1442580545253.png)

Wählen Sie unter *1. Tabelle wählen* die Datenbanktabelle, die erweitert werden soll. Geben Sie unter die Feldgruppe *2a. Feld anlegen* den gewünschten Feldname, Feldtyp und das Ausgabeformat. Der benötigten Feldtyp ist abhängig von der Art der Daten, die im neu erzeugten Datenbankfeld gespeichert werden sollen. Zur Auswahl stehen: Text, langer Text, Ja/Nein, Datum, Datum und Uhrzeit, Kommazahl, Ganzzahl.

In dem Eingabefeld *Ausgabeformat* kann optional das Ausgabeformat des Datenfeldes angegeben werden, z.B.  #.##0,00. 

In dem Eingabefeld *Parameter* kann man bestimmte Parameter oder eine SQL-Abfrage für das Feld angegeben werden. 

Durch einen Klick auf die Schaltfläche *Feld erstellen* wird das Datenbankfeld angelegt.

Unter *2b. spezielle Felder anlegen*, werden falls gewünscht, spezielle Felder angelegt wie *Erfasst am, Erfasst von, Geändert am, Geändert von, Schreibschutz*.

Auf dem Karteireiter *Vorschau* kann jederzeit eine Vorschau der bearbeiteten Oberfläche angezeigt werden, auch ohne die Änderungen vorher zu speichern.

Über das Symbol ![](http://xpecto.github.io/docs/img/img_1442580639187.png), kann eine neue Tabelle in der Datenbank angelegt werden. 

Die Reiter *Editor*, *Layout* und *Code* beinhalten Editoren zur Bearbeitung des VB- und XML-Codes zur Erweiterung der Funktionalität. 

**Nachschlagslisten**

Das Modul Nachschlagslisten dient dem Hinterlegen von Listen und Tabellen mit Werten, auf die an verschiedenen Stellen in der Software von kundenspezifischen Masken und Skripten zurückgegriffen werden kann. 
Beispiel: Das Eingabefeld für die Anrede in der Kundenmaske kann alternativ als Auswahlfeld angelegt und so konfiguriert werden, dass die auswählbaren Werte aus einer Nachschlagsliste mit der Bezeichnung *Anrede* entnommen werden. Die verfügbaren Werte können somit vom Benutzer durch Bearbeiten der Nachschlagsliste  „Anrede" selbst angepasst werden, ohne in die Skripte eingreifen zu müssen, die das Verhalten der Kundenmaske definieren.

![](http://xpecto.github.io/docs/img/img_1442581536742.png)

Durch die Verwendung eines Auswahlfeldes anstatt eines Eingabefeldes für die Anrede werden Tippfehler bie der Eingabe der Anrede vermeidet. Dadurch werden Peinlichkeiten bei der Erstellung von Serienbriefen vermieden, die dieses Feld enthalten. Darüber hinaus wird die Erstellung von Datenbankabfragen für Auswertungen mit Unterscheidungen der Kunden anhand des Geschlechts wesentlich erleichtert, da Tippfehler in den erfassten Anreden nicht berücksichtigt werden müssen.

Nachschlagslisten sind immer mit einer Skript-Programmierung an einer anderen Stelle der Software verbunden. Eine Nachschlagsliste, auf die nicht von einem kundenspezifischen Skript aus zugegriffen wird, hat keinen Sinn. Nachschlagslisten werden deshalb immer in Rücksprache und mit Hilfe des xpecto Kundensupports angelegt, der auch das zugehörige Skript programmiert. Änderungen und Erweiterungen der Werte in den hinterlegten Nachschlagslisten können später jederzeit ohne Zuhilfenahme des xpecto Kundensupports vom Benutzer durchgeführt werden. 

### Prozesse Rechte und Batchjobs

In der klassischen Menü-Ansicht ist die Maske *Prozesse und Rechte* über Menü *Extras → Anpassen → Prozesse, Rechte und Batchjobs* gestartet werden.

In der modernen Menü-Ansicht kann die Maske *Prozesse und Rechte* in der Registerkarte *System* Gruppe *Anpassungen* Funktionen: *Prozesse, Benutzer/Rechte, Hintergrunddienste*.

![](http://xpecto.github.io/docs/img/img_1462180609955.png)

Die Maske enthält ihre eigene Symbolleiste mit folgende Symbole:

| Symbol          |    Beschreibung     |  
| ------------- |:-------------| 
| ![](http://xpecto.github.io/docs/img/img_1461935229842.png)  |Speichern| 
| ![](http://xpecto.github.io/docs/img/img_1462788084971.png)  |Prozesse neu anlegen| 
| ![](http://xpecto.github.io/docs/img/img_1462788142810.png)    | Benutzer neu anlegen | 
| ![](http://xpecto.github.io/docs/img/img_1462788189080.png)   | Batch-Jobs neu anlegen | 
| ![](http://xpecto.github.io/docs/img/img_1462788233775.png)   | Aktuellen Datensatz löschen | 
| ![](http://xpecto.github.io/docs/img/img_1462788296199.png)   | Systembenutzer abfragen und speichern | 
| ![](http://xpecto.github.io/docs/img/img_1461935451257.png)   | Prozess importieren|
|![](http://xpecto.github.io/docs/img/img_1461935507991.png)| Prozess exportieren| 
|![](http://xpecto.github.io/docs/img/img_1462788381761.png)| Druckvorschau|

**Prozesse**

Unter Prozesse können Wiedervorlagen, Mahnprozesse und Zeichnungen angelegt werden.
xpectoPro ermöglicht die Integration von Ablaufprozessen in die tägliche Arbeit. Nahezu alle Elemente und Funktionen der Software können in vordefinierte Abläufe eingebunden werden. Die Abläufe sind umfangreich konfigurierbar und ermöglichen eine strukturierte Arbeitsweise. Insbesondere verteilte Teams profitieren von der Aufgabentrennung und der gemeinsamen Kommunikation über Prozesse.
Die Prozesse können über einen grafischen Designer erstellt werden. 
Die Steuerung der Prozesse erfolgt mit einer zentralen *Wiedervorlage-Steuerung* (siehe Handbuch *Bearbeiten → Wiedervorlage Steuerung*) die alle Prozesselemente einsehen darf. Leiter von Callcentern, Vertrieben oder Verwaltungen haben so stets den Überblick über alle wichtigen Abläufe.
Die Einbindung von externen Stellen zur Datenerfassung, zur Prüfung/Compliance oder zur Betreuung ist über Prozesse sehr gut möglich. 

Beispiel Mahnwesen:
- Kunde erzeugt Rücklastschrift oder zahlt nicht innerhalb eines bestimmten Zeitraums 
- Je nach Grund wird Callcenter oder Vertriebspartner aktiv 
- erneute Wartezeit 
- Kunde hat gezahlt → erledigt 
- Kunde hat nicht gezahlt → nächste Mahnstufe

Um einen Prozess neu anzulegen klicken Sie in dem Dialog xpectoPro Prozesse und Rechte auf das Symbol ![](http://xpecto.github.io/docs/img/img_1462787545827.png). Geben Sie den Name für Ihren neuen Prozess und die gewünschte Vorlage dazu. Bestätigen Sie dann Ihre Eingaben mit einen Klick auf *OK*. 

![](http://xpecto.github.io/docs/img/img_1462179894814.png)

Unter dem Reiter *Designer* haben Sie dann die Möglichkeit den Prozess zu designen. 

![](http://xpecto.github.io/docs/img/img_1462180172219.png)


**Benutzer**

In xpectoPro kann jeder Menüpunkt und jeder Karteireiter sowie das Starten der Software pro Benutzer individuell gesperrt oder erlaubt werden. Der in xpectoPro verwendete Benutzer ist der jeweils angemeldete Windows-Benutzer. In der Liste der vorhandenen Benutzer werden automatisch die in der Windows Domäne vorhandenen Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. Einen neuen Benutzer legen sie durch einen Klick auf das Symbol ![](http://xpecto.github.io/docs/img/img_1462187089244.png) an. 

Geben Sie einen Benutzernamen ein. Achten Sie darauf, dass der gewählte Benutzername bereits ein Benutzerkonto im Windows Betriebssystem besitzt. 

![](http://xpecto.github.io/docs/img/img_1424427033970.png)

Bei Windows Domänen-Benutzern setzt sich der Benutzer aus Domänenname\Benutzername zusammen. Sollten Ihre Benutzer also an einem Domänencontroller angemeldet sein, so berücksichtigen Sie dies bei der Erstellung des Benutzerkontos. Bestätigen Sie Ihre Eingaben mit *OK*. Nachdem Sie mit dem Symbol ![](http://xpecto.github.io/docs/img/img_1462187128337.png) gespeichert haben, wird der neue Benutzer in der Benutzer Liste angezeigt. 

Beim Start der Software werden zuerst die Rechte des angemeldeten Benutzers ermittelt und daraufhin nur die Menüpunkte und Karteireiter angezeigt, für die der Benutzer berechtigt ist oder gegebenfalls der Start der Software abgebrochen. Die Ermittlung der Berechtigungen eines angemeldeten Benutzers erfolgt in zwei Stufen. Zuerst werden die Rechte des Benutzer *Default* abgefragt (der Benutzer „Default" wird  bei der Installation der Software automatisch angelegt und mit dem Recht *Administrator* ausgestattet). Danach werden die Rechte des tatsächlich angemeldeten Benutzers abgefragt, diese überblenden gegebenenfalls die Rechte des Benutzers *Default*. 

Beispiel: Beim Benutzer *Default* sei das Recht zum Start von xpectoPro auf erlauben gesetzt. Bei einem bestimmten Benutzer sei jedoch zusätzlich das Recht zum Start von xpectoPro auf verbieten gesetzt. Dadurch ist allen Windows Benutzer grundsätzlich das Starten der Software möglich. Der bestimmte Benutzer kann jedoch xpectoPro nicht starten, obwohl beim Benutzer *Default* das Recht auf erlauben ist. 

Spezielle Rechte: Die Rechte *Administrator* und *Poweruser* umfassen alle möglichen Rechte, d.h. das Setzen eines der beiden Rechte bei einem Benutzer ist äquivalent zum Setzen aller anderen Rechte bei demselben Benutzer. Bei *Poweruser* können einzelne Rechte für den Benutzer durch Setzen des entsprechenden Rechts auf verbieten entzogen werden. Im Gegensatz dazu ist dies bei *Administrator* nicht möglich.

Zur Einstellung der Rechte eines Benutzers selektieren Sie den Benutzer und betätigen Sie die Schaltfläche 
 ![](http://xpecto.github.io/docs/img/img_1424439295301.png) in dem Reiter *Rechte*, um eine neue Berechtigungszeile einzufügen. In der Auswahlbox *Recht* wird das gewünschte Recht ausgewählt, und unter Wert die jeweilige Berechtigungsstufe *deny/verbieten*, *default* oder *allow/erlauben* gesetzt.

Über Gruppen-Rechte gelten die Berechtigungen die Sie dieser Gruppe geben, grundsätzlich für alle Mitglieder der Gruppe. 

Das Symbol *Systembenutzer abfragen und speichern* ![](http://xpecto.github.io/docs/img/img_1462187160501.png) holt alle Benutzer aus dem Active Directoy ab und speichert diese. In der Liste der vorhandenen Benutzer werden automatisch die in der Windows Domäne vorhandenen Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. 

**Batchjobs**

Batchjobs sind automatisierte Prozesse, das bedeutet dass eine Folge von auszuführenden Befehlen von dem Betriebsystem in einer Datei aufgeführt ist und für die Ausführung als eine einzelne Einheit vorgelegt wird. Ein Batchjob ist das Gegenteil von interaktive Verarbeitung in der ein Benutzer die einzelne Befehle sofort verarbeitet werden.
Ein neuer Batchjob kann mit einem Klick auf das Symbol ![](http://xpecto.github.io/docs/img/img_1462187304079.png) angelegt werden.

![](http://xpecto.github.io/docs/img/img_1462187275440.png)

Über die Druckvorschau ![](http://xpecto.github.io/docs/img/img_1462187329274.png) wird ein Ausdruck der aktuellen Eingabemaske gemacht, und zwar von dem Reiter der gerade aktiv ist. Die dazugehörigen Details stehen oben auf der Seite. Um die Druckvorschau-Funktion zu öffnen, klicken Sie auf das Symbol ![](http://xpecto.github.io/docs/img/img_1462187337467.png) in der Symbolleiste. In das Fenster *Print Preview* kann die Seite eingerichtet, und falls gewünscht gedruckt werden.

### Optimierung

Die Optimierungsfunktion hilft die Performance Ihrer xpectoPro Software zu verbessern. 
Die Optimierung erfolgt durch Verkleinerung und Beschleunigung der Datenbank für die Performance-Steigerung. Dafür werden die Protokolldateien verkleinern, um Speicherplatz für die Datenbank freizugeben.
Die zweite Option ist Indizes abfragen und erzeugen.
Hierbei ist zu beachten, dass die Performance der Anwendung nach Aktivierung der Funktion langsamer sein kann und sich die positiven Auswirkungen erst beim nächsten Programmstart zeigen. 



### Datenbank Backup

Das Backup kann nur von Benutzer mit dem Recht Administrator gestartet werden.

In der klassischen Menü-Ansicht ist die Funktion Datenbank Backup über Menü *Extras → Anpassen* erreichbar.

In der modernen Menü-Ansicht kann die Funktion über die Registerkarte *System* Gruppe *Datenbank* *Backup* gestartet werden.

![](http://xpecto.github.io/docs/img/img_1462791269064.png)

Es bietet hier die Möglichkeit Backup von einzelnen Tabellen zu erstellen oder von der ganzen Datenbank.
Als Format für Backup können Sie auswählen zwischen Binärformat, XML-Format oder Sync XML-Format.

![](http://xpecto.github.io/docs/img/img_1442927979481.png)

Es werden alle Tabellen ermittelt die zum Sichern sind. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442928143560.png), erstellen Sie eine Backup-Datei im markierten Format. Sie werden hier aufgefordert einen Speicherplatz für die Backup-Datei zu wählen. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442928753163.png) kann eine Backup-Datei wieder rückgesichert werden. Damit werden die vorhandenen Datenbank-Tabellen durch die der Backup-Datei überschrieben.