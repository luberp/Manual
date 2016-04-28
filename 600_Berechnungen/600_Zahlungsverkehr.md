<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>600_Zahlungsverkehr.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p><em>Zahlungsverkehr</em> ist ein zentrales Modul von xpectoPro, mit dem Sie Zahlungsaufträge wie Überweisungen, Lastschriften selbst erstellen und elektronisch an die Kreditinstitute übermitteln können.  <br>
Bei der Erfassung eines Vertrages werden alle für den späteren Bankeinzug relevanten Daten eingetragen.  Im Vertrag werden die Ratenhöhe, die Laufzeit, das Datum der ersten Rate, die Bankverbindung, das Einzugsinterval und die Art des Einzugs erfasst.  <br>
Aus dieser Daten berechnet das  Modul <em>Zahlungsverkehr</em> für ratierliche Verträge, die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten. Diese Daten können getestet werden über <em>Berechnungen → Probeberechnung → Sollstellungstest</em>. </p>

<p>In dem Dialog stehen folgende Funktionalitäten: <em>Lastschriften erzeugen, OPOS berechnen, Sollstellung löschen, Datenprüfung, Dateien erzeugen</em> zur Verfügung.</p>

<p>Über <em>Berechnungen → Zahlungsverkehr</em> kann das <em>Zahlungsverkehr</em>-Dialog geöffnet werden. Hier können Sie direkt mit dem Berechnungsverlauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern.  </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461827801423.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1441985519757.png" alt="" title=""></p>

<p>Starten Sie die Berechnung mit einem Klick auf <img src="http://xpecto.github.io/docs/img/img_1441715573070.png" alt="" title="">.  xpectoPro ermittelt nun alle fälligen Bankeinzüge zu diesem Datum und fasst diese zusammen. Es erscheint eine Liste mit Verträgen und den dazugehörigen Raten-Sollstellungen. Wählen Sie die abzurechnenden Verträge aus und erstellen Sie die gewünschte Ausgabedatei.  <br>
Mit einem Klick auf <img src="http://xpecto.github.io/docs/img/img_1441720924595.png" alt="" title=""> wird die Plausibilitätsprüfung der einzelnen Daten gestartet. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1441717900163.png" alt="" title=""></p>

<p>Klicken Sie auf <em>Ja</em> um die Zahlungsaufträge zusammenzufassen. <br>
Damit wird auf dem Konto des Kunden bei der Zusammenfassung nur 1 Buchungsposten (auf dessen Kontoauszug der Bank) angezeigt und in der Buchungstext können z. B. 5 Überweisungen zusammengehängt werden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1441716256692.png" alt="" title=""></p>

<p>Um die Details der einzelnen Sollstellungen anzeigen zu lassen klicken Sie auf <img src="http://xpecto.github.io/docs/img/img_1441717792618.png" alt="" title="">. Hier sehen Sie aus welchen Zahlungsaufträgen die Sollstellung enthält und welche Daten fehlerhaft sind. Die Fehlerhaften Einträge werden automatisch markiert und der Haken entfernt.</p>

<p>Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1441718401250.png" alt="" title=""> werden die Zahlungsverkehrsdateien in PDF- und CSV-Format erzeugt. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1440769740999.png" alt="" title=""></p>

<p>Noch dazu werden die verschiedene Ausgabeformate: PDF, CSV und XML in einen Ordner gespeichert.  Mit einem Doppelklick auf das Ordnersymbol, können Sie ihn öffnen. Die Dateien können dann über die entsprechenden Banksysteme eingereicht werden. <br>
Bei den einzelnen Verträgen würde dann der Zahlplan (Reiter <em>Sollbuchungen</em>) um diese Rate ergänzt. Der Status dieses Einzugs steht auf belastet da er zu Bank weitergegeben wurde. Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszugs-Manager. Das System erkannt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt, wird der Status auf bezahlt und der Vorgang ist somit abgeschlossen.</p>

<p>In dem <em>Zahlungsverkehr</em>-Dialog können Sie Offene Posten berechnen, über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442241462845.png" alt="" title=""> gelangen Sie in dem <em>xpectoPro OPOS Verarbeitung</em> Dialog  (siehe <em>Berechnungen → Offenen Posten</em>).  <br>
Aus einer OPOS Buchung wird eine Sollbuchung erstellt. Es wird hier ein Sollbuchungsdatensatz erstellt. Im oberen Bereich sind die erstellten Sollbuchungen zu sehen. </p></div></body>
</html>