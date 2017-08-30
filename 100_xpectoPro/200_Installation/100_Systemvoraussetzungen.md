Prinzipiell können sämtliche Komponenten von xpectoPro (Client, Datenbankserver) auf einem Rechner installiert werden (Einzelarbeitsplatz). In diesem Fall gelten die Systemvoraussetzungen ähnlich wie für den Datenbankserver. Bei mehreren Benutzern bzw. Clients werden die Komponenten auf mehreren unterschiedlichen Rechnern installiert. Informationen und Empfehlungen für eine mögliche Aufteilung und Konfiguration entnehmen Sie bitte den folgenden Informationen. Bitte beachten Sie, dass sämtliche Angaben in diesem Dokument lediglich geschätzte Mindestanforderungen darstellen.


  Client
  
- Prozessor: Rechner der aktuellen Generation 3
- Hauptspeicher: 4 GB, empfohlen 8 GB
- Betriebssystem: 32 bit, empfohlen 64bit Windows 7, 8.1, 10
- Bildschirmauflösung: mind. 1280 x 900
- Runtime-System .NET 4.6 ist Voraussetzung und muss installiert sein


Datenbankserver

- Prozessor: Rechner der aktuellen Generation 4
- Hauptspeicher:  Abhängig vom Datenvolumen und der Anzahl der Anwender
- Betriebssystem: Bitte beachten Sie hier die Freigabeliste von Microsoft für SQL Server
- Datenbanksystem: Microsoft SQL Server 2008 R2 oder 2012, 2014
  Collation Latin1_General_CI_AS
- Festplattensystem: Performantes RAID wird empfohlen
- Netzwerklaufwerk: Die Installation von xpectoPro benötigt ca. 1 GB Festplattenspeicher. Für die integrierte Dokumentablage (anwachsend) muss zusätzlich freier Speicherplatz zur Verfügung gestellt werden.
- Speicherplatz je 1000 Anteile: Durchschnittliche Werte pro Jahr Betriebszeit, mindestens 100 MB für die DB und 1 GB für das Fileserver-Dokumentarchiv


Sonstiges

- Barcodedrucker Zur Erstellung von Registrierungscodes zur Kennzeichnung von zu archivierenden Dokumenten (z.B. Dymo, LabelWriter)
- Gesellschafterversammlungen Notebook mit HDD-Platz für eine Teil-Datenbank empfohlener Leserstift: http://www.albasca.com/webstore/product_info.php/products_id/91


Freigabe

Für xpectoPro muss eine Freigabe (z.B. xpectoPro) als UNC-Pfad (\\SERVER\xpectoPro) auf einem beliebigen Server eingerichtet werden. Alle xpectoPro-User benötigen Vollzugriff auf diesen Ordner und sämtliche Unterordner (Update, Reports, Temp, Export, Archiv, Bank, Belege).


Erläuterungen

1 Die Größe des empfohlenen Arbeitsspeichers ist wesentlich von der Anzahl der Benutzer bzw. Clients abhängig,
2 Die Datenbank sollte in den Hauptspeicher passen.
3 Hier sind mindestens 2 Kerne notwendig, empfohlen sind 4 Kerne oder mehr.
4 Für die CPU-Performanz ist immer die Performanz eines einzelnen Kerns relevant. Setzen Sie auf jeden Fall mehrkernige Datenbankserver ein, um Hintergrundprozessen ausreichend Ressourcen zur Verfügung zu stellen. Wir empfehlen min. 4 Kerne.




