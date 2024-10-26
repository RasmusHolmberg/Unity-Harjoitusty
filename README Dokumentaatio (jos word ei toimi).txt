Pelissä on lessonien 3.1 – 3.4 toimintojen lisäksi alkuvalikko ja Game Over ruutu. 
Kun pelin käynnistää niin ensin tulee MainMenu scene jossa on valikko josta pelaaja voi painaa joko ”PLAY” tai ”QUIT” nappia. Lisäsin valikkoon myös looppaavaa taustamusiikkia. 

Quit nappi käytännössä vain tulostaa log viestin ”Quit!” näyttääkseen, että nappi toimii. 
Laitoin otsikoksi nyt vain ”SUPER EPIC RUNNER GAME” ”Hienolla” oranssilla tekstillä.

Valikon taustaksi päätin laittaa vain itse pelissä olevan taustan.  
Kun ”PLAY” nappia painetaan itse peli alkaa, se lataa ”Prototype 3” nimisen scenen jossa peli on. 

Itse pelissä hypit esteiden yli Space näppäimellä. Lisäsin peliin useita esteitä. Esteitä on viidenlaista ja niitä tulee satunnallisessa järjestyksessä. Esteet ovat erikokoisia, joten niiden yli hyppäämisessä on hieman eroa. Käytännössä esteet liikkuvat pelaajaa kohti eikä toisin päin. Samoin tausta myös liikkuu ja toistaa itseään antaen illuusion, että pelaaja liikkuu.

Ongelmia tuli kivi esteen kanssa, se oli aina osittain maan sisällä joten lisäsin rivin joka siirtää estettä hieman ylöspäin jos se sattui olemaan kivi. 
Lisäsin myös omin toimin partikkelit hyppäämistä varten. Muokkasin valmiiksi löytyvän ilotulite partikkelin niin, että se ei olisi liian silmille pistävä. 

Lessonien 3.1 – 3.4 lopputuloksessa löysin useita vikoja joten ratkoin myös niitä. Esimerkiksi pelaaja pystyi törmäämään useaan kertaan samaan esteeseen, joka aiheutti partikkelien ja äänien toistoa. Korjasin niin, että komennot eivät suoriudu, jos peli on Game Over tilassa. 
Kokeilin myös itse ladattuja ääniefektejä ja musiikkia, mutta pelissä valmiiksi olevat äänet olivat kuitenkin minusta sopivimmat. 
Lisäsin myös toiminnon joka katkaisee pelin musiikin kun on Game Over. 

Kun pelaaja törmää niin tulee ”GAME OVER!” läpinäkyvä ruutu, josta voi painaa joko ”RETRY” tai ”MENU” nappia. Retry aloittaa taas pelin samalla tavalla kuin alkuvalikossa. Menu taas vie takaisin alkuvalikkoon, josta voi edelleen painaa quit tai play. 

Painovoima painovoima painovoiam painovima. Suurin ongelma. Piti etsiä vastauksia netistä. Huomasin, että kun pelin aloittaa alusta Retry napilla, tai main menusta edeltävän Game Overin jälkeen, hyppääminen tuntui oudolta. Hypyn korkeus tuntui puolittuvan ja jokaisen uudelleen yrityksen jälkeen se vain meni huonommaksi, kunnes pelaaja uppoutui maan sisään. Tajusin, että painovoima jostain syystä nousi jokaisen uudelleen yrityksen jälkeen. Sain ratkaistua hyvin pitkän pähkäilyn jälkeen. Lisäsin erilliset komennot, jotka palauttavat painovoiman alkuperäiseen arvoonsa uudelleenkäynnistyksen jälkeen. 

Myös vielä sellainen ongelma, että multa partikkelit, jotka näkyvät pelaajan juostessa, jäivät päälle, kun pelaaja oli kaatunut eikä enää juossut. Näin kävi usein, jos esteeseen törmäsi samalla kun oli ilmassa. Lisäsin rivejä, jotka tarkistavat onko pelaaja ilmassa ja että onko Game Over jne.



