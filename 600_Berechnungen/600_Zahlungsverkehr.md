<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>600_Zahlungsverkehr.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Das Modul Zahlungsverkehr berechnet für ratierliche Verträge die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten.</p>

<p>Über Berechnungen Zahlungsverkehr soll das Zahlungsverkehr-Maske geöffnet werden. Hier können Sie direkt mit dem Berechnungsverlauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern.  <br>
xpectoPro ermittelt nun alle fällige Bankeinzüge zu diesem Datum und fasst diese zusammen.  <br>
Mit einem Klick auf Datenprüfung wird die Plausibilität der einzelne Daten gestartet. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1441717900163.png" alt="" title=""></p>

<p>Um die Details der einzelne Einzüge anzeigen zu lassen klicken Sie auf <img src="http://xpecto.github.io/docs/img/img_1441717792618.png" alt="" title="">. Hier können Sie sehen welche Daten fehlerhaft sind. </p>

<p>Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1441718401250.png" alt="" title=""> werden die Zahlungsverkehrsdateien erzeugt. Zusätzlich wird ein übersichtlicher Begleitzettel für jede Datei erstellt. Das System kann Lastschriften in verschiedene Formate ausgeben: PDF, CSV und XML. Die Dateien können dann über die entsprechende Banksysteme eingereicht werden. <br>
Bei der einzelne Verträge würde dann der Zahlplan (Reiter <em>Sollbuchungen</em>) um diese Rate ergänzt. Der Status dieser Einzug steht auf belastet da er zu Bank weitergegeben würde. Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszug-Manager. Das System erkannt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt, wird der Status auf bezahlt und der Vorgang wird somit abgeschlossen.</p>

<p>Wählen Sie für das abzurechnende Produkt den Stichtag. (fällige Raten bis zum Stichtag werden in der Berechnung berücksichtigt). </p>

<p>Starten Sie die Berechnung mit einem Klick auf <img src="http://xpecto.github.io/docs/img/img_1441715573070.png" alt="" title="">. Es erscheint eine Liste mit Verträgen und den dazugehörigen Raten-Sollstellungen. Wählen Sie die abzurechnenden Verträge aus und erstellen Sie die gewünschte Ausgabedatei.  <br>
Als Ausgabeformate stehen DTAUS (Standardformat deutscher Banken für den Zahlungsverkehr) oder EDIFACT (internationales Standardformat für den Zahlungsverkehr) zur Auswahl.</p>

<p>Nach Auswahl eines entsprechenden Berichts kann über den Button “Abrechnung drucken” eine Abrechnungs-Liste zu dem erstellten Sollbuchungslauf ausgegeben werden.</p>

<p>Das Modul Sollstellung berechnet für ratierliche Verträge die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten. <br>
Wählen Sie das abzurechnende Produkt und den Stichtag. (fällige Raten bis zum Stichtag werden in der Berechnung berücksichtigt). Fahren Sie fort mit weiter. Starten Sie die Berechnung der Sollstellung mit einem klick auf <em>Sollstellung berechnen</em>. Es erscheint eine Liste mit Verträge und den dazugehörigen Raten-Sollstellungen.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1441716256692.png" alt="" title=""></p>

<p>Sollstellung berechnen:</p>

<p>Datenprüfung: Die Daten werden auf Fehler geprüft.  Danach können falls gewünscht Dateien erzeugt werden und zwar eine PDF Datei (ein Begleitzettel) und eine xml-Datei, Details anzeigen oder Datei an Bank übermitteln.</p>

<p>Sollstellungslauf dient zur Durchführung von Lastschriften bei ratierlichen Wert. <br>
Bei der Erfassung eines Vertrages werden alle für den späteren Bankeinzug relevanten Daten  eingetragen. Im Vertrag erfassen Sie die Ratenhöhe, die Laufzeit, das Datum der erste Rate, die Bankverbindung, das Einzugsinterval und die Art des Einzugs.</p>

<p>Über Berechnungen  Sollstellung soll das Sollstellungsfenster geöffnet. Sie können hier direkt mit dem Berechnungslauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern. <br>
xpectoPro ermittelt nun alle fälligen Bankeinzüge zu diesem Datum und fasst diese nach verschiedene Kriterien zu eine Datei zusammen. Mit einem Klick auf „Datenprüfung” wird die Plausibilitätsprüfung der einzelne Daten gestartet. Falls Sie wünschen können Sie sich die Details der einzelne Einzüge anzeigen durch einen Klick auf „Details anzeigen”. Hier sehen Sie welche Daten fehlerhaft sind, diese werden automatisch rot markiert. Das System enthält ein komplexes Regelwerk, welches automatisch viele Problemfälle im Vorfeld erkennt. Existiert die BLZ, passt die Kontonummer zum Schema der zugehörigen Bank. Mit Dateien erzeugen werden die Zahlungsverkehrsdateien erzeugt. Zusätzlich wird ein übersichtlicher Begleitzettel für jede Datei erstellt. Das System kann Lastschriften in vier verschiedene Formate ausgeben: DTA, DTAUS, EDIFACT, SEPA für europäischen Kunden und CSV für alle andere. Die Dateien können jetzt über die entsprechende Banksysteme eingereicht werden. Bei der einzelne Verträge würde der Zahlplan (Sollbuchungen) um diese Rate ergänzt. Der Status dieser Einzug steht auf belastet da er zu Bank weitergegeben würde. Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszug-Manager. Das System erkennt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt springt der Status auf bezahlt und der Vorgang wird somit abgeschlossen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1440769740999.png" alt="" title=""></p></div></body>
</html>