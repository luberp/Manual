<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>100_Datensatz_löschen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Über diesen Menüpunkt wird der aktuell ausgewählte Kunde, Vertrag oder Vermittler gelöscht. Nach Bestätigung der Warnmeldung</p>

<p><img src="http://xpecto.github.io/docs/img/img_1420450924589.png" alt="" title=""></p>

<p>“Wollen Sie den Datensatz … wirklich löschen?” mit <em>Ja</em> wird der Datensatz aus der Datenbank gelöscht. Es können nur die Datensätze gelöscht werden, auf die noch nicht referenziert wurde. Im Speziellen heißt dies z.B., dass ein Vermittler, der bereits einen Vertrag verkauft hat, ein Kunde, zu dem bereits ein Vertrag erfasst ist, oder ein Vertrag, zu dem bereits Buchungen erfasst sind, nicht gelöscht werden können. Der Zweck dieses Menüpunkts ist die zeitnahe Löschung von Datensätzen.</p>

<p>Eine Löschung von bereits referenzierten Datensätzen wird mit folgender Fehlermeldung unterbunden:</p>

<p><img src="http://xpecto.github.io/docs/img/img_1420458029242.png" alt="" title=""></p></div></body>
</html>