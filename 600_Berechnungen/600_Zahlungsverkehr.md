Das Modul Zahlungsverkehr berechnet für ratierliche Verträge die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten.

Es erscheint eine Liste mit Verträgen und den dazugehörigen Raten-Sollstellungen. Markieren Sie die abzurechnenden Verträge (Häkchen setzen) und erstellen Sie die gewünschte Ausgabedatei. Als Ausgabeformate stehen DTAUS (Standardformat deutscher Banken für den Zahlungsverkehr)
oder EDIFACT (internationales Standardformat für den Zahlungsverkehr) zur Auswahl.

Nach Auswahl eines entsprechenden Berichts kann über den Button "Abrechnung drucken" eine Abrechnungs-Liste zu dem erstellten Sollbuchungslauf ausgegeben werden.

Das Modul Sollstellung berechnet für ratierliche Verträge die notwendigen Datensätze für den Lastschrift-Einzug der monatlichen Raten.
Wählen Sie das abzurechnende Produkt und den Stichtag. (fällige Raten bis zum Stichtag werden in der Berechnung berücksichtigt). Fahren Sie fort mit weiter. Starten Sie die Berechnung der Sollstellung mit einem klick auf *Sollstellung berechnen*. Es erscheint eine Liste mit Verträge und den dazugehörigen Raten-Sollstellungen.

Sollstellung berechnen:

![](http://xpecto.github.io/docs/img/img_1423577411603.png)

Datenprüfung: Die Daten werden auf Fehler geprüft.  Danach können falls gewünscht Dateien erzeugt werden und zwar ein Begleitzettel und eine xml-Datei, Details anzeigen oder Datei an Bank übermitteln.

Sollstellungslauf dient zur Durchführung von Lastschriften bei ratierlichen Wert.
Bei der Erfassung eines Vertrages werden alle für den späteren Bankeinzug relevanten Daten  eingetragen. Im Vertrag erfassen Sie die Ratenhöhe, die Laufzeit, das Datum der erste Rate, die Bankverbindung, das Einzugsinterval und die Art des Einzugs.

Über Berechnungen  Sollstellung soll das Sollstellungsfenster geöffnet. Sie können hier direkt mit dem Berechnungslauf beginnen, oder durch bereits erfolgte frühere Stichtage blättern.
xpectoPro ermittelt nun alle fälligen Bankeinzüge zu diesem Datum und fasst diese nach verschiedene Kriterien zu eine Datei zusammen. Mit einem Klick auf „Datenprüfung" wird die Plausibilitätsprüfung der einzelne Daten gestartet. Falls Sie wünschen können Sie sich die Details der einzelne Einzüge anzeigen durch einen Klick auf „Details anzeigen". Hier sehen Sie welche Daten fehlerhaft sind, diese werden automatisch rot markiert. Das System enthält ein komplexes Regelwerk, welches automatisch viele Problemfälle im Vorfeld erkennt. Existiert die BLZ, passt die Kontonummer zum Schema der zugehörigen Bank. Mit Dateien erzeugen werden die Zahlungsverkehrsdateien erzeugt. Zusätzlich wird ein übersichtlicher Begleitzettel für jede Datei erstellt. Das System kann Lastschriften in vier verschiedene Formate ausgeben: DTA, DTAUS, EDIFACT, SEPA für europäischen Kunden und CSV für alle andere. Die Dateien können jetzt über die entsprechende Banksysteme eingereicht werden. Bei der einzelne Verträge würde der Zahlplan (Sollbuchungen) um diese Rate ergänzt. Der Status dieser Einzug steht auf belastet da er zu Bank weitergegeben würde. Die Verbuchung erfolgt erst nach dem Einlesen der Kontoauszüge über unseren Kontoauszug-Manager. Das System erkennt dann automatisch die einzelne Lastschriften des Einzugs und verbucht diese auf dem Kundenkonto. Ist dies erledigt springt der Status auf bezahlt und der Vorgang wird somit abgeschlossen. 
