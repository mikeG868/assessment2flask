# assesment-test

Tämä harjoitus käyttää Flaskia https://flask.palletsprojects.com/en/2.0.x/

## Asennus
1) Käynnistä ohjelma asentamalla riippuvuudet esimerkiksi `pip install -r requirements.txt`
2) Aja `flask run --host=0.0.0.0 --port=80 --reload`. `--reload` parametri käynnistää projektin uusiksi aina kun lähdekoodi muuttuu. Samalla resetoituu tietokanta alkuperäiseen tilaansa.
3) Avaa selain omalla koneella ja kohdista se osoitteeseen http://localhost


Taustalla on SQLLite tietokanta, joka ei vaadi käyttäjältä erillistä serveriä. Kaikki tallennetaan lokaaliin tiedostoon ja luetaan sieltä.
Syntaksi on hyvin pitkälti samankaltainen kuin PostgreSQL:ssä.

## Tehtävänanto

Asenna tämän repositoryn Python ohjelma virtuaalikoneelle GCP:n niin, että se kuuntelee porttia 80.
