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

Sie haben hier die Möglichkeit die berechnete Datensätze zu filtern. Der Filter dient zum markieren von Provisionsauszahlungen die verbucht werden sollen. Im markiertem Eingabefenster kann noch ein weiterer Filter gesetzt werden. Hier im Beispiel 100, das heißt nur Provisionszahlungen über 100,00 € werden abgerechnet. Nur markierte Provisionszahlungen (gesetzter Haken) werden bei der Abrechnungserstellung berücksichtigt.

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

Mit dieser Funktion verbuchen Sie die ausgewählten Provisionen. Diese Buchungen werden dann bei Vermittler unter dem Reiter *Buchungen*, und bei Vertrag unter dem Reiter *Buchungsdaten*.

![](http://xpecto.github.io/docs/img/img_1432632479268.png)

Wenn Sie hier auf Weiter zu Belegdruck klicken dann werden Sie anschließend automatisch zum Belegdruck weiter geleitet.

![](http://xpecto.github.io/docs/img/img_1440748640999.png)

DTAUS/SEPA erstellen, damit wird ein Begleitzettel erstellt und der Bank eingereicht.

![](http://xpecto.github.io/docs/img/img_1440748885165.png)

Um die erstellten Auszahlungen als DTAUS-Datei auszugeben, klicken Sie auf
![](http://xpecto.github.io/docs/img/img_1440751324468.png). Die erstellte Datei ist im Temp-Verzeichnis (Unter Menü _Extras-&gt;Einstellungen-&gt;"Temp Pfad"_) zu finden und mühelos in Ihre E-Banking-Software einzulesen.

Provisionen löschen
Die komplette Abrechnung für einen Abrechnungszeitraum kann mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440751219341.png) wieder gelöscht werden.

Belege löschen damit werden die erzeugte Belege gelöscht.

Abrechnungen drücken
Soll die Provisionsabrechnung ausgedruckt oder per E-Mail zugestellt werden, so wählen Sie den zugehörigen Bericht (Häufig "Provisionsabrechnung") und den gewünschten Drucker bzw. das gewünschte Ausgabeformat. (PDF, Excel, Word...). Bestätigen Sie mit ![](http://xpecto.github.io/docs/img/img_1440751272141.png).

 ![](http://xpecto.github.io/docs/img/img_1440748756680.png)

Testdruck: Es wird dann für jeden  Vermittler  eine Provisionsabrechnung erzeugt, ohne Belegnummer.

Belegdruck: Sie werden gefragt, ob Sie Belegnummern erzeugen wollen. Beantworten Sie diese Frage mit _Nein_, wird lediglich eine Testabrechnung gedruckt. Beantworten Sie die Frage mit , so werden Abrechnungsbelege unter automatischer Vergabe lückenloser und fortlaufender Belegnummern (nach geltendem USt-Recht) gedruckt und zusätzlich in der Datenbank archiviert. 
Hinweis: Die Archivierungsfunktion genügt nicht den Anforderungen an eine ordnungsgemäße EDV-gestüzte Archivierung. Die archivierten Belege können in der Vermittler-Maske auf dem Karteireiter_Belege_ aufgerufen und jederzeit wieder im PDF-Format ausgegeben werden.

![](http://xpecto.github.io/docs/img/img_1440749157838.png)

Bereitstellung Abrechnung
Die Abrechnungen werden zum Abschluss erstellt und in den meisten Fällen direkt als PDF in unserem Vertriebspartnerportal zum Download für die Vermittler bereitgestellt. Die Bereitstellung ist dabei direkt in die Software integriert und sehr einfach. Die Empfänger erhalten eine E-Mail oder eine SMS als Benachrichtigung und Hiweis. Natürlich können die Abrechnungen auch direkt gedruckt werden. Das Layout der Abrechnung kann frei angepasst werden und soll modern un in Ihrem Style erfolgen.


Berechnungslauf starten
Berechnungslauf anzeigen und verbuchen
Belegdruck und auszahlung
