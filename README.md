# LA1500-

# Projekt-Dokumentation

Rhododendron Leoanardo Grigoni, Lennard Bühler, Marek Vonrogall, Dorian Herzig

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|  21.02.23     | 0.0.1   | Heute haben wir unser Projekt ausgewählt und mit der Projektdokumentation angefangen|
|  28.02.23     | 0.0.2     |  Heute haben wir an unserer Projekt dokumentation weitergearbeitet. Wir haben uns über Unity informiert und schon die ersten Arbeitspakete erfüllt.                                                           |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Wir machen ein Jump and Run game.


Wir wollen Lernen mit für uns einer neuen Technik mit Unity ein Spiel zu Programmieren. In diesem Spiel sollte man rennen und Springen können das Spiel sollte in 2 D sein. Es gibt immer Checkpoints für die man aber erst einen Boss Besiegen muss. Wir wollen so viele Level wie möglich machen. Wir wollen auch mit einer für uns neuen Gruppe kennenlernen mit ihnen zu komunizieren und zusammen arbeiten ohne das man dafpr schon mal etwas zusammen gemacht hat.


### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1      |muss|     Funktional|     Als User kann ich meine figur bewegen|
|  2     |kann|     Funktional|     Als User kann ich meine figur aussuchen|
|   3    |kann|     Funktional|     Als User kann ich mein level aussuchen|
|    4   |kann|     Funktional|     Als User kann ich im menü den hintergrund aussuchen|
|     5  |muss|      Funktional|    Als User kann ich im menü das spiel beenden|
|      6 |kann|     Funktional|     Als User kann ich die Tastenbelegungen verändern.|
|7       |kann|     Funktional|     Als User kann ich die Lautstärke verändern|
| 8      |kann|     Funktional|     Als User kann ich aussuchen ob ich zu zweit oder aleine spiele|
|  9     |kann|     Funktional|     Als User kann ich meine Spezialfähigkeit|
|   10   |kann|     Funktional|     Als User kann ich im Shop spezialfähigkeiten und skins kaufen und freischalten|
|11      |muss |   Funktional   |    Als User möchte ich das ich Level mehrmals spielen kann                             |
|12      |muss|   Funktional   |    Als User möchte ich wenn ich Sterbe bei dem letzten Checkpoint wieder Spannen    |
|  13    | muss|  Funktional    |    Als User möchte ich wenn ich den Endboss des einen Levels besiegt habe in das nächste Level kommenen|
|    14  | muss|   Funktional   |    Als User möchte ich das wenn ich die kleinen Story berende eine Belonung bekomme |
|      15|muss|  Funktional    |    Als User möchte das alle Münzen die ich in einem Run sammle dann bei mir im Menu angezeigt werden|







### 1.3 Testfälle

| TC-№   | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ----   | ------------ | ------- | ----------------- |
|1.1      |Das Spiel ist offen.               |Tasten Eingabe     |Die Figur bewegt sich.                               |
|2.1     |Das Hauptmenü ist offen.                 |Man klick auf die option im Menü      |Das Figuren Menü geht auf                                    |
|2.2    |Das Figuren Menü ist offen.                 |Man klickt auf die Gegenstände die man ausrüsten will.      |Der Gegenstand wird angezogen   |
|3.1   |Das Hauptmenü ist offen.                 |Man klickt auf Spielen       |Es öffnet sich ein Fenster mit einer Minimap auf der die Levels sind. |
|3.2  |Man ist auf der Minimap                 |Mann geht auf die Level Röhre die man will     |Das Level wird gestartet         |
|4.1| Das Hauptmenü ist offen.                 |Man klickt auf den Hintergrund      |Das Hintergrund veränderungs Menü geht auf |
|4.2|Das Hintergrund-Menü ist offen                 |Man klickt auf den Hintergrund den Man will      |Der Hintergrund verändert sich|
|5.1|Das Hauptmenü ist offen.                 |Man klickt auf den "Spiel verlassen" Knopf.      |Das Spiel schliest sich.                  |
|6.1|Das Hauptmenü ist offen.                  |Man klickt auf den "Einstellungen" Knopf      |Es öffnet sich das Einstellungen Fenster          |
|6.2|Das Einstellungen Fenster ist offen                 |Man klickt auf den "Tastenbelegungen verändern" Knopf.      |Es öffnet sich das Tastenmenü  |
|6.3|Das Tastenmenü ist offen.|Man klickt auf die Ausgabe die man Belegen will und Klickt auf die Taste die Man benutzen will.|Es steht das die Taste verändert wurde.|
|7.1    |   Spielgestartet, Hauptmenu ist offen              |  Man geht auf den Lautstärken regler und passt die Lautstärke an    |   Die Lautstärke wird angepass.                                 |
|8.1    |  Das Spiel ist gestartet, Haupmenu ist offen                | Man geht auf den Knopf "Weiterer Spieler einloggen"     |  Man hat die Möglichkeit einen weiteren Spieler einzuloggen                                  |
|9.1  |  Spiel ist gestartet, man ist schon weit im Game               | Man nimmt eine Spezialmüze auf      |   Man hat für eine gewisse Zeit eine Spezialeigenschaft.                                 |
|10.1|  Spiel ist gestartet, Shop offen               |  Man wällt den Skin und oder die Spezialfähigkeit aus und kauft sie sich mit Münzen oder Geld| Man hat Skin und oder Spezialeigenschaft im Inventar.                                    |
|11.1    |     Spiel ist gestartet, Spiel ist durchgespielt            |  Menu öffnen und auf "Spiel Neustart" drücken    |       Spiel wird neu gestartet                             |
|12.1    |    Spiel gestartet, in einem Level |  Man Stribt    |      Man spannt am letzen Checkpoint                              |
|13.1  |    Spiel gestartet, in einem Level am Schluss           |  Man besiegt den Endboss     |    Man kommt in das neue Level             |
| 14.1|    Spiel gestartet             |   Story gemacht    |        Der User bekommt eine kleine Belonung                            |
|15.1   |    Spiel gestartet, in einem Level             | Der Spieler nimmt eine Münze auf      |   Diese Münze wird im Menu nacher angezeigt und man kann sie benutzen                                 |








### 1.4 Diagramme

![usecaseLA1500](https://user-images.githubusercontent.com/110893394/220430797-04bcf396-6c44-4945-8e6b-f7fe7daf5490.png)

<img width="331" alt="image" src="https://user-images.githubusercontent.com/110893245/220439339-4d22c4c6-dd70-4818-963e-a6a0a1efc3b6.png">

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       | leonardo          |Der User kann nach links laufen              |               |
|  2.A    |       | Leonardo          |Der User kann nach rechts laufen              |               |
|   3.A   |       | Leonardo          |Die Map bewegt sich mit dem Charakter mit              |               |
|   4.A   |       | Leonardo          |Der User kann springen              |               |
|   5.A   |       | Leonardo          |Der User kann sprinten              |               |
|   6.A   |       | Leonardo          |Der User kann ein Figurenmenü öffnen              |               |
|   7.A   |       | Leonardo          |Figur verändert sich nach dem Menü              |               |
|    8.A  |       | Leonardo          |Der User kann ein Level aussuchen              |               |
|   9.A   |       | Leonardo          |Das Level ist das ausgesuchte              |               |
|    10.A  |       | Leonardo          |Das einstellungs Fenster geht auf              |               |
|   11.A   |       | Leonardo          |Im einstellungs Fenster kann man das Hintergrundmenü aufmachen              |               |
|   12.A   |       | Leonardo          |Man kann die verschiedenen Schichten des Hintergrunds verändern              |               |
|   13.A   |       | Leonardo          |Der Hintergrund passt sich dem eingestellten Hintergrund an              |               |
|  14.A    |       |   Lennard        |  Der Charakter kann in eine der Röhren gehen um zu einem Level zu gelangen            |               |
|   15.A   |       |   Lennard        |   Der  Charakter kann auf ein Hindernis springen         |               |
|  16.A    |       |   Lennard        |   Der Charakter kann über Hindernisse springen           |               |
|   17.A   |       |   Lennard        |    Der Charakter kann unter Hindernissen hindurchsliden          |               |
|  18.A    |       |   Lennard        |   Der Charakter kann sich in der Weltenauswahl nach Links bewegen        |               |
|   19.A   |       |    Lennard       |  Der Charakter kann sich in der Weltenauswahl nach Rechts bewegen             |               |
|   20.A   |       |    Lennard       |  Der Charakter kann in der Weltenauswahl zu einem Level gehen            |               |
|  21.A    |       |    Lennard       |   Der Charakter kann in der Weltenauswahl in ein Level gehen, indem er in die Röhre vor dem Level springt  |   |
|   22.A   |       |     Lennard      |  Der User kann auf einer fligenden Plattform landen             |               |
|  23.A    |       |    Lennard       |  Der User kann sich auf einer fligenden Plattform bewegen           |               |
|   24.A   |       |    Lennard       | Der User kann Spezialmünzen aufsammeln             |               |
|   25.A   |       |     Lennard      |  Der User kann Münzen aufsammeln        |               |
|   26.A   |       |     Marek      |    Der User kann im Shop Skins kaufen          |               |
|   27.A   |       |     Marek      |   Im Hintergrund gibt es eine Ebene für Wolken|       |
|  28.A    |       |     Marek      |   Im Hintergrund gibt es eine Ebene für Berge         |               |
|   29.A   |       |    Marek       |   Im Hintergrund gibt es eine Ebene für Häuser           |               |
|   30.A   |       |     Marek      |   Im Hintergrund gibt es eine Ebene für den Himmel           |               |
|  31.A    |       |     Marek      |   Im Vordergrund gibt es eine Ebene für Gras und kleinere Details           |               |
|   32.A   |       |     Marek      |   In den Levels sollen Münzen erscheinen.           |               |
|  33.A    |       |    Marek       |   Nach einem Kauf einer Charaktervariante soll der aktuelle Charakter mit dieser ersetzt werden           |               |
|   34.A   |       |    Marek       |   Der Spieler kann seine Charaktervarianten im Hauptmenü oder in der Levelauswahl auswählen.          |               |
|  35.A    |       |    Marek       |    Es erscheinen Münzen in den Levels         |               |
|   36.A   |       |    Marek       |    Die Anzahl eingesammelter Münzen wird während dem Spiel angezeigt.          |               |
|   37.A   |       |     Dorian     |    Spezialeigenschaften von eingesammelten Münzen sind auf eine gewisse Zeitdauer beschränkt.          |               |
|   38.A   |       |      Dorian    |    Der Shop wird gepixelt.          |               |
|   39.A   |       |     Dorian     |    Der User kann im Shop Spezialeigenschaften kaufen          |               |
|   40.A   |       |    Dorian      |   Der User hat verschiendene Levels zum Spielen           |               |
|   41.A   |       |    Dorian      |  Der User hat eine Weltenauswahl auf der die Levels sind             |               |
|   42.A   |       |    Dorian      |  Der Rumpf des Charakters wird gepixelt.            |               |
|   43.A   |       |    Dorian      |  Der Kopf des Charakters wird gepixelt.            |               |
|  44.A    |       |    Dorian      |  Die Beine des Charakters werden gepixelt.            |               |
|  45.A    |       |    Dorian      |  Die Arme des Charakters werden gepixelt.            |               |
|   46.A   |       |    Dorian      |  Die animation für das Schleichen des Charakters wird gepixelt.           |               |
|   47.A   |       |    Dorian      |  Die animation für das sliden des Charakters wird gepixelt.            |               |
|   48.A   |       |    Dorian      |  Verschiedene Varianten des Charakters werden gepixelt (diese können anschliessend im Münzenshop gekauft werden)            |               |


Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

1: Wir wollten anfangs ein Kochspiel machen in dem man die Zutaten hin und her ziehen musste, aber da wir wenig Erfahrung mit Unity hatten, haben wir uns dazu entschieden ein Spiel zu nehmen das mehr mainstream ist und mehr Tutorials hat.

2: Wir haben uns dazu entschieden dass wir alles wie ein Pixelart gestalten damit wir eine feste Resolution haben und damit man das Spiel auf tiefer Resolution spielen kann.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
