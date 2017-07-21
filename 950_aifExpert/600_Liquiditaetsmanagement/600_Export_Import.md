
#### Excel Export

aifExpert erlaubt den Export des Plans in das xlsx-Format. Dabei muss die Schaltfläche "Export" im Reiter "Aktionen" im Menü betätigt werden. Anschließend exportiert aifExpert den Plan genau so, wie er im Eingabe-Reiter zu sehen ist (d.h. mit dem entsprechenden Zeitraum und Intervall), in das xlsx-Format und öffnet die Datei in einem Tabellenkalkulationsprogramm. Die Datei selbst wird im Export-Pfad des aifExpert (einsehbar im Menü-Reiter "System" > Schaltfläche "Einstellungen“) gespeichert. 
Bitte beachten:
- Die Export-Funktion zeigt eine Fehlermeldung an, wenn noch ein Fenster des Tabellenkalkulationsprogramms geöffnet ist

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet22.png)

#### Excel Import

Neben dem Export des Plans im xlsx-Format kann aifExpert den jeweiligen Plan mit seinen Werten wieder zurück importieren. Bei Betätigung der Schaltfläche "Import" im Menü-Reiter "Aktionen" öffnet sich der Dialog zur Auswahl der zu importierenden Datei. Dabei öffnet der Dialog standardmäßig den Pfad, der auch beim Export verwendet wird. Nach Auswahl der zu importierenden Datei prüft aifExpert auf Übereinstimmung der Werte und fragt anschließend in einem Dialog, ob die Formeln neu berechnet werden sollen oder der Import ohne Neuberechnung durchgeführt werden soll.

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet23.png)

Bitte beachten: 
- Der Import unterstützt keine Anpassungen des Aufbaus (z.B. die Anlage von zusätzlichen Posten etc.) sondern nur die Anpassung oder Anlage von Werten innerhalb der Zeitraum-Anlass-Spalten
- Die Veränderung von Daten, die zum Aufbau gehören, wie Bezeichnung, Einheit etc. kann zu Fehlermeldungen führen.
- Die Löschung der ID des Postens in der zu importierenden xlsx-Datei führt zu keiner Aktualisierung des Datenpunktes
- Es muss die richtige Datei / Plan ausgewählt werden (Überprüfbar ist dies anhand der ID des Liquiditätsplans und des Dateinamens)
- Der Import von Werten auf einen Posten mit dem Parameter "readonly" ist nicht möglich
- Der Import von Werten auf einen Posten, welcher mit Formeln berechnet wird, ist nicht möglich
- Der Import von Werten auf einen Datenpunkt, welcher komplett festgeschrieben ist, erzeugt eine Korrekturbuchung

#### Generischer Import

Für einen Schnellimport der nicht auf dem exportierten Excel-Plan beruht wurde ein generischer Import implementiert.
Die Datei muss dabei als Datenformat eine Excel-Datei mit den Spalten
- Konto
- Wert
- Datum 

sein.

Durch die Betätigung der Schaltfläche "Excel Import" und Auswahl der generischen Import-Datei übernimmt legt der aifExpert entsprechend des Kontos des PlanPostens entsprechende Buchungssätze mit dem Wert und Datum der Import-Datei an. Die Zuordnung des Plans sowie Variante erfolgt automatisiert und ist von der vorherigen Auswahl abhängig. D.h. wenn der generische Import genutzt werden soll, muss der entsprechende Plan sowie die Variante, in die Import werden soll, im Eingabe-Reiter ausgewählt werden.

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet44.png)

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet45.png)

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet46.png)


#### Tipp zur Vorgehensweise

Für einen ordentlichen und schnellen Export und Import in und aus das xlsx-Format empfiehlt es sich den Plan zu exportieren und in der bereits geöffneten Datei weiter zu arbeiten. Hier sollten nur die Zellen ab Spalte "Sortierung" und ab der zweiten Zeile bearbeitet werden. Anschließend sollte die Datei in dem Tabellenkalkulationsprogramm einfach nur gespeichert werden > dann zum aifExpert wechseln und dort den Import starten. Sollten nun Anpassungen von nöten sein, kann der bereits offene Plan im Tabellenkalkulationsprogramm nochmal angepasst, gespeichert und im aifExpert der Import nochmal gestartet werden.

