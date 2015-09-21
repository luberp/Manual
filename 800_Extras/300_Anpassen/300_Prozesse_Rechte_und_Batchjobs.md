<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>300_Prozesse_Rechte_und_Batchjobs.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p><strong>Prozesse: Allgemein, Designer</strong></p>

<p>Unter Prozesse können Wiedervorlagen, Mahnprozesse und Zeichnungen angelegt werden. <br>
xpectoPro ermöglicht die Integration von Ablaufprozessen in die tägliche Arbeit. Nahezu alle Elemente und Funktionen der Software können in vordefinierte Abläufe eingebunden werden. Die Abläufe sind umfangreich konfigurierbar und ermöglichen eine strukturierte Arbeitsweise. Insbesondere verteilte Teams profitieren von der Aufgabentrennung und der gemeinsamen Kommunikation über Prozesse. <br>
Die Prozesse können über einen grafischen Designer erstellt werden.  <br>
Die Steuerung der Prozesse erfolgt mit einer zentralen <em>Wiedervorlage-Steuerung</em> (siehe <em>Bearbeiten → Wiedervorlage Steuerung</em>) die alle Prozesselemente einsehen darf. Leiter von Callcentern, Vertrieben oder Verwaltungen haben so stets den Überblick über alle wichtigen Abläufe. <br>
Die Einbindung von externen Stellen zur Datenerfassung, zur Prüfung/Compliance oder zur Betreuung ist über Prozesse sehr gut möglich. </p>

<p>Beispiel Mahnwesen: <br>
 - Kunde erzeugt Rücklastschrift oder zahlt nicht innerhalb eines <br>
  - bestimmten Zeitraums Je nach Grund wird Callcenter oder <br>
   - Vertriebspartner aktiv Bearbeiter ergänzt weiteres Vorgehen erneute <br>
 -   Wartezeit  <br>
 - Kunde hat gezahlt → erledigt  <br>
 - Kunde hat nicht gezahlt → nächste Mahnstufe</p>

<p>Um einen Prozess neu anzulegen klicken Sie in dem Dialog xpectoPro Prozesse und Rechte auf das Symbol <img src="http://xpecto.github.io/docs/img/img_1442841693322.png" alt="" title="">. Geben Sie den Name für Ihren neuen Prozess und wie den Prozess erstellt werden soll. Bestätigen Sie dann Ihre Eingaben mit einen Klick auf <em>OK</em>. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1442842675187.png" alt="" title=""></p>

<p>Unter dem Reiter <em>Designer</em> haben Sie dann die Möglichkeit der Prozess zu designen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1442842994942.png" alt="" title=""></p>

<p><strong>Benutzer: Allgemein, Rechte, Gruppenmitglieder</strong></p>

<p>In xpectoPro kann jeder Menüpunkt und jeder Karteireiter sowie das Starten der Software pro Benutzer individuell gesperrt oder erlaubt werden. Der in xpectoPro verwendete Benutzer ist der jeweils angemeldete Windows-Benutzer. In der Liste der vorhandene Benutzer werden automatisch die in der Windows Domäne vorhandene Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. Einen neuen Benutzer legen sie durch einen Klick auf das Symbol <img src="http://xpecto.github.io/docs/img/img_1424426984009.png" alt="" title=""> an. </p>

<p>Geben Sie einen Benutzernamen ein. Achten Sie darauf, dass der gewählte Benutzername bereits ein Benutzerkonto im Windows Betriebssystem besitzt. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1424427033970.png" alt="" title=""></p>

<p>Bei Windows Domänen-Benutzern setzt sich der Benutzer aus Domänenname\Benutzername zusammen. Sollten Ihre Benutzer also an einem Domänencontroller angemeldet sein, so berücksichtigen Sie dies bei der Erstellung des Benutzerkontos. Bestätigen Sie Ihre Eingaben mit <em>OK</em>. Nachdem Sie mit dem Symbol <img src="http://xpecto.github.io/docs/img/img_1424428777473.png" alt="" title=""> gespeichert haben, wird der neue Benutzer in der Benutzer Liste angezeigt. </p>

<p>Beim Start der Software werden zuerst die Rechte des angemeldeten Benutzers ermittelt und daraufhin nur die Menüpunkte und Karteireiter angezeigt, für die der Benutzer berechtigt ist oder gegebenfalls der Start der Software abgebrochen. Die Ermittlung der Berechtigungen eines angemeldeten Benutzers erfolgt in zwei Stufen. Zuerst werden die Rechte des Benutzer <em>Default</em> abgefragt (der Benutzer „Default” wird  bei der Installation der Software automatisch angelegt und mit dem Recht <em>Administrator</em> ausgestattet). Danach werden die Rechte des tatsächlich angemeldeten Benutzers abgefragt, diese überblenden gegebenenfalls die Rechte des Benutzers <em>Default</em>. </p>

<p>Beispiel: Beim Benutzer <em>Default</em> sei das Recht zum Start von xpectoPro auf erlauben gesetzt. Bei einem bestimmten Benutzer sei jedoch zusätzlich das Recht zum Start von xpectoPro auf verbieten gesetzt. Dadurch ist allen Windows Benutzer grundsätzlich das Starten der Software möglich. Der bestimmte Benutzer kann jedoch xpectoPro nicht starten, obwohl beim Benutzer <em>Default</em> das Recht auf erlauben ist. </p>

<p>Spezielle Rechte: Die Rechte <em>Administrator</em> und <em>Poweruser</em> umfassen alle möglichen Rechte, d.h. das Setzen eines der beiden Rechte bei einem Benutzer ist äquivalent zum Setzen aller anderen Rechte bei demselben Benutzer. Bei <em>Poweruser</em> können einzelne Rechte für den Benutzer durch Setzen des entsprechenden Rechts auf verbieten entzogen werden. Im Gegensatz dazu ist dies bei <em>Administrator</em> nicht möglich.</p>

<p>Zur Einstellung der Rechte eines Benutzers selektieren Sie den Benutzer und betätigen Sie die Schaltfläche  <br>
 <img src="http://xpecto.github.io/docs/img/img_1424439295301.png" alt="" title="">, um eine neue Berechtigungszeile einzufügen. In der Auswahlbox <em>Recht</em> wird das gewünschte Recht ausgewählt, und unter Wert die jeweilige Berechtigungsstufe <em>deny/verbieten</em>, <em>default</em> oder <em>allow/erlauben</em> gesetzt.</p>

<p>Gruppen-Rechte so dass Rechte die Sie dieser Gruppe geben grundsätzlich für alle Benutzer gelten. Beschreiben die Vorteile von Gruppen-Rechte. Es bietet sich die Möglichkeit die Rechte für mehrere Benutzer über Gruppen zu verwalten.</p>

<p>Das Symbol <em>Systembenutzer abfragen und speichern</em> <img src="http://xpecto.github.io/docs/img/img_1442583757418.png" alt="" title=""> holt alle Benutzer aus Active Directoy ab und speichert diese.In der Liste der vorhandenen Benutzer werden automatisch die in der Windows Domäne vorhandenen Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. </p>

<p><strong>Batchjobs: Allgemein</strong></p>

<p>Batchjobs sind automatisierte Prozesse, das bedeutet dass eine Folge von auszuführenden Befehlen von dem Betriebsystem in einer Datei aufgeführt ist und für die Ausführung als eine einzelne Einheit vorgelegt wird. Ein Batchjob ist das Gegenteil von interaktive Verarbeitung in der ein Benutzer die einzelne Befehle sofort verarbeitet werden. <br>
Einen neuen Batchjob kann mit einem Klick auf das Symbol <img src="http://xpecto.github.io/docs/img/img_1442846537833.png" alt="" title=""> angelegt werden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1442583492464.png" alt="" title=""></p>

<p>Unter Druckvorschau wird einen Ausdruck in der aktuelle Eingabemaske gemacht, und zwar von dem Reiter der gerade aktiv ist. Die dazugehörige Details stehen oben auf der Seite. Um die Druckvorschau-Funktion zu öffnen, klicken Sie auf das Symbol <img src="http://xpecto.github.io/docs/img/img_1442583883155.png" alt="" title="">  unter  in der Symbolleiste auf. In das Fenster Print Preview kann die Seite eingerichtet und falls gewünscht gedruckt werden.</p></div></body>
</html>