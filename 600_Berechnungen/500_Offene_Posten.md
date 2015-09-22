Offene Posten Liste dient als Nebenbuch der Buchführung. In der Nebenbuchhaltung wird eine nicht bezahlte Rechnungsposition auf dem Debitorenkonto bis zum Zeitpunkt der Zahlung (automatisch) als offener Posten geführt. 
Mit Hilfe von xpectoPro erhalten Sie eine vollständige Liste aller offener Rechnungen. Innerhalb dieses Dialoges können Sie weitere Funktionalitäten verwenden wie Überweisung, Lastschrift oder Posten verrechen.

 Unter diesen Menüpunkt werden Ihnen alle offenen Posten angezeigt. Dabei werden alle  zugehörigen Konten berücksichtigt – also es  werden sowohl Forderungen als auch Verbindlichkeiten aufgelistet.

Wenn Sie aber vorher eine Beteiligung ![](http://xpecto.github.io/docs/img/img_1441372403820.png) oder einen Vertrag ![](http://xpecto.github.io/docs/img/img_1441373565478.png) markiert haben, dann werden nur die zugehörigen offene Posten angezeigt.

Sie erreichen den *xpectoPro OPOS Verarbeitung* Dialog über *Berechnungen → Offene Posten*, oder unter *Berechnungen →Zahlungsverkehr → OPOS berechnen*.

Offene Posten können miteinander verrechnet werden, das heißt Forderungen bzw. Verbindlichkeiten können zusammengefasst werden oder Forderungen können mit Verbindlichkeiten gegeneinander aufgerechnet werden. Rechnung mit einer Gutschrift ausgleichen.

Der *OPOS Verarbeitung* Dialog berechnet die Buchungen für einstehende Einzahlungen und Auszahlungen. Diese Buchungen werden auf Basis von einen OPOS-Konto. Der OPOS-Konto muss unter *Produkte → Konten*  als  OPOS-Konto angelegt werden. 

Der *OPOS Verarbeitung* Dialog enthält in dem oberen Bereich die Filterbedingungen, in der Mitte die Liste der 
Posten für alle Beteiligungen, und unten die Details der Buchungen.

![](http://xpecto.github.io/docs/img/img_1441702035355.png)

Überweisungen werden für Kreditoren (Gläubiger) erstellt. Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440769189875.png), um eine Überweisung zu betätigen. 
Eine Lastschrift ist die Umkehrung der Überweisung. Der Zahlungsempfänger gibt hier seiner Bank den Auftrag, vom Konto des Zahlungspflichtigen bei dessen Bank (Zahlstelle) einen bestimmten Betrag abzubuchen.
Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440769218414.png) starten Sie eine Lastschrift. 

Wählen Sie in dem folgenden Dialog das Ausführungsdatum an. 

![](http://xpecto.github.io/docs/img/img_1441702086158.png)

Nachdem Sie den Zahlungszweck und abgehende Bankkonto eingegeben haben, öffnet sich der *Zahlungsverkehr*-Dialog. 

![](http://xpecto.github.io/docs/img/img_1441702135963.png)

Aus einer OPOS Buchung wird eine Sollbuchung erstellt. Es wird hier eine Soll-Buchungssatz erstellt. Im oberen Bereich sind die gerade erstellten Sollbuchungen zu sehen. 

Mit den Funktionen *Datenprüfung* und *Dateien erzeugen* können die Dateien dann wirklich erzeugt werden. Es werden die Sollbuchungen zu einer Transaktion zusammengefasst und zugleich wird ein Datensatz für den Zahlungsverkehr erzeugt. 

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440771677497.png) werden die Daten auf Korrektheit verifiziert, und wenn die geprüfte Daten in Ordnung sind dann wird die *Dateien erzeugen* Schaltfläche aktiv. 
Durch einen Doppelklick auf Details![](http://xpecto.github.io/docs/img/img_1440771513947.png), können Sie z.B. die Fehler der Datensätze sehen, falls die vorhanden sind.

![](http://xpecto.github.io/docs/img/img_1441702289501.png)

Durch einen Doppelklick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440771590046.png),werden die Sollbuchungen in Zahlungsdateien umgewandelt. Dafür werden eine CSV-, PDF- und XML-Datei erstellt, in einem unter *Extras → Einstellungen → Bank Pfad*, angegebener Ordner. 
 
![](http://xpecto.github.io/docs/img/img_1441702499437.png)