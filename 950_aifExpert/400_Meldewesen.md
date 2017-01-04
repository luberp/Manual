aifExpert setzt auf Standardisierung & Automatisierung und bietet die Möglichkeit die Informationen entsprechend den Vorgaben der deutschen Bundesbank, der BaFin sowie des Bundeszentralamts für Steuern elektronisch per Knopfdruck zu übertragen. 

Die hierfür benötigten Daten werden in speziellen Erfassungsmasken in aifExpert hinterlegt. Schnittstellen zu bestehenden Systemen, wie xpectoPro etc. können implementiert werden. Dadurch reduziert sich der manuelle Erfassungsaufwand erheblich, zusätzlich werden in dem integrierten Änderungsprotokoll- und dem Rechtesystem alle Veränderungen lückenlos dokumentiert.

aifExpert ist ein wichtiger Baustein, um die Erstellung des monatlichen Berichtswesens an die Deutsche Bundesbank, BaFin und das Bundeszentralamt für Steuern, professionell und mit geringstmöglichem Zeitaufwand IT-gestützt zu organisieren.

######Erläuterung
Rechtlich betrachtet ist die KVG nach § 26 Abs.1 ff. KAGB verpflichtet mit Sachkenntnis und im Interesse ihrer Anleger und der Integrität des Marktes zu handeln. Zur besseren staatlichen Kontrolle verabschiedete dazu der Gesetzgeber mit den Paragraphen §§ 34, 35 die Anzeige- und Meldepflichten gegenüber der BaFin und der Bundesbank. Demnach muss die KVG regelmäßig detaillierte Aufstellungen und Angaben zu den Vermögensgegenständen, Märkten und Instrumenten gegenüber den Finanzanstalten anzeigen. Dabei
müssen Informationen zu den wichtigsten Instrumenten, mit denen die KVG handelt, zu den Märkten, in denen die KVG Mitglied ist oder am Handel teilnimmt, sowie den größten Risiken und Konzentrationen jedes von der KVG verwalteten AIF vorgelegt werden.

Neben diesen umfangreichen Meldepflichten verabschiedete der Gesetzgeber das Gesetz zum automatischen Austausch von Informationen über Finanzkonten in Steuersachen (FKAustG). Dadurch sind deutsche Finanzinstitute verpflichtet, mit Beginn des Kalenderjahres 2016 für jedes meldepflichtige Konto die im FKAustG aufgeführten Daten zu erheben und bis zum 31. Juli des jeweiligen folgenden Kalenderjahres nach amtlich vorgeschriebenem Datensatz an das Bundeszentralamt für Steuern (BZSt) zu übermitteln.

----------

#####Stammdaten

Im Bereich der Stammdaten der Produkte und Gesellschaften greift aifExpert auf die gemeinsame Datenbasis von xpectoPro zu. Um korrekte und vollständige Meldungen abgeben zu können, müssen folgende Stammdaten gepflegt sein:

 - Produkte
	 - Reiter "Allgemein" > Bereich "Produktdefinition"
		 - Produkt-Name
	 - Reiter "Allgemein" > Bereich "Produkt-Gesellschaft"
		 - Firmenname
		 - Straße
		 - Land, PLZ, Wohnort
	 - Reiter "Parameter" > Bereich "Reporting"
		 - Alles notwendig, optional sind
			 - BaFin ID (notwendig für BaFin Meldung)
			 - Legal-Entity ID (notwendig für BaFin Meldung)
			 - Mindesthaltedauer (Jahre)
			 - Wertgesichert


![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen1.png)

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen2.png)

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen3.png)


 - Gesellschaften
	 - Reiter "Allgemein" > Bereich "Allgemein"
		 - Name
		 - Bundesbank ID (notwendig für BuBa Meldung)
		 - BaFin ID (notwendig für BaFin Meldung)
		 - Legal-Entity ID (notwendig für BaFin Meldung)
	 - Reiter "Allgemein" > Bereich "Adresse"
		 - Straße
		 - Land, PLZ, Wohnort


![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen26.png)

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen27.png)

----------

###Meldung für Bundesbank

#####1. Meldungsarten
Nachdem die Stammdaten korrekt und vollständig hinterlegt wurden beginnt nun der Prozess zur Erstellung der Meldung. 

Im ersten Schritt müssen die jeweiligen Meldungsarten erstellt und definiert werden. Das sind in diesem Fall die einzelnen Vordrucke der Bundesbank. Die Erstellung der Meldungsart kann durch die Betätigung der Schaltfläche "Neu" erfolgen. Im Reiter "Allgemein" kann diese benannt und mit einem Intervall und einer Fristigkeit versehen werden. Im Reiter "Aufbau" kann zu der jeweiligen Meldungsart die möglichen zu meldenden Posten hinterlegt werden. Diese Basis bewirkt, dass innerhalb dieser Meldungsart keine anderen Posten je Planung versehentlich gemeldet werden können. (siehe 2. Planungen)

Um eine sofortige und anwenderfreundliche Benutzung des aifExpert zu ermöglichen, sind die wichtigsten Meldungsarten und deren Aufbau bei der Installation bereits hinterlegt. 

Folgende Meldungsarten sind bereits hinterlegt bzw. implementiert:

 - Bbk10389: Allgemeine Angaben zur meldenden Gesellschaft (Vordruck 10389)
	 - Wird automatisch erstellt und vor den anderen Bundesbank-Meldungen gesetzt
 - Bbk10390: Allgemeine Angaben für das einzelne Investmentvermögen (Vordruck 10390)
 - Bbk10391: Monatliche Meldung für Investmentvermögen (Vordruck 10391)
 - Bbk10392: Monatliche Meldung für Investmentvermögen – Neubewertung (Vordruck 10392)

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen4.png)

*Beispiel*
*Es wurde die Meldungsart Bbk10390, welches den Bundesbank-Vordruck 10390 repräsentiert, erstellt und im Bereich "Aufbau" mit dem zu meldenden Posten "Art_Inhaber_Geschlossen" hinterlegt.*

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen5.png)

*Beispiel*
*Es wurde die Meldungsart Bbk103901, welches den Bundesbank-Vordruck 10391 repräsentiert, erstellt und im Bereich "Aufbau" mit den möglichen zu meldenden Posten hinterlegt.*

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen6.png)


#####2. Planungen
Nachdem die jeweiligen Meldungsarten definiert sind, erfolgt die Zuordnung der Produkte zur jeweiligen Meldungsart. Bedeutet, dass nun die Definition erfolgt, welche Produkte mit welchen Vordrucken überhaupt gemeldet werden können. Innerhalb dieser Definition wird auch festgelegt, welche Posten je Produkt je Meldungsart gemeldet werden sollen. Um eine Produkt (in diesem Fall eine "Planung") einer Meldungsart zuweisen zu können, muss die jeweilige Meldungsart ausgewählt und anschließend die Schaltfläche "Neu" > "Planung" betätigt werden. Anschließend öffnet sich ein Fenster zur Auswahl des jeweiligen Produktes. Nachdem das jeweilige Produkt ausgewählt wurde, wird dieses als Planung innerhalb der jeweiligen Meldungsart in der linken Liste angezeigt und kann nun im mittleren Bereich bearbeitet werden. Hier kann nun flexibel definiert werden, welche Posten für dieses Produkt gemeldet werden. Zwar können hier auch meldungsartfremde Posten hinterlegt werden, jedoch werden diese durch die hinterlegte Programmlogik letztendlich nicht gemeldet werden können, solange diese nicht im allgemeinen Aufbau der Meldungsart hinterlegt sind. Je Planung kann zusätzlich eine Abfrage im Feld "Datenherkunft-Posten" hinterlegt werden, um eine automatisierte Hinterlegung mit definierten Posten zu ermöglichen. Voraussetzend dafür ist eine vorhandene Definition der Posten im der Datenbank. Weiterhin kann je Posten im Bereich "Datenherkunft - Werte" unterschiedliche Quellen und Abfragen hinterlegt werden, die eine automatisierte Befüllung im Schritt 5. Meldung - Ausfüllen der Werte je Posten ermöglichen. 

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen7.png)

*Beispiel:*
*Es wurde zur Bbk10390 die Planung "IIF" hinterlegt. Zur Planung wurde der Posten "Inhaber private Haushalte" vom Typ "Art_Inhaber_Geschlossen" hinterlegt.*

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen8.png)

*Beispiel:*
*Es wurde zur Bbk10391 die Planung "IIF" hinterlegt. Zur Planung wurde verschiedene Posten von den definierten Typen hinterlegt.*

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen9.png)

#####3. Meldungen - Allgemein

Nachdem nun die Definition der Stammdaten und möglichen Meldungsarten und Planungen definiert ist kann die tatsächliche Meldung erfolgen. Dabei erlaubt der aifExpert die Meldung von mehreren Produkten bzw. mehreren Vordrucken innerhalb einer einzigen Meldung. Die Anlage der Meldung erfolgt mithilfe der Schalfläche "Neu" im Menü. Anschließend müssen im Reiter "Allgemein" die Felder der drei Bereiche "Allgemein", "Datei" und "Bbk Melder" befüllt werden. Essenzielle Felder sind dabei:

 - Bereich "Allgemein"
	 - Gesellschaft
	 - Periode
 - Bereich "Datei"
	 - Datei (Dateipfad - wird zum Erstellen der Datei benötigt)
 - Bereich "Bbk Melder"
	 - Alle Angaben

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen10.png)

#####4. Meldungen - Bestandteile

Nachdem der Meldungskopf definiert wurde kann im Reiter "Bestandteile" definiert werden, welche Planungen innerhalb dieser Meldung gemeldet werden sollen. Durch diese Funktion ist es möglich innerhalb einer Bundesbank-Meldung unterschiedliche Vordrucke für unterschiedliche Produkte zu melden. Zu beachten ist in diesem Bereich auch das Auswahlfeld "Erstmeldung". Sollte das Produkt zum ersten Mal der Bundesbank gemeldet werden, so ist dieses Feld für die jeweilige Planung in der entsprechenden Meldung zu aktivieren.

*Beispiel*
*In der Meldung 2016M12 für die Bundesbank wurden die Planungen Bbk10390 und Bbk10391 der Produktes "IIF" hinterlegt. Das heißt, dass innerhalb dieser Meldung die beiden Vordrucke 10390 und 10391 für das Produkt "IIF" erstellt werden.*

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen11.png)

#####5. Meldungen - Ausfüllen

Nachdem die Bestandteile der Meldung definiert worden sind, werden die zu meldenden Posten automatisch durch die Verbindung Meldungsart > Planung > Bestandteile (Meldung) erstellt und können nun mit den entsprechenden Werten befüllt werden. 

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen12.png)


#####6. Aktion - Prüfung anhand Bericht

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen13.png)

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen14.png)


#####7. Aktion - Erstellung der Datei


![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen15.png)


#####8. Benutzeraktion - Hochladen

#####9. Aktion - Kopie einer Meldung für neuen Zeitraum

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen16.png)

----------

###Meldung für BaFin / ESMA


----------

###Meldung für BZSt


----------


