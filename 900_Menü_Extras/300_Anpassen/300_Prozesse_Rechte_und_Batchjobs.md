<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>300_Prozesse_Rechte_und_Batchjobs.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Symbolleiste: Speichern, Prozesse neu anlegen, Benutzer neu anlegen, Batch-Jobs neu anlegen, Systembenutzer abfragen und speichern, Prozess importieren, Prozess exportieren, Druckvorschau. <br>
Prozesse: Allgemein, Designer <br>
Benutzer: Allgemein, Rechte, Gruppenmitglieder <br>
Batchjobs: Allgemein <br>
Batchjobs sind automatisierte Prozesse </p>

<hr>

<p>In xpectoPro kann jeder Menüpunkt und jeder Karteireiter sowie das starten der Software pro Benutzer individuell gesperrt oder erlaubt werden. Der in xpectoPro verwendete Benutzer ist der jeweils angemeldete Windows-Benutzer.</p>

<p>In der Liste der Vorhanden Benutzer werden automatisch die in der Windows Domäne vorhandenen Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. Einen neuen Benutzer legen Sie durch Click auf die Schaltfläche<img src="http://xpecto.github.io/docs/img/img211.png" alt="" title="">an.</p>

<p><img src="http://xpecto.github.io/docs/img/img212.png" alt="" title=""></p>

<p>Geben Sie einen Benutzernamen ein. Achten Sie darauf, dass der gewählte Benutzername bereits ein Benutzerkonto im Windows Betriebssystem besitzt. Bei Windows Domänen-Benutzern setzt sich der Benutzername aus Domänenname\Benutzername zusammen. Sollten Ihre Benutzer also an einem Domänenkontroller angemeldet sein, so berücksichtigen Sie dies bitte bei der Erstellung des Benutzerskontos. Bestätigen Sie mit <em>OK</em>. <br>
Nachdem Sie mit der Schaltfläche<img src="http://xpecto.github.io/docs/img/img013.png" alt="" title=""> speichern, wird der neue Benutzer in der linken Liste angezeigt.</p>

<p>Beim Start der Software werden zuerst die Rechte des angemeldeten Benutzers ermittelt und daraufhin nur die Menüpunkte und Karteireiter angezeigt, für die der Benutzer berechtigt ist oder gegebenenfalls der Start der Software abgebrochen. Die Ermittlung der Berechtigungen eines angemeldeten Benutzers erfolgt in zwei Stufen. Zuerst werden die Rechte des Benutzers “Default” abgefragt (der Benutzer “Default” wird bei der Installation der Software automatisch angelegt und mit dem Recht “Administrator” ausgestattet). Danach werden die Rechte des tatsächlich angemeldeten Benutzers abgefragt, diese überblenden gegebenenfalls die Rechte des Benutzers Default.</p>

<p>Beispiel: Beim Benutzer “Default” sei das Recht zum Start von eAgentur auf <em>erlauben</em> gesetzt. Bei einem bestimmten Benutzer sei jedoch zusätzlich das Recht zum Start von eAgentur auf _verbieten _gesetzt. Dadurch ist allen Windows Benutzern grundsätzlich das starten der Software möglich. Der bestimmte Benutzer kann jedoch eAgentur nicht starten, obwohl beim Benutzer “Default” das Recht auf erlauben <br>
gesetzt ist.</p>

<p>Spezielle Rechte: Die Rechte “Administrator” und “Poweruser” umfassen alle möglichen Rechte, d.h. das Setzen eines der beiden Rechte bei einem Benutzer ist äquivalent zum Setzten aller anderen Rechte bei demselben Benutzer. Bei “Poweruser” können einzelne Rechte für den Benutzer durch Setzen des entsprechenden Rechts auf _verbieten _entzogen werden. Im Gegensatz dazu ist dies bei “Administrator” nicht möglich!</p>

<p><img src="http://xpecto.github.io/docs/img/img214.png" alt="" title=""></p>

<p>Zur Einstellung der Rechte eines Benutzers selektieren Sie den Benutzer und betätigen Sie die Schaltfläche <img src="http://xpecto.github.io/docs/img/img046.png" alt="" title="">, um eine neue Berechtigungszeile einzufügen. In der Auswahlbox Recht wird das gewünschte Recht ausgewählt, und unter Wert die jeweilige Berechtigungsstufe <em>erlauben</em>, <em>verbieten</em> oder <em>default</em>.</p>

<hr>

<p>Unter Prozesse können Wiedervorlagen, Mahnprozesse, Zeichnung angelegt werden. <br>
xpectoPro ermöglicht die Integration von Ablaufprozessen in die tägliche Arbeit. Nahezu alle Elemente und Funktionen der Software können in vordefinierte Abläufe eingebunden werden. Die Abläufe sind umfangreich konfigurierbar und ermöglichen eine strukturierte Arbeitsweise. Insbesondere verteilte Teams profitieren von der Aufgabentrennung und der gemeinsamen Kommunikation über Prozesse. <br>
Die Prozesse können über einen grafischen Designer erstellt werden. Die Steuerung der Prozesse erfolgt mit einer zentralen „Wiedervorlage-Steuerung” die alle Prozesselemente einsehen darf. Leiter von Callcentern, Vertrieben oder Verwaltungen haben so stets den Überblick über alle wichtigen Abläufe. <br>
Die Einbindung von externen Stellen zur Datenerfassung, zur Prüfung/Compliance oder zur Betreuung ist über Prozesse sehr gut möglich. </p>

<p>Beispiel Annahmeprozess: <br>
Erstellung der Verkaufsunterlagen über Webportal durch Vertriebspartner <br>
Einreichung der Verkaufsunterlagen bei Gesellschaft <br>
Eingabe der Daten und Unterlagen durch Compliance, Vertreib o.ä. <br>
nach erfolgreicher Prüfung: Druck und Versand der Begrüßung <br>
Wartezeit auf Geldeingang, Alarm nach 14 Tagen <br>
vollständiger Geldeingang</p>

<p>Beispiel Kundenaquise: <br>
Kunde gibt Daten auf Kontaktformular ein. <br>
Callcenter ruft Kunden direkt an <br>
Versand von Unterlagen <br>
Callcenter ruft Kunden zur Beratung und Fragen an <br>
Kunde sendet unterschriebenen  Vertrag <br>
Weiterführung im Annahmeprozess</p>

<p>Beispiel Mahnwesen: <br>
Kunde erzeugt Rücklastschrift oder zahlt nicht innerhalb eines bestimmten Zeitraums <br>
Je nach Grund wird Callcenter oder Vertriebspartner aktiv <br>
Bearbeiter ergänzt weiteres Vorgehen <br>
erneute Wartezeit <br>
Kunde hat gezahlt erledigt <br>
Kunde hat nicht gezahlt nächste Mahnstufe</p>

<p>In xpectoPro kann jeder Menüpunkt und jeder Karteireiter sowie das Starten der Software pro Benutzer individuell gesperrt oder erlaubt werden. Der in xpectoPro verwendete Benutzer ist der jeweils angemeldete Windows-Benutzer. In der Liste der vorhandene Benutzer werden automatisch die in der Windows Domäne vorhandene Benutzer eingetragen. Werden die Benutzer nicht automatisch erkannt, können sie manuell angelegt werden. Einen neuen Benutzer legen sie durch Klick auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1424426984009.png" alt="" title=""> an.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1424427033970.png" alt="" title=""> <br>
Geben Sie einen Benutzernamen ein. Achten Sie darauf, dass der gewählte Benutzername bereits ein Benutzerkonto im Windows Betriebssystem besitzt.  <br>
Systembenutzer abfragen und speichern holt alle Benutzer aus Active Directoy ab und speichert diese.</p></div></body>
</html>