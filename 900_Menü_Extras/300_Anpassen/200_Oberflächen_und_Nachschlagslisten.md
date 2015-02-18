
Oberflächen
Vorschau, Designer, Editor, Layout, Code
Symbolleiste: Formularaufbau neu anlegen, Nachschlagsgruppen neu anlegen, Aktuellen Datensatz löschen, Standardoberfläche laden.
Unter Formularaufbau neu anlegen kann eine neue Oberfläche erstellen hier haben sie die Möglichkeit eine neue Oberfläche anzulegen und zwar leere Oberfläche, Kopie einer bestehenden Oberfläche oder xpecto Vorlagen.
Nachschlagslisten sind Comboboxen und  Dropdown-Menüs.

Im folgenden Abschnitt ist die Anpassung und Erweitbarkeit von Formulare bzw. Masken der xpectoPro beschrieben.
**Oberflächen**
In xpectoPro sind alle Eingabenmasken individuell anpassbar. Dies bezieht sich nicht nur auf das Layout der Masken, sondern erstreckt sich auch auf die damit verknüpfte Funktionalitäten. Während das Layout (Anzahl, Anordnung und Beschriftung der Eingabefelder) durchaus von erfahrenen Benutzern geändert werden kann, sollten Änderungen an der Funktionalität nur vom xpecto Kundensupport durchgeführt werden. 

Auf dem Karteireiter Vorschau wird der Name schon sagt einen Vorschau von der Oberfläche dargestellt. 
Auf dem Karteireiter Vorschau kann jederzeit eine Vorschau der bearbeiteten Maske angezeigt werden, auch ohne die Änderungen vorher zu speichern.
Sowie die Tabelle aus der die Daten verwerdet wurden, Sie haben hier die Möglichkeit die Felder mit verschiedene Daten zu testen, aktualisieren, vergleichen. 
Unter die Schaltfläche Mustervorlage ![](http://xpecto.github.io/docs/img/img_1424264077326.png) wird die Mustervorlage für Standard-Positionen und -Größen angezeigt.

Auf dem Karteireiter Designer befindet sich ein grafischer Editor zum Bearbeiten des Layouts der selektierten Maske. Eingabefelder, Auswahllisten sowie Buttons etc. können mit Hilfe des Designers problemlos verschoben werden und somit das Gesamtbild der Maske nach Ihren Wünschen angepasst werden. 
Um ein bereits bestehendes Label oder Eingabefeld zu verschieben, markieren Sie es durch einen Klick mit der linken Maustaste und ziehen es mit gedrückter Maustaste an die gewünschten Position.
Zum Einfügen eines neuen Eingabefeldes wählen Sie in der Liste im rechten oberen Bereich die entsprechende Datenbanktabelle und darunter die gewünschte Datenbankspalte aus, mit der das Feld verknüpft werden soll. Durch Klick auf das markierte Icon in der Werkzeugleiste wird das Eingabefeld eingefügt. 
Speichern Sie die veränderte Oberfläche mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1424252432208.png). 

Reichen in einer Tabelle die vorhandenen Felder nicht aus, so können weitere Felder angelegt werden. Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1424252468984.png) wird ein neues Datenbankfeld angelegt.

![](http://xpecto.github.io/docs/img/img_1424252729534.png).

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1424252792081.png) kann eine neue Tabelle in der Datenbank angelegt werden. 
Wählen Sie unter 1. Tabelle wählen die Datenbanktabelle, dier erweitert werden soll. Geben Sie unter 2a. Feld anlegen den gewünschten Feldname, Feldtyp, der benötigten Feldtyp ist abhängig von der Art der Daten , die im neu erzeugten Datenbankfeld gespeichert werden sollen. Zur Auswahl stehen: Text, langer Text, Ja/Nein, Datum, Datum und Uhrzeit, Kommazahl, Ganzzahl.
Unter Ausgabeformat kann optional das Ausgabeformat des Datenfeldes angegeben werden. z.B. Wert #0.00.

Hier kann man bestimmten Parameter für das Feld angegeben werden. z.B. proxy, R0801 bei Einfügen des Feldes Beschreibung wird auf das Feld R0801 verwiesen, oder eine Unterabfrage sogenannten Subquery (SELECT US_FullName FROM Config_US_Users WHERE US_Group = UG_ContainedUser)).
Unter 2b. spezielle Felder anlegen werden, falls gewünscht, spezielle Felder angelegt  wie Erfasst am, Erfasst von, Geändert am, Geändert von, Schreibschutz.
![](http://xpecto.github.io/docs/img/img_1424253034215.png) 
können neue Tabelle zu Vertriebstabellen oder für Produkt/Vertragstabellen angelegt werden.

![](http://xpecto.github.io/docs/img/img_1424262589171.png)

Unter die Schaltfläche Mustervorlage wird die Mustervorlage für Standard-Positionen und -Größen angezeigt.
Vergleichen mit Standard-Form macht ein Vergleich mit dem Standardoberfläche. 

Editor, Layout und Code beinhalten Editoren zur Bearbeitung des VB- und XML-Codes zur Erweiterung der Funktionalität der Masken.

**Nachschlagslisten**
Das Modul Nachschlagslisten dient dem Hinterlegen von Listen und Tabellen mit Werten, auf die an verschiedenen Stellen in der Software von kundenspezifischen Masken und Skripten zurückgegriffen werden kann. 

