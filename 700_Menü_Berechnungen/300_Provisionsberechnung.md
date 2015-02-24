Eine der zentralen Funktionen von xpectoPro ist die Provisionsberechnung. Um eine Provisionsberechnung zu erstellen, klicken Sie im Menü auf	_Berechnungen-&gt;Provisionsberechnung_.


![](http://xpecto.github.io/docs/img/img_1424767790694.png)


Links oben wird der Abrechnungszeitraum angezeigt. Der für die Provisionsabrechnung verwendete Abrechnungszeitraum beinhaltet alle manuell eingetragenen Vermittler-Buchungen im Zeitraum und alle im angegebenen Zeitraum fälligen Provisionszahlungen.

Rechts oben wird der Stichtag als Datum ausgegeben. Soll z.B.: eine Provisionsabrechnung für ein bestimmtes Produkt oder einen bestimmten Vermittler erstellt werden, muss die Checkbox Einschränkungen der Berechnung gesetzt werden.

Mögliche Einschränkungen sind:

*   Nach Produkt
*   Nach Tarif
*   Nach Vertragsnummer
*   Nach Vermittler
*   Nach Firma
*   Nach Provisionsart
*   Nach Transaktionsnummer

Nachdem Sie die gewünschten Einschränkungen ausgewählt haben, klicken Sie bitte auf _PROVISION BERECHNEN_.

![](http://xpecto.github.io/docs/img/img100.png)
![](http://xpecto.github.io/docs/img/img102.jpg)
[[TS6]](C:/src/EAWin/Docu/eAgentur.NET%20Handbuch/Handbuch_Neu_2.htm#_msocom_6)

In unserem Beispiel wird nun eine fällige Provisionszahlung in Euro und der Gegenwert in oftmals verwendeten firmeninternen Options- oder
Bonussystemen angezeigt.

iM markiertem Eingabefenster kann noch ein weiterer Filter gesetzt werden. Hier im Beispiel 100, das heißt nur Provisionszahlungen über 100,00
€ werden abgerechnet. Nur markierte Provisionszahlungen (gesetzter Haken) werden bei der Abrechnungserstellung berücksichtigt.

Nachdem Sie Ihre Auswahl getroffen haben klicken Sie auf weiter und bestätigen Sie die folgende Maske mit
![](http://xpecto.github.io/docs/img/img104.jpg)
.

![](http://xpecto.github.io/docs/img/img106.jpg)
[[TS7]](C:/src/EAWin/Docu/eAgentur.NET%20Handbuch/Handbuch_Neu_2.htm#_msocom_7)

Markieren Sie die Provisionszahlungen, für die eine Abrechnung erzeugt werden sollen durch "Haken setzen" und klicken Sie dann auf Auszahlung
erstellen. Es wird eine Auszahlung erstellt, in der in unserem Beispiel die auszuzahlende Provision mit anfallenden Bürokosten verrechnet wird und
somit nur reale Ansprüche des Vermittlers gegenüber der Zahlfirma berücksichtigt werden.

![](http://xpecto.github.io/docs/img/img108.jpg)
[[TS8]](C:/src/EAWin/Docu/eAgentur.NET%20Handbuch/Handbuch_Neu_2.htm#_msocom_8)

Die komplette Abrechnung für einen Abrechnungszeitraum kann mit der Schaltfläche
![](http://xpecto.github.io/docs/img/img110.jpg)
wieder gelöscht werden.

Um die erstellten Auszahlungen als DTAUS-Datei auszugeben, klicken Sie auf
![](http://xpecto.github.io/docs/img/img112.jpg)
. Die erstellte Datei ist im Temp-Verzeichnis (Unter Menü _Extras-&gt;Einstellungen-&gt;"Temp Pfad"_) zu finden und mühelos in Ihre
E-Banking-Software einzulesen.

Soll die Provisionsabrechnung ausgedruckt oder per E-Mail zugestellt werden, so wählen Sie den zugehörigen Bericht (Häufig
"Provisionsabrechnung") und den gewünschten Drucker bzw. das gewünschte Ausgabeformat. (PDF, Excel, Word...). Bestätigen Sie mit
![](http://xpecto.github.io/docs/img/img114.jpg)
.

Sie werden gefragt, ob Sie Belegnummern erzeugen wollen. Beantworten Sie diese Frage mit _Nein_, wird lediglich eine Testabrechnung gedruckt.
Beantworten Sie die Frage mit _Ja_, so werden Abrechnungsbelege unter automatischer Vergabe lückenloser und fortlaufender Belegnummern (nach
geltendem USt-Recht) gedruckt und zusätzlich in der Datenbank archiviert. Hinweis: Die Archivierungsfunktion genügt nicht den Anforderungen an
eine ordnungsgemäße EDV-gestüzte Archivierung. Die archivierten Belege können in der Vermittler-Maske auf dem Karteireiter_Belege_ aufgerufen und jederzeit wieder im PDF-Format ausgegeben werden.	[[TS9]](C:/src/EAWin/Docu/eAgentur.NET%20Handbuch/Handbuch_Neu_2.htm#_msocom_9)
