# LA1500-

# Projekt-Dokumentation

Rhododendron Leonardo Grigioni, Lennard Bühler, Marek Vonrogall, Dorian Herzig

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|  21.02.23     | 0.0.1   | Heute haben wir unser Projekt ausgewählt und mit der Projektdokumentation angefangen|
|  28.02.23     | 0.0.2     |  Heute haben wir an unserer Projektdokumentation weitergearbeitet. Wir haben uns über Unity informiert und schon die ersten Arbeitspakete erfüllt.                                                           |
|  7.03.23     | 0.0.3   |       Die ersten Arbeitspakete gemacht                                                  |
|  14.03.23     | 0.0.4   |       Weitere Arbeitspakete gemacht und Dokumentation verbessert                                                  |
|  21.03.23     | 1.0.0   |        Präsentation fertig gestellt, Arbeitspakete vervollständigt.                                                      |

## 1 Informieren

### 1.1 Ihr Projekt

Wir machen ein Jump and Run game.


Wir wollen lernen mit einer für uns neuen Technik mit Unity ein Spiel zu Programmieren. In diesem Spiel sollte man rennen und springen können. Das Spiel ist im 2D Stil gehalten. Das Ziel des Spiels ist es den Parkour zu schaffen und den Charakter sicher ins Ziel zu bringen, ohne die Spikes berühren. Wir wollen so viele Level wie möglich machen. Ebenfalls wollen wir unsere Gruppe besser kennenlernen. Wir streben auf eine gute Zusammenarbeit, trotzdessen wir uns nicht kennen.


### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
|1|muss|     Funktional|     Als User kann ich meine Figur bewegen, damit man das Spiel spielen kann|
|2|kann|     Funktional|     Als User kann ich meine Figur aussuchen, damit das Spiel nicht so langweilig ist|
|3|kann|     Funktional|     Als User kann ich mein Level aussuchen, damit man nicht nicht nur ein Level spielen kann, sondern auch andere und so Abwechslung bekommt|
|4|kann|     Funktional|     Als User möchte ich einen Hintergrund im Spiel, damit das Spiel besser aussieht|
|5|kann|     Funktional|     Als User kann ich im Menü das Spiel beenden, damit man das Spiel nicht immer offen haben muss|
|6|kann|     Funktional|     Als User kann ich die Tastenbelegungen verändern, damit verschiedene Spielertypen das Spiel mit ihren eigenen Tasten spielen können.|
|7|kann|     Funktional|     Als User kann ich die Lautstärke verändern, damit man wenn man die Musik lauter haben möchte sie lauter stellen kann und wenn man sie leiser haben möchte leiser machen kann.|
|8|kann|     Funktional|     Als User möchte ich fliegende Plattformen im Spiel haben, damit man auf diesen Plattformen hin und her springen kann um die Schwierigkeit zu erhöhen.|
|9|kann|     Funktional|     Als User kann ich Spezialmünzen im Spiel aufsammeln, welche mehr Punkte als die normalen Münzen geben, damit man schneller an Punkte kommt. |
|10|kann|    Funktional|     Als User kann ich im Shop Spezialfähigkeiten und Skins kaufen und freischalten, damit der User nicht immer nur den gleichen Skin spielen muss. |
|11|muss|    Funktional|     Als User möchte ich, dass ich Levels mehrmals spielen kann, damit man ein Level erneut spielen kann.                            |
|12|muss|    Funktional|     Als User möchte ich beim Tod des Charakters, das der Charakter respawnt.   |
|13|muss|    Funktional|     Als User möchte ich, wenn ich den Endboss eines Levels besiegt habe, in das nächste Level kommmen, damit man nicht in einem Level feststeckt sondern auch noch weitere Level spielen kann.|
|14|kann|    Funktional|     Als User möchte ich, dass wenn ich alle Level beende, eine Belohnung bekomme, damit es sich lohnt das Spiel durchzuspielen.|
|15|muss|    Funktional|     Als User möchte ich alle Münzen die ich in einem Durchlauf sammle in der oberen linken Ecke angezeigt bekommen, damit ich immer weiss wie viele Münzen ich bereits habe.|







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
|10.1|Spiel ist gestartet, Shop offen               |  Man wählt den Skin und oder die Spezialfähigkeit aus und kauft sie sich mit Münzen oder Geld| Man hat Skin und oder Spezialeigenschaft im Inventar.                                    |
|11.1|Spiel ist gestartet, Spiel ist durchgespielt            |  Menu öffnen und auf "Spiel Neustart" drücken    |       Spiel wird neu gestartet                             |
|12.1|    Spiel gestartet, in einem Level |  Man Stribt    |      Man spannt am letzen Checkpoint                              |
|13.1|    Spiel gestartet, in einem Level am Schluss           |  Man besiegt den Endboss     |    Man kommt in das neue Level             |
|14.1|    Spiel gestartet             |   Alle Level abgeschlossen    |        Der User bekommt eine kleine Belonung                            |
|15.1|    Spiel gestartet, in einem Level             | Der Spieler nimmt eine Münze auf      |   Diese Münze wird im Menu nacher angezeigt und man kann sie benutzen                                 |








### 1.4 Diagramme



<img width="619" alt="Bildschirm­foto 2023-03-21 um 08 56 26" src="https://user-images.githubusercontent.com/110892642/226546967-78546566-e5ff-46d0-a749-953911e7c09d.png">


![usecaseLA1500](https://user-images.githubusercontent.com/110893394/220430797-04bcf396-6c44-4945-8e6b-f7fe7daf5490.png)




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
|14.A|   21.03   | Lennard       |Der Spike erscheint im Level| 25             |
|15.A|   14.03   | Lennard       |Der  Charakter kann auf ein Hindernis springen                           | 25            |
|16.A|  14.03    | Lennard       |Der Charakter kann über Hindernisse springen                             | 30              |
|17.A|  14.03    | Lennard       |Der Charakter kann unter Hindernissen hindurchsliden                     | 45              |
|18.A|  21.03    | Lennard       |Im Spiel gibt es kleine Hindernisse(Spikes die schaden geben)         | 45              |
|19.A|   21.03   | Lennard       |Diese Spikes haben eine Hitbox          | 45              |
|20.A|   21.03   | Lennard       |Der Charakter kann sich auf einer fliegenden Plattform bewegen           | 45              |
|21.A|   21.03   | Lennard       |Wenn man einen dieser Spikes berührt wird man am Start gerespawnt   | 60  |
|22.A|   07.03   | Lennard       |Der User kann auf einer fligenden Plattform landen                       | 30              |
|23.A|   07.03   | Lennard       |Der User kann sich auf einer fligenden Plattform bewegen                 | 20              |
|24.A|   21.03   | Lennard       |Der User kann Spezialmünzen aufsammeln                                   | 20              |
|25.A|  14.03    | Lennard       |Wenn der User eine Münze aufsammelt verschwindet diese verschwinden                                |  35       |
|26.A|  07.03    | Marek         |Der User kann Münzen aufsammeln                               |  30             | 
|27.A|  14.03    | Marek         |Im Hintergrund gibt es eine Hintergrundebene (Himmel)                      |  20            |
|28.A|   14.03   | Marek         |Im Hintergrund gibt es eine Ebene für Bäume                       |  20           |
|29.A|  14.03    | Marek         |Im Hintergrund gibt es eine Ebene für Sterne                      |  20          |
|30.A|  14.03    | Marek         |Im Vordergrund gibt es eine Ebene für den Bäume                |   20          |
|31.A|  14.03    | Marek         |Im Vordergrund gibt es eine Ebene für Gras  |   20        |
|32.A|  14.03    | Marek         |Im Vordergrund gibt es eine Ebene für den Boden                          |  20             |
|33.A|  14.03    | Marek         |Die Ebenen erzeugen einen Parallax-Effekt      | 90              | 
|34.A|  21.03    | Marek         | Wenn man das Ziel berührt, bekommt man eine "Level Completed" Nachricht.             | 30       |
|35.A|  07.03    | Marek         |Es erscheinen Münzen in den Levels                                | 40              |
|36.A|   14.03   | Marek         |Die Anzahl eingesammelter Münzen wird während dem Spiel angezeigt.          |  60             | 
|37.A|   14.03   | Dorian        |Spezialeigenschaften von eingesammelten Münzen sind auf eine gewisse Zeitdauer beschränkt.          |  40          |
|38.A|   7.03    | Dorian        |Man hat eine Hintergrundmusik                                          | 40              |
|39.A|   21.03   | Dorian        |Der User kann im Shop Spezialeigenschaften kaufen                 | 40              |
|40.A|   21.03   | Dorian        |Der User hat verschiendene Levels zum Spielen                     | 40              |
|41.A|   21.03   | Dorian        |Der User hat eine Weltenauswahl auf der die Levels sind           | 40              |
|42.A|  14.03    | Dorian        |Der Rumpf des Charakters wird gepixelt.                           | 30             |
|43.A|  14.03    | Dorian        |Der Kopf des Charakters wird gepixelt.                            | 30              |
|44.A|  14.03    | Dorian        |Die Beine des Charakters werden gepixelt.                         | 30         |
|45.A|   14.03   | Dorian        |Die Arme des Charakters werden gepixelt.            |  30          |
|46.A|  14.03    | Dorian        |Die animation für das Schleichen des Charakters wird gepixelt.           |  90             |
|47.A|    21.03  | Dorian        |Die animation für das sliden des Charakters wird gepixelt.            | 90              |
|48.A|   21.03   | Dorian        |Der Spike wird gepixelt|20 | 20       


Total:



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
| 6.A  |    14.03.23   |   Leonardo        |      30         |                   |
| 7.A  |    14.03.23   |    Leonardo        |      40         |                   |
| 8.A  |   14.03.23    |     Leonardo       |       50        |                   |
| 9.A  |   14.03.23     |    Leonardo        |       45        |                   |
| 10.A |     14.03.23   |      Leonardo      |       25        |                   |
| 11.A |    14.03.23    |    Leonardo        |       25        |                   |
| 12.A |   21.03.23     |     Leonardo       |       90        |                   |
| 13.A |   21.03.23     |  Lennard         |         30      |                   |
| 14.A |   21.03.23    |   Lennard         |        25       |                   |
| 15.A | 14.03.23      |   Lennard         |        30       |    40               |
| 16.A  |  14.03.23     |  Lennard          |       45        |     50              |
| 17.A  |  14.03.23      |  Lennard          |       45        |                   |
| 18.A  |  07.03.23     |  Lennard          |       45        |     40              |
| 19.A  |  07.03.23     |  Lennard          |        45       |    40               |
| 2O.A  |    21.03.23   |  Lennard          |         60      |       55            |
| 21.A  |   14.03.23    |  Lennard          |        30       |                   |
| 22.A  |   07.03.23    |  Lennard          |        20       |    35               |
| 23.A  |  07.03.23     |   Lennard         |        20       |      40             |
| 24.A  |    21.03.23    |  Lennard          |        35       |     50              |
| 25.A  |    14.03.23    |  Lennard          |        90       |     75              |
| 26.A  |  07.03.23     |   Marek        |           30    |     35              |
| 27.A  |  14.03.23     |  Marek         |          20     |        20           |
| 28.A  |  14.03.23     |  Marek         |           20    |          20         |
| 29.A  |  14.03.23     |  Marek         |           20    |            20       |
| 30.A  |   14.03.23    |  Marek         |         20      |            20       |
| 31.A  |   14.03.23    |   Marek        |           20    |            20       |
| 32.A  |  14.03.23     |  Marek         |         20      |            20       |
| 33.A  |  14.03.23     |  Marek         |         90      |       120            |
| 34.A  |  21.03.23     |   Marek        |         30      |       30            |
| 35.A  |   07.03.23    |  Marek         |          40     |      30             |
| 36.A  |    07.03.23   |  Marek         |         60      |      70             |
| 37.A  |    14.03.23    |   Dorian        |        40       |                   |
| 38.A  | 07.03.23      |   Dorian        |         40      |    45               |
| 39.A  |   21.03.23     |   Dorian        |         40      |                   |
| 40.A  |   21.03.23     |   Dorian       |         40      |                   |
| 41.A  |   21.03.23     |    Dorian       |         40      |                   |
| 42.A  |07.03.23|    Dorian       |         30      |  20              |
| 43.A  |07.03.23|   Dorian        |         30      |  20              |
| 44.A  |07.03.23|   Dorian        |         30      |  20              |
| 45.A  |07.03.23|   Dorian        |         30      |  20              |
| 46.A  |14.03.23|   Dorian        |          90     |  70              |
| 47.A  |   21.03.23     |   Dorian        |           90    |     90              |
| 48.A  | 21.03.23       |   Dorian        |             20  |          20         |


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |    4.04.2023   |   Funktioniert       |  Lennard      |
| 2.1  |   4.04.2023    |   Funktioniert nicht       |  Lennard      |
| 3.1  |   4.04.2023    |  Funktioniert nicht        |  Lennard      |
| 4.1  |    4.04.2023   |    Funktioniert      | Lennard       |
| 5.1  |   4.04.2023    |    Funktioniert      |  Lennard      |
| 6.1  |  4.04.2023     |   Funktioniert nicht       | Lennard       |
| 7.1  |  4.04.2023     |    Funktioniert nicht      | Lennard       |
| 8.1  |   4.04.2023    |    Funktioniert      | Lennard       |
| 9.1  |    4.04.2023   |    Funktioniert     |  Lennard      |
| 10.1  |   4.04.2023    |   Funktioniert       | Lennard       |
| 11.1  |   4.04.2023    |   Funktioniert nicht       | Lennard       |
| 12.1  |   4.04.2023    |   Funktioniert        | Lennard       |
| 13.1  |   4.04.2023    |   Funktioniert nicht       |  Lennard      |
| 14.1  |   4.04.2023    |   Funktioniert       |   Lennard     |
| 15.1  |  4.04.2023     |  Funktioniert        |  Lennard      |

`Fazit:`
Die wichtigsten Teile des Programmes sind mit Erfolg ausgegangen, somit ist unser Programm spielbar. Doch Leider konnten wir wegen geringer Zeit nicht alle unsere Wünsche für das Programm erfüllen.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    | Das Programm ist gestartet, der Spieler befindet sich in der Spielwelt.  |   Leerzeichen wird gedrückt.      |   Der Spieler springt.    		    |  Der Spieler springt.         		|
| II   | Das Programm ist gestartet, der Spieler befindet sich in der Spielwelt.  |   A wird gedrückt.      	    |   Der Spieler bewegt sich nach links.  |  Der Spieler bewegt sich nach links.       |
| III  | Das Programm ist gestartet, der Spieler befindet sich in der Spielwelt.	 |   D wird gedrückt.		    |   Der Spieler bewegt sich nach rechts.  |  Der Spieler bewegt sich nach rechts.      |
| IV   | Das Programm ist gestartet, der Spieler befindet sich in der Spielwelt und bewegt sich.  |   Die Shift-Taste wird gedrückt.  | Der Spieler erhöht seine Geschwindigkeit (Sprint).  | Der Spieler erhöht seine Geschwindigkeit (Sprint).
| V    | Das Programm ist gestartet, der Spieler befindet sich in der Spielwelt und ist soeben gesprungen und berührt den Boden nicht mehr.  | Leerzeichen wird gedrückt. | Der Spieler springt nicht, da Mehrfachsprünge nicht erwünscht sind | Der Spieler springt nicht. |
| VI   | Das Programm ist gestartet, der Spieler befindet sich in der Spielwelt und ist soeben gesprungen, während er eine Wand berührt. | Leerzeichen wird gedrückt. | Der Spieler springt nicht, da Mehrfachsprünge nicht erwünscht sind | Der Spieler springt ein weiteres mal. |
| VII  | Das Programm ist gestartet, der Spieler befindet sich in der Spielwelt links neben einem Spike. | D wird gedrückt. | Der Spieler bewegt sich in den Spike hinein und das Level wird neugestartet. Ebenfalls werden alle Münzen und der Score zurückgesetzt. | Der Spieler bewegt sich in den Spike hinein und das Level wird neugestartet. Ebenfalls werden alle Münzen und der Score zurückgesetzt. |
| VIII | Das Programm ist gestartetm der Spieler befindet sich in der Spielwelt links neben dem Ziel. | D wird gedrückt. | Der Spieler bewegt sich in das Ziel und wird zum Abschlussbildschirm teleportiert. | Der Spieler bewegt sich in das Ziel und wird zum Abschlussbildschirm teleportiert. |


## 6 Auswerten

