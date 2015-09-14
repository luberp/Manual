Das Modul *Zahlungsverkehr* berechnet für ratierliche Verträge die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten. Über *Berechnungen → Zahlungsverkehr* soll das *Zahlungsverkehr*-Maske geöffnet werden. Hier können Sie direkt mit dem Berechnungsverlauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern.  

![](http://xpecto.github.io/docs/img/img_1441985519757.png)

Starten Sie die Berechnung mit einem Klick auf ![](http://xpecto.github.io/docs/img/img_1441715573070.png).  xpectoPro ermittelt nun alle fällige Bankeinzüge zu diesem Datum und fasst diese zusammen. Es erscheint eine Liste mit Verträgen und den dazugehörigen Raten-Sollstellungen. Wählen Sie die abzurechnenden Verträge aus und erstellen Sie die gewünschte Ausgabedatei. 

Mit einem Klick auf ![](http://xpecto.github.io/docs/img/img_1441720924595.png) wird die Plausibilitätsprüfung der einzelne Daten gestartet. 

![](http://xpecto.github.io/docs/img/img_1441717900163.png)

Klicken Sie auf *Ja* um die Zahlungsaufträge zusammenzufassen. 

![](http://xpecto.github.io/docs/img/img_1441716256692.png)

Um die Details der einzelne Sollstellungen anzeigen zu lassen klicken Sie auf ![](http://xpecto.github.io/docs/img/img_1441717792618.png). Hier sehen Sie welche Daten fehlerhaft sind, diese werden automatisch markiert. 

Bei der Erfassung eines Vertrages werden alle für den späteren Bankeinzug relevanten Daten  eingetragen. Im Vertrag erfassen Sie die Ratenhöhe, die Laufzeit, das Datum der erste Rate, die Bankverbindung, das Einzugsinterval und die Art des Einzugs.

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441718401250.png) werden die Zahlungsverkehrsdateien  in PDF- und CSV - Format erzeugt. 

![](http://xpecto.github.io/docs/img/img_1440769740999.png)

Noch dazu werden die verschiedene Ausgabeformate: PDF, CSV und XML in einen Ordner gespeichert. Die Dateien können dann über die entsprechende Banksysteme eingereicht werden.
Bei der einzelne Verträge würde dann der Zahlplan (Reiter *Sollbuchungen*) um diese Rate ergänzt. Der Status dieser Einzug steht auf belastet da er zu Bank weitergegeben würde. Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszug-Manager. Das System erkannt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt, wird der Status auf bezahlt und der Vorgang wird somit abgeschlossen.

In dem Zahlungsverkehr-Dialog können Sie Offene Posten berechnen über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442241462845.png) (siehe *Berechnungen → Offenen Posten*), oder Sie können die markierte Sollstellung löschen. 