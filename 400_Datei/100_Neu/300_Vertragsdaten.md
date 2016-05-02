Um Anlegern Zugangswege zu Investments zu ermöglichen, bieten sich Investitionen in Fonds an. Die Fonds werden in xpectoPro als Produkte hinterlegt. Kunden sind Investoren, die Produktbeteiligungen kaufen, welche als Verträge angelegt werden.

Um einen Vertrag anzulegen, markieren Sie den gewünschten Kunden, zu dem Sie einen Vertrag anlegen wollen. Sie haben in der klassischen Menüansicht zwei Möglichkeiten einen neuen Vertrag anzulegen. Entweder über *Datei → Neu → Vertragsdaten* oder über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461150969976.png).

In der modernen Menüansicht kann ein neuer Vertrag angelegt werden unter *Schnellzugriff* und durch Anklicken der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461160123775.png).

![](http://xpecto.github.io/docs/img/img_1461153154297.png)


Hier wird der Dialog *Neuer Datensatz* geöffnet. Wählen Sie hier *Vertragsdaten*, um einen neuen Vertrag anzulegen.

![](http://xpecto.github.io/docs/img/img_1461151680852.png)


Sie können aber auch den Pfeil  ![](http://xpecto.github.io/docs/img/img_1461153569579.png) unter Funktion *Neu* und *Vertragsdaten* anklicken, um einen neuen Vertrag anzulegen. 

Der Pfeil unter einer Funktion weist darauf hin, dass Untermenüs existieren.

![](http://xpecto.github.io/docs/img/img_1461151120846.png)

Es erscheint die Eingabeaufforderung *neuen Vertrag erstellen*. Hier wählen Sie ein Produkt aus und geben eine Vertragsnummer ein. Damit legen Sie die Beteiligung an einem Produkt fest. Es wird die nächste freie Vertragsnummer vorgeschlagen. Falls Sie intern eine abweichende Nummerierung verwenden, können Sie manuell eine nach Ihrer internen Richtlinie nächste freie Nummer vergeben. 

![](http://xpecto.github.io/docs/img/img_1461151200710.png)


Der neue Vertrag wird nach Bestätigung mit *OK* in der Beteiligung angezeigt.

Die Vertragsmaske enthält folgende Reiter: *Allgemein, Eigenschaften, Werte, OPOS, Übertragung, Salden, Buchungsdaten, Sollbuchungen, Ereignisse, Belege, Drittrechte*.

![](http://xpecto.github.io/docs/img/img_1461151792103.png)


Der Reiter *Allgemein* teil sich in folgende Feldgruppen: *Allgemein*, *Daten*, *Auswertung*, *Status, Provision*, *Konten, Rateneinzug*,  *Beteiligung*. Geben Sie die Daten zum Vertrag wie Tranche, Laufzeit, Zahlungsintervall usw. ein. 

Eine entscheidende Feldgruppe  ist *Status, Provision*. Wählen Sie den entsprechenden Vermittler aus der Vermittlerliste und bestätigen Sie mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461153950083.png). Damit werden die Provisionsansprüche erzeugt.

![](http://xpecto.github.io/docs/img/img_1461152188930.png)


Provisionsansprüche werden aus den Modellen und den Provisionssätzen in Verbindung mit den Daten des Vertrages erzeugt. Diese Daten sind sofort einsehbar und bilden meist die maximale Provision, die bei erfolgreichem Verlauf des Vertrags insgesamt gezahlt wird. Diese Ansprüche können dann manuell bearbeitet werden. Damit können spezielle Ansprüche für einzelne Verträge hinterlegt werden (siehe Handbuch *Vermittler → Provisionen*). Falls für diesen Vertrag die Provisionsberechnung durchgeführt wurde, wird für jede Provision die Felder *Ausbezahlt* und *letzte Zahlung* ausgefüllt (siehe *Berechnung → Provisionsberechnung*).

Über den Reiter *Eigenschaften* können Sie Bemerkungen zum Vertrag anlegen und ändern.  Diese Bemerkungen zum Vertrag sind dynamisch und an Ihre Wünsche anpassbar. 

Der Reiter *Werte* beinhaltet die Feldgruppen *Verknüpfung*, *Wert*, *Berechnungsparameter*, *Dokument* und dient der Zinsberechnung. Hier können manuell die Verbuchungsvorschriften für eine Kategorie definiert werden (siehe Handbuch *Neu → Produkte → Wertarten*). 

xpectoPro hat eine Offene Posten Buchhaltung, welche überprüft, ob die Forderungen bereits beglichen worden sind. Unter dem Reiter *OPOS* wird die Offene Posten-Liste angezeigt. Bei der OPOS-Liste handelt es sich demzufolge um die Liste aller offenen Rechnungen. 

Der Reiter *Übertragung* zeigt an, ob ein Vertrag eine Übertragung von vorhandenen Vertragsdaten auf einen anderen Kunden vorsieht. Eine Übertragung kann aus verschiedenen Gründen erfolgen. Zudem zeigt der Reiter *Übertragung* an, ob bei einem Vertrag bereits die Partei gewechselt wurde und wenn ja, ob es sich um einen Rechtsvorgänger oder Rechtsnachfolger handelt. 

![](http://xpecto.github.io/docs/img/img_1461157812980.png)


Wie ein Vertrag übertragen wird, ist unter *Bearbeiten → Vertrag übertragen* beschrieben.

Der Reiter *Salden* beinhaltet eine Saldenauswertung zu dem Vertrag. Die hier hinterlegten Konten beziehen sich auf die unter *Produkte* vorkonfigurierten Salden.

![](http://xpecto.github.io/docs/img/img_1461159004275.png)


Der Reiter *Buchungsdaten* zeigt eine Übersicht der Buchungsdaten, die den Vertrag betreffen (siehe  *Berechungen → Berechnungen und Transaktionen*). Die Feldgruppen sind im GoBS-Modus (Grundsätze ordnungsmäßiger DV-gestützter Buchführungssysteme) und deshalb nicht editierbar. Wie Sie eine neue Buchung anlegen können, finden Sie in der klassischen Menüansicht unter *Bearbeiten → Stapelbuchung* oder *Bearbeiten → Beteiligungs-/Vertragsbuchungen* und in der modernen Menüansicht unter dem Reiter *Buchhaltung*, Funktion *Beteiligungs-Vertragsbuchungen* oder *Stapelbuchung*.

Unter dem Reiter *Sollbuchungen* werden Informationen zu Lastschriften angezeigt. Für jede einzuziehende monatliche Rate wird hier automatisch (siehe *Berechnungen → Zahlungsverkehr*) ein Datensatz eingetragen mit Datum, Text, Betrag, Status und dem Fondskonto, auf das die Lastschrift eingezogen werden soll. 

Soll der Lastschrifteneinzug bei einem Vertrag für eine Monatsrate ausgesetzt werden, so muss bei dem entsprechenden Eintrag auf dem Karteireiter Sollbuchungen des betroffenen Vertrags der Status manuell auf ausgesetzt umgestellt werden.

Auf dem Karteireiter *Ereignisse* werden wichtige Ereignisse zum aktuell ausgewählten Vertrag festgehalten.  Die Ereignisse können auf mehreren Ebenen verteilt werden: *Kundenebene, Beteiligungsebene, Pflicht-Dokument, Beschwerde.* 

Beispiel: Sie haben ein Telefonat wegen einem Vertrag geführt. Markieren Sie den Vertrag und
wählen Sie dazu die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461159119190.png).

Wählen Sie das Datum und die Ereignisart,  hier Telefonat und hinterlegen Sie - falls gewünscht - eine Verknüpfung zu einer Datei. 

![](http://xpecto.github.io/docs/img/img_1461159331075.png)


Nachdem Sie die eingegebenen Daten mit *OK* bestätigt haben, wird das Telefonat-Ereignis in der Liste  angezeigt.

Durch Anklicken der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461159194556.png) können Sie das Ereignis bearbeiten. Um ein Ereignis zu löschen, klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461159231005.png).

In dem Reiter *Belege* können Belegarten, wie zum Beispiel Rechnungen, zu dem Vertrag angelegt werden.
Für die in xpectoPro durchgeführte Abrechnung können Belege mit fortlaufender Belegnummer erstellt und im PDF-Format gespeichert werden.

Unter dem Reiter *Drittrechte* können Ansprüche eines Dritten aus dem Vertrag erfasst werden. 