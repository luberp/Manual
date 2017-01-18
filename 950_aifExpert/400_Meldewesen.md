aifExpert setzt auf Standardisierung & Automatisierung und bietet die Möglichkeit, die Informationen entsprechend den Vorgaben der deutschen Bundesbank, der BaFin sowie des Bundeszentralamts für Steuern elektronisch per Knopfdruck zu übertragen. 

Die hierfür benötigten Daten werden in speziellen Erfassungsmasken in aifExpert hinterlegt. Schnittstellen zu bestehenden Systemen, wie xpectoPro etc. können implementiert werden. Dadurch reduziert sich der manuelle Erfassungsaufwand erheblich, zusätzlich werden in dem integrierten Änderungsprotokoll- und dem Rechtesystem alle Veränderungen lückenlos dokumentiert.

aifExpert ist ein wichtiger Baustein, um die Erstellung des monatlichen Berichtswesens an die Deutsche Bundesbank, BaFin und das Bundeszentralamt für Steuern, professionell und mit geringstmöglichem Zeitaufwand IT-gestützt zu organisieren.

######Erläuterung
Rechtlich betrachtet ist die KVG nach § 26 Abs.1 ff. KAGB verpflichtet, mit Sachkenntnis und im Interesse ihrer Anleger und der Integrität des Marktes zu handeln. Zur besseren staatlichen Kontrolle verabschiedete dazu der Gesetzgeber mit den Paragraphen §§ 34, 35 die Anzeige- und Meldepflichten gegenüber der BaFin und der Bundesbank. Demnach muss die KVG regelmäßig detaillierte Aufstellungen und Angaben zu den Vermögensgegenständen, Märkten und Instrumenten gegenüber den Finanzanstalten anzeigen. Dabei müssen Informationen zu den wichtigsten Instrumenten, mit denen die KVG handelt, zu den Märkten, in denen die KVG Mitglied ist oder am Handel teilnimmt, sowie den größten Risiken und Konzentrationen jedes von der KVG verwalteten AIF vorgelegt werden.

Neben diesen umfangreichen Meldepflichten verabschiedete der Gesetzgeber das Gesetz zum automatischen Austausch von Informationen über Finanzkonten in Steuersachen (FKAustG). Dadurch sind deutsche Finanzinstitute verpflichtet, mit Beginn des Kalenderjahres 2016 für jedes meldepflichtige Konto die im FKAustG aufgeführten Daten zu erheben und bis zum 31. Juli des jeweiligen folgenden Kalenderjahres nach amtlich vorgeschriebenem Datensatz an das Bundeszentralamt für Steuern (BZSt) zu übermitteln.

----------

####Stammdaten

Im Bereich der Stammdaten der Produkte und Gesellschaften greift aifExpert auf die gemeinsame Datenbasis von xpectoPro zu. Um korrekte und vollständige Meldungen abgeben zu können, müssen folgende Stammdaten gepflegt sein:

 - Produkte
	 - Reiter "Allgemein" > Bereich "Produktdefinition"
		 - Produkt-Name
	 - Reiter "Allgemein" > Bereich "Produkt-Gesellschaft"
		 - Firmenname
		 - Straße
		 - Land, PLZ, Wohnort
	 - Reiter "Parameter" > Bereich "Reporting"
		 - Alle Angaben notwendig, optional sind
			 - BaFin ID (notwendig für BaFin Meldung)
			 - Legal-Entity ID (optional für BaFin Meldung)
			 - GIIN (optional für BaFin Meldung)
			 - Mindesthaltedauer (Jahre)
			 - Wertgesichert


> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen1.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen2.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen3.png)


 - Gesellschaften
	 - Reiter "Allgemein" > Bereich "Allgemein"
		 - Name
		 - Bundesbank ID (notwendig für BuBa Meldung)
		 - BaFin ID (notwendig für BaFin Meldung)
		 - Legal-Entity ID (optional für BaFin Meldung)
 	 - Reiter "Allgemein" > Bereich "Firma / Gemeinschaft"
		 - Name
	 - Reiter "Allgemein" > Bereich "Adresse"
		 - Straße
		 - Land, PLZ, Wohnort


> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen26.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen27.png)

----------

##Meldung für Bundesbank

####1. Meldungsarten
Nachdem die Stammdaten korrekt und vollständig hinterlegt wurden, beginnt nun der Prozess zur Erstellung der Meldung. 

Im ersten Schritt müssen die jeweiligen Meldungsarten erstellt und definiert werden. Das sind in diesem Fall die einzelnen Vordrucke der Bundesbank. Die Erstellung der Meldungsart kann durch die Betätigung der Schaltfläche "Neu" erfolgen. Im Reiter "Allgemein" kann diese benannt und mit einem Intervall und einer Fristigkeit versehen werden. Im Reiter "Aufbau" können zu der jeweiligen Meldungsart die möglichen zu meldenden Posten hinterlegt werden. Diese Basis bewirkt, dass innerhalb dieser Meldungsart keine anderen Posten je Planung versehentlich gemeldet werden können (siehe 2. Planungen).

Um eine sofortige und anwenderfreundliche Benutzung des aifExpert zu ermöglichen, sind die wichtigsten Meldungsarten und deren Aufbau bei der Installation bereits hinterlegt. 

Folgende Meldungsarten sind bereits hinterlegt bzw. implementiert:

 - Bbk10389: Allgemeine Angaben zur meldenden Gesellschaft (Vordruck 10389)
	 - Wird automatisch erstellt und vor den anderen Bundesbank-Meldungen gesetzt
 - Bbk10390: Allgemeine Angaben für das einzelne Investmentvermögen (Vordruck 10390)
 - Bbk10391: Monatliche Meldung für Investmentvermögen (Vordruck 10391)
 - Bbk10392: Monatliche Meldung für Investmentvermögen – Neubewertung (Vordruck 10392)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen4.png)

*Beispiel:*
*Es wurde die Meldungsart Bbk10390, welches den Bundesbank-Vordruck 10390 repräsentiert, erstellt und im Bereich "Aufbau" mit dem zu meldenden Posten "Art_Inhaber_Geschlossen" hinterlegt.*

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen5.png)

*Beispiel:*
*Es wurde die Meldungsart Bbk10391, welches den Bundesbank-Vordruck 10391 repräsentiert, erstellt und im Bereich "Aufbau" mit den möglichen zu meldenden Posten hinterlegt.*

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen6.png)

----------

####2. Planungen
Nachdem die jeweiligen Meldungsarten definiert sind, erfolgt die Zuordnung der Produkte (Fonds) zur jeweiligen Meldungsart. Bedeutet, dass nun die Definition erfolgt, welche Produkte mit welchen Vordrucken überhaupt gemeldet werden können. Innerhalb dieser Definition wird auch festgelegt, welche Posten je Produkt je Meldungsart gemeldet werden sollen. Um eine Produkt (in diesem Fall eine "Planung") einer Meldungsart zuweisen zu können, muss die jeweilige Meldungsart ausgewählt und anschließend im Menü-Reiter die Schaltfläche "Neu" > "Planung" betätigt werden. Anschließend öffnet sich ein Fenster zur Auswahl des jeweiligen Produktes. Nachdem das jeweilige Produkt ausgewählt wurde, wird dieses als Planung innerhalb der jeweiligen Meldungsart in der linken Liste angezeigt und kann nun im mittleren Bereich bearbeitet werden. Hier kann nun flexibel definiert werden, welche Posten für dieses Produkt gemeldet werden. Zwar können hier auch meldungsartfremde Posten hinterlegt werden, jedoch können diese durch die hinterlegte Programmlogik letztendlich nicht gemeldet werden, solange diese nicht im allgemeinen Aufbau der Meldungsart hinterlegt sind. Je Planung kann zusätzlich eine Abfrage im Feld "Datenherkunft-Posten" hinterlegt werden, um eine automatisierte Hinterlegung mit definierten Posten zu ermöglichen. Voraussetzend dafür ist eine vorhandene Definition der Posten in der Datenbank. Weiterhin kann je Posten im Bereich "Datenherkunft - Werte" unterschiedliche Quellen (SQL oder SXIntegrator) und Abfragen hinterlegt werden, die eine automatisierte Befüllung im Schritt "5. Meldung - Ausfüllen" der Werte je Posten ermöglichen. Voraussetzungen für die automatisierte Werte-Befüllung sind: 

 - Für Bbk 10390: korrekte Vertrags- und Anlegerdaten aus xpectoPro 
 - Für Bbk 10391: Schnittstelle zu Buchhaltungsdaten
 - Für Bbk 10392: Schnittstelle zu Buchhaltungsdaten


> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen7.png)

*Beispiel:*
*Es wurde zur Bbk10390 die Planung "IIF" hinterlegt. Zur Planung wurde der Posten "Inhaber private Haushalte" vom Typ "Art_Inhaber_Geschlossen" hinterlegt.*

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen8.png)

*Beispiel:*
*Es wurde zur Bbk10391 die Planung "IIF" hinterlegt. Zur Planung wurden verschiedene Posten von den definierten Typen hinterlegt.*

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen9.png)

----------

####3. Meldungen - Allgemein

Nachdem nun die Definition der Stammdaten und möglichen Meldungsarten und Planungen definiert ist, kann die tatsächliche Meldung erfolgen. Dabei erlaubt der aifExpert die Meldung von mehreren Produkten bzw. mehreren Vordrucken innerhalb einer einzigen Meldung. Die Anlage der Meldung erfolgt mithilfe der Schalfläche "Neu" im Menü-Reiter. Anschließend müssen im Reiter "Allgemein" die Felder der drei Bereiche "Allgemein", "Datei" und "Bbk Melder" befüllt werden. Essenzielle Felder sind dabei:

 - Bereich "Allgemein"
	 - Gesellschaft
	 - Periode
 - Bereich "Datei"
	 - Datei (Dateipfad - wird zum Erstellen der Datei benötigt)
 - Bereich "Bbk Melder"
	 - Alle Angaben

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen10.png)

----------

####4. Meldungen - Bestandteile

Nachdem der Meldungskopf definiert wurde, kann im Reiter "Bestandteile" definiert werden, welche Planungen innerhalb dieser Meldung gemeldet werden sollen. Durch diese Funktion ist es möglich innerhalb einer Bundesbank-Meldung unterschiedliche Vordrucke für unterschiedliche Produkte zu melden. Zu beachten ist in diesem Bereich auch das Auswahlfeld "Erstmeldung". Sollte das Produkt zum ersten Mal der Bundesbank gemeldet werden, so ist dieses Feld für die jeweilige Planung in der entsprechenden Meldung zu aktivieren.

*Beispiel:*
*In der Meldung 2016M12 für die Bundesbank wurden die Planungen Bbk10390 und Bbk10391 des Produktes "IIF" hinterlegt. Das heißt, dass innerhalb dieser Meldung die beiden Vordrucke 10390 und 10391 für das Produkt "IIF" erstellt werden.*

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen11.png)

----------

####5. Meldungen - Ausfüllen

Nachdem die Bestandteile der Meldung definiert worden sind, werden die zu meldenden Posten automatisch durch die Verbindung Meldungsart > Planung > Bestandteile (Meldung) erstellt und können nun mit den entsprechenden Werten befüllt werden. Die Schaltfläche "Werte abfragen" ermöglicht dabei die automatisierte Befüllung der Posten mit den entsprechenden Werten. Voraussetzend ist aber dafür die Hinterlegung der Datenherkunft beim entsprechenden Posten (siehe 2. Planungen).
Nachdem die entsprechenden Werte mit den dazugehörigen Daten ausgefüllt worden sind, müssen die Daten gespeichert werden. Entweder über die Betätigung der Schaltfläche "Speichern" oder durch den Speichern-Dialog (sollte die Oberfläche / Auswahl gewechselt werden oder das Programm geschlossen werden).

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen12.png)

----------

####6. Aktion - Prüfung anhand Bericht (optional)

Nachdem jegliche Posten mit Werten versehen wurden, ist die Meldung als vollständig zu betrachten. Um eine Gegenprüfung der hinterlegten Daten und der Meldung zu ermöglichen steht ein standardisierter Bericht zur Verfügung. Dieser Bericht wird in der Berichtsvorschau geöffnet und kann in unterschiedliche Formate gespeichert und gedruckt werden. Um den Bericht "Bundesbankmeldung" nutzen zu können müssen im Berichts-Editor im Fenster "Neuen Bericht erstellen" im Reiter "xpecto Vorlagen" der Bericht "Bundesbankmeldung" ausgewählt und heruntergeladen werden.

*Beispiel:*
*Der hier vorgestellte Bericht repräsentiert die Meldung für Dezember 2016 (2016M12). Hier wurden die Bestandteile Bbk 10390 und Bbk 10391 des Produktes "IIF" ausgewählt und deren Posten mit Beispielwerten befüllt.*

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen13.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen14.png)

----------

####7. Aktion - Erstellung der Datei

Nachdem jegliche Posten mit Werten versehen wurden, ist die Meldung als vollständig zu betrachten. Nun kann die Meldung als Datei erzeugt werden. Dabei nutzt der aifExpert das von der Bundesbank fest vorgeschriebene Schema. Um die Meldung zu erstellen muss die entsprechende Meldung ausgewählt und anschließend die Schaltfläche "Dateien erzeugen" im Menü-Reiter "Aktionen" betätigt werden. Dabei legt der aifExpert die Meldung als .xml-Datei auf dem hinterlegten Dateipfad (Reiter "Allgemein" - Bereich "Datei" - Feld "Datei") ab. 

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen15.png)

----------

####8. Benutzeraktion - Hochladen

Nachdem die Datei erstellt wurde kann der Anwender die Dateien im Benutzerportal der Bundesbank hochladen. Eine automatisierte Schnittstelle, d.h. die Abgabe der Meldung aus dem aifExpert heraus, ist derzeit noch nicht möglich.

----------

####9. Aktion - Kopie einer Meldung für neuen Zeitraum

Um eine benutzerfreundliche und effiziente Lösung im Meldewesen anbieten zu können, können durch die Betätigung der Schaltfläche "Daten in nächsten Zeitraum kopieren" bereits erstellte Meldungen mit allen hinterlegten Informationen kopiert werden. Dies kann entweder durch eine neue Periode, eine Nachmeldung oder eine Änderungsmeldung notwendig werden. Um die Daten in eine neue Periode zu kopieren muss der sich öffnende Dialog nur bejaht werden - aifExpert schlägt automatisch die nächste Periode vor. Bei einer Nachmeldung oder Änderungsmeldung (d.h. eine zusätzliche Meldung in der selben Periode) muss im Dialog der entsprechende Zeitraum im Format *YYYY* M *MM* (Beispiel: 2016M07) eingegeben werden. Dabei erstellt der aifExpert eine zusätzliche Meldung für diese Periode. Zur Unterscheidung wird dabei jedoch eine neue Dateinummer (fortlaufende Nummer, die bei 1 beginnt). Das bedeutet, dass je Periode beliebig viele Meldungen, möglich sind.

*Beispiel:*
*Kopie der Meldung vom Dezember 2016 (2016M12). Anlage einer zweiten Meldung mit Dateinummer 2. Innerhalb der Bestandteile wurde die Bbk 10392 des Produktes "IIF" ausgewählt.*

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen16.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen17.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen18.png)

----------

##Meldung für BaFin / ESMA

####1. Meldungsarten

Nachdem die Stammdaten korrekt und vollständig hinterlegt wurden, beginnt nun der Prozess zur Erstellung der Meldung. 

Im ersten Schritt muss die Meldungsart erstellt und definiert werden. Die Erstellung der Meldungsart kann durch die Betätigung der Schaltfläche "Neu" erfolgen. Im Reiter "Allgemein" kann diese benannt und mit einem Intervall und einer Fristigkeit versehen werden. 

Um eine sofortige und anwenderfreundliche Benutzung des aifExpert zu ermöglichen, ist die Meldungsart "EsmaAIF" bei der Installation bereits hinterlegt. 


> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen19.png)

----------

####2. Planungen

Nachdem die Meldungsart definiert ist, erfolgt die Zuordnung der Produkte. Bedeutet, dass nun die Definition erfolgt, welche Produkte anhand der BaFin/Esma-Meldung überhaupt gemeldet werden können. Um ein Produkt (in diesem Fall eine "Planung") der Meldungsart "EsmaAIF" zuweisen zu können, muss die Meldungsart ausgewählt und anschließend die Schaltfläche "Neu" > "Planung" betätigt werden. Anschließend öffnet sich ein Fenster zur Auswahl des jeweiligen Produktes. Nachdem ein Produkt ausgewählt wurde, wird dieses als Planung innerhalb der Meldungsart "EsmaAIF" in der linken Liste angezeigt.

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen7.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen19.png)

----------

####3. Meldungen - Allgemein

Nachdem nun die Definition der Stammdaten, Meldungsarten und Planungen definiert ist kann die Erstellung der AIFM- und der AIF- Meldung erfolgen. Dabei erlaubt der aifExpert die Meldung von mehreren Produkten, d.h. mehreren AIF-Meldungen. Die Anlage der Meldung erfolgt im Menü-Reiter mithilfe der Schaltfläche "Neu". Anschließend müssen im Reiter "Allgemein" die Felder der drei Bereiche "Allgemein", "Datei" und "BaFin/ESMA-Meldung" befüllt werden. Dabei sind folgende Felder essenziell:

 - Bereich "Allgemein"
	 - Gesellschaft
	 - Periode
 - Bereich "Datei"
	 - Datei (Dateipfad - wird zum Erstellen der Datei benötigt)
 - Bereich "BaFin/ESMA Meldung"
	 - Alle Angaben

Die Felder der anderen Bereiche sind optional und werden für die AIFM-Meldung verwendet. 

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen20.png)

----------

####4. Meldungen - Bestandteile

Nachdem der Meldungskopf definiert wurde kann im Reiter "Bestandteile" definiert werden, welche Planungen innerhalb der AIF-Meldung gemeldet werden sollen. Zu beachten ist in diesem Bereich auch das Auswahlfeld "Erstmeldung". Sollte das Produkt zum ersten Mal der BaFin/ESMA gemeldet werden, so ist dieses Feld für die jeweilige Planung in der entsprechenden Meldung zu aktivieren. Je Planung können nun die entsprechenden Daten und Informationen für jeden geforderten Artikel gemeldet werden. 

 

*Beispiel:*
*In der Meldung 2016 für die BaFin wurden die Planungen EsmaAIF der Produkte "IIF" und "SIF" hinterlegt. Nun können je Planung die entsprechenden Daten je Artikel gepflegt werden. Bei der Erstellung der AIF-Meldung werden jeweils die hinterlegten Daten von "IIF" und "SIF" verwendet.*

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen21.png)

----------

####5. Aktion - Prüfung anhand Bericht (optional)

Nachdem alle notwendigen Felder mit Werten versehen wurden, sind die AIFM-Meldung sowie die AIF-Meldung als vollständig zu betrachten. Um eine Gegenprüfung der hinterlegten Daten und der AIFM-Meldung zu ermöglichen steht ein standardisierter Bericht zur Verfügung. Dieser Bericht wird in der Berichtsvorschau geöffnet und kann in unterschiedlichen Formate gespeichert und gedruckt werden. Um den Bericht "EsmaMeldung" nutzen zu können, müssen im Berichts-Editor, im Fenster "Neuen Bericht erstellen", im Reiter "xpecto Vorlagen", der Bericht "EsmaMeldung" ausgewählt und heruntergeladen werden. 

Ein standardisierter Bericht zur AIF-Meldung ist derzeit noch nicht vorhanden.

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen22.png)

----------

####6. Aktion - Erstellung der Datei

Nachdem alle notwendigen Felder mit Werten versehen wurden, sind die AIFM-Meldung sowie die AIF-Meldung als vollständig zu betrachten. Nun können die Meldungen als Dateien erzeugt werden. Dabei nutzt der aifExpert das von der ESMA fest vorgeschriebene Schema. Um die Meldungen zu erstellen, muss die entsprechende Meldung ausgewählt und anschließend die Schaltfläche "Dateien erzeugen", im Menü-Reiter "Aktionen" betätigt werden. Dabei legt der aifExpert die Meldungen als .xml-Dateien und in komprimierter Form als .xml.gz-Dateien (GZIP) auf dem hinterlegten Dateipfad (Reiter "Allgemein" - Bereich "Datei" - Feld "Datei") ab. 

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen23.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen24.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen25.png)

----------

####7. Benutzeraktion - Hochladen

Nachdem die Datei erstellt wurde, kann der Anwender die Dateien im Melde- und Veröffentlichungssystem der BaFin (MVP-Portal) hochladen.

----------

####8. Aktion - Kopie einer Meldung für neuen Zeitraum

Um eine benutzerfreundliche und effiziente Lösung im Meldewesen anzubieten, können durch die Betätigung der Schaltfläche "Daten in nächsten Zeitraum kopieren" bereits erstellte Meldungen mit allen hinterlegten Informationen kopiert werden. Um die Daten in eine neue Periode zu kopieren, muss der sich öffnende Dialog nur bejaht werden - aifExpert schlägt automatisch die nächste Periode vor. 

----------

##Meldung für BZSt

Coming Soon

----------


