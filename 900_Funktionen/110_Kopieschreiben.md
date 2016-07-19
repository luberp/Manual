# Kopieschreiben

Über die in xpectoPro integrierte Funktionalität Kopieschreiben ist es möglich eine Kopie eines Original-Schreibens, z. B. des Annahmeschreibens, an eine andere Adresse zusätzlich zu versenden.
Dabei ist es sogar möglich an beliebig viele Adressen eine Kopie zu versenden.

Hier ein Beispiel für einen möglichen Anwendungsfall:
Das Annahmeschreiben soll an den Kunden versendet werden.
Zusätzlich dazu soll dieses Schreiben in Kopie an dessen Vermittler versendet werden.
Außerdem möchte der Kunde, dass sein Steuerberater ebenfalls noch eine Kopie des Schreibens erhält.

Um die Funktionalität der Kopieschreiben nutzen zu können sind vorher einige Einstellungen notwendig.
Sie benötigen als erstes einen Bericht mit dem festen Namen "Kopie-Anschreiben" welcher als sogenannter Vorbrief fungiert.
Der Vorbrief ist das (An-)Schreiben, welches die 1. Seite des gesamten Schriftverkehrs an eine Adresse (z. B. den Schriftverkehr für den Steuerberater) bildet.
Schließlich muss das Anschriftenfeld sowie die Briefanrede des Kunden durch die Daten des Steuerberater ausgetauscht werden um den Steuerberater korrekt anzuschreiben.
Denn nur so kommt der Brief auch beim Steuerberater und nicht beim Kunden an.
Dieser Austausch der Daten geschieht durch die entsprechende Konfiguration/Anpassung dieses Berichts.
Der Inhalt des Vorbrief sollte möglichst einfach/generisch gehalten werden und z. B. nur darauf hingewiesen werden, dass Sie diesem Schreiben die Post für den Kunden xy erhalten.
Dies hat den Hintergrund, da es nur 1 Vorbrief Bericht gibt, aber gleichzeitig mehrere verschiedene zu versendende Berichte gibt.
Somit kann durch einen generischen Text einfach drauf verwiesen werden, dass im Anhang z. B. ein Annahmeschreiben oder eine Kündigungsbestätigung folgt.


* Einmalige Konfiguration des Kopieschreiben/Vorbriefschreibens:
** Über den Einstellungen Dialog der Software kann die Einstellung "CCWatermarkSettings" angepasst werden über die gesteuert wird welcher Text (Standardmäßig "KOPIE") und mit welchen Eigenschaften (Schrifart, Schriftgröße, Drehung, etc.) auf dem eigentlichen Hauptschreiben an den Kunden aufgedruckt werden soll.
** Außerdem ist die Anlage eines Berichts mit dem festen Namen "Kopie-Anschreiben" notwendig.
Dieser Bericht kann selbst angelegt werden oder aber aus den xpecto Vorlagen heruntergeladen werden. Dabei ist es sogar möglich, dass der Bericht "Kopie-Anschreiben" ein Bericht vom Typ "Kombidokument" ist, welcher dann z. B. für die verschiedenen Produkte einen anderen Vorbrief (z. B. mit anderem Text oder Briefpapier) liefert/druckt.
In diesem Fall muss die Abfrage der Einzelnen (Unter-)Berichte des Kombidokuments "Kopie-Anschreiben" entsprechend intelligent sein um das korrekte Schreiben zu liefern.

* Ergänzende Information zu den Einstellungen
Über die Einstellung OpenCCReportResult (welche Standardmäßig aktiviert ist) kann angegebeben werden, ob die Kopieschreiben Berichte geöffnet werden sollen.


* Ablauf der Konfiguration:
Der Kunde hat mehrere Adresen, welche im Reiter "Rollen" sichtbar sind, dabei muss bei mindestens einer der Adressen im Rahmen "Verwendung" der Haken bei der entsprechenden "Kopie"-Verwendung (z. B. Melde oder Post) ein Haken gesetzt.
Im Hauptschreiben (z. B. Annahmeschreiben) muss im Reiter "Allgemein" die Adressverwendung (z. B. Post) hinterlegt werden. Dadurch wird beim Druck diese Schreibens für jede Adresse dieses Kunden, welche im Feld Kopie-Verwendung "Post" einen Haken gesetzt hat, der ensprechende Schriftsatz erzeugt. Dieser besteht wie oben bereits dargestellt aus dem Vorbrief-Anschreiben und dem Original-Schreiben, welches an die Adresse mit der Verwendung "Post" gegangen ist.


Wird die Option "Vorbrief" in der Adresse verwendet (z. B. ist die Verwendung "Post" gesetzt) und gleichzeitig wird z. B. als Vorbrief "Eigenkopie" ausgewählt, dann wird beim Druck für den Vorbrief für diese Adresse immer die Melde Adresse (anstatt der Post-Adresse) im Vorbrief angezeigt.
Die Einträge der Auswahlliste "Vorbrief" könnten noch kundenspezifisch erweitert werden und dienen der Möglichkeit im Vorbrief (Bericht "Kopie-Anschreiben") anzugeben für aus welchem Grund/in welcher Funktion an diese Adresse ein Schreiben geschickt wird. 
Der Vorbrieftyp "Eigenkopie" sagt z. B. aus, dass man den Schriftsatz als Eigenkopie nochmal erhält.
Die anderen Vorbrieftypen "Steuerberater", "Vormund", "Vertriebspartners" etc. geben an in welcher (ausführenden) Funktion man die Kopieschreiben erhält.
