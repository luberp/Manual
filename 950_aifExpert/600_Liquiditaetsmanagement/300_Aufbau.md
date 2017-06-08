## Aufbau

Nachdem ein neuer Plan angelegt worden ist muss der Aufbau des Plan erstellt und definiert werden. Dazu muss im mittleren Bereich der Unterreiter "Aufbau" aufgerufen werden. Die Oberfläche für den Aufbau des Plans ist folgendermaßen strukturiert:
- Im oberen Bereich finden sich Angaben und Informationen vom Plan selbst
- Im mittleren Bereich können einzelne Posten angelegt, gelöscht und mit den entsprechenden Informationen versehen werden
- Im unteren Bereich erfolgt die Auflistung aller bisher hinterlegten Posten. Die Auflistung stellt gleichzeitig die Auswahlmöglichkeit der jeweiligen Posten dar. D.h. zur Bearbeitung eines entsprechenden Posten muss dieser in der Auflistung ausgewählt werden und kann anschließend im mittleren Bereich mit den entsprechenden Daten angepasst werden.

### Aufbau - Plan

#### Aufbau - Plan - Allgemein

Im Bereich "Allgemein" kann der Name sowie das Produkt des Plans angepasst werden.

#### Aufbau - Plan - zusätzliche Anlässe

Im Bereich "zusätzliche Anlässe" können spezifische Varianten / Anlässe des Plans hinterlegt werden (siehe ). Im Vergleich zu den globalen Anlässen, die für alle Pläne gelten, gelten diese nur für den jeweiligen Plan.

#### Aufbau - Plan - Vorgaben

Im Bereich "Vorgaben" können Standardparameter bestimmt werden, die bei der Auswahl im Unterreiter "Eingabe" gelten
  - Anlass
    - Hier wird ein globaler Anlass ausgewählt, der standardmäßig im Eingabe-Reiter diesen Plan mit dem entsprechenden Anlass öffnet
  - Intervall
    - Hier wird das Intervall ausgewählt, welches standardmäßig im Eingabe-Reiter in diesem Plan hinterlegt ist (z.B. Monatlich - Anzeige des Plans auf Monats-Basis)
    - Folgene Auswahlmöglichkeiten sind möglich
      - Täglich
      - Wöchentlich
      - 2-Wöchentlich
      - 4-Wöchentlich
      - Halbmonatlich
      - Monatlich
      - Vierteljährlich
      - Halbjährlich
      - Jährlich
  - Anzahl
    - Hier wird die Anzahl der Intervalle hinterlegt, die standardmäßig im Eingabe-Reiter im diesem Plan angezeigt werden (z.B. Intervall Monatlich > Anzahl 8 > Anzeige im Eingabe-Reiter von 8 Monaten)
    

### Aufbau - Posten

Die Anlage und Löschung von einzelnen Posten erfolgt mithilfe der zwei Schaltflächen links neben dem Bereich "Allgemein". Das Icon "+" legt einen neuen Posten an. Das Icon "x" löscht den in der unteren Liste ausgewählten Posten.

#### Aufbau - Posten - Allgemein

Im Bereich "Allgemein" können allgemeine Informationen zum Posten hinterlegt werden.
 - Bezeichnung
   - Hier muss zwingend eine Bezeichnung des Postens erfolgen
- Zusatzbez. 
  - Hier kann eine zusätzliche (z.B. ausländische) Bezeichnung hinterlegt werden.
- Typ
  - Hier kann der Typ des Postens ausgewählt werden. Diese Auswahl stellt eine Verknüpfung zum Meldewesen im Bereich der Bundesbankmeldung dar. Die Auswahllliste orientiert sich dabei an den Vorgaben der Bundesbank. 
  - Hintergrund: Im Meldewesen stellen im Bereich der Bundesbankmeldung die einzelnen Formularfelder auch Posten dar. Diese Posten können im Liquiditätsmanagement gepflegt und mit Werten versehen, die dann wiederrum im Meldewesen für die Bundesbankmeldung verwendet werden können
 - Owner
   - Der Owner (Besitzer) beschreibt das Produkt welchem dieser Posten zuzuordnen ist. Standardmäßig wird das selbe Produkt verwendt welches auch dem Plan zugrunde liegt. Um die Komplexität für die Benutzer bei der Einführung gering und die Bedienung nachvollziehbar zu halten ist die Auswahl eines anderen Produktes  beim Auslieferungszustand deaktiviert. Diese kann jedoch nachträglich aktiviert werden.
   - Hintergrund: Neben der Referenz auf bereits bestehende Posten in anderen Plänen stellt diese Funktion eine zusätzliche Möglichkeit zur Konsolidierung dar. Mithilfe dieser können Posten in jeweils unterschiedlichen Plänen vorkommen, benutzen aber alle dieselben Werte (z.B. Plan KVG und Plan Fonds1 besitzen beiden den gleichen Posten mit dem Owner "Fonds1" > In beiden Plänen werden können nun die Werte des Posten angezeigt und ggf. bearbeitet werden)

#### Aufbau - Posten - verknüpftes Asset

Im Bereich "verknüpftes Asset" kann eine Verknüpfung zum Portfoliomanagement hergestellt werden.
  - Asset
    - Hier erfolgt die Auflistung aller vorhandenen Assets aus dem Portfoliomanagement.
    - Nach der Auswahl eines Assets erfolgt eine Verknüpfung des Postens mit dem Asset.

#### Aufbau - Posten - Parameter

Im Bereich "Parameter" erfolgt die Definition des einzelnen Postens mit den entsprechenden Daten.
  - Hauptposten
    - aifExpert erlaubt die Hinterlegung einer Hierarchie von Posten, d.h. ein Posten ist Unterposten eines anderen (z.B. der Posten "Erträge als KVAG" gehört zum Hauptposten "Gesamterträge (Periode)". Um diese Hierarchie anzulegen muss in diesem Feld ausgewählt werden, zu welchem Hauptposten dieser jeweilige Posten gehört. 
  - Ist-Konto
    - Das Liquiditätsmanagement des aifExpert basiert auf dem GOBD-zertifizierten Buchhaltungskern. Das bedeutet: Die Werte die im Liquiditätsmanagement abgespeichert werden, stellen Buchungssätze dar. Um diese ordnungsgemäß in Datenbank speichern zu können ist die Angabe eines Ist-Kontos erforderlich. Bei fehlender Angabe des Ist-Kontos werden die Werte nicht in der Datenbank gespeichert. Bei der Hinterlegung einer Formel werden auch bei fehlendem Ist-Konto die Werte berechnet, jedoch nicht gespeichert. Diese Konstellation ermöglicht die Darstellung und Berechnung von Zwischen- oder Informativwerten.
  - Einheit
    - Das Feld "Einheit" ist ein zwingend zu hinterlegendes Feld. 
  - Style
    - Hier können verschiedene Einträge, zum Design und Verhalten des Postens, mitgegeben werden. 
    - Folgende Einträge können hinterlegt werden:

| Eintrag | Funktion | 
| ------------- |:-------------| 
| readonly      | Schreibschutz, nur lesender Zugriff | 
| fontbold      | Schrift fett | 
| fontgreen     | Schrift grün | 
| fontred       | Schrift rot | 
| fontyellow    | Schrift gelb | 
| fontblue      | Schrift blau | 
| font12        | Schrift Größe 12 | 
| font10        | Schrift Größe 10 | 
| backgreen     | Hintergrund grün | 
| backred       | Hintergrund rot | 
| backyellow    | Hintergrund gelb | 
| backblue      | Hintergrund blau | 
| backgrey      | Hintergrund grau | 
| backdarkgrey  | Hintergrund dunkelgrau | 

  - Sortierung
    - In diesem Feld kann ein Zahl oder Text hinterlegt werden, welcher die entsprechende Reihenfolge im Eingabe- und Auswertungs-Reiter der Posten darstellt.
  - Bemerkung
    - Im Feld "Bemerkung" können zusätzliche Informationen zu diesem Posten gespeichert werden. Diese werden im Eingabe- und Auswertungs-Reiter in der Spalte "Bemerkung" angezeigt.
  
#### Aufbau - Posten - Datenherkunft-Werte

Im Bereich "Datenherkunft - Werte" erfolgt die Bestimmung der Herkunft der Werte. Dies können entweder Formeln, Abfragen oder Funktionen, wie  sein.
  - Datenquelle
    - Im Feld "Datenquelle" muss die zukünftige Quelle der Werte ausgewählt werden. Folgende Auswahlmöglichkeiten sind standardmäßig hinterlegt:
      - Formel
      - Referenz
      - SQL
  - Datenparameter
    - Im Feld "Datenparameter" muss nun die entsprechende Information hinterlegt werden, woher im Fall der Quelle "Referenz" und "SQL" der Wert kommt.
    
| Quelle | Datenparameter | Beschreibung |
| ------------- |:-------------|:--------|
| Referenz | [Produkt, ID] | Bei einer Referenz muss im Datenparameter in eckigen Klammern die Referenz auf den jeweiligen Posten getroffen werden, indem zuerst das Produkt + Komma + ID des Postens angegeben wird (z.B. [KVG, A00000002] > Referenz auf diesen Posten.
| SQL | Select * From * Where * | Bei der Quelle "SQL" muss hier eine SQL-Abfrage hinterlegt werden, die den entsprechenden Wert aus der Datenbank abfragt.

  - Berechnung
    - Im Feld "Berechnung" muss nun die entsprechende Formel hinterlegt werden, aus der sich der Wert zusammensetzt.
    - Die Formelsystematik ist simpel gehalten, ermöglicht die Benutzung aller Grundrechenarten und eine beliebige Komplexität innerhalb dieser.
    
 | Art | Berechnung | Beschreibung |
 | ------------- |:-------------|:--------|
 | Summer Unterposten | = [subsum] | Diese Funktion addiert alle zugehörigen Unterposten dieses Postens auf
 | Addition | = [ID] + [ID] | Die Addition ist durch die Angabe der ID in eckigen Klammern möglich (z.B. [A00000002] + [A00000003] |
 | Subtraktion | = [ID] - [ID] | Die Substraktion ist durch die Angabe der ID in eckigen Klammern möglich |
 | Multiplikation | = [ID] * [ID] | Die Multiplikation ist durch die Angabe der ID in eckigen Klammern möglich |
 | Division | = [ID] / [ID] | Die Division ist durch die Angabe der ID in eckigen Klammern möglich |
 | Fortlaufend | = [ID,-1] | Für eine fortlaufende Werthinterlegung eines Postens muss seine eigene ID + Komma + -1 in eckigen Klammern angegeben werden (z.B. [A00000002, -1]) |
 | Fortlaufend & Berechnung | = [ID,-1] + [ID] | Für eine fortlaufende Berechnung (z.B. zur Berechnung des Cash-Flows) eines Postens muss seine eigene ID + Komma + -1 in eckigen Klammern sowie eine andere Berechnungsart zusätzlich angegeben werden (z.B. [A00000002, -1] + [A00000003]) |
 
--------