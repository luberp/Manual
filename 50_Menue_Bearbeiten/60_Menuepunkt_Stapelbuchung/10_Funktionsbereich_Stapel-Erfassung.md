Die Stapel-Erfassungs-Funktion dient der Ersterfassung von Buchungen. Dieser Funktionsbereich besitzt einen fest vorgegebenen Filter - es werden alle
Buchungen angezeigt, die von dem aktuell angemeldeten Benutzer am selben Tag bereits erfasst wurden. Über den Button _"Neue Buchung"_ wird ein
neuer Datensatz angelegt. Die Details des Buchungssatzes werden über die Bearbeitungs-Maske eingegeben und mit dem Button _Speichern_
gespeichert. Die Gültigkeit des eingegebenen Belegdatums und des Betrags wird direkt beim Verlassen des jeweiligen Feldes geprüft. Vor dem
Speichern wird außerdem geprüft, ob die Pflichtfelder Belegdatum, Konto, Gegenkonto, Betrag und Buchungstext befüllt sind. Weiters
dürfen Konto und Gegenkonto nicht identisch sein, der eingegebene Betrag nicht 0 sein, und das Belegdatum nicht in einer bereits geschlossenen
Buchungsperiode liegen. Beim Speichern der Buchung wird automatisch der Erfasser und der Erfassungszeitpunkt in den Buchungsdatensatz eingetragen. Die
Buchungsperiode, zu der ein Buchungssatz gehört, richtet sich nach dem Belegdatum, sie wird nicht separat erfasst.

Ein hier erfasster Datensatz kann über den Button _"Buchung löschen"_ jederzeit wieder gelöscht werden, solange er noch nicht
festgeschrieben ist.

![](http://xpecto.github.io/docs/img/img081.png)
