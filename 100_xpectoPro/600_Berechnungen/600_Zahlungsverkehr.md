*Zahlungsverkehr* ist ein zentrales Modul von xpectoPro, mit dem Sie Zahlungsaufträge wie Überweisungen, Lastschriften selbst erstellen und elektronisch an die Kreditinstitute übermitteln können. 
Bei der Erfassung eines Vertrages werden alle für den späteren Bankeinzug relevanten Daten eingetragen.  Im Vertrag werden die Ratenhöhe, die Laufzeit, das Datum der ersten Rate, die Bankverbindung, das Einzugsintervall und die Art des Einzugs erfasst. 
Aus diesen Daten berechnet das  Modul *Zahlungsverkehr* automatisch, für ratierliche Verträge die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten. 
![](http://xpecto.github.io/docs/xpecto/Grafiken/gr_gluehbirne.jpg) Diese Daten können getestet werden über *Berechnungen → Probeberechnung → Sollstellungstest* in der klassischen Ansicht und über *Zahlungsverkehr -> aktuellen Vertrag testen* in der modernen Ansicht.

In dem Dialog stehen folgende Funktionalitäten: *Lastschriften erzeugen, OPOS berechnen, Sollstellung löschen, Datenprüfung, Dateien erzeugen* zur Verfügung.

In der klassichen Menü-Ansicht kann das  *Zahlungsverkehr*-Dialog  über Menü *Berechnungen → Zahlungsverkehr* geöffnet werden. 

In der modernen Menü-Ansicht wird die Funktion *Zahlungsverkehr* unter Registerkarte *Buchhaltung* Gruppe *Buchungsdaten* angezeigt.

![](http://xpecto.github.io/docs/xpecto/Berechnungen/Zahlungsverkehr/Zahlungsverkehr_Menue.png)

Hier können Sie direkt mit dem Berechnungsverlauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern.  

Starten Sie die Berechnung mit einem Klick auf ![](http://xpecto.github.io/docs/img/img_1441715573070.png).  xpectoPro ermittelt nun alle fälligen Bankeinzüge zu diesem Datum und fasst diese zusammen. Es erscheint eine Liste mit Verträgen und den dazugehörigen Raten-Sollstellungen. Wählen Sie die abzurechnenden Verträge aus und erstellen Sie die gewünschte Ausgabedatei. 

![](http://xpecto.github.io/docs/img/img_1461830939718.png)

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440771677497.png) werden die Daten auf Korrektheit verifiziert, und wenn die geprüfte Daten in Ordnung sind dann wird die *Dateien erzeugen* Schaltfläche aktiv. 


Durch einen Doppelklick auf Details ![](http://xpecto.github.io/docs/img/img_1440771513947.png), können Sie z.B. die Fehler der Datensätze sehen, falls welche vorhanden sind.

Die Sollstellung kann auch gelöscht werden durch Betätigung der Schaltfläche *Sollstellung löschen*.

![](http://xpecto.github.io/docs/img/img_1461830868799.png)

In dem *Zahlungsverkehr*-Dialog können Sie Offene Posten berechnen, über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442241462845.png) gelangen Sie in dem *xpectoPro OPOS Verarbeitung* Dialog  (siehe Hanbuch *Berechnungen → Offenen Posten*). 
Aus einer OPOS Buchung wird ein Sollbuchungdatensatz erstellt und im oberen Bereich des Dialoges angezeigt. 

Durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440771590046.png), werden die Sollbuchungen in Zahlungsdateien umgewandelt. 
Die Sollbuchungen werden zu einer Transaktion zusammengefasst, und zugleich wird ein Datensatz für den Zahlungsverkehr erzeugt. 

![](http://xpecto.github.io/docs/img/img_1461831006328.png)

Bei der Erzeugung der Zahlungsverkehrsdatei werden folgende Dateien (in dem unter Menü *Extras → Einstellungen → Bank* Pfad, angegebenen Ordner angelegt): eine CSV-Datei, PDF Datei und die SEPA-Datei (Dateiendung .xml).
Die Dateien werden in einen Ordner gespeichert.  Mit einem Doppelklick auf das Ordnersymbol, können Sie ihn öffnen. Die Dateien können dann über die entsprechenden Banksysteme eingereicht werden.
Bei den einzelnen Verträgen würde dann der Zahlplan (Reiter *Sollbuchungen*) um diese Rate ergänzt. Der Status dieses Einzugs steht auf belastet da er zu Bank weitergegeben wurde. 
Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszugs-Manager. Das System erkennt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt, wird der Status auf bezahlt und der Vorgang ist somit abgeschlossen.
