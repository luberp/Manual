## Eingabe

Nachdem nun ein neuer Plan angelegt ist und der grundlegende Aufbau festgelegt wurde, kann dieser nun im Unterreiter "Eingabe" betrachtet werden. Der Eingabe-Reiter ist folgendermaßen strukturiert
 - Im obereren Bereich befinden sich verschiedene Steuerungsfunktionen
 - Im mittleren Bereich wird der Plan inklusive seiner Posten angezeigt
   - Links wird die Bezeichnung, Zusatzbezeichnung, die Bemerkung (kann per Tooltip komplett gelesen werden) sowie eine Schaltfläche zur Abholung von Werten (siehe Konsolidierung - Referenz) 
   - Rechts davon werden Spalten je Anlass und je Intervall angezeigt
 
Die Eingabe der kann nun innerhalb der jeweiligen Spalte (Intervall & Anlass) und Zeile (Posten) erfolgen. 
Die Werte müssen numerischer positiver oder negativer (mit Minus-Vorzeichen) sein. Dezimalzeichen sind mit einem Komma zu trennen und sind bis zur 10ten-Nachkommastelle möglich. Zur Übersichtlichkeit erfolgt die Anzeige von Dezimalzeichen wird nur dann wenn dieser Posten welche besitzt oder mit welchen rechnet.

In folgenden Konstellationen ist eine Werteingabe nicht möglich:
  - Sollte der Posten im Aufbau als "readonly" im Style-Feld deklariert worden sein, so kann eine Werteingabe nicht erfolgen.
  - Sollten der/die Wert/Werte festgeschrieben worden sein. Hier muss dann entweder über den Datenpunkt-Dialog manuell oder über den Excel Export/Import automatisch eine Korrekturbuchung angelegt werden.
  
### Eingabe - Steuerungsfunktionen

Folgende Steuerungsfunktionen sind im oberen Bereich:
  - Auswahlliste für Haupt-Anlass
    - Hier kann der Anlass, auf dem dieser Plan basiert, ausgewählt werden. Je nachdem welcher Anlass gerade ausgewählt wird, ändern sich die entsprechenden Spalten und zeigen das Kürzel des Anlasses über dem Datum an. Der standardmäßige Wert des Haupt-Anlasses kann im Aufbau-Reiter bestimmt werden. Die auswählbaren Anlässe werden global in einer Nachschlageliste oder speziell für den Plan im Aufbau-Reiter gespeichert.
  - Auswahlliste für Neben-Anlass
     - Hier kann ein zusätzlicher Anlass ausgewählt werden. Eine Auswahl bewirkt, dass der Plan entsprechend zwei Spalten je Zeitraum anzeigt (Eine Haupt-Anlass, die andere der Neben-Anlass) und diese gegenüberstellt.
  - Checkbox für Unterposten
      - Die Auswahl der Checkbox blendet Unterposten, quasi Posten, die zu einem Hauptposten, gehören aus oder wieder ein.
  - Auswahl und Bedienung des Zeitraums
      - Zur Auswahl und Bedienung des Zeitraums stehen mehrere Schaltflächen zur Verfügung. Die beiden äußeren Schalftlächen lassen je nach eingestellter Zeitraumsbetrachtung eine Periode zurück (linke Schaltfläche) oder vor (rechte Schaltfläche) springen. 
      - Der Dialog zur Einstellung der Zeitraumsbetrachtung lässt sich entweder durch die Betätigung der Bleistift-Schaltfläche links neben der Ansicht des aktuellen Zeitraums oder durch einen Doppelklick auf dieses Feld öffnen.
      Hier können wie schon im Intervall unterschiedliche Zeitraumsbetrachtungen ausgewählt werden.
  - Auswahlboxen für Intervall
    - Mithilfe dieser Auswahlboxen lässt sich auswählen nach welchem Intervall der eingestellte Zeitraum betrachtet werden soll.
    - Es stehen dabei vier verschiedene Auswahlmöglichkeiten zur Verfügung:
       - Jahr
       - Quartal
       - Monat
       - Tag
  - Feld für Intervallanzahl
    - Hier kann bestimmt werden wie viele entsprechende Intervalle in Zukunft der Plan betrachtet werden soll (Beispiel1: Zeitraum "2017" + Intervall "Jahr" + Anzahl 1 > Nur das Jahr 2017 wird angezeigt; Beispiel2: Zeitraum "2017" + Intervall "Monat" + Anzahl 24 > Es werden alle 24 Monate der Jahre 2017 und 2018 angezeigt)

### Eingabe - Datenpunkt

Jede Zelle stellt einen Datenpunkt dar, der je nach Zeitraumbetrachtung und Intervall aus einer oder mehreren zugrunde liegenden Buchungssätzen / Werten bestehen kann.

#### Eingabe - Datenpunkt-Ausprägungen

Jeder Datenpunkt kann verschiedene Ausprägungen annehmen, die in Form von Icons rechts neben den Werten angezeigt werden.

| Icon | Beschreibung | 
| ------------- |:-------------| 
| Liste      | Dieser Datenpunkt besteht aus mehreren Buchungssätzen / Werten | 
| Lock      | Alle Buchungssätze / Werte des Datenpunktes sind festgeschrieben | 
| PartialLock      | Nicht alle Buchungssätze / Werte des Datenpunktes sind festgeschrieben |
| Calc      | Der Datenpunkt wurde manuell überschrieben, obwohl er anhand einer Formel automatisch berechnet wird |
| UpCorner      | Es sind Bemerkungen in dem/n Buchungssatz/en vorhanden |
| DownCorner      | Es sind Dateien in dem/n Buchungssatz/en hinterlegt worden |

#### Eingabe - Datenpunkt-Dialog

Sobald der Datenpunkt aus Werten besteht, kann per Doppelklick einen zusätzlicher Dialog aufrufen werden. Mithilfe dieses Dialogs lassen sich die einzelnen zugrunde liegenden Werte betrachten:
Zur Auswahl steht im oberen Bereich eine Auswahlliste zur Verfügung. Dort sind alle Buchungssätze / Werte hinterlegt die letztendlich diesen Datenpunkt ausmachen. Jeder dieser Buchungssätze / Werte kann im mittleren Bereich gegen geprüft und begutachtet werden. Dabei steht im linken Bereich "Verarbeitungsinfos" die genauen Informationen wer diesen Wert angelegt oder festgeschrieben hat. Zusätzlich können im Bereich "Bemerkung" zu jedem Buchungssatz zusätzliche Informationen hinterlegt werden. Im Bereich "Aktionen" stehen zwei Funktionen zur Verfügung:
- Buchungen festschreiben
   - Bei Betätigung dieser Schaltfläche schreibt aifExpert die zugrunde liegenden Buchungssätze des Datenpunktes fest. Bedeutet, dass diese nicht mehr verändert und gelöscht werden können.
- Datei hinterlegen
  - Mithilfe dieser Schaltfläche kann je Buchungssatz eine Datei hinterlegt werden.

Im oberen rechten Bereich des Datenpunkt-Dialogs können weitere Buchungssätze angelegt oder bestehende nicht festgeschriebene gelöscht werden. Die Anlage von neuen Buchungssätzen aus diesem Dialog kommt dann in Betracht, sollte alle bestehenden Buchungssätze bereits festgeschrieben worden sein (Die Eingabe eines anderen Wertes im Plan ist nicht mehr möglich). 

--------