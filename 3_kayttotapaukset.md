# Käyttötapaukset
#### __Järjestelmän loppukäyttäjät__
 - __Opettajat__
 - __Opiskelijat__
 - __Vahtimestari__

#### __Käyttötapauskaavio__
    * < insert here > http://i57.tinypic.com/20uslfo.png
    Inline-style: 
![alt text](http://i60.tinypic.com/xfut13.jpg "Kayttotapaus")


#### __Tärkeimmät käyttötapaukset käyttötapausskenaarioina__

#####__Opettajat__
- __Käyttötapaus:__ Opettajan luokkatilakartta
    -     __Alkutila__
        -   Kartan voi avata valitsemalla sen päävalikosta kirjautumisen jälkeen.
    -     __Tapahtuman normaali kulku__
        -   Kartta ilmestyy. Siitä näkee oman sijainnin sekä nykyisen ja seuraavan luokkatilan korostettuna. 
    -     __Mikä voi mennä pieleen?__
        -   Wi-Fi-signaali tulkitaan väärin ja sovellus kertoo käyttäjälle väärää tietoa - kalibrointivirhe.
        -   Kartassa korostettu luokkatila ei vastaa varausjärjestelmässä näkyvää tietoa.
    -     __Samanaikaisesti tapahtuvat aktiviteetit__
        -   Ei mitään samanaikasesti tapahtuvaa.
    -     __Vaihtoehtoiset kulut__
        -   Ei vaihtoehtoisia kulkuja
    -     __Lopputila__
        -   Ei tilanmuutosta.

- __Käyttötapaus:__  Läsnäololista
    -     __Alkutila__
        -   Läsnäololistan voi avata valitsemalla sen päävalikosta kirjautumisen jälkeen. 
    -     __Tapahtuman normaali kulku__
        -   Läsnäololistassa näkyy kaikki kurssille ilmoittautuneet henkilöt. Läsnäololistanäkymässä ruudulle ilmestyy lyhytkestoisina popup-näkyminä sisään kävelleiden opiskelijoiden tiedot. Opiskelijan tullessa luokkaan, hänet merkitään automaattisesti läsnäolevaksi. 
    -     __Mikä voi mennä pieleen?__
        -   Järjestelmä rekisteröi käytävällä olevat henkilöt läsnäoleviksi.
        -   Järjestelmä rekisteröi vain henkilöt joilla on järjestelmään rekisteröity puhelin mukana. Jos opiskelijalla ei ole puhelinta mukana, eikä hän muista mainita läsnäolostaan opettajalle, hänen läsnäolo saattaa jäädä merkitsemätä.
        -   Luokkatilavarausjärjestelmän ristiriita todellisen tilanteen kanssa. (Päällekäinvaraukset)
        -   Salakuljetetut puhelimet
            -   Opiskelijat salakuljettavat pakollisten oppiaineiden tunneille toisten puhelimia, jolloin järjestelmä luulee henkilön olleen paikalla, vaikka todellisuudessa näin ei ole.
    -     __Samanaikaisesti tapahtuvat aktiviteetit__
        -   Useita opiskelijoita kävelee luokkaan samanaikaisesti. Popup-näkymät jonoutuvat ja ilmestyvät peräkkäin.
    -     __Vaihtoehtoiset kulut__
        -   Opiskelijoita voidaan myös merkitä läsnäolevaksi manuaalisesti, jos heillä ei ole rekisteröityä älylaitetta.
    -     __Lopputila__
        -   Tunnin päättyessä tiedot läsnäolijoista tallennetaan tietokantaan, ja seuraavan kurssin läsnäololista ilmestyy.

- __Käyttötapaus:__  Tehtävän palautuslista - Jos tunnilla tehdään tuntitehtäviä, opettaja voi merkitä ne tehdyksi. Tehtävän palautuslista on erillään läsnäololistasta.
    -     __Alkutila__  
        -   Tehtävän palautuslistan voi avata valitsemalla sen päävalikosta kirjautumisen jälkeen. Alkunäkymässä näkyy kurssin opiskelijoiden nimet listauksena. 
    -     __Tapahtuman normaali kulku__
        -   Tehtävien tultua tehdyksi opettaja voi merkata listaan kaikki ketkä ovat tehneet tunnin tehtävät.
    -     __Mikä voi mennä pieleen?__
        -   Opettaja merkkaa tehtävän tehdyksi väärälle henkilölle.
    -     __Samanaikaisesti tapahtuvat aktiviteetit__
        -   Opettaja ei voi merkitä samanaikaisesti kahta henkilöä esim. kahdella sormella. Vain yksi kosketus rekisteröidään.
    -     __Vaihtoehtoiset kulut__
        -   Ei vaihtoehtoisia kulkuja.
    -     __Lopputila__
        -   Tunnin päätyttyä tiedot tehdyistä tehtävistä tallentuu tietokantaan.


#####__Opiskelijat:__
- __Käyttötapaus:__  Opiskelijan luokkatilakartta
    -     __Alkutila__
        -   Opiskelijan luokkatilakarttanäkymä avautuu automaattisesti kun opiskelijatili tunnistetaan. Siinä näkyy oppilaitoksen kartta, ja "Lainatut kirjat" -nappi
    -     __Tapahtuman normaali kulku__
        -   Kartassa näkyy opiskelijan sijainti rakennuksessa, sekä nykyisen, että tulevan tunnin luokkatilat korostettuna. Karttaa voi lähentää ja loitontaa. Se laskee nykyisestä sijainnista reitin nykyiseen tai seuraavaan luokkatilaan, jos käyttäjällä ei ole sillä hetkellä tuntia meneillään.
    -     __Mikä voi mennä pieleen?__
        -   Wi-Fi-signaali tulkitaan väärin ja sovellus kertoo käyttäjälle väärää tietoa - kalibrointivirhe.
        -   Kartassa korostettu luokkatila ei vastaa varausjärjestelmässä näkyvää tietoa.
    -     __Samanaikaisesti tapahtuvat aktiviteetit__
        -   Ei mitään samanaikasesti tapahtuvaa.
    -     __Vaihtoehtoiset kulut__
        -   Ei vaihtoehtoisia kulkuja.
    -     __Lopputila__
        -   Ei tilanmuutosta.

- __Käyttötapaus:__  Kirjan lainaus (kun laite kirjan vieressä)
    -     __Alkutila__
        -   Opiskelijan luokkatilakarttanäkymä avautuu automaattisesti kun opiskelijatili tunnistetaan. Siinä näkyy oppilaitoksen kartta, ja "Lainatut kirjat" -nappi. Karttanäkymässä oltaessa käyttäjä voi lainata kirjoja.
    -     __Tapahtuman normaali kulku__
        -   Käyttäjä laittaa älylaitteensa kirjaa vasten, jolloin kirjassa oleva RFID-tagi aktivoituu. Ruudulle ilmestyy ikkuna, jossa on kirjan tiedot. Se kysyy käyttäjältä haluaako hän lainata kyseisen kirjan. 
    -     __Mikä voi mennä pieleen?__
        -   Radiosignaalin luku ei toimi.
        -   Tuplalainaus?
    -     __Samanaikaisesti tapahtuvat aktiviteetit__
        -   Käyttäjällä kaksi kirjaa samanaikaisesti kädessä, ja molempien kirjojen RFID-tagit aktivoituvat. Kirjat jonoutuvat ikkunoiksi.
    -     __Vaihtoehtoiset kulut__
        -   Ei vaihtoehtoisia kulkuja.
    -     __Lopputila__
        -   Käyttäjä painaa "Lainaa" -nappia, ja tieto kirjan lainauksesta tallennetaan tietokantaan.

- __Käyttötapaus:__  Lainatut kirjat (nappula)
    -     __Alkutila__
        -   Opiskelijan luokkatilakarttanäkymä avautuu automaattisesti kun opiskelijatili tunnistetaan. Siinä näkyy oppilaitoksen kartta, ja "Lainatut kirjat" -nappi. Karttanäkymässä oltaessa käyttäjä voi lainata kirjoja.
    -     __Tapahtuman normaali kulku__
        -   "Lainassa olevat kirjat" -näkymä aukeaa käyttäjän painaessa "Lainatut kirjat" -nappia. Siitä näkee kaikkien lainassa olevien kirjojen tiedot, sekä palautuspäivämäärät. Takaisin päänäkymään pääsee painamalla "Takaisin" -napppia.
    -     __Mikä voi mennä pieleen?__
        -   Jos käyttäjä käy uusimassa lainojaan tietokoneen nettiselaimessa, tiedot eivät välttämättä päivity ruudulle heti.
    -     __Samanaikaisesti tapahtuvat aktiviteetit__
        -   Ei samanaikaisesti tapahtuvaa.
    -     __Vaihtoehtoiset kulut__
        -   Ei vaihtoehtoisia kulkuja.
    -     __Lopputila__
        -   Karttanäkymä.

#####__Vahtimestari__
- __Käyttötapaus:__  Vahtimestarin MasterMap
    -     __Alkutila__
        -   Kun vahtimestari kirjautuu sisään järjestelmään, hän siirtyy suoraan MasterMappiin
    -     __Tapahtuman normaali kulku__
        -   Vahtimestari voi seurata rakennuksessa olevia rekisteröityneitä laitteita reaaliajassa.
    -     __Mikä voi mennä pieleen?__
        -   Ei mikään.
    -     __Samanaikaisesti tapahtuvat aktiviteetit__
        -   Useiden laitteiden lokaatiotieto päivittyy järjestelmään samanaikaisesti.
    -     __Vaihtoehtoiset kulut__
        -   Ei vaihtoehtoisia kulkuja.
    -     __Lopputila__
        -   Alkutila.