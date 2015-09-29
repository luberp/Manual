Um Anlegern Zugangswege zu Investments zu ermöglichen  bieten sich Investitionen in Fonds. Die Fonds werden in xpectoPro als Produkte hinterlegt. 
Kunden sind Investoren die Produktbeteiligungen kaufen, die als Verträge angelegt werden.

Um einen Vertrag anzulegen markieren Sie den gewünschten Kunden zu dem Sie einen Vertrag anlegen wollen. Sie haben die Möglichkeit einen neuen Vertrag anzulegen über *Menü → Neu → Vertrag*, oder über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1426508800812.png).

Es erscheint die Eingabeaufforderung *neuen Vertrag erstellen*, hier wählen Sie ein Produkt und einen Vertragsnummer ein. Damit legen Sie die Beteiligung an einen Produkt fest. 
Es wird eine Vertragsnummer vorgeschlagen, wenn Sie nicht damit einverstanden sind dann vergeben Sie nach Ihrer internen Richtlinien eine freie Nummer.

![](http://xpecto.github.io/docs/img/img_1443172055290.png)

Der neue Vertrag wird nachdem Speichern unter der Beteiligung angezeigt.

![](http://xpecto.github.io/docs/img/img_1443172880219.png)

Der Reiter *Allgemein* teil sich in folgende Feldgruppen: *Allgemein*, *Daten*, *Auswertung*, *Status, Provision*, *Konten, Rateneinzug*,  *Beteiligung*. 
Geben Sie die Daten zum Vertrag wie Trasche, Laufzeit, Zahlungsintervall usw. ein. 

Eine entscheidende Feldgruppe  ist *Status, Provision*. Wählen Sie den entsprechenden Vermittler aus der Vermittlerliste  und bestätigen Sie mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img041.png). Damit werden die Provisionsansprüche erzeugt.
![](http://xpecto.github.io/docs/img/img_1432631850462.png)

Provisionsansprüche werden aus den Modellen und den Provisionsätzen, in Verbindung mit den Daten des Vertrages, erzeugt. 
Diese Daten sind sofort einsehbar und bilden meist die maximale Provision die bei erfolgreichem Verlauf des Vertrags insgesamt gezahlt wird. Diese Ansprüche können dann manuell bearbeitet werden. Damit können spezielle Ansprüche für einzelne Verträge hinterlegt werden (siehe *Vermittler → Provisionen*). Falls für diesen Vertrag die Provisionsberechnung durchgeführt würde, dann werden für jede Provision die Felder *Ausbezahlt* und *letzte Zahlung* ausgefüllt (siehe *Berechnung → Provisionsberechnung*).

![](http://xpecto.github.io/docs/img/img_1440763968478.png)

Über den Reiter *Eigenschaften* können sie die Bemerkungen zum Vertrag anlegen und ändern.  Diese Bemerkungen zum Vertrag sind dynamisch und an Ihre Wünsche anpassbar. 

Der Reiter *Werte* beinhaltet die Feldgruppen:  *Verknüpfung*, *Wert*, *Berechnungsparameter*, *Dokument* und dient der Zinsberechnung und dient dazu manuell  für eine Kategorie, die Verbuchungsvorschriften zu definieren siehe (*Neu → Produkte → Wertarten*). 

xpectoPro bietet eine Offene Posten Buchhaltung, die überprüft ob die Forderungen bereit beglichen würden. Unter dem Reiter *OPOS* wird die OPOS-Liste angezeigt. Eine OPOS-Liste ist die Liste aller offenen Rechnungen. 

Der Reiter *Übertragung* dient der Übertragung von vorhandenen Vertragsdaten auf andere Kunden. Eine Übertragung kann aus verschiedene Grunde gemacht werden. Diese können im Bereich Übertragungs-Parameter unter Übertragungs-Art ausgewählt werden. Dazu müssen Sie noch andere Übertragungs-Parameter einstellen wie Übertragungs-Art, Erwerbs-Art, Entgeltlich, Verkaufserlös, Vertrags-Übergang, Ergebnis-Übergang.

Um eine Übertragung durchzuführen markieren Sie den zu übertragenen Vertrag, und gehen Sie zum Reiter *Übertragung*.
In dem Untereiter *Übertragung durchführen* können die Nachfolger eingestellt werden. Dazu Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1426513187688.png), es öffnet sich der Suchdialog *Kunden auswählen*. Hier können Sie den Nachfolger suchen und durch Doppelklick auswählen.

![](http://xpecto.github.io/docs/img/img_1443173397056.png)

Nachdem die Übertragungs-Parameter eingestellt würden Klicken Sie auf die Schaltfläche *Übertragung durchführen.*
Wählen Sie in dem folgenden Dialog die fehlende Umbuchungs-Vorschriften.

![](http://xpecto.github.io/docs/img/img_1443173762535.png)

Der Untereiter *Vorgänger/Nachfolger* zeigen ob einen Vertrag Vorgänger oder Rechtsnachfolger hat.

![](http://xpecto.github.io/docs/img/img_1443174186737.png)

Nachdem der Übertrag durchgeführt würde, wird der Vertrag-Status in automatisch in übertragen, geändert .

Der Reiter *Salden* beihaltet eine Saldenauswertung zu dem Vertrag. Die hier hinterlegte Konten beziehen sich auf die unter *Produkte* vorkonfigurierte Salden.

![](http://xpecto.github.io/docs/img/img_1443172824687.png)

Der Reiter *Buchungsdaten* zeigt eine Übersicht der Buchungsdaten die den Vertrag betreffen (siehe *Berechungen → Berechnungen und Transaktionen*). Die Feldgruppen sind in GoBS-Modus (Grundsätze ordnungsmäßiger DV-gestützter Buchführungssysteme) und deshalb nicht editierbar. Um eine neue Buchung anzulegen (siehe *Bearbeiten → Stapelbuchungen* oder *Bearbeiten → Beteiligungs-/Vertragsbuchungen*).

![](http://xpecto.github.io/docs/img/img_1443172984417.png)

Unter dem Reiter *Sollbuchungen* werden Informationen zu Lastschriften angezeigt. Für jede einzuziehende monatliche Rate wird hier automatisch (siehe *Berechnungen → Zahlungsverkehr*) ein Datensatz eingetragen mit Datum, Text, Betrag, Status und dem Fondskonto, auf das die Lastschrift eingezogen werden soll.
Soll der Lastschrifteinzug bei einem Vertrag für eine  Monatsrate ausgesetzt werden, so muss bei dem entsprechende Eintrag auf dem Karteireiter Sollbuchungen des betroffenen Vertrags der Status manuell auf ausgesetzt umgestellt werden.

Auf dem Karteireiter *Ereignisse* werden wichtige Ereignisse zum aktuell ausgewählten Vertrag festgehalten.  Die Ereignisse können auf mehrere Ebenen verteilt werden: *Kundenebene, Beteiligungsebene, Pflicht-Dokument, Beschwerde.* 

Beispiel: Sie haben einen Telefonat wegen einem Vertrag durchgeführt. Markieren Sie den Vertrag und
wählen Sie dazu die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1443175241487.png).

Wählen Sie das Datum, die Ereignisart: Telefonat und hinterlegen Sie - falls gewünscht - eine Verknüpfung zu einer Datei. 

![](http://xpecto.github.io/docs/img/img_1443175387538.png)

Nachdem die eingegebenen Daten mit *OK* bestätigt haben, wird das Telefonat-Ereignis in der Liste  angezeigt.

Durch eine Klick auf die  ![](http://xpecto.github.io/docs/img/img_1438327135428.png) können Sie das Ereignis bearbeiten. Um ein Ereignis zu löschen wählen Sie die Schaltfläche![](http://xpecto.github.io/docs/img/img_1438330503651.png).

![](http://xpecto.github.io/docs/img/img_1443173024837.png)

In dem Reiter *Belege* können Belegarten und z.B. Gutschriften, Rechnungen zu dem Vertrag angelegt werden.
Für die in xpectoPro durchgeführte Abrechnungen können Belege mit fortlaufender Belegnummer erstellt und im PDF-Format gespeichert werden.

Unter *Drittrechte* können die Ansprüche eines Dritten auf dem Vertrag, erfasst werden. 