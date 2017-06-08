#### 1. Zugangsdaten

aifExpert nutzt zur Übertragung der Meldungen und zur Kommunikation mit dem BZSt die Massendatenschnittstelle (ELMA5). Um diese Schnittstelle nutzen zu können bedarf es vorheriger Anmeldungen auf dem Portal des BZSt. Nach den erfolgreichen Anmeldungen erhält der Anwender eine Reihe von Zugangsdaten sowie eine Zerfitikat-Datei. Diese Zugangsdaten sowie das Zertifikat sind essenziell für die ordnungsgemäße Benutzung des BZSt-Moduls vom aifExpert. Mithilfe der Schaltfläche "BZSt" im Bereich Zugangsdaten im Menü-Reiter "Stammdaten" öffnet sich ein Dialog in dem die notwendigen Informationen sowie das Zertifikat hinterlegt werden kann. 

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen28.png)


----------

#### 2. Meldungsarten

Nachdem die Stammdaten sowie die Zugangsdaten korrekt und vollständig hinterlegt wurden, beginnt nun der Prozess zur Erstellung der Meldung. 

Im ersten Schritt muss die Meldungsart erstellt und definiert werden. Die Erstellung der Meldungsart kann durch die Betätigung der Schaltfläche "Neu" im Menü-Reiter erfolgen. Im Reiter "Allgemein" kann diese benannt und mit einem Intervall und einer Fristigkeit versehen werden. 

Um eine sofortige und anwenderfreundliche Benutzung des aifExpert zu ermöglichen, ist die Meldungsart "CRS" bei der Installation bereits hinterlegt. 

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen29.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen30.png)

----------

#### 3. Planungen

Nachdem die Meldungsart definiert ist, erfolgt die Zuordnung der Produkte. Bedeutet, dass nun die Definition erfolgt, welche Produkte (Fonds) anhand der BZSt-Meldung überhaupt gemeldet werden können. Um ein Produkt (in diesem Fall eine "Planung") der Meldungsart "CRS" zuweisen zu können, muss die Meldungsart ausgewählt und anschließend die Schaltfläche "Neu" > "Planungen" betätigt werden. Anschließend öffnet sich ein Fenster zur Auswahl des jeweiligen Produktes. Nachdem ein Produkt ausgewählt wurde, wird dieses als Planung innerhalb der Meldungsart "CRS" in der linken Liste angezeigt.

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen31.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen32.png)

----------

#### 4. Meldungen - Meldungskopf

Nachdem nun die Definition der Stammdaten, Meldungsarten und Planungen definiert ist, kann die Erstellung der CRS-Meldung erfolgen. Dabei erlaubt der aifExpert die Meldung von mehreren Produkten, d.h. mehreren CRS-Meldungen. Der hierarchische Aufbau der Liste ist nach dem Schema Meldungskopf und darunterliegend die einzelnen CRS-Meldungen aufgebaut. Zuerst erfolgt die Anlage des Meldungskopfes mithilfe der Schaltfläche "Neu" im Menü-Reiter. Im Meldungskopf wird neben der Periode auch die Meldestelle definiert. Hier findet sich auch der Up-/Download-Bereich für die Kommunikation zum BZSt (siehe 8. Aktion - Dateien hochladen).

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen33.png)

----------

#### 5. Meldungen - Meldungen

Nachdem der Meldungskopf definiert wurde kann nun eine CRS-Meldung für das spezifische Produkt erstellt werden. Die Anlage der Meldung erfolgt mithilfe der Schaltfläche "Neu" im Menü-Reiter. Dabei bezieht sich die CRS-Meldung auf den darüber liegenden ausgewählten Meldungskopf.  Im Reiter "Allgemein" muss nun das jeweilige Produkt (in diesem Fall ist es eine Planung, die vorher im Bereich "Meldungsart" hinterlegt worden ist) ausgewählt werden. Im Reiter "Bestandteile" können nun die jeweiligen Konten inklusive der spezifischen Informationen für die CRS-Meldung hinterlegt werden. Es können dabei eine beliebig große Anzahl an Konten sowie den dazugehörigen wirtschaftlich Berechtigten erfasst und gespeichert werden. Die vollständige manuelle Eingabe der meldepflichtigen Konten sollte jedoch die letzte Wahl sein. Anhand einer Schnittstelle zu xpectoPro und der entsprechenden Kennzeichnung der Anleger in der Datenbank können die notwendigen Informationen automatisiert in die Meldung übertragen werden. Dazu muss die Schaltfläche "Konten aktualisieren" im Menü im Reiter "Aktionen" betätigt werden.

*Beispiel:*
*In der Meldung 2016 für die BZSt wurde die Planung CRS des Produktes "TRI1" verwendet. Nun können die entsprechenden Daten für die CRS-Meldung für den TRI1 gepflegt werden. Anhand der Schnittstelle zu der Anlegerverwaltung xpectoPro werden die Informationen zu den einzelnen Konten automatisiert in die Meldung übergeben. Bei der anschließenden Erstellung der CRS-Meldung werden jeweils die hinterlegten Stammdaten von "TRI1" sowie die entsprechenden Meldedaten verwendet.*

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen34.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen35.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen36.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen37.png)


----------


#### 6. Aktion - Prüfung anhand Bericht (optional)

Nachdem alle notwendigen Felder mit Werten versehen wurden, ist die CRS-Meldung als vollständig zu betrachten. Um eine Gegenprüfung der hinterlegten Daten der einzelnen Konten zu ermöglichen steht ein standardisierter Bericht zur Verfügung. Bei Betätigung der Schaltfläche "Bericht anzeigen" im Menü im Reiter "Aktionen" wird dieser Bericht in der Berichtsvorschau geöffnet und kann nun in unterschiedlichen Formaten gespeichert und gedruckt werden. Um den Bericht "CRSMeldung" nutzen zu können, müssen im Berichts-Editor, im Fenster "Neuen Bericht erstellen", im Reiter "xpecto Vorlagen", der Bericht "CRSMeldung" ausgewählt und heruntergeladen werden. 

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen43.png)

----------

#### 7. Aktion - Erstellung der Datei

Nachdem alle notwendigen Felder mit Werten versehen wurden, ist die CRS-Meldung als vollständig zu betrachten.  Nun können die Meldungen als xml. Dateien erzeugt werden. Dabei nutzt der aifExpert das von der OECD fest vorgeschriebene Schema. Um eine einzelne Meldungen zu erstellen, muss die entsprechende Meldung ausgewählt und anschließend die Schaltfläche "Dateien erzeugen", im Menü-Reiter "Aktionen" betätigt werden. Für eine Mehrfacherzeugung muss der Meldungskopf ausgewählt werden. Dabei legt der aifExpert die Meldungen als .xml-Dateien auf dem hinterlegten Dateipfad (Meldungskopf - Reiter "Allgemein" - Bereich "Datei" - Feld "Datei") ab. Sollte kein spezifischer Dateipfad hinterlegt sein, erfolgt die Ablage automatisch im eingestellten Archiv-Pfad des aifExpert. Nach der Erstellung der Datei können diese nun im nächsten Schritt an das BZSt hochgeladen werden (siehe 8. Aktion - Dateien hochladen).

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen38.png)

----------

#### 8. Aktion - Dateien hochladen

Nachdem die zu meldenden Dateien erstellt wurde, können diese nun im Bereich des Meldungskopfes im Up-/Download-Bereich an das BZSt gemeldet werden. Das hochladen der jeweiligen Datei erfolgt dabei durch die Betätigung der Schaltfläche innerhalb der jeweiligen Meldung. Dieser Vorgang wird zusätzlich zur Sicherheit separat protokolliert, d.h. es wird erfasst wer und wann das Hochladen vorgenommen hat.

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen39.png)

----------

#### 9. Aktion - Abholung BZSt-Antworten

Nachdem die Dateien hochgeladen wurden, können nun die jeweiligen Antworten des BZSt abgeholt werden.
Dies erfolgt zentral, d.h. unabhängig von Meldung und Periode, mithilfe der Schaltfläche "Abholung" im Menü-Reiter "Aktionen". Dabei werden die Antworten vom BZSt heruntergeladen und der jeweiligen Meldung zugeordnet. 

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen40.png)


----------

#### 10. Aktion - Kopie einer Meldung für neuen Zeitraum

Um eine benutzerfreundliche und effiziente Lösung im Meldewesen anzubieten, können durch die Betätigung der Schaltfläche "Daten in nächsten Zeitraum kopieren" bereits erstellte Meldungen mit allen hinterlegten Informationen kopiert werden. Um die Daten in eine neue Periode zu kopieren, muss der sich öffnende Dialog nur bejaht werden - aifExpert schlägt automatisch die nächste Periode vor. 

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen41.png)

> ![](http://xpecto.github.io/docs/img/aifExpert_Meldewesen42.png)


----------

#### 11. Aktion - Löschen

Die Löschung von Datensätzen und Einträgen erfolgt nach einem standardisierten Schema. 
Dabei stellt dieses sicher, dass nur Datensätze gelöscht werden können, die nicht mehr von anderen Datensätzen referenziert werden.
D.h. Eine Löschung einer CRS-Meldung kann nur dann erfolgen, wenn im Vorfeld im Reiter "Bestandteile" die einzelnen Konten gelöscht wurden.
Die Schaltfläche "Löschen" im Menü bezieht sich dabei immer auf den ausgewählten Eintrag in der linken Liste.
Innerhalb der einzelnen Detailreiter (wie z.B. Reiter "Bestandteile") erfolgt das Löschen und Neuanlegen durch die integrierten Schaltflächen. 

----------

