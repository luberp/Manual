<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>910_Duplikte_finden.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Mit zunehmendem Alter der Datenbank enstehen Duplikaten, besonders wenn mehrere Benutzer Daten eingeben. Unter Duplikate finden können Duplikate gesucht und aufgelöst, damit kann die Genauigkeit Ihrer Daten erhöht werden. <br>
Es gibt die Möglichkeit nach Duplikate in Kundendaten, Vertriebspartner und Kontoverbindungen zu suchen.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1421242451087.png" alt="" title=""> <br>
Wählen Sie hier Kontoverbindungen. <br>
<img src="http://xpecto.github.io/docs/img/img_1421247350050.png" alt="" title=""></p>

<p>Bitte klicken Sie auf die jeweiligen Werte, die in den neuen Datensatz übernehmen werden sollen. <br>
<img src="http://xpecto.github.io/docs/img/img_1421247414670.png" alt="" title=""></p>

<p>Duplikate auflösen</p>

<p><img src="http://xpecto.github.io/docs/img/img_1421247541196.png" alt="" title=""></p>

<p>“Wollen Sie den Datensatz ….wirklich löschen?” mit <em>Ja</em> wird der Datensatz aus der Datenbank gelöscht. Es können nur neu <br>
erfasste Datensätze, bzw. Datensätze, auf die noch nicht von anderen Datensätzen verwiesen wird, gelöscht werden. Im speziellen <br>
heißt dies z.B., dass ein Vermittler, der bereits einen Vertrag verkauft hat, ein Kunde, zu dem bereits ein Vertrag erfasst ist, oder ein Vertrag, zu <br>
dem bereits Buchungen erfasst sind, nicht gelöscht werden kann. Der Zweck dieses Menüpunkts ist lediglich die zeitnahe Löschung von <br>
Falscherfassungen.</p>

<p>Aus Gründen der Historisierung und Nachvollziehbarkeit werden Datensätze, die bereits mit anderen Datensätzen verknüpft sind, nicht aus <br>
der Datenbank gelöscht, sondern nur durch einen entsprechenden Status (wie z.B. Storno oder ausgeschieden) gekennzeichnet.</p>

<p>Eine saubere Datenbasis erleichtert die Arbeit ungemein. Ein häufiges Problem bei der Erfassung von Daten ist die doppelte Eingabe von Kunden, Vertriebspartner oder anderen Adressen.</p>

<p>Mit dem xpecto Werkzeug “Duplikate finden” können Sie elegant doppelte Adressen suchen, finden und zusammenführen.</p>

<p>Um das Werkzeug zu benutzen wählen Sie “Bearbeiten”/”Duplikate finden”. Sie wählen nun die Datenbasis wie z.B. Kundendaten. Das System listet nach kurzer Wartezeit die gefundenen Duplikate auf und zeigt die Unterschiede der beiden Datensätze an. Sie können nun die entsprechenden Daten verändern oder die zu übernehmenden Datenfelder auswählen. Mit einem Klick auf “Duplikat auflösen” wird ein Datensatz entfernt und der verbleibende Datensatz aktualisiert. Alle Daten die zum alten Kunden gehören wie Verträge, Provisionen und Dokumente werden automatisch auf den neuen Kunden übertragen.</p></div></body>
</html>