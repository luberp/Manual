In der klassischen Menü-Ansicht über das Menü *Berechnungen → Probeberechnungen* sind verschiedene Testberechnungen zu den  Berechnungsmodulen aufrufbar. 

In der modernen Menü-Ansicht ist die Funktion *Provisionsberechnung* unter Registerkarte *Vertrieb* Gruppe *Provisionen* zu sehen.

![](http://xpecto.github.io/docs/img/img_1461832876332.png)

Bei den Testberechnungen werden dieselben Berechnungen durchgeführt, wie bei den realen Berechnungsläufen, jedoch werden nur die Log-Ausgaben der Berechnungsskripte angezeigt, aber keine Datensätze in der Datenbank erzeugt. Der Aufruf einer beliebigen Testberechnung durch den Anwender ist daher unschädlich.
Diese dienen der Fehlersuche auch durch die Endanwender um den Fehler selbständig zu finden die nur an falsch eingestellten Werten liegen.


### Provisionstest

Über den Dialog *Provisionstest* können Sie, für einen bestimmten Zeitraum, die Provisionen des Vertrages berechnen. 
Wählen Sie dazu einen Abrechnungszeitraum und klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440592833421.png).

Es wird für diesen Vertrag die Abschlussprovision- und Bestandsprovision-Ansprüche, berechnet.

![](http://xpecto.github.io/docs/img/img_1440592795229.png)

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440593037818.png) bekommen Sie eine Liste der Provisionsansprüche der einzelnen Vermittler angezeigt.
Diese Liste wird durch das hinterlegte Provisionsabrechnungsskript beeinflusst (das Skript wird durch xpecto Kundensupport angelegt/angepasst).

![](http://xpecto.github.io/docs/img/img_1440593007992.png)

### Sollstellungstest

Über den Dialog *Sollstellungstest* können Sie testen ob für den ausgewählten Vertrag, für die stichtagbezogene  Buchung (Sollstellung), alle Kriterien erfüllt sind. Wählen Sie dazu einen Stichtag und klicken Sie auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1440595722119.png).

![](http://xpecto.github.io/docs/img/img_1440595181744.png)

Hier werden die Sollbuchungen angezeigt und falls ein Sollstellungsskript im Produkt hinterlegt ist dann wird das Skript für die Generierung der Buchungen verwendet z. B. dessen Ausgaben werden oben angezeigt.
