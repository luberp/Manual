<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>120_Berechnungen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p> <br>
 <br>
 <br>
 <br>
 <br>
120_Berechnungen.md <br>
</p>



<p> <br>
</p><div class="container"><p>Die Funktion Berechnungen kann verschiedenste Werte, Buchungen, Anteilsbuchungen und Belege für Verträge und Beteiligungen erzeugen.</p></div><p></p>

<p>Die Möglichkeiten des Moduls sind dabei sehr vielfältig. Es reicht von einfachen Gewinnverteilungen auf Basis einer festen Zeichnungssumme bis zu komplexen Berechnungen von Dividenden mit direkter Berechnung der nötigen Steuern.</p>

<p>Berechnungen sind dabei in verschiedenen Berechnungsprofilen organisiert. Diese Profile werden im Dialog in der linke Liste anzeigt und können beliebig strukturiert werden. Sie können Profile je Produkt anlegen oder je Aufgabe ganz nach ihren Vorstellungen. Die Organisation der Berechnungen in Profilen ermöglicht eine einfachere Übersicht für den Anwender.</p>

<p>Profile haben selbst nur wenige Einstellungen im Reiter “Konfiguration”. Sie können den Namen des Profils setzen und ein Intervall für die Berechnungen angeben. Bei monatlichen Zinsberechnungen würde “monatlich” gut passen, für Jahresabschlüsse und deren Verteilungen ist “jährlich” die richtige Wahl. Profile enthalten für jeden Zeitraum unterschiedliche Berechnungen. Die Navigation innerhalb eines Profil geschieht ebenfalls auf Basis dieser Intervalle und Zeiträume. Sie können in jährlichen Profilen dann zwischen den Jahren umschalten und in monatlichen Profilen die einzelnen Monate durchblättern. Die Beschreibung des Profils ermöglicht eine Dokumentation der gedachten Aufgabe für andere Anwender.</p>

<p>Nach der Erstellung eines Profils zeigt der Dialog direkt den Reiter “Berechnungen” an. Dort können Berechnungen angelegt, durchgeführt, ausgewertet, verarbeitet und gelöscht werden. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1469546950163.png" alt="" title=""></p>

<h2 id="berechnungen-anlegen">Berechnungen anlegen</h2>

<p>Neue Berechnungen können mit einem Klick auf das +-Symbol erzeugt werden. Das System erzeugt nach der Abfrage des entsprechenden Produktes sofort einen leeren Berechnungsdatensatz im oben angegebenen Zeitraum. Dieser Berechnungsdatensatz enthält alle Elemente die für die Durchführung dieser Berechnung notwendig sind.</p>

<p>Häufig werden Berechnungen nur einmal eingestellt und dann in neue Zeiträume oder in neue Produkte kopiert. Beide Möglichkeiten bietet ihnen xpectoPro. In einem neuen Zeitraum der noch keine Berechnungen enthält ist der Knopf “aus vorheriger Periode kopieren” sichtbar. Damit können die Berechnungen aus einer vorherigen Periode kopiert werden. Das System meldet die Anzahl und die Periode der gefundenen Berechnungen und bietet eine Option (“Berechnungsläufe kopieren”) zum kopieren in die aktuelle Periode an.</p>

<p>Berechnungen können mit dem “kopieren”-Symbol auch direkt innerhalb einer Periode kopiert werden. Nach dem Markieren von einer oder mehreren Berechnungen werden diese Zeilen durch die Funktion kopiert. Falls Sie Berechnungen eines Produktes ausgewählt haben, werden Sie nach dem Zielprodukt gefragt. Falls Sie Berechnungen von verschiedenen Produkten ausgewählt haben, werden die Berechnungen direkt mit dem bisherigen Produkt kopiert.</p>

<p>Die Berechnungen werden erst nach dem Speichern in die Datenbank geschrieben.</p>

<h2 id="berechnungen-löschen">Berechnungen löschen</h2>

<p>Berechnungen können mit dem Lösch-Symbol über der Liste gelöscht werden. Dabei können nur Berechnungen gelöscht werden die nicht durchgeführt wurden oder deren Daten vorab gelöscht wurden.</p>

<p>Die Löschungen werden erst nach dem Speichern in die Datenbank geschrieben.</p>

<h2 id="berechnete-summen-anzeigen">Berechnete Summen anzeigen</h2>

<p>Berechnungen erzeugen viele Einzeldaten wie Werte oder Buchungen. Oft ist die Gesamtsumme dieser Buchungen interessant oder die Summer der aktuell noch offenen Posten. Durch die Funktion “berechnete Summen anzeigen” werden für jede Berechnung diese Werte errechnet und in drei weiteren Spalten in der Liste angezeigt. Die Errechnung der Spalten kann einige Zeit in Anspruch nehmen.</p>

<h2 id="berechnungs-parameter">Berechnungs-Parameter</h2>

<p>Die einzelnen Parameter einer Berechnungen bestimmen alle Eigenschaften des Ablaufs. Große Sorgfalt sollte daher bei Änderungen herrschen. Sie können sich jederzeit an unsere Kundenbetreuung bei Fragen oder Unsicherheiten wenden.</p>

<p>Die Parameter einer Berechnung gliedern sich in verschieden Abteilungen und sich am Ablauf der Berechnung orientieren.</p>

<h3 id="allgemein">Allgemein</h3>

<ul>
<li>Name: Ein sprechender Name für exakt diese Berechnung in diesem Zeitraum. Der Name wir im Regelfall auch als Buchungstext für die späteren Buchungen und Werte benutzt. Ein guter Name wäre “Steuerliches Ergebnis 2014” oder “Basiszinsen 2014M10”. Wenn der Name den Zeitraum enthält, wird der Name beim Kopieren von einer Periode zur nächsten Periode entsprechend geändert.</li>
<li>Berechnungsart: xpectoPro ermöglich sehr unterschiedliche Berechnungsarten <br>
<ul><li>Gebührenabrechnung: Ziel ist die Berechnung von Gebühren, Kosten oder anderen Werte für einzelne Verträge die dann aber gesammelt an Empfänger weitergegeben werden. (z.B. Verwaltungsgebühren, Provisionsabrechnung zwischen Produkt und Alleinvertrieb)</li>
<li>Gewinnverteilung: Verteilung von Gewinnen, Verlusten an Verträge und Beteiligungen</li>
<li>Zinsberechnung: Durchführung einer Zinsberechnung </li>
<li>Entnahmeberechnung: Berechnungen für die regelmäßige Kapitalminderung in Verträgen (z.B. Entnahmepläne)</li>
<li>Forderungsberechnung: Berechnungen von Forderungen ggü. Endkunden (z.B. Darlehensfinanzierungen, Finanzierungsrunden …)</li>
<li>Anteilskauf: Berechnungen von Anteilskäufen oder Depoteinbuchungen auf Basis von Kapitalständen (z.B. Edelmetalle, Aktien, Anteile)</li>
<li>VertragsÜbertragung: Diese Berechnungsart wird im Normalfall nicht über den Berechnungsdialog durchgeführt. Die Berechnungsart wird intern vom Übertragungsmodul verwendet.</li>
<li>Beschreibung: Eine kurze Beschreibung der Berechnung für Anwender und Mitarbeiter.</li>
<li>Produkt: Für welches Produkt ist diese Berechnung angelegt</li>
<li>Wertart/Zusatz: Welche Wertart soll mit dieser Berechnung erzeugt werden</li>
<li>Ebene: Sollen die Berechnungen auf Vertrags- oder Beteiligungsebene ablaufen</li>
<li>Zeitraum: Der Zeitraum für die Summierung von Werten oder für die Auswertung von Salden, kann abweichend von der Periode sein</li>
<li>Buchungsdatum: Datum zu dem die Werte und Buchungen gebucht werden</li>
<li>Anlass: Der Anlaß der Berechnung. Der Wert kann für die Organisation der Berechnungen benutzt werden. (z.B. Erklärung, Prüfung …)</li></ul></li>
</ul>

<p></p><h3 id="datenbasis">Datenbasis</h3> <br>
<p></p></div></body>
</html>