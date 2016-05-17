<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>911_Stapelbuchungen.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>xpectoPro enthält eine vollständige und zertifizierte Buchhaltung. Alle Einzahlungen, Forderungen, Dividenden, Gebühren und Auszahlungen werden innerhalb der Buchhaltung für jeden Anleger geführt. Die Buchung erfolgt mit einem vom Anwender vorgegebenen Kontenrahmen, typischerweise SKR03 oder SKR04. <br>
Da die meisten Buchungen automatisch vom System bei bestimmten Aktionen erzeugt werden, ist die genaue Kenntnis des Kontenrahmens für die tägliche Benutzung meist nicht relevant. </p>

<p>Die Stapelbuchung-Maske ermöglicht die manuelle Eingabe, die Änderung und die Suche von Buchungen. Für die Weitergabe der Buchungen und die Revisionssicherheit der Buchhaltung können Sie Buchungen festschreiben und in protokollierter Weise exportieren.</p>

<p>In der klassischen Menü-Ansicht gelangen Sie in die Stapelbuchung durch klicken  in Menü <em>Bearbeiten → Stapelbuchung</em>.</p>

<p>In der modernen Menü-Ansicht finden Sie die Stapelbuchung in der Registerkarte <em>Buchhaltung</em> Gruppe <em>Buchungsdaten.</em></p>

<p><img src="http://xpecto.github.io/docs/img/img_1461684057429.png" alt="" title=""> </p>

<p>Die Stapelbuchung kann jeweils für ein bestimmtes Produkt samt seinen Buchungen, geöffnet werden. Sind in der Datenbank mehrere Produkte angelegt, so wird vor dem Öffnen der Stapelbuchungs-Maske ein Produkt-Auswahl-Dialog angezeigt. Solange die Maske geöffnet ist, können darin nur Buchungsdaten des entsprechenden Produkts / Fonds verwaltet werden.</p>

<p>Die Maske <em>Stapelbuchung</em> ist das zentrale Werkzeug zur Verwaltung von Buchungsdaten der Fondsbuchhaltung. Sie ist im wesentlichen in vier Funktionsbereiche untergliedert:</p>

<ul>
<li>Stapel-Erfassung</li>
<li>Suchen / Ändern</li>
<li>Buchungen festschreiben</li>
<li>Buchungen exportieren</li>
</ul>

<p>Jeder Funktionsbereich der Stapelbuchung definiert sich durch die Verfügbarkeit spezifischer Filter und Buttons zum Durchführen bestimmter Aktionen. Allen vier Funktionsbereichen gemein ist ein Bearbeitungsbereich mit den Feldgruppen: <em>Buchung bearbeiten, Fremdwährung</em> und <em>Verarbeitungsinfos</em> - zum Anzeigen bzw. Bearbeiten einer Buchung, und eine Buchungsliste. Die jeweiligen von Anwender konfigurierten Filter bestimmen welche Buchungen in der Buchungsliste angezeigt werden. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461685073709.png" alt="" title=""></p>

<p>Die Feldgruppe <em>Buchung bearbeiten</em> zeigt die Detail-Informationen des aktuell in der Buchungsliste selektierten Buchungssatzes. Sie enthält die Felder <em>Belegdatum, Konto, Gegenkonto, Betrag, Buchungstext, Belegnummer</em> sowie optional auszufüllenden (und nicht zur Buchhaltung gehörenden) Felder <em>Valutadatum, Vertrag, Ust-Kennz.</em> und <em>Bemerkung.</em> Die Pflichtfelder sind gelb hinterlegt. </p>

<p>Das <em>Belegdatum</em> informiert über Kontobewegungen, während das <em>Valutadatum</em> das Datum ist, an dem eine Gutschrift oder Belastung wirksam wird. Das <em>Valutadatum</em> zeigt den echten Kontostand an. Dieses kann unter Umständen vom <em>Belegdatum</em> abweichen.  <br>
Unter <em>Vertrag</em> kann eine Vertrags-Nr. erfasst werden, der die selektierte Buchungen zugeordnet werden soll.  <br>
Unter <em>USt-Kennz.</em> (Umsatzsteuer-Kennzeichen) kann ein Umsatzsteuer-Satz erfasst werden, der bei Berechnungen verwendet werden soll. <br>
Unter <em>Betrag</em> ist zum eingegebenen Betrag zusätzlich die Währung auszuwählen. Dabei fließen nur Datensätze mit der beim Produkt hinterlegten Währung in die Buchhaltung ein (siehe Handbuch <em>Produkt → Währung</em>). <br>
Unter <em>Bemerkung</em> können Bearbeiter-Hinweise zu der selektierten Buchungen eingegeben werden. <br>
Unter bestimmten Voraussetzungen (z.B. <em>Buchungen exportieren</em> gewählt oder <em>Buchungen festschreiben</em>) ist die Feldgruppe <em>Buchung bearbeiten</em> in GoBS-Modus (Grundsätze ordnungsmäßiger DV-gestützter Buchführungssysteme). GoBS-Modus ist ein Read-Only-Modus Darstellung, Sie können diese Buchungen nicht ändern.</p>

<p>Der Reiter <em>Stapel-Erfassung</em> dient der Ersterfassung von Buchungen. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden alle Buchungen angezeigt, die von dem aktuell angemeldeten Benutzer am selben Tag bereits erfasst wurden. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461685406019.png" alt="" title=""></p>

<p>Klicken Sie auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439974064694.png" alt="" title=""> um Vorlagen für Ihre Buchungssätze anzulegen oder zu bearbeiten. <br>
Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439801023332.png" alt="" title=""> wird ein neuer Datensatz angelegt. Die Details des Buchungssatzes werden über die Feldgruppe <em>Buchung bearbeiten</em> eingegeben. <br>
Die Gültigkeit des eingegebenen Belegdatums und des Betrags wird direkt beim Verlassen des jeweiligen Feldes geprüft. Vor dem Speichern wird außerdem geprüft, ob die Pflichtfelder <em>Betrag, Belegdatum, Konto, Gegenkonto</em> und <em>Buchungstext</em> befüllt sind. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1439812810573.png" alt="" title=""></p>

<p>Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439804594653.png" alt="" title=""> wird die Buchung gespeichert. Beim Speichern der Buchung wird automatisch der Erfasser und der Erfassungszeitpunkt in den Buchungsdatensatz eingetragen. Die Buchungsperiode, zu der ein Buchungssatz gehört, richtet sich nach dem Belegdatum, sie wird nicht separat erfasst. Ein hier erfasster Datensatz kann über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439813538430.png" alt="" title=""> jederzeit wieder gelöscht werden, solange er noch nicht festgeschrieben ist. Festschreiben bedeutet dass eine Buchung dann nur noch durch eine Storno/Korrekturbuchung korrigiert werden kann. Damit werden nachträgliche Manipulationen erschwert.</p>

<p>Reiter <em>Suchen / Ändern</em> dient der Recherche und ermöglicht das Suchen und Ändern von Buchungen. Die Suchkriterien zum Auffinden der gewünschten Buchungssätze können über verschiedenen Filter wie  <em>Buchungsperiode, Beteiligung/Vertrag, Erfassung, Kontierung, Festschreibung</em> konfiguriert werden.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1461685262474.png" alt="" title=""></p>

<p>Nicht festgeschriebene Buchungen können gelöscht oder geändert werden. Änderungen werden erst durch einen Klick auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439804594653.png" alt="" title=""> gespeichert. Vor dem Speichern werden dieselben Gültigkeitsprüfungen durchlaufen, wie in dem Reiter <em>Stapel-Erfassung</em>. </p>

<p>Bereits festgeschriebene Buchungen (erkennbar durch eingetragene Buchungs-Nr in der Feldgruppe <em>Verarbeitungsinfos</em>) können nachträglich nicht mehr verändert werden. Wird eine festgeschriebene Buchung selektiert, so ist der Bearbeitungsbereich in Read-Only-Modus und die Schaltfläche  <img src="http://xpecto.github.io/docs/img/img_1439813538430.png" alt="" title=""> ist deaktiviert. Solange die betroffene Buchungsperiode nicht geschlossen ist, kann jedoch über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439816158639.png" alt="" title=""> eine Storno-Buchung erzeugt werden. Wird die Abfrage “Möchten Sie eine Korrekturbuchung anlegen?” mit <em>Ja</em> beantwortet, so wird eine änderbare (da nicht festgeschriebene) Kopie der Original-Buchung in derselben Buchungsperiode angelegt.</p>

<p>Der Reiter <em>Buchungen festschreiben</em> dient der Übertragung von Buchungssätze in das Buchungsjournal.  <br>
Im Buchungsjournal werden alle Buchungen eines gewählten Zeitraums tabellarisch aufgelistet. Die Kriterien zur Auswahl der festzuschreibenden Datensätze können über verschiedene Filter konfiguriert werden, wie <em>Buchungsperiode, Beteiligung/Vertrag, Erfassung, Kontierung</em>. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461685459829.png" alt="" title=""></p>

<p>Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439820973695.png" alt="" title=""> werden alle aufgelisteten Erfassungen in das Buchungsjournal übertragen und in jeden betroffenen Buchungssatz der Festschreibungs-Zeitpunkt, der ausführende Benutzer und eine fortlaufenden Buchungsnummer eingetragen werden. Die Festschreibung einer einmal in das Journal übertragenen Buchung kann nachträglich nicht mehr aufgehoben werden. Die Buchung kann dann nur noch über <em>Suchen / Ändern</em> <img src="http://xpecto.github.io/docs/img/img_1439816158639.png" alt="" title=""> storniert werden.</p>

<p>Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1463479213984.png" alt="" title=""> wird eine Buchungsperiode geschlossen. Eine Buchungsperiode entspricht einem Kalendermonat. In einer bereits geschlossenen Buchungsperiode kann nicht mehr gebucht werden. Um das Buchen in einer geschlossenen Buchungsperiode zu ermöglichen, muss die Periode über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1463479270448.png" alt="" title=""> wieder geöffnet werden. Das wieder öffnen einer Buchungsperiode hebt jedoch nicht die Festschreibung der Buchungen in dieser Periode auf. <br>
Um eine Übersicht über die schon geschlossene und geöffnete Buchungsperioden zu haben,  klicken Sie auf die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439975955612.png" alt="" title=""> - <em>Historie zum öffnen und schließen von Buchungsperioden</em>.</p>

<p>Der Reiter <em>Buchungen exportieren</em> dient der Übergabe von Buchungssätze an das Buchhaltungssystem des Fonds bzw. eines Steuerberaters. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden nur Buchungen angezeigt, die bereits festgeschrieben sind. Dadurch ist sichergestellt, dass keine Buchungssätze die sich noch nicht im Buchungsjournal befinden, an externe Buchhaltungssysteme übergeben werden können. </p>

<p><img src="http://xpecto.github.io/docs/img/img_1461685921010.png" alt="" title=""></p>

<p>Nach dem Aufruf des Dialogs ist der Radiobutton in der Feldgruppe <em>nicht exportiert</em> aktiv. Dadurch werden nur Buchungssätze exportiert, die vorher noch nicht exportiert wurden. Soll ein bereits erfolgter Buchungsexport wiederholt werden so muss der Filter <em>Exportiert</em> dementsprechend angepasst werden.  <br>
Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439892039334.png" alt="" title=""> wird eine Datei im CSV-Format erzeugt, die die aufgelisteten Buchungssätze enthält. Dabei wird automatisch der Exportzeitpunkt und der auszuführende Benutzer in die betroffenen Buchungsdatensätze eingetragen. Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1439894313567.png" alt="" title=""> wird dieselbe Export-Datei erzeugt, jedoch ohne Informationen in den Buchungsdatensatz einzutragen.</p>

<p>Die Reihenfolge der Bearbeitungsschritte in der Stapelbuchung ist: 1. Erfassen, 2. Festschreiben, 3. Schließen, 4. Exportieren.</p></div></body>
</html>