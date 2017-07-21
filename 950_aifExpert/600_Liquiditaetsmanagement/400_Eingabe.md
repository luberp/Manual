

Nachdem nun ein neuer Plan angelegt ist und der grundlegende Aufbau festgelegt wurde, kann dieser nun im Unterreiter "Eingabe" betrachtet werden. Der Eingabe-Reiter ist folgendermaßen strukturiert

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet34.png)


 - Im oberen Bereich befinden sich verschiedene Steuerungsfunktionen

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet11.png)


 - Im mittleren Bereich wird der Plan inklusive seiner Posten angezeigt
   - Links wird die Bezeichnung, Zusatzbezeichnung, die Bemerkung (kann per Tooltip komplett gelesen werden) sowie eine Schaltfläche zur Abholung von Werten (siehe Konsolidierung - Referenz) 
   - Rechts davon werden Spalten je Anlass und je Intervall angezeigt
 
> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet35.png)
 
Die Eingabe der kann nun innerhalb der jeweiligen Spalte (Intervall & Anlass) und Zeile (Posten) erfolgen. 
Die Werte müssen numerisch und positiv oder negativ (mit Minus-Vorzeichen) sein. Dezimalzeichen sind mit einem Komma zu trennen, sind entsprechend der Kommastellen-Zahl, welche im Aufbau definiert worden ist, und maximal bis zur 6ten-Nachkommastelle möglich. Zur Übersichtlichkeit erfolgt die Anzeige von Dezimalzeichen nur dann, wenn diese vorhanden sind oder zur Berechnung benutzt werden.

Bei den folgenden Konstellationen ist eine Werteingabe nicht möglich:
  
  - Sollte der Posten im Aufbau als "readonly" im Style-Feld deklariert worden sein, so kann eine Werteingabe nicht erfolgen.
  - Sollten der/die Wert/Werte festgeschrieben sein. Hier muss dann entweder manuell über den Datenpunkt-Dialog oder automatisch über den Excel Export/Import eine Korrekturbuchung angelegt werden.
  - Sollte der Posten mithilfe einer Formel berechnet oder eine Datenquelle besitzen (SQL oder Referenz).
  
#### Eingabe - Steuerungsfunktionen

Folgende Steuerungsfunktionen sind im oberen Bereich:
  - Auswahlliste für Haupt-Anlass
    - Hier kann der Anlass, auf dem dieser Plan basiert, ausgewählt werden. Je nachdem welcher Anlass ausgewählt wird, ändern sich die entsprechenden Spalten und zeigen das Kürzel des Anlasses über dem Datum an. Der standardmäßige Wert des Haupt-Anlasses kann im Reiter Aufbau bestimmt werden. Die auswählbaren Anlässe werden global in einer Nachschlagsliste oder speziell für den Plan im Reiter Aufbau gespeichert.
  - Auswahlliste für Neben-Anlass
     - Hier kann ein zusätzlicher Anlass ausgewählt werden. Eine Auswahl bewirkt, dass der Plan entsprechend zwei Spalten je Zeitraum anzeigt (eine für den Haupt-Anlass, die andere für den Neben-Anlass) und diese gegenüberstellt.
  - Checkbox für Unterposten
      - Die Auswahl der Checkbox blendet Unterposten - Posten, die zu einem Hauptposten gehören - aus oder wieder ein.
  - Auswahl und Bedienung des Zeitraums
      - Zur Auswahl und Bedienung des Zeitraums stehen mehrere Schaltflächen zur Verfügung. Die beiden äußeren Schaltflächen lassen je nach eingestellter Zeitraum-Betrachtung eine Periode zurück (linke Schaltfläche) oder vor (rechte Schaltfläche) springen. 
      - Der Dialog zur Einstellung der Zeitraum-Betrachtung lässt sich entweder durch die Betätigung der Bleistift-Schaltfläche links neben der Ansicht des aktuellen Zeitraums oder durch einen Doppelklick auf das Feld öffnen.
      Hier können wie schon im Intervall unterschiedliche Zeitraum-Betrachtungen ausgewählt werden.
  - Auswahlboxen für Intervall
    - Mithilfe dieser Auswahlboxen lässt sich auswählen, nach welchem Intervall der eingestellte Zeitraum betrachtet werden soll.
    - Es stehen dabei vier verschiedene Auswahlmöglichkeiten zur Verfügung:
       - Jahr
       - Quartal
       - Monat
       - Tag
  - Feld für Intervallanzahl
    - Hier kann bestimmt werden wie viele entsprechende Intervalle in Zukunft der Plan betrachtet werden soll (Beispiel1: Zeitraum "2017" + Intervall "Jahr" + Anzahl 1 > Nur das Jahr 2017 wird angezeigt; Beispiel2: Zeitraum "2017" + Intervall "Monat" + Anzahl 24 > Es werden alle 24 Monate der Jahre 2017 und 2018 angezeigt)

#### Eingabe - Datenpunkt

Jede Zelle stellt einen Datenpunkt dar, der je nach Zeitraum-Betrachtung und Intervall aus einer oder mehreren zugrunde liegenden Buchungssätzen / Werten bestehen kann.

##### Eingabe - Datenpunkt-Ausprägungen

Jeder Datenpunkt kann verschiedene Ausprägungen annehmen, die in Form von Icons rechts neben den Werten angezeigt werden.

| Icon | Beschreibung | 
| ------------- |:-------------| 
| ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet14.png)| Dieser Datenpunkt besteht aus mehreren Buchungssätzen / Werten | 
| ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet15.png)     | Alle Buchungssätze / Werte des Datenpunktes sind festgeschrieben | 
| ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet16.png)      | Nicht alle Buchungssätze / Werte des Datenpunktes sind festgeschrieben |
| ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet17.png)      | Der Datenpunkt wurde manuell überschrieben, obwohl er anhand einer Formel automatisch berechnet wird |
| ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet36.png)      | Es sind Bemerkungen oder Dateien in dem/n Buchungssatz/en hinterlegt worden |

##### Eingabe - Datenpunkt-Dialog

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet13.png)

Sobald der Datenpunkt aus einem oder mehreren Werten besteht, kann per Doppelklick ein zusätzlicher Dialog aufrufen werden. Mithilfe dieses Dialogs lassen sich die einzelnen zugrunde liegenden Werte betrachten:
Zur Auswahl steht im unteren Bereich eine Liste zur Verfügung. Dort sind alle Buchungssätze / Werte hinterlegt die letztendlich diesen Datenpunkt ausmachen. Jeder dieser Buchungssätze / Werte kann im mittleren Bereich geprüft und begutachtet werden. Dabei stehen im rechten Bereich "Verarbeitungsinfos" die genauen Informationen, wer diesen Wert angelegt oder festgeschrieben hat. Zusätzlich können im Bereich "Bemerkung" zu jedem Buchungssatz zusätzliche Informationen hinterlegt werden. 

Im Bereich "Aktionen" steht die Funktion "Festschreibung" zur Verfügung. Bei Betätigung dieser Schaltfläche schreibt aifExpert die zugrunde liegenden Buchungssätze des Datenpunktes fest. Das bedeutet, dass diese nicht mehr verändert und gelöscht werden können.

Im Bereich "Datei" kann eine Datei entweder mithilfe eines Dialoges oder durch die Angabe des Pfades hinterlegt werden. Die Betätigung der rechten Schaltfläche in diesem Bereich öffnet die entsprechende Datei.

Im oberen linken Bereich des Datenpunkt-Dialogs können weitere Buchungssätze angelegt oder bestehende nicht festgeschriebene gelöscht werden. Die Anlage von neuen Buchungssätzen aus diesem Dialog kommt dann in Betracht, sollten alle bestehenden Buchungssätze bereits festgeschrieben sein (Die Eingabe eines anderen Wertes im Plan ist nicht mehr möglich). Dabei übernimmt und schlägt der aifExpert zur Neuanlage der Buchung die Werte der ersten Buchung der Liste vor.

#### Eingabe - Varianten

Jeder Plan kann in unterschiedlichen Varianten / Anlässen gepflegt und mit Werten versehen werden.
Die Auswahl des zu betrachtenden Haupt-Anlasses ist in den Steuerungsfunktionen möglich. Der standardmäßige Haupt-Anlass des Plans wird im Planaufbau gesetzt. 
Um zwei Anlässe vergleichen zu können, kann in den Steuerungsfunktionen ein Neben-Anlass ausgewählt werden. Dabei blendet der aifExpert zusätzliche Spalten für den Neben-Anlass ein. Es wird für jeden einzelnen Zeitraum jeweils eine Spalte je Anlass angezeigt.

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet37.png)

#### Eingabe - Auswertung

Um eine abgegrenzte Auswertung der Anlässe (Anlass1 gilt bis zum Zeitraum x, danach gilt Anlass2) zu ermöglichen steht in den Steuerungsfunktionen nach Auswahl eines Neben-Anlasses eine Checkbox "Auswertung" zur Verfügung. Nach der Betätigung dieser Box erscheint zwischen den Spalten in der Eingabe ein Slider. Dieser kann zwischen die jeweilige Spalte gezogen werden und bewirkt, dass bis zum Slider der Haupt-Anlass und nach dem Slider der Neben-Anlass betrachtet wird. Laufende Summen werden dabei fortlaufend weiter berechnet.

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet38.png)


--------
