Offene Posten Liste dient als Nebenbuch der Buchführung. In der Nebenbuchhaltung wird eine nicht bezahlte Rechnungsposition auf dem Debitorenkonto bis zum Zeitpunkt der Zahlung (automatisch) als offener Posten geführt. 
Mit Hilfe von xpectoPro erhalten Sie eine vollständige Liste aller offener Rechnungen. Innerhalb dieses Dialoges können Sie weitere Funktionalitäten verwenden wie Überweisung, Lastschrift oder Posten verrechen.

Unter diesen Menüpunkt werden Ihnen alle offenen Posten angezeigt. Dabei werden alle zugehörigen Konten berücksichtigt  - es werden sowohl Forderungen als auch Verbindlichkeiten aufgelistet.

In der klassischen Menü-Ansicht wird der Dialog OPOS Verarbeitung über Menü *Berechnungen → Offenen Posten*  oder *Berechnungen →Zahlungsverkehr → OPOS berechnen*.

In der modernen Menü-Ansicht wird die Funktion *offene Posten* über die Registerkarte *Buchhaltung* Gruppe *Buchungdaten* erreicht.

![](http://xpecto.github.io/docs/img/img_1461769970816.png)

Wenn Sie aber vorher eine Beteiligung  oder einen Vertrag markiert haben, dann werden nur die zugehörigen offene Posten angezeigt.

![](http://xpecto.github.io/docs/img/img_1461769707029.png)

Der *OPOS Verarbeitung* Dialog enthält in dem oberen Bereich die Filterbedingungen, in der Mitte die Liste der 
Posten für alle Beteiligungen, und unten die Details der Buchungen.

Offene Posten können miteinander verrechnet werden, das heißt Forderungen bzw. Verbindlichkeiten können zusammengefasst werden oder Forderungen können mit Verbindlichkeiten gegeneinander aufgerechnet werden. Rechnung mit einer Gutschrift ausgleichen.

Der *OPOS Verarbeitung* Dialog berechnet die Buchungen für einstehende Einzahlungen und Auszahlungen. Diese Buchungen werden auf Basis von einen OPOS-Konto. Der OPOS-Konto muss unter *Produkte → Reiter Konten* als OPOS-Konto angelegt werden. 

Überweisungen werden für Kreditoren (Gläubiger) erstellt. Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440769189875.png), um eine Überweisung zu betätigen. 
Eine Lastschrift ist die Umkehrung der Überweisung. Der Zahlungsempfänger gibt hier seiner Bank den Auftrag, vom Konto des Zahlungspflichtigen bei dessen Bank (Zahlstelle) einen bestimmten Betrag abzubuchen.
Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440769218414.png) starten Sie eine Lastschrift. 

Geben Sie in dem folgenden Dialog das Ausführungsdatum an. 

![](http://xpecto.github.io/docs/img/img_1441702086158.png)


Nachdem Sie den Zahlungswährung und Zahlungsverkehr eingegeben haben, öffnet sich der *Zahlungsverkehr*-Dialog. 

![](http://xpecto.github.io/docs/img/img_1461771119658.png)

Aus einer OPOS Buchung wird eine Sollbuchung erstellt. Es wird hier ein Sollbuchungs-Datensatz erstellt. Im oberen Bereich sind die gerade erstellten Sollbuchungen zu sehen. 

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440771677497.png) werden die Daten auf Korrektheit verifiziert, und wenn die geprüfte Daten in Ordnung sind dann wird die *Dateien erzeugen* Schaltfläche aktiv. 
Durch einen Doppelklick auf Details![](http://xpecto.github.io/docs/img/img_1440771513947.png), können Sie z.B. die Fehler der Datensätze sehen, falls welche vorhanden sind.



Durch einen Doppelklick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440771590046.png),werden die Sollbuchungen in Zahlungsdateien umgewandelt. Die Sollbuchungen werden zu einer Transaktion zusammengefasst, und zugleich wird ein Datensatz für den Zahlungsverkehr erzeugt. 
Bei der Erzeugung der Zahlungsverkehrsdatei werden folgende Dateien (in dem unter *Extras → Einstellungen → Bank* Pfad, angegebenen Ordner angelegt): eine CSV-Datei, PDF Datei und die SEPA-Datei (Dateiendung .xml).
 
![](http://xpecto.github.io/docs/img/img_1461770850059.png)

Durch einen Doppelklick auf die erstellte Datei kann die Datei geöffnet werden.