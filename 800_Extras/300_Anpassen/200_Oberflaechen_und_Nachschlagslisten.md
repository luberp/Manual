<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>200_Oberflaechen_und_Nachschlagslisten.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Im folgenden Abschnitt ist die Anpassung und Erweiterbarkeit von Formulare bzw. Masken der xpectoPro beschrieben.</p>

<p>In der klassischen Menü-Ansicht kann die Maske <em>Oberflächen und Nachschlagslisten</em> über Menü <em>Extras → Anpassen → Oberflächen und Nachschlagslisten</em> oder durch drucken auf die F12-Taste.</p>

<p>In der modernen Menü-Ansicht kann die Maske über die Registerkarte <em>System</em> Gruppe Anpassungen Funktion <em>Oberflächen</em> und Funktion <em>Nachschlagslisten.</em></p>

<p><img src="http://xpecto.github.io/docs/img/img_1462178525763.png" alt="" title=""></p>

<p><strong>Oberflächen</strong></p>

<p>In xpectoPro sind viele Eingabenmasken individuell anpassbar. Dies bezieht sich nicht nur auf das Layout der Masken, sondern erstreckt sich auch auf die damit verknüpfte Funktionalitäten. Während das Layout (Anzahl, Anordnung und Beschriftung der Eingabefelder) durchaus von erfahrenen Benutzern geändert werden kann, sollten Änderungen an der Funktionalität nur vom xpecto Kundensupport durchgeführt werden. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1462174447372.png" alt="" title=""></p>

<p>Auf dem Reiter <em>Vorschau</em> wird eine Vorschau von der Oberfläche dargestellt, auch ohne die Änderungen vorher zu speichern. Sie haben hier die Möglichkeit die Felder mit verschiedene Daten zu testen.</p>

<p>Über die Schaltfläche <em>Mustervorlage</em> <img src="http://xpecto.github.io/docs/img/img_1424264077326.png" alt="" title=""> wird die Mustervorlage für Standard-Positionen und -Größen angezeigt. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1462174005141.png" alt="" title=""></p>

<p>Auf dem Reiter <em>Designer</em> befindet sich ein grafischer Editor zum Bearbeiten des Layouts der selektierten Oberfläche. Eingabefelder, Auswahllisten sowie Buttons etc. können mit Hilfe des Designers problemlos verschoben werden und somit das Gesamtbild nach Ihren Wünschen angepasst werden. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1462174170782.png" alt="" title=""></p>

<p>Um ein bereits bestehendes Label oder Eingabefeld zu verschieben, markieren Sie es durch einen Klick mit der linken Maustaste und ziehen es mit gedrückter Maustaste an die gewünschten Position.  <br>
Zum Einfügen eines neuen Eingabefeldes wählen Sie in der Liste im rechten oberen Bereich die entsprechende Datenbanktabelle und darunter die gewünschte Datenbankspalte aus, mit der das Feld verknüpft werden soll. Durch Klick auf das  Icon <img src="http://xpecto.github.io/docs/img/img_1442578074569.png" alt="" title=""> in der Werkzeugleiste wird das Eingabefeld eingefügt. Speichern Sie die veränderte Oberfläche mit dem Symbol <img src="http://xpecto.github.io/docs/img/img_1442578440840.png" alt="" title=""> . </p>

<p>Reichen in einer Tabelle die vorhandene Felder nicht aus, so können weitere Felder angelegt werden. Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442580597049.png" alt="" title=""> wird ein neues Datenbankfeld angelegt.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1442580545253.png" alt="" title=""></p>

<p>Wählen Sie unter <em>1. Tabelle wählen</em> die Datenbanktabelle, die erweitert werden soll. Geben Sie unter die Feldgruppe <em>2a. Feld anlegen</em> den gewünschten Feldname, Feldtyp und das Ausgabeformat. Der benötigten Feldtyp ist abhängig von der Art der Daten, die im neu erzeugten Datenbankfeld gespeichert werden sollen. Zur Auswahl stehen: Text, langer Text, Ja/Nein, Datum, Datum und Uhrzeit, Kommazahl, Ganzzahl.</p>

<p>In dem Eingabefeld <em>Ausgabeformat</em> kann optional das Ausgabeformat des Datenfeldes angegeben werden, z.B.  #.##0,00. </p>

<p>In dem Eingabefeld <em>Parameter</em> kann man bestimmte Parameter oder eine SQL-Abfrage für das Feld angegeben werden. </p>

<p>Durch einen Klick auf die Schaltfläche <em>Feld erstellen</em> wird das Datenbankfeld angelegt.</p>

<p>Unter <em>2b. spezielle Felder anlegen</em>, werden falls gewünscht, spezielle Felder angelegt wie <em>Erfasst am, Erfasst von, Geändert am, Geändert von, Schreibschutz</em>.</p>

<p>Auf dem Karteireiter <em>Vorschau</em> kann jederzeit eine Vorschau der bearbeiteten Oberfläche angezeigt werden, auch ohne die Änderungen vorher zu speichern.</p>

<p>Über das Symbol <img src="http://xpecto.github.io/docs/img/img_1442580639187.png" alt="" title="">, kann eine neue Tabelle in der Datenbank angelegt werden. </p>

<p>Die Reiter <em>Editor</em>, <em>Layout</em> und <em>Code</em> beinhalten Editoren zur Bearbeitung des VB- und XML-Codes zur Erweiterung der Funktionalität. </p>

<p><strong>Nachschlagslisten</strong></p>

<p>Das Modul Nachschlagslisten dient dem Hinterlegen von Listen und Tabellen mit Werten, auf die an verschiedenen Stellen in der Software von kundenspezifischen Masken und Skripten zurückgegriffen werden kann.  <br>
Beispiel: Das Eingabefeld für die Anrede in der Kundenmaske kann alternativ als Auswahlfeld angelegt und so konfiguriert werden, dass die auswählbaren Werte aus einer Nachschlagsliste mit der Bezeichnung <em>Anrede</em> entnommen werden. Die verfügbaren Werte können somit vom Benutzer durch Bearbeiten der Nachschlagsliste  „Anrede” selbst angepasst werden, ohne in die Skripte eingreifen zu müssen, die das Verhalten der Kundenmaske definieren.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1442581536742.png" alt="" title=""></p>

<p>Durch die Verwendung eines Auswahlfeldes anstatt eines Eingabefeldes für die Anrede werden Tippfehler bie der Eingabe der Anrede vermeidet. Dadurch werden Peinlichkeiten bei der Erstellung von Serienbriefen vermieden, die dieses Feld enthalten. Darüber hinaus wird die Erstellung von Datenbankabfragen für Auswertungen mit Unterscheidungen der Kunden anhand des Geschlechts wesentlich erleichtert, da Tippfehler in den erfassten Anreden nicht berücksichtigt werden müssen.</p>

<p>Nachschlagslisten sind immer mit einer Skript-Programmierung an einer anderen Stelle der Software verbunden. Eine Nachschlagsliste, auf die nicht von einem kundenspezifischen Skript aus zugegriffen wird, hat keinen Sinn. Nachschlagslisten werden deshalb immer in Rücksprache und mit Hilfe des xpecto Kundensupports angelegt, der auch das zugehörige Skript programmiert. Änderungen und Erweiterungen der Werte in den hinterlegten Nachschlagslisten können später jederzeit ohne Zuhilfenahme des xpecto Kundensupports vom Benutzer durchgeführt werden. </p></div></body>
</html>