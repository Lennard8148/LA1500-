

# Lern-Bericht
Rhododendron:
Lennard Bühler, Marek von Rogall, Dorian Herzig, Leonardo Grigioni

## Einleitung

Wir haben in Unity einen Jump and Run Spiel programmiert das dem Spiel Super-Mario ähnelt, bei unserem Spiel muss man von einem Start über Hindernisse und Fallen springen und rennen bis man zum Ende kommt.

## Was habe ich gelernt?

In diesem Projekt haben wir gelernt, wie man mit Tasten eingaben, verschiedene Bewegungen in einer 2D-Welt von Unity programmieren kann, damit unser Charakter sich bewegen kann.

## Code-Erklärung

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
OnCollisionExit2D ist dazu da, dass man keine Doppelsprünge macht in dem man die Taste wiederholt betätigt.
OnCollisionEnter2D ist dazu da, dass man wieder springen kann, wenn man landet.

`Gif:`

## Verifikation
* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes und des Gifs.

* `Code:` Dieser Code ist ein Beispiel, denn man für das Programm benutzen kann.

* `Gif:` Das Gif dient zur Demonstration des Programmes.

# Reflexion zum Arbeitsprozess

👍In unserer Gruppenarbeit haben wir kompakt und gezielt gearbeitet, wenn ein Ziel als Gruppe zu erreichen war.

👎 Bei unserer Gruppe hatten wir das Problem, dass wir Datenverlust erlitten haben und dadurch sind bestimmte Sachen verloren gegangen. Zudem brauchten wir einige Zeit, um zu entscheiden, welches Thema wir nehmen wollen.

**VBV**: 
