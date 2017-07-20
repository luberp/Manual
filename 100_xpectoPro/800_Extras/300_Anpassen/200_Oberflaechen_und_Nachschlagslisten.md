Im folgenden Abschnitt ist die Anpassung und Erweiterbarkeit von Formulare bzw. Masken der xpectoPro beschrieben.

In der klassischen Menü-Ansicht kann die Maske *Oberflächen und Nachschlagslisten* über Menü *Extras → Anpassen → Oberflächen und Nachschlagslisten* oder durch Drücken der F12-Taste.

In der modernen Menü-Ansicht kann die Maske über die Registerkarte *System* Gruppe Anpassungen Funktion *Oberflächen* und Funktion *Nachschlagslisten* oder durch Drücken der F12-Taste.

![](http://xpecto.github.io/docs/img/img_1462178525763.png)

Oberflächen

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