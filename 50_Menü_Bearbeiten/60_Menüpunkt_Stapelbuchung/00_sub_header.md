Die Stapelbuchungs-Maske ist das zentrale Werkzeug zur Verwaltung von Buchungsdaten der Fondsbuchhaltung. Sie ist im wesentlichen in vier Funktionsbereiche
untergliedert:

*   Stapel-Erfassung
*   Suchen/Ändern
*   Buchungen festschreiben
*   Buchungen exportieren

Die Stapelbuchungs-Maske kann jeweils nur für ein bestimmtes Produkt geöffnet werden. Sind in der Datenbank mehrere Produkte angelegt, so wird
vor dem Öffnen der Stapelbuchungs-Maske ein Produkt-Auswahl-Dialog angezeigt. Das gewählte Produkt wird in der Titelzeile des
Stapelbuchungs-Dialogs ausgegeben. Solange der Dialog geöffnet ist, können darin nur Buchungsdaten des entsprechenden Produkts / Fonds verwaltet
werden.

Jeder Funktionsbereich der Stapelbuchungs-Maske definiert sich durch die Verfügbarkeit spezifischer Filter und Buttons zum Durchführen bestimmter
Aktionen. Allen vier Funktionsbereichen gemein ist eine Buchungsliste sowie eine Bearbeitungs-Maske zum Anzeigen bzw. Bearbeiten einer Buchung. Die
jeweiligen vom Anwender konfigurierten Filter bestimmten, welche Buchungen in der Buchungsliste angezeigt werden.

Die Bearbeitungs-Maske zeigt die Detail-Informationen des aktuell in der Buchungsliste selektierten Buchungssatzes. Sie enthält die Felder	_Belegdatum_, _Konto_, _Gegenkonto_, _Betrag_, _Buchungstext_, _Belegnummer_, sowie die optional
auszufüllenden (und nicht zur Buchhaltung gehörenden) Felder _Valutadatum_, _Vertrag_, _USt-Kennz._ und _Bemerkung_.
Unter _Valutadatum_ wird das Datum erfasst, zu dem der Datensatz bei Berechnungen (wie z.B. Gebührenberechnung) berücksichtigt wird.
Dieses kann unter Umständen vom Belegdatum abweichen. Unter _Vertrag_ kann eine Vertrags-Nr erfasst werden, der die selektierte Buchung
zugeordnet werden soll. Unter _USt-Kennz._ kann ein USt-Satz erfasst werden, der bei Berechnungen verwendet werden soll. Dieses Feld enthält
nicht die USt zu der selektierten Buchung. Die in der Software geführte Nebenbuchhaltung unterstütz generell keine USt-Behandlung! Unter	_Bemerkung_ können Bearbeiter-Hinweise zu der selektierten Buchung eingegeben werden. Unter _Betrag_ ist zum eingegebenen Betrag
zusätzlich die Währung auszuwählen.
Dabei fließen nur Datensätze mit der beim Produkt unter _Buchh. Währung_ hinterlegten Währung in die Buchhaltung ein,
eventuell vorhandene Datensätze mit anderen Währungen/Einheiten dienen lediglich Berechnungszwecken außerhalb der Buchhaltung.
[[TS2]](C:/src/EAWin/Docu/eAgentur.NET%20Handbuch/Handbuch_Neu_2.htm#_msocom_2)

Unter bestimmten Voraussetzungen (z.B. Funktionsbereich _"Buchungen exportieren"_ gewählt, oder festgeschriebene Buchung selektiert) ist die
Bearbeitungs-Maske im Read-Only-Modus.

![](img/clip_image079.png)
