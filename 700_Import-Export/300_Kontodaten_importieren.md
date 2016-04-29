<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>300_Kontodaten_importieren.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Dieses Modul dient dem Import von Bankbewegungsdaten mittels Export-Dateien aus E-Banking-Programmen. Der Import von Bankbewegungen geschieht in zwei Schritten. Im ersten Schritt (siehe diesen Menüpunkt) werden die Bewegungsdaten in eine temporäre Tabelle importiert. Im zweiten Schritt (siehe nachfolgendes Menüpunkt: <em>Kontodaten zuweisen</em>), werden aus den Datensätzen der temporären Tabelle Buchungssätze erzeugt.</p>

<p>In der klassischen Menü-Ansicht ist der Import über Menü <em>Import/Export → Kontodaten importieren</em>.</p>

<p>In der modernen Menü-Ansicht ist diese Funktion über die Registerkarte <em>Buchhaltung</em> Gruppe <em>Kontodaten</em> zu finden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461915546419.png" alt="" title=""></p>

<p>Starten Sie den Dialog Buchungsdaten importieren und wählen Sie das Produkt aus, zu dem die Kontodaten importiert werden sollen, die Datei die die Bankbewegungen enthält sowie das Importkonto (Bankkonto), von dem die Buchungen stammen.</p>

<p>Klicken Sie auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1441983048557.png" alt="" title=""> um die zu importierende Datei auszuwählen.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461916837261.png" alt="" title=""></p>

<p>Je nach Dateiformat der zu importierenden Daten müssen das Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. Enthalten die zu importierenden Daten Datensätze, die sich bereits in der verwendeten Datenbank befinden, so setzen Sie ein Häkchen bei <em>Datei enthält alte Daten</em>. Dies verhindert die doppelte Anlage bereits vorhandener Datensätze (bereits vorhandene Datensätze werden durch einen Abgleich-Algorithmus erkannt und übersprungen). Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden.  <br>
Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442233708499.png" alt="" title=""> werden die Importdaten (bei Verwendung der richtigen Trennzeichen bzw. Textzeichen) als Tabelle angezeigt.  <br>
Weisen sie nun die Spalten der Importdatei den passenden Spalten der Datenbank zu - <em>Schritt 3: Spalten zuweisen</em>. Bei Dateien im  MT940 Bankformat wird die Spaltenzuordnung automatisch vorgeschlagen. <br>
Nachdem alle Spalten zugewiesen sind, starten Sie den Import durch die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442233746695.png" alt="" title="">.  <br>
Bankbewegungen, die im Verwendungszweck eine Vertragsnummer enthalten, werden dabei automatisch dem angegebenen Vertrag zugewiesen.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1441983215647.png" alt="" title=""></p>

<p>Bestätigen Sie obige Meldung mit <em>Weiter zu Kontodaten zuweisen</em>. Die Bankbewegungen/Importdaten sind nun erfolgreich in die temporäre Tabelle importiert worden. </p>

<p>Achtung: Der Import der Buchungen ist an dieser Stelle noch nicht vollständig. Daten, die importiert wurden, aber noch nicht übernommen wurden, werden bei Berechnungen noch nicht berücksichtigt. Die importierten Daten werden hier lediglich in eine temporäre Tabelle geschrieben, sie müssen später noch über das Modul <em>Kontodaten zuweisen</em> in die Buchungstabelle übertragen werden (siehe nachfolgenden Menüpunkt: <em>Kontodaten zuweisen</em>).</p></div></body>
</html>