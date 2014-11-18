
Damit Ihre sensiblen Kundendaten nicht in falsche Hände geraten, verfügt Agentur / Fonds über ein zuverlässiges System zur Vergabe von Benutzerrechten. Wenn Ihre Mitarbeiter zwar die Kunden- und Vertragsdaten pflegen sollen, aber jedoch keine Einsicht in das Ergebnis Ihrer Provisionsabrechnung haben dürfen, so ist das ein Fall für das Agentur / Fonds Rechte - System.

Um Benutzer und deren Rechte zu konfigurieren, klicken Sie im Menü auf Extras - Rechte.

Sie melden sich an Agentur / Fonds mit dem Benutzernamen an, mit dem Sie lokal an Ihrem PC ( Windows ) angemeldet sind. Bei der Installation von Agentur / Fonds wird grundsätzlich ein "default Benutzer" angelegt der die Zugriffsrechte eines Administrators besitzt.

![](http://xpecto.github.io/docs/img/img_111.png)

Einen neuen Benutzer legen Sie durch einen Klick auf die Schaltfläche ![](http://xpecto.github.io/docs/img/img_112.png) an.

![](http://xpecto.github.io/docs/img/img_113.png)

Geben Sie einen Benutzernamen ein. Achten Sie darauf, dass der gewählte Benutzername bereits ein Benutzerkonto im Windows Betriebssystem besitzt. Bei Windows Domänen - Benutzer setzt sich der Benutzername aus Domänenname\Benutzername zusammen. Sollten Ihre Benutzer also an einem Domänenkontroller angemeldet sein, so berücksichtigen Sie dies bitte bei der Erstellung des Benutzerskontos.

Bestätigen Sie mit "OK".

Nachdem Sie mit ![](http://xpecto.github.io/docs/img/img_114.png) speichern, wird der neue Benutzer in der linken Liste angezeigt.

![](http://xpecto.github.io/docs/img/img_115.png)

Markieren Sie den neu angelegten Benutzer und betätigen Sie die Schaltfläche ![](http://xpecto.github.io/docs/img/img_116.png). Die Auswahlmenüs Rechte und Wert werden aktiv. Grundsätzlich verfügt ein neu angelegtes Benutzerkonto über keinerlei Rechte.

Es gibt zwei Möglichkeiten, um die Zugriffsberechtigungen eines Benutzerkontos zu konfigurieren.

Möglichkeit 1:

Als erstes Recht wird im linken Auswahlmenü das Recht "Rechte / Poweruser" gewählt. Der Poweruser besitzt alle Rechte eines Administrators (alle), kann aber im Gegensatz zum Administrator in seinen Zugriffsrechten eingeschränkt werden.

Im rechten Auswahlmenü muss nun ein Wert für das Recht ( im Beispiel Rechte / Poweruser) gewählt werden.

Zur Auswahl stehen:

- allow / erlauben
- deny / verbieten
- default

Für Rechte / Poweruser wählen Sie allow / erlauben und speichern anschließend mit ![](http://xpecto.github.io/docs/img/img_117.png).

Jetzt verfügt Ihr neu angelegter Benutzer über alle Rechte. Durch Auswahl der entsprechenden Rechte und Setzen des Wertes "deny / verbieten" kann das Benutzerkonto nun Recht für recht Eingeschränkt werden. Eine Änderung der Benutzerrechte wird ist nach erneutem Speichern wirksam.

Möglichkeit 2:

Das angelegte Benutzerkonto verfügt, wie bereits oben erwähnt, über keinerlei Benutzerrechte. Heben Sie nun Einschränkung für Einschränkung durch Auswahl eines Benutzerrechtes und Setzen des Wertes "allow / erlauben" auf.

In den meisten Fällen erweist sich Möglichkeit 1 als die sinnvollere Methode, da im Normalfall nur wenige Zugriffsrechte beschnitten werden müssen.

Bestätigen Sie die Änderung jedes einzelnen Zugriffsrechtes mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_118.png) und wählen Sie mit der Schaltfläche ![](http://xpecto.github.io/docs/img/img_119.png) ein weiteres Zugriffsrecht.

Konfigurierbare Benutzerrechte:

| Zugriffsrecht                                         | Auswirkung bei Aktivierung                                                                                                       |
| ---                                                   | ---                                                                                                                              |
| Funktion / Agentur starten                            | Starten von Agentur                                                                                                              |
| Funktion / Trace Fenster anzeigen                     | Mit Hilfe des Trace Fensters ist eine Nachverfolgung der abgelaufenen Datenbankzugriffe möglich                                  |
| Funktion / Provision einfügen                         |                                                                                                                                  |
| Menü / Datei / Daten speichern                        | Ermöglicht das Ändern (Speichern) und Anlegen von Datensätzen                                                                    |
| Menü / Datei / neuen Kunden anlegen                   | Ermöglicht das Anlegen neuer Kunden                                                                                              |
| Menü / Datei / neuen Vertrag anlegen                  | Ermöglicht das Anlegen neuer Verträge                                                                                            |
| Menü / Datei / neuen Vermittler anlegen               | Ermöglicht das Anlegen neuer Vermittler                                                                                          |
| Menü / Datei / zu den Firmen - Daten                  | Ermöglicht Zugang zu den Firmendaten                                                                                             |
| Menü / Datei / zu den Produkt - Daten                 | Ermöglicht Zugang zu den Produkt - Daten                                                                                         |
| Menü / Bearbeiten / Datensatz löschen                 | Ermöglicht das löschen von Datensätzen                                                                                           |
| Menü / Bearbeiten / ID ändern                         | Ermöglicht das Ändern von Vertragsnummern und Vermittlernummern                                                                  |
| Menü / Berichte / Belege verwalten                    |                                                                                                                                  |
| Menü / Berichte / Bericht bearbeiten                  | Ermöglicht das Ändern von Berichten und Auswertungen                                                                             |
| Menü / Berichte / Bericht erzeugen                    | Ermöglicht das Erzeugen von Berichten und Auswertungen                                                                           |
| Menü / Berichte / Entnahmeberechnung                  | Ermöglicht die Durchführung der Entnahmeberechnung                                                                               |
| Menü / Berichte / Fondsberechnung                     | Ermöglicht die Durchführung der Fondsberechnung                                                                                  |
| Menü / Berichte / Gewinnverteilung                    | Ermöglicht die Durchführung der Gewinnverteilung                                                                                 |
| Menü / Berichte / Provisionsberechnung                | Ermöglicht die Durchführung der Provisionsberechnung                                                                             |
| Menü / Berichte / Sollstellung                        | Ermöglicht die Durchführung der Sollstellung                                                                                     |
| Menü / Berichte / Zinsberechnung                      | Ermöglicht die Durchführung der Zinsberechnung                                                                                   |
| Menü / Extras / Abfragen erstellen                    | Ermöglicht die Erstellung eigener Datenbankabfragen mit Hilfe des Abfrageeditors                                                 |
| Menü / Extras / Auswahllisten                         | Ermöglicht das Erstellen / Ändern von Auswahllisten                                                                              |
| Menü / Extras / Backup erzeugen                       | Ermöglicht die Erstellung eines Datenbank - Backups                                                                              |
| Menü / Extras / Einstellungen                         | Ermöglicht den Zugang zum Menüpunkt Einstellungen                                                                                |
| Menü / Extras / Einstellungen / Erweiterungen         | Ermöglicht den Zugang zu Menüpunkt Einstellungen / Erweiterungen                                                                 |
| Menü / Extras / Einstellungen / Provisionen           | Ermöglicht den Zugang zu Menüpunkt Einstellungen / Provisionen                                                                   |
| Menü / Extras / Einstellungen / Berechnungen          | Ermöglicht den Zugang zu Menüpunkt Einstellungen / Berechnungen                                                                  |
| Menü / Extras / Einstellungen / Karrieresystem        | Ermöglicht den Zugang zu Menüpunkt Einstellungen / Karrieresystem                                                                |
| Menü / Extras / Einstellungen / Provisionskosten      | Ermöglicht den Zugang zu Menüpunkt Einstellungen / Provisionskosten                                                              |
| Menü / Extras / Felder anpassen                       | Ermöglicht den Zugang zu Menüpunkt Extras / Felder anpassen                                                                      |
| Menü / Extras / Lizenzen                              | Ermöglicht den Zugang zu Menüpunkt Extras / Lizenzen                                                                             |
| Menü / Extras / Oberflächen anpassen                  | Ermöglicht den Zugang zu Menüpunkt Extras / Oberflächen anpassen                                                                 |
| Menü / Extras / Nachschlagslisten bearbeiten          | Ermöglicht den Zugang zu Menüpunkt Extras / Nachschlagslisten bearbeiten                                                         |
| Menü / Extras / Provisionen einfügen                  | Ermöglicht den Zugang zu Menüpunkt Extras / Provisionen einfügen                                                                 |
| Menü / Extras / Rechte                                | Ermöglicht den Zugang zu Menüpunkt Extras / Rechte                                                                               |
| Menü / Extras / Update                                | Ermöglicht den Zugang zu Menüpunkt Extras / Update                                                                               |
| Menü / Extras / Wiedervorlage                         | Ermöglicht den Zugang zu Menüpunkt Extras / Wiedervorlage                                                                        |
| Menü / Import / Kontodaten importieren                | Ermöglicht den Zugang zu Menüpunkt Import / Kontodaten importieren                                                               |
| Menü / Import / Kontodaten übernehmen                 | Ermöglicht den Zugang zu Menüpunkt Import / Kontodaten übernehmen                                                                |
| Menü / Import / Kunden- und Vertragsdaten importieren | Ermöglicht den Zugang zu Menüpunkt Import / Vertragsdaten importieren                                                            |
| Menü / Import / Tabellen synchronisieren              | Ermöglicht den Zugang zu Menüpunkt Import / Tabellen synchronisieren                                                             |
| Rechte / Administrator                                | Dieses Zugriffsrecht beinhaltet alle Rechte(Administratorrechte) Keine zusätzliche Einschränkung anderer Zugriffsrechte möglich. |
| Rechte / Poweruser                                    | Dieses Zugriffsrecht beinhaltet alle Rechte. Eine zusätzliche Einschränkung der Zugriffsrechte ist möglich.                      |
| Tab / Kunde + Vertrag                                 | Ermöglicht den Zugang zur kompletten Ansicht Kunde und Vertrag                                                                   |
| Tab / Kunde / Allgemein                               | Ermöglicht den Zugang zur Ansicht Kunde Karteireiter Allgemein                                                                   |
| Tab / Kunde / Eigenschaften                           | Ermöglicht den Zugang zur Ansicht Kunde Karteireiter Eigenschaften                                                               |
| Tab / Kunde / Ereignisse                              | Ermöglicht den Zugang zur Ansicht Kunde Karteireiter Ereignisse                                                                  |
| Tab / Kunde / Zusatzdaten                             | Ermöglicht den Zugang zur Ansicht Kunde Karteireiter Zusatzdaten                                                                 |
| Tab / Vertrag / Allgemein                             | Ermöglicht den Zugang zur Ansicht Vertrag Karteireiter Allgemein                                                                 |
| Tab / Vertrag / Provision                             | Ermöglicht den Zugang zur Ansicht Vertrag Karteireiter Provision                                                                 |
| Tab / Vertrag / Auswertungen                          | Ermöglicht den Zugang zur Ansicht Vertrag Karteireiter Auswertungen                                                              |
| Tab / Vertrag / Buchungsdaten                         | Ermöglicht den Zugang zur Ansicht Vertrag Karteireiter Buchungsdaten                                                             |
| Tab / Vertrag / Ereignisse                            | Ermöglicht den Zugang zur Ansicht Vertrag Karteireiter Ereignisse                                                                |
| Tab / Vertrag / Sollbuchungen                         | Ermöglicht den Zugang zur Ansicht Vertrag Karteireiter Sollbuchungen                                                             |
| Tab / Mitarbeiter                                     | Ermöglicht den Zugang zur kompletten Ansicht Mitarbeiter                                                                         |
| Tab / Mitarbeiter / Allgemein                         | Ermöglicht den Zugang zur Ansicht Mitarbeiter Karteireiter Allgemein                                                             |
| Tab / Mitarbeiter / Auswertung                        | Ermöglicht den Zugang zur Ansicht Mitarbeiter Karteireiter Auswertung                                                            |
| Tab / Mitarbeiter / Belege                            | Ermöglicht den Zugang zur Ansicht Mitarbeiter Karteireiter Belege                                                                |
| Tab / Mitarbeiter / Buchungen                         | Ermöglicht den Zugang zur Ansicht Mitarbeiter Karteireiter Buchungen                                                             |
| Tab / Mitarbeiter / Eigenschaften                     | Ermöglicht den Zugang zur Ansicht Mitarbeiter Karteireiter Eigenschaften                                                         |
| Tab / Mitarbeiter / Ereignisse                        | Ermöglicht den Zugang zur Ansicht Mitarbeiter Karteireiter Ereignisse                                                            |
| Tab / Mitarbeiter / Provision                         | Ermöglicht den Zugang zur Ansicht Mitarbeiter Karteireiter Provision                                                             |
| Tab / Mitarbeiter / Struktur                          | Ermöglicht den Zugang zur Ansicht Mitarbeiter Karteireiter Struktur                                                              |
| Tab / Mitarbeiter / Zusatzdaten                       | Ermöglicht den Zugang zur Ansicht Mitarbeiter Karteireiter Zusatzdaten                                                           |


