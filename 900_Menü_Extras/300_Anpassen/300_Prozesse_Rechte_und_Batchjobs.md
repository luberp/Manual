
Symbolleiste: Speichern, Prozesse neu anlegen, Benutzer neu anlegen, Batch-Jobs neu anlegen, Systembenutzer abfragen und speichern, Prozess importieren, Prozess exportieren, Druckvorschau.

**Prozesse: Allgemein, Designer**
Unter Prozesse können Wiedervorlagen, Mahnprozesse, Zeichnung angelegt werden.
xpectoPro ermöglicht die Integration von Ablaufprozessen in die tägliche Arbeit. Nahezu alle Elemente und Funktionen der Software können in vordefinierte Abläufe eingebunden werden. Die Abläufe sind umfangreich konfigurierbar und ermöglichen eine strukturierte Arbeitsweise. Insbesondere verteilte Teams profitieren von der Aufgabentrennung und der gemeinsamen Kommunikation über Prozesse.
Die Prozesse können über einen grafischen Designer erstellt werden. Die Steuerung der Prozesse erfolgt mit einer zentralen „Wiedervorlage-Steuerung" die alle Prozesselemente einsehen darf. Leiter von Callcentern, Vertrieben oder Verwaltungen haben so stets den Überblick über alle wichtigen Abläufe.
Die Einbindung von externen Stellen zur Datenerfassung, zur Prüfung/Compliance oder zur Betreuung ist über Prozesse sehr gut möglich. 

Beispiel Annahmeprozess:
Erstellung der Verkaufsunterlagen über Webportal durch Vertriebspartner
Einreichung der Verkaufsunterlagen bei Gesellschaft
Eingabe der Daten und Unterlagen durch Compliance, Vertreib o.ä.
nach erfolgreicher Prüfung: Druck und Versand der Begrüßung
Wartezeit auf Geldeingang, Alarm nach 14 Tagen
vollständiger Geldeingang

Beispiel Kundenaquise:
Kunde gibt Daten auf Kontaktformular ein.
Callcenter ruft Kunden direkt an
Versand von Unterlagen
Callcenter ruft Kunden zur Beratung und Fragen an
Kunde sendet unterschriebenen  Vertrag
Weiterführung im Annahmeprozess

Beispiel Mahnwesen:
Kunde erzeugt Rücklastschrift oder zahlt nicht innerhalb eines bestimmten Zeitraums
Je nach Grund wird Callcenter oder Vertriebspartner aktiv
Bearbeiter ergänzt weiteres Vorgehen
erneute Wartezeit
Kunde hat gezahlt erledigt
Kunde hat nicht gezahlt nächste Mahnstufe

Prozesse neu anlegen
**Benutzer: Allgemein, Rechte, Gruppenmitglieder**
In xpectoPro kann jeder Menüpunkt und jeder Karteireiter sowie das Starten der Software pro Benutzer individuell gesperrt oder erlaubt werden. Der in xpectoPro verwendete Benutzer ist der jeweils angemeldete Windows-Benutzer. In der Liste der vorhandene Benutzer werden automatisch die in der Windows Domäne vorhandene Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. Einen neuen Benutzer legen sie durch Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1424426984009.png) an.

![](http://xpecto.github.io/docs/img/img_1424427033970.png)

Geben Sie einen Benutzernamen ein. Achten Sie darauf, dass der gewählte Benutzername bereits ein Benutzerkonto im Windows Betriebssystem besitzt. 

**Systembenutzer abfragen und speichern** holt alle Benutzer aus Active Directoy ab und speichert diese.

Geben Sie einen Benutzername ein. Achten Sie darauf, dass der gewählte Benutzername bereits ein Benutzerkonto im Windows Betriebssystem besitzt. Bei Windows Domänen-Benutzern setzt sich der Benutzer aus Domänenname\Benutzername zusammen. Sollten Ihre Benutzer also an einem Domänencontroller angemeldet sein, so berücksichtigen Sie dies bei der Erstellung des Benutzerkontos. Bestätigen Sie mit OK. Nachdem Sie mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_1424428777473.png) gespeichert haben, wird der neue Benutzer in der Benutzer Liste angezeigt. 

Beim Start der Software werden zuerst die Rechte des angemeldeten Benutzers ermittelt und daraufhin nur die Menüpunkte und Karteireiter angezeigt, für die der Benutzer berechtigt ist oder gegebenfalls der Start der Software abgebrochen. Die Ermittlung der Berechtigungen eines angemeldeten Benutzers erfolgt in zwei Stufen. Zuerst werden die Rechte des Benutzer „Default" abgefragt (der Benutzer „Default" wird  bei der Installation der Software automatisch angelegt und mit dem Recht „Administrator" ausgestattet. Danach werden die Rechte des tatsächlich angemeldeten Benutzers abgefragt , diese überblenden gegebenenfalls die Rechte des Benutzers Default. 
Beispiel: Beim Benutzer „Default" sei das Recht zum Start von xpectoPro auf erlauben gesetzt. Bei einem bestimmten Benutzer sei jedoch zusätzlich das Recht zum Start von xpectoPro auf verbieten gesetzt. Dadurch ist allen Windows Bentzer grundsätzlich das Starten der Software möglich. Der bestimmte Benutzer kann jedoch xpectoPro  nicht starten, obwohl beim Benutzer „Default" das Recht auf erlauben ist. 

Spezielle Rechte: Die Rechte „Administrator" und „Poweruser" umfassen alle möglichen Rechte, d.h. das Setzen eines der beiden Rechte bei einem Benutzer ist äquivalent zum Setzen aller anderen Rechte bei demselben Benutzer. Bei „Poweruser" können einzelne Rechte für den Benutzer durch Setzen des entsprechenden Rechts auf verbieten entzogen werden. Im Gegensatz dazu ist dies bei „Administrator" nicht möglich.
Zur Einstellung der Rechte eines Benutzers selektieren Sie den Benutzer und betätigen Sie die Schaltfläche 
 ![](http://xpecto.github.io/docs/img/img_1424439295301.png), um eine neue Berechtigungszeile einzufügen. In der Auswahlbox Recht wird das gewünschte Recht ausgewählt, und unter Wert die jeweilige Berechtigungsstufe erlauben, verbieten oder default.
 
Beschreiben die Vorteile von Gruppen-Rechte.

**Batchjobs: Allgemein**
Batchjobs sind automatisierte Prozesse, das bedeutet dass eine Folge von auszuführenden Befehlen von dem Betriebsystem in einer Datei aufgeführt ist und für die Ausführung als eine einzelne Einheit vorgelegt wird. Ein Batchjob ist das Gegenteil von interaktive Verarbeitung in der ein Benutzer die einzelne Befehle sofort verarbeitet werden.