*Zahlungsverkehr* ist ein zentrales Modul von xpectoPro, mit dem Sie Zahlungsaufträge wie Überweisungen, Lastschriften selbst erstellen und elektronisch an die Kreditinstitute übermitteln können. 
Bei der Erfassung eines Vertrages werden alle für den späteren Bankeinzug relevanten Daten eingetragen.  Im Vertrag werden die Ratenhöhe, die Laufzeit, das Datum der ersten Rate, die Bankverbindung, das Einzugsintervall und die Art des Einzugs erfasst. 
Aus diesen Daten berechnet das  Modul *Zahlungsverkehr* automatisch, für ratierliche Verträge die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten. 


----------


![](http://xpecto.github.io/docs/xpecto/Grafiken/gr_gluehbirne.jpg) Diese Daten können vorab über *Berechnungen → Probeberechnung → Sollstellungstest* in der klassischen Ansicht oder über *Zahlungsverkehr -> aktuellen Vertrag testen* in der modernen Ansicht getestet werden bevor diese zur regulären Berechnung herangezogen werden.

----------

Im Dialog *Zahlungsverkehr* stehen folgende Funktionalitäten zur Verfügung: *Lastschriften berechnen, aktuellen Vertrag testen, OPOS berechnen, Daten löschen, Daten prüfen, Zahlungsdatei erzeugen*.

In der klassichen Menü-Ansicht kann das  *Zahlungsverkehr*-Dialog  über Menü *Berechnungen → Zahlungsverkehr* geöffnet werden. 

In der modernen Menü-Ansicht wird die Funktion *Zahlungsverkehr* unter Registerkarte *Buchhaltung* Gruppe *Buchungsdaten* angezeigt.

![](http://xpecto.github.io/docs/xpecto/Berechnungen/Zahlungsverkehr/Zahlungsverkehr_Menue.png)

Hier können Sie direkt mit dem Berechnungslauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern.  

![](http://xpecto.github.io/docs/xpecto/Berechnungen/Zahlungsverkehr/Lastschrift_berechnen.png)

Starten Sie die Berechnung mit einem Klick auf ![](http://xpecto.github.io/docs/xpecto/Berechnungen/Zahlungsverkehr/Lastschrift_berechnen_Button.png) .xpectoPro ermittelt nun alle fälligen Bankeinzüge zu diesem Datum und fasst diese zusammen. Es erscheint eine Liste mit Verträgen und den dazugehörigen Raten-Sollstellungen. Wählen Sie die abzurechnenden Verträge aus und erstellen Sie die gewünschte Ausgabedatei. 


----------

![](http://xpecto.github.io/docs/xpecto/Grafiken/gr_gluehbirne.jpg) Bitte beachten Sie dass eine Ausgabedatei erst nach Prüfung der Datensätze erzeugt werden kann. Verwenden Sie hierzu die Funktion *Daten prüfen*.
Durch einen Doppelklick auf Details ![](http://xpecto.github.io/docs/xpecto/Berechnungen/Zahlungsverkehr/Details.png), können Sie z.B. die Fehler der Datensätze sehen, falls welche vorhanden sind.
Sollstellungen können falls notwendig über den Button *Daten löschen* gelöscht werden.

----------



![](http://xpecto.github.io/docs/xpecto/Berechnungen/Zahlungsverkehr/Zahlungsverkehr.png)

Im *Zahlungsverkehr*-Dialog können Sie offene Posten berechnen, über die Schaltfläche ![](http://xpecto.github.io/docs/xpecto/Berechnungen/Zahlungsverkehr/OPOS_berechnen.png) gelangen Sie in den *xpectoPro OPOS Verarbeitung* Dialog  (siehe Handbuch *Berechnungen → Offenen Posten*). 
Aus einer OPOS Buchung wird ein Sollbuchungdatensatz erstellt und im oberen Bereich des Dialoges angezeigt. 

Durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/xpecto/Berechnungen/Zahlungsverkehr/Zahlungsdatei_erzeugen_Button.png), werden die Sollbuchungen in Zahlungsdateien umgewandelt. 
Die Sollbuchungen werden zu einer Transaktion zusammengefasst, und zugleich wird ein Datensatz für den Zahlungsverkehr erzeugt. 

![](http://xpecto.github.io/docs/xpecto/Berechnungen/Zahlungsverkehr/Zahlungsverkehrsdatei.png)

Bei Erzeugung der Zahlungsverkehrsdatei werden folgende Dateien im Verzeichnis für Bankdaten angelegt:

 - Eine CSV-Datei mit folgendem Inhalt: Vertragsnummer, Produkt, Name u. Adresse des Anteileigners, Betrag,        Währung, Buchungstext sowie die Bankverbindung.
 - Ein Begleitzettel zur Transaktion.
 - Eine SEPA-Datei zur Übermittlung an das Kreditinstitut.

Bei den einzelnen Verträgen würde dann der Zahlplan (Reiter *Sollbuchungen*) um diese Rate ergänzt. Der Status dieses Einzugs steht auf belastet da er zu Bank weitergegeben wurde. 
Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszugs-Manager. Das System erkennt automatisch die einzelne Lastschriften des Einzugs und verbucht diese dem Kundenkonto. Ist dies erledigt, wird der Status auf bezahlt gesetzt und der Vorgang ist somit abgeschlossen.
