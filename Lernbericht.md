

# Lern-Bericht
Rhododendron:
Lennard Bühler, Marek von Rogall, Dorian Herzig, Leonardo Grigioni

## Einleitung

Wir haben in Unity einen Jump and Run Spiel programmiert das dem Spiel Super-Mario ähnelt, bei unserem Spiel muss man von einem Start über Hindernisse und Fallen springen und rennen bis man zum Ende kommt.

## Was habe ich gelernt?

In diesem Projekt haben wir gelernt, wie man mit Tasten eingaben, verschiedene Bewegungen in einer 2D-Welt von Unity programmieren kann, damit unser Charakter sich bewegen kann.

## Code-Erklärung

Als erstes wird das laufen des Charakters nach links und rechts definiert. Unity macht das quasi automatisch und es sind keine weiteren Tastenzuweisungen notwendig.
Anschliessend haben wir den Sprung des Charakters eingebaut. Dies war etwas komplizerter, da wir das unendliche Springen in der Luft vermeiden wollten.
Dazu haben wir zwei Funktionen erstellt. OnCollisionExit2D() soll schauen ob der Spieler den Boden verlässt. Wenn dies geschehen ist, kann der Spieler erst wieder springen, wenn durch die Funktion OnCollisionEnter2D() festgestellt wurde, dass der Spieler den Boden wieder berührt hat.
Ausserdem kann unser Chrakter sprinten. Um dies zu erreichen, erhöhen wir die Bewegungsgeschwindigkeit, wenn die Shift-Taste gedrückt wird, und setzten die Bewegungsgeschwindigkeit wieder auf den ursprünglichen Wert zurück, wenn diese nicht mehr gedrückt wird.

`Code:`

``` C#
    {
        Move = Input.GetAxis("Horizontal");

        rb.velocity = new Vector2(speed * Move, rb.velocity.y);

        if (Input.GetButtonDown("Jump") && isJumping == false)
        {
            rb.AddForce(new Vector2(rb.velocity.x, jump), ForceMode2D.Impulse);
        }

        bool sprint = Input.GetKey("left shift");
        if (sprint == true) { speed = 20; }
        else { speed = 9; }
    }
    
    private void OnCollisionEnter2D(Collision2D other)
    
    {
        if(other.gameObject.CompareTag("Floor"))
        {
            isJumping = false;
        }
    }
    
    private void OnCollisionExit2D(Collision2D other)
    
    {
        if (other.gameObject.CompareTag("Floor"))
        {
            isJumping = true;
        }
    }
```

`Video  :`
[Video](LA1500-Video.mp4)

## Verifikation
* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes und des Gifs.

* `Code:` Dieser Code ist ein Beispiel, denn man für das Programm benutzen kann.

* `Video:` Das Video dient zur Demonstration des Programmes.

# Reflexion zum Arbeitsprozess

👍In unserer Gruppenarbeit haben wir kompakt und gezielt gearbeitet, wenn ein Ziel als Gruppe zu erreichen war.

👎 Bei unserer Gruppe hatten wir das Problem, dass wir die Daten nur lokal gespeichert haben. Aufgrund dessen ist uns leider ein grosser Teil unserer Arbeit verloren gegangen. Zudem brauchten wir am Anfang einige Zeit um zu entscheiden, welches Thema wir nehmen wollten. Unsere Arbeitseinteilung war mangelhaft. Die Informieren & Planen Schritte von IPERKA sind uns nicht so gut gelungen.

**VBV**: 
Ein Verbesserungsvorschlag für uns wäre, dass wir das nächste Mal unsere Daten immer wieder in der Cloud speichern sollen, da bei uns ein Laptop einen Schaden erlitten hat und haben dadurch Datenverlust erlitten.
