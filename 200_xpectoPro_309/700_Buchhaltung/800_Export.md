Dieser Menüpunkt führt direkt zur *Buchungen exportieren*-Maske auf dem Stapelbuchungs-Dialog (siehe Handbuch *Bearbeiten → Stapelbuchung Reiter Buchungen exportieren*).

Diese Funktion kann unter der klassischen Menü-Ansicht *Import/Export → Buchungsexport* gestartet werden.

In der modernen Menü-Ansicht ist die Funktion unter Karteireiter *Buchhaltung* Gruppe *Buchungsdaten* Funktion *Export* zu finden.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Buchungsexport/Export_menue.png)

Der Reiter *Buchungen exportieren* dient der Übergabe von Buchungssätze an das Buchhaltungssystem des Fonds bzw. eines Steuerberaters. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden nur Buchungen angezeigt, die bereits festgeschrieben sind. Dadurch ist sichergestellt, dass keine Buchungssätze die sich noch nicht im Buchungsjournal befinden, an externe Buchhaltungssysteme übergeben werden können. 

Wählen Sie zunächst das Produkt für den der Export durchgeführt werden soll.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Buchungsexport/Produkt_waehlen.png)

Im Anschluss öffnet sich der Export Dialog. Als Standard werden Ihnen nun bereits alle Buchungen angezeigt die bislang noch nicht exportiert wurden.

![](http://xpecto.github.io/docs/xpecto/Import_Export/Buchungsexport/Buchungsexporte_Main.png)


Nach Aufruf des Dialogs ist der Radiobutton in der Feldgruppe Exportiert *nicht exportiert* aktiv. Dadurch werden nur Buchungssätze exportiert, die vorher noch nicht exportiert wurden. Soll ein bereits erfolgter Buchungsexport wiederholt werden so muss der Filter *Exportiert* dementsprechend angepasst werden. 

![](http://xpecto.github.io/docs/xpecto/Import_Export/Buchungsexport/Filter_default.png)


----------


| Schaltfläche      |  Funktion in der Applikation     |  
| ------------- |:-------------| 
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Buchungsexport/Buchungsperiode.png)     | Wenn aktiv kann eine beliebige Buchungsperiode ausgewählt werden|
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Buchungsexport/Exportiert.png)  | Wenn aktiv kann gewählt werden ob bereits exportierte bzw. nicht exportiere Buchungssätze angezeigt werden sollen  |
| ![](http://xpecto.github.io/docs/xpecto/Import_Export/Buchungsexport/Exportoptionen.png)  | *ein Buchungssatz je Zeile* -> Buchungskonto und Gegenkonto werden in der Exportdatei einer Zeile geführt. *Buchungssatz in zwei Zeilen* -> Buchungskonto sowie Gegenkonto werden in der Exportdatei jeweils in einer separaten Zeile geführt. |  


----------


Über die Schaltfläche ![](http://xpecto.github.io/docs/xpecto/Import_Export/Buchungsexport/Button_Export.png) wird eine Datei im CSV-Format erzeugt, die die aufgelisteten Buchungssätze enthält. Dabei wird automatisch der Exportzeitpunkt und der auszuführende Benutzer in die betroffenen Buchungsdatensätze eingetragen. Über die Schaltfläche ![](http://xpecto.github.io/docs/xpecto/Import_Export/Buchungsexport/Button_Testexport.png) wird dieselbe Export-Datei erzeugt, jedoch werden keine Informationen zum Zeitpunkt oder Benutzer gesetzt.