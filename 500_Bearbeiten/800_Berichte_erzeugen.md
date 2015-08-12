<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>800_Berichte_erzeugen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Als Berichte werden die Ausdrucke bzw. Schreiben bezeichnet, die mit xpectoPro erstellt werden können. Jeder in xpectoPro hinterlegte Bericht hat eine Bezeichnung, ein vordefiniertes Layout und eine Datenbankabfrage zum Befüllen von Platzhaltern. </p>

<p>Über den Menüpunkt  <em>Bearbeiten → Berichte erzeugen</em> wird die xpectoPro Berichterstellung aufgerufen.  <br>
Um ein neues Bericht zu erzeugen wählen Sie unter <em>Bearbeiten → Berichte erzeugen</em> oder in der Symbolleiste die Schaltfläche<img src="http://xpecto.github.io/docs/img/img_1429027617646.png" alt="" title="">.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1439378634520.png" alt="" title=""></p>

<p>Da die Berichte über Namen unterschieden werden und in Gruppen verwaltet, müssen zuerst die Berichtengruppe ausgewählt und die dazu passende Berichte werden vorgeschlagen. Hier kann zwischen verschiedene Dateiausgaben ausgewählt werden. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1435072379530.png" alt="" title=""></p>

<p>Wenn die Felder ausgefüllt sind dann drucken Sie die Druckvorschau/Seitenansicht  <img src="http://xpecto.github.io/docs/img/img_1435072419471.png" alt="" title="">. </p>

<p>Sie werden aufgefordert einen Produkt für die Berichterstellung auszuwählen. <br>
<img src="http://xpecto.github.io/docs/img/img_1435072508917.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1435071898992.png" alt="" title=""></p>

<p>FFIDs </p>

<p>Berichte  <br>
Bericht erzeugen: generiert nur den Bericht.  <br>
Bericht bearbeiten: Vorlage generiert und bearbeitet. <img src="http://xpecto.github.io/docs/img/img_1429027648565.png" alt="" title=""> <br>
Integrierter Berichtsgenerator: Active Reports. </p>

<p>Berichte werden über Namen unterschieden und thematisch in Gruppen verwaltet.  <br>
Adressmuster, Textbausteine, individuelle Schreiben.  <br>
Speichern, Berichtgruppe neu anlegen, Berichte neu anlegen, Adressmuster neu anlegen, Textbausteine neu anlegen, Individuelle Schreiben neu anlegen, Aktuellen Datensatz löschen, Bericht importieren, Bericht exportieren. </p>

<p>Ordnerstruktur.  <br>
Das Muster ist eine SQL-Abfrage die nur ein einziges Feld und eine einzige Zeile zurückliefern kann. Der Parameter @ID wird mit der KundenNr oder einer anderen ID an die Abfrage übergeben.</p>

<p>Platzhalter für Vermittler-, Kunden- und Vertragsdaten werden dabei automatisch mit den Werten des in eAgentur aktuell ausgewählten Datensatzes befüllt.</p>

<p>Mehrseitige Listen oder Auswertungen werden mit den Schaltflächen  durchblättert.</p>

<p>Der erstellte Bericht kann nun über die Schaltfläche gedruckt, oder über die Schaltflächen Word, Excel, PDF und TIFF als Datei im gleichnamigen Format exportiert werden. Soll ein bestimmtes Schreiben vor dem Druck noch nachbearbeitet werden, so bietet es sich z.B. an, den Bericht als Word-Datei zu exportieren, in Microsoft Word die gewünschten Änderungen vorzunehmen und dann direkt von Word aus zu drucken.</p>

<p>Berichte, die von Ihrem Ersteller entsprechend parametrisiert sind, werden zusätzlich als so genannte Favoriten-Berichte in der Hauptmaske von eAgentur auf der Werkzeugleiste angeboten. Es bietet sich an, häufig verwendete Berichte als Favoriten-Berichte zu hinterlegen, da sie über diesen Weg schneller erreicht werden können. Das kann unter dem Reiter <em>Kategorien</em> eingestellt werden.</p>

<p>Mit der Schaltfläche wird der selektierte Favoriten-Bericht auf den in der nebenstehenden Druckerauswahl gewählten Drucker gedruckt. Ist die Schaltfläche aktiviert, so wird der Bericht beim Druck automatisch als PDF-Datei gespeichert und eine Verknüpfung unter den Ereignissen des aktuell ausgewählten Vermittlers, Kunden oder Vertrags hinterlegt.</p>

<p>Hinweis: Dies dient lediglich der Arbeitserleichterung durch schnelles Wiederfinden gedruckter Dokumente, genügt jedoch nicht den Anforderungen einer ordnungsgemäßen EDV-gestützten Archivierung.</p>

<p>Funktionen und Abläufe - Briefversand über Dienstleister  <br>
Anbindung an die Großkundenschnittstellen der PIN AG. Diese Schnittstelle ermöglicht den Versand von Briefen ohne diese selbst auszufrucken. Diese einfache Integration ermöglicht den Massenversand von Briefen auf eine sehr komfortable Weise. Als Beispiel dient ein Werbeschreiben das wir an den Kunden in den PLZ Gebiete 1 und 2 versenden möchten. Das Schreiben würde als Wordbericht in xpectoPro angelegt und kann über die Favoritenleiste   direkt erstellt und angezeigt werden. Für den Massenversand wird ein Verteiler benötigt. Die einfachste Möglichkeit zur Erstellung eines Verteilers wird in dem Dialog Abfragen erstellen angeboten. <br>
Wir benötigen jeweils eine Filterbedingung für jeden gewünschten PLZ. In dem nächsten Schritt werden die gewünschten Felder gewählt. Das System schlägt schon hier die typischen Felder vor, eine weitere Auswahl ist nicht nötig. Der nächste Dialog zeigt nun das Ergebnis an. Der Verteiler umfasst die Kunden die jetzt in eine Kampagne (Massendruck) verwendet werden. Mit einem Klick auf <img src="http://xpecto.github.io/docs/img/img_1429266575881.png" alt="" title=""> wird die Kampagne gestartet. Die Kunden werden hier als Empfänger angezeigt. Als nächstes wird das gewünschte Schreiben ausgewählt. <br>
Es geht hier um Massendruck durch einen externer Dienstleister. <br>
Wenn den Drucker: Briefversand nicht angezeigt wird dann bitte an Support wenden da ein Vertrag abgeschlossen werden muss mit dem PIN AG, und dann der Support die Einrichtungen vornehmen kann. </p>

<p>Durch Auswählen des Checkboxes Berichte archivieren werden die Schreiben an an die Kunden archiviert. Der Klick auf Start werden die einzelne Scheiben erstellt und die Dokumente werden in dem Zwischenspeicher des Briefversandes abgelegt. Die Schreiben sind damit erstellt und müssen nur noch an die PIN AG übertragen werden. Die Kampagne kann damit abgeschlossen werden.</p>

<p>Um ein neues Bericht zu erstellen wählen Sie unter <em>Extras → Anpassen → Berichte und Adressmuster</em> oder in der Symbol- und Funktionsleiste die Schaltfläche<img src="http://xpecto.github.io/docs/img/img_1429027648565.png" alt="" title="">.  Sie gelangen in der Maske <em>Berichte und Adressmuster</em>.</p>

<p>Auf der linke Seite wird einen Übersicht </p>

<p>Die Navigation beinhaltet folgende Bäume: Berichte, Adressmuster, Textbausteine, individuelle Schreiben. Jeder Baum enthält sein eigener Ansicht und die entsprechende Eingabemaske auf der rechte Seite.</p></div></body>
</html>