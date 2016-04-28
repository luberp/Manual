*Zahlungsverkehr* ist ein zentrales Modul von xpectoPro, mit dem Sie Zahlungsaufträge wie Überweisungen, Lastschriften selbst erstellen und elektronisch an die Kreditinstitute übermitteln können. 
Bei der Erfassung eines Vertrages werden alle für den späteren Bankeinzug relevanten Daten eingetragen.  Im Vertrag werden die Ratenhöhe, die Laufzeit, das Datum der ersten Rate, die Bankverbindung, das Einzugsinterval und die Art des Einzugs erfasst. 
Aus dieser Daten berechnet das  Modul *Zahlungsverkehr* für ratierliche Verträge, die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten. Diese Daten können getestet werden über *Berechnungen → Probeberechnung → Sollstellungstest*. 

In dem Dialog stehen folgende Funktionalitäten: *Lastschriften erzeugen, OPOS berechnen, Sollstellung löschen, Datenprüfung, Dateien erzeugen* zur Verfügung.

Über *Berechnungen → Zahlungsverkehr* kann das *Zahlungsverkehr*-Dialog geöffnet werden. Hier können Sie direkt mit dem Berechnungsverlauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern.  


![](http://xpecto.github.io/docs/img/img_1461827801423.png)


![](http://xpecto.github.io/docs/img/img_1441985519757.png)

Starten Sie die Berechnung mit einem Klick auf ![](http://xpecto.github.io/docs/img/img_1441715573070.png).  xpectoPro ermittelt nun alle fälligen Bankeinzüge zu diesem Datum und fasst diese zusammen. Es erscheint eine Liste mit Verträgen und den dazugehörigen Raten-Sollstellungen. Wählen Sie die abzurechnenden Verträge aus und erstellen Sie die gewünschte Ausgabedatei. 
Mit einem Klick auf ![](http://xpecto.github.io/docs/img/img_1441720924595.png) wird die Plausibilitätsprüfung der einzelnen Daten gestartet. 

![](http://xpecto.github.io/docs/img/img_1441717900163.png)

Klicken Sie auf *Ja* um die Zahlungsaufträge zusammenzufassen.  
Damit wird auf dem Konto des Kunden bei der Zusammenfassung nur 1 Buchungsposten (auf dessen Kontoauszug der Bank) angezeigt und in der Buchungstext können z. B. 5 Überweisungen zusammengehängt werden.

![](http://xpecto.github.io/docs/img/img_1441716256692.png)

Um die Details der einzelnen Sollstellungen anzeigen zu lassen klicken Sie auf ![](http://xpecto.github.io/docs/img/img_1441717792618.png). Hier sehen Sie aus welchen Zahlungsaufträgen die Sollstellung enthält und welche Daten fehlerhaft sind. Die Fehlerhaften Einträge werden automatisch markiert und der Haken entfernt.

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441718401250.png) werden die Zahlungsverkehrsdateien in PDF- und CSV-Format erzeugt. 

![](http://xpecto.github.io/docs/img/img_1440769740999.png)

Noch dazu werden die verschiedene Ausgabeformate: PDF, CSV und XML in einen Ordner gespeichert.  Mit einem Doppelklick auf das Ordnersymbol, können Sie ihn öffnen. Die Dateien können dann über die entsprechenden Banksysteme eingereicht werden.
Bei den einzelnen Verträgen würde dann der Zahlplan (Reiter *Sollbuchungen*) um diese Rate ergänzt. Der Status dieses Einzugs steht auf belastet da er zu Bank weitergegeben wurde. Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszugs-Manager. Das System erkannt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt, wird der Status auf bezahlt und der Vorgang ist somit abgeschlossen.

In dem *Zahlungsverkehr*-Dialog können Sie Offene Posten berechnen, über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442241462845.png) gelangen Sie in dem *xpectoPro OPOS Verarbeitung* Dialog  (siehe *Berechnungen → Offenen Posten*). 
Aus einer OPOS Buchung wird eine Sollbuchung erstellt. Es wird hier ein Sollbuchungsdatensatz erstellt. Im oberen Bereich sind die erstellten Sollbuchungen zu sehen. 