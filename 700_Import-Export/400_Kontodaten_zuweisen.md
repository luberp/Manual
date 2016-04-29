<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>400_Kontodaten_zuweisen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>In diesem Modul werden aus der vorher in eine temporäre Tabelle, importierten Buchungen/Bankbewegungen Buchnungssätze erzeugt und den korrekten Verträgen/Beteiligungen/Produkten zugewiesen. Dabei müssen Buchungen die noch nicht automatisch einem Vertrag zugewiesen wurden, manuell zugewiesen werden.</p>

<p>In der modernen Menü-Ansicht starten Sie den Dialog <em>importierte Buchungen zuweisen</em> über Menü <em>Import/Export → Kontodaten zuweisen</em>.</p>

<p>In der klassischen Menü-Ansicht wird der Dialog über Registerkarte <em>Buchhaltung</em> Gruppe <em>Kontodaten</em> Funktion <em>Verbuchung</em> gestartet.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461921052626.png" alt="" title=""></p>

<p>Klicken  Sie auf die Funktion Verbuchung um mit der Kontodaten zuweisen anzufangen.</p>

<p>In dem Dialog <em>Buchungen zuweisen</em> wird die Liste der Produkte mit ihre offenen und geparkte Buchungen angezeigt.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461921347593.png" alt="" title=""></p>

<p>Die Schaltfläche Rundruf starten <img src="http://xpecto.github.io/docs/img/img_1461922190992.png" alt="" title=""> dient dazu die Kontobewegungen für den markierten Produkt bei der Bank abzufragen. </p>

<p>Ein Rundruf für alle Produkte kann über die Registerkarte <em>Buchhaltung</em> Gruppe <em>Kontodaten</em> Funktion <em>Rundruf</em> gestartet werden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461922444175.png" alt="" title=""></p>

<p>Durch einen Klick auf  <em>OK</em> werden Sie zum Dialog <em>importierte Buchungen zuweisen</em> weitergeleitet.  <br>
Der Dialog <em>importierte Buchungen zuweisen</em> enthält die Reiter <em>Buchungen anzeigen</em> und <em>geparkte Buchungen anzeigen</em>.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461924039863.png" alt="" title=""></p>

<p>Unter dem Reiter <em>Buchungen anzeigen</em> werden die Details der Buchung und in der Mitte die Navigation, mit der Pfeilen können Sie durch die Buchungen blättern.  <br>
In der Feldgruppe <em>Buchung</em> sehen Sie den Zahlungspflichtigen/Kontoinhaber/Absender, den Verwendungszweck und die Details der Buchung. Mit einem Doppelklick auf einzelne Wörter wird das Wort als Suchkriterium verwendet. Klicken Sie mit der Maus auf Teile der Buchungsdaten wie z.B. Name um alle Verträge mit Vertragsbezeichner zu erhalten. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461923077386.png" alt="" title=""></p>

<p>Mit einem Klick auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442307719407.png" alt="" title=""> werden aus allen Bankbewegungen, die beim Import bereits einem Vertrag zugewiesen wurden, automatisch Buchungssätze erzeugt und gespeichert. Dazu muss zu dem jeweiligen Produkt hinterlegt sein, welche Kontierung hier verwendet werden soll.  <br>
Das zu verwendende Konto wird in der Produktmaske (<em>Datei → Produkte</em>) auf dem Reiter <em>Allgemein</em> unter <em>Konto RZ</em> eingetragen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461923339214.png" alt="" title=""></p>

<p>Neben der Möglichkeit eine neue Buchung anzulegen können Sie die Kontobewegungen über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1461923451087.png" alt="" title=""> direkt bei der Bank abfragen.  Es wird ein Kontorundruf durchgeführt. Die gefundene Buchungen werden von der Bank dann abgeholt und in der Liste eingefügt.</p>

<p>Mit einem Klick auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442404617262.png" alt="" title=""> werden Sie zu dem Stapelbuchungsdialog weitergeleitet (siehe Handbuch <em>Bearbeiten → Stapelbuchung</em>). </p>

<p>In der untere Hälfte des Dialogs <em>importierte Daten zuweisen</em> sehen Sie die Liste der Buchungen mit der Vorschlag wie die Buchungen verbucht werden sollen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461924691118.png" alt="" title=""></p>

<p>Im Bereich unten kann das Konto für den zu erzeugenden Buchungssatz ausgewählt werden. Werden hier mehrere Zeilen eingetragen, so wird die Bankbuchung in mehrere Buchungssätze gesplittet. Die Aufteilung der Beträge muss dabei manuell eingetragen werden. Der Buchungstext kann per Hand angepasst werden.</p>

<p>Die Schaltfläche <em>offene Posten abfragen</em> dient dazu um offene Posten für diesen Vertrag anzuzeigen und die Schaltfläche <em>Rückbuchung zuordnen</em> dient dazu die geschlossene Posten für den markierter Vertrag anzuzeigen.</p>

<p>Über die Schaltfläche <em>Sammelauftrag auflösen</em> können Sie aus einem Zahlungsauftrag mehrere Einzelaufträge wie Überweisungen oder Lastschriften erstellen. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1442411007721.png" alt="" title=""></p>

<p>Markierte Buchungen, die nicht gespeichert werden sollen, können mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1461925093310.png" alt="" title=""> gelöscht werden.</p>

<p><em>Buchungen aufteilen</em> teilt die Buchung in 2 Buchungen auf. Der Aufteilungsbetrag kann eingegeben werden. Die so entstandene Buchungen können dann wieder verbucht werden.</p>

<p><em>Buchungen übertragen</em> damit werden die Buchungen von anderen Fonds auf einen anderen übertragen. Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442406481698.png" alt="" title="">, werden die Buchungen für spätere Verbuchungen zugänglich gemacht. Die werden dann sichtbar unter dem Reiter <em>geparkte Buchungen anzeigen.</em></p>

<p>Um den Vorgang einem Prozess zuzuweisen, setzen Sie in der Checkbox <em>Prozess starten</em> ein Häkchen. Der Prozess wird dann in der Wiedervorlage-Liste, bei der verantwortlichen Person angezeigt.</p>

<p>Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442236615351.png" alt="" title="">, speichern Sie die zum Vertrag zugewiesenen Buchungen (das Speichern ist nur möglich, wenn die Summe der eingegebenen Split-Beträge exakt den Buchungsbetrag ergibt). Nach erfolgreichen Speichern wird die nächste Import-Buchung angezeigt.  <br>
Alle gespeicherten Buchungen werden in die interne Buchhaltung aufgenommen (siehe Hanbuch <em>Bearbeiten → Stapelbuchung</em> und unter Vertragsmaske Reiter <em>Buchungsdaten</em> angezeigt.</p>

<p>Eine falsch importierte Buchung kann im Nachhinein gelöscht werden, und zwar in dem Dialog <em>Stapelbuchung</em>. Der Dialog kann über <em>Bearbeiten → Stapelbuchung</em> oder über <em>Bearbeiten → Beteiligungs-/Vertragsbuchungen</em> geöffnet werden. Markieren Sie hier die gewünschte Buchung und klicken Sie auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1442912298087.png" alt="" title="">. </p></div></body>
</html>