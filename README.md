Päiväkirjasovelluksen prototyyppi/raakile.

Käyttöliittymällä pystyy luomaan oman tunnuksen, joka tallentuu tietokantaan (HealthDiary) ja siitä valmistuu myös key tokeni joka on näkyvillä selaimessa inspect- työkalun avulla.
Luodulla tunnuksella (käyttäjänimi ja salasana) pystyy kirjautumaan etusivulta ja siitä käyttäjä ohjataan automaattisesti varsinaiselle päiväkirjasivulle, jossa pystyy lisäämään päiväkirjamerkinnän. 
Sivusto ilmoittaa onnistuneesta kirjautumisesta pop-up viestillä, josta painamalla "ok" siirtyy eteenpäin. 
Ilmoitus tulee myös väärästä tunnuksesta ja/ tai salasanasta. Painamalla "ok" pääsee yrittämämän kirjautumista uudelleen.

![image](https://github.com/LauraNerg/projekti24/assets/111856877/f00709b2-2a20-4dfe-9ae6-a225d5638629)

![image](https://github.com/LauraNerg/projekti24/assets/111856877/5e83d9d1-6c8b-43bc-a84a-0d6a2bfcd2be)

^ Päiväkirjasivulle pystyy kirjoittamaan tekstiä, mutta se ei ohjaa sitä eteenpäin vielä. 
'Kirjaudu ulos' nappulasta pääsee takaisin kirjautumissivulle: ns etusivulle.

![image](https://github.com/LauraNerg/projekti24/assets/111856877/b493752e-f6a4-4dc0-841b-f8d4e78de83a)

^ Tietokanta tallentaa luotuja käyttäjiä ja niiden tunnistetiedot: käyttäjäleveli, käyttäjänimi, salasana, sähköposti ja luomispäivämäärä.


Toiminnallisuudet: Käyttäjätunnuksen luominen ja sillä kirjautuminen päiväkirjasovellukseen

Kehityssuunnitelma: 
Päiväkirjasivulta tietojen lisääminen ja tallentaminen tietokantaan. 
Kirjautunut käyttäjä voi hakea omia päiväkirjamerkintöjään (= uuden välilehden luominen).

Käytetyt jutskat:

Back-end: Opettajan esimerkki serveri
Tietokanta: Opettajan esimerkki/tunnilla luotu tietokanta
Front-end: Opettajan pohja, mutta siitä itse jatkojalostettu ulkoasu ja toiminta.
