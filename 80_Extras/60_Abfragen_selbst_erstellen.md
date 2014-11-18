
Agentur bietet einen anwenderfreundlichen Abfrageeditor für Datenbankabfragen, der auch weniger geübten Anwendern die Möglichkeit gibt, eigene Datenbankabfragen bzw. Auswertungen zu erstellen.

Sie erreichen den Abfrageeditor im Menü Extras - Listen und Abfragen - Abfrage erstellen.

![](http://xpecto.github.io/docs/img/img_120.png)

Fahren Sie mit der Maus über Teile der Abfrage um Tipps zu erhalten.

![](http://xpecto.github.io/docs/img/img_121.png)

Fahren Sie mit Ihrer Maus über "jede der Bedingungen trifft zu (AND)" und klicken Sie mit der rechten Maustaste darauf. Es erscheint ein Kontextmenü in dem Sie die Bedingung nach Ihren Wünschen anpassen können.

Mögliche Bedingungen sind:

- Jede der Bedingungen trifft zu (AND)
- Eine oder mehrere Bedingungen treffen zu (OR)
- Keine der Bedingungen trifft zu (NOT OR)

Mit einem Rechtsklick auf das Hintergrundfeld öffnet sich ein Kontextmenü in dem Sie ein(en)

- Feld einfügen
- Block einfügen

Ein Feld fügen Sie dann ein, wenn z.B. nur der Status eines Vertrages mit dieser Bedingung abgefragt werden soll.

Einen Block fügen Sie ein, wenn mehrere Felder mit der gleichen Bedingung verknüpft werden sollen.

Mit ![](http://xpecto.github.io/docs/img/img_122.png) löschen Sie das Feld aus Ihrer Abfrage.

Um die Feldauswahl dieser Bedingung zu ändern, klicken Sie mit der rechten Maustaste auf das ausgewählte Feld (hier "Vertragsnummer") und wählen im Kontextmenü das gewünschte, abzufragende Feld aus.

Auf die gleiche Weise wird der Operator der Bedingung ausgewählt. Es stehen folgende Operatoren zur Verfügung:

- Entspricht einem der folgenden Werte
- Beginnt mit folgendem Text
- Enthält folgenden Text
- Liegt zwischen den folgenden Werten
- Ist kleiner / früher oder entspricht folgenden Wert
- Ist größer / später oder entspricht folgenden Wert

Letztlich wird im Eingabefeld der Wert der Bedingung eingetragen.

Betrachten wir folgendes Beispiel:

Sie wollen wissen, welche Kunden eines bestimmten Vermittlers im Jahr 2003 ein bestimmtes Produkt xy gekauft haben.

Starten Sie den Abfrageeditor und fügen Sie einen Block ein.

Erstellen Sie folgende Bedingung:

![](http://xpecto.github.io/docs/img/img_123.png)

Als Wert tragen sie die Nummer Ihres Vermittlers ein. Somit ist sichergestellt, dass alle später abgefragten Infos zu Ihrem Vermittler gehören.

![](http://xpecto.github.io/docs/img/img_124.png)

In der nächsten Bedingung wird das Produkt festgelegt. Es sollen schließlich nur alle Kunden, die ein bestimmtes Produkt gekauft haben, im Ergebnis enthalten sein.

Als dritte Bedingung grenzen Sie die Abfrage auf das Jahr 2003 ein.

Somit ist das Ergebnis bereits auf alle Verträge, die von einem bestimmten Vermittler im Jahre 2003 abgeschlossen wurden, eingegrenzt.

Klicken sie nun auf ![](http://xpecto.github.io/docs/img/img_125.png)

![](http://xpecto.github.io/docs/img/img_126.png)

Wählen Sie nun die gewünschten Daten Ihrer Auswertung aus. In unserem Beispiel waren das alle Kunden, also Kundennummer, Name und Vorname.

Setzen Sie in der Auswahl Kundendaten bei Kundennummer, Name und Vorname jeweils ein Häkchen.

Klicken Sie auf weiter...

![](http://xpecto.github.io/docs/img/img_127.png)

Das Ergebnis Ihrer Abfrage wird präsentiert. Kundennummer, Kundenname und Kundenvorname aller Kunden, die im Jahre 2003 ein bestimmtes Produkt bei Ihrem gewünschten Vermittler gekauft haben.

Erfahrene Benutzer können das vom Abfrageeditor erzeugte SQL-Statement im oberen Fenster betrachten und gegebenenfalls abändern oder erweitern. Die Abfrage kann nach Änderungen mit ![](http://xpecto.github.io/docs/img/img_128.png) erneut gestartet werden.

Nun kann das Ergebnis unserer Abfrage als CSV - Datei ( z.B. zum Import in andere Programme) oder als PDF - Datei ausgegeben werden. Benutzen Sie für den Export die Schaltflächen ![](http://xpecto.github.io/docs/img/img_129.png) oder ![](http://xpecto.github.io/docs/img/img_130.png).

Beenden Sie den Abfrageeditor mit ![](http://xpecto.github.io/docs/img/img_131.png).

Der Abfrageeditor ist als Hilfestellung für unerfahrene Benutzer gedacht und deckt einfache Abfragen ab. Komplexe Abfragen wie z.B. Sollbuchungen etc. können mit dem Abfrageeditor nur teilweise oder gar nicht abgedeckt werden. Falls Sie Auswertungen auf Grundlage komplexer Abfragen benötigen, kontaktieren Sie bitte Ihr xpecto - Team.


