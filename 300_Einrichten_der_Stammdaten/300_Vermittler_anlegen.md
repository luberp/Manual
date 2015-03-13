
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

Auf den Karteireitern _Zusatzdaten_ und _Eigenschaften_ werden zusätzliche Infos wie Adressherkunft oder Bemerkungen zum Vermittler festgehalten.
