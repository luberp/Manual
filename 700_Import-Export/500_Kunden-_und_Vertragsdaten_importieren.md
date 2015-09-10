<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>500_Kunden-_und_Vertragsdaten_importieren.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Dieses Modul dient dem Import von Verträgen einschließlich Kundenstammdaten.</p>

<p>Wählen Sie das Produkt bzw. den Fonds, zu dem die Kundendaten importiert werden sollen. Enthält die zu importierende Datei bereits eine Produktspalte, setzen Sie in der Checkbox <em>“Datei enthält Produktspalte”</em> ein Häkchen. Hierdurch entfällt die Auswahl des Produkts. Klicken Sie auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1441889824466.png" alt="" title=""> um die zu importierende Datei auszuwählen.</p>

<p>Je nach Dateiformat der zu importierenden Daten müssen das Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung derAuswahlfelder entspricht dem Import einer Datei im CSV Format. Unter <em>“Prozedur”</em> wird die zur Verarbeitung der Daten zu verwendende Import-Prozedur ausgewählt. Import-Prozeduren müssen vorher vom xpecto Kundensupport hinterlegt werden. Enthalten die zu importierenden Daten Datensätze, die sich bereits in der verwendeten Datenbank befinden, so setzen Sie ein Häkchen bei    <em>vorhandene Kunden und Verträge aktualisieren</em>. Dies verhindert die doppelte Anlage bereits vorhandener Datensätze (bereits vorhandene Datensätze werden durch einen Abgleich-Algorithmus erkannt und aktualisiert). Unter <em>Schritt 2: Importparameter festlegen</em> kann angegeben werden, dass fehlende Verträge, Kunden oder Vermittler angelegt werden sollen. Andernfalls werden nur bestehende Datensätze aktualisiert.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1441889791683.png" alt="" title=""></p>

<p>Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1441889857529.png" alt="" title=""> werden die Importdaten (bei Verwendung der richtigen Trennzeichen bzw. Textzeichen) als Tabelle angezeigt. Weisen sie nun die Spalten der Importdatei den passenden Spalten der Datenbank zu. Nachdem alle Spalten zugewiesen sind, starten Sie den Import durch die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1441889884609.png" alt="" title="">.</p>

<p>Der erfolgreiche Import der Kundendaten und Vertragsdaten wird durch eine Meldung unter Angabe der Anzahl der importierten Kunden und Verträge bestätigt. Bei Fehlschlagen des Imports eines oder mehrerer Datensätze (z.B. aufgrund fehlerhafter Daten) wird eine entsprechende Meldung angezeigt, und der komplette Import abgebrochen. Prüfen Sie in diesem Fall die zu importierende Datei auf Korrektheit, oder wenden Sie sich an den xpecto Kundensupport.</p></div></body>
</html>