Das Modul Zahlungsverkehr berechnet für ratierliche Verträge die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten. Über *Berechnungen → Zahlungsverkehr* soll das *Zahlungsverkehr*-Maske geöffnet werden. Hier können Sie direkt mit dem Berechnungsverlauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern. 
xpectoPro ermittelt nun alle fällige Bankeinzüge zu diesem Datum.  
Starten Sie die Berechnung mit einem Klick auf ![](http://xpecto.github.io/docs/img/img_1441715573070.png). Es erscheint eine Liste mit Verträgen und den dazugehörigen Raten-Sollstellungen. Wählen Sie die abzurechnenden Verträge aus und erstellen Sie die gewünschte Ausgabedatei. 

![](http://xpecto.github.io/docs/img/img_1441985519757.png)

Wenn auf Datenprüfung klicken:

![](http://xpecto.github.io/docs/img/img_1441717900163.png)

Klicken Sie auf Ja um die Zahlungsaufträge zusammenzufassen. 
Um die Details der einzelne Einzüge anzeigen zu lassen klicken Sie auf ![](http://xpecto.github.io/docs/img/img_1441717792618.png). Hier sehen Sie welche Daten fehlerhaft sind, diese werden automatisch markiert. 

Als Ausgabeformate stehen DTAUS (Standardformat deutscher Banken für den Zahlungsverkehr) oder EDIFACT (internationales Standardformat für den Zahlungsverkehr) zur Auswahl.

![](http://xpecto.github.io/docs/img/img_1441716256692.png)

Sollstellungslauf dient zur Durchführung von Lastschriften bei ratierlichen Wert.
Bei der Erfassung eines Vertrages werden alle für den späteren Bankeinzug relevanten Daten  eingetragen. Im Vertrag erfassen Sie die Ratenhöhe, die Laufzeit, das Datum der erste Rate, die Bankverbindung, das Einzugsinterval und die Art des Einzugs.

Sie können hier direkt mit dem Berechnungslauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern. xpectoPro ermittelt nun alle fälligen Bankeinzüge zu diesem Datum und fasst diese nach verschiedene Kriterien zu eine Datei zusammen. Mit einem Klick auf ![](http://xpecto.github.io/docs/img/img_1441720924595.png) wird die Plausibilitätsprüfung der einzelne Daten gestartet. 

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441718401250.png) werden die Zahlungsverkehrsdateien erzeugt. Zusätzlich wird ein übersichtlicher Begleitzettel für jede Datei erstellt. Das System kann Lastschriften in verschiedene Formate ausgeben: PDF, CSV und XML. Die Dateien können dann über die entsprechende Banksysteme eingereicht werden.
Bei der einzelne Verträge würde dann der Zahlplan (Reiter *Sollbuchungen*) um diese Rate ergänzt. Der Status dieser Einzug steht auf belastet da er zu Bank weitergegeben würde. Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszug-Manager. Das System erkannt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt, wird der Status auf bezahlt und der Vorgang wird somit abgeschlossen.

Zusätzlich wird ein übersichtlicher Begleitzettel für jede Datei erstellt. Das System kann Lastschriften in vier verschiedene Formate ausgeben: DTA, DTAUS, EDIFACT, SEPA für europäischen Kunden und CSV für alle andere. Die Dateien können jetzt über die entsprechende Banksysteme eingereicht werden. Bei der einzelne Verträge würde der Zahlplan (Sollbuchungen) um diese Rate ergänzt. Der Status dieser Einzug steht auf belastet da er zu Bank weitergegeben würde. Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszug-Manager. Das System erkennt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt springt der Status auf bezahlt und der Vorgang wird somit abgeschlossen. 

![](http://xpecto.github.io/docs/img/img_1440769740999.png)