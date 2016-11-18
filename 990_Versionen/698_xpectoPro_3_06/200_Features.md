* Feature [#35335] Adressmaske

Das Feld Geburtsland auf der Adressmaske ist jetzt eine Search-Box.

* Feature [#36403] Offene Posten Maske im Vertrag, Produkt bzw. der Beteiligung

   Anpassung der Spalten je nach Sichtweise

* Feature [#36663] Stapelbuchungsdialog - Festschreiben von Buchungen

   Warnhinweis mit möglicher Blockierung anderer Benutzer wegen Sperrung der Buchungsdatentabelle beim Festschreiben der Buchungen
   
* Feature [#37049] Stapelbuchungsdialog - Summenanzeige im Filter

   In der Liste mit den Buchungen können nun im Stapelbuchungsdialog nach der Filterung die Summen anzeigt werden.
   
* Feature [#37131] Geldwäschegesetz

   Die Geldwäschegesetz Sorgfaltspflicht kann jetzt in der Person und zusätzlich beim Vertrag angegeben werden.
   
* Feature [#37136] Hinweis auf Drittrechte bei Konten-Verwendung

   Bereits bisher wurde bei der Auswahl einer Bankverbindung auf dem Reiter [Konten-Verwendung] ein Hinweis auf vorhandene Drittrechte angezeigt. Jetzt wird zusätzlich direkt auf der Maske auf Drittrechte hingewiesen, auch wenn die Bankverbindung nicht geändert wird.
   
* Feature [#37140] Berechnungen nach EStG § 15a und § 15b

   Die Benutzung der 15a/b Berechnung in den Berechnungen erfolgt über den neuen Typ "Modul". Vorab muß das Kaptialkonto bestimmt und das Ergebnis verteilt sein.
   Die Konfiguration der einzelnen Wertarten und Bedingungen ist in zwei Ebenen zu machen:
  
   * Modul-Konfiguration
   Durch den Klick auf die Modul-Konfiguration können folgende Parameter eingestellt werden:
   # Modus: 15a oder 15b
   # Berechnungsbasis: Alle Wertarten für das Kapitalkonto und für das zu verteilende Ergebnis
      Die Wertarten dürfen dabei in eigenen Zeilen stehen und können ein Vorzeichen (-/+) haben
      Die Summierung dieser Werte erfolgt über aktive Werte innerhalb der Periode.
   # Ausgabe: In welche Wertart sollen die "Verrechenbaren Verluste" gespeichert werden und welchen Text sollen diese Werte erhalten.
      (An den Text wird automatisch die aktuelle Periode angehängt.) Zusätzlich wird diese Wertart auch für die Summierung der "Verrechenbaren Verluste"
      benutzt. Diese werden über den gesamten Vertrag (15b) oder über die letzten 10 Jahre summiert (15a).
      
   * Berechnungs-Konfiguration
   Das Modul liefert als Standardwert das "Anrechenbare Ergebnis" zurück und wird mit der "Wertart" der Berechnung gespeichert. Als Text
   für diese Werte wird der "Name" verwendet. (wie immer) Um echte Werte zu bekommen (und nicht nur 0er-Werte mit korrekter Bewertung),
   muss als Zinsmethode "Endstand" und als Zähler/Nenner jeweils 1,00 eingegeben werden. Damit wird die Bewertung 1:1 in den Betrag übernommen.
   
* Feature [#37176] Erfassung der CRS/FATCA-Selbstauskunft

   Möglichkeit zur Erfassung der CRS/FATCA-Selbstauskunft und der resultierenden Meldungspflicht in der Personenansicht. Die Erstellung der CRS-XML-Daten wird im Meldecenter von aifExpert erledigt.
   Die Klassifizierung der Person/Firma kann ebenfalls direkt im Adressdialog erfolgen. Die entsprechende Auswahlliste kann individuell gepflegt werden.
   
* Feature [#37782] Vertrag_Salden

   Spaltenbreite für die ID-Spalte vergrößert.
   
* Feature [#37795] Gesellschaften - Reiter Allgemein

   Das Gesellschaftskürzel ist nun nicht mehr änderbar.

* Feature [#37949] Buchungen zuweisen - Sammelaufträge auflösen

   Über den neuen Knopf in der Liste "Sammelauftrag auflösen" kann der jeweilige Sammler auf "eingelöst" gesetzt werden. 
   Das ist insbesondere für Sammler interessant die als Einzelbuchungen schon verbucht wurden und es keine Sammelbuchung auf dem Kontoauszug gegeben hat. 
   Die Liste der Sammler wird dadurch übersichtlicher.

* Feature [#37960] Scan-Manager: Einzelne Datei-Scannen per Shift-Klick

   Im Scan-Manager kann jetzt anstatt aller Dokumente in der Scan-Inbox optional nur ein einzelnes Dokument verarbeitet werden, indem man beim Klick auf [Start] die Shift-Taste gedrückt hält.

* Feature [#37984] Datentypänderungsmeldung nach Softwareupdate deaktiviert

   Die Meldung, dass sich ein Datentyp einer Spalte geändert hat wurde nun deaktiviert und wird nun nur noch intern protokolliert.

* Feature [#38267] Standardwährung der Bankverbindung bei Neuanlage

   Der neue Parameter BankAccountDefaultCurrency gibt die Standardwährung für neue Bankverbindungen an. Im Auslieferungszustand wird immer EUR gesetzt, das kann aber frei geändert werden.
 
* Feature [#38272] Rückfragen und Kommunikation über das Ticket-System

   Neuer Status "rückfrage", wenn der Support Rückfragen zu einem Ticket hat. Rückfragen können über die Ticket-Beschreibung beantwortet werden. Bei jeder Ergänzung der Beschreibung wird automatisch eine Trennlinie, das Datum und die E-Mail-Adresse des Benutzers eingefügt.

* Feature [#38295] Synchronisation

   Optimierung der Synchronisation beim Übermitteln der Löschungen.
   
* Feature [#38348] Rechtesystem

   Überarbeitung des Dialogs zum Einstellen der Benutzer- und Gruppenrechte.
   
* Feature [#38349] Rechtesystem

   Erweitertes Recht für Gesellschaften (DataShowHideCorporation), welches das Recht DataShowHide2A ersetzt, das sich auch direkt auf alle Produkte, Verträge und Beteiligungen auswirkt.
   
* Feature [#38358] Erweiterung der Länder-Tabelle um 3-stellige ISO-Länder-Kürzel

   Die Länder-Tabelle (08) enthält jetzt zusätzlich 3-stellige ISO-Länder-Kürzel (bisher nur 2-stellige)
   
* Feature [#38409] Buchungen zuweisen

   Die aufklappende Liste zur Auswahl der Kontos wurde verbreitert.
   
* Feature [#38447] Erstellungen des Zahlungsverkehr - Auszahlungskonto nach Währung wählbar

   Die Erstellung des Zahlungsverkehr kann jetzt mehrere Bankverbindungen nutzen und frägt je Währung nach.
   Bei Berechnungen kann die Bankverbindung für Fonds- und Hauswährung getrennt festgelegt werden.
   
* Feature [#38508] Neues Feld Vorgang bei Legitimationsdaten

   Auf der Maske für die Legitimationsdaten gibt es ein neues Feld Vorgang für eine eventuelle Vorgangs-Nummer (z.B. bei Online/Video-Identifizierung)
   
* Feature [#38593] Adressmaske - Zusatzdaten Person/Firma und Steuern in Reitern organisiert

   Für die Erweiterung der Maske benötigen wir mehr Platz. Die Zusatzdaten für Person und Firma sind nie gemeinsam nötig, die Steuerdaten werden nur sporadisch aktiv benutzt. Durch die Zusammenlegung der Daten entsteht Platz für GWG/CRS/FATCA.
   
* Feature [#38650] Berechnungen: neuer Berechnungstyp "Modul" für integrierte und von xpecto gepflegte Funktionen

   Die Darstellung der Berechnungstypen auf der Maske Berechnungen_Parameter hat sich verändert. Die einzelnen Möglichkeiten werden jetzt alternativ dargestellt und sind über Optionsbuttons auswählbar.
   Für die einzelnen Einstellungen zu den Berechnungstypen ist damit mehr Platz. Den neuen Typ "Modul" kann man über eine mitgelieferte, zusätzliche Oberfläche konfigurieren. Das System ist einfach erweiterbar und
   ermöglicht individuelle Einstellungsdialoge für die von uns gelieferten Module.
   
* Feature [#38665] aifExpert: Druckvorschau im Risikomanager

* Feature [#38682] Nachschlagsliste TwoFactorAuthMethods geändert in ZweiFaktorAuthMethode (Listenbezeichnungen einheitlich deutsch)

* Feature [#38762] Tracer: Löschung von Datensätze

   Wenn im Tracer Datensätze mit Änderungsverfolgung gelöscht werden erscheint bei Benutzern mit Admin-Rechten eine Nachfrage, ob auch abhängige Datensätze mitgelöscht werden sollen.

* Feature [#38790] Nachschlagsliste für den Bildungsstand

   Neuer Eintrag "Kein Abschluss" (KA) in der Nachschlagsliste BilStand (Höchster Bildungsabschluss).

* Feature [#38821] Zahlungsverkehr: Unterschiedliche Konten bei unterschiedlichen Währungen je Produkt

   Bei der Erstellung des Zahlungsverkehrs werden jetzt mehrere Konten unterstützt. Das System fordert den Benutzer für jede neue Währung auf das entsprechende Konto zu wählen.
   Für die Hauswährung kann das entsprechende Konto direkt in den Berechnungen hinterlegt werden. Die häufige Kombination aus Fonds-/Hauswährung kann damit direkt vorkonfiguriert werden.
   
* Feature [#38849] Wiedervorlagen/Prozesse können jetzt auch für beliebige Personen angelegt werden (bisher nur für Vermitler/Kunden/Verträge).

* Feature [#38877] xpectoPro enthält jetzt Funktionen für die Sanktionslisten aus EU, UK und US. Für die PEP-Liste ziehen wir die (in der EU) ziemlich vollständige Liste aus der Wikipedia. Die Funktion kann

   direkt über den Knopf neben dem Feld Nachname in der Maske "Adresse/Allgemein" ausgeführt werden. Die entsprechenden Listen können direkt heruntergeladen werden, der Import dauert
   aber in der Regel 1-2 Stunden. Die Treffer werden in einem kleinen Dialog gesammelt angezeigt. Es werden 4 Felder in die Prüfung einbezogen: Nachname, Vorname, Firmennname und Geburtsdatum.
   Als Test können Politiker benutzt werden (Nachname=Obama, Vorname=Barack, Geburtsdatum + Firma=leer)

* Feature [#38964] Wunschversand - Standardeinstellung verändert

   Die Standardeinstellung für den Wunschversand (Einstellung DefaultDesiredShippingType) wurde nun (für neue Datenbanken) von "E-Mail" auf "Post" geändert.
   Außerdem wurde die Standard-Einstellung für den zu versendenden E-Mail Bericht (Einstellung DesiredShippingTypeEMailReport) auf "E-Mail-Anschreiben bei Wunschversand" gesetzt.
   
* Feature [#38968] Neues Vertragsfeld Vertriebsneutral

* Feature [#38977] Legitimation

   Neue Option "Ungültig" bei Legitimationsprüfung
   
* Feature [#39018] HTML-Berichte

   Die Kopf- / Fußzeile kann nun aus anderem HTML-Bericht verwendet werden.
   
* Feature [#39019] Bearbeiten einer Adresse

   Beim Bearbeiten einer Adresse/Rolle wird nun in der Titelzeile der gerade bearbeiteten Adresse die ID des Datensatzes angezeigt.
   
* Feature [#39020] Beteiligungsspezifische Adressen

   In der Liste der Beteiligungsspezifischen Adressen wird nun die ID des Link- und Zieldatensatzes angezeigt.
   
* Feature [#39157] Adressen - Abweichende Adressen pro Vertrag

   Analog zu den Adressen auf Beteiligungsebene ist es nun möglich (im Reiter Rollen) pro Vertrag eine oder mehrere Adressen pro Vertrag zu hinterlegen.
   Für den Druck von Schreiben bzw. Kopie-Schreiben wird (wie bei Adressen auf Beteiligungsebene) die Suche nach der zu verwendenden Adresse (für einen Vertrag) abgebrochen, wenn beim gewählten Vertrag eine entsprechende Adresse hinterlegt ist.
   Somit gibt es keinen Fallback auf die Beteiligungsadresse bzw. die normale Adresse.
   Es müssen somit alle für einen speziellen Vertrag zu verwendenden und abweichenden Adressen vollständig erfasst werden.
   
* Feature [#39160] Druckvorschau - Verbesserte Anzeige der Kopieschreibenempfänger

   In der Druckvorschau wird nun angezeigt wer der Empfänger des Original-Schreibens ist und welche Person(en) eine Kopie des Schreibens erhalten.
   Diese Funktion berücksichtigt sogar die Beteiligungs- bzw. Vertragsspezifischen Empfänger/Adressen.
   
* Feature [#39229] Filtertree: durchsuchbare Felder festlegen 

   Die durchsuchbaren Felder können jetzt frei festgelegt und auch eingeschränkt werden.
   
* Feature [#39237] Filtertree: Suche nach einzelnen Feldern PLZ=84030 oder PLZ:84030

   Es können jetzt im Filtertree zusätzlich noch direkte Suchen für einzelne Felder angegeben werden. Die Suche "PLZ=84030 Land:DE" sucht alle Kunden (oder Vertriebspartner) in 84030 Landshut, Deutschland.
   Als Trennzeichen kann sowohl ein Gleichheitszeichen als auch ein Doppelpunkt benutzt werden. 
   Als Feldname kann der FriendlyName, die FieldID, der SQL-Feldname oder der SQL-Feldname ohne Tabellenkürzel angegeben werden. 
   
* Feature [#39277] Funktion für die xpecto Alarmierung bei kritischen, automatisierten Funktionen.

* Feature [#39279] Erzeugung des Zahlungsverkehrs - Zusammenfassung der verschiedenen Fehler

   Bei der Erzeugung von Zahlungsverkehr aus offenen Posten, werden viele Zustände überprüft die verhindern, dass der Zahlungsverkehr erstellt werden kann. Der neue Fehlerdialog fasst alle Probleme in einer einheitlichen Weise zusammen und ermöglicht den Export einer Einzelliste.
   
* Feature [#39285] DataGrids: neue Option "zu Kampagne hinzufügen"

* Feature [#39286] Tracer - Button "Kampagne" um Auswahl der Kampagnenart erweitert

   Aus dem Abfrage-Tracer heraus kann nun ausgewählt welche Art der Kampagne gestartet werden soll.
   Aktuell gibt es die 2 Arten: "Dynamische Daten (Abfrage speichern)" und "Statische Daten (Aktuelle Liste speichern)".
   Bei der Dynamischen Kampagne wird die Abfrage bei jeder Ausführung der Kampagne erneut Ausführung und die aktuellen Daten neu geladen.
   Bei der Statischen Kampagne hingegeben werden die Ergebnisdatensätze, welchem beim Erzeugen der Kampagne vorhanden waren, tatsächlich gespeichert. Diese Liste verändert sich somit bei einer späteren Ausführung nicht und liefert immer die gleichen/ursprünglichen Ergebnisse.
   
* Feature [#39287] Kampagnen: Schaltfläche zum entfernen eines Datensatz aus einer statischen Kampagne eindeutiger benannt: statt "Aus Liste löschen" => "Ausgewählte Empfänger entfernen"

* Feature [#39291] Menüpunkt "Zu Kampagne hinzufügen"

   Textergänzung des Popups für die Kampagnenauswahl "statische Kampagne".

* Feature [#39292] Überweisungen und Lastschriften in CZ mit CZK

   Überweisungen und Lastschriften die zwischen CZ-Konten in CZK stattfinden, werden jetzt automatisch im ABO/UHL1-Format erzeugt.
   
* Feature [#39314] Rechtesystem

   Die DataHideXX-Rechte können jetzt auch als verbietende Rechte angegeben werden. Damit können einzelne Daten bei bestimmten Benutzern/Gruppen einfach unterdrückt werden. (z.B. bestimmte Gruppen von Vermittlern)
   
* Feature [#39559] Kontodaten zuweisen: Tastaturkürzel Strg+S 

   Mit dem üblichen Tastaturkürzel kann jetzt auch in diesem Dialog gespeichert werden.
   
* Feature [#39579] Buchungen zuweisen

   verbesserte Fortschrittsanzeigen beim Aufteilen der Offenen Posten
   
* Feature [#39599] Backupfunktion: Wiederherstellen einer Datenbank

   Beim Wiederherstellen einer Datenbank werden einzelne Spalten, die in der Zieldatenbank nicht vorhanden sind, auf Nachfrage erzeugt.
   
* Feature [#39658] Berechnungen: Spaltensortierung angepasst

   Die Spalte für die Buchungssumme der Werte wird nun weiter vorne angezeigt.
   
* Feature [#39666] Die neue Scriptengine wird jetzt auch für Berechnungen benutzt. Module und Scripte werden damit identisch behandelt. Achtung:

   folgende Methoden müssen auf "Overrides" gestellt werden: FondsInterestCalculation, FondsReturnCalculation, FondsTaxCalculation
   Die Patch-Funktion versucht dies automatisch zu erledigen. Die Scripte sind damit inkompatibel zwischen den beiden Versionen.
   Die Berechnungen können jetzt ganz allgemein 3 Einsprungpunkte benutzen:
   
   * FondsCalculation: Berechnung der Bewertungen, je Vertrag oder Beteiligung
   * PostFondsCalculation: Berechnungen für alle Werte/Buchungen in einem Aufruf (vor einer evtl. Gewinnverteilung)
   * FondsTaxCalculation: Berechnungen von Steuern oder anderen nachgelagerten Dingen auf Basis der Buchungen je Vertrag (nur für Vertragsebene), wird beim erzeugen der Buchungen aufgerufen
   
* Feature [#39713] Benutzerrechte - Priorität für Gruppen

   Die Überlagerung von Rechten aus Benutzergruppen können nun über eine numerische Priorität gesteuert werden. Default wird immer als erstes angewandt, danach werden Domänen-Gruppenmitgliedschaften in der angegebenen Reihenfolge (aufsteigend) angewandt, danach xpecto-interne Benutzergruppenzuordnungen.
   Das bedeutet, dass eine Gruppe mit einem höheren Wert, bereits getroffene Einstellungen aus den niedriger priorisierten Gruppen überschreiben kann.
   Als letztes werden dann noch die Benutzerspezifisch spezifizierten Rechte angewandt.

* Feature [#39729] Benutzerrechte: Effektive Berechtigungen für den ausgewählten Benutzer anzeigen

    In der Benutzerverwaltung können nun, bei Verwendung einer auf ActiveDirectory basierenden Windows-Domäne, die effektiven Berechtigungen für den ausgewählten Benutzer angezeigt werden.
    
* Feature [#39774] MT940 Bankdatenimport: Unterstützung für Format-Abweichungen in Österreich

* Feature [#39791] Buchungen zuweisen: Retourenbehandlung verbessert

   Retouren werden meist direkt von der Bank mit Gebühren belegt. Der Betrag weicht damit vom Ursprungsbetrag ab. Die Erkennung dieser Gebühr wurde nun verbessert:
   Die beiden Parameter ImportAssignFeePercent und ImportAssignFeeFix geben die maximale Gebühr an die in einem Posten stecken kann. Die Berechnung erfolgt mit folgender Formel:
   MaximaleGebühr = ImportAssignFeeFix + (Buchungssumme * ImportAssignFeePercent). Wenn die Retoure jetzt um weniger als die berechnete MaximaleGebühr reduziert ist, wird der Posten
   trotzdem erkannt. Im nächsten Stable-Release gibt es eine neue Vorschlagsfunktion für Buchungen, die Verbuchung des Rests ist dann wesentlich komfortabler.
   
* Feature [#39809] Überarbeitung der Mitarbeiter Stammdaten Maske

* Feature [#39812] Oberflächenaktualisierung Adresse_Einfach

* Feature [#39900] DMS Ereignistypen

   Neuer DMS-Typ Selbstauskunft
   
* Feature [#39926] Überarbeitung Produkt_Zusatzdaten

   Neues Feld für die GIIN angezeigt.
   
* Feature [#39927] Adressmaske - GIIN-Feld

   In der Adresse kann nun (analog zum Produkt) die GIIN erfasst werden.
   
* Feature [#39943] Adressen auf Beteiligungsebene - Prüfung der Verwendung auf Eindeutigkeit

   Bei der Anlage einer Beteiligungsspezifischen Adresse wird nun geprüft, ob es bereits eine Adresse mit der gleichen Verwendung (z. B. Post) zu dieser Beteiligung gibt.
   Ist dies der Fall, so erhält der Benutzer vor dem Speichern die Möglichkeit zu entscheiden welche der beiden Adressen die gewählte Verwendung (z. B. Post) erhalten soll.
   
* Feature [#39963] Legal Entity Identifier (LEI): Prüfroutinen und Abfrageschnittstelle integriert

   Für die Suche und Prüfung der LEI (Legal Entity Identifier) wurden Schnittstellen zum Portal openleis.com eingebaut. Die Schnittstelle ist aktuell nur intern verfügbar. 
   
* Feature [#40004] Customform-Designer: Aktionen rückgängig machen

* Feature [#40169] Änderungsverfolgung: Alle Änderungen protokollieren

   xpectoPro protokolliert nun jede Datenänderung. Die bisher selektive Protokollierung für wichtige Tabellen (über LogTableChanges) wird nun auf alle Daten ausgedehnt. 
   Öffentliche Tabellen (Banken, Orte ...) und binäre Daten werden nicht protokolliert. Bei Massentabellen (Buchungen, Werte ...) wird die Erstellung des Datensatzes
   direkt im Datensatz selbst protokolliert, die Änderungsverfolgung startet hier bei der nachträglichen manuellen Änderung oder Löschung.
   
* Feature [#40198] Buchungen zuweisen: Verbuchung der Rücküberweisungen/Rücklastschriften vor Auflösung des Sammlers verbieten

   Ab sofort ist das Verbuchung der Rücküberweisungen/Rücklastschriften vor Auflösung des Sammlers verboten.
   
* Feature [#40248] eBrief Dialog - Anzeige des Suchnamens zu den Dokumenten

* Feature [#40355] Veranstaltungen auf Gesellschaftsebene

   Veranstaltungen erlauben jetzt Teilnehmer aus mehreren Produkten einer Gesellschaft.
   
* Feature [#40361] Erweiterung für A2A

   Beim starten der Software mit TestDB (z. B. nach einem Softwareupdate von xpectoPro) werden nun auch bestimmte Funktion in A2A aktualisiert.
   
* Feature [#40439] PEP: direkter Hinweis in Kunde_Kopfzeile

* Feature [#40441] Materialbestellung und Materialverwaltung

   xpectoPro enthält ein optionales Modul für die Verwaltung von Vertriebsmaterialien und deren Bestellungen durch die Vertriebspartner
   Die Funktion kann nach einer Freischaltung über den Reiter "Individual" aufgerufen werden.
   
* Feature [#40442] Dateibereitstellung für Vertriebsmitarbeiter im Webportal

   Über den optional Reiter "Dateibereitstellung" kann nun Vertriebsmitarbeitern direkt eine Datei im Portal zum Download bereitgestellt werden.
   
* Feature [#40456] Vertrag_Drittrechte: Überarbeitung der Personen/Kontoauswahl
