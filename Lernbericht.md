

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

✍️ Erklären Sie kurz und bündig, inwiefern die von Ihnen verwendeten Medien zeigen, was Sie gelernt haben.

# Reflexion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
