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

Im ersten Schritt müssen die jeweiligen Meldungsarten erstellt und definiert werden. Das sind in diesem Fall die einzelnen Formulare der Bundesbank. Im Reiter "Aufbau" kann zu der jeweiligen Meldungsart die möglichen zu meldenden Posten hinterlegt werden. Diese Basis bewirkt, dass innerhalb dieser Meldungsart keine anderen Posten je Planung versehentlich gemeldet werden können. (siehe 2. Planungen)

Um eine sofortige und anwenderfreundliche Benutzung des aifExpert zu ermöglichen, sind die wichtigsten Meldungsarten und deren Aufbau bei der Installation bereits hinterlegt. 

Folgende Meldungsarten sind bereits hinterlegt bzw. implementiert:

 - Bbk10389: Allgemeine Angaben zur meldenden Gesellschaft (Vordruck 10389)
	 - Wird automatisch erstellt und vor den anderen Bundesbank-Meldungen gesetzt
 - Bbk10390: Allgemeine Angaben für das einzelne Investmentvermögen (Vordruck 10390)
 - Bbk10391: Monatliche Meldung für Investmentvermögen (Vordruck 10391)
 - Bbk10392: Monatliche Meldung für Investmentvermögen – Neubewertung (Vordruck 10392)

*Beispiel*
*Es wurde die Meldungsart Bbk10390, welches den Bundesbank-Vordruck 10390 repräsentiert, erstellt und im Bereich "Aufbau" mit dem zu meldenden Posten "Art_Inhaber_Geschlossen" hinterlegt.*

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen4.png)

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen5.png)

*Beispiel*
*Es wurde die Meldungsart Bbk103901, welches den Bundesbank-Vordruck 10391 repräsentiert, erstellt und im Bereich "Aufbau" mit den möglichen zu meldenden Posten hinterlegt.*

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen6.png)

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen7.png)

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen8.png)

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen9.png)

![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen10.png)

----------

###Meldung für BaFin / ESMA


----------

###Meldung für BZSt


----------


