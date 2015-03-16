
Bei den in xpectoPro verwaltete Vetriebsgesellschaften handelt es sich in der Regel um Strukturvertriebe, bei denen die Vermittler ausgehend von einem Vertriebskopf (der ebenfalls als Vermittler in der Software erfasst ist) in einer Art Baumsturktur organisiert sind. Häufig werben bestehende Vermittler weiter Vermittler an, die dann in der Baumstruktur unter ihnen eingeordnet werden. 
In der Regel erhalten höher einstrukturierte Vermittler für Vertragsabschlüsse ihrer Unterstruktur die Provisionsdifferenz zwischen Ihrem eigenen Provisionssatz und dem meist niedrigeren Provisionssatz eines direkt untergeordneten Vermittlers.
Die Software bietet zwei alternative Methoden, um die Vermittler-Struktur und die Provisionssätze der Vermittler zu definieren: die Erfassung individueller Provisionssätze und die Verwendung eines Karriere-Systems. Die Definition des Strukturbaums erfolgt durch Verlinkung der einzelnen Vermittler untereinander. Je nach dem, welche der beiden oben genannten Methoden angewendet wird, funktioniert diese Verlinkung auf unterschiedliche Weise.

**individuelle Provisionen - die flexible Methode**
Bei Verwendung individueller Provisionssätze werden bei jedem Vermittler auf dem Karteireiter *Provisionssätze* die Provisionssätze des Vermittlers eingetragen.Hierbei repräsentiert ein Datensatz den Provisionssatz des ausgewählten Vermittlers für genau einen Provisionstyp, eine Firma, ein Produkt und einen Tarif. Unter *Berechnung* werden Wert und Einheit als Parameter für die Berechnung der Provision eingetragen. Optional kann der Gültigkeitszeitraum eines Provisionssatzes mittels „Gültig ab" und/oder „bis" eingeschränkt werden.

Definition des Vermittler-Strukturbaums: bei den Vermittlern muss untere Struktur-Betreuer-Nummer jeweils der dem ausgewählten Vermittler direkt übergeordnete Vermittler eingetragen werden. Sind bei einem Vermittler mehrere Provisionssätze eingetragen (z.B. für verschiedene Produkte), wird typischerweise in allen Provisionssätze derselbe übergeordnete Vermittler gewählt (es sei denn für verschiedene Produkte  oder Provisionstypen sollen unterschiedliche Vermittler-Strukturen definiert werden). Struktur-Betreuer-Nummer ist ein Pflichtfeld , beim Strukturkopf (oberster Vermittler des Strukturbaums) wird als übergeordneter Vermittler seine eigene Vermittler-Nr. eingetragen. Bis auf diesen Sonderfall, sind Zirkelbezüge unzulässig. 

    Beispiel

**Karriere-System - die einfache Methode (Default)**
Bei Verwendung eines Karriere-Systems werden bei den einzelnen Vermittler keine Provisionssätze erfasst. Stattdessen wird bei jedem Vermittler auf dem Karteireiter *Allgemein* eine Karrierestufe ausgewählt. Zu den vorhandenen Karrierestufen müssen wiederum Standard-Provisionssätze festgelegt werden. Über den Menüpunkt *Datei  → Firmen* oder *Datei → Produkte* ist der Dialog „xpectoPro Firmen und Produkte" erreichbar, über den die Firmen, Produkte und Gesellschaften verwaltet werden.  Auf dem Reiter *Produkte* auf dem Karteireiter *Provisionssätze* werden für das ausgewählte Produkt die Standard-Provisionssätze für die einzelnen Karrierestufen, Firmen, Provisionstypen und optional für die einzelnen Tarife definiert.


Wichtige Eckdaten für die Vertriebsverwaltung sind Ihre Vermittler. Sie erreichen die Maske durch einen Klick auf den Karteireiter _Vermittler_.

![](http://xpecto.github.io/docs/img/img_1426067509382.png)

Links wird gegebenenfalls eine Übersicht Ihrer bestehenden Vermittler angezeigt. Legen Sie neue Vermittler mit Menü	_Datei-&gt;Neu-&gt;Vermittler_ oder über die Schaltfläche ![](http://xpecto.github.io/docs/img/img026.png) an. Gehen Sie der Aufforderung, eine freie Vermittlernummer einzugeben, nach und bestätigen Sie mit OK. Evtl. wurde die Software bei der Installation so eingestellt, dass Vermittlernummern automatisch fortlaufend vergeben werden. In diesem Fall wird vom Programm die nächste freie Nummer vorgeschlagen. Ansonsten vergeben Sie nach Ihrer vertriebsinternen Richtlinie eine freie Nummer.

Erfassen Sie die vermittlerspezifischen Daten wie Name, Adresse, Kontaktdaten sowie Bankverbindung und Finanzamtdaten.

Die Eingabefelder _Benutzer_ und _Passwort _dienen der Anmeldung des Vermittlers am xpecto Webportal. Die hier eingetragenen Zugangsdaten werden durch das Übertragen der Vermittlerdaten auf den Webserver (siehe Kapitel "Tabellen synchronisieren") automatisch frei geschalten.

Karteireiter Adressen
Karteireiter Eigenschaften
Karteireiter Provisionssätze
Karteireiter Struktur
Karteireiter Buchungen
Karteireiter Ereignisse
Karteireiter Belege
Karteireiter Umsätze 
Karteireiter Auswertungen: Links, Google Maps
Auf den Karteireitern _Zusatzdaten_ und _Eigenschaften_ werden zusätzliche Infos wie Adressherkunft oder Bemerkungen zum Vermittler festgehalten.

Grundlagen Provision
Die Provisionsabrechnung mit xpectoPro ist sehr umfangreich und extrem anpassbar. Die Verwaltung hat dabei immer einen guten Überblick und Möglichkeiten zum manuellen Eingriff. 

Die Provisionsabrechnung besteht aus mehrere Teilen.

Provisionsmodelle
Provisionsmodelle sind der wichstigsten Bestandteil bei der Provisionsabrechnung. Diese Provisionsmodelle sind der wichstigste Bestandteil bei der Provisionsabrechnung. Diese Provisionsmodelle bestehen aus einem Stück Programmcode (VB.Net) und kann daher eine sehr umfangreiche Logik aufnehmen. xpectoPro kann für Sie garantiert jedes Provisionsmodell bereitstellen.

Provisionssätze
Die Provisionssätze legen die Höhe der Provisionen fest. Die Provisionssätze können dabei je Karrierestufe oder individuell für jeden Vetriebspartner getrennt hinterlegt werden. Die Pflege über die Karrierestufen ermöglicht dabei eine sehr einfache Verwaltung, da für neue Produkte nur die Sätze in den Karrierestufen gepflegt werden müssen. Falls Sie die Sätze für einzelne Vertriebspartner oder auch für alle Vertriebspartner individuell festlegen möchten, so ist auch dies möglich. Sie können die beiden Formen auch mischen und so nur die Sätze für bestimmte Produkte individuell festlegen. Für alle anderen Produkte gilt in diesem Fall dann die aktuelle Karrierestufe.

Berechnung Ansprüche
Bei der Vertragserfassung werden aus den Modellen und den Sätzen in Verbindung mit den Daten des Vertrags/Umsatzes die zukünftigen Provisionsansprüche für diesen Vertrag berechnet. Diese Daten sind sofort einsehbar und bilden meist die maximale Provision die bei erfolgreichem Verlauf des Vertrags insgesamt gezahlt wird. Diese Ansprüche können manuell bearbeitet werden. Damit können spezielle Ansprüche für einzelne Verträge hinterlegt werden.

Berechnung Zahlungen
In bestimmte Abstände erfolgt eine Provisionsabrechnung. Sie können tägliche, wöchentliche, halbmonatliche, monatliche, quartalsweise, halbjährige und jährliche Intervalle hinterlegen. Beim Abrechnungsverlauf errechnet xpectoPro die fällige Provisionszahlung für jeden Vertrag auf Basis der hinterlegten Ansprüche. Die errechnete Daten werden dem Benutzer angezeigt. Der Benutzer kann die gewünschten Vertriebspartner oder Verträge markieren und diese dann endgültig abrechnen. Die kumulierten Zahlungen fließen nun in die Buchhaltung für die Vertriebspartner.

Buchhaltung Vertriebspartner
Die Buchhaltung für jeden Vertriebspartner ermöglicht die Buchung von zusätzlichen Dingen. Vorschüsse, Abschläge, Teilauszahlungen, Negativsalden und Überträge werden automatisch verwaltet und können entsprechend hinterlegt werden. Die Buchung von spezielle Dingen wie: Boni, Einmalprovisionen, Bürokosten, Materialkosten, Leasingsraten können direkt im Dialog erledigt werden und beeinflussen die Auszahlungen und werden auf den Belegen und sauberer Form mit ausgewiesen.

Bereitstellung Abrechnung
Die Abrechnungen werden zum Abschluss erstellt und in den meisten Fällen direkt als PDF in unserem Vertriebspartnerportal zum Download für die Vermittler bereitgestellt. Die Bereitstellung ist dabei direkt in die Software integriert und sehr einfach. Die Empfänger erhalten eine E-Mail oder eine SMS als Benachrichtigung und Hinweis. Natürlich können die Abrechnungen auch direkt gedruckt werden.
Das Layout der Abrechnung kann frei angepasst werden und soll modern und in ihrem Style erfolgen.

