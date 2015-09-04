Offene Posten Liste dient als Nebenbuch der Buchführung. Mit Hilfe von xpectoPro erhalten Sie eine vollständige Liste aller offener Rechnungen. Innerhalb dieser Maske können Sie weitere Funktionalitäten verwenden wie Überweisung, Lastschrift oder Posten verrechen.


Sie erreichen die *xpectoPro OPOS Verarbeitung* Maske über *Berechnungen → Offene Posten* oder unter *Berechnungen →Zahlungsverkehr → Werte berechnen*.

Produkt Konto OPOS - Konto

Die Offenen Posten Maske berechnet die Buchungen für einstehende Einzahlungen und Auszahlungen. Diese Buchungen werden auf Basis von unten Produkte Konto angelegter Konto.
Es geht haupsächlich um außgehender Zahlungsverkehr. Aus einer OPOS Buchung wird eine Sollbuchung erstellt. Es wird hier eine Soll-Buchungssatz erstellt. 

![](http://xpecto.github.io/docs/img/img_1440772574042.png)



![](http://xpecto.github.io/docs/img/img_1440769189875.png)

![](http://xpecto.github.io/docs/img/img_1440769218414.png)
 Ausführungsdatum
![](http://xpecto.github.io/docs/img/img_1440769342773.png)


![](http://xpecto.github.io/docs/img/img_1440769392486.png)
Das abgehende Bankkonto des Fonds 
![](http://xpecto.github.io/docs/img/img_1440769418756.png)

Zahlungsverkehrmaske 
Wenn keine weiteren offenen Posten im Dialog übrig bleiben, öffnet sich automatisch der Dialog Zahlungsverkehr (früherer Name Sollstellung, Menu Bearbeiten - Zahlungsverkehr).
Im oberen Bereich sind die gerade erstellten Sollbuchungen zu sehen. 


![](http://xpecto.github.io/docs/img/img_1440772638410.png)

Mit den bekannten Funktionen „Datenprüfung“ und „Dateien erzeugen“ können die Dateien dann wirklich erzeugt werden. Es werden die Sollbuchungen zu einer Transaktion zusammengefasst (SB_Transaction) und zugleich wird ein Datensatz für den Zahlungsverkehr (ZV, incl. ZV_FileName und ZV_FileNamePDF, Join über den Key ZV_Transaction) erzeugt. 


 ![](http://xpecto.github.io/docs/img/img_1440771677497.png) und wenn die geprüfte Daten in Ordnung sind dann werden die Dateien erzeugen aktiv. dann auf Details ![](http://xpecto.github.io/docs/img/img_1440771513947.png)

![](http://xpecto.github.io/docs/img/img_1440772783601.png)

 Dateien erzeugen ![](http://xpecto.github.io/docs/img/img_1440771590046.png).   Dann werden eine CSV, PDF und XML.

![](http://xpecto.github.io/docs/img/img_1440772902738.png)

Überweisung

![](http://xpecto.github.io/docs/img/img_1440773727879.png)


![](http://xpecto.github.io/docs/img/img_1440773653998.png)

CSV, PDF, XML
Die erzeugte Dateien werden dann in der Liste angezeigt. 
![](http://xpecto.github.io/docs/img/img_1440773806090.png)