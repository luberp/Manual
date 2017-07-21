
Eine Konsolidierung von Plänen und Posten ist auf zwei Wege möglich:
- Die Anlage eines Plan-Produkt-fremden Postens (diese Funktion ist standardmäßig deaktiviert) durch das Feld "Owner" im Aufbau
  - Mithilfe dieser können Posten in jeweils unterschiedlichen Plänen vorkommen, benutzen aber alle dieselben Werte (z.B. Plan KVG und Plan Fonds1 besitzen beiden den gleichen Posten mit dem Owner "Fonds1" > In beiden Plänen können nun die Werte des Posten angezeigt und ggf. bearbeitet werden)
- Durch eine Referenz im Feld "Datenparameter" im Aufbau 
  - Bei einer Referenz muss im Datenparameter in eckigen Klammern die Referenz auf den jeweiligen Posten getroffen werden, indem zuerst das Produkt + Komma + ID des Postens angegeben wird > [Produkt, ID] (z.B. [KVG, A00000002] > Referenz auf diesen Posten.
  - Nun referenziert dieser Posten auf den anderen. Durch die Betätigung der Aktualisieren-Schaltfläche, links neben der Spalte Einheit im Eingabe-Reiter, prüft der aifExpert ob sich beim referenzierten Posten Werte verändert haben und übergibt diese dem entsprechenden Posten, d.h. aifExpert holt sich die Werte ab. Alternativ kann im Menü-Reiter unter Aktionen die Schaltfläche "Referenzen" betätigt werden. Dabei holt aifExpert für alle referenzierten Posten die Werte ab.
  - Standardmäßig müssen die Werte manuell abgeholt werden. Eine automatische Abholung kann jedoch eingestellt werden.
  

> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet39.png)
> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet40.png)
> ![](http://xpecto.github.io/docs/aifExpert/aifExpert_Liquiditaet41.png)


--------
