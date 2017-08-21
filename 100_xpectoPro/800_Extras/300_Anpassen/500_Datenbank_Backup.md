Das Backup kann nur von Benutzern mit dem Recht *Administrator* gestartet werden.

In der klassischen Menü-Ansicht ist die Funktion Datenbank Backup über Menü *Extras → Anpassen* erreichbar.

In der modernen Menü-Ansicht kann die Funktion über die Registerkarte *System* Gruppe *Datenbank* *Backup* gestartet werden.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Datenbank_Backup/Backup_Manue.png)

Sie haben hier die Möglichkeit einzelne Tabellen zu sichern falls eine komplette Sicherung nicht notwendig ist, markieren Sie an dieser Stelle einfach die notwendigen Tabellen der Datenbank. Default wird eine Sicherung der gesamten Datenbank durchgeführt.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Datenbank_Backup/Backup_Main.png)

Als Backup-Format können hier zwischen den Formaten *Binär, XML oder Sync XML-Format* gewählt werden.
Das gewählte Format spielt hier, je nach Verwendung, eine untergeordnete Rolle da bei Rücksicherung das Export_Format automatisch erkannt wird.

![](http://xpecto.github.io/docs/xpecto/Extras/Anpassen/Datenbank_Backup/Backup_Format.png)

Es werden nun alle Tabellen der Datenbank angezeigt. Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442928143560.png) erstellen Sie eine Backup-Datei der gesamten Datenbank in dem von Ihnen gewählten Format.  

Über die Schaltfläche ![](http://xpecto.github.io/docs/img/img_1442928753163.png) kann eine Backup-Datei rückgesichert werden, alle Datenbank-Tabellen werden durch die zuvor exportieren Tabellen der Backup-Datei überschrieben.