<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>600_Abfragen_erstellen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>xpectoPro bietet einen anwenderfreundlichen Abfrageeditor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt, eigene Datenbankabfragen bzw. Auswertungen zu erstellen. <br>
Sie erreichen den Abfrageeditor über den Menüpunkt <em>Bearbeiten → Abfragen erstellen</em>.</p>

<p>Nach dem öffnen des Abfrageeditors wird der Bedingungs-Assistent mit einem Bedingungsblock angezeigt, der bereits eine Bedingung enthält. Eine Bedingung ist definiert durch einen Feldnamen (links), einen Bedingungstyp (mitte) und einem vom Anwender einzugebende Vergleichswert. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1439279198546.png" alt="" title=""></p>

<p>Bedingungszeilen sind in Blöcken zusammengefasst. Am oberen Rand eines Blocks wird der verwendete Gruppierungstyp angezeigt. Mögliche Typen sind:</p>

<ul>
<li>jede der Bedingungen trifft zu (AND)  </li>
<li>eine oder mehrere Bedingungen treffen zu (OR)</li>
</ul>

<p><img src="http://xpecto.github.io/docs/img/img_1439278901176.png" alt="" title=""></p>

<p>Über die Schaltfläche “<em>Feld hinzufügen</em>” wird einem Block eine Bedingung hinzugefügt. Über die Schaltfläche “<em>Block hinzufügen</em>” wird einem Block ein Unterblock hinzugefügt. Auf diese Weise kann für einen Teil der Bedingungen ein anderer Gruppierungstyp verwendet werden.</p>

<p>Die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1419329462773.png" alt="" title=""> löscht eine Bedingungszeile oder einen Block.</p>

<p>Durch Klick auf den Feldnamen oder den Bedingungstyp kann eine Bedingung angepasst werden. Ein Klick auf den Feldnamen öffnet ein Kontextmenü zur Auswahl des gewünschten Feldnamens. Per Klick auf den Bedingungstyp kann der Typ ausgewählt werden. Folgende Bedingungstypen stehen zur  Verfügung:</p>

<table>
<thead>
<tr>
  <th>Bedingungstypen</th>
</tr>
</thead>
<tbody><tr>
  <td>entspricht einem der folgenden Werte</td>
</tr>
<tr>
  <td>endet mit</td>
</tr>
<tr>
  <td>beginnt mit</td>
</tr>
<tr>
  <td>ist leer</td>
</tr>
<tr>
  <td>entspricht keinem der folgenden Werte</td>
</tr>
<tr>
  <td>enthält nicht</td>
</tr>
<tr>
  <td>endet nicht mit</td>
</tr>
<tr>
  <td>beginnt nicht mit</td>
</tr>
<tr>
  <td>ist nicht leer</td>
</tr>
</tbody></table>


<p>Schließlich werden in den Eingabefeldern die Vergleichswerte der jeweiligen Bedingung eingetragen.</p>

<p>Beispiel: Sie wollen wissen, welche Kunden des Vermittlers VP0001 im Zeitraum 01.12.2014 bis 31.12.2014 Verträge des Produkts “TRI1, Top Return Invest I” abgeschlossen hat.</p>

<p>Starten Sie den Abfrageeditor und passen Sie die vorgegebene Bedingungszeile folgendermaßen an: Klicken Sie auf den Feldnamen Vertrags-Nr und wählen im darauf folgenden Kontextmenü das Feld Vertriebspartner Betreuer-Nr. Tragen Sie in das Eingabefeld die Vermittlernummer ein.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1431932441285.png" alt="" title=""></p>

<p>Legen Sie über “<em>Feld hinzufügen</em>” zwei weitere Bedingungszeilen an, wählen Sie mit der oben beschriebenen Methode die Felder Produkte Produktname und Vertragsdaten  Abschlussdatum und tragen Sie die entsprechenden Werte in die zugehörigen Eingabefelder ein.</p>

<p>Klicken sie nun auf <em>Weiter</em>. Auf der nächsten Seite können die Datenbankfelder, die in der Anzeige des Abfrageergebnisses ausgegeben werden sollen, durch anhaken ausgewählt werden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1431933240955.png" alt="" title=""></p>

<p>In diesem Beispiel sind Adresse, Bezeichner, Kundennummer des Kunden, Adresse und Bezeichner des Vertriebspartners ausgewählt.</p>

<p>Klicken sie nun erneut auf <em>Weiter</em>, um zur Anzeige des Abfrageergebnisses zu gelangen. In der Ergebnisanzeige wird im oberen Bereich die anhand der vorher definierten Parameter automatisch generierte Datenbankabfrage angezeigt. Darunter erscheint eine Liste mit dem Ergebnis der Abfrage.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1431932658461.png" alt="" title=""></p>

<p>Die dargestellten Datensätze können über Betätigung der entsprechenden Schaltflächen  CSV, SQL oder Excel weitergegeben werden.  <br>
Die Weitergabe der Daten ist  einfach. Ein Klick auf “<em>Excel</em>” oder “<em>CSV</em>” öffnet die ermittelten Daten direkt in Excel und Sie können die Daten dann dort weiterverarbeiten. <br>
Die Daten können auch direkt an eine Kampagne übergeben werden. Über die Schaltfläche Kampagne kann eine Kampagne gestartet werden (siehe <em>Bearbeiten → Kampagnen</em>).  <br>
Über SQL Schaltfläche können Sie Insert Statement erstellen, Daten in Importdialog laden oder Aktion abbrechen. <br>
Mit Hilfe von Insert Statements werden neue Datensätze in eine Tabelle eingefügt. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1431933091869.png" alt="" title=""></p>

<p>Über dem Importdialog können Sie z.B. Datensätze importieren, Tabellen importieren in der Datenbank oder zwischen Datenbanken. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1431932842038.png" alt="" title=""></p>

<p>Wählen Sie das Produkt aus, zu dem die Datensätze importiert werden sollen. </p>

<p>Klicken Sie auf die Schaltfläche  <img src="http://xpecto.github.io/docs/img/img_1421152862771.png" alt="" title=""> um die zu importierende Datei auszuwählen.</p>

<p>Je nach Dateiformat der zu importierenden Daten müssen die Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format.  <br>
Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1421159835110.png" alt="" title=""> werden die Importdaten als Tabelle angezeigt. <br>
Starten sie den Import durch die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1421159892128.png" alt="" title="">.</p>

<p>Nachdem Sie die folgende Meldung mit <em>OK</em> bestätigt haben sind die angezeigten Daten importiert. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1421160002075.png" alt="" title=""></p>

<p>Durch Betätigung von <img src="http://xpecto.github.io/docs/img/img_1431935009760.png" alt="" title="">  können Sie den Abfrageeditor beenden.</p></div></body>
</html>