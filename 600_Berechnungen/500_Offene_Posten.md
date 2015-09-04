Offene Posten Liste dient als Nebenbuch der Buchführung. In der Nebenbuchhaltung wird eine nicht bezahlte Rechnungsposition auf dem Debitorenkonto bis zum Zeitpunkt der Zahlung (automatisch) als offener Posten geführt. Mit Hilfe von xpectoPro erhalten Sie eine vollständige Liste aller offener Rechnungen. Innerhalb dieser Maske können Sie weitere Funktionalitäten verwenden wie Überweisung, Lastschrift oder Posten verrechen.

 Unter diesen Menüpunkt werden Ihnen alle offenen Posten angezeigt. Dabei werden alle  zugehörigen Konten berücksichtigt – also es  werden sowohl Forderungen als auch Verbindlichkeiten aufgelistet.

Wenn Sie aber vorher eine Beteiligung ![](http://xpecto.github.io/docs/img/img_1441372403820.png) oder einen Vertrag ![](http://xpecto.github.io/docs/img/img_1441373565478.png) markiert haben, dann werden nur die zugehörigen offene Posten angezeigt.

Sie erreichen die *xpectoPro OPOS Verarbeitung* Maske über *Berechnungen → Offene Posten* oder unter *Berechnungen →Zahlungsverkehr → Werte berechnen*.
Die *OPOS Verarbeitung* Maske enthält in dem oberen Bereich die Filterbedingungen, in der Mitte die Liste der 
offenen Posten für alle Beteiligungen, und unten die Details.

Offene Posten können miteinander verrechnet werden, das heißt Forderungen bzw. Verbindlichkeiten können zusammengefasst werden oder Forderungen können mit Verbindlichkeiten gegeneinander aufgerechnet werden. Rechnung mit einer Gutschrift ausgleichen.


Öffnen Sie die Offene Posten und markieren Sie 

Produkt Konto OPOS - Konto

Die Offenen Posten Maske berechnet die Buchungen für einstehende Einzahlungen und Auszahlungen. Diese Buchungen werden auf Basis von unten Produkte Konto angelegter Konto.
Es geht haupsächlich um außgehender Zahlungsverkehr. 

Überweisungen werden für Kreditoren (Gläubiger) erstellt.
![](http://xpecto.github.io/docs/img/img_1440769189875.png)


![](http://xpecto.github.io/docs/img/img_1440773727879.png)

Eine Lastschrift ist gewissermaßen die Umkehrung der Überweisung. Der Zahlungsempfänger gibt hier seiner Bank  den Auftrag, vom Konto des Zahlungspflichtigen bei dessen Bank (Zahlstelle) einen bestimmten Betrag abzubuchen.
![](http://xpecto.github.io/docs/img/img_1440769218414.png)
 Ausführungsdatum
![](http://xpecto.github.io/docs/img/img_1440769342773.png)


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

![](http://xpecto.github.io/docs/img/img_1440773653998.png)

CSV, PDF, XML
Die erzeugte Dateien werden dann in der Liste angezeigt. 
![](http://xpecto.github.io/docs/img/img_1440773806090.png)