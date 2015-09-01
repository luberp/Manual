Eine der zentralen Funktionen von xpectoPro ist die Provisionsberechnung. 
Sie können tägliche, wöchentliche, halbmonatliche, monatliche, quartalsweise, halbjährige und jährliche Intervalle hinterlegen. Das geschieht in dem Dialog *Zeitraum wählen* (siehe *Berechnungen → Abrechnungszeitraum festlegen*).
Der für die Provisionsabrechnung verwendete Abrechnungszeitraum beinhaltet alle manuell eingetragenen Vermittler-Buchungen im Zeitraum und alle im angegebenen Zeitraum fälligen Provisionszahlungen. 

Um die Provisionsberechnung zu starten klicken Sie im Menü *Bearbeiten* auf *Provisionsberechnung*. 
In der Maske *Berechnungsverlauf starten* können Sie in der Dropdownliste auswählen, wie  die Berechnung durchgeführt wird.

|  Berechnung           |    Beschreibung     |  
| ------------- |:-------------| 
| 1 Alle Provisionen      | es werden alle Vertrags- und Vermittlerstruktur Provisionen berechnet.| 
| 2 Vertrags-Provisionen    | es wird für die vorhandene Verträge die Provisionen berechnet, mit den vorhandene Provisionen verglichen, und falls gewünscht verbucht.| 
| 3 restliche Provisionen    | es werden die Provisionen für die Vermittler-Struktur berechnet. | 

![](http://xpecto.github.io/docs/img/img_1440767716626.png)

Soll eine Provisionsabrechnung für ein bestimmtes Produkt oder einen bestimmten Vermittler usw. erstellt werden, dann wählen Sie die Checkbox *Einschränkungen der Berechnung* an. 
Nachdem Sie die gewünschten Einschränkungen ausgewählt haben, klicken Sie auf *Start*.
Es öffnet sich ein Dialog, wo abgefragt wird, ob die fehlenden Provisionen in die Verträge eingefügt werden sollten. 

![](http://xpecto.github.io/docs/img/img_1432632082918.png) 

Wenn Sie hier auf *Ja* klicken werden die fehlende Provisionen automatisch in die Verträge eingefügt und gespeichert, dann werden Sie zu dem *Berechnungslauf anzeigen und verbuchen* weitergeleitet.  Klicken Sie auf  *Nein*, um direkt in dem weiteren Schritt *Berechnungslauf anzeigen und verbuchen* zu gelangen.  

![](http://xpecto.github.io/docs/img/img_1440748523514.png)

Sie haben hier die Möglichkeit die berechnete Datensätze zu filtern. Der Filter dient zum markieren von Provisionsauszahlungen die verbucht werden sollen. 

![](http://xpecto.github.io/docs/img/img_1440747927011.png)

|  Checkbox           |    Beschreibung     |  
| ------------- |:-------------| 
|   ![](http://xpecto.github.io/docs/img/img_1440753874370.png)  | Alle Provisionen auswählen| 
| ![](http://xpecto.github.io/docs/img/img_1440753891145.png)    | Alle Provisionen über der nebenstehenden Schwelle auswählen| 
|![](http://xpecto.github.io/docs/img/img_1440753923716.png)|Nur Provisionsauszahlungen über die Schwelle werden abgerechnet|
|![](http://xpecto.github.io/docs/img/img_1440753950213.png)|Entfernt die getroffene Auswahl|
|![](http://xpecto.github.io/docs/img/img_1440753976766.png)|Berechnugslauf verwerfen. Es kann eine neue Berechnung gestartet werden.|

Nun markieren Sie die Provisionszahlungen die bei der Berechnung berücksichtigt werden sollen, und klicken Sie auf die Schaltfläche:  ![](http://xpecto.github.io/docs/img/img_1432632280997.png). 

![](http://xpecto.github.io/docs/img/img_1440748563962.png)

Mit dieser Funktion verbuchen Sie die ausgewählten Provisionen. Diese verbuchte Werte werden dann bei Vertrag in der Provisionsliste angezeigt. 

![](http://xpecto.github.io/docs/img/img_1432632479268.png)

Wenn Sie hier auf *Weiter zu Belegdruck und Auszahlung* klicken, werden Sie zur Maske *Belegdruck und Auszahlung* weitergeleitet. Hier wird eine Auflistung der verbuchte Provisionen für den ausgewählten Zeitintervall angezeigt..

![](http://xpecto.github.io/docs/img/img_1440748640999.png)

Um eine bestehende Buchung in der Abrechnung zu ändern, klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441095989354.png).  Sie können eine neue Buchung wie z.B. einen Vorschuss, einfügen durch betätigen der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441100101421.png).
Falls Sie eine Abrechnung geändert haben, dann klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441108231660.png), um die Liste der Abrechnungen zu aktualisieren.

Um die erstellten Auszahlungen als SEPA-Datei auszugeben, klicken Sie auf
![](http://xpecto.github.io/docs/img/img_1440751324468.png). 

In der Maske *Zahlungdatei erstellen* kann zwischen mehrere Verfahren zur Durchführung von Überweisungen ausgewählt werden. Sie können die Ausführungsoptionen und den Speicherort festlegen und ob ein Begleitzettel erstellt werden soll.

![](http://xpecto.github.io/docs/img/img_1440748885165.png)

Wählen Sie hier *SEPA* um eine SEPA-Datei zu erstellen. Es wird automatisch überprüft ob die Datei erstellt werden kann. Klicken Sie auf Speichern um die Datei zu erstellen. Es wird hier ein Zahlungsverkehr - Begleitzettel erstellt und gespeichert. 

Nun kehren Sie  zur Maske *Belegdruck und Auszahlungen*  zurück.

Die komplette Abrechnung für einen Abrechnungszeitraum kann mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440751219341.png) wieder gelöscht werden.

Soll die Provisionsabrechnung gedruckt oder per E-Mail zugestellt werden klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440751272141.png), so wählen Sie den zugehörigen Bericht (Häufig *Provisionsabrechnung*) und den gewünschten Drucker bzw. das gewünschte Ausgabeformat. 

Sie können einen *Testdruck*, um für jeden  Vermittler  eine Provisionsabrechnung erzeugen ohne Belegnummer, oder *Belegdruck*, um Abrechnungsbelege unter automatischer Vergabe lückenloser und fortlaufender Belegnummern zu erstellen. 

 ![](http://xpecto.github.io/docs/img/img_1440748756680.png)
 
Um die Belege zu löschen klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441103301118.png). Es werden alle Belege für die markierte Datensätze gelöscht.
