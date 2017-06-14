In der klassischen Menüansicht wird über *Bearbeiten  → Datensatz löschen*  der aktuell ausgewählte  Datensatz (zum Bespiel Kunde, Vertrag, Vermittler, Person, Veranstaltung, Produkt) gelöscht. 

In der modernen Menüansicht kann ein Datensatz über die Registerkarte *Berichte und Massenaktionen*, Gruppe *Bearbeiten* gelöscht werden.

![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Datensatz_loeschen/Menue_loeschen.png)

Es erscheint folgende Warnmeldung:

![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Datensatz_loeschen/Datensatz_loeschen.png)

*![](http://xpecto.github.io/docs/xpecto/Grafiken/gr_gluehbirne.jpg) In diesem Beispiel handelt es sich um einen Datensatz aus der Kategorie "Verträge", sie erkennen dieses am Kürzel "V" im Datensatz Namen.*
     

Bestätigen Sie den Dialog “Wollen Sie den Datensatz … wirklich löschen?” mit *Ja* wird der Datensatz aus der Datenbank gelöscht. Es erfolgt keine weitere Rückmeldung vom System.


Der Versuch einer Löschung von bereits referenzierten Datensätzen wird mit folgender Meldung quittiert:

![](http://xpecto.github.io/docs/xpecto/Bearbeiten/Datensatz_loeschen/Datensatz_kann_nicht_geloescht_werden.png)
 
![](http://xpecto.github.io/docs/xpecto/Grafiken/gr_gluehbirne.jpg)Es können nur Datensätze gelöscht werden, auf die noch nicht referenziert wurde. Im Speziellen heißt das, dass zum Bespiel ein Vermittler, der bereits einen Vertrag vermittelt hat, ein Kunde, zu dem bereits ein Vertrag erfasst wurde oder ein Vertrag, zu dem bereits Buchungen erfasst worden sind, nicht gelöscht werden können. 