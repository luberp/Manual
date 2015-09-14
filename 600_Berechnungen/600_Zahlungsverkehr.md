<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>600_Zahlungsverkehr.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Das Modul <em>Zahlungsverkehr</em> berechnet für ratierliche Verträge die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten. Über <em>Berechnungen → Zahlungsverkehr</em> soll das <em>Zahlungsverkehr</em>-Maske geöffnet werden. Hier können Sie direkt mit dem Berechnungsverlauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern.  </p>

<p><img src="http://xpecto.github.io/docs/img/img_1441985519757.png" alt="" title=""></p>

<p>Starten Sie die Berechnung mit einem Klick auf <img src="http://xpecto.github.io/docs/img/img_1441715573070.png" alt="" title="">.  xpectoPro ermittelt nun alle fällige Bankeinzüge zu diesem Datum und fasst diese zusammen. Es erscheint eine Liste mit Verträgen und den dazugehörigen Raten-Sollstellungen. Wählen Sie die abzurechnenden Verträge aus und erstellen Sie die gewünschte Ausgabedatei. </p>

<p>Mit einem Klick auf <img src="http://xpecto.github.io/docs/img/img_1441720924595.png" alt="" title=""> wird die Plausibilitätsprüfung der einzelne Daten gestartet. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1441717900163.png" alt="" title=""></p>

<p>Klicken Sie auf <em>Ja</em> um die Zahlungsaufträge zusammenzufassen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1441716256692.png" alt="" title=""></p>

<p>Um die Details der einzelne Sollstellungen anzeigen zu lassen klicken Sie auf <img src="http://xpecto.github.io/docs/img/img_1441717792618.png" alt="" title="">. Hier sehen Sie welche Daten fehlerhaft sind, diese werden automatisch markiert. </p>

<p>Bei der Erfassung eines Vertrages werden alle für den späteren Bankeinzug relevanten Daten  eingetragen. Im Vertrag erfassen Sie die Ratenhöhe, die Laufzeit, das Datum der erste Rate, die Bankverbindung, das Einzugsinterval und die Art des Einzugs.</p>

<p>Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1441718401250.png" alt="" title=""> werden die Zahlungsverkehrsdateien  in PDF und CSV erzeugt. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1440769740999.png" alt="" title=""></p>

<p>Das System kann Lastschriften in verschiedene Formate ausgeben: PDF, CSV und XML. Die Dateien können dann über die entsprechende Banksysteme eingereicht werden. <br>
Bei der einzelne Verträge würde dann der Zahlplan (Reiter <em>Sollbuchungen</em>) um diese Rate ergänzt. Der Status dieser Einzug steht auf belastet da er zu Bank weitergegeben würde. Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszug-Manager. Das System erkannt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt, wird der Status auf bezahlt und der Vorgang wird somit abgeschlossen.</p>

<p>In dem Zahlungsverkehr-Dialog können Sie Offene Posten berechnen über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442241462845.png" alt="" title=""> (siehe <em>Berechnungen → Offenen Posten</em>), oder Sie können die markierte Sollstellung löschen. </p></div></body>
</html>