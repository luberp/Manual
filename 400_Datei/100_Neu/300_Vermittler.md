Ein Vermittler kann ein Verkäufer, Mitarbeiter oder Betreuer sein. Um einen neune Vermittler anzulegen betätigen Sie die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1431437056167.png) oder das Menü *Datei → Neu → Vermittler*. Es wird die nächste freie Nummer vorgeschlagen, wenn Sie nicht damit einverstanden sind dann vergeben Sie nach Ihrer internen Richtlinien eine freie Nummer.  Nachdem Sie die gewünschte neue Vermittlernummer eingegeben haben bestätigen Sie mit *OK*. 

 Unter dem Reiter *Allgemein* steht eine Übersicht von der Meldedaten, Provisionsdaten und  login für den Vertriebspartner-Portal.
 
![](http://xpecto.github.io/docs/img/img_1438595956872.png)

Der Reiter *Adressen* beinhaltet die folgende Unterkarteireiter: Allgemein, Rollen, Kontoverbindungen, Legitimationsdaten, Kirchensteuer, Auslands-Steuer.

Unter dem Reiter *Eigenschaften* können weitere Informationen wie Daten, Bemerkungen und vordefinierte Eigenschaften zum Vermittler erfasst werden

Bei Verwendung individueller Provisionssätze werden bei jedem Vermittler auf dem Karteireiter *Provisionssätze* die Provisionssätze des Vermittlers eingetragen. Hierbei repräsentiert ein Datensatz den Provisionssatz des ausgewählten Vermittlers für genau einen Provisionstyp, eine Firma, ein Produkt und optional einen Tarif. 

Reiter *Struktur* 
Definition des Vermittler-Strukturbaums: bei den Vermittlern muss untere Struktur-Betreuer-Nummer jeweils der dem ausgewählten Vermittler direkt übergeordnete Vermittler eingetragen werden. Sind bei einem Vermittler mehrere Provisionssätze eingetragen (z.B. für verschiedene Produkte), wird typischerweise in allen Provisionssätze derselbe übergeordnete Vermittler gewählt (es sei denn für verschiedene Produkte  oder Provisionstypen sollen unterschiedliche Vermittler-Strukturen definiert werden). Struktur-Betreuer-Nummer ist ein Pflichtfeld, beim Strukturkopf (oberster Vermittler des Strukturbaums) wird als übergeordneter Vermittler seine eigene Vermittler-Nr. eingetragen. Bis auf diesen Sonderfall, sind Zirkelbezüge unzulässig. 

![](http://xpecto.github.io/docs/img/img_1438602553303.png)


Unter *Berechnung* werden Wert und Einheit als Parameter für die Berechnung der Provision eingetragen. Optional kann der Gültigkeitszeitraum eines Provisionssatzes mittels „Gültig ab“ und/oder „Gültig bis“ eingeschränkt werden.

Unter *Buchungen*

![](http://xpecto.github.io/docs/img/img_1438593920330.png)

Auf dem Karteireiter *Ereignisse* werden wichtige Ereignisse zum aktuell ausgewählten Vermittler, Kunden oder Vertrag sowie zugehörige Dokumente festgehalten. Wählen Sie das Datum, die Ereignisart wie z.B. E-Mail oder Telefonat und hinterlegen Sie - falls gewünscht - eine Verknüpfung zu einer zugehörigen Datei (wie z.B. die originale E-Mail).

![](http://xpecto.github.io/docs/img/img_1438594393957.png)

*Auf dem Karteireiter Ereignisse werden wichtige Ereignisse zum aktuell ausgewählten Vermittler, Kunden oder Vertrag sowie zugehörige Dokumente festgehalten. Wählen Sie das Datum, die Ereignisart wie z.B. E-Mail oder Telefonat und hinterlegen Sie - falls gewünscht - eine Verknüpfung zu einer zugehörigen Datei (wie z.B. die originale E-Mail).*

Reiter *Belege*

![](http://xpecto.github.io/docs/img/img_1438594583641.png)

Reiter *Umsätze* 

Reiter *Auswertungen*
Links: xpectoWebPortal, lokalisieren mit Maps Google.com
Google Maps: Kunden anzeigen, Struktur anzeigen

Bei den in xpectoPro verwaltete Vetriebsgesellschaften handelt es sich in der Regel um Strukturvertriebe, bei denen die Vermittler ausgehend von einem Vertriebskopf (der ebenfalls als Vermittler in der Software erfasst ist) in einer Art Baumsturktur organisiert sind. Häufig werben bestehende Vermittler weiter Vermittler an, die dann in der Baumstruktur unter ihnen eingeordnet werden. 
In der Regel erhalten höher einstrukturierte Vermittler für Vertragsabschlüsse ihrer Unterstruktur die Provisionsdifferenz zwischen Ihrem eigenen Provisionssatz und dem meist niedrigeren Provisionssatz eines direkt untergeordneten Vermittlers.
Die Software bietet zwei alternative Methoden, um die Vermittler-Struktur und die Provisionssätze der Vermittler zu definieren: die Erfassung individueller Provisionssätze und die Verwendung eines Karriere-Systems. Die Definition des Strukturbaums erfolgt durch Verlinkung der einzelnen Vermittler untereinander. Je nach dem, welche der beiden oben genannten Methoden angewendet wird, funktioniert diese Verlinkung auf unterschiedliche Weise.

**Provisionierung Methoden**

> **individuelle Provisionen - die flexible Methode** Bei Verwendung individueller Provisionssätze werden bei jedem Vermittler auf dem
> Karteireiter *Provisionssätze* die Provisionssätze des Vermittlers
> eingetragen. Hierbei repräsentiert ein Datensatz den Provisionssatz
> des ausgewählten Vermittlers für genau einen Provisionstyp, eine
> Firma, ein Produkt und einen Tarif. 
> 
> Die Provisionsmodelle sind der wichtigste Bestandteile bei der
> Provisionsabrechnung Diese Provisionsmodelle bestehen aus einem Stück
> Programmcode (VB.net) und kann daher eine sehr umfangreiche Logik
> aufnehmen.
> 
> Die Provisionssätze legen die Höhe der Provisionen fest. Die
> Provisionssätze können dabei je Karrierestufe oder individuell für
> jeden Vermittler getrennt hinterlegt werden. Die Pflege über die
> Karrierestufen ermöglicht dabei eine einfache Verwaltung, da für neue
> Produkte nur die Sätze in den Karrierestufen gepflegt werden müssen.
> Falls Sie die Sätze für einzelne Vermittler oder auch alle Vermittler
> individuell festlegen möchten, so ist es auch dies möglich. Sie können
> die beide Formen auch mischen und so nur die Sätze für bestimte
> Produkte individuell festlegen. Für alle andere Produkte gilt in
> diesem Fall dann die aktuelle Karrierestufe.


   uiuzolio
   
       

> **Karriere-System - die einfache Methode (Default)** Bei Verwendung eines Karriere-Systems werden bei den einzelnen Vermittler keine
> Provisionssätze erfasst. Stattdessen wird bei jedem Vermittler auf dem
> Karteireiter *Allgemein* eine Karrierestufe ausgewählt. Zu den
> vorhandenen Karrierestufen müssen wiederum Standard-Provisionssätze
> festgelegt werden. Über den Menüpunkt *Datei  → Firmen* oder *Datei →
> Produkte* ist die Maske „xpectoPro Firmen und Produkte" erreichbar,
> über der die Firmen, Produkte und Gesellschaften verwaltet werden.  In
> dem Ansicht *Produkte* auf dem Reiter *Provisionssätze* werden für das
> ausgewählte Produkt die Standard-Provisionssätze für die einzelnen
> Karrierestufen, Firmen, Provisionstypen und optional für die einzelnen
> Tarife definiert.



![](http://xpecto.github.io/docs/img/img_1438603327829.png)

![](http://xpecto.github.io/docs/img/img_1438596753690.png)

![](http://xpecto.github.io/docs/img/img_1426067509382.png)

Links wird gegebenenfalls eine Übersicht Ihrer bestehenden Vermittler angezeigt. Legen Sie einen neuen Vermittler mit Menü	_Datei → Neu → Vermittler_ oder über die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1431437056167.png) an. Gehen Sie der Aufforderung, eine freie Vermittlernummer einzugeben, nach und bestätigen Sie mit OK. Evtl. wurde die Software bei der Installation so eingestellt, dass Vermittlernummern automatisch fortlaufend vergeben werden. In diesem Fall wird vom Programm die nächste freie Nummer vorgeschlagen. Ansonsten vergeben Sie nach Ihrer vertriebsinternen Richtlinie eine freie Nummer.

Erfassen Sie die vermittlerspezifischen Daten wie Name, Adresse, Kontaktdaten sowie Bankverbindung und Finanzamtdaten.

Die Eingabefelder *Benutzer* und *Passwort* dienen der Anmeldung des Vermittlers am xpecto Webportal. Die hier eingetragenen Zugangsdaten werden durch das Übertragen der Vermittlerdaten auf den Webserver (siehe Kapitel "Tabellen synchronisieren") automatisch frei geschalten.


Reiter *Auswertungen*: Links, Google Maps

Auf den Reiter *Eigenschaften* werden zusätzliche Infos wie Adressherkunft oder Bemerkungen zum Vermittler festgehalten.

In der Vermittler-Ansicht auf dem Karteireiter *Buchungen* werden Vermittler-Buchungen zu dem aktuell ausgewählten Vermittler verwaltet.
Vermittler-Buchungen sind durch die Provisionsabrechnung berechnete oder manuell erfasste Provisionszahlungen oder Einbehalte davon. Ein entsprechender Datensatz ist durch einen Schlüssel zur Kennzeichnung der Provisionsart, einen Text, ein Datum und einen Betrag definiert. Vermittler-Buchungen werden durch ihre Ähnlichkeit zu Buchungssätzen so bezeichnet, sind jedoch nicht zu verwechseln mit Buchungen der Finanzbuchhaltung.

Um z.B. eine Provisionsvorauszahlung manuell zu buchen, klicken Sie auf ![](http://xpecto.github.io/docs/img/img046.png) , wählen das Datum, den zugehörigen Schlüssel, den Text, den Betrag mit Währung, sowie die Firma. Je nach Buchungsart kann festgelegt werden, ob die Zahlung umsatzsteuerpflichtig ist oder nicht.

