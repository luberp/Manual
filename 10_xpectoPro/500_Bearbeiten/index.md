

## Datensatz loeschen

In der klassischen Menüansicht wird über *Bearbeiten  → Datensatz löschen*  der aktuell ausgewählte  Datensatz (zum Bespiel Kunde, Vertrag, Vermittler, Person, Veranstaltung, Produkt) gelöscht. 

In der modernen Menüansicht kann ein Datensatz über die Registerkarte *Berichte und Massenaktionen*, Gruppe *Bearbeiten* gelöscht werden.

![](http://xpecto.github.io/docs/img/img_1462806622224.png)

Es erscheint folgende Warnmeldung:

![](http://xpecto.github.io/docs/img/img_1420450924589.png)

Bestätigen Sie den Dialog “Wollen Sie den Datensatz … wirklich löschen?” mit *Ja* wird der Datensatz aus der Datenbank gelöscht. 
Es können nur die Datensätze gelöscht werden, auf die noch nicht referenziert wurde. Im Speziellen heißt das, dass zum Bespiel ein Vermittler, der bereits einen Vertrag verkauft hat, ein Kunde, zu dem bereits ein Vertrag erfasst wurde oder ein Vertrag, zu dem bereits Buchungen erfasst worden sind, nicht gelöscht werden können. Der Zweck dieses Menüpunktes ist die zeitnahe Löschung von Datensätzen.

Eine Löschung von bereits referenzierten Datensätzen wird mit folgender Fehlermeldung unterbunden:

![](http://xpecto.github.io/docs/img/img_1420458029242.png)
 


## Datensatz kopieren

Mit der Funktion Datensatz kopieren können Sie Verträge,  Kunden, Vermittler, Personen und Veranstaltungen kopieren. Um einen Datensatz zu kopieren, markieren Sie zuerst den gewünschten Datensatz und wählen dann in der klassischen Menüansicht *Bearbeiten → Datensatz kopieren*. Es wird die nächste freie Nummer vorgeschlagen. Falls Sie intern eine andere Nummerierung  verwenden, können Sie auch hier die nach Ihrer internen geltenden Richtlinie freie Nummer vergeben. 

![](http://xpecto.github.io/docs/img/img_1439214682763.png)

Nachdem Sie die gewünschte neue Nummer eingegeben haben, bestätigen Sie mit *OK*.  
Es ist nicht möglich, zwei Datensätze mit derselben Nummer zu speichern.


## Zu Kampagne hinzufuegen

Kampagnen ermöglichen Massenaktionen wie den Druck oder Mailversand von Schreiben oder Einladungen. Ermöglicht wird dies durch die Kombination aus Listenerstellung und der Nutzung dieser Daten für den Massendruck. 
xpectoPro bietet als Datenquelle für die Kampagnen vordefinierte Verteiler, individuelle Abfragen oder statische Daten (siehe *Bearbeiten → Kampagne*).

Die Funktion *Zu Kampagne hinzufügen* fügt Daten zu einer vorhandenen Kampagne ein. 

Um einen Datensatz zu einer Kampagne hinzuzufügen, muss in dem *Kampagnen und Massendruck*-Dialog im Reiter *Kampagne* die Option *statische Daten* markiert sein.

![](http://xpecto.github.io/docs/img/img_1461658954205.png)

Nachdem Sie die neuen Einstellungen gespeichert haben, markieren Sie den Datensatz, der zur Kampagne hinzugefügt werden soll. Wählen Sie in der klassischen Menüansicht *Bearbeiten → Zu Kampagne* hinzufügen, um zum Beispiel einen Teilnehmer hinzuzufügen.

In der modernen Menüansicht ist die Funktion in der Registerkarte *Berichte und Massenaktionen*, Gruppe *Erstellung* zu finden.

![](http://xpecto.github.io/docs/img/img_1461669901566.png)

Anschließend klicken Sie auf *Start*, um die Kampagne zu starten.


## ID aendern

Über diesen Menüpunkt kann die Vermittler-, Kunden- oder Vertrags-ID geändert werden.  
Um eine ID zu ändern, wählen Sie in der klassischen Menüansicht *Bearbeiten → ID ändern*. 

Sie werden aufgefordert eine Nummer einzugeben. 

![](http://xpecto.github.io/docs/img/img_1421233957681.png)

In der modernen Menüansicht wählen Sie unter Registerkarte *Berichte und Massenaktionen* in der Gruppe *Bearbeiten* die Funktion *Datensatz ID ändern*.

![](http://xpecto.github.io/docs/img/img_1461670050892.png)

Es wird die nächste freie Nummer vorgeschlagen. Falls Sie intern eine andere Nummerierung verwenden, können Sie die nach Ihrer internen geltenden Richtlinie freie Nummer vergeben. Nachdem Sie die gewünschte neue Nummer eingegeben haben, bestätigen Sie mit *OK*. Damit wird die neue ID für den Datensatz gespeichert.


## Aktualisieren

Aktualisieren dient dazu, die Anzeige aufzufrischen. Um Ihre Ansicht zu aktualisieren, wählen Sie in der klassischen Menüansicht *Bearbeiten → Aktualisieren* oder drücken Sie die F5-Taste.


## Abfragen erstellen

xpectoPro bietet einen anwenderfreundlichen Abfrage-Editor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt, eigene Datenbankabfragen bzw. Auswertungen zu erstellen.

In der klassischen Menü-Ansicht erreichen Sie den Abfrage-Editor über den Menüpunkt *Bearbeiten → Abfragen erstellen*.

In der modernen Menü-Ansicht ist die Funktion *Abfragen / Verteiler* unter der Registerkarte *Berichte und Massenaktionen* Gruppe *Bearbeiten.*

![](http://xpecto.github.io/docs/img/img_1461657987778.png)

Klicken Sie auf die Funktion *Abfragen / Verteiler* um den Editor *Abfragen und Listen* zu öffnen.

Nach dem Öffnen des *Abfragen und Liste* Editors wird der Assistent mit einem Bedingungsblock angezeigt, der bereits eine Bedingung enthält. Eine Bedingung ist definiert durch einen Feldnamen (links), einen Bedingungstyp (mitte) und einem vom Anwender einzugebenden Vergleichswert. 

![](http://xpecto.github.io/docs/img/img_1461660884744.png)

Bedingungszeilen sind in Blöcken zusammengefasst. Am oberen Rand eines Blocks wird der verwendete Gruppierungstyp angezeigt. Mögliche Typen sind:

 - jede der Bedingungen trifft zu (AND)  
 - eine oder mehrere Bedingungen treffen zu (OR)
 
![](http://xpecto.github.io/docs/img/img_1461661044973.png)

Über die Schaltfläche “*Feld hinzufügen*” wird einem Block eine Bedingung hinzugefügt. Über die Schaltfläche “*Block hinzufügen*” wird einem Block ein Unterblock hinzugefügt. Auf diese Weise kann für einen Teil der Bedingungen ein anderer Gruppierungstyp verwendet werden.

Die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1461661108624.png) löscht eine Bedingungszeile.

Durch Klick auf den Feldnamen oder den Bedingungstyp kann eine Bedingung angepasst werden. Ein Klick auf den Feldnamen öffnet ein Kontextmenü zur Auswahl des gewünschten Feldnamens. Per Klick auf den Bedingungstyp kann der Typ ausgewählt werden. Folgende Bedingungstypen stehen zur  Verfügung:

|  Bedingungstypen           | 
| ------------- |
|   entspricht einem der folgenden Werte     | 
|enthält|
|    endet mit   | 
|beginnt mit|
|ist leer|
|entspricht keinem der folgenden Werte|
|enthält nicht|
|endet nicht mit |
|beginnt nicht mit|
|ist nicht leer|
|entspricht einem der folgenden Tage|
|ist von - bis|
|ist kleiner/früher oder entspricht folgendem Wert|
|ist größer/später oder entspricht folgendem Wert|
|entspricht keinem der folgenden Tage|
|ist nicht von - bis|

Schließlich werden in den Eingabefeldern die Vergleichswerte der jeweiligen Bedingung eingetragen.

Beispiel: Sie wollen wissen, welche Kunden der Vermittler VP0001 und VP0002 im Zeitraum 01.01.2001 bis 01.04.2016 Verträge des Produkts *TRI1, Top Return Invest I* abgeschlossen haben.
 
Starten Sie den Abfrage-Editor und passen Sie die vorgegebene Bedingungszeile folgendermaßen an: klicken Sie auf den Feldnamen *Vertrags-Nr* wählen im darauffolgenden Kontextmenü das Feld *Vertriebspartner → Betreuer-Nr.* Tragen Sie in das Eingabefeld die Vermittlernummer ein. Sie haben hier die Möglichkeit nach einem Feld zu suchen. 

![](http://xpecto.github.io/docs/img/img_1461661794519.png)

Legen Sie über “*Feld hinzufügen*” zwei weitere Bedingungszeilen an, wählen Sie mit der oben beschriebenen Methode die Felder: *Produkte → Produktname* und *Vertragsdaten → Abschlussdatum* und tragen Sie die entsprechenden Werte in die zugehörigen Eingabefelder ein.

![](http://xpecto.github.io/docs/img/img_1461663211041.png)

Klicken sie nun auf *Weiter*. Auf der nächsten Seite können die Datenbankfelder, die in der Anzeige des Abfrageergebnisses ausgegeben werden sollen, durch Anhaken ausgewählt werden.

![](http://xpecto.github.io/docs/img/img_1461663371382.png)

In diesem Beispiel sind *Bezeichner, Kundennummer, Abschlussdatum, Produkt, Tarif, Vertragsnummer, Betreuernummer, Produktname* ausgewählt.

Klicken sie nun erneut auf *Weiter*, um zur Anzeige des Abfrageergebnisses zu gelangen. In der Ergebnisanzeige wird im oberen Bereich die, anhand der vorher definierten Parameter automatisch generierte Datenbankabfrage angezeigt. Darunter erscheint eine Liste mit dem Ergebnis der Abfrage.

Die dargestellten Datensätze können über Betätigung der entsprechenden Schaltflächen  *CSV*, *SQL* *Excel* und *Kampagne* weitergegeben werden. Ein Klick auf *Excel* oder *CSV* öffnet die ermittelten Daten direkt in Excel und Sie können die Daten dann dort weiterverarbeiten werden.  

![](http://xpecto.github.io/docs/img/img_1461663524234.png)

Die Daten können auch direkt an eine Kampagne übergeben werden. Über die Schaltfläche *Kampagne* kann eine Kampagne gestartet werden (siehe  Handbuch *Bearbeiten → Kampagnen*). 

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461663694281.png) können Sie *Insert Statements erstellen*, Daten in *Importdialog laden* oder die *Aktion abbrechen*.  Die Insert-Operationen werden dann im Editor angezeigt.

Um die Daten zu importieren, klicken Sie auf die Schaltfläche *Daten in Importdialog laden*.

![](http://xpecto.github.io/docs/img/img_1461663786302.png)

Im Importdialog können Sie z.B. Datensätze / Tabellen in der Datenbank importieren (siehe Handbuch *Import/Export → Allgemeiner Import*). 

![](http://xpecto.github.io/docs/img/img_1461664576287.png)

Um Datensätze zu importieren, in denen das Produkt nicht in einer Spalte vorhanden ist, muss das Produkt ausgewählt werden.

Durch Betätigung der Schaltfläche *Vorschau* werden die vorbereitete Daten angezeigt.
Wenn bereits Datensätze mit derselbe ID in der Datenbank vorhanden sind, dann werden diese nur aktualisiert, falls die Checkbox *vorhandene Daten aktualisiert* markiert ist.

Wenn Sie Tabellen aus einer Datei, in der Datenbank importieren wollen, dann klicken Sie auf die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1421152862771.png) neben das Feld Datei, um die zu importierende Datei auszuwählen.

Je nach Dateiformat der zu importierenden Daten müssen die Trennzeichen, sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. 
Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. 
Durch betätigen von *Vorschau* werden die Importdaten als Tabelle angezeigt.
 Um den Import zu starten, klicken Sie auf die Schaltfläche: ![](http://xpecto.github.io/docs/img/img_1421159892128.png).

Nachdem Sie die folgende Meldung mit *OK* bestätigt haben, werden die angezeigten Daten importiert. 

![](http://xpecto.github.io/docs/img/img_1421160002075.png)

Durch Betätigung von ![](http://xpecto.github.io/docs/img/img_1431935009760.png)  wird der Abfrage-Editor beendet. 


## Kampagnen

Kampagnen ermöglichen Massenaktionen wie den Druck oder Mailversand von Schreiben oder Einladungen. Durch die  Kombination aus Listenerstellung und der Nutzung dieser Daten für den Massendruck wird eine große Anzahl von Empfänger erreicht.

In der klassischen Menü-Ansicht erreichen Sie die Maske Kampagnen und Massendruck  über *Bearbeiten → Kampagnen* oder über *Bearbeiten → Abfrage erstellen → Kampagne*. Die Maske „Kampagnen und Massendruck" kann außerdem auch unter *Veranstaltungen → Reiter Allgemein* → Feldgruppe *Aktionen* *Einladungen drucken* (siehe Handbuch *Neu  → Veranstaltungen*) erreicht werden.

In der modernen Menü-Ansicht ist die Maske Kampagnen und Massendruck über Karteireiter *Berichte und Massenaktionen* Gruppe *Erstellung* erreichbar.

![](http://xpecto.github.io/docs/img/img_1461670219898.png)

Um eine neue Kampagne zu starten öffnen Sie die Maske *Kampagnen und Massendruck* und klicken auf die Schaltfläche: ![](http://xpecto.github.io/docs/img/img_1461665467946.png).

Die Maske enthält eine eigene Symbolleiste. Diese dient dazu, um Ihnen die Arbeit zu erleichtern,  damit können Sie einfach ![](http://xpecto.github.io/docs/img/img_1461671943922.png) *Speichern*,  ![](http://xpecto.github.io/docs/img/img_1461671772817.png) *Kampagne neu anlegen*,![](http://xpecto.github.io/docs/img/img_1461577385984.png) *aktuellen Datensatz löschen*,  ![](http://xpecto.github.io/docs/img/img_1461671810290.png)  *Kampagne kopieren*.


Außerdem enthält die  Maske *Kampagnen und Massendruck* die  Reiter *Allgemein* und *Kampagne*. 

Der Reiter *Allgemein* beinhaltet den Namen, die Beschreibung und falls vorhanden die letzte Ausführung der Kampagne.

Unter dem Karteireiter *Kampagne* können die Datenquelle, Ausgaben und Aktionen eingestellt werden.

![](http://xpecto.github.io/docs/img/img_1461673010754.png)

In der Feldgruppe *Datenquelle wählen* ergibt sich die Möglichkeit zwischen *vordefinierter Verteiler*, *individuelle Abfrage*  und *statischen Daten* zu wählen.

*Vordefinierter Verteiler* ist ein spezieller Bericht der eine Abfrage enthält und eine Liste darstellt. Falls die Option *Vordefinierter Verteiler* gewählt ist dann wird die in dem Bericht über Abfrage gesteuerte Daten als Datenquelle eingefügt. Dieser Bericht kann dann mehrmals verwendet werden. Dafür muss der Bericht als *Verteiler für Kampagne* markiert werden. (siehe Handbuch *Extras → Anpassen → Berichte und Adressmuster → Berichte → Kategorien*). 

Über die *individuelle Abfrage* werden die Daten die über die Abfrage ausgeliefert würden in die Kampagne eingefügt (siehe Handbuch *Bearbeiten → Abfragen erstellen*). Durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461674902900.png) wird der Dialog *Abfrage editieren für Kampagne* geöffnet. Falls die Abfrage eine Bearbeitung benötigt können hier die gewünschte Änderungen vorgenommen werden.

Über die Option *statische Daten* wird eine dritte Möglichkeit für die Datenquellen angeboten. Hier können markierte Daten z.B. Teilnehmer über die Funktion *zu Kampagne hinzufügen* (siehe Handbuch *Bearbeiten →  Zu Kampagne hinzufügen*) in die gewünschte Kampagne eingefügt. Dafür muss vorher die Option *statischen Daten* markierte werden und gespeichert.

In der Feldgruppe *Aktion wählen* können Sie die Funktion die für Ihre Kampagne  ausgeführt werden soll, wählen: *Berichte drucken, Provision einfügen, SMS, Datei Upload, Weiteres*.

Beispiel: Es sollen neue Kunden gefunden werden, und zwar aus dem Adressbestand sollen alle potentielle Kunden mit einer E-Mail Adresse, über neue Produkte informiert werden. Schreiben Sie allen Teilnehmer der Kampagne per E-Mail an. Die Schreiben hinterlegen Sie automatisch im Dokumenten-Archiv.

Als erstes erstellen Sie die Abfrage um die Kunden auszuwählen. Starten Sie hier über *Bearbeiten → Abfragen erstellen* der *Abfragen und Listen* Editor. 

![](http://xpecto.github.io/docs/img/img_1461676078337.png)

Nachdem Sie die Abfrage erstellt  und die benötigte Felder ausgewählt haben klicken Sie auf *Weiter*.
Starten Sie eine neue Kampagne über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461676124268.png). 

Es wird eine neue Kampagne mit einem von xpectoPro automatisch generierten Namen angelegt.
In dem Reiter *Allgemein* geben Sie *Informationskampagne* für den Namen und eine optionale Beschreibung für Ihre Kampagne an. Speichern Sie Ihre Änderungen.

In dem Reiter *Kampagne* wählen Sie unter Aktion *Berichte drucken* als Bericht das *Infoschreiben*, das vorher als *Verteiler für Kampagne* markiert würde. Die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461940899447.png) dient dazu um einen anderen Bericht für die Kampagne zu wählen. Dafür wird die Maske *Berichte und Textbausteine* geöffnet. Hier können die Einstellungen für einen anderen Bericht markiert werden (siehe Handbuch *Extras  → Anpassen  →  Berichte und Adressmuster*).

![](http://xpecto.github.io/docs/img/img_1461676474711.png)

Anschließend klicken Sie auf *Start* um die Kampagne zu starten.


## Berichte erzeugen

Als Berichte werden die Ausdrucke bzw. Schreiben bezeichnet, die mit xpectoPro erstellt werden können. Jeder in xpectoPro hinterlegter Bericht hat eine Bezeichnung, ein vordefiniertes Layout und eine Datenbankabfrage zum Befüllen von Platzhaltern. Ein Bericht wird für der markierte Datensatz generiert.

In der klassischen Menü-Ansicht wird ein neuer Bericht generiert über den Menüpunkt  *Bearbeiten → Berichte erzeugen*, über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1429027617646.png) oder falls ein Favorit eingerichtet würde in das Hauptfenster direkt neben das Favoriten-Feld über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461680897090.png) *Druckvorschau /Seitenansicht*.

![](http://xpecto.github.io/docs/img/img_1461680850196.png)

In der modernen Menü-Ansicht generieren Sie einen Bericht in der Registerkarte *Schnellzugriff* Funktion *Vorschau*.

![](http://xpecto.github.io/docs/img/img_1461681103966.png)

Unabhängig von Favoriten und markierter Datensatz kann ein Bericht  über die Registerkarte *Berichte und Massenaktionen* Funktion *Einzelbericht* erzeugt werden.

 ![](http://xpecto.github.io/docs/img/img_1461681719690.png)

Wenn als Favorit eine *Briefvorlage* eingestellt würde, dann wird für jeder markierter Datensatz ein Bericht generiert der die Daten des Datensatzes enthält.

Wie die Berichte als Favoriten angezeigt werden, wird unten beschrieben (siehe unten [Favoriten anzeigen](#id3)).

Da die Berichte über Namen unterschieden werden und in Gruppen verwaltet, müssen zuerst die Berichtengruppe ausgewählt und in dem Berichtfeld werden dann die dazu passende Berichte vorgeschlagen. 

![](http://xpecto.github.io/docs/img/img_1461677534072.png)

Wenn die Felder ausgefüllt sind dann drücken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439381184713.png).

|  Schaltfläche            |    Beschreibung     |  
| ------------- |:-------------| 
|![](http://xpecto.github.io/docs/img/img_1439381184713.png)| Druckvorschau/Seitenansicht|
|![](http://xpecto.github.io/docs/img/img_1439391939484.png)| Bericht in Datei exportieren oder drucken|
|![](http://xpecto.github.io/docs/img/img_1439381119609.png) |Dokumente archivieren ein/aus|
|![](http://xpecto.github.io/docs/img/img_1439381347699.png)  |Bericht bearbeiten. Es kann eine neue Vorlage generiert und bearbeitet werden.|
|![](http://xpecto.github.io/docs/img/img_1439381384906.png)| Filter Fields IDs|

Sie können jeden Bericht den Sie erstellt haben ganz einfach im Editor bearbeiten und verändern. Nutzen Sie dazu die zur Verfügung gestellte Editorleiste.

![](http://xpecto.github.io/docs/img/img_1439389795642.png)

<a id="id3">**Favoriten anzeigen**</a>

xpectoPro bietet an häufig verwendete Berichte als Favoriten-Berichte zu hinterlegen, da sie über diesen Weg schneller erreicht werden können. Dazu muss der Bericht als *Allgemeiner Bericht*  für Favoriten markiert werden. (siehe Handbuch *Extras → Anpassen → Berichte und Adressmuster → Berichte → Reiter Kategorien*).

![](http://xpecto.github.io/docs/img/img_1439387898787.png)

Um ein Bericht direkt in das Hauptfenster zu generieren, wählen Sie dafür den gewünschten Datensatz in der Kunden- oder Vermittleransicht, und klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461681281157.png).

![](http://xpecto.github.io/docs/img/img_1461680747695.png)

Der erstellte Bericht kann nun über die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1439391939484.png) gedruckt werden.


## Erweiterte Suche

Über *Erweiterte Suche* können Sie Kundendaten, Vertriebspartner, Adressen, Veranstaltungen, Produkte suchen.

In der klassischen Menü-Ansicht wird der Suchdialog über *Bearbeiten → Erweiterte Suche* oder über das Symbol  ![](http://xpecto.github.io/docs/img/img_1429027888314.png) in der *Symbolleiste*.

In der modernen Menü-Ansicht kann der Suchdialog über die Registerkarte *Suche* in der Gruppe *Ziele* durch einen Klick auf die einzelne Schaltflächen gestartet werden.

![](http://xpecto.github.io/docs/img/img_1461682359703.png)

 Starten Sie mit der Suche, indem Sie den gesuchten Name in das Suchfeld eingeben.
 
Um nach mehreren Kriterien zu suchen klicken Sie auf die Schaltfläche *Felder einblenden* ![](http://xpecto.github.io/docs/img/img_1461682679587.png), z.B. Suche nach alle Kunden die in Berlin wohnen und einen Vertrag des Produktes TRI1 haben.

![](http://xpecto.github.io/docs/img/img_1461682745019.png)

Sie können durch einen Doppelklick auf einen Eintrag kann aus der Liste heraus den Datensatz geöffnet und bearbeitet werden. 


## Duplikte finden

Unter *Duplikate finden* können Duplikate in der Datenbank gesucht und aufgelöst werden, um die Genauigkeit der Daten zu erhöhen. Duplikate sind identische Datensätze, die entstehen wenn mehrere Benutzer identische Daten eingeben haben.

Über der klassischen Menü-Ansicht werden die Duplikate gefunden wenn Sie im Menü *Bearbeiten* auf *Duplikate finden* klicken. 

In der modernen Menü-Ansicht ist die Funktion *Duplikate finden* in der Registerkarte *Berichte und Massenaktionen* Gruppe *Bearbeiten* zu finden.

![](http://xpecto.github.io/docs/img/img_1461682914699.png)


Es gibt die Möglichkeit nach Duplikaten in Kundendaten, Vertriebspartner und Kontoverbindungen zu suchen.

![](http://xpecto.github.io/docs/img/img_1461682996732.png)

Wählen Sie ein Datenbasis z.B. Kundendaten. Das System listet nach kurzer Wartezeit die gefundenen Duplikate auf und zeigt die Unterschiede der beiden Datensätze an. Sie können nun die entsprechenden Daten verändern oder die zu übernehmenden Datenfelder auswählen. 

![](http://xpecto.github.io/docs/img/img_1461683795875.png)

Über die Schaltfläche *Anzeigen* werden die Stammdaten des Datensatzes z.B. Kunde im Hauptfenster angezeigt. 

Bitte markieren Sie dem Datensatz den Sie behalten möchten.
Mit einem Klick auf ![](http://xpecto.github.io/docs/img/img_1421247414670.png) wird der nicht markierter Datensatz entfernt und der verbleibende Datensatz aktualisiert. Alle Daten die zum alten Kunden gehören wie Verträge, Provisionen und Dokumente werden automatisch auf den neuen Kunden übertragen.


## Stapelbuchungen

xpectoPro enthält eine vollständige und zertifizierte Buchhaltung. Alle Einzahlungen, Forderungen, Dividenden, Gebühren und Auszahlungen werden innerhalb der Buchhaltung für jeden Anleger geführt. Die Buchung erfolgt mit einem vom Anwender vorgegebenen Kontenrahmen, typischerweise SKR03 oder SKR04.
Da die meisten Buchungen automatisch vom System bei bestimmten Aktionen erzeugt werden, ist die genaue Kenntnis des Kontenrahmens für die tägliche Benutzung meist nicht relevant. 

Die *Stapelbuchung*-Maske ermöglicht die manuelle Eingabe, die Änderung und die Suche von Buchungen. Für die Weitergabe der Buchungen und die Revisionssicherheit der Buchhaltung können Sie Buchungen festschreiben und in protokollierter Weise exportieren.

In der klassischen Menü-Ansicht gelangen Sie in die *Stapelbuchung* durch klicken  in Menü *Bearbeiten → Stapelbuchung*.

In der modernen Menü-Ansicht finden Sie die *Stapelbuchung* in der Registerkarte *Buchhaltung* Gruppe *Buchungsdaten.*

![](http://xpecto.github.io/docs/img/img_1461684057429.png) 

Die *Stapelbuchung* kann jeweils für ein bestimmtes Produkt samt seinen Buchungen, geöffnet werden. Sind in der Datenbank mehrere Produkte angelegt, so wird vor dem Öffnen der *Stapelbuchung*-Maske ein Produkt-Auswahl-Dialog angezeigt. Solange die Maske geöffnet ist, können darin nur Buchungsdaten des entsprechenden Produkts / Fonds verwaltet werden.

Die Maske *Stapelbuchung* ist das zentrale Werkzeug zur Verwaltung von Buchungsdaten der Fondsbuchhaltung. Sie ist im wesentlichen in vier Funktionsbereiche untergliedert:
 
 - *Stapel-Erfassung*
 -  *Suchen / Ändern*
 -  *Buchungen festschreiben*
 -  *Buchungen exportieren*

Jeder Funktionsbereich der *Stapelbuchung* definiert sich durch die Verfügbarkeit spezifischer Filter und Buttons zum Durchführen bestimmter Aktionen. Allen vier Funktionsbereichen gemein ist ein Bearbeitungsbereich mit den Feldgruppen: *Buchung bearbeiten, Fremdwährung* und *Verarbeitungsinfos* - zum Anzeigen bzw. Bearbeiten einer Buchung, und eine Buchungsliste. Die jeweiligen von Anwender konfigurierten Filter bestimmen welche Buchungen in der Buchungsliste angezeigt werden. 
 
![](http://xpecto.github.io/docs/img/img_1461685073709.png)

Die Feldgruppe *Buchung bearbeiten* zeigt die Detail-Informationen des aktuell in der Buchungsliste selektierten Buchungssatzes. Sie enthält die Felder *Belegdatum, Konto, Gegenkonto, Betrag, Buchungstext, Belegnummer* sowie optional auszufüllenden (und nicht zur Buchhaltung gehörenden) Felder *Valutadatum, Vertrag, Ust-Kennz.* und *Bemerkung.* Die Pflichtfelder sind gelb hinterlegt. 

Das *Belegdatum* informiert über Kontobewegungen, während das *Valutadatum* das Datum ist, an dem eine Gutschrift oder Belastung wirksam wird. Das *Valutadatum* zeigt den echten Kontostand an. Dieses kann unter Umständen vom *Belegdatum* abweichen. 
Unter *Vertrag* kann eine Vertrags-Nr. erfasst werden, der die selektierte Buchungen zugeordnet werden soll. 
Unter *USt-Kennz.* (Umsatzsteuer-Kennzeichen) kann ein Umsatzsteuer-Satz erfasst werden, der bei Berechnungen verwendet werden soll.  
Unter *Betrag* ist zum eingegebenen Betrag zusätzlich die Währung auszuwählen. Dabei fließen nur Datensätze mit der beim Produkt hinterlegten Währung in die Buchhaltung ein (siehe Handbuch *Produkt → Währung*).
Unter *Bemerkung* können Bearbeiter-Hinweise zu der selektierten Buchungen eingegeben werden.
Unter bestimmten Voraussetzungen (z.B. *Buchungen exportieren* gewählt oder *Buchungen festschreiben*) ist die Feldgruppe *Buchung bearbeiten* in GoBS-Modus (Grundsätze ordnungsmäßiger DV-gestützter Buchführungssysteme). GoBS-Modus ist ein Read-Only-Modus Darstellung, Sie können diese Buchungen nicht ändern.

Der Reiter *Stapel-Erfassung* dient der Ersterfassung von Buchungen. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden alle Buchungen angezeigt, die von dem aktuell angemeldeten Benutzer am selben Tag bereits erfasst wurden. 

![](http://xpecto.github.io/docs/img/img_1461685406019.png)

Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439974064694.png) um Vorlagen für Ihre Buchungssätze anzulegen oder zu bearbeiten.
Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439801023332.png) wird ein neuer Datensatz angelegt. Die Details des Buchungssatzes werden über die Feldgruppe *Buchung bearbeiten* eingegeben.
Die Gültigkeit des eingegebenen Belegdatums und des Betrags wird direkt beim Verlassen des jeweiligen Feldes geprüft. Vor dem Speichern wird außerdem geprüft, ob die Pflichtfelder *Betrag, Belegdatum, Konto, Gegenkonto* und *Buchungstext* befüllt sind. 

![](http://xpecto.github.io/docs/img/img_1439812810573.png)

 Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439804594653.png) wird die Buchung gespeichert. Beim Speichern der Buchung wird automatisch der Erfasser und der Erfassungszeitpunkt in den Buchungsdatensatz eingetragen. Die Buchungsperiode, zu der ein Buchungssatz gehört, richtet sich nach dem Belegdatum, sie wird nicht separat erfasst. Ein hier erfasster Datensatz kann über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439813538430.png) jederzeit wieder gelöscht werden, solange er noch nicht festgeschrieben ist. Festschreiben bedeutet dass eine Buchung dann nur noch durch eine Storno/Korrekturbuchung korrigiert werden kann. Damit werden nachträgliche Manipulationen erschwert.
 
Reiter *Suchen / Ändern* dient der Recherche und ermöglicht das Suchen und Ändern von Buchungen. Die Suchkriterien zum Auffinden der gewünschten Buchungssätze können über verschiedenen Filter wie  *Buchungsperiode, Beteiligung/Vertrag, Erfassung, Kontierung, Festschreibung* konfiguriert werden.

![](http://xpecto.github.io/docs/img/img_1461685262474.png)

Nicht festgeschriebene Buchungen können gelöscht oder geändert werden. Änderungen werden erst durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439804594653.png) gespeichert. Vor dem Speichern werden dieselben Gültigkeitsprüfungen durchlaufen, wie in dem Reiter *Stapel-Erfassung*. 

Bereits festgeschriebene Buchungen (erkennbar durch eingetragene Buchungs-Nr in der Feldgruppe *Verarbeitungsinfos*) können nachträglich nicht mehr verändert werden. Wird eine festgeschriebene Buchung selektiert, so ist der Bearbeitungsbereich in Read-Only-Modus und die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1439813538430.png) ist deaktiviert. Solange die betroffene Buchungsperiode nicht geschlossen ist, kann jedoch über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439816158639.png) eine Storno-Buchung erzeugt werden. Wird die Abfrage "Möchten Sie eine Korrekturbuchung anlegen?" mit *Ja* beantwortet, so wird eine änderbare (da nicht festgeschriebene) Kopie der Original-Buchung in derselben Buchungsperiode angelegt.

Der Reiter *Buchungen festschreiben* dient der Übertragung von Buchungssätze in das Buchungsjournal. 
Im Buchungsjournal werden alle Buchungen eines gewählten Zeitraums tabellarisch aufgelistet. Die Kriterien zur Auswahl der festzuschreibenden Datensätze können über verschiedene Filter konfiguriert werden, wie *Buchungsperiode, Beteiligung/Vertrag, Erfassung, Kontierung*. 

![](http://xpecto.github.io/docs/img/img_1461685459829.png)

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439820973695.png) werden alle aufgelisteten Erfassungen in das Buchungsjournal übertragen und in jeden betroffenen Buchungssatz der Festschreibungs-Zeitpunkt, der ausführende Benutzer und eine fortlaufenden Buchungsnummer eingetragen werden. Die Festschreibung einer einmal in das Journal übertragenen Buchung kann nachträglich nicht mehr aufgehoben werden. Die Buchung kann dann nur noch über *Suchen / Ändern* ![](http://xpecto.github.io/docs/img/img_1439816158639.png) storniert werden.

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1463479213984.png) wird eine Buchungsperiode geschlossen. Eine Buchungsperiode entspricht einem Kalendermonat. In einer bereits geschlossenen Buchungsperiode kann nicht mehr gebucht werden. Um das Buchen in einer geschlossenen Buchungsperiode zu ermöglichen, muss die Periode über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1463479270448.png) wieder geöffnet werden. Das wieder öffnen einer Buchungsperiode hebt jedoch nicht die Festschreibung der Buchungen in dieser Periode auf.
Um eine Übersicht über die schon geschlossene und geöffnete Buchungsperioden zu haben,  klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439975955612.png) - *Historie zum öffnen und schließen von Buchungsperioden*.

Der Reiter *Buchungen exportieren* dient der Übergabe von Buchungssätze an das Buchhaltungssystem des Fonds bzw. eines Steuerberaters. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden nur Buchungen angezeigt, die bereits festgeschrieben sind. Dadurch ist sichergestellt, dass keine Buchungssätze die sich noch nicht im Buchungsjournal befinden, an externe Buchhaltungssysteme übergeben werden können. 

![](http://xpecto.github.io/docs/img/img_1461685921010.png)

Nach dem Aufruf der Maske *Stapelbuchung* ist der Radiobutton in der Feldgruppe *nicht exportiert* aktiv. Dadurch werden nur Buchungssätze exportiert, die vorher noch nicht exportiert wurden. Soll ein bereits erfolgter Buchungsexport wiederholt werden so muss der Filter *Exportiert* dementsprechend angepasst werden. 
Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439892039334.png) wird eine Datei im CSV-Format erzeugt, die die aufgelisteten Buchungssätze enthält. Dabei wird automatisch der Exportzeitpunkt und der auszuführende Benutzer in die betroffenen Buchungsdatensätze eingetragen. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439894313567.png) wird dieselbe Export-Datei erzeugt, jedoch ohne Informationen in den Buchungsdatensatz einzutragen.

Die Reihenfolge der Bearbeitungsschritte in der Stapelbuchung ist: 1. Erfassen, 2. Festschreiben, 3. Schließen, 4. Exportieren.


## Beteiligungs Vertragsbuchungen

Die Funktion *Beteiligungs-/Vertragsbuchungen* ermöglicht die manuelle Eingabe, Änderung und Suchen von  Buchungen für einen Vertrag oder Beteiligung.

In den klassischen Menü-Ansicht klicken Sie unter Menü *Bearbeiten → Beteiligungs-/Vertragsbuchungen* um eine neue Buchung für einen Vertrag anzulegen.

In der modernen Menü-Ansicht wird eine neue Buchung angelegt in der Registerkarte *Buchhaltung* Gruppe *Buchungdaten* Funktion *Beteiligungs-Vetragsbuchungen*.

![](http://xpecto.github.io/docs/img/img_1461686191068.png)

Starten Sie die Funktion *Beteiligungs-/Vertragsbuchungen*. Falls Sie in dem Vertragsansicht noch kein Vertrag oder Beteiligung (mehr zu [Beteiligung](#id3) wird unten beschrieben) ausgewählt ist, werden Sie aufgefordert einen Vertrag auszuwählen.

![](http://xpecto.github.io/docs/img/img_1439988459598.png)

Genau wie bei der Stapelerfassung, haben Sie die Möglichkeit unter dem Reiter *Stapel-Erfassung* eine Ersterfassung von Buchungen. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden alle Buchungen angezeigt, die von dem aktuell angemeldeten Benutzer am selben Tag bereits erfasst wurden.

![](http://xpecto.github.io/docs/img/img_1461686685179.png)

Falls Sie einen anderen Vertrag für die Buchung wünschen, dann klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439992255614.png). 
In dem folgenden Dialog können Sie dann einen anderen Vertrag für die Buchung wählen:

![](http://xpecto.github.io/docs/img/img_1461686722405.png)

Der Reiter *Suchen / Ändern* dient der Recherche und ermöglicht das Suchen und Ändern von Buchungen. Da der Filter *Beteiligung/Vertag* für den ausgewählten Vertrag eingestellt würde, können Sie hier, eine neue Buchung für den ausgewählten Vertrag anlegen.  

![](http://xpecto.github.io/docs/img/img_1461687440018.png)

Sichern Sie Ihre Änderungen durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439804594653.png). 

<a id="id3">**Beteiligungen**</a>

Mit xpectoPro ergibt sich die Möglichkeit in mehrere Produkte zu investieren. Durch die Beteiligungen an einen Produkt erwerben die Anleger Anteile an einen Produkt. Ein Kunde, der in verschiedene Produkte investiert möchte, hat dann mehrere Verträge mit unterschiedliche Beteiligungen. 
Eine Beteiligung an einen Produkt wird in dem Dialog *neuen Vertrag erstellen* (siehe Handbuch *Datei → Neu → Vertrag*) festgelegt.

Beteiligungen werden in dem Kundensicht unter Kunde, mit der Symbol ![](http://xpecto.github.io/docs/img/img_1461687665304.png), dargestellt.  

Klicken Sie auf eine Beteiligung um in die Eingabemaske der Beteiligung zu gelangen.

![](http://xpecto.github.io/docs/img/img_1461687574081.png)

Unter dem Reiter *Allgemein* erhalten Sie eine Vertragsübersicht. Das sind alle Verträge des Kundes die an dieses Produkt beteiligt sind.

Unter dem Reiter *Eigenschaften* können weitere Informationen wie Daten, Bemerkungen und vordefinierte Eigenschaften zur Beteiligung erfasst werden.

 Der Reiter *Werte* dient der Zinsberechnung und dient dazu manuell für eine Kategorie die Verbuchungsvorschriften zu definieren siehe (Handbuch *Neu → Produkte → Wertarten*).
 
xpectoPro bietet eine Offene Posten Buchhaltung, die überprüft ob die Forderungen bereit beglichen wurden. Unter dem Reiter *OPOS* wird die OPOS-Liste angezeigt. Eine OPOS-Liste ist die Liste aller offenen Rechnungen. 

Der Reiter *Buchungsdaten* zeigt eine Übersicht der Buchungsdaten die den Vertrag betreffen.

Auf dem Reiter *Ereignisse* werden wichtige Ereignisse zum aktuell ausgewählten Beteiligung festgehalten. 
Der Reiter *Salden* beinhaltet eine Saldenkonfiguration und eine Summen und Salden Liste. Die hier hinterlegten Konten beziehen sich auf die unter Produkt vorkonfigurierten Salden.

![](http://xpecto.github.io/docs/img/img_1461688325074.png)

In der *Summen und Salden* Liste werden die Inhalte der bebuchten Konten mit jeweiligen Summen, tabellarisch dargestellt.

Die einzelnen Spalten sind:

|Spalte| Beschreibung|
|----|----|
|Konto |interne Kontonummer|
|Bezeichnung|Name des Kontos|
|Eröffnungsbilanz|Saldo zum Jahresbeginn, Summe der Bewegungen auf dem Konto|
|Monat S / H |Veränderungen im betrachteten Monat|
|Kum. S / H |Veränderungen vom Beginn des Jahres bis einschließlich des betrachteten Monats|
|Saldo|Saldo zum Ende des betrachteten Monats|

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461688384792.png) können Sie sehen welche Buchungen zum Saldo bzw. zum Konto gemacht wurden.

Unter dem Reiter *Konten-Verwendung* können die Bankkonten (siehe Kunden → Adressen → Kontoverbindungen) für unterschiedliche Verwendungszwecke eingesetzt.

Unter dem Reiter *Handelsregister* wird der Handelsregister Eintrag der Beteiligung festgehalten. 
Der Reiter Handelsregister ermöglicht bestimmte Informationen über die im Handelsregister eingetragenen Unternehmen oder am Geschäftsleben beteiligten Personen aufzunehmen.


Unter der Reiter *Dauervollmachten* können Sie eine Stellvertretung für eine bestimmte Person anlegen. 





## Vertrag uebertragen

Die Funktion *Vertrag übertragen* dient der Übertragung der Vertragsdaten auf einen anderen Kunde. 

Um einen bestehenden Vertrag zu übertragenen wählen Sie in der klassischen Menü-Ansicht Menü *Bearbeiten →  Vertrag übertragen*. 

In der modernen Menü-Ansicht wählen Sie den Karteireiter *Berichte und Massenaktionen* Gruppe *Bearbeiten* Funktion *Vertrag übertragen*.

 ![](http://xpecto.github.io/docs/img/img_1461156880109.png) 
 
Um die Übertragung zu starten muss zuerst ein Vertrag ausgewählt werden, dann klicken Sie auf die Funktio *Vertrag übertragen*.

Es wird der  Dialog *Übertragung* angezeigt. Der Dialog bietet Ihnen die Möglichkeit eine Übertragung durchzuführen oder einen Vertrag zu beenden. 
 
![](http://xpecto.github.io/docs/img/img_1461689330179.png)

Nachdem Sie die Parameter für die Übertragung eingegeben haben, klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461745086541.png) um den Nachfolger für den Vertrag einzutragen. 

Es eröffnet sich hier der Dialog *Kunden auswählen*. Der Dialog  bietet die Möglichkeit über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461745563222.png) die erweiterte Suchfelder anzuzeigen. 


![](http://xpecto.github.io/docs/img/img_1461745295229.png)

Falls der Kunde noch nicht angelegt wurde, können Sie in dem Dialog durch einen Klick ![](http://xpecto.github.io/docs/img/img_1461745391144.png) auf das Symbol  eine neue Person anzulegen.

Durch einen Doppelklick auf den gesuchten Kunde wird der Dialog Kunden auswählen geschlossen und der Kunde ausgewählt und als Nachfolger eingefügt. 

![](http://xpecto.github.io/docs/img/img_1461746072363.png)

Durch einen Klick auf die Schaltfläche *Übertragung durchführen* werden Sie dann aufgefordert einen Umbuchungs-Vorschrift zu wählen.

![](http://xpecto.github.io/docs/img/img_1443173762535.png)

Nachdem der Übertrag durchgeführt würde, wird der Vertragsstatus automatisch in übertragen, geändert, und der Vertrag wird bei Nachfolger angezeigt.

![](http://xpecto.github.io/docs/img/img_1461746349219.png)

## Wiedervorlage Liste

Die *Wiedervorlage Liste* befindet sich im Hauptfenster und dient der Übersicht aller fälligen Wiedervorlagen. So können Sie die Liste nach Fälligkeitsdatum abarbeiten.
Über die Funktion *Wiedervorlage Liste* wird die Anzeige der *Wiedervorlage Liste* im Hauptfenster ein- oder ausgeschaltet.

![](http://xpecto.github.io/docs/img/img_1461748772668.png)

Durch einen Doppelklick auf eine Wiedervorlage in der *Wiedervorlage Liste* wird der entsprechende Kunde, Vertrag, Vermittler, Personen oder Veranstaltung geladen und die Details der Wiedervorlage werden angezeigt.  Weitere Möglichkeiten zum Bearbeiten der Wiedervorlagen werden unter Handbuch *Datei → Neu → Wiedervorlage Prozess* beschrieben.

![](http://xpecto.github.io/docs/img/img_1461750025416.png)

Der unter der *Wiedervorlage Liste* eingebauten Filter dient zum Sortieren der Liste. Nachdem Sie einen anderen Kriterium für Ihre Anzeige ausgewählt haben, klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1461750078718.png) um die Daten neu laden.

Die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439994083070.png) - *Wiedervorlage Historie anzeigen*, zeigt Ihnen der Verlauf des ausgewählten Prozesses.

## Wiedervorlage Seitenleiste

Über diese Funktion wird die Anzeige der Wiedervorlage Seitenleiste im Hauptfenster ein- oder ausgeschaltet. Die Wiedervorlage Seitenleiste zeigt die Liste der Wiedervorlagen für einen Kunde, Vertrag, Vermittler, Person oder Veranstaltung. 
Um die Wiedervorlage Seitenleiste zu aktivieren, wählen Sie z.B. einen Vertrag, und dann klicken Sie unter Menü *Bearbeiten* auf *Wiedervorlage Seitenleiste*. 


## Wiedervorlage Steuerung

Der Dialog *Wiedervorlage Steuerung* dient dazu für einen Prozess mit einem bestimmten Prozessschritt eine gewünschte Aktion für mehrere Wiedervorlagen zu wählen und durchzuführen.

In der klassischen Menü-Ansicht wählen Sie unter *Bearbeiten → Wiedervorlage Steuerung* um den *Wiedervorlage Steuerung* Dialog zu öffnen. 

In der modernen Menü-Ansicht kann der Dialog *Wiedervorlage Steuerung* in der Registerkarte *Berichte und Massenaktionen* Gruppe *Erstellung* mit einem Klick auf die Funktion *Prozess-Steuerung* geöffnet werden.

![](http://xpecto.github.io/docs/img/img_1461142467369.png)

Welche Einstellungen notwendig sind um einen Prozess zu starten und weitere Möglichkeiten zum Bearbeiten der Wiedervorlagen werden unter Handbuch *Datei → Neu → Wiedervorlage Prozess* beschrieben.


![](http://xpecto.github.io/docs/img/img_1461749682825.png)

Durch drucken auf die Schaltfläche*Start* wird die ausgewählte Aktion für die Wiedervorlagen ausgeführt. 

