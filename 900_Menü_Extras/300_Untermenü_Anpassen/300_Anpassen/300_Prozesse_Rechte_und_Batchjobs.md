In eAgentur kann jeder Menüpunkt und jeder Karteireiter sowie das starten der Software pro Benutzer individuell gesperrt oder erlaubt werden. Der in
eAgentur verwendete Benutzer ist der jeweils angemeldete Windows-Benutzer.

In der Liste der Vorhanden Benutzer werden automatisch die in der Windows Domäne vorhandenen Benutzer eingetragen. Werden die Benutzer nicht
automatisch erkannt, können sie manuell angelegt werden. Einen neuen Benutzer legen Sie durch Click auf die Schaltfläche
![](http://xpecto.github.io/docs/img/img211.png)
an.

![](http://xpecto.github.io/docs/img/img212.png)

Geben Sie einen Benutzernamen ein. Achten Sie darauf, dass der gewählte Benutzername bereits ein Benutzerkonto im Windows Betriebssystem besitzt. Bei
Windows Domänen-Benutzern setzt sich der Benutzername aus Domänenname\Benutzername zusammen. Sollten Ihre Benutzer also an einem
Domänenkontroller angemeldet sein, so berücksichtigen Sie dies bitte bei der Erstellung des Benutzerskontos. Bestätigen Sie mit _OK_.
Nachdem Sie mit der Schaltfläche
![](http://xpecto.github.io/docs/img/img013.png)
speichern, wird der neue Benutzer in der linken Liste angezeigt.

Beim Start der Software werden zuerst die Rechte des angemeldeten Benutzers ermittelt und daraufhin nur die Menüpunkte und Karteireiter angezeigt,
für die der Benutzer berechtigt ist oder gegebenenfalls der Start der Software abgebrochen. Die Ermittlung der Berechtigungen eines angemeldeten
Benutzers erfolgt in zwei Stufen. Zuerst werden die Rechte des Benutzers "Default" abgefragt (der Benutzer "Default" wird bei der Installation
der Software automatisch angelegt und mit dem Recht "Administrator" ausgestattet). Danach werden die Rechte des tatsächlich angemeldeten
Benutzers abgefragt, diese überblenden gegebenenfalls die Rechte des Benutzers Default.

Beispiel: Beim Benutzer "Default" sei das Recht zum Start von eAgentur auf _erlauben_ gesetzt. Bei einem bestimmten Benutzer sei jedoch
zusätzlich das Recht zum Start von eAgentur auf _verbieten _gesetzt. Dadurch ist allen Windows Benutzern grundsätzlich das starten der
Software möglich. Der bestimmte Benutzer kann jedoch eAgentur nicht starten, obwohl beim Benutzer "Default" das Recht auf _erlauben_
gesetzt ist.

Spezielle Rechte: Die Rechte "Administrator" und "Poweruser" umfassen alle möglichen Rechte, d.h. das Setzen eines der beiden Rechte bei
einem Benutzer ist äquivalent zum Setzten aller anderen Rechte bei demselben Benutzer. Bei "Poweruser" können einzelne Rechte für den
Benutzer durch Setzen des entsprechenden Rechts auf _verbieten _entzogen werden. Im Gegensatz dazu ist dies bei "Administrator" nicht
möglich!

![](http://xpecto.github.io/docs/img/img214.png)

Zur Einstellung der Rechte eines Benutzers selektieren Sie den Benutzer und betätigen Sie die Schaltfläche
![](http://xpecto.github.io/docs/img/img046.png)
, um eine neue Berechtigungszeile einzufügen. In der Auswahlbox Recht wird das gewünschte Recht ausgewählt, und unter Wert die jeweilige
Berechtigungsstufe _erlauben_, _verbieten_ oder _default_.
