<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>912_Stapelbuchungen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>xpectoPro enthält eine vollständige, zertifizierte Buchhaltung. Alle Einzahlungen, Forderungen, Dividenden, Gebühren und Auszahlungen werden innerhalb der Buchhaltung für jeden Anleger geführt. Die Buchung erfolgt mit einem vom Anwender vorgegebenen Kontenrahmen, typischerweise SKR03 oder SKR04.</p>

<p>Da die meisten Buchungen automatisch vom System bei bestimmten Aktionen erzeugt werden, ist die genaue Kenntnis des Kontenrahmens für die tägliche Benutzung meist nicht relevant. In bestimmten Fällen ist es jedoch sinnvoll direkt Buchungen anzulegen oder zu ändern. Für diese manuellen Buchungen und Korrekturen dient der Stapelbuchungsdialog.</p>

<p>Sie erreichen den Stapelbuchungim Menü “Bearbeiten”.Die Maske  ermöglicht die Eingabe, die Änderung und die Suche von Buchungen. Für die Weitergabe der Buchungen und die Revisionssicherheit der Buchhaltung können Sie Buchungen festschreiben und in protokollierter Weise exportieren.</p>

<p>Die Stapelbuchungs-Maske ist das zentrale Werkzeug zur Verwaltung von Buchungsdaten der Fondsbuchhaltung. Sie ist im wesentlichen in vier Funktionsbereiche untergliedert:</p>

<ul>
<li>Stapel-Erfassung</li>
<li>Suchen / Ändern</li>
<li>Buchungen festschreiben</li>
<li>Buchungen exportieren</li>
</ul>

<p>Die Stapelbuchung kann jeweils für ein bestimmtes Produkt samt seinen Buchungen, geöffnet werden. Sind in der Datenbank mehrere Produkte angelegt, so wird vor dem Öffnen der Stapelbuchungs-Maske ein Produkt-Auswahl-Dialog angezeigt. Das gewählte Produkt wird in der Titelzeile des Stapelbuchungs-Dialog angezeigt. Solange der Dialog geöffnet ist, können darin nur Buchungsdaten des entsprechenden Produkts / Fonds verwaltet werden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1439547282677.png" alt="" title=""></p>

<p>Jeder Funktionsbereich der Stapelbuchung definiert sich durch die Verfügbarkeit spezifischer Filter und Buttons zum Durchführen bestimmter Aktionen. Allen vier Funktionsbereichen gemein ist ein Berarbeitungsbereich sowie Buchungsliste sowie einemit  zum Anzeigen bzw. Bearbeiten einer Buchung. Die jeweiligen von Anwender konfigurierten Filter bestimmen, welche Buchungen in der Buchungsliste angezeigt werden. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1439810233436.png" alt="" title=""></p>

<p>Die Feldgruppe <em>Buchung bearbeiten</em> zeigt die Detail-Informationen des aktuell in der Buchungsliste selektierten Buchungssatzes. Sie enthält die Felder <em>Belegdatum, Konto, Gegenkonto, Betrag, Buchungstext, Belegnummer</em> sowie optional auszufüllenden (und nicht zur Buchhaltung gehörenden) Felder <em>Valutadatum, Vertrag, Ust-Kennz.</em> und <em>Bemerkung.</em> Die Pflichtfelder sind gelb hinterlegt. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1439798971081.png" alt="" title=""></p>

<p><em>Valutadatum</em> bezeichnet das Datum, ab dem Kontobewegungen wirksam werden. Valuta und Wertstellung bedeuten das gleiche, sie unterscheiden sich aber von der Buchung. Das <em>Valutadatum</em> ist das Datum, an dem eine Gutschrift oder Belastung wirksam wird. Das Buchungsdatum informiert nur über Kontobewegungen, während die Valuta den echten Kontostand anzeigt. </p>

<p>Unter <em>Valutadatum</em> wird das Datum erfasst, zu dem der Datensatz bei Berechnungen (wie z.B. Gebührenberechnung) berücksichtigt wird. Dieses kann unter Umständen vom Belegdatum abweichen. Unter <em>Vertrag</em> kann eine Vertrags-Nr. erfasst werden, der die selektierte Buchungen zugeordnet werden soll.  <br>
Unter <em>USt-Kennz.</em> (Umsatzsteuer-Kennzeichen) kann ein Umsatzsteuer-Satz erfasst werden, der bei Berechnungen verwendet werden soll. Dieses Feld enthält nicht die Umsatzsteuer zu der selektierten Buchung.  <br>
Unter Bemerkung können Bearbeiter-Hinweise zu der selektierten Buchungen eingegeben werden. <br>
Unter Betrag ist zum eingegebenen Betrag zusätzlich die Währung auszuwählen. Dabei fließen nur Datensätze mit der beim Produkt hinterlegten Währung in die Buchhaltung ein (siehe <em>Produkt → Währung</em>). <br>
Unter bestimmte Voraussetzungen (z.B. <em>Buchungen exportieren</em> gewählt oder <em>Buchungen festschreiben</em>) ist die Feldgruppe <em>Buchung bearbeiten</em> in GoBS-Modus (Grundsätze ordnungsmäßiger DV-gestützter Buchführungssysteme). GOBS-Modus ist ein Read-Only-Modus Änderungsschutz, keine Änderungen möglich.</p>

<p>Das sind die Buchungsschlüssel die bei Produkt hinterlegt sind. </p>

<p>Festschreiben damit nichts mehr geändert wird. <br>
Wenn eine festgeschriebene Buchung gelöscht wird, wird sie einfach nur storniert. <br>
1.Festschreiben 2.Schließen 3. Exportieren.</p>

<p>Stapelbuchungen sind alle Buchungsdaten pro Fond.</p>

<p>Buchungen exportieren von Nebenbuchhaltung zur Hauptbuchhaltung.</p>

<p>Reiter <em>Stapel-Erfassung</em> dient der Ersterfassung von Buchungen. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden alle Buchungen angezeigt, die von dem aktuell angemeldeten Benutzer am selben Tag bereits erfasst wurden. Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439801023332.png" alt="" title=""> wird ein neuer Datensatz angelegt. Die Details des Buchungssatzes werden über die Feldgruppe <em>Buchung bearbeiten</em> eingegeben und dann  <br>
<img src="http://xpecto.github.io/docs/img/img_1439804594653.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1439799333097.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1439799522434.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1439799558194.png" alt="" title=""></p>

<p><img src="http://xpecto.github.io/docs/img/img_1439799593743.png" alt="" title=""></p></div></body>
</html>