<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>200_Oberflaechen_und_Nachschlagslisten.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Im folgenden Abschnitt ist die Anpassung und Erweitbarkeit von Formulare bzw. Masken der xpectoPro beschrieben.</p>

<p><strong>Oberflächen</strong></p>

<p>In xpectoPro sind alle Eingabenmasken individuell anpassbar. Dies bezieht sich nicht nur auf das Layout der Masken, sondern erstreckt sich auch auf die damit verknüpfte Funktionalitäten. Während das Layout (Anzahl, Anordnung und Beschriftung der Eingabefelder) durchaus von erfahrenen Benutzern geändert werden kann, sollten Änderungen an der Funktionalität nur vom xpecto Kundensupport durchgeführt werden. </p>

<p>Auf dem Reiter <em>Vorschau</em> wird der Name schon sagt einen Vorschau von der Oberfläche dargestellt.  <br>
Auf dem Karteireiter Vorschau kann jederzeit eine Vorschau der bearbeiteten Maske angezeigt werden, auch ohne die Änderungen vorher zu speichern. <br>
Sowie die Tabelle aus der die Daten verwerdet wurden, Sie haben hier die Möglichkeit die Felder mit verschiedene Daten zu testen, aktualisieren, vergleichen.  <br>
Unter die Schaltfläche Mustervorlage <img src="http://xpecto.github.io/docs/img/img_1424264077326.png" alt="" title=""> wird die Mustervorlage für Standard-Positionen und -Größen angezeigt.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1442575324950.png" alt="" title=""></p>

<p>Auf dem Reiter <em>Designer</em> befindet sich ein grafischer Editor zum Bearbeiten des Layouts der selektierten Oberfläche. Eingabefelder, Auswahllisten sowie Buttons etc. können mit Hilfe des Designers problemlos verschoben werden und somit das Gesamtbild nach Ihren Wünschen angepasst werden.  <br>
Um ein bereits bestehendes Label oder Eingabefeld zu verschieben, markieren Sie es durch einen Klick mit der linken Maustaste und ziehen es mit gedrückter Maustaste an die gewünschten Position.  <br>
Zum Einfügen eines neuen Eingabefeldes wählen Sie in der Liste im rechten oberen Bereich die entsprechende Datenbanktabelle und darunter die gewünschte Datenbankspalte aus, mit der das Feld verknüpft werden soll. Durch Klick auf das markierte Icon in der Werkzeugleiste wird das Eingabefeld eingefügt.  <br>
Speichern Sie die veränderte Oberfläche mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1424252432208.png" alt="" title="">. </p>

<p>Reichen in einer Tabelle die vorhandenen Felder nicht aus, so können weitere Felder angelegt werden. Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1424252468984.png" alt="" title=""> wird ein neues Datenbankfeld angelegt.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1424252729534.png" alt="" title="">.</p>

<p>Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1424252792081.png" alt="" title=""> kann eine neue Tabelle in der Datenbank angelegt werden.  <br>
Wählen Sie unter <em>1. Tabelle wählen</em> die Datenbanktabelle, dier erweitert werden soll. Geben Sie unter die Feldgruppe <em>2a. Feld anlegen</em> den gewünschten Feldname, Feldtyp. Der benötigten Feldtyp ist abhängig von der Art der Daten, die im neu erzeugten Datenbankfeld gespeichert werden sollen. Zur Auswahl stehen: Text, langer Text, Ja/Nein, Datum, Datum und Uhrzeit, Kommazahl, Ganzzahl. <br>
In dem Eingabefeld <em>Ausgabeformat</em> kann optional das Ausgabeformat des Datenfeldes angegeben werden, z.B. Wert #0.00.</p>

<p>In dem Eingabefeld <em>Parameter</em> kann man bestimmten Parameter für das Feld angegeben werden. z.B. proxy, R0801 bei Einfügen des Feldes Beschreibung wird auf das Feld R0801 verwiesen, oder eine Unterabfrage sogenannten Subquery (SELECT US_FullName FROM Config_US_Users WHERE US_Group = UG_ContainedUser)).</p>

<p>Unter <em>2b. spezielle Felder anlegen</em>, werden falls gewünscht, spezielle Felder angelegt  wie Erfasst am, Erfasst von, Geändert am, Geändert von, Schreibschutz.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1424253034215.png" alt="" title=""> </p>

<p>können neue Tabelle zu Vertriebstabellen oder für Produkt/Vertragstabellen angelegt werden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1424262589171.png" alt="" title=""></p>

<p>Unter die Schaltfläche Mustervorlage wird die Mustervorlage für Standard-Positionen und -Größen angezeigt. <br>
Vergleichen mit Standard-Form macht ein Vergleich mit dem Standardoberfläche. </p>

<p>Editor, Layout und Code beinhalten Editoren zur Bearbeitung des VB- und XML-Codes zur Erweiterung der Funktionalität der Masken.</p>

<p><strong>Nachschlagslisten</strong></p>

<p>Das Modul Nachschlagslisten dient dem Hinterlegen von Listen und Tabellen mit Werten, auf die an verschiedenen Stellen in der Software von kundenspezifischen Masken und Skripten zurückgegriffen werden kann.  <br>
Beispiel: Das Eingabefeld für die Anrede in der Kundenmaske kann alternativ als Auswahlfeld angelegt und so konfiguriert werden, dass die auswählbaren Werte aus einer Nachschlagsliste mit der Bezeichnung „Anrede” entnommen werden. Die verfügbaren Werte können somit vom Benutzer durch Bearbeiten der Nachschlagsliste  <br>
„Anrede” selbst angepasst werden, ohne in die Skripte eingreifen zu müssen, die das Verhalten der Kundenmaske definieren. <br>
Durch die Verwendung eines Auswahlfeldes anstatt eines Eingabefeldes für die Anrede vermeidet Tippfehler bei der Eingabe der Anrede. Dadurch werden Peinlichkeiten bei der Erstellung von Serienbriefen vermieden, die dieses Feld enthalten. Darüber hinaus wird die Erstellung von Datenbankabfragen für Auswertungen mit Unterscheidungen der Kunden anhand des Geschlechts wesentlich erleichtert, da Tippfehler in den erfassten Anreden nicht berücksichtigt werden müssen.</p>

<p>Nachschlagslisten sind immer mit einer Skript-Programmierung an einer anderen Stelle der Software verbunden. Eine Nachschlagsliste, auf die nicht von einem kundenspezifischen Skript aus zugegrieffen wird, hat keinen Sinn. Nachschlagslisten werden deshalb immer in Rücksprache un mit Hilfe des xpecto Kundensupports angelegt, der auch das zugehörige Skript programmiert. Änderungen und Erweiterungen der Werte in den hinterlegten Nachschlagslisten können später jederzeit ohne Zuhilfenahme des xpecto Kundensupports vom Benutzer durchgeführt werden. </p>

<p>lookup, propkunden <br>
ComboBox, SerchBox,</p></div></body>
</html>