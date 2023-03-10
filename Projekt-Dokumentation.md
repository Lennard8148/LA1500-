# LA1500-

# Projekt-Dokumentation

Rhododendron Leonardo Grigioni, Lennard Bühler, Marek Vonrogall, Dorian Herzig

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|  21.02.23     | 0.0.1   | Heute haben wir unser Projekt ausgewählt und mit der Projektdokumentation angefangen|
|  28.02.23     | 0.0.2     |  Heute haben wir an unserer Projekt dokumentation weitergearbeitet. Wir haben uns über Unity informiert und schon die ersten Arbeitspakete erfüllt.                                                           |
|  7.03.23     | 0.0.3   |       Die ersten Arbeitspakete gemacht                                                  |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Wir machen ein Jump and Run game.


Wir wollen Lernen mit für uns einer neuen Technik mit Unity ein Spiel zu Programmieren. In diesem Spiel sollte man rennen und Springen können das Spiel sollte in 2 D sein. Es gibt immer Checkpoints für die man aber erst einen Boss Besiegen muss. Wir wollen so viele Level wie möglich machen. Wir wollen auch mit einer für uns neuen Gruppe kennenlernen mit ihnen zu komunizieren und zusammen arbeiten ohne das man dafpr schon mal etwas zusammen gemacht hat.


### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
|1|muss|     Funktional|     Als User kann ich meine figur bewegen, damit man das Spiel spielen kann|
|2|kann|     Funktional|     Als User kann ich meine figur aussuchen, damit das Spiel nicht so langweilig ist|
|3|kann|     Funktional|     Als User kann ich mein level aussuchen, damit man nicht nicht nur ein Level spielen kann, sondern auch andere und so abwechslung bekommt|
|4|kann|     Funktional|     Als User kann ich im Menü den hintergrund aussuchen, damit das Spiel besser aussieht|
|5|kann|     Funktional|     Als User kann ich im menü das Spiel beenden, damit man das Spiel nicht immer offen haben muss|
|6|kann|     Funktional|     Als User kann ich die Tastenbelegungen verändern, damit verschiedene Spielertypen das Spiel mit ihren eigenen Tasten spielen können.|
|7|kann|     Funktional|     Als User kann ich die Lautstärke verändern, damit man wenn man die Musik lauter haben möchte sie lauter stellen kann und wenn man sie leiser haben möchte leiser machen kann.|
|8|kann|     Funktional|     Als User kann ich aussuchen ob ich zu zweit oder aleine spiele, damit man das Spiel auch mit einem Kollegen zusammen Spielen kann.|
|9|kann|     Funktional|     Als User kann ich Spezialfähigkeiteiten im Spiel haben, damit man Gegner besiegen kann und ein Level schneller durchspielen kann, kommt auf die Spezialfähigkeit an was man für eine hat. |
|10|kann|    Funktional|     Als User kann ich im Shop spezialfähigkeiten und skins kaufen und freischalten, damit der User nicht immer nur den gleichen Skin spielen muss, auch Spezialfähigkeiten kann man in einem Level für eine gewisse dauer kaufen mit Münzen|
|11|muss|    Funktional|     Als User möchte ich das ich Level mehrmals spielen kann, damit wenn man ein Level schon einmal gespielt hat es nochmals zu spielen.                            |
|12|muss|    Funktional|     Als User möchte ich wenn ich Sterbe bei dem letzten Checkpoint wieder Spannen, damit man nicht immer wenn man stirbt das Level ganz neu Spielen muss.   |
|13|muss|    Funktional|     Als User möchte ich wenn ich den Endboss des einen Levels besiegt habe in das nächste Level kommen, damit man nicht immer nur in einem Level feststeckt sondern auch noch weitere Level spielen kann.|
|14|kann|    Funktional|     Als User möchte ich, dass wenn ich alle Level beende, eine Belohnung bekommen, damit es sich lohnt das Spiel durchzuspielen.|
|15|muss|    Funktional|     Als User möchte das alle Münzen die ich in einem Run sammle in der oberen linken Ecke angezeigt bekommen, damit ich immer weiss wie viele Münzen ich bereits habe.|







### 1.3 Testfälle

| TC-№   | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ----   | ------------ | ------- | ----------------- |
|1.1|Das Spiel ist offen.                     |Tasten Eingabe     |Die Figur bewegt sich.                               |
|2.1|Das Hauptmenü ist offen.                 |Man klick auf die option im Menü      |Das Figuren Menü geht auf                                    |
|2.2|Das Figuren Menü ist offen.              |Man klickt auf die Gegenstände die man ausrüsten will.      |Der Gegenstand wird angezogen   |
|3.1|Das Hauptmenü ist offen.                 |Man klickt auf Spielen       |Es öffnet sich ein Fenster mit einer Minimap auf der die Levels sind. |
|3.2|Man ist auf der Minimap                  |Man geht auf die Level Röhre die man will     |Das Level wird gestartet         |
|4.1|Das Hauptmenü ist offen.                 |Man klickt auf den Hintergrund      |Das Hintergrund veränderungs Menü geht auf |
|4.2|Das Hintergrund-Menü ist offen           |Man klickt auf den Hintergrund den Man will      |Der Hintergrund verändert sich|
|5.1|Das Hauptmenü ist offen.                 |Man klickt auf den "Spiel verlassen" Knopf.      |Das Spiel schliest sich.                  |
|6.1|Das Hauptmenü ist offen.                 |Man klickt auf den "Einstellungen" Knopf      |Es öffnet sich das Einstellungen Fenster          |
|6.2|Das Einstellungen Fenster ist offen      |Man klickt auf den "Tastenbelegungen verändern" Knopf.      |Es öffnet sich das Tastenmenü  |
|6.3|Das Tastenmenü ist offen.                |Man klickt auf die Ausgabe die man Belegen will und Klickt auf die Taste die Man benutzen will.|Es steht das die Taste verändert wurde.|
|7.1|Spielgestartet, Hauptmenu ist offen         |  Man geht auf den Lautstärken regler und passt die Lautstärke an    |   Die Lautstärke wird angepass.                                 |
|8.1|Das Spiel ist gestartet, Haupmenu ist offen                | Man geht auf den Knopf "Weiterer Spieler einloggen"     |  Man hat die Möglichkeit einen weiteren Spieler einzuloggen                                  |
|9.1|Spiel ist gestartet, man ist schon weit im Game               | Man nimmt eine Spezialmüze auf      |   Man hat für eine gewisse Zeit eine Spezialeigenschaft.                                 |
|10.1|Spiel ist gestartet, Shop offen               |  Man wällt den Skin und oder die Spezialfähigkeit aus und kauft sie sich mit Münzen oder Geld| Man hat Skin und oder Spezialeigenschaft im Inventar.                                    |
|11.1|Spiel ist gestartet, Spiel ist durchgespielt            |  Menu öffnen und auf "Spiel Neustart" drücken    |       Spiel wird neu gestartet                             |
|12.1|    Spiel gestartet, in einem Level |  Man Stribt    |      Man spannt am letzen Checkpoint                              |
|13.1|    Spiel gestartet, in einem Level am Schluss           |  Man besiegt den Endboss     |    Man kommt in das neue Level             |
|14.1|    Spiel gestartet             |   Alle Level abgeschlossen    |        Der User bekommt eine kleine Belonung                            |
|15.1|    Spiel gestartet, in einem Level             | Der Spieler nimmt eine Münze auf      |   Diese Münze wird im Menu nacher angezeigt und man kann sie benutzen                                 |








### 1.4 Diagramme

![usecaseLA1500](https://user-images.githubusercontent.com/110893394/220430797-04bcf396-6c44-4945-8e6b-f7fe7daf5490.png)

<img width="331" alt="image" src="https://user-images.githubusercontent.com/110893245/220439339-4d22c4c6-dd70-4818-963e-a6a0a1efc3b6.png">

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
|1.A|  07.03    | Leonardo      |Der User kann nach links laufen                                   | 20           |
|2.A|   07.03    | Leonardo      |Der User kann nach rechts laufen                                  | 20         |
|3.A|   14.03    | Leonardo      |Die Map bewegt sich mit dem Charakter mit                         | 35            |
|4.A|   07.03    | Leonardo      |Der User kann springen                                            | 20            |
|5.A|  07.03     | Leonardo      |Der User kann sprinten                                            | 20             |
|6.A|   14.03    | Leonardo      |Der User kann ein Figurenmenü öffnen                              | 30              |
|7.A|  14.03     | Leonardo      |Figur verändert sich nach dem Menü                                | 40              |
|8.A|    14.03   | Leonardo      |Der User kann ein Level aussuchen                                 | 50              |
|9.A|    14.03   | Leonard       |Das Level ist das ausgesuchte                                     | 45              |
|10.A|   14.03   | Leonardo      |Das einstellungs Fenster geht auf                                 | 25         |
|11.A|   14.03   | Leonardo      |Im einstellungs Fenster kann man das Hintergrundmenü aufmachen           | 25             |
|12.A|  21.03    | Leonardo      |Man kann die verschiedenen Schichten des Hintergrunds verändern          | 90              |
|13.A|   21.03   | Leonardo      |Der Hintergrund passt sich dem eingestellten Hintergrund an              | 30              |
|14.A|   21.03   | Lennard       |Der Charakter kann in eine der Röhren gehen um zu einem Level zu gelangen| 20              |
|15.A|   14.03   | Lennard       |Der  Charakter kann auf ein Hindernis springen                           | 25            |
|16.A|  14.03    | Lennard       |Der Charakter kann über Hindernisse springen                             | 30              |
|17.A|  14.03    | Lennard       |Der Charakter kann unter Hindernissen hindurchsliden                     | 45              |
|18.A|  21.03    | Lennard       |Der Charakter kann sich in der Weltenauswahl nach Links bewegen          | 45              |
|19.A|   21.03   | Lennard       |Der Charakter kann sich in der Weltenauswahl nach Rechts bewegen         | 45              |
|20.A|   21.03   | Lennard       |Der Charakter kann in der Weltenauswahl zu einem Level gehen             | 45              |
|21.A|   21.03   | Lennard       |Der Charakter kann in der Weltenauswahl in ein Level gehen, indem er in die Röhre vor dem Level springt  | 60  |
|22.A|   07.03   | Lennard       |Der User kann auf einer fligenden Plattform landen                       | 30              |
|23.A|   07.03   | Lennard       |Der User kann sich auf einer fligenden Plattform bewegen                 | 20              |
|24.A|   21.03   | Lennard       |Der User kann Spezialmünzen aufsammeln                                   | 20              |
|25.A|  14.03    | Lennard       |Der User kann im Shop Skins kaufen                                 |  35       |
|26.A|  07.03    | Marek         |Der User kann Münzen aufsammeln                               |  30             | 
|27.A|  14.03    | Marek         |Im Hintergrund gibt es eine Hintergrundebene (Himmel)                      |  20            |
|28.A|   14.03   | Marek         |Im Hintergrund gibt es eine Ebene für Bäume                       |  20           |
|29.A|  14.03    | Marek         |Im Hintergrund gibt es eine Ebene für Sterne                      |  20          |
|30.A|  14.03    | Marek         |Im Vordergrund gibt es eine Ebene für den Bäume                |   20          |
|31.A|  14.03    | Marek         |Im Vordergrund gibt es eine Ebene für Gras  |   20        |
|32.A|  14.03    | Marek         |Im Vordergrund gibt es eine Ebene für den Boden                          |  20             |
|33.A|  14.03    | Marek         |Die Ebenen erzeugen einen Parallax-Effekt      | 90              | 
|34.A|  21.03    | Marek         | Nach einem Kauf einer Charaktervariante soll der aktuelle Charakter mit dieser ersetzt werden              | 30       |
|35.A|  07.03    | Marek         |Es erscheinen Münzen in den Levels                                | 40              |
|36.A|   14.03   | Marek         |Die Anzahl eingesammelter Münzen wird während dem Spiel angezeigt.          |  60             | 
|37.A|   14.03   | Dorian        |Spezialeigenschaften von eingesammelten Münzen sind auf eine gewisse Zeitdauer beschränkt.          |  40          |
|38.A|   7.03    | Dorian        |Man hat eine Hintergrundmusik                                          | 40              |
|39.A|   14.03   | Dorian        |Der User kann im Shop Spezialeigenschaften kaufen                 | 40              |
|40.A|   21.03   | Dorian        |Der User hat verschiendene Levels zum Spielen                     | 40              |
|41.A|   21.03   | Dorian        |Der User hat eine Weltenauswahl auf der die Levels sind           | 40              |
|42.A|  14.03    | Dorian        |Der Rumpf des Charakters wird gepixelt.                           | 30             |
|43.A|  14.03    | Dorian        |Der Kopf des Charakters wird gepixelt.                            | 30              |
|44.A|  14.03    | Dorian        |Die Beine des Charakters werden gepixelt.                         | 30         |
|45.A|   14.03   | Dorian        |Die Arme des Charakters werden gepixelt.            |  30          |
|46.A|  14.03    | Dorian        |Die animation für das Schleichen des Charakters wird gepixelt.           |  90             |
|47.A|    21.03  | Dorian        |Die animation für das sliden des Charakters wird gepixelt.            | 90              |
|48.A|   21.03   | Dorian        |Verschiedene Varianten des Charakters werden gepixelt (diese können anschliessend im Münzenshop gekauft werden)|90 |        


Total:

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden
1: Wir haben uns entschieden unser Spiel mit Unity zu machen weil wir alsGruppe noch nie damit gearbeitet haben und es kennenlernen wollen.

2: Wir haben uns dazu entschieden dass wir alles wie ein Pixelart gestalten damit wir eine feste Resolution haben und damit man das Spiel auf tiefer Resolution spielen kann.

3: Wir haben uns entschieden das wir unsere Karakere selbst Zeichnen weil wird das schon können.


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |  07.03.23     |     Leonardo      |     20          |    40              |
| 2.A  |   07.03.23    |   Leonardo         |     20          |   40                |
| 3.A  |    14.03.23   |    Leonardo        |     35          |   50                |
| 4.A  |   07.03.23    |   Leonardo         |     20          |  45                 |
| 5.A  |    07.03.23   |    Leonardo        |     20          |    40               |
| 6.A  |       |   Leonardo        |      30         |                   |
| 7.A  |       |    Leonardo        |      40         |                   |
| 8.A  |       |     Leonardo       |       50        |                   |
| 9.A  |       |    Leonardo        |       45        |                   |
| 10.A |       |      Leonardo      |       25        |                   |
| 11.A |       |    Leonardo        |       25        |                   |
| 12.A |       |     Leonardo       |       90        |                   |
| 13.A |       |  Lennard         |         30      |                   |
| 14.A |   14.03.23    |   Lennard         |        25       |                   |
| 15.A | 14.03.23      |   Lennard         |        30       |    40               |
| 16.A  |  14.03.23     |  Lennard          |       45        |     50              |
| 17.A  |       |  Lennard          |       45        |                   |
| 18.A  |  07.03.23     |  Lennard          |       45        |     40              |
| 19.A  |  07.03.23     |  Lennard          |        45       |    40               |
| 2O.A  |       |  Lennard          |         60      |                   |
| 21.A  |       |  Lennard          |        30       |                   |
| 22.A  |   07.03.23    |  Lennard          |        20       |    35               |
| 23.A  |  07.03.23     |   Lennard         |        20       |      40             |
| 24.A  |       |  Lennard          |        35       |                   |
| 25.A  |       |  Lennard          |        90       |                   |
| 26.A  |  07.03.23     |   Marek        |           30    |     35              |
| 27.A  |  14.03.23     |  Marek         |          20     |        20           |
| 28.A  |  14.03.23     |  Marek         |           20    |          20         |
| 29.A  |  14.03.23     |  Marek         |           20    |            20       |
| 30.A  |   14.03.23    |  Marek         |         20      |            20       |
| 31.A  |   14.03.23    |   Marek        |           20    |            20       |
| 32.A  |  14.03.23     |  Marek         |         20      |            20       |
| 33.A  |  14.03.23     |  Marek         |         90      |       120            |
| 34.A  |  21.03.23     |   Marek        |         30      |                   |
| 35.A  |   07.03.23    |  Marek         |          40     |      30             |
| 36.A  |    07.03.23   |  Marek         |         60      |      70             |
| 37.A  |       |   Dorian        |        40       |                   |
| 38.A  | 07.03.23      |   Dorian        |         40      |    45               |
| 39.A  |       |   Dorian        |         40      |                   |
| 40.A  |       |   Dorian       |         40      |                   |
| 41.A  |       |    Dorian       |         40      |                   |
| 42.A  |07.03.23|    Dorian       |         30      |  20              |
| 43.A  |07.03.23|   Dorian        |         30      |  20              |
| 44.A  |07.03.23|   Dorian        |         30      |  20              |
| 45.A  |07.03.23|   Dorian        |         30      |  20              |
| 46.A  |14.03.23|   Dorian        |          90     |  70              |
| 47.A  |       |   Dorian        |           90    |                   |
| 48.A  |       |   Dorian        |             90  |                   |
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
