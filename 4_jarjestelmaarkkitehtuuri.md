##  Järjestelmäarkkitehtuuri

Järjestelmän olennaisena osana toimii langaton verkkoyhteys. Sen avulla voidaan paikantaa opettajat, oppilaat sekä vahtimestari. Karttapalvelu on olennainen osa jokaista käyttäjäryhmää, ja toimiakseen oikein se vaatii toimivan verkkoyhteyden. Kartat päivittyvät reaaliajassa, joten verkkoyhteyksiin on kiinnitettävä erityistä huomiota.

Tietokanta on myös tärkeä osa järjestelmää. Käyttäjätunnukset, salasanat ja muutkin tiedot tallentuvat Cyberdyne Systemsin tietokantaan. Oppilaitoksen vahtimestari(master) voi pyytää Cyberdyne Systemsin tietokannasta haluamiaan tietoja. Tiedot on jäsennelty tietokannassa tarkimmillaan opiskelijakohtaisesti. Tietoja voi myös pyytää esimerkiksi kursseittain jäsenneltynä.

Kontrolli/logiikkakerroksessa on sovelluksen toiminnallinen osa. Siinä suoritetaan käyttäjän tekemät tapahtumat, hallinnoidaan logiikkaa ja suoritetaan sovelluksen koodia.

Käyttöliittymä on päällimmäisin kerros, joka näkyy käyttäjälle. Sen toiminnot ovat suoraan kytköksissä kontrolli/logiikkakerrokseen.

![image](https://github.com/Jakewell/Cyberdyne_Systems/blob/master/Jarjestelma.jpg)
