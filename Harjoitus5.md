### 1. Selitä seuraavat käsitteet ###

1. Näkymä on se osa käyttöliittymää, jonka käyttäjä näkee. Näkymä saattaa sisältää esim. valikkoja, tekstiä, kuvia jne.

2. Wireframe on käyttöliittymästä luotu rautalankamalli, jossa näkyy esim. osien ääriviivat. Se on eräänlainen luonnos.

3. Mockup on skaalattu tai täysikokoinen luonnos, jota voidaan käyttää esim. esittelemään tuotetta tai ohjelmistoa.

4. Prototyyppi on mockup, jolla on kuitenkin toiminnallisuutta ja sitä voidaan testata.


### 2. Käyttöliittymän näkymät ###

1. Käyttöliittymät ja käyttötapaukset voidaan yhdistää demonstroimalla, miten käyttöliittymä muuttuu eri käyttötapauksissa. Esimerkiksi oppilaan ja opettajan näkymät ovat erilaiset samassa sovelluksessa, kun oppilas saapuu opetustilaan.

2. 
    - Opettajan päänäkymä
    - Läsnäoloilmoitus opettajan näkymään
    - Oppilaan karttanäkymä
    - Oppilaan kirjastonäkymä

3. Opettajan näkymä on oleellisin. Sovellukseen tarvitsee kirjautua vain kerran. Tämän jälkeen sovellus siirtyy oletusnäkymään. Oletusnäkymässä ruudulla ei ole paljoa informaatiota, ainoastaan oppilaitoksen logo yms. Kun opiskelija saapuu opetustilaan, opettajan näytölle ilmestyy opiskelijan kuva ja tietoa hänestä. Tässä vaiheessa opiskelija rekisteröityy automaattisesti läsnäolevaksi. Opettaja voi myös siirtyä tehtävienpalautustilaan, jossa voi nopeasti merkata kurssin palautetut tehtävät. Päänäkymästä pääsee myös läsnäololistaan.

    Opiskelijan näkymässä on oppilaitoksen kartta, josta voi tarkistaa esimerkiksi seuraavan oppitunnin sijainnin. Alapalkista löytyy oma näkymä, joka aukeaa kartan päälle. Tästä näkymästä löytää lainaamansa oppikirjat. Itse kirjojen lainaus tapahtuu käyttämällä puhelinta kirjan päällä ja painamalla ruudulle ilmestyvää "Ok" -nappulaa.

4. 
- Opettaja:
	- Päänäkymä -> Automaattinen ilmoitus opiskelijan läsnäolosta
	- Päänäkymä -> Tuntitehtävienpalautusnäkymä
	- Päänäkymä -> Läsnäololista

- Oppilas:
	- Karttanäkymän alapalkki -> Kirjastonäkymä
	
- Visualisoinnit:
	- Uusi näkymä työntää vanhan näkymän esim. yläreunan kautta pois

5. 
- Opettaja:
	- Perusnäkymä: Applikaation logo + kuvakkeet toisiin näkymiin
	- Opiskelija saapuu luokkaan: Kuva, nimi, ryhmä, tunnus, muuta tietoa + viesti alalaidassa
	- Tuntitehtävienpalautus: Nimilista, jossa on ainoastaan läsnäolijat + voidaan merkata tehtävät tehdyksi
	- Läsnäololista: Kaikki kurssin opiskelijoiden nimet + merkkausmahdollisuus
	
- Oppilas:
	- Karttanäkymä: Oppilaitoksen kartta
	- Kirjastonäkymä: Lista lainatuista kirjoista + palautuspäivä yms. Lisäksi: Kirjaa lainattaessa näytölle ilmestyy viesti ja hyväksymisnappi.
	
### 3. Visualisointi ###
