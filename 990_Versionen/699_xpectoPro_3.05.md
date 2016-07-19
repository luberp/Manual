# xpectoPro 3.05. - 18.07.2016

## Features

* Feature [#22810] Adressen: Staatsangehörigkeit als eigenes Feld in der Ländertabelle z.B. "deutsch"

* Feature [#25716] Fieldmap: Proxy-Felder können jetzt auch korrekte Owner benutzen

* Feature [#26584] Nachschlagslisten: Die Standardeinträge können jetzt per Knopf in der Maske nachgeladen werden

* Feature [#27896] Tranchen: Möglichkeit der Erfassung von Tranchen zu einem Produkt (inkl. Platzierungs-Art und -Zeitraum sowie Gesamtvolumen).
Das aktive Volumen wird automatisch berechnet und angezeigt.
Bei der Vertragserfassung kann die zugehörige Tranche gewählt werden.

* Feature [#29124] Veranstaltungen: schriftliches Umlaufverfahren PDF auslesen
Die Funktion zum Erkennen des Abstimmungsergebnisses wurde deutlich überarbeitet. Erkennungsrate,
Geschwindigkeit und Benutzerfreundlichkeit wurden verbessert.

* Feature [#31538] Nachschlagslisten: Beschreibungen dürfen jetzt auch Zeilenumbrüche haben. Diese bitte mit "\n" angeben.

* Feature [#32143] Softwarestart: TestDB: Feldprüfungen beschleunigt
DDL wird komplett abgefragt statt wie bisher je Feld

* Feature [#33732] PDF Verarbeitung: MassenPDFs können mit den internen Werkzeugen beliebig geteilt werden
Die trainierbare Texterkennung ermöglicht die einache Trennung von Massen-PDFs (speziell bei Datenübernahmen) auf Einzelschreiben.

* Feature [#34115] Kombidokument: den alten Begriff "Metabericht" in allen Dialogen und Anzeigen ersetzt

* Feature [#34341] Sollbuchungen: ausgeführte Sollbuchungen sind nicht mehr änderbar

* Feature [#35415] Ribbon: Menu durch Userfeedback nochmals verbessert
Reiter Aktionen und Werkzeuge neu strukturiert
Die Breite des Menus wurde auf 1200 Punkte beschränkt.

* Feature [#35437] Schnellkontakt: Funktionen überarbeitet und Usability erhöht

* Feature [#35767] Ticket-System: Tickets können direkt in xpectoPro angelegt und verwaltet werden (inkl. Priorisierung sowie Anpassung von Betreff und Beschreibung).
Menü: [Hilfe]->[Ticket Übersicht]
Ribbon: [Hilfe]->[Tickets]->[Übersicht]

* Feature [#35827] DataEngine: starke Beschleunigung bei Massenaktionen (z.B. Transaktion löschen, Berechnung durchführen ...)

* Feature [#35829] Buchungen zuweisen: manuelle Erfassung von Buchungen deutlich verbessert (Custom-Form Import_BuchungManuell)

* Feature [#35834] Kombibericht: Berücksichtigung von Duplex über alle Einzelschreiben: automatisches Einfügen von Leerseiten

* Feature [#35887] Veranstaltungen: Stimmbasis je TOP einstellbar (Treugeber, Direktkommanditisten ...)

* Feature [#35888] CustomForm: mögliche Anzeige der Änderungen bei Überarbeitungen (Diff)

* Feature [#35898] ComboBox: Adressen werden im Standard mit "Adressekurz" angezeigt

* Feature [#35909] A2A Bericht: Abfragetesten erzeugt jetzt die notwendige Insert-Abfrage 

* Feature [#35925] Vertrag_Salden: Hauptbuch-Konten nur in SuSa-Liste vom Produkt anzeigen (nicht auf Vertrag/Beteiligung)

* Feature [#35937] Berechnungen: Beschleunigte Berechnung (Faktor 100x) für Standardfälle ohne Scripting
Die Beschleunigung ist das Ergebnis einiger Änderungen im Softwarekern. Verteilungen auf Basis von 
Werten, Feldern und Salden sind erheblich schneller als früher. Die Verteilung auf Basis von Formeln
oder Scripten ist dagegen nur wenig beschleunigt.

* Feature [#35948] Zahlungsverkehr: Auszahlungen in Fremdwährung: Steuerung über Offene Posten mit Vorgabe über eine Berechnung
Die Wunschwährung von Kunden kann damit genauso berücksichtigt werden wie die Vorgabe durch die Verwaltung. 
Insgesamt stehen 5 Modi zur Verfügung:
** Oposwährung
** Fondswährung
** Hauswährung
** Kundenwunsch/Fonds
** Kundenwunsch/Haus

* Feature [#35986] Verträge: Stimmrechte: Option zur Berechnung per Zeichnungssumme (anstatt Saldo)
Für Kunden ohne vollständig gebuchtes Beteiligungskapital

* Feature [#36039] Buchungen zuweisen: Script FondsImportFindContract neu. Suche nach korrektem Vertrag per Script 
z.B. Suche über Rechnungsnummer oder andere Merkmale

* Feature [#36045] Script: clContract.IsActive(Date): Werte aus ob ein Vertrag zum Datum aktiv ist (VT_VertragsBeginn/Ende)

* Feature [#36072] Berechnungen: Werte können Aktiv und Inaktiv geschaltet werden über Schaltfläche in den Berechnungs_Details

* Feature [#36074] Berechnungen: Löschen von Berechnungen: Auswahl des Datenumfangs (Werte, Buchungen ...)

* Feature [#36077] Excel-Reader: Aus XLSX-Dateien können alle Arbeitsblätter eingelesen werden. Für die Benutzung in speziellen Scripten.

* Feature [#36131] Vertrag_Werte: Erfassung von manuellen Werten mit bis zu 14 Unterwerten

* Feature [#36159] Zahlungsverkehr: Gebührensituation bei DTAZV-Überweisungen kann in den OPs hinterlegt werden

* Feature [#36170] Kontorundruf: "Kontoauszüge Ab"-Datum für die Anfrage bei der Bank kann gesetzt werden
Durch Fehler in den Banksystemen sind teilweise abweichende Datumswerte notwendig. Der
Standard wäre der 1.1.2013. Da die Banksysteme immer nur einen bestimmten Zeitraum liefern
(Normal = 3 Monate, CoBa = deutlich weniger) muss das Datum im Regelfall nicht benutzt werden.

* Feature [#36171] Offene Posten: Tarifspalte wird in Vertragsansicht mit angezeigt

* Feature [#36184] Buchungen zuweisen: Retouren automatisch erkennen und korrekten (den ursprünglichen OP-Wert) Wert vorschlagen

* Feature [#36221] Buchungen zuweisen: Kontorundruf soll Buchungen sofort anzeigen
Nach einem Kontorundruf werden die abgeholten Buchungen jetzt direkt angezeigt.

* Feature [#36227] Zahlungsverkehr: Übertragung von Zahlungsaufträgen direkt an die Bank mit 4-Augen-Prinzip und Protokollierung
Zahlungsaufträge können im Normalfall nicht mehr direkt vom selben Benutzer an die Bank versendet werden. Der
Versand wird zudem revisionssicher protokolliert.

* Feature [#36266] Berechnungen: Reihenfolge der Karteireiter Allgemein und Konfiguration vertauscht
Damit ist im Normalfall immer der eigentliche Berechnungs-Bereich aktiv und nur bei
der (seltenen) Neuanlage von Berechnungsprofilen wird die Konfiguration angezeigt.

* Feature [#36276] Produkt_Berechnungen: neuer Reiter in den Produkten als Übersicht aller Verteilungen dieses Produktes 
Berechnungen können direkt kopiert und neu angelegt werden. Die Verteilung der Jahresergebnisse kann
damit vom Produkt her gestartet werden.

* Feature [#36296] Buchungen zuweisen: optionale Anzeige einer Liste aller offenen oder geparkten Buchungen
Die Liste wird im Standard nicht angezeigt. Der Dialog wird dadurch sehr breit. 
Für die Nutzung muss die Einstellung ImportAssignTransList auf true gestellt werden. 
Die aktive Buchung kann direkt in der Liste gewählt werden. Die Übersichtlichkeit ist
durch die Liste wesentlich verbessert.

* Feature [#36301] Sollstellung: Lastschrift-Mandate wandern bei Benutzung von Zweckkonten vom Vertrag in die Zweckkonten
Die MandatsID ist damit frei definierbar. Ein Mandat für mehrere Verträge ist ebenfalls möglich.
Die entsprechenden Vertragsfelder werden damit überflüssig.

* Feature [#36322] Veranstaltungen_Scandialog: Anzeige/Bildschirmnutzung verbessert

* Feature [#36384] Veranstaltungen: Vertreter können jetzt auch weitere Bevollmächtige anmelden

* Feature [#36387] Adresse_Kontoverbindungen: neue Reihenfolge der Felder, IBAN ist wichtigstes und damit erstes Feld

* Feature [#36396] Veranstaltung_Scandefinition: Übersichtlichkeit verbessert, Anleitung integriert

* Feature [#36402] Veranstaltungen: Schreibschutz für abgearbeitete Veranstaltungen sichert Datenintegrität

* Feature [#36415] Berechnungen: neue Option "Nur mit Bewertung" erzeugt ein Ergebnis nur für Berechnungen bei denen auch eine Bewertung ermittelt wurde (<>0)

* Feature [#36418] Kampagne: Der Bezeichner vom Kunden soll auch bei der Beteiligung angezeigt werden (wie beim Vertrag)

* Feature [#36420] Produkt_Beteiligungen, Produkt_Vertraege: Kampagnen können nun direkt gestartet werden (Rechtsklick auf Liste)

* Feature [#36421] Veranstaltungen: Vertreter: neuer Button zum öffnen des Stimmergebnis der Bevollmächtigten-Person beim Bevollmächtigten

* Feature [#36448] Tickets: Kunden können direkt Tickets aus xpectoPro anlegen

* Feature [#36530] Berechnungen: Wichtige Änderung bei der Behandlung von leeren Datumsfeldern + neue Option FilterNurAktiv
Behandlung des Feldinhalts für das Startdatum (z.B. Abschlussdatum)
Leere Werte im Startdatum werden jetzt immer mit WE_Bewertung=0 und WE_Buchungstext&="(nicht berechnet, leeres Startdatum)" gespeichert
Früher konnten die Salden (nur diese) auch Werte ohne das Datum erzeugen
Dieser Fall tritt nur bei gesetztem Feld für das Startdatum auf. Das Feld darf aber weiterhin auch leer sein
Die neue Option FilterNurAktiv startet die Berechnung für diese Verträge erst gar nicht und liefert daher
auch für diese Verträge kein Ergebnis.

* Feature [#36560] Berechnungen + Zahlungsverkehr: Maskentrenner (horizontaler Splitter) zwischen den beiden Listen bewegt sich jetzt relativ zur Fenstergröße

* Feature [#36573] Berechnungen: neuer Parameter SimpleCalculationResults: vereinfachte Buchungsliste im Berechnungsdialog (Geschwindigkeit)
Die Anzeige der Werte verzichtet auf Angaben zu Sollbuchungen und offenen Posten, ist dafür aber deutlich schneller.

* Feature [#36574] Oberfläche: Fortschrittsanzeige: Verbesserte Behandlung und Anzeige von mehrstufigen Aktionen. (z.B. beim Start von mehreren Berechnungen gleichzeitig)

* Feature [#36575] Vertrag_Ereignisse, Kunde_Ereignisse: neue Filter Option "Untereinträge anzeigen"

* Feature [#36582] Performance: Geschwindigkeitsverbesserung durch automatische Datenbank-Indizes auf weiteren Feldkombinationen

* Feature [#36616] Berichte: Automatischer Druck von Vorbriefen
MAINFEATURE

* Feature [#36636] Beteiligung_Handelsregister: zusätzliche Anzeige des Gesamtbetrages der Beteiligung

* Feature [#36705] Produkt_Vertraege, Produkt_Beteiligungen - Suche ohne Kundenname unterstützen, Tagesdatum als Standard "Gültig bis"-Datum

* Feature [#36754] Buchungen zuweisen: automatisch Speichern: keine Fehlermeldungen bei nicht speicherbaren Buchungen (AutoSaveTimeOut = -1) oder nur sehr kurze Anzeige (AutoSaveTimeOut = x Sekunden)

* Feature [#36776] Rechteverwaltung: neuer Dialog, wesentliche Vereinfachung

* Feature [#36782] CustomForm: neues Slider-Control z.B. für Prozentwerte oder stufenlose Eingaben

* Feature [#36790] Übertragungen: Herabsetzung und Zusammenführung als Massenaktion über Kampagne

* Feature [#36796] Softwarestart: Patchsystem erweitert für den einfachen Softwareupdate incl. aller Abhängigkeiten

* Feature [#36812] Dataexplorer: Dialogfenster können jetzt mit ESC geschlossen werden

* Feature [#36819] Dataexplorer: Fensterposition/-größe: Anzeige und Anpassung im Multimonitorbetrieb verbessert

* Feature [#36884] Script/XText: Alle Ausdrücke können jetzt zusätzlich zu FieldIDs (z.B. [B0805]) auch den internen Feldnamen enthalten (z.B. [AD_Nachname])
Diese Änderung ist zentral integriert und betrifft praktisch alle dynamischen Texte. z.B. Buchungstexte bei Überweisungen/Lastschriften und Exportinfos beim Buchhaltungsexport

* Feature [#36888] CustomForm: Hinweis auf angepasste Form in der Kopfzeile des Designers

* Feature [#36918] Updates: Jeder Softwareupdate wird nun als LogEintrag gespeichert (incl. Benutzer)

* Feature [#36920] Kontingentverwaltung für Vertriebspartner je Produkt:
** Bei Produkten kann die "Kontingentsteuerung" per Checkbox aktiviert werden
** Vertriebspartner haben einen eigenen Reiter Kontingente
** Bei der Auswahl des Vertriebspartners im Vertrag wird das vorhandene Kontingent geprüft

* Feature [#36998] Übertragungen: Änderungen an Vertrags-Beginn/Ergebnis-Beginn/Entnahme-Beginn bzw. -Ende auf RV/RN und UT durchschreiben

* Feature [#37022] Vorbriefe: Untersützung von Duplex: Einfügen von Leerseiten wenn Hauptschreiben auf Duplex gedruckt werden soll

* Feature [#37071] Wunschversand: erzeugte E-Mail wird archiviert

* Feature [#37077] Hauptfenster: Wiederherstellung des Fenster (aus Taskleiste) beschleunigt

* Feature [#37097] Stapelbuchung: Storno überarbeitet
Storno-Funktion überarbeitet. Korrekte Behandlung von mehrfach Stornos.

* Feature [#37117] Veranstaltungen: Quorum für TOPs neu

* Feature [#37118] Veranstaltungen: Mehrheitsbeschluss bei TOPs incl. Gewichtung

* Feature [#37223] ScriptEngine: Umstellung auf Massenkompilierung, Geschwindigkeitssteigerung
Alle Scripte und Oberflächen einer Datapane (z.B. Kunden oder Verträge) werden jetzt in einem Rutsch kompiliert und verarbeitet.
Der Maskenaufbau ist damit nicht mehr verzögert, alle Karteireiter sollten sofort angezeigt werden.
Falls die Karteireiter nacheinander im Abstand von einigen Sekunden angezeigt werden, 
ist wahrscheinlich ein Script nicht ganz korrekt eingerichtet. Das sollte die Kundenbetreuung beheben.

* Feature [#37227] Veranstaltungen: Verbesserung der Veranstaltungsoberflächen
** Hinzufügen einer "Anmeldungsmaske" für Präsenzveranstaltung
** Zentralisierung der Funktionen zu Teilnehmern und Bevollmächtigten
** Umbenennung des Tabs "Scandialog" innerhalb der Stimmabgabe in "Rückläuferverarbeitung"
** Hinzufügen eines Tabs "Barcodeauswertung" zur Erfassung der Stimmzettel von Präzenzveranstaltung anhand von Barcodes

* Feature [#37288] Zahlungsverkehr: Vertrag-Sollbuchungen bearbeiten
In den Details des (geplanten) Zahlungsverkehrs können die einzelnen Sollbuchungen mit Doppelklick bearbeitet werden.
Die Summe wird erst nach dem Neuladen der Daten im Zahlungsverkehr (Pfeilsymbol rechts oben) angezeigt. Änderungen
am Buchungstext sind sofort aktiv.

* Feature [#37315] Berechnungen: Beteiligungsebene zusätzlich zu Vertragsebene
Alle Berechnungen können jetzt direkt auf der Beteiligungsebene durchgeführt werden. Summen und Salden
werden über alle Verträge (und Beteiligungsbuchungen) hinweg summiert. Als Ergebnis erhält man
einen Wert je Beteiligung.
MAINFEATURE

* Feature [#37330] Adressen: Neues Feld NameZusatz für Adressen

* Feature [#37343] Offene Posten: Filter verschönert: Beteiligung/Vertrag mit Delete-Knopf, weniger Updates beim Filtern
** Beschleunigung und mehr Komfort im Dialog "offene Posten":
** Vertrag und Beteiligung können per Knopf gelöscht werden
** weniger Listenaktualisierungen bei der Angabe von Parametern

* Feature [#37370] Druckvorschau: Bei Kopieschreiben-Vorbrief Hinweis ausgeben
Im Druckvorschau-Fenster wird nun bei Schreiben, die einen Vorbrief enthalten, die Anschrift des Empfängers eingeblendet

* Feature [#37374] Berichte: Parameter: Abfragen in Sammelbox jetzt auch mit Suchfeld
Die "Abfrage-Parameter-Sammelbox" (Zusammenfassung von einzelnen Abfragen) stellt nun auch Suchfelder dar.

* Feature [#37381] Prozesse: Prozessübergänge: erlaubte Attribute können auch negiert angegeben werden 
Hat z.B. ein Übergang das erlaubte Attribut "!Mahnung" kann die Aktion nur ausführt werden wenn
der laufende Prozess das Attribut Mahnung NICHT hat.

* Feature [#37394] Wiedervorlagen: Wiedervorlagen sollen abhängig der Priorität farblich hervorgehoben werden
Wiedervorlagen können nun, abhängig von der Priorität, farbig hervorgehoben werden wenn
der Parameter ReminderPriorityColor entsprechend gesetzt wird.

* Feature [#37413] Script: clContract./clHolding.GetValueSum: Summenfunktion für Werte

* Feature [#37414] CustomForms: neues "value"-Tag für Radiobuttons

* Feature [#37415] Berechnungen: nur positive Werte/Salden/Formeln mit Option BerechnungNurPositiv (Standard = true)
Negative Kapitalstände werden im Normalfall nicht "verzinst". Bei Bedarf können aber positive
und negative Stände verrechnet werden.

* Feature [#37416] Berechnungen: neuer Berechnungstyp: Wertarten
Als neue Bewertungsgrundlage können Werte benutzt werden. Die Werte können als einfachen Formel angegeben werden. 
Beispiel: WertArtA+WertArtB-WertArtC
Es werden alle aktiven (=nicht veralteten) Werte im eingestellten Zeitraum summiert.Die Bezugsgrundlage ist
dabei WE_Buchungsdatum in Bezug auf den eingestellten Zeitraum. WE_Buchungsdatum muß daher befüllt sein.
MAINFEATURE

* Feature [#37435] Berechnungen: Testberechnung für alle Verträge
Der neue Testmodus "Gesamt" berechnet die ausgewählte Berechnung für alle Verträge und zeigt die Ergebnisse an. 
Die Testberechnung kann auch bei schon durchgeführten Berechnungen gemacht werden.
Die Werte und Buchungen werden nur im Speicher erzeugt und werden nicht in die Datenbank geschrieben. 

* Feature [#37437] Script: Nachschlagslisten: Neue Funktion LookupList.GetKeyByDescription()

* Feature [#37440] Berechnungen: Wertliste: neue Spalte Zeichnungssumme
Die untere Liste der Werte enthält jetzt zusätzlich die Zeichnungssumme

* Feature [#37525] Softwareupdate: neuer Parameter: ReleaseRing: Stable, Release oder Test
Der neue Parameter gibt an welche Builds vom Server zum Update angeboten werden. 
Es gibt 3 unterschiedliche ReleaseRing(e): Stable (Wert 10 = Standard), Release (Wert 20), Test (Wert 30)
Je nach Einstellung werden die einzelnen Veröffentlichungen zum Download angeboten. Die Versionsnummer enthält als Zusatz den Namen des ReleaseRings.
Hinweis: Die Software weiß selbst nicht in welchem ReleaseRing sie veröffentlicht wurde.

* Feature [#37538] Webportale: Nutzer können sich per Twofactor-Authentication anmelden
Das können TANs per SMS oder per E-Mail sein.

* Feature [#37573] Berechnungen: Die Zinsberechnung act/360 (Eurozinsmethode) wurde hinzugefügt. 
Die Zinstage werden dabei nach Kalendertagen berechnet, der Basiszeitraum aber mit 360 Tagen angenommen. 
Damit liegt der normale Jahreszins über dem angegebenen Prozentsatz. (365/360 für ein normales Jahr, 366/360 für ein Schaltjahr)
Beispiel: 10000€, 7% für 2015 ergibt 10.000€ * 0,07 * 365 / 360 = 709,72€

* Feature [#37590] Beteiligungen_Zweckbankverbindung: Kostenteilung: leeren Eintrag ermöglichen (= Standard)

* Feature [#37613] Vertrag_Sollbuchungen: neuer, standardisierter Maskenaufbau
neuer Friendlyname für SB_ExternalPayment ("erwartete Zahlung")

* Feature [#37624] Auslieferungszustand: Neue Vertrags-Status 8.3 beendet und 8.4 reduziert
Es gibt zwei neue Vertrags-Status '8.3 beendet' und '8.4 reduziert'.
Umschreibungen vom Typ Vertragsbeendigung oder Kapitalherabsetzung setzen den entsprechenden Status.

* Feature [#37695] ModernStyle: Neuer Parameter ForceNewAppStyle: zwingt Nutzer zur neuen Ansicht
Durch die etwas unterschiedliche Rechtestruktur ist es teilweise nötig den Zugang zur alten Menu/Symbolleiste zu verbieten.
In neuen Datenbanken kann die alte Menue/Symbolleiste nicht mehr eingeblendet werden. 

* Feature [#37702] Vertraege_Ereignisse, Beteiligung_Ereignisse: neuer Knopf für neue Vertragsereignisse

* Feature [#37705] Script: Dom-Queries: Support für DFIRST und neu: DLAST, mit Angabe eines Feldnamens in der Form "dom,15000,DLAST+15800,15610,XXX"

* Feature [#37807] Script: vb.NumberToWords für Französisch neu
Ein zusätzlicher Parameter mit der gewünschten Sprache wurde hinzugefügt. Bei leer/"DE" wird wie üblich der deutsche Text ausgegeben, bei "FR" der französische.

* Feature [#37849] Prozessdesigner: Button zum öffnen der SpecialForm für komplexere Prozesse

* Feature [#37910] Produkt_Beteiligungen + Produkt_Verträge: Beschleunigung (durch optionale Salden) und Vereinheitlichung der Funktion

* Feature [#37929] Datensatz kopieren: Behandlung von verlinkten Adressen verbessert, Nachfrage ob Kopie oder Link

* Feature [#37958] Benutzer_Allgemein + CustomForms: Neuer Validierungs-Typ E-Mail
Im Oberflächendesigner gibt es bei den Feldvalidierungen einen weiteren Typ "enEMail", der prüft, ob eine korrekt aufgebaute E-Mail-Adresse eingetragen ist.

* Feature [#37992] Kontoverbindungen: in Listen mit neuem Standard (incl. deutlichem Sperrgrund) (KV_Bezeichner neu)
Das neue Feld enthält eine berechnete Zusammenfassung der Bankverbindung incl. einem deutlichen Hinweis auf eine etwaige Sperrre. Die Feldlisten werden nur verändert, wenn diese bisher nicht kundenspezifisch geändert wurden.

* Feature [#37993] Script: Hilfsfunktion vb.GetAge() liefert das Alter zu einem Geburtsdatum

* Feature [#38033] Produkt_Provisionen: neuer Aufbau

* Feature [#38035] Transaktionen: Oberfläche aktualisiert

* Feature [#38036] Anlageerfahrung: Neues Feld für Informationsquelle zu Anlageerfahrung
Zur Anlageerfahrung gibt es ein neues Feld "Informations-Quellen" zur Angabe der Quellen/Medien, über die sich der Anleger regelmäßig über Kapitalmarktprodukte informiert.

* Feature [#38037] Listen: Hyperlinks können jetzt recht einfach definiert werden über die ColumnConfiguration

* Feature [#38038] Offene Posten + Berechnungen: Tabellen mit Hyperlinks, Tabellenaufbau konfigurierbar

* Feature [#38087] Listen: Hyperlinks mit Schlüsseln (z.B. VertragsNr) die einen Schrägstrich enthalten funktionieren jetzt korrekt

* Bug [#27726] Archivaufkleber drucken: zusätzliches Ereignis wurde erzeugt


## Bugs

* Bug [#30654] Stapelbuchungsdialog - Softwareabsturz bei Eingabe des Exportdatums

* Bug [#33974] Berichtsdesigner - Abfrage testen funktioniert nicht mehr

* Bug [#34891] Schnellerfassung im Adressmodell - Kontoverbindungen und Legitimationsdaten werden nicht befüllt

* Bug [#35260] Zahlungsverkehr: Ungültige / gesperrte Zweckkonten dürfen keine Sollbuchungen auslösen

* Bug [#35263] OP_ZweckkontoID sollte bei direkt wieder gelöschten (nicht getätigten) Auszahlungen auch mitgelöscht werden.

* Bug [#35352] ID ändern: Adressreferenz wurde nicht überall geändert

* Bug [#35764] Listen: Formatierte Werte werden teilweise nicht korrekt angezeigt

* Bug [#35771] Ereignisse: Outlookimport: Pfad von Anhängen war absolut ohne %ArchivePath% Platzhalter

* Bug [#35863] Abfrage erstellen: Vertragstatus werden von allen Produkten angezeigt

* Bug [#35868] Adressverwendung: Anzeige von Berechnungen die an dieser Adresse hängen

* Bug [#35878] Menu - Datei - Neu: sollte keinen Dialog öffnen sondern nur aufklappen

* Bug [#35916] SMS-Versand: exaktere Fehlerbehandlung und Anwenderinformation

* Bug [#35918] Kontodatenimport: CAMT/C53 Auszüge: lfd. Saldo konnte in bestimmter Konstellation nicht berechnet werde

* Bug [#35926] Berechnungen: tägl. Verzinsung act/act: ungewöhnliche Zeiträume über mehrere Jahre die zudem Schaltjahre enthielten wurden falsch behandelt (Beispiel 1/2015 - 1/2017)

* Bug [#35956] Mitarbeiter_EreignisListe: Druck Barcode defekt

* Bug [#35974] Buchungen zuweisen: Doppelklick auf Splitbuchung löscht diese

* Bug [#36001] Sollbuchungen: zusammengefasste Sollbuchungen aus offenen Posten konnten unter bestimmten Umständen nicht mehr gelöscht werden

* Bug [#36033] Kombidokument: hinzufügen von Berichten: nicht standardmäßig Option "Einzelbericht" setzen

* Bug [#36043] Scanmodul: fehlerhafte Seitendrehung wenn Barcode in der oberen Hälfte

* Bug [#36056] Berechnungen: Gebührenabrechnung: Belegdruck: BelegNr wurde nicht in Buchungen geschrieben

* Bug [#36143] Berechnungen: Gebührenabrechnung: Zahlungsverkehr über offene Posten geht nicht

* Bug [#36172] Vertrag_Belege: Anzeige von Belege nicht mehr möglich

* Bug [#36197] Dataexplorer: Suche: Suche nach ungewöhnlichem Datum (1.1.1700) führte zu Fehlermeldung

* Bug [#36308] Lizenzsystem: Problem bei der Aktivierung mit vielen Produkten und langen Produktnamen

* Bug [#36335] Berichte bearbeiten: Schreibschutz konnte durch Änderungshistorie umgangen werden

* Bug [#36340] Beteiligung_ZweckKonten: kundenspezifische Zwecke wurden nicht berücksichtigt

* Bug [#36346] PDF Berichte: Befüllung von Feldern in bestimmten Dokumenten nicht möglich

* Bug [#36375] Word Berichte: Unterberichte funktionieren nicht mehr

* Bug [#36399] Produkte_Wertarten: Währung und Bezeichnung Pflichtfelder

* Bug [#36555] Wiedervorlage Seitenleiste: Anzeige wird automatisch beim Datensatzwechsel neu geladen, auch wenn eine Wiedervorlage geöffnet wurde
Der Parameter WiedervorlageEditAutoClose kann zur Steuerung benutzt werden. Das alte Verhalten wäre WiedervorlageEditAutoClose=False

* Bug [#36713] Berichte: Briefpapier: Teilweise schlechte Qualität bei PDF-Vorlagen

* Bug [#36738] Softwarestart: TestDB wurde bei jedem Start durchgeführt = langsam (Problem mit Feld G0501)

* Bug [#36779] Provisionen: Berechnung Ansprüche: Mandantenkennung/Owner nicht immer vollständig

* Bug [#36836] Synchronisation: Kontoverbindungen (B2) vor Produkt_Konten (61) verarbeiten

* Bug [#36873] Sektionsbasierte Berichte: Felder ohne Formeln in Fußzeilen wurden auf Folgeseiten geleert

* Bug [#36919] Customforms: Shape-Elemente wurde sehr breit dargestellt, Änderungsverfolgung dadurch extrem weit rechts

* Bug [#36931] Veranstaltung_Allgemein: Meldung verbessert im Fehlerzustand

* Bug [#36985] Berechnungen: Beschleunigung macht Probleme bei sehr großen Produkten

* Bug [#37020] Veranstaltungen: Auslesen von Stimmzetteln: Fehlermeldung nicht genügend Arbeitsspeicher bei bestimmter Konfiguration

* Bug [#37055] Übertragungen: erfolgreichen Status nach Durchführung anzeigen

* Bug [#37061] Kopieschreiben: Bei Kopien an die Meldeadresse keinen Vorbrief erzeugen

* Bug [#37229] Scanmodul: Barcodes teilweise nicht vollständig erkannt

* Bug [#37245] Vertrag_Allgemein: Produktspezifische Maske wurde nicht angezeigt

* Bug [#37258] Sicherung Anpassungen: Fehlermeldung bei Übertragung der kundenspezifischen Änderungen

* Bug [#37313] Dataexplorer: Sortierung von Spezialspalten liefert Fehlermeldung

* Bug [#37331] Kopieschreiben in Verbindung mit noch nicht archivierten Wordberichten machen Probleme

* Bug [#37342] Kampagne: Druck von Berichten mit Nachfragen (z.B. Produkt o.ä.): Nachfrage wurde öfters wiederholt

* Bug [#37390] MasterDetail: geschachtelte MasterDetails wurden nicht korrekt befüllt

* Bug [#37392] Sollstellung: Problem mit der Berechnung bei Zweckonten

* Bug [#37404] Oberflächen: Datumsfelder: Datumswerte die über den Button eingegeben (angeklickt) werden, werden nicht gespeichert

* Bug [#37460] Hintergrunddienste: Beim Start über die Oberfläche wird lastrun/nextrun nicht gesetzt

* Bug [#37555] Schnellerfassung: Probleme mit produktspezifischen Oberflächen 

* Bug [#37585] Schnellkontakt: Nachträglich hinzugefügt E-Mail Adresse wird automatisch verworfen
Schnellkontakt lässt nun per Hand erfasste E-Mail-Adressen im To zu.

* Bug [#37597] Rechtschreibung: Strasse -> Straße in einigen Feldern

* Bug [#37598] Sollstellung: manuell erfasste Lastschriften werden nicht gezogen

* Bug [#37649] Oberfläche: Searchbox: wird teilweise nicht sauber gesetzt und damit versehentlich gelöscht

* Bug [#37655] Adresse_Rollen: Anzeige verschönert

* Bug [#37661] Sollbuchungen: manuelles Bearbeiten löscht Transaktionsnummer
Speichern einer Sollbuchung mit Transaktionsnummer hat diese entfernt. Das Verhalten wurde korrigiert.
Die Transaktionsnummer wird nun nicht mehr entfernt.

* Bug [#37681] Suchdialog: Suche nach Key/ID möglich

* Bug [#37724] Duplikate: Dubletten wurden teilweise nicht gefunden

* Bug [#37727] Buchungen zuweisen: Sollstellungen ohne Währung können nicht verbucht werden (sollten Fehlermeldung liefern)

* Bug [#37760] Oberfläche: Searchbox: Problem mit Feldern aus mehreren Tabellen

* Bug [#37762] Beteiligungen_Eigenschaften: Funktion überarbeitet

* Bug [#37766] Produkte_Wechselkurse: Fehlerbehandlung erweitert und Hinweise eingebaut

* Bug [#37780] Vermittler_Auswertungen: Überarbeitung und Fehlerbehebung

* Bug [#37810] Datenberichte: Summen werden teilweise nicht angezeigt

* Bug [#37864] Fortschrittsanzeigen: teilweise schon laufende Prozesse werden noch mit "Start" angezeigt

* Bug [#37917] Kampagne: Berichte mit komplexen Namen können nicht ausgewählt werden 

* Bug [#37918] Kopieanschreiben: PDF Berichte als Anschreiben werden nicht befüllt

* Bug [#37950] Stapelbuchung: Fehlermeldung bei Suche nach Beteiligung/Vertrag

* Bug [#37969] Zahlungsverkehr: Monaco ist ein SEPA-Land

* Bug [#37995] Produkte_Wertarten: ID darf nicht leer sein
Validierung für ID eingebaut (not empty)

* Bug [#37996] Berechnungen: beschleunigte Berechnung hat Probleme mit nicht gefüllten Datumsfeldern in Werten

* Bug [#38004] Sektionsbasierte Berichte: Doppelklick auf Gruppe oder Details erstellt fehlerhaften Code im Script

* Bug [#38005] Stapelbuchung: Buchungssumme von Buchungen in einem offenen Posten verändern den offenen Rest des Posten nicht

* Bug [#38021] Backup: Fortschrittsanzeige bei Restore fehlerhaft oder nicht sichtbar

* Bug [#38030] Stapelbuchung: Buchung aus offenen Posten löschen sollte nicht den Posten komplett auflösen sondern korrigieren.

* Bug [#38031] Datenbankoptimierung: Benutzer sollte sofortiges Feedback über laufende Aktionen bekommen

* Bug [#38032] Provisionstest: Benutzer sollte sofortiges Feedback über laufende Aktionen bekommen

* Bug [#38084] Belegexport: Funktion exportiert nicht vollständig

* Bug [#38095] Scriptcompiler: Fehlerhafte Scripte sollten nicht zum fehlenden Scripten in anderen Masken führen

* Bug [#38118] Unter bestimmten Konstellationen kann es beim Selektieren einer Bankbuchung im Verbuchungs-Dialog zum Absturz kommen.

* Bug [#38120] Produkt_Übertragungen: zeigt Einträge nicht auf den Produkt eingegrenzt an

