<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>300_Kontodaten_importieren.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Dieses Modul dient dem Import von Bankbewegungsdaten mittels Export-Dateien aus E-Banking-Programmen. Der Import von Bankbewegungen geschieht in zwei Schritten. Im ersten Schritt (siehe diesen Menüpunkt) werden die Bewegungsdaten in eine Temporärtabelle importiert. Im zweiten Schritt (siehe nachfolgendes Menüpunkt: <em>Kontodaten zuweisen</em>) werden aus den Datensätzen der Temporärtabelle Buchungssätze erzeugt.</p>

<p>Wählen Sie das Produkt aus, zu dem die Kontodaten importiert werden sollen, sowie das Importkonto (Bankkonto), von dem die Buchungen stammen.</p>

<p>Klicken Sie auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1441983048557.png" alt="" title=""> um die zu importierende Datei auszuwählen.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1441982998218.png" alt="" title=""></p>

<p>Je nach Dateiformat der zu importierenden Daten müssen das Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. Enthalten die zu importierenden Daten Datensätze, die sich bereits in der verwendeten Datenbank befinden, so setzen Sie ein Häkchen bei <em>“Datei enthält alte Daten”</em>. Dies verhindert die doppelte Anlage bereits vorhandener Datensätze (bereits vorhandene Datensätze werden durch einen Abgleich-Algorithmus erkannt und übersprungen). Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img160.png" alt="" title=""> <br>
werden die Importdaten (bei Verwendung der richtigen Trennzeichen bzw. Textzeichen) als Tabelle angezeigt. Weisen sie nun die Spalten der Importdatei den passenden Spalten der Datenbank zu. Nachdem alle Spalten zugewiesen sind, starten Sie den Import durch die Schaltfläche<img src="http://xpecto.github.io/docs/img/img162.png" alt="" title="">. Bankbewegungen, die im Verwendungszweck eine Vertragsnummer enthalten, werden dabei automatisch dem angegebenen Vertrag zugewiesen.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1441983215647.png" alt="" title=""></p>

<p>Bestätigen Sie obige Meldung mit <em>OK</em>. Die Importdaten sind nun erfolgreich in die Importtabelle Ihrer Buchungsdaten importiert werden. Wie aus obiger Meldung hervor geht, wurden 8 Buchungen importiert und 0 Buchungen sofort Verträgen zugeordnet.</p>

<p>Achtung: Der Import der Buchungen ist an dieser Stelle noch nicht vollständig. Daten, die importiert wurden, aber noch nicht übernommen wurden, werden bei Berechnungen noch nicht berücksichtigt. Die importierten Daten werden hier lediglich in eine Temporärtabelle geschrieben, sie müssen später noch über das Modul <em>“Kontodaten verbuchen”</em> in die Buchungstabelle übertragen werden (siehe nachfolgenden Menüpunkt: <em>Kontodaten zuweisen</em>).</p></div></body>
</html>