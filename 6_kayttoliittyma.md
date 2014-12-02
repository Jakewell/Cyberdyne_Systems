## Käyttöliittymä

Sovelluksen käyttöliittymät jakautuvat kolmeen osaan. Yksi osa käyttöliittymästä sisältää opettajan näkymät, toinen oppilaan näkymät ja kolmas vahtimestarin(master) näkymät. Kullakin käyttäjäryhmällä on sovelluksessa erilaiset käyttötarkoitukset.

#### Login

![Image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Login.jpg)

Kirjautumisruutuun syötetään käyttäjätunnus ja salasana. Palveluun tarvitsee kirjautua vain kerran, jonka jälkeen käyttäjä on aina sisäänkirjautuneena.

----------

#### Opettajan käyttöliittymä

----------

**1. Opettajan perusnäkymä**

![Image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Opettaja_perus.jpg)

Opettajan perusnäkymä on yksinkertainen. Siitä pääsee tehtävien palautukseen, läsnäololistaan ja karttapalveluun. Sen lisäksi näkymässä ovat oppilaitoksen ja sovelluksen kehittäjän logot. Opiskelijan saapuessa luokkaan ruudulle avautuu automaattinen ilmoitus kyseisen opiskelijan tiedoista. Tässä kohtaa hän myös rekisteröityy automaattisesti kurssin läsnäololistalle.

----------

**2. Automaattinen ilmoitus läsnäolosta**

![Image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Opettaja_saapuminen.jpg)

Automaattisessa ilmoituksessa on profiili kyseisestä opiskelijasta. Ilmoitus häviää ruudulta automaattisesti hetken kuluttua. Vaihtoehtoisesti näkymän voi myös pyyhkaistä sormella kuvaruudun reunan yli, jolloin palataan perusnäkymään.

----------

**3. Tehtävien palautukset**

![Image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Opettaja_tehtpalautus.jpg)

Tässä näkymässä on listattuna kurssille ilmoittautuneiden nimet, sekä merkattuna palautetut tehtävät. Takaisin-painikkeella pääsee takaisin opettajan perusnäkymään.

----------

**4. Läsnäololista**

![Image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Opettaja_lasnaolo.jpg)

Läsnäololista on lähes identtinen tehtävien palautukset -näkymän kanssa. Läsnäololistaan tulee merkintä opiskelijan kohdalle automaattisesti, kun tämä saapuu opetustilaan. Takaisin perusnäkymään pääsee takaisin-painikkeella.

----------

**5. Karttanäkymä**

![Image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Opettaja_kartta.jpg)

Karttanäkymässä opettaja näkee nykyisen ja tulevan työtilan, jossa hänen kuuluu opettaa. Työtila on korostettu oppilaitoksen pohjapiirrokseen eri värillä.

----------

#### Opiskelijan käyttöliittymä

----------

**1. Perusnäkymä (karttanäkymä)**

![Image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Oppilas_kartta.jpg)

Opiskelijalla on sovelluksen osalta myös muutamia palveluita. Perusnäkymässä hän voi nähdä sijaintinsa oppilaitoksen pohjapiirustuksessa. Samalla kartassa näkyy myös seuraavan oppitunnin sijainti, joka haetaan lukujärjestyksen ja tämänhetkisen ajan tiedoista. Perusnäkymästä pääsee myös tarkastelemaan itsellä lainassa olevia kirjoja.

----------

**2. Kirjan lainaus**

![Image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Oppilas_lainaus.jpg)

Kirjaa lainattaessa mobiililaite voidaan sijoittaa kirjan viereen, jolloin radiotaajuuksilla haettavat teoksen tiedot avautuvat näytölle. Tämän jälkeen käyttäjä voi lainata kyseisen teoksen yhdellä napin painalluksella. Tämän jälkeen näkymä palautuu perusnäkymään.

----------

**3. Lainatut kirjat**

![Image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Oppilas_lainatut.jpg)

Tässä näkymässä on listattuna itsellä lainassa olevat teokset, sekä niiden eräpäivät. Takaisin-painikkeesta pääsee perusnäkymään.

----------

#### Vahtimestarin(master) käyttöliittymä

----------

**1. Perusnäkymä (karttanäkymä)**

![Image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Vahtimestari_perus.jpg)

Vahtimestari voi nähdä karttapalvelussaan kaikkien sovellusta käyttävien sijainnin. Näin ollen hän voi seurata esimerkiksi mahdollisia epäilyttäviä tilanteita kampusalueella, sekä tarkistaa nopeasti onko oppilaitoksessa ihmisiä vielä sulkemisaikaan.
