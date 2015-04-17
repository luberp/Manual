
<title>800_Berichte_erzeugen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container">Als Berichte werden die Ausdrucke bzw. Schreiben bezeichnet, die mit xpectoPro erstellt werden können. Jeder in xpectoPro hinterlegte Bericht hat eine Bezeichnung, ein vordefiniertes Layout und eine Datenbankabfrage zum Befüllen von Platzhaltern. 

Über den Menüpunkt  Bearbeiten Berichte erzeugen wird die xpectoPro Berichtserstellung aufgerufen. 
FFIDs 
Bearbeiten: Bericht erzeugen 
Anpassen: Berichte und Adressmuster 
<img src="http://xpecto.github.io/docs/img/img_1424860132052.png" alt="" title=""> Bericht erzeugen. 
<img src="http://xpecto.github.io/docs/img/img_1424858324357.png" alt="" title="">Bericht bearbeiten.

Berichte 
Bericht erzeugen: generiert nur den Bericht. 
Bericht bearbeiten: Vorlage generiert und bearbeitet. 
Integrierter Berichtsgenerator: Active Reports. 
Um ein neues Bericht zu erstellen, bieten sich in xpectoPro folgende Möglichkeiten:  
über Bearbeiten Berichte erzeugen oder über die Schaltflache <img src="http://xpecto.github.io/docs/img/img_1424858324357.png" alt="" title=""> in der Symbolleiste.

Adressmuster, Textbausteine, individuelle Schreiben. 
Speichern, Berichtgruppe neu anlegen, Berichte neu anlegen, Adressmuster neu anlegen, Textbausteine neu anlegen, Individuelle Schreiben neu anlegen, Aktuellen Datensatz löschen, Bericht importieren, Bericht exportieren. 
Berichte werden über Namen unterschieden und thematisch in Gruppen verwaltet. 
Ordnerstruktur. 
Das Muster ist eine SQL-Abfrage die nur ein einziges Feld und eine einzige Zeile zurückliefern kann. Der Parameter @ID wird mit der KundenNr oder einer anderen ID an die Abfrage übergeben.

Klicken Sie auf <img src="http://xpecto.github.io/docs/img/img070.png" alt="" title=""> um den gewählten Bericht in xpectoPro zu erstellen. Platzhalter für Vermittler-, Kunden- und Vertragsdaten werden dabei automatisch mit den Werten des in eAgentur aktuell ausgewählten Datensatzes befüllt.

Mehrseitige Listen oder Auswertungen werden mit den Schaltflächen<img src="http://xpecto.github.io/docs/img/img072.png" alt="" title=""> durchblättert.

Der erstellte Bericht kann nun über die Schaltfläche<img src="http://xpecto.github.io/docs/img/img073.png" alt="" title=""> gedruckt, oder über die Schaltflächen Word, Excel, PDF und TIFF als Datei im gleichnamigen Format exportiert werden. Soll ein bestimmtes Schreiben vor dem Druck noch nachbearbeitet werden, so bietet es sich z.B. an, den Bericht als Word-Datei zu exportieren, in Microsoft Word die gewünschten Änderungen vorzunehmen und dann direkt von Word aus zu drucken.

Berichte, die von Ihrem Ersteller entsprechend parametrisiert sind, werden zusätzlich als so genannte Favoriten-Berichte in der Hauptmaske von eAgentur auf der Werkzeugleiste angeboten. Es bietet sich an, häufig verwendete Berichte als Favoriten-Berichte zu hinterlegen, da sie über diesen Weg schneller erreicht werden können.

<img src="http://xpecto.github.io/docs/img/img075.png" alt="" title="">

Mit der Schaltfläche<img src="http://xpecto.github.io/docs/img/img076.png" alt="" title=""> wird der selektierte Favoriten-Bericht auf den in der nebenstehenden Druckerauswahl gewählten Drucker gedruckt. Ist die Schaltfläche 
<img src="http://xpecto.github.io/docs/img/img077.png" alt="" title=""> aktiviert, so wird der Bericht beim Druck automatisch als PDF-Datei gespeichert und eine Verknüpfung unter den Ereignissen des aktuell ausgewählten Vermittlers, Kunden oder Vertrags hinterlegt.

Hinweis: Dies dient lediglich der Arbeitserleichterung durch schnelles Wiederfinden gedruckter Dokumente, genügt jedoch nicht den Anforderungen einer ordnungsgemäßen EDV-gestützten Archivierung.

Funktionen und Abläufe - Briefversand über Dienstleister 
Anbindung an die Großkundenschnittstellen der PIN AG. Diese Schnittstelle ermöglicht den Versand von Briefen ohne diese selbst auszufrucken. Diese einfache Integration ermöglicht den Massenversand von Briefen auf eine sehr komfortable Weise. Als Beispiel dient ein Werbeschreiben das wir an den Kunden in den PLZ Gebiete 1 und 2 versenden möchten. Das Schreiben würde als Wordbericht in xpectoPro angelegt und kann über die Favoritenleiste   direkt erstellt und angezeigt werden. Für den Massenversand wird ein Verteiler benötigt. Die einfachste Möglichkeit zur Erstellung eines Verteilers wird in dem Dialog Abfragen erstellen angeboten.  
Wir benötigen jeweils eine Filterbedingung für jeden gewünschten PLZ. In dem nächsten Schritt werden die gewünschten Felder gewählt. Das System schlägt schon hier die typischen Felder vor, eine weitere Auswahl ist nicht nötig. Der nächste Dialog zeigt nun das Ergebnis an. Der Verteiler umfasst die Kunden die jetzt in eine Kampagne (Massendruck) verwendet werden. Mit einem Klick auf <img src="http://xpecto.github.io/docs/img/img_1429265846225.png" alt="" title=""> wird die Kampagne gestartet.