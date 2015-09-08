Offene Posten Liste dient als Nebenbuch der Buchführung. In der Nebenbuchhaltung wird eine nicht bezahlte Rechnungsposition auf dem Debitorenkonto bis zum Zeitpunkt der Zahlung (automatisch) als offener Posten geführt. 
Mit Hilfe von xpectoPro erhalten Sie eine vollständige Liste aller offener Rechnungen. Innerhalb dieser Maske können Sie weitere Funktionalitäten verwenden wie Überweisung, Lastschrift oder Posten verrechen.

 Unter diesen Menüpunkt werden Ihnen alle offenen Posten angezeigt. Dabei werden alle  zugehörigen Konten berücksichtigt – also es  werden sowohl Forderungen als auch Verbindlichkeiten aufgelistet.

Wenn Sie aber vorher eine Beteiligung ![](http://xpecto.github.io/docs/img/img_1441372403820.png) oder einen Vertrag ![](http://xpecto.github.io/docs/img/img_1441373565478.png) markiert haben, dann werden nur die zugehörigen offene Posten angezeigt.

Sie erreichen die *xpectoPro OPOS Verarbeitung* Maske über *Berechnungen → Offene Posten*, unter *Berechnungen →Zahlungsverkehr → Werte berechnen* oder unter *Zahlungsverkehr → OPOS berechnen*.

Die *OPOS Verarbeitung* Maske enthält in dem oberen Bereich die Filterbedingungen, in der Mitte die Liste der 
Posten für alle Beteiligungen, und unten die Details der Buchungen.

Offene Posten können miteinander verrechnet werden, das heißt Forderungen bzw. Verbindlichkeiten können zusammengefasst werden oder Forderungen können mit Verbindlichkeiten gegeneinander aufgerechnet werden. Rechnung mit einer Gutschrift ausgleichen.

Die Offenen Posten Maske berechnet die Buchungen für einstehende Einzahlungen und Auszahlungen. Diese Buchungen werden auf Basis von einen OPOS-Konto. Der OPOS-Konto muss unter *Produkte → Konten*  als  OPOS-Konto angelegt werden. 

Die *OPOS Verarbeitung* Maske enthält in dem oberen Bereich die Filterbedingungen, in der Mitte die Liste der 
Posten für alle Beteiligungen, und unten die Details der Buchungen.

![](http://xpecto.github.io/docs/img/img_1441702035355.png)

Überweisungen werden für Kreditoren (Gläubiger) erstellt. Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440769189875.png), um eine Überweisung zu betätigen.

Wählen Sie in dem folgenden Dialog das Ausführungsdatum an. 

![](http://xpecto.github.io/docs/img/img_1441702086158.png)

Nachdem Sie den Zahlungszweck und abgehende Bankkonto eingegeben haben, öffnet sich die *Zahlungsverkehr*-Maske.

![](http://xpecto.github.io/docs/img/img_1441702135963.png)

Aus einer OPOS Buchung wird eine Sollbuchung erstellt. Es wird hier eine Soll-Buchungssatz erstellt. Im oberen Bereich sind die gerade erstellten Sollbuchungen zu sehen. 

Mit den Funktionen *Datenprüfung* und *Dateien erzeugen* können die Dateien dann wirklich erzeugt werden. Es werden die Sollbuchungen zu einer Transaktion zusammengefasst und zugleich wird ein Datensatz für den Zahlungsverkehr erzeugt. 
Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440771677497.png) werden die Daten auf Korrektheit verifiziert, und wenn die geprüfte Daten in Ordnung sind dann werden die *Dateien erzeugen* Schaltfläche aktiv. 
Durch einen Doppelklick auf Details![](http://xpecto.github.io/docs/img/img_1440771513947.png), können Sie z.B. die Fehler der Datensätze sehen, falls die vorhanden sind.

![](http://xpecto.github.io/docs/img/img_1441702289501.png)

Durch einen Doppelklick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440771590046.png),werden die Sollbuchungen in Zahlungsdateien umgewandelt. Dafür werden eine CSV-, PDF- und XML-Datei erstellt, in einem unter *Extras → Einstellungen → Bank Pfad*, angegebener Ordner. 
 
![](http://xpecto.github.io/docs/img/img_1441702499437.png)

Eine Lastschrift ist gewissermaßen die Umkehrung der Überweisung. Der Zahlungsempfänger gibt hier seiner Bank  den Auftrag, vom Konto des Zahlungspflichtigen bei dessen Bank (Zahlstelle) einen bestimmten Betrag abzubuchen.
![](http://xpecto.github.io/docs/img/img_1440769218414.png)


![](http://xpecto.github.io/docs/img/img_1440769392486.png)
Das abgehende Bankkonto des Fonds 
![](http://xpecto.github.io/docs/img/img_1440769418756.png)

Zahlungsverkehrmaske 
Wenn keine weiteren offenen Posten im Dialog übrig bleiben, öffnet sich automatisch der Dialog Zahlungsverkehr (früherer Name Sollstellung, Menu Bearbeiten - Zahlungsverkehr).
Aus einer OPOS Buchung wird eine Sollbuchung erstellt. Es wird hier eine Soll-Buchungssatz erstellt. 

Im oberen Bereich sind die gerade erstellten Sollbuchungen zu sehen. 

![](http://xpecto.github.io/docs/img/img_1440772638410.png)

Mit den bekannten Funktionen „Datenprüfung“ und „Dateien erzeugen“ können die Dateien dann wirklich erzeugt werden. Es werden die Sollbuchungen zu einer Transaktion zusammengefasst (SB_Transaction) und zugleich wird ein Datensatz für den Zahlungsverkehr (ZV, incl. ZV_FileName und ZV_FileNamePDF, Join über den Key ZV_Transaction) erzeugt. 


 ![](http://xpecto.github.io/docs/img/img_1440771677497.png) und wenn die geprüfte Daten in Ordnung sind dann werden die Dateien erzeugen aktiv. dann auf Details ![](http://xpecto.github.io/docs/img/img_1440771513947.png)

![](http://xpecto.github.io/docs/img/img_1440772783601.png)

 Dateien erzeugen ![](http://xpecto.github.io/docs/img/img_1440771590046.png).   Dann werden eine CSV, PDF und XML.

![](http://xpecto.github.io/docs/img/img_1440772902738.png)

CSV, PDF, XML
Die erzeugte Dateien werden dann in der Liste angezeigt. 
![](http://xpecto.github.io/docs/img/img_1440773806090.png)

