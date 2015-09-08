<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>500_Offene_Posten.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Offene Posten Liste dient als Nebenbuch der Buchführung. In der Nebenbuchhaltung wird eine nicht bezahlte Rechnungsposition auf dem Debitorenkonto bis zum Zeitpunkt der Zahlung (automatisch) als offener Posten geführt.  <br>
Mit Hilfe von xpectoPro erhalten Sie eine vollständige Liste aller offener Rechnungen. Innerhalb dieser Maske können Sie weitere Funktionalitäten verwenden wie Überweisung, Lastschrift oder Posten verrechen.</p>

<p>Unter diesen Menüpunkt werden Ihnen alle offenen Posten angezeigt. Dabei werden alle  zugehörigen Konten berücksichtigt – also es  werden sowohl Forderungen als auch Verbindlichkeiten aufgelistet.</p>

<p>Wenn Sie aber vorher eine Beteiligung <img src="http://xpecto.github.io/docs/img/img_1441372403820.png" alt="" title=""> oder einen Vertrag <img src="http://xpecto.github.io/docs/img/img_1441373565478.png" alt="" title=""> markiert haben, dann werden nur die zugehörigen offene Posten angezeigt.</p>

<p>Sie erreichen die <em>xpectoPro OPOS Verarbeitung</em> Maske über <em>Berechnungen → Offene Posten</em> oder unter <em>Berechnungen →Zahlungsverkehr → Werte berechnen</em>. <br>
Die <em>OPOS Verarbeitung</em> Maske enthält in dem oberen Bereich die Filterbedingungen, in der Mitte die Liste der  <br>
Posten für alle Beteiligungen, und unten die Details der Buchungen.</p>

<p>Offene Posten können miteinander verrechnet werden, das heißt Forderungen bzw. Verbindlichkeiten können zusammengefasst werden oder Forderungen können mit Verbindlichkeiten gegeneinander aufgerechnet werden. Rechnung mit einer Gutschrift ausgleichen.</p>

<p>Die Offenen Posten Maske berechnet die Buchungen für einstehende Einzahlungen und Auszahlungen. Diese Buchungen werden auf Basis von unten <em>Produkte → Konto</em> angelegter Konto.  <br>
Es geht haupsächlich um außgehender Zahlungsverkehr. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1441702035355.png" alt="" title=""></p>

<p>Überweisungen werden für Kreditoren (Gläubiger) erstellt. Klicken Sie auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1440769189875.png" alt="" title="">, um eine Überweisung zu betätigen.</p>

<p>Wählen Sie in dem folgenden Dialog das Ausführungsdatum an. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1441702086158.png" alt="" title=""></p>

<p>Nachdem Sie den Zahlungszweck und abgehende Bankkonto eingegeben haben, öffnet sich die <em>Zahlungsverkehr</em>-Maske.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1441702135963.png" alt="" title=""></p>

<p>Aus einer OPOS Buchung wird eine Sollbuchung erstellt. Es wird hier eine Soll-Buchungssatz erstellt. Im oberen Bereich sind die gerade erstellten Sollbuchungen zu sehen. </p>

<p>Mit den Funktionen „Datenprüfung“ und „Dateien erzeugen“ können die Dateien dann wirklich erzeugt werden. Es werden die Sollbuchungen zu einer Transaktion zusammengefasst und zugleich wird ein Datensatz für den Zahlungsverkehr erzeugt.  <br>
 <img src="http://xpecto.github.io/docs/img/img_1440771677497.png" alt="" title=""> und wenn die geprüfte Daten in Ordnung sind dann werden die Dateien erzeugen aktiv. dann auf Details <img src="http://xpecto.github.io/docs/img/img_1440771513947.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1441702289501.png" alt="" title=""></p>

<p>Dateien erzeugen <img src="http://xpecto.github.io/docs/img/img_1440771590046.png" alt="" title="">.   Dann werden eine CSV, PDF und XML.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1441702499437.png" alt="" title=""></p>

<p>Eine Lastschrift ist gewissermaßen die Umkehrung der Überweisung. Der Zahlungsempfänger gibt hier seiner Bank  den Auftrag, vom Konto des Zahlungspflichtigen bei dessen Bank (Zahlstelle) einen bestimmten Betrag abzubuchen. <br>
<img src="http://xpecto.github.io/docs/img/img_1440769218414.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1440769392486.png" alt="" title=""> <br>
Das abgehende Bankkonto des Fonds  <br>
<img src="http://xpecto.github.io/docs/img/img_1440769418756.png" alt="" title=""></p>

<p>Zahlungsverkehrmaske  <br>
Wenn keine weiteren offenen Posten im Dialog übrig bleiben, öffnet sich automatisch der Dialog Zahlungsverkehr (früherer Name Sollstellung, Menu Bearbeiten - Zahlungsverkehr). <br>
Aus einer OPOS Buchung wird eine Sollbuchung erstellt. Es wird hier eine Soll-Buchungssatz erstellt. </p>

<p>Im oberen Bereich sind die gerade erstellten Sollbuchungen zu sehen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1440772638410.png" alt="" title=""></p>

<p>Mit den bekannten Funktionen „Datenprüfung“ und „Dateien erzeugen“ können die Dateien dann wirklich erzeugt werden. Es werden die Sollbuchungen zu einer Transaktion zusammengefasst (SB_Transaction) und zugleich wird ein Datensatz für den Zahlungsverkehr (ZV, incl. ZV_FileName und ZV_FileNamePDF, Join über den Key ZV_Transaction) erzeugt. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1440771677497.png" alt="" title=""> und wenn die geprüfte Daten in Ordnung sind dann werden die Dateien erzeugen aktiv. dann auf Details <img src="http://xpecto.github.io/docs/img/img_1440771513947.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1440772783601.png" alt="" title=""></p>

<p>Dateien erzeugen <img src="http://xpecto.github.io/docs/img/img_1440771590046.png" alt="" title="">.   Dann werden eine CSV, PDF und XML.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1440772902738.png" alt="" title=""></p>

<p>CSV, PDF, XML <br>
Die erzeugte Dateien werden dann in der Liste angezeigt.  <br>
<img src="http://xpecto.github.io/docs/img/img_1440773806090.png" alt="" title=""></p>

<hr>

<p>Offene Posten Liste dient als Nebenbuch der Buchführung. In der Nebenbuchhaltung wird eine nicht bezahlte Rechnungsposition auf dem Debitorenkonto bis zum Zeitpunkt der Zahlung (automatisch) als offener Posten geführt.  <br>
Mit Hilfe von xpectoPro erhalten Sie eine vollständige Liste aller offener Rechnungen. Innerhalb dieser Maske können Sie weitere Funktionalitäten verwenden wie Überweisung, Lastschrift oder Posten verrechen.</p>

<p>Unter diesen Menüpunkt werden Ihnen alle offenen Posten angezeigt. Dabei werden alle  zugehörigen Konten berücksichtigt – also es  werden sowohl Forderungen als auch Verbindlichkeiten aufgelistet.</p>

<p>Wenn Sie aber vorher eine Beteiligung <img src="http://xpecto.github.io/docs/img/img_1441372403820.png" alt="" title=""> oder einen Vertrag <img src="http://xpecto.github.io/docs/img/img_1441373565478.png" alt="" title=""> markiert haben, dann werden nur die zugehörigen offene Posten angezeigt.</p>

<p>Sie erreichen die <em>xpectoPro OPOS Verarbeitung</em> Maske über <em>Berechnungen → Offene Posten</em> oder unter <em>Berechnungen →Zahlungsverkehr → Werte berechnen</em>. <br>
Die <em>OPOS Verarbeitung</em> Maske enthält in dem oberen Bereich die Filterbedingungen, in der Mitte die Liste der  <br>
Posten für alle Beteiligungen, und unten die Details der Buchungen.</p>

<p>Offene Posten können miteinander verrechnet werden, das heißt Forderungen bzw. Verbindlichkeiten können zusammengefasst werden oder Forderungen können mit Verbindlichkeiten gegeneinander aufgerechnet werden. Rechnung mit einer Gutschrift ausgleichen.</p>

<p>Öffnen Sie die OPOS Verarbeitung Maske  und markieren Sie alle offene Posten oder nur die für die </p>

<p>Produkt Konto OPOS - Konto</p>

<p>Die Offenen Posten Maske berechnet die Buchungen für einstehende Einzahlungen und Auszahlungen. Diese Buchungen werden auf Basis von unten Produkte Konto angelegter Konto. <br>
Es geht haupsächlich um außgehender Zahlungsverkehr. </p>

<p>Überweisungen werden für Kreditoren (Gläubiger) erstellt. Klicken Sie auf die Schaltfläche  <img src="http://xpecto.github.io/docs/img/img_1440769189875.png" alt="" title=""> um eine Überweisung zu erstellen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1441701549077.png" alt="" title=""></p>

<p>Wählen Sie dann das Ausführungsdatum an. </p>

<p>Eine Lastschrift ist gewissermaßen die Umkehrung der Überweisung. Der Zahlungsempfänger gibt hier seiner Bank  den Auftrag, vom Konto des Zahlungspflichtigen bei dessen Bank (Zahlstelle) einen bestimmten Betrag abzubuchen. <br>
<img src="http://xpecto.github.io/docs/img/img_1440769218414.png" alt="" title=""> <br>
 Ausführungsdatum <br>
<img src="http://xpecto.github.io/docs/img/img_1440769342773.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1440769392486.png" alt="" title=""> <br>
Das abgehende Bankkonto des Fonds  <br>
<img src="http://xpecto.github.io/docs/img/img_1440769418756.png" alt="" title=""></p>

<p>Zahlungsverkehrmaske  <br>
Wenn keine weiteren offenen Posten im Dialog übrig bleiben, öffnet sich automatisch der Dialog Zahlungsverkehr (früherer Name Sollstellung, Menu Bearbeiten - Zahlungsverkehr). <br>
Aus einer OPOS Buchung wird eine Sollbuchung erstellt. Es wird hier eine Soll-Buchungssatz erstellt. </p>

<p>Im oberen Bereich sind die gerade erstellten Sollbuchungen zu sehen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1440772638410.png" alt="" title=""></p>

<p>Mit den bekannten Funktionen „Datenprüfung“ und „Dateien erzeugen“ können die Dateien dann wirklich erzeugt werden. Es werden die Sollbuchungen zu einer Transaktion zusammengefasst (SB_Transaction) und zugleich wird ein Datensatz für den Zahlungsverkehr (ZV, incl. ZV_FileName und ZV_FileNamePDF, Join über den Key ZV_Transaction) erzeugt. </p>

<p>Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1440771677497.png" alt="" title=""> und wenn die geprüfte Daten in Ordnung sind dann werden die Dateien erzeugen aktiv,  dann auf Details <img src="http://xpecto.github.io/docs/img/img_1440771513947.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1440772783601.png" alt="" title=""></p>

<p>Dateien erzeugen <img src="http://xpecto.github.io/docs/img/img_1440771590046.png" alt="" title="">.   Dann werden eine CSV, PDF und XML.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1440772902738.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1440773653998.png" alt="" title=""></p>

<p>CSV, PDF, XML <br>
Die erzeugte Dateien werden dann in der Liste angezeigt.  <br>
<img src="http://xpecto.github.io/docs/img/img_1440773806090.png" alt="" title=""></p></div></body>
</html>