Die Software aifExpert basiert auf einem Client-Server-Modell in Form einer Microsoft Windows basierten Client-Applikation, welche mit einer zentralen Datenbank verbunden ist. 

Dieses Handbuch beschreibt **keine** administrativen Aufgaben wie zum Beispiel die Konfiguration von Einstellungen oder das Hinterlegen von Berechnungsskripten. Ebenso wenig wird auf die Installation und Einrichtung von serverseitigen Komponenten wie Microsoft SQL-Server oder das Anlegen von Datenbanken und die Definition von Datenstrukturen eingegangen. All diese Tätigkeiten sind nicht Aufgabe des Anwenders, diese werden vom xpecto Kundensupport vor Ort oder per Fernwartung durchgeführt, da hierfür tiefgreifende Kenntnisse der Software und teilweise sogar Programmierkenntnisse notwendig sind. 

In diesem Handbuch wird nur die Installation der Client-Applikation und die Herstellung der Verbindung zu einer bestehenden Datenbank beschrieben. 

Die aifExpert Installations-CD enthält alle zur Installation benötigten Dateien. Eine aktuelle Installationsdatei steht außerdem unter folgender Adresse zum Download bereit:

http://www.xpecto.de/down/setup.msi

Bitte beachten Sie die Schreibweise (Groß- und Kleinschreibung) der URLs!

Für die Installation von aifExpert werden Administratorrechte benötigt.


----------


###Systemvoraussetzungen


*Server:*

 - Microsoft SQL Server 2012/2014/2016 Datenzuwachs: ca. 200-2.000MB/a
 - Zentrales Verzeichnis für restliche Daten Datenzuwachs: ca. 1GB/a

*Arbeitsstation:*

 - Betriebssystem: Microsoft Windows 7/ 8 / 8.1 / 10
 - Prozessor: Intel oder vergleichbare CPU mit mindestens 1GHz
 - Arbeitsspeicher: mindestens 1 GB
 - Grafikkarte: Empfohlen mindestens 16Bit Farbtiefe und 1024x768 Bildpunkte
 - Festplatte: 200 MB
 - Administratorrechte für Installation
 - Hauptbenutzerrechte für Betrieb


----------

###Installation der Software


Starten Sie die Datei setup.exe von der xpecto Website.

Als Benutzer von Microsoft Windows bestätigen Sie die Sicherheitswarnung, die auf einen unbekannten Herausgeber hinweist mit	*Ausführen* und die darauf folgende Sicherheitswarnung der Benutzerkontensteuerung mit *Zulassen.*

Das Setup beginnt nun mit der Vorbereitung der Installation und entpackt die aifExpert Installationsdateien.

In dem darauf folgenden Dialog bestimmen Sie den Ordner, in welchem  aifExpert installiert werden soll. Es wird empfohlen, den vorgeschlagenen Ordner beizubehalten. Bestätigen Sie den Dialog mit *Weiter*.

Bestätigen Sie die Installation mit *Weiter*, um die Installation zu starten. aifExpert wird nun auf Ihrem Rechner installiert. 

Beenden Sie die Installation mit der Schaltfläche *Fertigstellen.* Bei Problemen während der Installation wenden Sie sich bitte an den xpecto Kundensupport.

Zum Starten von aifExpert klicken Sie im Startmenü auf den Eintrag aifExpert.


----------

###Verbindung zur Datenbank herstellen


Alle benötigten Einstellungen, um die aifExpert Client-Applikation mit einer Datenbank zu verbinden, sind in einer xpecto Einstellungsdatei gespeichert.

Durch Doppelklick auf eine von Ihrem Administrator oder dem xpecto Kundensupport zur Verfügung gestellten Einstellungsdatei wird aifExpert mit den entsprechenden Einstellungen gestartet und automatisch mit der richtigen Datenbank verbunden.

![](http://xpecto.github.io/docs/img/img_1437996071744.png)


