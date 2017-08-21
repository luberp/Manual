Die Optimierungsfunktion hilft die Performance Ihrer xpectoPro Software zu verbessern.  Sie erreichend den Menüpunt über *System -> Optimierung* in der modernen Menüansicht der Software. 
In der klassichen Ansicht starten Sie die Optimierung über *Extras -> Anpassen -> Optimierung*.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Optimierung/Optimierung_Menue.png)

Die Optimierung erfolgt im wesentlichen über drei Funktionen die bereits vorgegeben sind:


 - Shrinking Log *(Hierbei werden Logdateien des SQL-Servers gepackt, dieses gibt zusätzlichen Speicherplatz des SQL-Servers frei)*.
 - Statistiken aktualisieren *(Die Verteilungsstatistiken werden von SQL Server verwendet, um die Navigation durch die Tabellen während der Verarbeitung von Transact-SQL -Anweisungen zu optimieren)*.
 - fehlende Indizes abfragen / erzeugen *(Das Anlegen eines neuen Indexes ändert den Tabelleninhalt nicht. Es wird lediglich eine neue Datenstruktur angelegt, die auf die Tabellendaten verweist. Ein Datenbank-Index ähnelt also dem Index am Ende eines Buches: Er hat seinen eigenen Speicherplatz, besteht großteils aus Redundanzen und verweist auf die eigentliche Information, die an einer anderen Stelle gespeichert ist, wodurch der Zugriff auf die benötigten Daten beschleunigt wird)*.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Optimierung/Indizes_abfragen.png)

An dieser Stelle können die notwendigen Indexierungen die erzeugt werden sollten ausgewählt werden. Sie starten den Vorgang über den Button *markierte Indizes erzeugen*. 

![](http://xpecto.github.io/docs/xpecto/Grafiken/gr_gluehbirne.jpg)*Bitte beachten Sie dass eine Optimierung nicht in jedem Fall sinnvoll ist, dieses hängt unter anderem damit zusammen welche Hardware und SQL-Server Sie einsetzen*.





