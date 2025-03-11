# AsuntojenHinnat
Projektin kuvaus
Tämä projekti analysoi vuokrayksiöiden mediaanihintojen kehitystä Suomen suurimmissa kaupungeissa vuosien 2020–2024 aikana. Tarkastelun kohteena ovat asuntojen hintojen kehitys eri kaupungeissa sekä hintojen kokonaiskasvu suhteessa inflaatioon.
# Analyysin vaiheet

# Datan lataaminen ja esikäsittely
Asuntojen hintatiedot (AsuntojenHinnat.csv) ja inflaatiotiedot (Inflaatio.csv) luettiin Pandas-kirjaston avulla.
CSV-tiedostojen koodaukseksi määritettiin ISO-8859-1, ja erotinmerkkinä käytettiin puolipistettä.

# Vuokra-asuntojen hintakehityksen analysointi
Suodatettiin ensimmäiseksi vuoden 2020 ensimmäisen kvartaalin hintatiedot eri kaupungeista ja laitettiin ne kasvavaan järjestykseen.
Hintakehityksen visualisointiin käytettiin Seaborn-kirjastoa, jossa piirrettiin aikajanakuvio eri kaupunkien mediaanihintojen muutoksista.
Hintakehityksen laskennassa huomioitiin ensimmäisen ja viimeisimmän vuoden kvartaalin mediaanihinnat.

# Hintojen prosentuaalinen kasvulaskenta
Jokaiselle kaupungille laskettiin hintojen kokonaiskasvu prosentteina.
Kaupungit järjestettiin kasvuprosentin mukaisesti laskevaan järjestykseen.

# Inflaation vaikutuksen analysointi
Inflaatiodatan perusteella laskettiin vuosittainen prosentuaalinen inflaatiomuutos.
Kokonaisinflaatio vuosien 2020-2024 välillä laskettiin vertailtavaksi asuntojen hintakehitykseen.

# Tärkeimmät tulokset
Tampere, Oulu ja Turku kokivat suurimman prosentuaalisen nousun yksiöiden neliöhinnoissa.
Helsinki ja Lahti kokivat suhteessa pienemmän hintakehityksen.

# Käytetyt teknologiat
Python (pandas, seaborn, matplotlib)
CSV-datan käsittely ja analysointi Pandas-kirjastolla
Tietojen visualisointi Seabornilla ja Matplotlibilla
Data-analyysi hintakehityksen ja inflaation vertailuun
