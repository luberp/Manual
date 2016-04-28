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

<p>In der klassichen Menü-Ansicht kann das  <em>Zahlungsverkehr</em>-Dialog  über Menü<em>Berechnungen → Zahlungsverkehr</em> geöffnet werden. </p>

<p>In der modernen Menü-Ansicht wird die Funktion <em>Zahlungsverkehr</em> unter Registerkarte <em>Buchhaltung</em> Gruppe <em>Buchungsdaten</em> angezeigt.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461827801423.png" alt="" title=""></p>

<p>Hier können Sie direkt mit dem Berechnungsverlauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern.  </p>

<p>Starten Sie die Berechnung mit einem Klick auf <img src="http://xpecto.github.io/docs/img/img_1441715573070.png" alt="" title="">.  xpectoPro ermittelt nun alle fälligen Bankeinzüge zu diesem Datum und fasst diese zusammen. Es erscheint eine Liste mit Verträgen und den dazugehörigen Raten-Sollstellungen. Wählen Sie die abzurechnenden Verträge aus und erstellen Sie die gewünschte Ausgabedatei. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461830939718.png" alt="" title=""></p>

<p>Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1440771677497.png" alt="" title=""> werden die Daten auf Korrektheit verifiziert, und wenn die geprüfte Daten in Ordnung sind dann wird die <em>Dateien erzeugen</em> Schaltfläche aktiv. </p>

<p>Durch einen Doppelklick auf Details <img src="http://xpecto.github.io/docs/img/img_1440771513947.png" alt="" title="">, können Sie z.B. die Fehler der Datensätze sehen, falls welche vorhanden sind.</p>

<p>Die Sollstellung kann auch gelöscht werden durch Betätigung der Schaltfläche <em>Sollstellung löschen</em>.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461830868799.png" alt="" title=""></p>

<p>In dem <em>Zahlungsverkehr</em>-Dialog können Sie Offene Posten berechnen, über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442241462845.png" alt="" title=""> gelangen Sie in dem <em>xpectoPro OPOS Verarbeitung</em> Dialog  (siehe Hanbuch <em>Berechnungen → Offenen Posten</em>).  <br>
Aus einer OPOS Buchung wird ein Sollbuchungdatensatz erstellt und m oberen Bereich des Dialoges angezeigt. </p>

<p>Durch einen Klick auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1440771590046.png" alt="" title="">, werden die Sollbuchungen in Zahlungsdateien umgewandelt.  <br>
Die Sollbuchungen werden zu einer Transaktion zusammengefasst, und zugleich wird ein Datensatz für den Zahlungsverkehr erzeugt. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461831006328.png" alt="" title=""></p>

<p>Bei der Erzeugung der Zahlungsverkehrsdatei werden folgende Dateien (in dem unter Menü <em>Extras → Einstellungen → Bank</em> Pfad, angegebenen Ordner angelegt): eine CSV-Datei, PDF Datei und die SEPA-Datei (Dateiendung .xml). <br>
Die Dateien werden in einen Ordner gespeichert.  Mit einem Doppelklick auf das Ordnersymbol, können Sie ihn öffnen. Die Dateien können dann über die entsprechenden Banksysteme eingereicht werden. <br>
Bei den einzelnen Verträgen würde dann der Zahlplan (Reiter <em>Sollbuchungen</em>) um diese Rate ergänzt. Der Status dieses Einzugs steht auf belastet da er zu Bank weitergegeben wurde.  <br>
Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszugs-Manager. Das System erkennt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt, wird der Status auf bezahlt und der Vorgang ist somit abgeschlossen.</p></div></body>
</html>