<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>600_Abfragen_erstellen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>xpectoPro bietet einen anwenderfreundlichen Abfrageeditor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt, eigene Datenbankabfragen bzw. Auswertungen zu erstellen.</p>

<p>Sie erreichen den Abfrageeditor über den Menüpunkt <em>Bearbeiten → Abfrage erstellen</em>.</p>

<p>Nach dem öffnen des Abfrageeditors wird der Bedingungs-Assistent mit einem Bedingungsblock angezeigt, der bereits eine Bedingung enthält. Bewegen Sie die Maus über Teile des Bedingungsblocks, um Tipps zu erhalten. Eine Bedingungszeile ist definiert durch einen Feldnamen (links), einen Bedingungstyp (mitte) und einem vom Anwender einzugebende Vergleichswert. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1419329260261.png" alt="" title=""></p>

<p>Bedingungszeilen sind in Blöcken zusammengefasst. Am oberen Rand eines Blocks wird der verwendete Gruppierungstyp angezeigt. Mögliche Typen sind:</p>

<ul>
<li>jede der Bedingungen trifft zu (AND)   </li>
<li>eine oder mehrere Bedingungen treffen zu (OR)</li>
</ul>

<p>Über die Schaltfläche “<em>Feld hinzufügen</em>” wird einem Block eine Bedingung hinzugefügt. Über die Schaltfläche “<em>Block hinzufügen</em>” wird einem Block ein Unterblock hinzugefügt. Auf diese Weise kann für einen Teil der Bedingungen ein anderer Gruppierungstyp verwendet werden.</p>

<p>Die Schaltfläche  <img src="http://xpecto.github.io/docs/img/img_1419329462773.png" alt="" title=""> löscht eine Bedingungszeile.</p>

<p>Durch Klick auf den Feldnamen oder den Bedingungstyp kann eine Bedingung angepasst werden. Ein Klick auf den Feldnamen öffnet ein Kontextmenü zur Auswahl des gewünschten Feldnamens. Per Klick auf den Bedingungstyp kann der Typ ausgewählt werden. Folgende Bedingungstypen stehen zur  Verfügung:</p>

<ul>
<li>entspricht einem der folgenden Werte </li>
<li>endet mit </li>
<li>beginnt mit </li>
<li>ist leer</li>
<li>ist nicht leer</li>
</ul>

<p>Schließlich werden in den Eingabefeldern die Vergleichswerte der jeweiligen Bedingung eingetragen.</p>

<p>Betrachten wir folgendes Beispiel: <br>
Sie wollen wissen, welche Kunden des Vermittlers VP0001 im Zeitraum 01.12.2014 bis 31.12.2014 Verträge des Produkts “TRI1, Top Return Invest I” abgeschlossen hat.</p>

<p>Starten Sie den Abfrageeditor und passen Sie die vorgegebene Bedingungszeile folgendermaßen an: Klicken Sie auf den Feldnamen Vertrags-Nr und wählen im darauf folgenden Kontextmenü das Feld Vertriebspartner Betreuer-Nr. Tragen Sie in das Eingabefeld die Vermittlernummer ein.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1419332163233.png" alt="" title=""></p>

<p>Legen Sie über “<em>Feld hinzufügen</em>” zwei weitere Bedingungszeilen an, wählen Sie mit der oben beschriebenen Methode die Felder Produktname und Abschlussdatum und tragen Sie die entsprechenden Werte in die zugehörigen Eingabefelder ein.</p>

<p>Klicken sie nun auf <em>Weiter</em>. Auf der nächsten Seite können die Datenbankfelder, die in der Anzeige des Abfrageergebnisses ausgegeben werden sollen, durch anhaken ausgewählt werden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1419341604703.png" alt="" title=""></p>

<p>In diesem Beispiel sind Adresse, Bezeichner, Kundennummer des Kunden, Adresse und Bezeichner des Vertriebspartners ausgewählt.</p>

<p>Klicken sie nun erneut auf <em>Weiter</em>, um zur Anzeige des Abfrageergebnisses zu gelangen. In der Ergebnisanzeige wird im oberen Bereich die anhand der vorher definierten Parameter automatisch generierte Datenbankabfrage angezeigt. Darunter erscheint eine Liste mit dem Ergebnis der Abfrage.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1421155722737.png" alt="" title=""></p>

<p>Die dargestellten Datensätze können über Betätigung der entsprechenden Schaltflächen  CSV, SQL oder Excel weitergegeben werden. <br>
Die Weitergabe der Daten ist  einfach. Ein Klick auf “Excel” oder “CSV” öffnet die ermittelten Daten direkt in Excel und Sie können die Daten dann dort weiterverarbeiten.  <br>
Die Daten können auch direkt an eine Kampagne übergeben werden. Über die Schaltfläche Kampagne kann eine Kapagne gestartet werden (siehe Kampagne). <br>
Über SQL Schaltfläche können Sie Insert Statement erstellen, Daten in Importdialog laden oder Aktion abbrechen.  <br>
Mit Hilfe von Insert Statements werden neue Datensätze in eine Tabelle eingefügt. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1419342669871.png" alt="" title=""></p>

<p>Über dem Importdialog können Sie z.B. Datensätze importieren, Tabellen importieren in der Datenbank oder zwischen Datenbanken. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1419345799957.png" alt="" title=""></p>

<p>Wählen Sie das Produkt aus, zu dem die Datensätze importiert werden sollen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1421152862771.png" alt="" title=""></p>

<p>um die zu importierende Datei auszuwählen.  <br>
Je nach Dateiformat der zu importierenden Daten müssen die Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. <br>
Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. Mit der Schaltfläche (Bild) werden die Importdaten als Tabelle angezeigt.  <br>
Starten sie den Import durch die Schaltfläche.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1419345799957.png" alt="" title=""></p>

<p>Beenden Sie den Abfrageeditor mit <img src="http://xpecto.github.io/docs/img/img_1419346860827.png" alt="" title="">.</p>

<p>Der Abfrageeditor bietet Anwendern ohne SQL-Kenntnisse die Möglichkeit, Datenbankabfragen mittlerer Komplexität selbständig zu erstellen. <br>
Falls Sie Auswertungen benötigen, die mit den beschriebenen Methoden nicht abbildbar sind, wenden Sie sich an den xpecto Kundensupport.</p></div></body>
</html>