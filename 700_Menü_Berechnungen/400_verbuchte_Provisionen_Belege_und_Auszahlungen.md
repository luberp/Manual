Über diesen Menüpunkt wird der aktuell ausgewählte Kunde, Vertrag oder Vermittler gelöscht. Nach Bestätigung der Warnmeldung
"Wollen Sie den Datensatz ....wirklich löschen?" mit _Ja_ wird der Datensatz aus der Datenbank gelöscht. Es können nur neu
erfasste Datensätze, bzw. Datensätze, auf die noch nicht von anderen Datensätzen verwiesen wird, gelöscht werden. Im speziellen
heißt dies z.B., dass ein Vermittler, der bereits einen Vertrag verkauft hat, ein Kunde, zu dem bereits ein Vertrag erfasst ist, oder ein Vertrag, zu
dem bereits Buchungen erfasst sind, nicht gelöscht werden kann. Der Zweck dieses Menüpunkts ist lediglich die zeitnahe Löschung von
Falscherfassungen.

Aus Gründen der Historisierung und Nachvollziehbarkeit werden Datensätze, die bereits mit anderen Datensätzen verknüpft sind, nicht aus
der Datenbank gelöscht, sondern nur durch einen entsprechenden Status (wie z.B. Storno oder ausgeschieden) gekennzeichnet.
Zahlfirmen sind die Firmen die Provisionen zahlen an Vertriebspartner. 
Vetriebspartner können Provisionen von meherere Firmen bekommen deswegen hier die zwei Reiter.
![](http://xpecto.github.io/docs/img/img_1423816637524.png)

DTAUS/SEPA erstellen.
Viele Produkte haben einen monatlichen Zahlplan. Diese Zahlungen sind oft per Lastschrift vom Konto des Kunde einzuziehen. Für den Einzug der Lastschrift gibt es unterschiedliche Standards. 
In Deutschland gibt es das bisherige Verfahren von Einzugsermächtigung und Abbuchungsauftrag, meist in Verbindung mit dem Dateiformat DTA oder DTAUS. In Östereich findet sich das Format EDIFACT DirDeb, auf europäische Ebenen (incl. Schweiz und andere) hat man sich für den neunen Standard SEPA entscheiden.

Egal welche Dateien ihre Bank benötigt, unsere Software kannn aus den automatisch berechneten Zahlplänen die gewünschten Dateien erstellen. 
Die Erstellung der Dateien ist sehr einfach. Wir haben einen zentralen Dialog für alle zu verwaltenden Produkte. Der Dialog berechnet alle nötigen Dateien und bietet dann automatisch die einzelnen Dateien zur Erstellung an. Folgende Unterscheidung sind möglich:
Datei je Produkt oder je Gesellschaft
Datei je Bankkonto (z.B. Deutschland/Österreich)
Datei nach Zahlungsart (z.B. Sonderzahlung/Rate)
Datei je nach Art der Zahlung (z.B. Abbuchung/Einzug/SEPA)

Für jede Datei wird ein übersichtlicher Begleitzettel erstellt. Die Dateien werden in einem Ordnersystem abgelegt und sind in sogenannten Transaktionen organisiert. Somit ist immer klar welsche Buchungen in welcher Datei enthalten sind und welche noch in eine Datei verpackt werden müssen.
Bei der Berechnung der fälligen Raten ist unser System ebenfalls sehr genau. Wir ziehen die Raten immer bis zur vollständiger Begleichung des Forderungskontos ein. Damit können anfallende Gebühren zu Lasten des Kunden automatisch  dem Kunden berechnet werden. Die Schlußrate ist dabei in der Regel "krumm", ist also keine vollständige Rate.

Raten können sich aus unterschiedlichen Beträgen zusammensetzen, inkludiertes Agio wird auch so behandelt.

Die einzelne Sollbuchungen des Zahlplans werden in jedem Vertrag dargestellt und können dort bei Bedarf verändert werden. Aussetzer, Nachholer oder der Einzug einer Startzahlung stellen kein Problem dar.

Provisionen löschen.
Belege löschen.
Abrechnungen drücken.