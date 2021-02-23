# Hausarbeit: responsive Mobile-first Website mit CSS-Grid und Flexbox

In Teams soll eine Mobile first Website mit 4 responsiven Stufen erstellt werden.

Die Teams wurden per Zufallsverfahren zusammengestellt, um gleichstarke Gruppen zu bilden. Teamfähigkeit steht vor Individualleistung. Die, die eher Schwierigkeiten mit dem Stoff haben, können so von denen, die keine Schwierigkeiten haben lernen.

Die Hausarbeit wird nicht benotet. Es gibt nur ein bestanden oder nicht bestanden.

## Funktionsanforderungen

Das Layout der Site soll mit CSS-Grid und Flexbox erstellt werden.
Mobile-First mit den responsiven Stufen:

Mobile Portrait
ab 576px: Mobile Landscape
ab 768px: Tablet Portrait
ab 992px: Tablet landscape und Desktop
ab 1200px: Large Desktop
Diese Stufen sind angelehnt an das CSS-Framework Bootstrap, welches default diese Stufen verwendet.

Achtet darauf, dass auch zwischen diesen Stufen das Layout Sinnvoll ist, indem ihr Units fr, %, vw, vmin etc. sinnvoll einsetzt und an sinnvollen Stellen mit z.B. min-width oder max-width statt width arbeitet.

Die Website soll aus einer Home-Seite plus N weiteren HTML-Seiten bestehen (N = Anzahl Teammitglieder).
Jedes Teammitglied soll eine dieser N Seiten eigenständig erstellen.
Es soll eine sinnvolle Navigation zwischen den Seiten bereitgestellt werden.
Einheiliche Gestaltung der wiederkehrenden Elemente, wie z.B. Header und Navigation, auf allen Seiten. Die restlichen Seiteninhalte werden von jedem Teammitglied frei gestaltet.

## Seiteninhalt

Die Home-Seite soll die Namen und Matrikelnummern der Teammitglieder enthalten.
Inhalt der Teammitglieds-Seiten, soll die Dokumentation des Designkonzepts sein, bestehend aus:

Bild(ern), die eine Skizze des Layouts zeigen (Computergrafik oder auch handschriftlich und eingescannt/abfotografiert)
Bescheibung der Umsetzung, in der die Entscheidungsgrundlagen für z.B.

die verwendeten Grid-Parameter (column und row größen und units, gap, justify und align etc.)
die verwendeten Grid- und Flex-Container sowie Grid- und Flex-Items
die erwendeten paddings, margins, width etc.
etc.
beschrieben wird.

Also für alle Layout-relevanten HTML-Elemente und CSS-Eigenschaften, soll nachvollziehbar beschrieben werden, warum ihr das so verwendet habt und warum es dann zu dem sichtbaren Endergebnis führt.

## Implementationsanforderungen

Verwendet korrekte semantische Auszeichnungen.
Verwendet korrektes Semantic-Sectioning mit HTML5 Strukturelemente (main ,header, footer, section, articel usw.).
Verwendet eine gemeinsame CSS-Datei für das Basis-Design. Die Gestaltung der Teammitglieder-Seiten erfolgt wie gewohnt innerhalb im Style-Bereich im Head der Html-Seite
Der Dateiname der Home-Seite soll index.html sein.
Die Navigation zu den einzelnen Seiten muss den Namen des Teammitgliedes beinhalten.
Ebenfalls muss der entsprechende Name auf der Teammitglieds-Seite zu finden sein.
Verwendet auch hier wieder im Footer das Mailto wie in Labor 4 und ersetzt vorname.nachname@stud.hs-flensburg.de durch eure Mail-Adresse und Vorname und Name durch euren Namen:

`<a href="mailto:vorname.nachname@stud.hs-flensburg.de?subject=Webdesign%20Hausarbeit%20Feedback&body=Moin,%0D%0A%0D%0A%0D%0A%0D%0AGruß%0D%0ATommy">
    An Vorname Nachname Mailen
</a>`

## Abgabe / Benotung

**Abgabetermin 5. März**

Abgegeben wird jeweils eine ZIP-Datei pro Team. Sie enthält alle Dateien der Site (HTML, CSS, images)
Die Hausarbeit ist eine unbenotete Studienleistung, die mit erfolgreicher oder nicht erfolgreicher Teilnahme bewertet wird
