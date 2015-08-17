xpectoPro enthält eine vollständige, zertifizierte Buchhaltung. Alle Einzahlungen, Forderungen, Dividenden, Gebühren und Auszahlungen werden innerhalb der Buchhaltung für jeden Anleger geführt. Die Buchung erfolgt mit einem vom Anwender vorgegebenen Kontenrahmen, typischerweise SKR03 oder SKR04.

Da die meisten Buchungen automatisch vom System bei bestimmten Aktionen erzeugt werden, ist die genaue Kenntnis des Kontenrahmens für die tägliche Benutzung meist nicht relevant. In bestimmten Fällen ist es jedoch sinnvoll direkt Buchungen anzulegen oder zu ändern. Für diese manuellen Buchungen und Korrekturen dient der Stapelbuchungsdialog.

Sie erreichen den Stapelbuchungsdialog im Menü "Bearbeiten". Der Dialog ermöglicht die Eingabe, die Änderung und die Suche von Buchungen. Für die Weitergabe der Buchungen und die Revisionssicherheit der Buchhaltung können Sie Buchungen festschreiben und in protokollierter Weise exportieren.

Die Stapelbuchungs-Maske ist das zentrale Werkzeug zur Verwaltung von Buchungsdaten der Fondsbuchhaltung. Sie ist im wesentlichen in vier Funktionsbereiche untergliedert:
 
 - Stapel-Erfassung
 -  Suchen / Ändern
 -  Buchungen festschreiben
 -  Buchungen exportieren
 
Die Stapelbuchungs-Maske kann jeweils für ein bestimmtes Produkt geöffnet werden. Sind in der Datenbank mehrere Produkte angelegt, so wird vor dem Öffnen der Stapelbuchungs-Maske ein Produkt-Auswahl-Dialog angezeigt. Das gewählte Produkt wird in der Titelzeile des Stapelbuchungs-Dialog angezeigt. Solange der Dialog geöffnet ist, können darin nur Buchungsdaten des entsprechenden Produkts / Fonds verwaltet werden.

![](http://xpecto.github.io/docs/img/img_1439547282677.png)

 Jeder Funktionsbereich der Stapelbuchungs-Maske definiert sich durch die Verfügbarkeit spezifischer Filter und Buttons zum Durchführen bestimmter Aktionen. Allen vier Funktionsbereichen gemein ist eine Buchungsliste sowie eine Berarbeitungs-Maske zum Anzeigen bzw. Bearbeiten einer Buchung. Die jeweiligen von Anwender konfigurierten Filter bestimmen, welche Buchungen in der Buchungsliste angezeigt werden. 

Die Feldgruppe *Buchung bearbeiten* zeigt die Detail-Informationen des aktuell in der Buchungsliste selektierten Buchungssatzes. Sie enthält die Felder *Belegdatum, Konto, Gegenkonto, Betrag, Buchungstext, Belegnummer* sowie optional auszufüllenden (und nicht zur Buchhaltung gehörenden) Felder *Valutadatum, Vertrag, Ust-Kennz.* und *Bemerkung.* Die Pflichtfelder sind gelb hinterlegt. 

![](http://xpecto.github.io/docs/img/img_1439798971081.png)

*Valutadatum* bezeichnet das Datum, ab dem Kontobewegungen wirksam werden. Valuta und Wertstellung bedeuten das gleiche, sie unterscheiden sich aber von der Buchung. Das *Valutadatum* ist das Datum, an dem eine Gutschrift oder Belastung wirksam wird. Das Buchungsdatum informiert nur über Kontobewegungen, während die Valuta den echten Kontostand anzeigt. 

Unter *Valutadatum* wird das Datum erfasst, zu dem der Datensatz bei Berechnungen (wie z.B. Gebührenberechnung) berücksichtigt wird. Dieses kann unter Umständen vom Belegdatum abweichen. Unter *Vertrag* kann eine Vertrags-Nr. erfasst werden, der die selektierte Buchungen zugeordnet werden soll. 
Unter *USt-Kennz.* (Umsatzsteuer-Kennzeichen) kann ein Umsatzsteuer-Satz erfasst werden, der bei Berechnungen verwendet werden soll. Dieses Feld enthält nicht die Umsatzsteuer zu der selektierten Buchung. 
Unter Bemerkung können Bearbeiter-Hinweise zu der selektierten Buchungen eingegeben werden.
Unter Betrag ist zum eingegebenen Betrag zusätzlich die Währung auszuwählen. Dabei fließen nur Datensätze mit der beim Produkt hinterlegten Währung in die Buchhaltung ein (siehe *Produkt → Währung*).
Unter bestimmte Voraussetzungen (z.B. *Buchungen exportieren* gewählt oder *Buchungen festschreiben*) ist die Feldgruppe *Buchung bearbeiten* in GoBS-Modus (Grundsätze ordnungsmäßiger DV-gestützter Buchführungssysteme). GOBS-Modus ist ein Read-Only-Modus Änderungsschutz, keine Änderungen möglich.


 
Das sind die Buchungsschlüssel die bei Produkt hinterlegt sind. 
Festschreiben damit nichts mehr geändert wird.
Wenn eine festgeschriebene Buchung gelöscht wird, wird sie einfach nur storniert.
1.Festschreiben 2.Schließen 3. Exportieren.

Stapelbuchungen sind alle Buchungsdaten pro Fond.

Buchungen exportieren von Nebenbuchhaltung zur Hauptbuchhaltung.


Reiter *Stapel-Erfassung* dient der Ersterfassung von Buchungen. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden alle Buchungen angezeigt, die von dem aktuell angemeldeten Benutzer am selben Tag bereits erfasst wurden. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439801023332.png) wird ein neuer Datensatz angelegt. Die Details des Buchungssatzes werden über die Feldgruppe *Buchung bearbeiten* eingegeben und dann 
![](http://xpecto.github.io/docs/img/img_1439801999354.png)

![](http://xpecto.github.io/docs/img/img_1439799333097.png)




![](http://xpecto.github.io/docs/img/img_1439799522434.png)

![](http://xpecto.github.io/docs/img/img_1439799558194.png)

![](http://xpecto.github.io/docs/img/img_1439799593743.png)

