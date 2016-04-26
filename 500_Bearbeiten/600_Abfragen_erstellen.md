<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>600_Abfragen_erstellen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>xpectoPro bietet einen anwenderfreundlichen Abfrage-Editor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt, eigene Datenbankabfragen bzw. Auswertungen zu erstellen.</p>

<p>In der klassischen Menü-Ansicht erreichen Sie den Abfrage-Editor über den Menüpunkt <em>Bearbeiten → Abfragen erstellen</em>.</p>

<p>In der modernen Menü-Ansicht ist die Funktion <em>Abfragen / Verteiler</em> unter der Registerkarte <em>Berichte und Massenaktionen</em> Gruppe <em>Bearbeiten.</em></p>

<p><img src="http://xpecto.github.io/docs/img/img_1461657987778.png" alt="" title=""></p>

<p>Klicken Sie auf die Funktion <em>Abfragen / Verteiler</em> um den Editor <em>Abfragen und Listen</em> zu öffnen.</p>

<p>Nach dem öffnen des <em>Abfragen und Liste</em> Editors wird der Bedingungsassistent mit einem Bedingungsblock angezeigt, der bereits eine Bedingung enthält. Eine Bedingung ist definiert durch einen Feldnamen (links), einen Bedingungstyp (mitte) und einem vom Anwender einzugebende Vergleichswert. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461660884744.png" alt="" title=""></p>

<p>Bedingungszeilen sind in Blöcken zusammengefasst. Am oberen Rand eines Blocks wird der verwendete Gruppierungstyp angezeigt. Mögliche Typen sind:</p>

<ul>
<li>jede der Bedingungen trifft zu (AND)  </li>
<li>eine oder mehrere Bedingungen treffen zu (OR)</li>
</ul>

<p><img src="http://xpecto.github.io/docs/img/img_1461661044973.png" alt="" title=""></p>

<p>Über die Schaltfläche “<em>Feld hinzufügen</em>” wird einem Block eine Bedingung hinzugefügt. Über die Schaltfläche “<em>Block hinzufügen</em>” wird einem Block ein Unterblock hinzugefügt. Auf diese Weise kann für einen Teil der Bedingungen ein anderer Gruppierungstyp verwendet werden.</p>

<p>Die Schaltfläche  <img src="http://xpecto.github.io/docs/img/img_1461661108624.png" alt="" title=""> löscht eine Bedingungszeile.</p>

<p>Durch Klick auf den Feldnamen oder den Bedingungstyp kann eine Bedingung angepasst werden. Ein Klick auf der Feldnamen öffnet ein Kontextmenü zur Auswahl des gewünschten Feldnamens. Per Klick auf den Bedingungstyp kann der Typ ausgewählt werden. Folgende Bedingungstypen stehen zur  Verfügung:</p>

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
  <td>enthält</td>
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
<tr>
  <td>entspricht einem der folgenden Tage</td>
</tr>
<tr>
  <td>ist von - bis</td>
</tr>
<tr>
  <td>ist kleiner/früher oder entspricht folgendem Wert</td>
</tr>
<tr>
  <td>ist größer/später oder entspricht folgendem Wert</td>
</tr>
<tr>
  <td>entspricht keinem der folgenden Tage</td>
</tr>
<tr>
  <td>ist nicht von - bis</td>
</tr>
</tbody></table>


<p>Schließlich werden in den Eingabefeldern die Vergleichswerte der jeweiligen Bedingung eingetragen.</p>

<p>Beispiel: Sie wollen wissen, welche Kunden der Vermittler VP0001 und VP0002 im Zeitraum 01.01.2001 bis 01.04.2016 Verträge des Produkts <em>TRI1, Top Return Invest I</em> abgeschlossen haben.</p>

<p>Starten Sie den Abfrage-Editor und passen Sie die vorgegebene Bedingungszeile folgendermaßen an: klicken Sie auf den Feldnamen <em>Vertrags-Nr</em> wählen im darauf folgenden Kontextmenü das Feld <em>Vertriebspartner → Betreuer-Nr.</em> Tragen Sie in das Eingabefeld die Vermittlernummer ein. Sie haben hier die Möglichkeit nach einem Feld zu suchen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461661794519.png" alt="" title=""></p>

<p>Legen Sie über “<em>Feld hinzufügen</em>” zwei weitere Bedingungszeilen an, wählen Sie mit der oben beschriebenen Methode die Felder: <em>Produkte → Produktname</em> und <em>Vertragsdaten → Abschlussdatum</em> und tragen Sie die entsprechenden Werte in die zugehörigen Eingabefelder ein.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461663211041.png" alt="" title=""></p>

<p>Klicken sie nun auf <em>Weiter</em>. Auf der nächsten Seite können die Datenbankfelder, die in der Anzeige des Abfrageergebnisses ausgegeben werden sollen, durch anhaken ausgewählt werden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461663371382.png" alt="" title=""> <br>
In diesem Beispiel sind <em>Bezeichner, Kundennummer, Abschlussdatum, Produkt, Tarif, Vertragsnummer, Betreuernummer, Produktname</em> ausgewählt.</p>

<p>Klicken sie nun erneut auf <em>Weiter</em>, um zur Anzeige des Abfrageergebnisses zu gelangen. In der Ergebnisanzeige wird im oberen Bereich die anhand der vorher definierten Parameter automatisch generierte Datenbankabfrage angezeigt. Darunter erscheint eine Liste mit dem Ergebnis der Abfrage.</p>

<p>Die dargestellten Datensätze können über Betätigung der entsprechenden Schaltflächen  <em>CSV</em>, <em>SQL</em> <em>Excel</em> und <em>Kampagne</em> weitergegeben werden. Ein Klick auf <em>Excel</em> oder <em>CSV</em> öffnet die ermittelten Daten direkt in Excel und Sie können die Daten dann dort weiterverarbeiten.  </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461663524234.png" alt="" title=""></p>

<p>Die Daten können auch direkt an eine Kampagne übergeben werden. Über die Schaltfläche <em>Kampagne</em> kann eine Kampagne gestartet werden (siehe  Handbuch <em>Bearbeiten → Kampagnen</em>). </p>

<p>Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1461663694281.png" alt="" title=""> können Sie <em>Insert Statements erstellen</em>, Daten in <em>Importdialog laden</em> oder die <em>Aktion abbrechen</em>.  Die Insert-Operationen werden dann in Editor angezeigt.</p>

<p>Um die Daten zu importieren klicken Sie auf die Schaltfläche Daten in Importdialog laden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461663786302.png" alt="" title=""></p>

<p>In dem Importdialog können Sie z.B. Datensätze / Tabellen in der Datenbank importieren(siehe Handbuch <em>Import/Export → Allgemeiner Import</em>). </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461664576287.png" alt="" title=""></p>

<p>Um Datensätze zu importieren, wählen Sie das Produkt aus, zu dem die Datensätze importiert werden sollen  falls der Produkt nicht in eine Spalte enthalten ist. </p>

<p>Durch Betätigung der Schaltfläche <em>Vorschau</em> werden die vorbereitete Daten angezeigt. <br>
Wenn bereits Datensätze mit derselbe ID in der Datenbank vorhanden sind, dann werden diese nicht aktualisiert nur wenn die Checkbox <em>vorhandene Daten aktualisiert</em> markiert ist.</p>

<p>Wenn Sie Tabellen aus einer Datei, in der Datenbank importieren wollen, dann klicken Sie auf die Schaltfläche  <img src="http://xpecto.github.io/docs/img/img_1421152862771.png" alt="" title="">  neben das Feld Datei um die zu importierende Datei auszuwählen.</p>

<p>Je nach Dateiformat der zu importierenden Daten müssen die Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format.  <br>
Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden.  <br>
Durch betätigen von <em>Vorschau</em> werden die Importdaten als Tabelle angezeigt. <br>
 Um den Import zu starten klicken Sie auf die Schaltfläche: <img src="http://xpecto.github.io/docs/img/img_1421159892128.png" alt="" title="">.</p>

<p>Nachdem Sie die folgende Meldung mit <em>OK</em> bestätigt haben sind die angezeigten Daten importiert. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1421160002075.png" alt="" title=""></p>

<p>Durch Betätigung von <img src="http://xpecto.github.io/docs/img/img_1431935009760.png" alt="" title="">  wird der Abfrage-Editor beendet.</p></div></body>
</html>