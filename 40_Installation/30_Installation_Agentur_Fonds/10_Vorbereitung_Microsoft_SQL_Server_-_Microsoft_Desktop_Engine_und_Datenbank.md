
Sofern in Ihrem Unternehmen bereits ein Microsoft SQL Server im Einsatz ist, muss ein neuer Benutzer und eine Datenbank angelegt werden. Gehen Sie hierbei wie im Handbuch Microsoft SQL Server beschrieben vor.

Befindet sich in Ihrem Unternehmen bisher noch kein Microsoft SQL Server im Einsatz, gehen Sie bitte nach folgender Anleitung vor.

- Die Datei CD.zip entpacken und im Verzeichnis CD\MSDE\setup.exe ausführen. Hiermit wird Microsoft Desktop Engine installiert.
- Starten Sie den Computer neu.
- Den gewünschten Datenbanknamen in der Datei CD\MSDE.tools\MSDECreateDatabase ändern. (Standardmäßig wird eine Datenbank mit dem Namen Agentur angelegt) Anschließend die nach Wunsch geänderte Batch-Datei CreateDatabase ausführen.
- Die Datei CD\MSDE.tools\MSDEChangeLogin.bat ausführen. Hiermit wird der Benutzername der Datenbank auf sa (Standard) und das Passwort auf xpecto gesetzt.
- Starten Sie Ihren Computer neu.

Die Microsoft Desktop Engine ist somit auf Ihrem System installiert und die benötigte Datenbank sowie ein Benutzer angelegt.

