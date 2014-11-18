
Eine der zentralen Funktionen von Agentur / Fonds ist die Provisionsberechnung. Um eine Provisionsberechnung zu erstellen, klicken Sie auf Menü Berichte - Provisionsberechnung.

![](http://xpecto.github.io/docs/img/img_038.png)

Geben Sie links oben den Abrechnungszeitraum ein. Der für die Provisionsabrechnung verwendete Abrechnungszeitraum beinhaltet alle manuell eingetragenen Buchungen im Zeitraum und alle im angegebenen Zeitraum fälligen Provisionszahlungen.
Mögliche Abrechnungszeiträume sind:

| Zeitraum        | Eingabeformat |
| ---             | ---           |
| Täglich         | 2005/06/12    |
| wöchentlich     | 2005KW30      |
| zweiwöchentlich | 2005DW15      |
| halbmonatlich   | 2005HM8       |
| Monatlich       | 2005M3        |
| vierteljährlich | 2005Q2        |
| halbjährlich    | 2005H1        |
| Jährlich        | 2005          |

Rechts oben wird der Stichtag als Datum ausgegeben. Soll z.B.: eine Provisionsabrechnung für ein bestimmtes Produkt oder einen bestimmten Vermittler erstellt werden, muss die Checkbox Einschränkungen der Berechnung gesetzt werden.

Mögliche Einschränkungen sind:

- Nach Produkt
- Nach Tarif
- Nach Vertragsnummer
- Nach Vermittler
- Nach Zahlfirma
- Nach Provisionsart

Nachdem Sie die gewünschten Einschränkungen ausgewählt haben, klicken Sie bitte auf PROVISION BERECHNEN.

![](http://xpecto.github.io/docs/img/img_039.png)

In unserem Beispiel wird nun eine fällige Provisionszahlung in Euro und der Gegenwert in oftmals verwendeten firmeninternen Options- oder Bonussystemen angezeigt.

Im markiertem Eingabefenster kann noch ein weiterer Filter gesetzt werden. Hier im Beispiel 100, das heißt nur fällige Provisionszahlungen über 100€ werden abgerechnet. Nur markierte Provisionszahlungen (gesetzter Haken) werden bei der Abrechnungserstellung berücksichtigt.

Nachdem Sie Ihre Auswahl getroffen haben klicken Sie auf weiter und bestätigen Sie die folgende Maske mit ![](http://xpecto.github.io/docs/img/img_040.png).

![](http://xpecto.github.io/docs/img/img_041.png)

Markieren Sie die Provisionszahlungen, für die eine Abrechnung erzeugt werden sollen durch "Haken setzen" und klicken Sie dann auf Auszahlung erstellen. Es wird eine Auszahlung erstellt, in der in unserem Beispiel die auszuzahlende Provision mit anfallenden Bürokosten verrechnet wird und somit nur reale Ansprüche des Vermittlers gegenüber der Zahlfirma berücksichtigt werden.

![](http://xpecto.github.io/docs/img/img_042.png)

Noch nicht ausgegebene Buchungen können mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_043.png) wieder auf Ihren ursprünglichen Zustand gesetzt werden.

Um die erstellten Auszahlungen als DTAUS - Datei auszugeben, wählen Sie die Zahlfirma aus und klicken dann auf ![](http://xpecto.github.io/docs/img/img_044.png). Die erstellte Datei ist im Temp - Verzeichnis ( Unter Menü Extras - Einstellungen Temp Pfad ) zu finden und mühelos in Ihre E-Banking - Software einzulesen.

Soll die Provisionsabrechnung ausgedruckt oder per E-Mail zugestellt werden, so wählen Sie im Bereich Ausgabe wiederum die Zahlfirma, den zugehörigen Bericht (Bericht Provisionsabrechnung) und das gewünschte Ausgabeformat. (PDF, Excel, Word...)

Bestätigen Sie mit ![](http://xpecto.github.io/docs/img/img_045.png).

Sie werden gefragt , ob Sie Belegnummern erzeugen wollen. Es ist gesetzlich vorgeschrieben, dass lückenlose Belegnummern für Abrechnungen geführt werden müssen.

Bestätigen Sie diese Frage nur mit JA, wenn es sich um eine reale Abrechnung handelt, nicht jedoch bei Testläufen!

Schließen Sie die Provisionsabrechnung mit ![](http://xpecto.github.io/docs/img/img_046.png).

Die erstellten Belege werden in der Maske Vermittler - Karteireiter Belege archiviert, und können dort jederzeit wieder im PDF- Format ausgegeben werden. Physikalisch werden die Belege nicht im Archiv sondern in der Datenbank gespeichert.


