Eine der zentralen Funktionen von xpectoPro ist die Provisionsberechnung. 
Sie können tägliche, wöchentliche, halbmonatliche, monatliche, quartalsweise, halbjährige und jährliche Intervalle hinterlegen. Das geschieht in dem Dialog *Zeitraum wählen* (siehe Handbuch *Berechnungen → Abrechnungszeitraum festlegen*). Der Zeitraum kann auch direkt in dem Fenster *Berechnungsverlauf starten* geändert werden.
Der für die Provisionsabrechnung verwendete Abrechnungszeitraum beinhaltet alle manuell eingetragenen Vermittler-Buchungen im Zeitraum und alle im angegebenen Zeitraum fälligen Provisionszahlungen. 

In der klassischen Menü-Ansicht kann die Provisionsberechnung gestartet werden über *Berechnungen → Provisionsberechnung*.

In der modernen Menü-Ansicht wird die Provisionsberechnung über die Registerkarte *Vertrieb* Gruppe *Provisionen* gestartet.

![](http://xpecto.github.io/docs/img/img_1461751530160.png)

In der Maske *Berechnungsverlauf starten* können Sie in der Dropdownliste auswählen für welche Provisionen die Berechnung durchgeführt wird.

![](http://xpecto.github.io/docs/img/img_1461751780442.png)


|  Berechnung           |    Beschreibung     |  
| ------------- |:-------------| 
| 1 Alle Provisionen      | es werden alle Vertrags- und Vermittler Provisionen berechnet.| 
| 2 Vertrags-Provisionen    | es werden die Provisionen für alle vorhandenen Verträge berechnet, mit den vorhandenen Provisionen verglichen und falls gewünscht verbucht.| 
| 3 restliche Provisionen    | es werden die Provisionen der Vermittler-Struktur berechnet. | 

Soll eine Provisionsabrechnung für ein bestimmtes Produkt oder einen bestimmten Vermittler usw. erstellt werden, dann wählen Sie die Checkbox *Einschränkungen der Berechnung* . 
Nachdem Sie die gewünschten Einschränkungen gesetzt haben, klicken Sie auf *Start*.
Es öffnet sich ein Dialog, der abfrägt ob fehlenden Provisionen in die Verträge eingefügt werden sollen. 

![](http://xpecto.github.io/docs/img/img_1432632082918.png) 

Mit *Ja* werden für alle vorhandenen Verträge die entsprechenden Provisionsansprüche erzeugt. Verträge für die bereits Provisionsansprüche erzeugt wurden sind hiervon ausgenommen.

![](http://xpecto.github.io/docs/xpecto/Grafiken/gr_gluehbirne.jpg)*Diese Funktion ist sinnvoll für den Fall, dass Sie beim erfassen von Vertragsdaten keine Provisionsansprüche erzeugt haben.*

![](http://xpecto.github.io/docs/img/img_1461756428644.png)

In der Maske *Berechnungslauf anzeigen und verbuchen* gibt die Möglichkeit die berechnete Datensätze zu filtern. Der Filter dient  dazu, um Provisionsauszahlungen die verbucht werden sollen zu markieren. 

![](http://xpecto.github.io/docs/img/img_1440747927011.png)

|  Checkbox           |    Beschreibung     |  
| ------------- |:-------------| 
|   ![](http://xpecto.github.io/docs/img/img_1440753874370.png)  | Alle Provisionen auswählen| 


----------


| ![](http://xpecto.github.io/docs/img/img_1440753891145.png)    | Alle Provisionen über der nebenstehenden Schwelle auswählen| 
|![](http://xpecto.github.io/docs/img/img_1440753923716.png)|Nur Provisionsauszahlungen über die Schwelle werden abgerechnet|


----------


|![](http://xpecto.github.io/docs/img/img_1440753950213.png)|Entfernt die getroffene Auswahl|
|![](http://xpecto.github.io/docs/img/img_1440753976766.png)|Berechnugslauf verwerfen. Es kann eine neue Berechnung gestartet werden|

Nun markieren Sie die Provisionszahlungen die bei der Berechnung berücksichtigt werden sollen, und klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1432632280997.png). 

Durch die Bestätigung mit *Ja* werden die die ausgewählten Provisionen verbucht. Diese verbuchten Werte werden dann bei Vertrag in der Provisionsliste angezeigt. 

![](http://xpecto.github.io/docs/img/img_1461756475178.png)

Danach wird die Erfolgsmeldung *Die Verbuchung wurde erfolgreich durchgeführt* in dem Dialog *Verbuchung der Provisionsberechnung.*

![](http://xpecto.github.io/docs/img/img_1461753606041.png)

Wenn Sie in dem Dialog *Verbuchung der Provisionsabrechnung* auf *Weiter zu Belegdruck und Auszahlung* klicken, werden Sie zur Maske *Belegdruck und Auszahlung* weitergeleitet. Hier wird eine Auflistung der verbuchte Provisionen für den ausgewählten Zeitintervall angezeigt.

![](http://xpecto.github.io/docs/img/img_1461759266502.png)

 Sie können hier jederzeit zwischen dem vorherigen Zeitraum und dem nächsten Zeitraum wechseln. Mit Hilfe der Pfeile können Sie nun einen anderen Zeitraum wählen.

![](http://xpecto.github.io/docs/img/img_1461757224272.png)

Um eine bestehende Buchung in der Abrechnung zu ändern, klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441095989354.png).  Sie können durch betätigen der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441100101421.png) eine neue Buchung, wie z.B. einen Vorschuss, einfügen.
Falls Sie eine Abrechnung geändert haben, dann klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441108231660.png), um die Liste der Abrechnungen zu aktualisieren.

Um die erstellten Auszahlungen als SEPA-Datei auszugeben, klicken Sie auf ![](http://xpecto.github.io/docs/img/img_1440751324468.png). 

In der Maske *Zahlungsdatei erstellen* kann zwischen mehreren Verfahren zur Durchführung von Überweisungen ausgewählt werden. Sie können die Ausführungsoptionen, den Speicherort festlegen und angeben, ob ein Begleitzettel erstellt werden soll.

![](http://xpecto.github.io/docs/img/img_1461758647572.png)

Z.B. kann als Format *CSV* ausgewählt werden. Es wird automatisch überprüft ob die Datei erstellt werden kann. Klicken Sie auf Speichern um die Datei zu erstellen. Es wird hier ein Zahlungsverkehr - Begleitzettel erstellt und angezeigt. 

Nun kehren Sie zur Maske *Belegdruck und Auszahlungen* zurück duch Schliessen der Maske *Zahlungsdatei erstellen*.

![](http://xpecto.github.io/docs/img/img_1461759310739.png)

Die komplette Abrechnung für einen Abrechnungszeitraum kann mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440751219341.png) wieder gelöscht werden.

Soll die Provisionsabrechnung gedruckt oder per E-Mail zugestellt werden, klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440751272141.png), so wählen Sie den zugehörigen Bericht (häufig *Provisionsabrechnung*) und den gewünschten Drucker bzw. das gewünschte Ausgabeformat. 

![](http://xpecto.github.io/docs/img/img_1461759452003.png)

Sie können einen *Testdruck*, um für jeden  Vermittler  eine Provisionsabrechnung erzeugen ohne Belegnummer. Alternativ können Sie einen *Belegdruck* wählen, um Abrechnungsbelege unter automatischer Vergabe lückenloser und fortlaufender Belegnummern zu erstellen. 

![](http://xpecto.github.io/docs/img/img_1461759529178.png)

Um die Belege zu löschen klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1441103301118.png). Es werden alle Belege für die markierte Datensätze gelöscht.
