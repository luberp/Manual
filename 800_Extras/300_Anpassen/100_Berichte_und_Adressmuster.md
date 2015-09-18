<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>100_Berichte_und_Adressmuster.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Alle Ausdrucke, die mit xpecto erstellt werden (wie z. B. Provisionsabrechnungen, Kundenanschreiben,c.), basieren auf gespeicherten Vorlagen, die entweder über die integrierte Berichtserstellungs-Komponente ActiveReports, oder über den Word-Editor erstellt werden. Die Vorlagen für Ausdrucke und Schreiben werden deshalb im folgenden (und auch bei der Kommunikation mit dem xpecto Kundensupport) als Berichte bezeichnet. Jeder Bericht besteht aus einem Layout, einer Datenbankabfrage sowie einigen Konfigurationsparametern. </p>

<p>Neben Berichte können Sie auch Adressmuster, Textbausteine und individuelle Schreiben erstellen.</p>

<p>Über die Symbolleiste <img src="http://xpecto.github.io/docs/img/img_1442245724286.png" alt="" title=""> oder über Menü <em>Extras → Anpassen → Berichte und Adressmuster</em> starten Sie den <em>xpectoPro Berichte und Textbausteine</em> -Dialog.</p>

<p>Berichte werden über Namen unterschieden, und thematisch in Gruppen verwaltet. Klicken Sie auf das Symbol <img src="http://xpecto.github.io/docs/img/img_1424086630188.png" alt="" title=""> um eine neue Gruppe anzulegen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1424086718173.png" alt="" title=""></p>

<p>Geben Sie den Namen für die neue Gruppe an und bestätigen Sie mit <em>OK</em>.</p>

<p>Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1424086982407.png" alt="" title=""> wird ein neuer Bericht angelegt. Gleichzeitig können Sie auch eine neue Gruppe anlegen. durch Auswählen des Checkboxes <em>neue Gruppe anlegen.</em> </p>

<p><img src="http://xpecto.github.io/docs/img/img_1442415998478.png" alt="" title=""></p>

<p>Ein neuer Bericht kann entweder ein leerer Bericht, eine Kopie eines bestehenden Berichts, ein tabellarischer Bericht oder eine xpecto Vorlage angelegt werden.  <br>
In jedem Fall muss der Name für den neuen Bericht, die Gruppe in die der Bericht eingegliedert werden soll und die Datenbasis, angegeben werden.  <br>
Bei Auswahl einer Datenbasis wird automatisch eine entsprechende Datenbankanfrage generiert und im Bericht hinterlegt. </p>

<table>
<thead>
<tr>
  <th>Bericht Art</th>
  <th align="left">Beschreibung</th>
</tr>
</thead>
<tbody><tr>
  <td>Microsoft Word</td>
  <td align="left">Word-Bericht</td>
</tr>
<tr>
  <td>integrierter Berichtsgenerator</td>
  <td align="left">Active Reports. ActiveReports ist sind Komponenten für Forms- und Webanwendungen um Daten in Dokumente und web basierte Formate anzuzeigen.</td>
</tr>
<tr>
  <td>Datenexport</td>
  <td align="left">Excel-Bericht in Tabellenform</td>
</tr>
<tr>
  <td>HTML Mail</td>
  <td align="left">HTML Format</td>
</tr>
<tr>
  <td>PDF Formular</td>
  <td align="left">PDF Format</td>
</tr>
<tr>
  <td>Meta-Bericht</td>
  <td align="left">Fasst mehrere Berichte zusammen</td>
</tr>
<tr>
  <td>Einfaches RTF oder Docx</td>
  <td align="left">RTF oder Docx Format</td>
</tr>
<tr>
  <td>Festes Seiten Layout</td>
  <td align="left">Seiten Layout vorgegeben</td>
</tr>
</tbody></table>


<p>Die Art des Berichts kann nachträglich nicht mehr geändert werden! Durch Klick auf <em>OK</em> wird der Bericht angelegt.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1442317569556.png" alt="" title=""></p>

<p>Unter dem Reiter <em>Allgemein</em> können der Name und die Gruppe des Berichts geändert werden. Außerdem besteht die Möglichkeit, eine Beschreibung einzugeben.</p>

<p>Unter dem Reiter <em>Entwurf</em> wird das Layout des Berichts erstellt. Je nach dem, ob es sich um einen Word-Bericht oder um einen ActiveReports-Bericht handelt, erscheint hier ein Word-Editor oder der Berichtseditor von Data Dynamics zur Bearbeitung des Layouts. Die Funktionsweise des Word-Editors ist angelehnt an die Grundfunktionen von Microsoft-Word. Der Editor sollte nur von Benutzer mit Erfahrung in Microsoft-Word verwendet werden, die Bedienung ist dann selbsterklärend.  <br>
Hilfe zur Bedienung des Layout-Editors von Data Dynamics erhalten Sie im Internet unter der Adresse <a href="http://www.componentone.com/">http://www.componentone.com/</a> oder vom xpecto Kundensupport.</p>

<p>Unter dem Reiter <em>Abfrage</em> kann die dem Bericht zugrunde liegende Datenbankabfrage bearbeitet werden.  <br>
Benutzer benötigen hierzu Grundkenntnisse SQL. Das Eingabefeld <em>Filter Field-IDs</em> zeigt der zuletzt ausgewählten Wert in eine Tabelle an, und kann in der WHERE-Bedingung eingebaut werden.</p>

<p>Unter dem Reiter <em>Zusatzdaten</em> kann jeweils ein anderen Bericht als Kopfzeile bzw. Fußzeile, Briefpapier ausgewählt werden. So kann auf einfache Weise ein einheitlicher Briefkopf für mehrere Berichte verwendet werden. Änderungen am Briefkopf müssen dann zentral an einer Stelle durchgeführt werden, und nicht in jedem einzelnen Bericht. Als Kopf-, Fußzeile, oder Briefpapier können nur die Berichte verwendet die entsprechend kategorisiert sind. Unter dem Reiter <em>Kategorien</em>  Feldgruppe <em>Unterbericht</em> können die Einstellungen festgelegt.</p>

<p>Unter dem Reiter <em>Kategorien</em> kann der bearbeitete Bericht kategorisiert werden. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1442317999574.png" alt="" title=""></p>

<p>Mit den Optionen unter der Feldgruppe <em>Allgemeiner Bericht</em> kann festgelegt werden, unter welchen Umständen der Bericht in den Berichts-Favoriten auf der Symbol- und Funktionsleiste dem Hauptfenster angezeigt werden soll. Dies ist sinnvoll für häufig verwendete Berichte, da diese dann direkt von der Hauptmaske aus gedruckt werden können.</p>

<p>Unter der Feldgruppe <em>Unterbericht</em> kann festgelegt werden, dass es sich bei dem Bericht um eine Kopfzeile Fußzeile oder Briefpapier handelt. Der Bericht kann dann in anderen Berichten als Kopfzeile bzw. Fußzeile ausgewählt werden. </p>

<p>Die Optionen unter <em>Beleg</em> geben die Möglichkeit ein Bericht als Beleg zu archivieren, dazu muss ein Belegtyp angegeben werden.</p>

<p>Die Optionen unter <em>Spezieller Bericht</em> haben keine direkte Auswirkung, sie sind für weitere geplante Funktionen vorgesehen. Wenn z.B. Verteiler für Kampagnen ausgewählt ist, dann wird der Bericht in der Kampagnen unter Feldgruppe <em>Datenquelle wählen</em> zu Auswahl stehen.</p>

<p>Unter dem Reiter <em>Versandoptionen</em> werden die Parameter für die Online-Zustellung von Ausdrucken, Archiv-Einstellungen und Exportformat definiert. Z.B. <em>eBrief Sofortdruck</em> hat eine Schnittstelle zu Software damit wird die PDF Datei zur Versandzentrum geschickt und für Versand vorbereitet, oder <em>eService Upload</em> in VP-Portal und Kundenportal.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1442570315303.png" alt="" title=""></p>

<p>In dem Dialog <em>xpectoPro Berichte und Textbausteine</em> über die eigene Symbolleiste, können Sie ein ausgewählter Bericht löschen, exportierten oder importieren.  <br>
Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1424865740751.png" alt="" title="">  wird der aktuell selektierte Bericht gelöscht. Bestätigen Sie danach der folgende Dialog mit <em>Ja</em> um den Bericht endgültig zu löschen.</p>

<p><em>Adressmuster</em> ist eine SQL-Abfrage die nur ein einziges Feld und eine einzige Zeile zurück liefern darf.</p>

<p>Textbausteine, Individuelle Schreiben</p>

<p>Individuelle Schreiben können aus Textbausteine gebaut werden.</p>

<p>Symbol: Bericht erzeugen: generiert nur den Bericht. <br>
Symbol: Bericht bearbeiten: generiert die Vorlage die man danach bearbeiten kann.</p></div></body>
</html>