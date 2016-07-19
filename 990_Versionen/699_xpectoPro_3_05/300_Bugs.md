* Bug [#27726] Archivaufkleber drucken: zusätzliches Ereignis wurde erzeugt

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

