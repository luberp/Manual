Um die vorliegende Installation von eAgentur stets auf dem neuesten Stand zu halten, kann über diese Funktion ein Online-Update der Software
durchgeführt werden. Durch Click auf _"Update überprüfen"_ wird überprüft, ob auf dem xpecto Update-Server eine
neuere Version, als die aktuell installierte, zur Verfügung steht.

![](http://xpecto.github.io/docs/img/img216.png)

Ist bereits die aktuellste Version installiert, so erscheint die Meldung _"Es ist keine neuere Version verfügbar"_. Ist die aktuell
installierte Version nicht mehr aktuell, so wird die installierte und die zur Verfügung stehende Version angezeigt.

![](http://xpecto.github.io/docs/img/img218.png)

Bestätigen Sie mit _Ja_, um die angezeigte Version von eAgentur herunter zu laden und zu installieren. Nach Abschluss der Installation wird die
Software automatisch beendet und neu gestartet.

Die Versionsnummer des Softwarestandes, mit dem eine bestehende Datenbank zuletzt gestartet wurde, ist in der Datenbank gespeichert. Beim ersten Start der
Software mit einer Versionsnummer, die höher ist, als die in der Datenbank gespeicherte, wird automatisch ein Hinweis angezeigt mit der Frage, ob die
Versionsnummer in der Datenbank gespeichert werden soll.

![](http://xpecto.github.io/docs/img/img219.png)

Wurde die neue Version nur zu Testzwecken installiert, so ist die Frage mit _Nein_ zu beantworten. Die vorher in der Datenbank eingetragene
Versionsnummer bleibt dann bestehen. Wird die Frage mit _Ja_ beantwortet, so wird die neue Versionsnummer in der Datenbank eingetragen. Beim Zugriff
auf die Datenbank von einem anderen Arbeitsplatz im Netzwerk, an dem noch nicht die aktuelle Version installiert ist, erscheint dann eine entsprechende
Meldung mit dem Hinweis auf den veralteten Softwarestand.

Sofern auf allen Arbeitsplätzen im Netzwerk unter _Extras-&gt;Einstellungen_ ein korrekter gemeinsamer Update-Pfad eingerichtet ist (dies wird
vom xpecto Kundensupport bei der Installation eingestellt), wird nach der Durchführung des Updates an einem Arbeitsplatz das Update in dem Update-Pfad
abgelegt. An jedem weiteren Arbeitsplatz wird dann beim nächsten Start der Software das Update automatisch durchgeführt. Auf diese Weise wird
gewährleistet, dass immer alle Arbeitsplätze mit demselben Versionsstand der Software ausgestattet sind.

![](http://xpecto.github.io/docs/img/img179.png)
Für die Durchführung des Updates sind Administratorrechte oder zumindest Schreibrechte im eAgentur Installationsordner notwendig. Dies gilt auch
für die oben beschriebene automatische Update-Installation an den weiteren Arbeitsplätzen. Verfügt der angemeldete Benutzer nicht über
die notwendigen Rechte, so wird ein Eingabedialog angezeigt, in dem Benutzername und Passwort eines Benutzers eingegeben werden können, der über
die geforderten Rechte verfügt. Wenden Sie sich in diesem Fall an Ihren Systemadministrator.
