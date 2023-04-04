

# Lern-Bericht
Rhododendron:
Lennard Bühler, Marek von Rogall, Dorian Herzig, Leonardo Grigioni

## Einleitung

Wir haben in Unity ein Jump 'n' Run Spiel programmiert, welches dem Spiel Super-Mario ähnelt. Bei unserem Spiel muss man von einem Start über Hindernisse und Fallen springen und das Ziel erreichen.

## Was habe ich gelernt?

In diesem Projekt haben wir gelernt, wie man mit Tasteneingaben, verschiedene Bewegungen in einer 2D-Welt von Unity programmieren kann, damit unser Charakter sich bewegen kann.

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

`Video:`
[Video](LA1500-Video.mp4)

## Verifikation
* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes und des Gifs.

* `Code:` Dieser Code ist die Bewegung unseres Charakteres in unserem Programm.

* `Video:` Das Video dient zur Demonstration des Programmes.

# Reflexion zum Arbeitsprozess

👍 Bei unserer Arbeit lief gut, dass wir uns schnell in Unity einarbeiten konnten. Dadurch konnten wir schon schnell unsere ersten Arbeitspakete erledigen.

👎 Bei unserer Gruppe hatten wir das Problem, dass wir die Daten nur lokal gespeichert haben. Aufgrund dessen ist uns leider ein grosser Teil unserer Arbeit verloren gegangen. Zudem brauchten wir am Anfang einige Zeit um zu entscheiden, welches Thema wir nehmen wollten. Unsere Arbeitseinteilung war mangelhaft. Die Informieren & Planen Schritte von IPERKA sind uns nicht so gut gelungen.

**VBV**: 
Aufgrund dessen, dass einer unserer Laptops einen Schaden erlitten hat, und wir folglich einen grossen Teil unserer Arbeit verloren haben, werden wir in Zukunft die Daten regelmässig in der Cloud abspeichern, um die Daten in solch einem Fall nicht zu verlieren.
