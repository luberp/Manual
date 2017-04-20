Um Anlegern Zugangswege zu Investments zu ermöglichen  bieten sich Investitionen in Fonds. Die Fonds werden in xpectoPro als Produkte hinterlegt. 
Kunden sind Investoren die Produktbeteiligungen kaufen, die als Verträge angelegt werden.

Um einen Vertrag anzulegen markieren Sie den gewünschten Kunden zu dem Sie einen Vertrag anlegen wollen. Sie haben die Möglichkeit in der klassischen Menü-Ansicht einen neuen Vertrag anzulegen über *Menü → Neu → Vertrag*, oder über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461150969976.png).
In der modernen Menü-Ansicht wenn Sie sich gerade in der Vertragsmaske befinden kann ein neuer Vertrag angelegt durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461160123775.png).

![](http://xpecto.github.io/docs/img/img_1461153154297.png)

Hier wird der Dialog *Neuer Datensatz* geöffnet. Wählen Sie hier *Vertragsdaten* um einen neuen Vertrag anzulegen.

![](http://xpecto.github.io/docs/img/img_1461151680852.png)

Fall Sie sich nicht in der Vertragsmaske befinden klicken Sie dann auf der Pfeil  ![](http://xpecto.github.io/docs/img/img_1461153569579.png) unter Funktion *Neu* und dann auf *Vertragsdaten* um einen neuen Vertrag anzulegen. Der Pfeil unter einer Funktion weist darauf hin, dass Untermenüs existieren.

![](http://xpecto.github.io/docs/img/img_1461151120846.png)

Es erscheint der Dialog *neuen Vertrag erstellen*, hier wählen Sie ein Produkt und geben eine Vertragsnummer ein. Damit legen Sie die Beteiligung an einen Produkt fest. 
Es wird eine Vertragsnummer vorgeschlagen, wenn Sie nicht damit einverstanden sind dann vergeben Sie nach Ihrer internen Richtlinien eine freie Nummer.

![](http://xpecto.github.io/docs/img/img_1461151200710.png)

Der neue Vertrag wird nach Bestätigung mit *OK* in der Beteiligung angezeigt.

Die Vertragsmaske enthält folgende Reiter: *Allgemein, Eigenschaften, Werte, OPOS, Übertragung, Salden, Buchungsdaten, Sollbuchungen, Ereignisse, Belege, Drittrechte*.

![](http://xpecto.github.io/docs/img/img_1461151792103.png)

Der Reiter *Allgemein* teilt sich in folgende Feldgruppen: *Allgemein*, *Daten*, *Auswertung*, *Status, Provision*, *Konten, Rateneinzug*,  *Beteiligung*. 
Geben Sie die Daten zum Vertrag wie Tranche, Laufzeit, Zahlungsintervall usw. ein. 
Speichern Sie Ihre neue Daten ab. 

Eine entscheidende Feldgruppe  ist *Status, Provision*. Wählen Sie den entsprechenden Vermittler aus der Vermittlerliste  und bestätigen Sie mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461153950083.png). Damit werden die Provisionsansprüche erzeugt.

![](http://xpecto.github.io/docs/img/img_1461152188930.png)

Provisionsansprüche werden aus den Modellen und den Provisionsätzen, in Verbindung mit den Daten des Vertrages, erzeugt. 
Diese Daten sind sofort einsehbar und bilden meist die maximale Provision die bei erfolgreichem Verlauf des Vertrags insgesamt gezahlt wird. Diese Ansprüche können dann manuell bearbeitet werden. Damit können spezielle Ansprüche für einzelne Verträge hinterlegt werden (siehe Handbuch *Vermittler → Provisionen*). Falls für diesen Vertrag die Provisionsberechnung durchgeführt würde, dann werden für jede Provision die Felder *Ausbezahlt* und *letzte Zahlung* ausgefüllt (siehe dieses Handbuch *Berechnung → Provisionsberechnung*).

Über den Reiter *Eigenschaften* können sie die Bemerkungen zum Vertrag anlegen und ändern.  Diese Bemerkungen zum Vertrag sind dynamisch und an Ihre Wünsche anpassbar. 

Der Reiter *Werte* beinhaltet die Feldgruppen: *Verknüpfung*, *Wert*, *Berechnungsparameter*, *Dokument* und dient der Zinsberechnung und dient dazu manuell für eine Kategorie die Verbuchungsvorschriften zu definieren (siehe Handbuch *Neu → Produkte → Wertarten*). 

xpectoPro bietet eine Offene Posten Buchhaltung, die überprüft ob die Forderungen bereit beglichen wurden. Unter dem Reiter *OPOS* wird die OPOS-Liste angezeigt. Eine OPOS-Liste ist die Liste aller offenen Buchungen. 

Der Reiter *Übertragung* zeigt dann an, ob einen Vertrag die Person gewechselt hat und zwar ob Rechtsvorgänger oder Rechtsnachfolger hat. Eine Übertragung kann aus verschiedenen Gründen gemacht werden z. B. Erbfall, Aufteilung auf 2 weitere Personen, wegen Scheidung.

![](http://xpecto.github.io/docs/img/img_1461157812980.png)

Wie ein Vertrag übertragen wird ist unter Handbuch *Bearbeiten → Vertrag übertragen* beschrieben.

Der Reiter *Salden* beihaltet eine Saldenauswertung zu dem Vertrag. Die hier hinterlegte Konten beziehen sich auf die unter *Produkte* vorkonfigurierte Salden.

![](http://xpecto.github.io/docs/img/img_1461159004275.png)

Der Reiter *Buchungsdaten* zeigt eine Übersicht der Buchungsdaten die den Vertrag betreffen (siehe Handbuch *Berechungen → Berechnungen und Transaktionen*). Die Feldgruppen sind im GoBS-Modus (Grundsätze ordnungsmäßiger DV-gestützter Buchführungssysteme) und deshalb nicht editierbar. Um eine neue Buchung anzulegen (siehe Handbuch *Bearbeiten → Stapelbuchungen* oder *Bearbeiten → Beteiligungs-/Vertragsbuchungen*).

Unter dem Reiter *Sollbuchungen* werden Informationen zu Lastschriften und auch Auszahlungen/Überweisungen angezeigt. Für jede einzuziehende monatliche Rate wird hier automatisch (siehe Handbuch *Berechnungen → Zahlungsverkehr*) ein Datensatz eingetragen mit Datum, Text, Betrag, Status und dem Fondskonto, auf das die Lastschrift eingezogen werden soll.
Soll der Lastschrifteinzug bei einem Vertrag für eine  Monatsrate ausgesetzt werden, so muss bei dem entsprechenden Eintrag auf dem Karteireiter *Sollbuchungen* des betroffenen Vertrags der Status manuell auf ausgesetzt umgestellt werden.

Auf dem Karteireiter *Ereignisse* werden wichtige Ereignisse zum aktuell ausgewählten Vertrag festgehalten.  Die Ereignisse können auf mehrere Ebenen verteilt werden: *Kundenebene, Beteiligungsebene, Pflicht-Dokument, Beschwerde.* 

Beispiel: Sie haben ein Telefonat wegen einem Vertrag durchgeführt. Markieren Sie den Vertrag und
wählen Sie dazu die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461159119190.png).

Wählen Sie das Datum, die Ereignisart: Telefonat und hinterlegen Sie - falls gewünscht - eine Verknüpfung zu einer Datei. 

![](http://xpecto.github.io/docs/xpecto/Datei/de/Ereignis_zur_Beteiligung.png)

Nachdem die eingegebenen Daten mit *OK* bestätigt haben, wird das Telefonat-Ereignis in der Liste  angezeigt.

Durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461159194556.png) können Sie das Ereignis bearbeiten. Um ein Ereignis zu löschen klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461159231005.png).

In dem Reiter *Belege* werden die Belege die durch Berechnungen erzeugt wurden angezeigt.
Für die in xpectoPro durchgeführte Abrechnungen können Belege mit fortlaufender Belegnummer erstellt und im PDF-Format gespeichert werden.

Unter *Drittrechte* können die Ansprüche eines Dritten an dem Vertrag, erfasst werden. 