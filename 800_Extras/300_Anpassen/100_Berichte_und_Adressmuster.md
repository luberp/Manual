<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>100_Berichte_und_Adressmuster.md</title>
<link rel="stylesheet" href="https://stackedit.io/res-min/themes/base.css" />
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
</head>
<body><div class="container"><p>Alle Ausdrucke, die mit xpecto erstellt werden (wie z. B. Provisionsabrechnungen, Kundenanschreiben, Auswertungen, etc.), basieren auf gespeicherten Vorlagen, die entweder über die integrierte Berichtserstellungs-Komponente ActiveReports von Data Dynamics, oder über den Word-Editor erstellt werden. Die Vorlagen für Ausdrucke und Schreiben werden deshalb im folgenden (und auch bei der Kommunikation mit dem xpecto Kundensupport) als Berichte bezeichnet. Jeder Bericht besteht aus einem Layout, einer Datenbankabfrage sowie einigen Konfigurationsparametern. </p>

<p>Neben Bericht können Sie auch Adressmuster, Textbausteine und individuelle Schreiben erstellen.</p>

<p>Über die Symbolleiste <img src="http://xpecto.github.io/docs/img/img_1442245724286.png" alt="" title=""> oder über Menü <em>Extras → Anpassen → Berichte und Adressmuster</em> starten Sie den <em>Berichte und Textbausteine</em> -Dialog.</p>

<p>Berichte werden über Namen unterschieden, und thematisch in Gruppen verwaltet. Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1424086630188.png" alt="" title=""> wird eine neue Gruppe angelegt. Markieren Sie dann <em>neue Gruppe anlegen</em>, und geben Sie hier den Name an.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1424086718173.png" alt="" title=""></p>

<p>Geben Sie den Namen für die neue Gruppe ein und bestätigen Sie mit <em>OK</em>.</p>

<p>Mit der Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1424086982407.png" alt="" title=""> wird ein neuer Bericht angelegt. Gleichzeitig können Sie auch eine neue Gruppe anlegen. durch Auswählen des Checkboxes <em>neue Gruppe anlegen.</em> </p>

<p><img src="http://xpecto.github.io/docs/img/img_1442319951175.png" alt="" title=""></p>

<p>Ein neuer Bericht kann entweder ein leerer Bericht eine Kopie eines bestehenden Berichts, ein tabellarischer Bericht oder eine xpecto Vorlage. In jedem Fall muss der Name für den neuen Bericht angegeben werden, die Gruppe in die der Bericht eingegliedert werden soll und die Datenbasis dazu. Bei Auswahl einer Datenbasis wird automatisch eine entsprechende Datenbankabfrage generiert und im Bericht hinterlegt.  <br>
Die Art des Berichts kann nachträglich nicht mehr geändert werden! Durch Klick auf <em>OK</em> wird der Bericht angelegt.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1442317569556.png" alt="" title=""></p>

<p>Unter dem Reiter <em>Allgemein</em> können der Name und die Gruppe des Berichts geädert werden. Außerdem besteht die Möglichkeit, eine Beschreibung einzugeben.</p>

<p>Filter Field-IDs zeigt an der zuletzt ausgewählten Wert in eine Tabelle und kann als WHERE-Bedingung gebaut werden. <br>
Allgemein, Entwurf, Abfrage, Zusatzdaten, Kategorien, Versandoptionen.</p>

<p>Unter dem Reiter <em>Entwurf</em> wird das Layout des Berichts erstellt. Je nach dem, ob es sich um einen Word-Bericht oder um einen ActiveReports-Bericht handelt, erscheint hier ein Word-Editor  oder der Berichtseditor von Data Dynamics zur Bearbeitung des Layouts. Die Funktionsweise des Word-Editors ist angelehnt an die Grundfunktionen von Microsoft-Word. Der Editor sollte nur von Benutzer mit Erfahrung in Microsoft-Word verwendet werden, die Bedienung ist dann selbsterklärend. Hilfe zur Bedienung des Layout-Editors von Data Dynamics erhalten Sie im Internet unter der Adresse <a href="http://www.datadynamics.com">http://www.datadynamics.com</a>  <a href="http://www.componentone.com/">http://www.componentone.com/</a> oder vom xpecto Kundensupport.</p>

<p>ActiveReports ist sind Komponenten und Tools um Daten in Dokumente und web basierte Formate anzuzeigen. <br>
Neben den Komponenten mit ActiveReports können die Dateien in Formate wie PDF, Excel, RTF und TIFF exportiert werden.</p>

<p>Unter dem Reiter <em>Zusatzdaten</em> kann jeweils ein anderen Bericht als Kopfzeile bzw. Fußzeile, Briefpapier ausgewählt werden. So kann auf einfache Weise ein einheitlicher Briefkopf für mehrere Berichte verwendet werden. Änderungen am Briefkopf müssen dann zentral an einer Stelle durchgeführt werden, und nicht in jedem einzelnen Bericht. Als Kopf-, Fußzeile, oder Briefpapier können nur die Berichte verwendet die entsprechend kategorisiert sind.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1442317999574.png" alt="" title=""></p>

<p><em>Kategorien</em> sind die Einstellungen für die Hauptfenster. Mit den Optionen unter <em>Allgemeiner Bericht</em> kann festgelegt werden, unter welchen Umständen der Bericht in den Berichts-Favoriten auf der Werkzeugleiste der Hauptmaske angezeigt werden soll. Dies ist sinnvoll für häufig verwendete Berichte, da diese dann direkt von der Hauptmaske aus gedruckt werden können.</p>

<p><img src="http://xpecto.github.io/docs/img/img_1424100723603.png" alt="" title=""></p>

<p>Unter Unterbericht kann festgelegt werden, dass es sich bei dem Bericht um eine Kopfzeile, Fußzeile oder einen Briefpapier handelt. Der Bericht kann dann in anderen Berichten ausgewählt und verwendet werden.</p>

<p>Die Optionen unter Beleg geben die Möglichkeit ein Bericht als Beleg zu archivieren, dazu muss ein Belegtyp angegeben werden.</p>

<p>Beleg, Spezieller Bericht, Erweiterte Berechtigungen Drucksystem. <br>
Die Optionen unter spezieller Bericht sind für weitere geplante Funktionen vorgesehen. <br>
Erweiterte Berechtigungen Drucksystem.</p>

<p>Versandoptionen sind SMS  E-Mail eBrief.  EBrief hat eine Schnittstelle zu Software damit wird die PDF Datei zur Versandzentrum geschickt und für Versand vorbereitet. <br>
Unter dem Karteireiter Abfrage kann die dem Bericht zugrunde liegende Datenbankabfrage bearbeitet werden.  <br>
Benutzer benötigen hierzu Grundkenntnisse SQL.</p>

<p>Individuelle Schreiben können aus Textbausteine gebaut werden.</p>

<p>Über die Schaltfläche <img src="http://xpecto.github.io/docs/img/img_1424865740751.png" alt="" title="">  wird der aktuell selektierte Bericht gelöscht. Bestätigen Sie danach der Dialog mit <em>Ja</em> <img src="http://xpecto.github.io/docs/img/img_1424865976218.png" alt="" title="">.</p>

<p>Bearbeiten Berichte erzeugen. <br>
Anpasssen: Berichte und Adressmuster → Berichte, Adressmuster, Textbausteine, individuelle Schreiben <br>
Symbolleiste: Speichern, Berichtsgruppen neu anlegen, Berichte neu anlegen, Adressmuster neu anlegen, Textbausteine neu anlegen, Individuelle Schreiben neu anlegen, Aktuellen Datensatz löschen, Bericht importieren, Bericht exportieren. <br>
Symbol: Bericht erzeugen: generiert nur den Bericht. <br>
Symbol: Bericht bearbeiten: generiert die Vorlage die man danach bearbeiten kann. <br>
integrierter Berichtsgenerator ist Active Report.</p></div></body>
</html>