Das Modul Nachschlagslisten dient dem Hinterlegen von Listen und Tabellen mit Werten, auf die an verschiedenen Stellen in der Software von
kundenspezifischen Masken und Scripten zurückgegriffen werden Kann.

![](http://xpecto.github.io/docs/img/img208.png)
![](http://xpecto.github.io/docs/img/img210.png)

Beispiel: Das Eingabefeld für die Anrede in der Kundenmaske kann alternativ als Auswahlfeld angelegt und so konfiguriert werden, dass die
auswählbaren Werte aus einer Nachschlagsliste mit der Bezeichnung "Anrede" entnommen werden. Die verfügbaren Werte können somit vom
Benutzer durch bearbeiten der Nachschlagsliste "Anrede" selbst angepasst werden, ohne in die Scripte eingreifen zu müssen, die das Verhalten der
Kundenmaske definieren.

Vorteile: Die Verwendung eines Auswahlfeldes anstatt eines Eingabefeldes für die Anrede vermeidet Tippfehler bei der Eingabe der Anrede. Dadurch
werden Peinlichkeiten bei der Erstellung von Serienbriefen vermieden, die dieses Feld enthalten. Darüber hinaus wird die Erstellung von
Datenbankabfragen für Auswertungen mit Unterscheidung der Kunden anhand des Geschlechts wesentlich erleichtert, da Tippfehler in den erfassten Anreden
nicht berücksichtigt werden müssen.

Nachschlagslisten sind immer mit einer Script-Programmierung an einer anderen Stelle der Software verbunden. Eine Nachschlagsliste, auf die nicht von einem
kundenspezifischen Script aus zugegriffen wird, hat keinen Sinn. Nachschlagslisten werden deshalb immer in Rücksprache und mit Hilfe des xpecto
Kundensupports angelegt, der auch das zugehörige Script programmiert. Änderungen und Erweiterungen der Werte in den hinterlegten
Nachschlagslisten können später jederzeit ohne Zuhilfenahme des xpecto Kundensupports vom Benutzer durchgeführt werden.
