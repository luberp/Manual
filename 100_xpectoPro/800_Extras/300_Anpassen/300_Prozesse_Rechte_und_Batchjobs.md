In der klassischen Menü-Ansicht ist die Maske *Prozesse und Rechte* über Menü *Extras → Anpassen → Prozesse, Rechte und Batchjobs* gestartet werden.

In der modernen Menü-Ansicht kann die Maske *Prozesse und Rechte* in der Registerkarte *System* Gruppe *Anpassungen* Funktionen: *Prozesse, Benutzer/Rechte, Hintergrunddienste*.

![](http://xpecto.github.io/docs/img/img_1462180609955.png)

Die Maske enthält ihre eigene Symbolleiste mit folgende Symbole:

| Symbol          |    Beschreibung     |  
| ------------- |:-------------| 
| ![](http://xpecto.github.io/docs/img/img_1461935229842.png)  |Speichern| 
| ![](http://xpecto.github.io/docs/img/img_1462788084971.png)  |Prozesse neu anlegen| 
| ![](http://xpecto.github.io/docs/img/img_1462788142810.png)    | Benutzer neu anlegen | 
| ![](http://xpecto.github.io/docs/img/img_1462788189080.png)   | Batch-Jobs neu anlegen | 
| ![](http://xpecto.github.io/docs/img/img_1462788233775.png)   | Aktuellen Datensatz löschen | 
| ![](http://xpecto.github.io/docs/img/img_1462788296199.png)   | Systembenutzer abfragen und speichern | 
| ![](http://xpecto.github.io/docs/img/img_1461935451257.png)   | Prozess importieren|
|![](http://xpecto.github.io/docs/img/img_1461935507991.png)| Prozess exportieren| 
|![](http://xpecto.github.io/docs/img/img_1462788381761.png)| Druckvorschau|


----------


Prozesse


----------


Unter Prozesse können Wiedervorlagen, Mahnprozesse und Zeichnungen angelegt werden.
xpectoPro ermöglicht die Integration von Ablaufprozessen in die tägliche Arbeit. Nahezu alle Elemente und Funktionen der Software können in vordefinierte Abläufe eingebunden werden. Die Abläufe sind umfangreich konfigurierbar und ermöglichen eine strukturierte Arbeitsweise. Insbesondere verteilte Teams profitieren von der Aufgabentrennung und der gemeinsamen Kommunikation über Prozesse.
Die Prozesse können über einen grafischen Designer erstellt werden. 
Die Steuerung der Prozesse erfolgt mit einer zentralen *Wiedervorlage-Steuerung* (siehe Handbuch *Bearbeiten → Wiedervorlage Steuerung*) die alle Prozesselemente einsehen darf. Leiter von Callcentern, Vertrieben oder Verwaltungen haben so stets den Überblick über alle wichtigen Abläufe.
Die Einbindung von externen Stellen zur Datenerfassung, zur Prüfung/Compliance oder zur Betreuung ist über Prozesse sehr gut möglich. 

Beispiel Mahnwesen:
- Kunde erzeugt Rücklastschrift oder zahlt nicht innerhalb eines bestimmten Zeitraums 
- Je nach Grund wird Callcenter oder Vertriebspartner aktiv 
- erneute Wartezeit 
- Kunde hat gezahlt → erledigt 
- Kunde hat nicht gezahlt → nächste Mahnstufe

Um einen Prozess neu anzulegen klicken Sie in dem Dialog xpectoPro Prozesse und Rechte auf das Symbol ![](http://xpecto.github.io/docs/img/img_1462787545827.png). Geben Sie den Name für Ihren neuen Prozess und die gewünschte Vorlage dazu. Bestätigen Sie dann Ihre Eingaben mit einen Klick auf *OK*. 

![](http://xpecto.github.io/docs/img/img_1462179894814.png)

Unter dem Reiter *Designer* haben Sie dann die Möglichkeit den Prozess zu designen. 

![](http://xpecto.github.io/docs/img/img_1462180172219.png)


----------


Benutzer


----------


In xpectoPro kann jeder Menüpunkt und jeder Karteireiter sowie das Starten der Software pro Benutzer individuell gesperrt oder erlaubt werden. Der in xpectoPro verwendete Benutzer ist der jeweils angemeldete Windows-Benutzer. In der Liste der vorhandenen Benutzer werden automatisch die in der Windows Domäne vorhandenen Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. Einen neuen Benutzer legen sie durch einen Klick auf das Symbol ![](http://xpecto.github.io/docs/img/img_1462187089244.png) an. 

Geben Sie einen Benutzernamen ein. Achten Sie darauf, dass der gewählte Benutzername bereits ein Benutzerkonto im Windows Betriebssystem besitzt. 

![](http://xpecto.github.io/docs/img/img_1424427033970.png)

Bei Windows Domänen-Benutzern setzt sich der Benutzer aus Domänenname\Benutzername zusammen. Sollten Ihre Benutzer also an einem Domänencontroller angemeldet sein, so berücksichtigen Sie dies bei der Erstellung des Benutzerkontos. Bestätigen Sie Ihre Eingaben mit *OK*. Nachdem Sie mit dem Symbol ![](http://xpecto.github.io/docs/img/img_1462187128337.png) gespeichert haben, wird der neue Benutzer in der Benutzer Liste angezeigt. 

Beim Start der Software werden zuerst die Rechte des angemeldeten Benutzers ermittelt und daraufhin nur die Menüpunkte und Karteireiter angezeigt, für die der Benutzer berechtigt ist oder gegebenfalls der Start der Software abgebrochen. Die Ermittlung der Berechtigungen eines angemeldeten Benutzers erfolgt in zwei Stufen. Zuerst werden die Rechte des Benutzer *Default* abgefragt (der Benutzer „Default" wird  bei der Installation der Software automatisch angelegt und mit dem Recht *Administrator* ausgestattet). Danach werden die Rechte des tatsächlich angemeldeten Benutzers abgefragt, diese überblenden gegebenenfalls die Rechte des Benutzers *Default*. 

Beispiel: Beim Benutzer *Default* sei das Recht zum Start von xpectoPro auf erlauben gesetzt. Bei einem bestimmten Benutzer sei jedoch zusätzlich das Recht zum Start von xpectoPro auf verbieten gesetzt. Dadurch ist allen Windows Benutzer grundsätzlich das Starten der Software möglich. Der bestimmte Benutzer kann jedoch xpectoPro nicht starten, obwohl beim Benutzer *Default* das Recht auf erlauben ist. 

Spezielle Rechte: Die Rechte *Administrator* und *Poweruser* umfassen alle möglichen Rechte, d.h. das Setzen eines der beiden Rechte bei einem Benutzer ist äquivalent zum Setzen aller anderen Rechte bei demselben Benutzer. Bei *Poweruser* können einzelne Rechte für den Benutzer durch Setzen des entsprechenden Rechts auf verbieten entzogen werden. Im Gegensatz dazu ist dies bei *Administrator* nicht möglich.

Zur Einstellung der Rechte eines Benutzers selektieren Sie den Benutzer und betätigen Sie die Schaltfläche 
 ![](http://xpecto.github.io/docs/img/img_1424439295301.png) in dem Reiter *Rechte*, um eine neue Berechtigungszeile einzufügen. In der Auswahlbox *Recht* wird das gewünschte Recht ausgewählt, und unter Wert die jeweilige Berechtigungsstufe *deny/verbieten*, *default* oder *allow/erlauben* gesetzt.

Über Gruppen-Rechte gelten die Berechtigungen die Sie dieser Gruppe geben, grundsätzlich für alle Mitglieder der Gruppe. 

Das Symbol *Systembenutzer abfragen und speichern* ![](http://xpecto.github.io/docs/img/img_1462187160501.png) holt alle Benutzer aus dem Active Directoy ab und speichert diese. In der Liste der vorhandenen Benutzer werden automatisch die in der Windows Domäne vorhandenen Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. 


----------


Batchjobs


----------


Batchjobs sind automatisierte Prozesse, das bedeutet dass eine Folge von auszuführenden Befehlen von dem Betriebsystem in einer Datei aufgeführt ist und für die Ausführung als eine einzelne Einheit vorgelegt wird. Ein Batchjob ist das Gegenteil von interaktive Verarbeitung in der ein Benutzer die einzelne Befehle sofort verarbeitet werden.
Ein neuer Batchjob kann mit einem Klick auf das Symbol ![](http://xpecto.github.io/docs/img/img_1462187304079.png) angelegt werden.

![](http://xpecto.github.io/docs/img/img_1462187275440.png)

Über die Druckvorschau ![](http://xpecto.github.io/docs/img/img_1462187329274.png) wird ein Ausdruck der aktuellen Eingabemaske gemacht, und zwar von dem Reiter der gerade aktiv ist. Die dazugehörigen Details stehen oben auf der Seite. Um die Druckvorschau-Funktion zu öffnen, klicken Sie auf das Symbol ![](http://xpecto.github.io/docs/img/img_1462187337467.png) in der Symbolleiste. In das Fenster *Print Preview* kann die Seite eingerichtet, und falls gewünscht gedruckt werden.