xpectoPro enthält eine vollständige und zertifizierte Buchhaltung. Alle Einzahlungen, Forderungen, Dividenden, Gebühren und Auszahlungen werden innerhalb der Buchhaltung für jeden Anleger geführt. Die Buchung erfolgt mit einem vom Anwender vorgegebenen Kontenrahmen, typischerweise SKR03 oder SKR04.
Da die meisten Buchungen automatisch vom System bei bestimmten Aktionen erzeugt werden, ist die genaue Kenntnis des Kontenrahmens für die tägliche Benutzung meist nicht relevant. 

Die *Stapelbuchung*-Maske ermöglicht die manuelle Eingabe, die Änderung und die Suche von Buchungen. Für die Weitergabe der Buchungen und die Revisionssicherheit der Buchhaltung können Sie Buchungen festschreiben und in protokollierter Weise exportieren.

In der klassischen Menü-Ansicht gelangen Sie in die *Stapelbuchung* durch klicken  in Menü *Bearbeiten → Stapelbuchung*.

In der modernen Menü-Ansicht finden Sie die *Stapelbuchung* in der Registerkarte *Buchhaltung* Gruppe *Buchungsdaten.*

![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Stapelbuchungen/Menue.png) 

Die *Stapelbuchung* kann jeweils für ein bestimmtes Produkt samt seinen Buchungen, geöffnet werden. Sind in der Datenbank mehrere Produkte angelegt, so wird vor dem Öffnen der *Stapelbuchung*-Maske ein Produkt-Auswahl-Dialog angezeigt.  Bitte wählen Sie hier das entsprechende Produkt aus.

![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Stapelbuchungen/Produkt_auswaehlen.png)

Die *Stapelbuchung* ist das zentrale Werkzeug zur Verwaltung von Buchungsdaten der Fondsbuchhaltung. Sie ist im wesentlichen in vier Funktionsbereiche untergliedert:
 
 -   ![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Stapelbuchungen/Stapel_erfassung.png) -> *einzelne oder selektive Buchungen erfassen*
 -  ![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Stapelbuchungen/Suchen_aendern.png) -> *vorhandene Buchungen bearbeiten*
 -  ![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Stapelbuchungen/Buchungen_festschreiben.png) -> *Buchungsselektionen oder einzelne Buchungen festschreiben*
 -  ![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Stapelbuchungen/Buchungen_exportieren.png) -> *Export der festgeschriebenen Buchungen*

Jeder Funktionsbereich der *Stapelbuchung* definiert sich durch die Verfügbarkeit spezifischer Filter und Buttons zum durchführen bestimmter Aktionen. Allen vier Funktionsbereichen gemein ist ein Bearbeitungsbereich mit den Feldgruppen: *Buchung bearbeiten, Fremdwährung* und *Verarbeitungsinfos* - zum Anzeigen bzw. Bearbeiten einer Buchung, und eine Buchungsliste. Die jeweiligen von Anwender konfigurierten Filter bestimmen welche Buchungen in der Buchungsliste angezeigt werden. 
 
![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Stapelbuchungen/Selektionsfilter_Buchung_bearbeiten.png)

Die Feldgruppe *Buchung bearbeiten* zeigt die Detail-Informationen des aktuell in der Buchungsliste selektierten Buchungssatzes. Sie enthält die Felder *Belegdatum, Konto, Gegenkonto, Betrag, Buchungstext, Belegnummer* sowie optional auszufüllenden (und nicht zur Buchhaltung gehörenden) Felder *Valutadatum, Vertrag, Ust-Kennz.* und *Bemerkung.* Die Pflichtfelder sind gelb hinterlegt.

 ![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Stapelbuchungen/Buchung_bearbeiten.png)

Das *Belegdatum* informiert über Kontobewegungen, während das *Valutadatum* das Datum ist, an dem eine Gutschrift oder Belastung wirksam wird. Das *Valutadatum* zeigt den echten Kontostand an. Dieses kann unter Umständen vom *Belegdatum* abweichen. 
Unter *Vertrag* kann eine Vertrags-Nr. erfasst werden, der die selektierte Buchungen zugeordnet werden soll. 
Unter *USt-Kennz.* (Umsatzsteuer-Kennzeichen) kann ein Umsatzsteuer-Satz erfasst werden, der bei Berechnungen verwendet werden soll.  
Unter *Betrag* ist zum eingegebenen Betrag zusätzlich die Währung auszuwählen. Dabei fließen nur Datensätze mit der beim Produkt hinterlegten Währung in die Buchhaltung ein (siehe Handbuch *Produkt → Währung*).
Unter *Bemerkung* können Bearbeiter-Hinweise zu der selektierten Buchungen eingegeben werden.
Unter bestimmten Voraussetzungen (z.B. *Buchungen exportieren* gewählt oder *Buchungen festschreiben*) ist die Feldgruppe *Buchung bearbeiten* in GoBS-Modus (Grundsätze ordnungsmäßiger DV-gestützter Buchführungssysteme). GoBS-Modus ist ein Read-Only-Modus Darstellung, Sie können diese Buchungen nicht ändern.

Der Reiter *Stapel-Erfassung* dient der Ersterfassung von Buchungen. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden alle Buchungen angezeigt, die von dem aktuell angemeldeten Benutzer am selben Tag bereits erfasst wurden. 

![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Stapelbuchungen/Stapel_erfassung_Menue.png)

Klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439974064694.png) um Vorlagen für Ihre Buchungssätze anzulegen oder zu bearbeiten.
Beim Erfassen von Buchungen über Vorlagen sind bereits  Buchungstext, Konto sowie Gegenkonto fest definiert, Fehlbuchungen werden damit schon im Vorfeld unterbunden.
Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439801023332.png) wird ein neuer Datensatz angelegt. Die Details des Buchungssatzes werden über die Feldgruppe *Buchung bearbeiten* eingegeben.
Die Gültigkeit des eingegebenen Belegdatums und des Betrags wird direkt beim Verlassen des jeweiligen Feldes geprüft. Vor dem Speichern wird außerdem geprüft, ob die Pflichtfelder *Betrag, Belegdatum, Konto, Gegenkonto* und *Buchungstext* befüllt sind. 

![](http://xpecto.github.io/docs/img/img_1439812810573.png)

 Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439804594653.png) wird die Buchung gespeichert. Beim Speichern der Buchung wird automatisch der Erfasser und der Erfassungszeitpunkt in den Buchungsdatensatz eingetragen. Die Buchungsperiode, zu der ein Buchungssatz gehört, richtet sich nach dem Belegdatum, sie wird nicht separat erfasst. Ein hier erfasster Datensatz kann über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439813538430.png) jederzeit wieder gelöscht werden, solange er noch nicht festgeschrieben ist. Festschreiben bedeutet dass eine Buchung dann nur noch durch eine Storno/Korrekturbuchung korrigiert werden kann. Damit werden nachträgliche Manipulationen erschwert.
 
Reiter *Suchen / Ändern* dient der Recherche und ermöglicht das Suchen und Ändern von Buchungen. Die Suchkriterien zum Auffinden der gewünschten Buchungssätze können über verschiedenen Filter wie  *Buchungsperiode, Beteiligung/Vertrag, Erfassung, Kontierung, Festschreibung* konfiguriert werden.

![](http://xpecto.github.io/docs/img/img_1461685262474.png)

Nicht festgeschriebene Buchungen können gelöscht oder geändert werden. Änderungen werden erst durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439804594653.png) gespeichert. Vor dem Speichern werden dieselben Gültigkeitsprüfungen durchlaufen, wie in dem Reiter *Stapel-Erfassung*. 

Bereits festgeschriebene Buchungen (erkennbar durch eingetragene Buchungs-Nr in der Feldgruppe *Verarbeitungsinfos*) können nachträglich nicht mehr verändert werden. Wird eine festgeschriebene Buchung selektiert, so ist der Bearbeitungsbereich in Read-Only-Modus und die Schaltfläche  ![](http://xpecto.github.io/docs/img/img_1439813538430.png) ist deaktiviert. Solange die betroffene Buchungsperiode nicht geschlossen ist, kann jedoch über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439816158639.png) eine Storno-Buchung erzeugt werden. Wird die Abfrage "Möchten Sie eine Korrekturbuchung anlegen?" mit *Ja* beantwortet, so wird eine änderbare (da nicht festgeschriebene) Kopie der Original-Buchung in derselben Buchungsperiode angelegt.

Der Reiter *Buchungen festschreiben* dient der Übertragung von Buchungssätze in das Buchungsjournal. 
Im Buchungsjournal werden alle Buchungen eines gewählten Zeitraums tabellarisch aufgelistet. Die Kriterien zur Auswahl der festzuschreibenden Datensätze können über verschiedene Filter konfiguriert werden, wie *Buchungsperiode, Beteiligung/Vertrag, Erfassung, Kontierung*. 

![](http://xpecto.github.io/docs/img/img_1461685459829.png)

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439820973695.png) werden alle aufgelisteten Erfassungen in das Buchungsjournal übertragen und in jeden betroffenen Buchungssatz der Festschreibungs-Zeitpunkt, der ausführende Benutzer und eine fortlaufenden Buchungsnummer eingetragen werden. Die Festschreibung einer einmal in das Journal übertragenen Buchung kann nachträglich nicht mehr aufgehoben werden. Die Buchung kann dann nur noch über *Suchen / Ändern* ![](http://xpecto.github.io/docs/img/img_1439816158639.png) storniert werden.

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1463479213984.png) wird eine Buchungsperiode geschlossen. Eine Buchungsperiode entspricht einem Kalendermonat. In einer bereits geschlossenen Buchungsperiode kann nicht mehr gebucht werden. Um das Buchen in einer geschlossenen Buchungsperiode zu ermöglichen, muss die Periode über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1463479270448.png) wieder geöffnet werden. Das wieder öffnen einer Buchungsperiode hebt jedoch nicht die Festschreibung der Buchungen in dieser Periode auf.
Um eine Übersicht über die schon geschlossene und geöffnete Buchungsperioden zu haben,  klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439975955612.png) - *Historie zum öffnen und schließen von Buchungsperioden*.

Der Reiter *Buchungen exportieren* dient der Übergabe von Buchungssätze an das Buchhaltungssystem des Fonds bzw. eines Steuerberaters. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden nur Buchungen angezeigt, die bereits festgeschrieben sind. Dadurch ist sichergestellt, dass keine Buchungssätze die sich noch nicht im Buchungsjournal befinden, an externe Buchhaltungssysteme übergeben werden können. 

![](http://xpecto.github.io/docs/img/img_1461685921010.png)

Nach dem Aufruf der Maske *Stapelbuchung* ist der Radiobutton in der Feldgruppe *nicht exportiert* aktiv. Dadurch werden nur Buchungssätze exportiert, die vorher noch nicht exportiert wurden. Soll ein bereits erfolgter Buchungsexport wiederholt werden so muss der Filter *Exportiert* dementsprechend angepasst werden. 
Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439892039334.png) wird eine Datei im CSV-Format erzeugt, die die aufgelisteten Buchungssätze enthält. Dabei wird automatisch der Exportzeitpunkt und der auszuführende Benutzer in die betroffenen Buchungsdatensätze eingetragen. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1439894313567.png) wird dieselbe Export-Datei erzeugt, jedoch ohne Informationen in den Buchungsdatensatz einzutragen.

Die Reihenfolge der Bearbeitungsschritte in der Stapelbuchung ist: 1. Erfassen, 2. Festschreiben, 3. Schließen, 4. Exportieren.
