<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>300_Prozesse_Rechte_und_Batchjobs.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>In der klassischen Menü-Ansicht ist die Maske <em>Prozesse und Rechte</em> über Menü <em>Extras → Anpassen → Prozesse, Rechte und Batchjobs</em> gestartet werden.</p>

<p>In der modernen Menü-Ansicht kann die Maske <em>Prozesse und Rechte</em> in der Registerkarte <em>System</em> Gruppe <em>Anpassungen</em> Funktionen: <em>Prozesse, Benutzer/Rechte, Hintergrunddienste</em>.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1462180609955.png" alt="" title=""></p>

<p><strong>Prozesse</strong></p>

<p>Unter Prozesse können Wiedervorlagen, Mahnprozesse und Zeichnungen angelegt werden. <br>
xpectoPro ermöglicht die Integration von Ablaufprozessen in die tägliche Arbeit. Nahezu alle Elemente und Funktionen der Software können in vordefinierte Abläufe eingebunden werden. Die Abläufe sind umfangreich konfigurierbar und ermöglichen eine strukturierte Arbeitsweise. Insbesondere verteilte Teams profitieren von der Aufgabentrennung und der gemeinsamen Kommunikation über Prozesse. <br>
Die Prozesse können über einen grafischen Designer erstellt werden.  <br>
Die Steuerung der Prozesse erfolgt mit einer zentralen <em>Wiedervorlage-Steuerung</em> (siehe Handbuch <em>Bearbeiten → Wiedervorlage Steuerung</em>) die alle Prozesselemente einsehen darf. Leiter von Callcentern, Vertrieben oder Verwaltungen haben so stets den Überblick über alle wichtigen Abläufe. <br>
Die Einbindung von externen Stellen zur Datenerfassung, zur Prüfung/Compliance oder zur Betreuung ist über Prozesse sehr gut möglich. </p>

<p>Beispiel Mahnwesen: <br>
- Kunde erzeugt Rücklastschrift oder zahlt nicht innerhalb eines bestimmten Zeitraums  <br>
- Je nach Grund wird Callcenter oder Vertriebspartner aktiv  <br>
- erneute Wartezeit  <br>
- Kunde hat gezahlt → erledigt  <br>
- Kunde hat nicht gezahlt → nächste Mahnstufe</p>

<p>Um einen Prozess neu anzulegen klicken Sie in dem Dialog xpectoPro Prozesse und Rechte auf das Symbol <img src="http://xpecto.github.io/docs/img/img_1462787545827.png" alt="" title="">. Geben Sie den Name für Ihren neuen Prozess und die gewünschte Vorlage dazu. Bestätigen Sie dann Ihre Eingaben mit einen Klick auf <em>OK</em>. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1462179894814.png" alt="" title=""></p>

<p>Unter dem Reiter <em>Designer</em> haben Sie dann die Möglichkeit den Prozess zu designen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1462180172219.png" alt="" title=""></p>

<p><strong>Benutzer</strong></p>

<p>In xpectoPro kann jeder Menüpunkt und jeder Karteireiter sowie das Starten der Software pro Benutzer individuell gesperrt oder erlaubt werden. Der in xpectoPro verwendete Benutzer ist der jeweils angemeldete Windows-Benutzer. In der Liste der vorhandenen Benutzer werden automatisch die in der Windows Domäne vorhandenen Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. Einen neuen Benutzer legen sie durch einen Klick auf das Symbol <img src="http://xpecto.github.io/docs/img/img_1462187089244.png" alt="" title=""> an. </p>

<p>Geben Sie einen Benutzernamen ein. Achten Sie darauf, dass der gewählte Benutzername bereits ein Benutzerkonto im Windows Betriebssystem besitzt. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1424427033970.png" alt="" title=""></p>

<p>Bei Windows Domänen-Benutzern setzt sich der Benutzer aus Domänenname\Benutzername zusammen. Sollten Ihre Benutzer also an einem Domänencontroller angemeldet sein, so berücksichtigen Sie dies bei der Erstellung des Benutzerkontos. Bestätigen Sie Ihre Eingaben mit <em>OK</em>. Nachdem Sie mit dem Symbol <img src="http://xpecto.github.io/docs/img/img_1462187128337.png" alt="" title=""> gespeichert haben, wird der neue Benutzer in der Benutzer Liste angezeigt. </p>

<p>Beim Start der Software werden zuerst die Rechte des angemeldeten Benutzers ermittelt und daraufhin nur die Menüpunkte und Karteireiter angezeigt, für die der Benutzer berechtigt ist oder gegebenfalls der Start der Software abgebrochen. Die Ermittlung der Berechtigungen eines angemeldeten Benutzers erfolgt in zwei Stufen. Zuerst werden die Rechte des Benutzer <em>Default</em> abgefragt (der Benutzer „Default” wird  bei der Installation der Software automatisch angelegt und mit dem Recht <em>Administrator</em> ausgestattet). Danach werden die Rechte des tatsächlich angemeldeten Benutzers abgefragt, diese überblenden gegebenenfalls die Rechte des Benutzers <em>Default</em>. </p>

<p>Beispiel: Beim Benutzer <em>Default</em> sei das Recht zum Start von xpectoPro auf erlauben gesetzt. Bei einem bestimmten Benutzer sei jedoch zusätzlich das Recht zum Start von xpectoPro auf verbieten gesetzt. Dadurch ist allen Windows Benutzer grundsätzlich das Starten der Software möglich. Der bestimmte Benutzer kann jedoch xpectoPro nicht starten, obwohl beim Benutzer <em>Default</em> das Recht auf erlauben ist. </p>

<p>Spezielle Rechte: Die Rechte <em>Administrator</em> und <em>Poweruser</em> umfassen alle möglichen Rechte, d.h. das Setzen eines der beiden Rechte bei einem Benutzer ist äquivalent zum Setzen aller anderen Rechte bei demselben Benutzer. Bei <em>Poweruser</em> können einzelne Rechte für den Benutzer durch Setzen des entsprechenden Rechts auf verbieten entzogen werden. Im Gegensatz dazu ist dies bei <em>Administrator</em> nicht möglich.</p>

<p>Zur Einstellung der Rechte eines Benutzers selektieren Sie den Benutzer und betätigen Sie die Schaltfläche  <br>
 <img src="http://xpecto.github.io/docs/img/img_1424439295301.png" alt="" title="">, um eine neue Berechtigungszeile einzufügen. In der Auswahlbox <em>Recht</em> wird das gewünschte Recht ausgewählt, und unter Wert die jeweilige Berechtigungsstufe <em>deny/verbieten</em>, <em>default</em> oder <em>allow/erlauben</em> gesetzt.</p>

<p>Über Gruppen-Rechte gelten die Berechtigungen die Sie dieser Gruppe geben, grundsätzlich für alle Mitglieder der Gruppe. </p>

<p>Das Symbol <em>Systembenutzer abfragen und speichern</em> <img src="http://xpecto.github.io/docs/img/img_1462187160501.png" alt="" title=""> holt alle Benutzer aus dem Active Directoy ab und speichert diese. In der Liste der vorhandenen Benutzer werden automatisch die in der Windows Domäne vorhandenen Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. </p>

<p><strong>Batchjobs</strong></p>

<p>Batchjobs sind automatisierte Prozesse, das bedeutet dass eine Folge von auszuführenden Befehlen von dem Betriebsystem in einer Datei aufgeführt ist und für die Ausführung als eine einzelne Einheit vorgelegt wird. Ein Batchjob ist das Gegenteil von interaktive Verarbeitung in der ein Benutzer die einzelne Befehle sofort verarbeitet werden. <br>
Ein neuer Batchjob kann mit einem Klick auf das Symbol <img src="http://xpecto.github.io/docs/img/img_1462187304079.png" alt="" title=""> angelegt werden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1462187275440.png" alt="" title=""></p>

<p>Über die Druckvorschau <img src="http://xpecto.github.io/docs/img/img_1462187329274.png" alt="" title=""> wird ein Ausdruck der aktuellen Eingabemaske gemacht, und zwar von dem Reiter der gerade aktiv ist. Die dazugehörigen Details stehen oben auf der Seite. Um die Druckvorschau-Funktion zu öffnen, klicken Sie auf das Symbol <img src="http://xpecto.github.io/docs/img/img_1462187337467.png" alt="" title=""> in der Symbolleiste. In das Fenster <em>Print Preview</em> kann die Seite eingerichtet, und falls gewünscht gedruckt werden.</p></div></body>
</html>