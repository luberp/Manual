In der klassischen Menü-Ansicht wird über *Bearbeiten  → Datensatz löschen*  der aktuell ausgewählte  Datensatz (z.B. Kunde, Vertrag, Vermittler, Person, Veranstaltung, Produkt) gelöscht. 

In der modernen Menü-Ansicht kann ein Datensatz über die Registerkarte *Berichte und Massenaktionen* Gruppe *Bearbeiten* gelöscht werden.

![](http://xpecto.github.io/docs/img/img_1462806622224.png)

Nach Bestätigung der Warnmeldung:

![](http://xpecto.github.io/docs/img/img_1420450924589.png)

“Wollen Sie den Datensatz … wirklich löschen?” mit *Ja* wird der Datensatz aus der Datenbank gelöscht. 
Es können nur die Datensätze gelöscht werden, auf die noch nicht referenziert wurde. Im Speziellen heißt dies, dass z.B. ein Vermittler, der bereits einen Vertrag verkauft hat, ein Kunde, zu dem bereits ein Vertrag erfasst ist, oder ein Vertrag, zu dem bereits Buchungen erfasst sind, nicht gelöscht werden können. Der Zweck dieses Menüpunktes ist die zeitnahe Löschung von Datensätzen.

Eine Löschung von bereits referenzierten Datensätzen wird mit folgender Fehlermeldung unterbunden:

![](http://xpecto.github.io/docs/img/img_1420458029242.png)
 
