
![](http://xpecto.github.io/docs/img/img_1433857409710.png)

![](http://xpecto.github.io/docs/img/img_1433857700115.png)

Über diesen Menüpunkt wird der aktuell ausgewählte Kunde, Vertrag oder Vermittler gelöscht. Nach Bestätigung der Warnmeldung
"Wollen Sie den Datensatz ....wirklich löschen?" mit _Ja_ wird der Datensatz aus der Datenbank gelöscht. Es können nur neu
erfasste Datensätze, bzw. Datensätze, auf die noch nicht von anderen Datensätzen verwiesen wird, gelöscht werden. Im speziellen
heißt dies z.B., dass ein Vermittler, der bereits einen Vertrag verkauft hat, ein Kunde, zu dem bereits ein Vertrag erfasst ist, oder ein Vertrag, zu
dem bereits Buchungen erfasst sind, nicht gelöscht werden kann. Der Zweck dieses Menüpunkts ist lediglich die zeitnahe Löschung von
Falscherfassungen.

Aus Gründen der Historisierung und Nachvollziehbarkeit werden Datensätze, die bereits mit anderen Datensätzen verknüpft sind, nicht aus
der Datenbank gelöscht, sondern nur durch einen entsprechenden Status (wie z.B. Storno oder ausgeschieden) gekennzeichnet.
