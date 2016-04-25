

## Datensatz loeschen

In der klassischen Menü-Ansicht wird über *Bearbeiten  → Datensatz löschen*  der aktuell ausgewählte  Datensatz (z.B. Kunde, Vertrag, Vermittler, Interessent) gelöscht. 

In der modernen Menü-Ansicht kann ein Datensatz gelöscht über die Registerkarte *Berichte und Massenaktionen* Gruppe *Bearbeiten*.

![](http://xpecto.github.io/docs/img/img_1461583732465.png)

Nach Bestätigung der Warnmeldung:

![](http://xpecto.github.io/docs/img/img_1420450924589.png)

“Wollen Sie den Datensatz … wirklich löschen?” mit *Ja* wird der Datensatz aus der Datenbank gelöscht. 
Es können nur die Datensätze gelöscht werden, auf die noch nicht referenziert wurde. Im Speziellen heißt dies z.B. dass ein Vermittler, der bereits einen Vertrag verkauft hat, ein Kunde, zu dem bereits ein Vertrag erfasst ist, oder ein Vertrag, zu dem bereits Buchungen erfasst sind, nicht gelöscht werden können. Der Zweck dieses Menüpunktes ist die zeitnahe Löschung von Datensätzen.

Eine Löschung von bereits referenzierten Datensätzen wird mit folgender Fehlermeldung unterbunden:

![](http://xpecto.github.io/docs/img/img_1420458029242.png)

## Datensatz kopieren

Mit der Funktion Datensatz kopieren können Sie Verträge,  Kunden, Vermittler, Personen und Veranstaltungen kopieren. Um einen Datensatz zu kopieren markieren Sie zuerst den gewünschten Datensatz und dann wählen Sie unter Menüleiste *Bearbeiten → Datensatz kopieren*. Es wird die nächste freie Nummer vorgeschlagen, wenn Sie nicht damit einverstanden sind dann vergeben Sie nach Ihrer internen Richtlinien eine freie Nummer. 

![](http://xpecto.github.io/docs/img/img_1439214682763.png)

Nachdem Sie die gewünschte neue Nummer eingegeben haben, bestätigen Sie mit *OK*.  
Es ist nicht möglich, zwei Datensätze  mit demselben Nummer zu speichern.



## Zu Kampagne hinzufuegen



## ID aendern

Über diesen Menüpunkt kann die Vermittler-, Kunden- oder Vertrags-ID geändert werden.  
Um eine ID zu ändern wählen Sie das Menü *Bearbeiten → ID ändern*. Sie werden aufgefordert eine Nummer einzugeben. 

![](http://xpecto.github.io/docs/img/img_1421233957681.png)

Es wird die nächste freie Nummer vorgeschlagen, wenn Sie nicht damit einverstanden sind dann vergeben Sie nach Ihrer internen Richtlinien eine freie Nummer. Nachdem Sie die gewünschte neue Nummer eingegeben haben, bestätigen Sie mit *OK*. Damit wird die neue ID für den Datensatz gespeichert.


## Aktualisieren

Aktualisieren dient dazu immer die zuletzt gespeicherte Datensätze angezeigt zu bekommen. Um Ihre Daten zu aktualisieren wählen Sie in der Menüleiste *Bearbeiten → Aktualisieren* oder drücken Sie auf die F5-Taste.

## Abfragen erstellen

xpectoPro bietet einen anwenderfreundlichen Abfrage-Editor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt, eigene Datenbankabfragen bzw. Auswertungen zu erstellen.
Sie erreichen den Abfrage-Editor über den Menüpunkt *Bearbeiten → Abfragen erstellen*.

Nach dem öffnen des *Abfragen und Liste* Editors wird der Bedingungsassistent mit einem Bedingungsblock angezeigt, der bereits eine Bedingung enthält. Eine Bedingung ist definiert durch einen Feldnamen (links), einen Bedingungstyp (mitte) und einem vom Anwender einzugebende Vergleichswert. 

![](http://xpecto.github.io/docs/img/img_1439279198546.png)

Bedingungszeilen sind in Blöcken zusammengefasst. Am oberen Rand eines Blocks wird der verwendete Gruppierungstyp angezeigt. Mögliche Typen sind:

 - jede der Bedingungen trifft zu (AND)  
 - eine oder mehrere Bedingungen treffen zu (OR)
 
![](http://xpecto.github.io/docs/img/img_1439278901176.png)

Über die Schaltfläche “*Feld hinzufügen*” wird einem Block eine Bedingung hinzugefügt. Über die Schaltfläche “*Block hinzufügen*” wird einem Block ein Unterblock hinzugefügt. Auf diese Weise kann für einen Teil der Bedingungen ein anderer Gruppierungstyp verwendet werden.

Die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1419329462773.png) löscht eine Bedingungszeile oder einen Block.

Durch Klick auf den Feldnamen oder den Bedingungstyp kann eine Bedingung angepasst werden. Ein Klick auf der Feldnamen öffnet ein Kontextmenü zur Auswahl des gewünschten Feldnamens. Per Klick auf den Bedingungstyp kann der Typ ausgewählt werden. Folgende Bedingungstypen stehen zur  Verfügung:

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

Beispiel: Sie wollen wissen, welche Kunden des Vermittlers VP0001 im Zeitraum 01.12.2014 bis 01.01.2015 Verträge des Produkts *TRI1, Top Return Invest I* abgeschlossen hat.
 
Starten Sie den Abfrage-Editor und passen Sie die vorgegebene Bedingungszeile folgendermaßen an: klicken Sie auf den Feldnamen *Vertrags-Nr* und wählen im darauf folgenden Kontextmenü das Feld *Vertriebspartner → Betreuer-Nr.* Tragen Sie in das Eingabefeld die Vermittlernummer ein.

![](http://xpecto.github.io/docs/img/img_1431932441285.png)

Legen Sie über “*Feld hinzufügen*” zwei weitere Bedingungszeilen an, wählen Sie mit der oben beschriebenen Methode die Felder: *Produkte → Produktname* und *Vertragsdaten → Abschlussdatum* und tragen Sie die entsprechenden Werte in die zugehörigen Eingabefelder ein.

Klicken sie nun auf *Weiter*. Auf der nächsten Seite können die Datenbankfelder, die in der Anzeige des Abfrageergebnisses ausgegeben werden sollen, durch anhaken ausgewählt werden.

![](http://xpecto.github.io/docs/img/img_1431933240955.png)

In diesem Beispiel sind *Bezeichner, Kundennummer, Abschlussdatum, Produkt, Tarif, Vertragsnummer, Betreuernummer, Produktname* ausgewählt.

Klicken sie nun erneut auf *Weiter*, um zur Anzeige des Abfrageergebnisses zu gelangen. In der Ergebnisanzeige wird im oberen Bereich die anhand der vorher definierten Parameter automatisch generierte Datenbankabfrage angezeigt. Darunter erscheint eine Liste mit dem Ergebnis der Abfrage.

![](http://xpecto.github.io/docs/img/img_1439281607237.png)

Die dargestellten Datensätze können über Betätigung der entsprechenden Schaltflächen  *CSV*, *SQL* oder *Excel* weitergegeben werden. Ein Klick auf *Excel* oder *CSV* öffnet die ermittelten Daten direkt in Excel und Sie können die Daten dann dort weiterverarbeiten.  

Die Daten können auch direkt an eine Kampagne übergeben werden. Über die Schaltfläche *Kampagne* kann eine Kampagne gestartet werden (siehe  Menüleiste *Bearbeiten → Kampagnen*). 

Über die *SQL* Schaltfläche können Sie *Insert Statements erstellen*, Daten in *Importdialog laden* oder die *Aktion abbrechen*. 

![](http://xpecto.github.io/docs/img/img_1431933091869.png)

In dem Importdialog können Sie z.B. Datensätze importieren, Tabellen importieren in der Datenbank (siehe *Import/Export → Allgemeiner Import*). 

![](http://xpecto.github.io/docs/img/img_1439282833536.png)

Um Datensätze zu importieren, wählen Sie das Produkt aus, zu dem die Datensätze importiert werden sollen  falls der Produkt nicht in eine Spalte enthalten ist. 

Wenn bereits Datensätze mit derselbe ID in der Datenbank vorhanden sind, dann werden diese nicht aktualisiert nur wenn die Checkbox *vorhandene Daten aktualisiert* markiert ist.

Wenn Sie Tabellen aus einer Datei, in der Datenbank importieren wollen, dann klicken Sie auf die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1421152862771.png) um die zu importierende Datei auszuwählen.

Je nach Dateiformat der zu importierenden Daten müssen die Trennzeichen sowie das Textzeichen ausgewählt werden. Die Vorbelegung der Auswahlfelder entspricht dem Import einer Datei im CSV Format. 
Wahlweise können die Kopfzeile sowie die leeren Spalten angezeigt werden. 
Durch betätigen von *Vorschau* werden die Importdaten als Tabelle angezeigt.
 Um den Import zu starten klicken Sie auf die Schaltfläche: ![](http://xpecto.github.io/docs/img/img_1421159892128.png).

Nachdem Sie die folgende Meldung mit *OK* bestätigt haben sind die angezeigten Daten importiert. 

![](http://xpecto.github.io/docs/img/img_1421160002075.png)

Durch Betätigung von ![](http://xpecto.github.io/docs/img/img_1431935009760.png)  wird der Abfrage-Editor beendet.


## Kampagnen

Kampagnen ermöglichen Massenaktionen wie den Druck oder Mailversand von Schreiben oder Einladungen, durch die  Kombination aus Listenerstellung und der Nutzung dieser Daten für den Massendruck.

Sie können die Maske „Kampagnen und Massendruck"  über *Bearbeiten → Kampagnen* oder über *Bearbeiten → Abfrage erstellen → Kampagne* erreichen. Die Maske „Kampagnen und Massendruck" kann auch unter *Veranstaltungen → Allgemein* → Feldgruppe *Massendruck* erreicht werden.

![](http://xpecto.github.io/docs/img/img_1439291391925.png)

Um eine neue Kampagne anzulegen klicken Sie in der Maske *Kampagnen und Massendruck* auf die Schaltfläche: ![](http://xpecto.github.io/docs/img/img_1421833044056.png).

Auf der linke Seite wird eine Übersicht der bereits bestehenden Kampagnen dargestellt.
![](http://xpecto.github.io/docs/img/img_1434112012527.png)

Auf der rechten Seite in der Eingabemaske stehen die Reiter *Allgemein* und *Kampagne*.

Der Reiter *Allgemein* beinhaltet den Namen, die Beschreibung und falls vorhanden die letzte Ausführung der Kampagne.

Der Karteireiter *Kampagne* ist in mehrere Feldgruppen unterteilt.

![](http://xpecto.github.io/docs/img/img_1426689870428.png)

In der Feldgruppe *Datenquelle wählen* ergibt sich die Möglichkeit zwischen *vordefinierter Verteiler* und *individuelle Abfrage* zu wählen.

*Vordefinierter Verteiler* ist ein spezieller Bericht der als Verteiler für Kampagnen ausgewählt würde. Dafür muss der Bericht als *Verteiler für Kampagne* markiert werden. (siehe *Extras → Anpassen → Berichte und Adressmuster → Berichte → Kategorien*). 

![](http://xpecto.github.io/docs/img/img_1439293172987.png)

Die *individuelle Abfrage* gibt Ihnen die Möglichkeit eine schon erstellte Abfrage (siehe *Bearbeiten → Abfragen erstellen → Kampagne*), zu bearbeiten. 

Um eine individuelle Abfrage zu bearbeiten klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1435065913280.png). Es öffnet sich der Dialog *Abfrage editieren für Kampagne.*

![](http://xpecto.github.io/docs/img/img_1439298144966.png)

Hier können Sie die schon hinterlegte Abfrage in dem Dialog *Abfrage editieren für Kampagne* bearbeiten und an Ihre Kampagne anpassen. 
Wenn Sie aber keine Abfrage hinterlegt haben, dann bietet sich hier die Möglichkeit vorher eine Abfrage in den Dialog „Abfragen und Listen" zu erstellen (siehe *Bearbeiten → Abfragen erstellen*).  Durch die Betätigung von der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1433864762504.png), werden Sie direkt zu den *Kampagnen und Massendruck* Dialog weitergeleitet.

Falls die Abfrage mehrere Gruppen liefert, werden die in die Feldgruppe *Gruppe von Daten für Aktionen* angezeigt. Sie können hier die gewünschte Gruppe für Ihre Kampagne markieren.

![](http://xpecto.github.io/docs/img/img_1439300061171.png)

Feldgruppe *Auswahl der Empfänger* bietet die Möglichkeit die Datensätze zu filtern.

In der Feldgruppe *Aktion wählen* können Sie die Funktion die für Ihre Kampagne  ausgeführt werden soll, wählen: Berichte drucken, Provision einfügen, SMS, Datei Upload, Weiteres.

![](http://xpecto.github.io/docs/img/img_1439300124949.png)

Beispiel: Es sollen neue Kunden gefunden werden, und zwar aus dem Adressbestand sollen alle potentielle Kunden mit einer E-Mail Adresse, über neue Produkte informiert werden. Schreiben Sie allen Teilnehmer der Kampagne per E-Mail an. Die Schreiben hinterlegen Sie automatisch im Dokumenten-Archiv.

Als erstes erstellen Sie die Abfrage um die Kunden auszuwählen. Starten Sie hier über Bearbeiten → Abfragen erstellen der *Abfragen und Listen* Editor. 

![](http://xpecto.github.io/docs/img/img_1439370565761.png)

Nachdem Sie die Abfrage erstellt  und die benötigte Felder ausgewählt haben,  dann klicken Sie auf *Weiter*.

Starten Sie eine neue Kampagne über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1433864762504.png). 

Es wird eine neue Kampagne angelegt mit einem von xpectoPro automatisch generierten Namen angelegt.
In dem Reiter Allgemein geben Sie *Informationskampagne* für den Namen und eine optionale Beschreibung für Ihre Kampagne an. Speichern Sie Ihre Änderungen.

In dem Reiter *Kampagne* wählen Sie unter Aktion Berichte drucken als Bericht die Infoschreiben (siehe *Extras → Anpassen → Berichte und Adressmuster*), 

![](http://xpecto.github.io/docs/img/img_1439374542325.png)

Anschließend klicken Sie auf *Start* um die Kampagne zu starten.


## Berichte erzeugen

Als Berichte werden die Ausdrucke bzw. Schreiben bezeichnet, die mit xpectoPro erstellt werden können. Jeder in xpectoPro hinterlegte Bericht hat eine Bezeichnung, ein vordefiniertes Layout und eine Datenbankabfrage zum Befüllen von Platzhaltern. Unter *Bericht erzeugen* wird ein neuer Bericht generiert. 

Über den Menüpunkt  *Bearbeiten → Berichte erzeugen*, über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1429027617646.png) oder direkt in das Hauptfenster (siehe unten Favoriten), wird  die *Berichterstellung* Fenster aufgerufen. 

Da die Berichte über Namen unterschieden werden und in Gruppen verwaltet, müssen zuerst die Berichtengruppe ausgewählt und in dem Berichtfeld werden die dazu passende Berichte vorgeschlagen. 

![](http://xpecto.github.io/docs/img/img_1439392757622.png)

Wenn die Felder ausgefüllt sind dann drücken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439381184713.png).

|  Schaltfläche            |    Beschreibung     |  
| ------------- |:-------------| 
|![](http://xpecto.github.io/docs/img/img_1439381184713.png)| Druckvorschau/Seitenansicht|
|![](http://xpecto.github.io/docs/img/img_1439391939484.png)| Bericht in Datei exportieren oder drucken|
|![](http://xpecto.github.io/docs/img/img_1439381119609.png) |Dokumente archivieren ein/aus|
|![](http://xpecto.github.io/docs/img/img_1439381347699.png)  |Bericht bearbeiten. Es kann eine neue Vorlage generiert und bearbeitet werden.|
|![](http://xpecto.github.io/docs/img/img_1439381384906.png)| Filter Fields IDs|

Sie können jeden Bericht, den Sie erstellt haben, ganz einfach im Editor bearbeiten und
verändern. Nutzen Sie dazu die zur Verfügung gestellte Editorleiste.

![](http://xpecto.github.io/docs/img/img_1439389795642.png)

**Favoriten**
Es bietet sich an, häufig verwendete Berichte als Favoriten-Berichte zu hinterlegen, da sie über diesen Weg schneller erreicht werden können. Dazu muss der Bericht als *Allgemeiner Bericht*  für Favoriten markiert werden. (siehe *Extras → Anpassen → Berichte und Adressmuster → Berichte → Kategorien*).

![](http://xpecto.github.io/docs/img/img_1439387898787.png)

Um ein Bericht direkt in das Hauptfenster zu generieren, wählen Sie dazu den gewünschten Datensatz in der Kunden- oder Vermittleransicht, und klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439381184713.png).

![](http://xpecto.github.io/docs/img/img_1439388275964.png)

Der erstellte Bericht kann nun über die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1439391939484.png) gedruckt werden.

## Erweiterte Suche

Über *Erweiterte Suche* können Sie Kundendaten, Vertriebspartner, Adressen, Veranstaltungen.
Sie erreichen den Suchdialog über *Bearbeiten → Erweiterte Suche* oder über das Symbol  ![](http://xpecto.github.io/docs/img/img_1429027888314.png) in der *Symbol- und Funktionsleiste*.

![](http://xpecto.github.io/docs/img/img_1437999785393.png)
 
 Starten Sie mit der Suche, indem Sie den gesuchten Name in das Suchfeld eingeben.
Um nach mehreren Kriterien zu suchen klicken Sie auf die Schaltfläche *Felder einblenden* ![](http://xpecto.github.io/docs/img/img_1438066313704.png), z.B. Suche nach alle Kunden die in Berlin wohnen und einen Vertrag des Produktes TRI1 haben.

![](http://xpecto.github.io/docs/img/img_1437999710660.png)

Sie können durch einen Doppelklick aus der Liste heraus den Datensatz öffnen und bearbeiten. 


## Duplikte finden

xpectoPro bietet Ihnen die Auflösung der Duplikate. Unter *Duplikate finden* können Duplikate in der Datenbank gesucht und aufgelöst werden, um die Genauigkeit der Daten zu erhöhen. Duplikate sind identische Datensätze, die entstehen wenn mehrere Benutzer Daten eingeben.
Es gibt die Möglichkeit nach Duplikaten in Kundendaten, Vertriebspartner und Kontoverbindungen zu suchen.
Um das Werkzeug zu benutzen wählen Sie *Bearbeiten → Duplikate finden*. 

![](http://xpecto.github.io/docs/img/img_1421242451087.png)

Sie wählen nun die Datenbasis wie z.B. Kundendaten. Das System listet nach kurzer Wartezeit die gefundenen Duplikate auf und zeigt die Unterschiede der beiden Datensätze an. Sie können nun die entsprechenden Daten verändern oder die zu übernehmenden Datenfelder auswählen. 

![](http://xpecto.github.io/docs/img/img_1439546407890.png)

Bitte klicken Sie auf die jeweiligen Werte, die in den neuen Datensatz übernehmen werden sollen.
Mit einem Klick auf ![](http://xpecto.github.io/docs/img/img_1421247414670.png) wird ein Datensatz entfernt und der verbleibende Datensatz aktualisiert. Alle Daten die zum alten Kunden gehören wie Verträge, Provisionen und Dokumente werden automatisch auf den neuen Kunden übertragen.


## Stapelbuchungen

xpectoPro enthält eine vollständige, zertifizierte Buchhaltung. Alle Einzahlungen, Forderungen, Dividenden, Gebühren und Auszahlungen werden innerhalb der Buchhaltung für jeden Anleger geführt. Die Buchung erfolgt mit einem vom Anwender vorgegebenen Kontenrahmen, typischerweise SKR03 oder SKR04.
Da die meisten Buchungen automatisch vom System bei bestimmten Aktionen erzeugt werden, ist die genaue Kenntnis des Kontenrahmens für die tägliche Benutzung meist nicht relevant. 

In bestimmten Fällen ist es jedoch sinnvoll direkt Buchungen anzulegen oder zu ändern. Für diese manuellen Buchungen und Korrekturen dient der Stapelbuchung.

Sie erreichen die Stapelbuchung im Menü *Bearbeiten*. Der Dialog ermöglicht die Eingabe, die Änderung und die Suche von Buchungen. Für die Weitergabe der Buchungen und die Revisionssicherheit der Buchhaltung können Sie Buchungen festschreiben und in protokollierter Weise exportieren.

Der Dialog *Stapelbuchung* ist das zentrale Werkzeug zur Verwaltung von Buchungsdaten der Fondsbuchhaltung. Sie ist im wesentlichen in vier Funktionsbereiche untergliedert:
 
 - Stapel-Erfassung
 -  Suchen / Ändern
 -  Buchungen festschreiben
 -  Buchungen exportieren
 
Die Stapelbuchung kann jeweils für ein bestimmtes Produkt samt seinen Buchungen, geöffnet werden. Sind in der Datenbank mehrere Produkte angelegt, so wird vor dem Öffnen der Stapelbuchungs-Maske ein Produkt-Auswahl-Dialog angezeigt. Das gewählte Produkt wird in der Titelzeile des Stapelbuchungs-Dialog angezeigt. Solange der Dialog geöffnet ist, können darin nur Buchungsdaten des entsprechenden Produkts / Fonds verwaltet werden.
Um in die Stapelbuchung zu gelangen, klicken Sie in Menü *Bearbeiten → Stapelbuchung*.

![](http://xpecto.github.io/docs/img/img_1439547282677.png)

 Jeder Funktionsbereich der Stapelbuchung definiert sich durch die Verfügbarkeit spezifischer Filter und Buttons zum Durchführen bestimmter Aktionen. Allen vier Funktionsbereichen gemein ist ein Bearbeitungsbereich mit den Feldgruppen: *Buchung bearbeiten, Fremdwährung* und *Verarbeitungsinfos* - zum Anzeigen bzw. Bearbeiten einer Buchung, und eine Buchungsliste. Die jeweiligen von Anwender konfigurierten Filter bestimmen, welche Buchungen in der Buchungsliste angezeigt werden. 
 
![](http://xpecto.github.io/docs/img/img_1439810233436.png)

Die Feldgruppe *Buchung bearbeiten* zeigt die Detail-Informationen des aktuell in der Buchungsliste selektierten Buchungssatzes. Sie enthält die Felder *Belegdatum, Konto, Gegenkonto, Betrag, Buchungstext, Belegnummer* sowie optional auszufüllenden (und nicht zur Buchhaltung gehörenden) Felder *Valutadatum, Vertrag, Ust-Kennz.* und *Bemerkung.* Die Pflichtfelder sind gelb hinterlegt. 

![](http://xpecto.github.io/docs/img/img_1439798971081.png)

Das *Belegdatum* informiert über Kontobewegungen, während das *Valutadatum* das Datum ist, an dem eine Gutschrift oder Belastung wirksam wird. Das *Valutadatum* zeigt den echten Kontostand an. Dieses kann unter Umständen vom *Belegdatum* abweichen. 
Unter *Vertrag* kann eine Vertrags-Nr. erfasst werden, der die selektierte Buchungen zugeordnet werden soll. 
Unter *USt-Kennz.* (Umsatzsteuer-Kennzeichen) kann ein Umsatzsteuer-Satz erfasst werden, der bei Berechnungen verwendet werden soll.  
Unter *Betrag* ist zum eingegebenen Betrag zusätzlich die Währung auszuwählen. Dabei fließen nur Datensätze mit der beim Produkt hinterlegten Währung in die Buchhaltung ein (siehe *Produkt → Währung*).
Unter *Bemerkung* können Bearbeiter-Hinweise zu der selektierten Buchungen eingegeben werden.
Unter bestimmten Voraussetzungen (z.B. *Buchungen exportieren* gewählt oder *Buchungen festschreiben*) ist die Feldgruppe *Buchung bearbeiten* in GoBS-Modus (Grundsätze ordnungsmäßiger DV-gestützter Buchführungssysteme). GoBS-Modus ist ein Read-Only-Modus Darstellung, Sie können diese Buchungen nicht ändern.

Der Reiter *Stapel-Erfassung* dient der Ersterfassung von Buchungen. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden alle Buchungen angezeigt, die von dem aktuell angemeldeten Benutzer am selben Tag bereits erfasst wurden. 

![](http://xpecto.github.io/docs/img/img_1439974032925.png)

Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439974064694.png) um Vorlagen für Ihre Buchungssätze anzulegen oder zu bearbeiten.
Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439801023332.png) wird ein neuer Datensatz angelegt. Die Details des Buchungssatzes werden über die Feldgruppe *Buchung bearbeiten* eingegeben.
Die Gültigkeit des eingegebenen Belegdatums und des Betrags wird direkt beim Verlassen des jeweiligen Feldes geprüft. Vor dem Speichern wird außerdem geprüft, ob die Pflichtfelder *Betrag, Belegdatum, Konto, Gegenkonto* und *Buchungstext* befüllt sind. 

![](http://xpecto.github.io/docs/img/img_1439812810573.png)

 Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439804594653.png) wird die Buchung gespeichert. Beim Speichern der Buchung wird automatisch der Erfasser und der Erfassungszeitpunkt in den Buchungsdatensatz eingetragen. Die Buchungsperiode, zu der ein Buchungssatz gehört, richtet sich nach dem Belegdatum, sie wird nicht separat erfasst. Ein hier erfasster Datensatz kann über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439813538430.png) jederzeit wieder gelöscht werden, solange er noch nicht festgeschrieben ist. Festschreiben bedeutet dass eine Buchung dann nur noch durch eine Storno/Korrekturbuchung korrigiert werden kann. Damit werden nachträgliche Manipulationen erschwert.
 
Reiter *Suchen / Ändern* dient der Recherche und ermöglicht das Suchen und Ändern von Buchungen. Die Suchkriterien zum Auffinden der gewünschten Buchungssätze können über verschiedenen Filter wie  *Buchungsperiode, Beteiligung/Vertrag, Erfassung, Kontierung, Festschreibung* konfiguriert werden.

![](http://xpecto.github.io/docs/img/img_1439974891019.png)

Nicht festgeschriebene Buchungen können gelöscht oder geändert werden. Änderungen werden erst durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439804594653.png) gespeichert. Vor dem Speichern werden dieselben Gültigkeitsprüfungen durchlaufen, wie in dem Reiter *Stapel-Erfassung*. 

Bereits festgeschriebene Buchungen (erkennbar durch eingetragene Buchungs-Nr) können nachträglich nicht mehr verändert werden. Wird eine festgeschriebene Buchung selektiert, so ist der Bearbeitungsbereich in Read-Only-Modus und die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1439813538430.png) ist deaktiviert. Solange die betroffene Buchungsperiode nicht geschlossen ist, kann jedoch über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439816158639.png) eine Storno-Buchung erzeugt werden. Wird die Abfrage "Möchten Sie eine Korrekturbuchung anlegen?" mit *Ja* beantwortet, so wird eine änderbare (da nicht festgeschriebene) Kopie der Original-Buchung in derselben Buchungsperiode angelegt.

Reiter *Buchungen festschreiben* dient der Übertragung von Buchungssätze in das Buchungsjournal. 
Im Buchungsjournal werden alle Buchungen eines gewählten Zeitraums tabellarisch aufgelistet. Die Kriterien zur Auswahl der festzuschreibenden Datensätze können über verschiedene Filter konfiguriert werden, wie *Buchungsperiode, Beteiligung/Vertrag, Erfassung, Kontierung*. 

![](http://xpecto.github.io/docs/img/img_1439975378338.png)

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439820973695.png) werden alle aufgelisteten Erfassungen in das Buchungsjournal übertragen und in jeden betroffenen Buchungssatz der Festschreibungs-Zeitpunkt, der ausführende Benutzer und eine fortlaufenden Buchungsnummer eingetragen werden. Die Festschreibung einer einmal in das Journal übertragenen Buchung kann nachträglich nicht mehr aufgehoben werden. Die Buchung kann dann nur noch über *Suchen / Ändern* ![](http://xpecto.github.io/docs/img/img_1439816158639.png) storniert werden.

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439820230811.png) wird eine Buchungsperiode geschlossen. Eine Buchungsperiode entspricht einem Kalendermonat. In einer bereits geschlossenen Buchungsperiode kann nicht mehr gebucht werden. Um das Buchen in einer geschlossenen Buchungsperiode zu ermöglichen, muss die Periode über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439820257578.png) wieder geöffnet werden. Das wieder öffnen einer Buchungsperiode hebt jedoch nicht die Festschreibung der Buchungen in dieser Periode auf.
Um eine Übersicht über die schon geschlossene und geöffnete Buchungsperioden zu haben,  klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439975955612.png) - *Historie zum öffnen und schließen von Buchungsperioden*.

Der Reiter *Buchungen exportieren* dient der Übergabe von Buchungssätze an das Buchhaltungssystem des Fonds bzw. eines Steuerberaters. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden nur Buchungen angezeigt, die bereits festgeschrieben sind. Dadurch ist sichergestellt, dass keine Buchungssätze die sich noch nicht im Buchungsjournal befinden, an externe Buchhaltungssysteme übergeben werden können. 

![](http://xpecto.github.io/docs/img/img_1439975835584.png)

Über weitere Filter können die zu exportierenden Buchungen ausgewählt werden. Nach dem Aufruf des Dialogs ist der Filter *nicht exportiert* aktiv. Dadurch werden nur Buchungssätze exportiert, die vorher noch nicht exportiert wurden. Soll ein bereits erfolgter Buchungsexport wiederholt werden so muss der Filter *Exportiert* dementsprechend angepasst werden. 
Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439892039334.png) wird eine Datei im CSV-Format erzeugt, die die aufgelisteten Buchungssätze enthält. Dabei wird automatisch der Exportzeitpunkt und der auszuführende Benutzer in die betroffenen Buchungsdatensätze eingetragen. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439894313567.png) wird dieselbe Export-Datei erzeugt, jedoch ohne Informationen in den Buchungsdatensatz einzutragen.

Die Reihenfolge der Bearbeitungsschritte in der Stapelbuchung ist: 1. Erfassen, 2. Festschreiben, 3. Schließen, 4. Exportieren.


## Beteiligungs Vertragsbuchungen

Die Funktion *Beteiligungs-/Vertragsbuchungen* dient der manuellen Buchungen und Korrekturen, für eine Vertrag oder Beteiligung.

Um eine neue Buchung für einen Vertrag anzulegen, klicken Sie unter *Bearbeiten → Beteiligungs-/Vertragsbuchungen*. Falls Sie in dem Vertragsansicht noch kein Vertrag ausgewählt ist, werden Sie aufgefordert einen Vertrag auszuwählen.

![](http://xpecto.github.io/docs/img/img_1439988459598.png)

Genau wie bei Stapelerfassung, haben Sie die Möglichkeit unter dem Reiter *Stapel-Erfassung* eine Ersterfassung von Buchungen. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden alle Buchungen angezeigt, die von dem aktuell angemeldeten Benutzer am selben Tag bereits erfasst wurden.

![](http://xpecto.github.io/docs/img/img_1439989206664.png)

Der Reiter *Suchen / Ändern* dient der Recherche und ermöglicht das Suchen und Ändern von Buchungen. Da der Filter Beteiligung/Vertag für den ausgewählten Vertrag eingestellt würde, können Sie hier, eine neue Buchung für diesen Vertrag anlegen.  
Falls Sie eine andere Einstellung wünschen, dann klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439992255614.png).

In dem folgenden Dialog können Sie dann einen anderen Vertrag wählen:

![](http://xpecto.github.io/docs/img/img_1439992214552.png)

![](http://xpecto.github.io/docs/img/img_1439992073968.png)

Sichern Sie Ihre Änderungen durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439804594653.png) . 

**Beteiligungen**
Mit xpectoPro ergibt sich die Möglichkeit in mehrere Produkte zu investieren. Durch die Beteiligungen an einen Produkt erwerben die Anleger Anteile an einen Produkt. Ein Kunde, der in verschiedene Produkte investiert möchte, hat dann mehrere Verträge mit unterschiedliche Beteiligungen. 
Eine Beteiligung an einen Produkt wird in dem Dialog neuen Vertrag erstellen (siehe *Datei → Neu → Vertrag*) festgelegt.

Beteiligungen werden in dem Kundensicht unter Kunde, mit der Symbol ![](http://xpecto.github.io/docs/img/img_1439978235195.png), dargestellt.  

Klicken Sie auf eine Beteiligung um in die Eingabemaske zu gelangen.

![](http://xpecto.github.io/docs/img/img_1438780567378.png)

Unter dem Reiter *Allgemein* erhalten Sie eine Vertragsübersicht. Das sind alle Verträge des Kundes die an dieses Produkt beteiligt sind.

xpectoPro bietet eine Offene Posten Buchhaltung, die überprüft ob die Forderungen bereit beglichen wurden. Unter dem Reiter *OPOS* wird die OPOS-Liste angezeigt. Eine OPOS-Liste ist die Liste aller offenen Rechnungen. 

Der Reiter *Salden* beinhaltet eine Saldenkonfiguration und eine Summen und Salden Liste. Die hier hinterlegten Konten beziehen sich auf die unter Produkt vorkonfigurierten Salden.

![](http://xpecto.github.io/docs/img/img_1439903745722.png)

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

Mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439980233293.png) können Sie sehen welche Buchungen zum Saldo bzw. zum Konto gemacht wurden.

![](http://xpecto.github.io/docs/img/img_1439905236293.png)

![](http://xpecto.github.io/docs/img/img_1439905104073.png)

Unter dem Reiter *Konto-Verwendung* können die Bankkonten (siehe Kunden → Adressen → Kontoverbindungen) für unterschiedliche Verwendungszwecke eingesetzt.

Unter der Reiter *Dauervollmachten* können Sie eine Vollmacht für eine bestimmte Person anlegen.

## Vertrag uebertragen

Über diesen Menüpunkt kann der aktuell ausgewählter Vertrag zu einem anderen Kunde übertragen werden. Damit wird der Vertrag von einem Kunde zu einem anderen verschoben. Dafür markieren Sie den Vertrag den Sie übertragen wollen und dann wählen Sie unter Menüleiste *Bearbeiten → Vertrag übertragen.*

![](http://xpecto.github.io/docs/img/img_1439215255854.png)

Der Dialog *Vertrag übertragen* ermöglicht das Suchen nach dem Kundendaten oder nach Vertragsdaten. Durch einen Doppelklick auf dem gewünschten Kunde wird den ausgewählter Vertrag dem Kunden zugewiesen. 
Bestätigen Sie hier die Meldung mit *OK*.

![](http://xpecto.github.io/docs/img/img_1434110869275.png)

Um den Vertrag bei dem neuen Kunde zu sehen müssen Sie nur die Daten aktualisieren. Dafür wählen Sie in der Menüleiste *Bearbeiten → Aktualisieren* oder drücken Sie die F5-Taste.


## Wiedervorlage Liste

Die Wiedervorlage Liste befindet sich im Hauptfenster und dient der Übersicht über alle fällige Wiedervorlagen. So können Sie die Liste nach Fälligkeitsdatum abarbeiten.
Über die Funktion *Wiedervorlage Liste* wird die Anzeige der Wiedervorlage Liste im Hauptfenster ein- oder ausgeschaltet.

![](http://xpecto.github.io/docs/img/img_1439993705072.png)

Durch Doppelklick auf eine Wiedervorlage in der Wiedervorlage Liste wird der entsprechende Kunde, Vertrag, Vermittler, Personen oder Veranstaltung geladen und die Details der Wiedervorlage werden angezeigt. 

Der unter der Wiedervorlage Liste eingebauten Filter dient zum Sortieren der Liste. Nachdem Sie einen anderen Kriterium für Ihre Anzeige ausgewählt haben, klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439994170249.png) um die Daten neu laden.

Die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439994083070.png) - *Wiedervorlage Historie anzeigen*, zeigt Ihnen der Verlauf des ausgewählten Prozesses.


## Wiedervorlage Seitenleiste

Über diese Funktion wird die Anzeige der Wiedervorlage Seitenleiste im Hauptfenster ein- oder ausgeschaltet. Die Wiedervorlage Seitenleiste zeigt die Liste der Wiedervorlagen für einen Kunde, Vertrag, Vermittler, Person oder Veranstaltung. 
Um die Wiedervorlage Seitenleiste zu aktivieren, wählen Sie z.B. einen Vertrag, und dann klicken Sie unter Menü Bearbeiten auf *Wiedervorlage Seitenleiste*. 


## Wiedervorlage Steuerung

Der Dialog *Wiedervorlage Steuerung* dient dazu für einen Prozess mit einen bestimmte Prozessschritt eine gewünschte Aktion gleichzeitig für mehrere Wiedervorlagen zu wählen und durchzuführen.
Um den *Wiedervorlage Steuerung* Dialog zu öffnen wählen Sie unter *Bearbeiten → Wiedervorlage Steuerung* oder klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1434097634985.png) in der Wiedervorlage Ansicht. Sie können z.B. alle fällige Mahnprozesse mit der Mahnstuffe 1 *Neuem Benutzer zuweisen*,  es wird ein neuer Benutzer abgefragt und diesem dann die gewählten Wiedervorlagen zugewiesen.

![](http://xpecto.github.io/docs/img/img_1434095945225.png)

Nachdem Sie die gewünschte Aktion ausgewählt haben drucken Sie auf *Start*.

