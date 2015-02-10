<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>500_Berechnungen_und_Transaktionen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p><img src="http://xpecto.github.io/docs/img/img_1423558893524.png" alt="" title=""></p>

<p>Über diesen Menüpunkt wird der aktuell ausgewählte Kunde, Vertrag oder Vermittler gelöscht. Nach Bestätigung der Warnmeldung <br>
“Wollen Sie den Datensatz ….wirklich löschen?” mit <em>Ja</em> wird der Datensatz aus der Datenbank gelöscht. Es können nur neu <br>
erfasste Datensätze, bzw. Datensätze, auf die noch nicht von anderen Datensätzen verwiesen wird, gelöscht werden. Im speziellen <br>
heißt dies z.B., dass ein Vermittler, der bereits einen Vertrag verkauft hat, ein Kunde, zu dem bereits ein Vertrag erfasst ist, oder ein Vertrag, zu <br>
dem bereits Buchungen erfasst sind, nicht gelöscht werden kann. Der Zweck dieses Menüpunkts ist lediglich die zeitnahe Löschung von <br>
Falscherfassungen.</p>

<p>Aus Gründen der Historisierung und Nachvollziehbarkeit werden Datensätze, die bereits mit anderen Datensätzen verknüpft sind, nicht aus <br>
der Datenbank gelöscht, sondern nur durch einen entsprechenden Status (wie z.B. Storno oder ausgeschieden) gekennzeichnet. <br>
xpectoPro ermöglicht vielfältige Berechnungen und Ausschüttungen. Die Berechnungen werden exakt nach ihren Vorgaben erstellt. Etwaige Steuern wie Kapitalertragssteuer, Solidaritätszuschlag oder EU-Quellensteuer können sehr einfach integriert werden. Thesaurierungen, Auszahlungssperren und Freistellungsaufträge werden berücksichtigt.</p>

<p>Die Berechnung der Buchungen wird über den Dialog “Berechnungen”/”Berechnungen und Transaktionen” durchgeführt. Hier können alle laufenden Berechnungen als Vorlage hinterlegt werden. Die Berechnungen haben dabei eine Art der Berechnung (wie z.B. Gewinnverteilung, Verzinsung, Entnnahme) ein Ausführungsinterall und eine grundsätzliche Berechnungsmethode (wie z.B. 30/360 Tage Regelung oder eine Verzinsung der monatlichen Endstände). Jedes Produkt wird intern als eigener Mandant mit einer eigenen Buchhaltung geführt, die Berechnung kann aber übergreifend erfolgen. Die Berechnung von Dividenden oder Zinsen ist somit auch für viele Produkte elegant durchführbar.</p>

<p>Die Berechnung kann für einen bestimmten Zeitraum des festgelegten Intervalls erfolgen. Der Buchungssatz und der Buchungstext können individuell verändert werden. Mit einem Klick auf “Start” wird die Berechnung für alle Verträge der gewählten Produkte durchgeführt. Nach erfolgter Berechnung sehen wir das Ergebnis für jedes Produkt. Von hier aus können wir die abschließenden Schritte durchführen:</p>

<p>Überweisung/Zahlungsdateien und Belege erstellen  <br>
Übersichtslisten für die komplette Berechnung erstellen  <br>
Einzelschreiben für jeden Anleger erstellen und versenden <br>
Der komplette Ablauf ist sehr gut automatisiert und wird von uns für die einzelnen Anwendungsfälle genauestens konfiguriert. Die regelmäßige Berechnung von Zinsen, Dividenden, Basisdividenden oder Überschüssen ist damit eine leichte Übung.</p></div></body>
</html>