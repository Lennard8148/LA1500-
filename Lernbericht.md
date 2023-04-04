

# Lern-Bericht
Rhododendron:
Lennard Bühler, Marek von Rogall, Dorian Herzig, Leonardo Grigioni

## Einleitung

Wir haben einen Level-Runner ähnlich wie Mario programmiert.

## Was habe ich gelernt?

Wir haben gelernt wie man die Figur sich so bewegen lässt wie in Mario.

## Beschreibung

✍️ Verwenden Sie drei verschiedene Medien, um zu zeigen, was Sie gelernt haben. Zum Beispiel:

Wir haben gelernt wie man die Tastensteuerungen programmiert um die Figur so zu bewegen wie in Mario.

```
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


## Verifikation
* `Textbeschreibung:` Die Textbeschreibung dient zur Verständlichkeit des Codes und des Gifs.

* `Code:` Dieser Code ist ein Beispiel, denn man für das Programm benutzen kann.

* `Gif:` Das Gif dient zur Demonstration des Programmes.

# Reflexion zum Arbeitsprozess

👍In unserer Gruppenarbeit haben wir kompakt und gezielt gearbeitet, wenn ein Ziel als Gruppe zu erreichen war.

👎 wir hatten viele technische Probleme was dazu führte das wir arbeit verloren oder arbeit nicht alle machen konnten.

**VBV**: 
