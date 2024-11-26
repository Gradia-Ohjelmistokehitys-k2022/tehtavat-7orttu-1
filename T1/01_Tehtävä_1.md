
**RAJAPINNAT T1: Yleistä, Käsitteitä, JSON**

Kirjoita alla olevista kohdista T1.1 - T1.3 dokumentti/dokumentit Wordilla tai PowerPointilla kansioon T1 ja palauta se myös pdf-muodossa Gitiin.

Tehtäviin löydät tietoa esim osoitteesta: https://apipheny.io/free-api/

Hyvä esimerkki Jsonin käyttämisestä C# -ohjelmissa on osoitteessa: https://zetcode.com/csharp/json/

Voit etsiä muualtakin verkosta lisätietoa.

----

```
// Aja yhden kerran seuraava komento
git remote add upstream https://github.com/Gradia-Ohjelmistokehitys-k2024/Rajapinnat-PetriRaatikainenGradia

// Aja silloin tällöin 3 seuraavaa komentoa
git fetch 
git pull upstream main --allow-unrelated-histories
git merge upstream/main

// Aja edellisten jälkeen ja muutenkin joka päivä 3 seuraavaa komentoa
git add .
git commit -m "Downstreamed changes from template"
git push 
```
----

**T1.1  Ykköstehtävä: Rajapinnat - yleistä**

**a)** Lue ensin tietoa rajapinnoista edellä annetusta linkistä. Kirjoita esim. seuraavista asioista:

Mitä rajapinnat ovat? Miksi niitä tarvitaan? Mihin niitä käytetään? Mitä koet oppineesi tässä vaiheessa?
[[ Rajapinnat ovat tapa käyttää/yhdistää muihin palveluihin omasta koodistasi tai kutsua sieltä rajapinnan sovelluksen metodeita tai tapahtumia. Apeja ovat esimerkiksi Youtube API, jonka voi yhdistää vaikka Discord bottiin, jotta voi kuunnella musiikkia sen kautta Discordissa. ]]

**b)** Tutustu myös johonkin valitsemaasi rajapintaan syvemmin.

Kerro minkä rajapinnan valitsit? Miksi? Mihin sitä käytetään? Kuinka laaja rajapinta on, mitä kaikkea sillä voi tehdä? Pohdi voisiko tämä olla valitsemasi harjoitustyön aihe?
[[ Valitsin Youtube API. Valitsin sen, koska Youtube on asia mitä käytän joka päivä ja sen on hyödyllinen niin viihteen kannalta kuin tiedonsaanninkin kannalta. Sillä voi tehdä paljon ja tehdäänkin jo paljon. Voit ottaa videoiden ja kanavien tietoja(esimerkiksi nettisivu "Socialblade" näyttää kanavien ja videoiden tietoja), voit ladata videoita(esimerkiksi YTDLNIS:llä) ja striimata niitä esimerkiksi boteilla. Youtube APIn käyttö todellakin voisi olla se, jolla tekisin harjoitustyön. ]]

**c)** Ota selvää onko olemassa suomalaisia tietolähteitä, joihin on määritelty rajapinta? (Mahdollisia aiheita: Kartta/Aikataulut/Sää/Tilastot/...)
[[ Vayla.fi sivustolta löysin monia eri rajapintoja Suomesta. Se sisälsi esimerkikis road ja railway transport APIt, kuten myös water ja air transport APIt. ]]



**T1.2  Käsitetehtävä (Määritelmiä/Apua/Ohjeita/Tietoa)**

Suomenna alla olevat käsitteet/kysymykset sillä tasolla, että tiedät mistä puhutaan. Kirjoita yksi monisivuinen Word tai PowerPoint dokumentti näistä aiheita. Käytä tietolähteenä edellä annettua apipheny-linkkiä.
```
a) What is an API?
b) What is an API URL?
c) What are parameters?
d) What is an endpoint?
e) What is an API key/token?
f) What are headers?
g) What is a GET request?
h) What is a POST request?
```
[[ WORD TIEDOSTO(repositoriossa) = T1.2-VASTAUKSET ]]



**T1.3  JSON-tehtävä**
Ota selvää: mikä on Json, mihin sitä käytetään, miten c# toimii sen kanssa. Kirjoita muutaman sivun mittainen Word tai Powerpoint esitys- aiheesta. 

[[ WORD TIEDOSTO(repositoriossa) = JSON-T1.3 ]]

**Palauta tehtävät Gitiin.**