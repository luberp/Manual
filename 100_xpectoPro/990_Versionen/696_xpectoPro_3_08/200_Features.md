* Feature [#38231] Ereignisse auf Personenebene einbauen (Tabelle EK mit EK_AddressID)
  
  Ereignisse und Eigenschaften auf Personenebene
  Neue Reiter "Ereignisse" und "Eigenschaften" auf Personen-/Adressebene analog den Kundenereignissen bzw. Kundeneigenschaften

* Feature [#40377] neue clVBA-Funktion um ein (Support-) Ticket aus xpectoPro per Code zu erzeugen

  Neues Ticket per Code erzeugen
  neue clVBA-Funktion um ein (Support-) Ticket aus xpectoPro per Code zu erzeugen.

* Feature [#40927] PEP Anzeige umstellen auf Listenansicht
  
  PEP Anzeige
  Die Anzeige der PEP Daten bei der PEP Prüfung (über einen Button in der Adresse) wurde nun auf eine Listenansicht umgestellt.

* Feature [#41234] Oberflächendesigner - Neues Feld anlegen - Datentyp Blob aufnehmen
  
  Oberflächendesigner: Neues Feld anlegen
  Datentyp Blob z. B. für Bilder aufgenommen

* Feature [#42664] Rechtesystem - Neues Recht DataHide20 mit Filterbedingung
  
  Rechtesystem - Neues Recht DataHide20 mit Angabe einer Filterbedingung

* Feature [#43358] BD_Anlass (60816) neu: Anlass der Buchung, vgl. WE_Anlass

  Beim Einbuchen von Werten wird nun automatisch auch das neue Feld BD_Anlass gesetzt.

* Feature [#43580] Maske Vertrag_OffenePosten: Neuer Button zum Aktualisieren von OPs auf der OPOS-Maske

  Ein Aktualisieren-Button berechnet den OP-Rest aller bestehenden offenen Posten des Vertrags neu.

* Feature [#43746] Sammlung von Druckdokumenten (Neuer Drucker "Sammeln")
  
  Sammlung von Druckdokumenten für späteren gesammelten Druck
  Es steht nun einen neuer Drucker "Sammeln" zur Auswahl.
  Achtung Änderung: Wunschversand "Nur Archiv" legt nun auch einen Spoolereintrag an, aber mit "Printed to Drucker:Sammeln".

* Feature [#44002] Ticketsystem in xpectoPro - Alle Tickets als Typ Support anlegen
  
  Das Anlegen eines neuen Tickets wurde vereinfacht. Initial werden nun alle neuen Tickets dem Support zugeordnet und das Support-Team
  passt im Zweifelsfall den Typ dann an.

* Feature [#44178] Person - Adresse - Steuer & Recht - FATCA/CRS: Zusätzliches Feld + Anpassung Status

  Die Kennzeichnung der entsprechenden Meldepflicht ist weiter verfeinert worden. Je Meldeverpflichtung kann nun entweder "Keine 
  Meldepflicht", "Meldepflicht gemäß Selbstauskunft" oder "Meldepflicht aufgrund Indizien" ausgewählt werden.

* Feature [#44325] Adressen: Prüfung und Komfortbefüllung direkt über Strasse
  
  Adressen: Komfortbefüllung und Prüfung von Strasse, Land, PLZ und Wohnort
  Bei der Eingabe der Strasse kann jetzt direkt der Ort angehängt werden. Die Eingabe wird dann direkt per Webschnittstelle geprüft und   die Felder Strasse, Land, PLZ und Wohnort werden direkt befüllt. Die  Aktion wird nur ausgeführt, wenn der Wohnort nicht schon befüllt
  ist, zudem muss der Suchtext (im Feld Strasse) ein Komma enthalten. Gut funktioniert Suchbegriffe wie "Benz 13, Landshut" oder "AB
  12, Hamburg".

* Feature [#44327] Geocoding: alternativer Anbieter photon.komoot.de, wählbar über neuen Parameter GeoCodingProvider

  Geocoding: alternativer Anbieter photon.komoot.de (jetzt Standard)
  Als zusätzlicher Anbieter für die Prüfung und Lokalisierung von Adressen wurde ein deutscher Dienst von komoot.de integriert. Der
  genutzte Dienst kann über den neuen Parameter GeoCodingProvider eingestellt werden. Es sind die beiden Anbieter Google und Komoot
  möglich.


* Feature [#44498] E-Mail Versand von Berichten - Angabe von verschiedenen Empfänger E-Mail Adressen ermöglichen
  
  E-Mail Versand von Berichten - Angabe von verschiedenen Empfänger E-Mail Adressen ermöglicht
  Das "E-Mail Empfänger" Feld sowie die 2 neuen Felder "E-Mail Empfänger CC" und "E-Mail Empfänger BCC" können nun u. a. über die 
  Platzhalter-Syntax <code>%[Mein_EMailFeld_aus_der_Abfrage]%</code> mit Daten aus der SQL-Abfrage des Berichts befüllt werden.

* Feature [#44856] Sync: Parameter UseSyncPeek: benutzt beschleunigten Abgleich
  
  Synchronisation - Standardmäßig den beschleunigten Datenabgleich nutzen
  Die Synchronisation benutzt nun den neuen Parameter UseSyncPeek zum beschleunigten Abgleich der geänderten und neuen Datensätze
  standardmäßig. Diese Einstellung verringert die Dauer des gesamten Synchronisationsvorgangs erheblich.

* Bug [#43599] Bezeichung von Schnellauswahl Report
  
  In der Schnellauswahl für Reports wird nun, falls nichts selektiert ist, "Bitte wählen" angezeigt.

* Feature [#43203] Neue Funktionen fürs Web / Web-Oberflächen:
  
  SafeQuery.executeScalar()
  SafeQuery.executeScalar(defaultValue)
  SafeQuery.executeSingleRow()
