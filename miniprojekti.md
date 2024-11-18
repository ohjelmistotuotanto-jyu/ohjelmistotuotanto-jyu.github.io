---
layout: page
title: Miniprojekti
permalink: /miniprojekti/
---

### Johdanto

- Kurssin viikoilla 4-8 tehdään miniprojekti
- **Kurssin läpipääsy edellyttää hyväksyttyä osallistumista miniprojektiin** tai sen [hyväksilukemista](/osa0#miniprojektin-hyv%C3%A4ksilukeminen)

- Projekti tehdään noin 5 hengen ryhmissä
- Projektissa ohjelmoidaan jonkin verran, **pääpaino ei ole ohjelmoinnissa** vaan systemaattisen prosessin (tästä lisää myöhemmin) noudattamisessa.
- **Jokaisen ryhmän jäsenen on tarkoitus tehdä kunkin sprintin aikana töitä noin 6 tuntia projektin eteen**
  - Asiakastapaamisiin menevää aikaa ei lasketa viikoittaiseen työaikaan!
- Ryhmä tekee kussakin sprintissä sen minkä se sprinttiin varatussa ajassa pystyy tekemään, ei enempää eikä vähempää
  - Kuuden tunnin työajan reilu ylittäminen siis **ei ole** järkevää, se on suorastaan kiellettyä

### Ryhmän muodostaminen

Täytä ryhmien muodostamisessa käytettävä lomaka viimeistään keskiviikkona 20.11. Lomake löytyy [täältä](https://tim.jyu.fi/view/kurssit/tie/teka3003/ohjelmistotuotanto-s2024/ajanvaraus). Ryhmät ja ryhmien tapaamisajat julkaistaan torstaina (21.11.). Ensimmäiset tapaamiset ovat heti seuraavalla viikolla. Ensimmäinen tapaaminen voi kestää enemmän, kuin puoli tuntia (tapaaminen jatkuu puoli tuntia valitsemasi ajan jälkeen - tai aloitetaan puoli tuntia aikaisemmin) 

- Ensimmäiseen tapaamiseen tullessa on syytä tuntea materiaalin osien 1 ja 2 asioista ainakin seuraavat:
  - Scrum
  - sprintti
  - user story
  - product backlog
  - sprint backlog
  - hyväksymäkriteeri
  - definition of done
- Tämä dokumentti ja miniprojektin ensimmäiseen asiakastapaamiseen mennessä julkaistavat arvosteluperusteet kannattaa lukea huolellisesti
<!--
 [arvosteluperusteet](/miniprojektin_arvosteluperusteet) on myös syytä lukea huolellisesti ennen aloitustilaisuutta
-->

### Hankkeen alustava kuvaus

[kuvaus](/speksi/)

### Työn eteneminen

Seuraavien viikkojen asiakastapaaminen (sprintin katselmointi ja uuden sprintin suunnittelu) tapahtuu saman 2h sisällä missä aloitustilaisuus pidetään. Tilaisuuden kesto on 30 minuuttia. 

#### viikko 4 (18.11. alkava viikko)

- Ryhmä muodostuvat/muodostetaan
- Kaikille ryhmille yhteisenä tehtävänä ennen ensimmäistä tapaamista versionhallinnan pystyttäminen ja alustavan backlogin laatiminen

#### viikko 5

- Ensimmäinen tapaaminen
- Vaatimusten tarkempi kartoitus ja ensimmäisen sprintin suunnittelu

#### viikko 6

- Sprintin 1 katselmointi ja sprintin 2 suunnittelu

#### viikko 7 

- Sprintin 2 katselmointi, retrospektiivi ja sprintin 3 suunnittelu

#### viikko 8 

- Loppudemot


### Toteutettava ohjelmisto

Esitellään alustavasti perjantain 19.11. luennolla ja tarkemmin ensimmäisessä asikastapaamisessa.

### Tekniset ja prosessiin liittyvät vaatimukset

- Ryhmä laatii yhdessä asiakkaan kanssa _product backlogin_
  - Vaatimukset kirjataan backlogiin user storyinä
- Sprintin suunnittelun yhteydessä ryhmä sitoutuu toteuttamaan sopivan määrän backlogin kärjessä olevista user storyistä
  - Jokaisen ryhmäläisen "työaika" on 6 tuntia viikossa
    - Työajan ylittävä sankarikoodaus ei ole suositeltavaa, se on jopa kiellettyä
  - Ryhmä sitoutuu ainoastaan niihin storyihin, jotka se kuvittelee kykenevänsä toteuttamaan sprintissä **definition of donen** määrittelemällä laatutasolla. Definition of done on määritelty alla
  - Kannattaa huomata, että storyihin sitoutuminen ei tarkoita sitä, että ne on pakko tehdä valmiiksi. Ohjelmistoja tehdessä sattuu ja tapahtuu ennakoimattomia asioita, ja aina suunnitelmat eivät toteudu.
  - Asiakkaalle ei kannata luvata liikaa, ja varsinkin ensimmäisten sprinttien aikana arvioissa on otava varovainen, konfiguroimiseen, testaamiseen ja ryhmän järjestäytymiseen tulee kulumaan paljon aikaa
- Ryhmä ylläpitää _sprint backlogia_
  - User storyt jaetaan sprintin suunnittelussa teknisen tason tehtäviksi eli _taskeiksi_ jotka sijoitetaan sprint backlogiin
  - Ryhmä tekee päivittäin jäljellä olevan työajan arviointia ja dokumentoi tämän sprintin burndown-käyränä
  - Sprint backlogista tulee ilmetä kunkin taskin osalta
    - jäljellä olevan työajan estimaatti
    - taskin tila (esim. aloitettu, ohjelmoitu, testauksessa, valmis)
    - taskin tekijä(t)
- Ryhmä toteuttaa jatkuvaa integraatiota (continuous integration)
  - Oletusarvoisesti kannattaa käyttää laskareista 1 tuttua GitHub Actionsia
- Koodi on talletettu GitHubiin (tai muuhun versionhallintaan, jonne asiakkaalla on pääsy)
- Projektin GitHub-repositoriolla on järkevä README.md

#### Product ja sprint backlog

- Backlogissa vaatimukset ilmaistaan järkevästi muotoiltuna user storyinä
  - **miniprojektissa ei ole tarvetta estimoida user storya**, ainoastaan sprintissä olevien taskien työmäärä estimoidaan
- Kuten edellä todettiin sprint backlogista tulee ilmetä kunkin taskin osalta
  - jäljellä olevan työajan estimaatti
  - taskin tila (esim. aloitettu, ohjelmoitu, testauksessa, valmis)
  - taskin tekijä(t)
- Backlogit voi toteuttaa esim. Google Docs -spreadsheetinä, mallia voi ottaa seuraavista:
  - erään ohtuprojektin [backlogit](https://docs.google.com/spreadsheets/d/13RzIZI2NFFuV0zdRjrrfoC-CrootK8AZNuHS571Wlxo/edit#gid=1)
  - <http://www.mountaingoatsoftware.com/scrum/sprint-backlog> (tämä on sikäli huono, että siitä eivät ilmene taskin tekijät)
- Backlogit voi tehdä Google Docsin sijaan myös johonkin backlogien ylläpitämiseen tarkoitettuun työkaluun
  - kannattaa varmistaa, että työkalu kuitenkin tukee edellä lueteltuja vaatimuksia

#### Definition of done

Seuraavassa lähtökohta definition donelle. Ryhmän tulee määritellä GitHub-repositorioon oma, omiin lähtökohtiin sopiva DoD

- User storyille tulee määritellä hyväksymiskriteerit, jotka dokumentoidaan sprintistä 2 alkaen [Robot-frameworkin](/robot_framework/) syntaksilla
  - hyvänä käytänteenä on laittaa README:stä linkki hyväksymäkriteerit määritteleviin tiedostoihin
- Toteutetun koodin testikattavuuden tulee olla kohtuullinen
- Asiakas pääsee näkemään koko ajan koodin ja testien tilanteen CI-palvelusta
- Koodin ylläpidettävyyden tulee olla mahdollisimman hyvä
  - järkevä nimeäminen
  - järkevä/selkeä ja perusteltu arkkitehtuuri
  - yhtenäinen koodityyli (noudattaa pylintin avulla määriteltyjä sääntöjä)

#### Repositorio ja README

README:ssa tulee löytyä ainakin seuraavat asiat:

- Linkit backlogeihin (backlogeista tulee olla luettavissa olevat versiot julkisessa internetissä)
- Linkki CI-palveluun
- Linkki sovelluksen toimivaan versioon (jos sovellus on verkossa)
- Jos kyse työpöytäsovelluksesta, tulee ohjelmalle olla asennus- ja käyttöohje
- Työlle tulee määritellä lisenssi <https://help.github.com/articles/licensing-a-repository/>

### Vihjeitä ryhmätyöskentelyyn

Melko varma resepti epäonnistumiseen on huono kommunikaatio. Tehkää siis asioita mahdollisimman paljon yhdessä, mieluiten paikanpäällä tai jos se ei onnistu niin esim. Discordin voice chatissa. Ylipäänsä on hyvä kommunikoida ryhmälle mitä lähtee tekemään ja milloin on saanut sen valmiiksi, tällöin vältytään päällekkäisyyksiltä. Erityisesti projektin alkuvaiheessa esim. GitHub-actionsia konfiguroitaessa yhdessä tapahtuvaan työskentelyyn kannattaa panostaa. Projektin kuluessa omatoiminenkin työskentely muuttuu jo helpommaksi jos ja kun ryhmä on sopinut työskentelyn periaatteista ja pelisäännöistä.

Pariohjelmointi/konfigurointi on havaittu erittäin hyödylliseksi. Voikin olla hyvä idea, että jokaista user storyä työstää aina kaksi henkilöä.

Jokaiselle asialle, kuten vaikkapa README.md-tiedostolle, project backlogille ja sprint backlogille kannattanee nimetä joku vastuuhenkilö joka varmistaa, että ryhmä hoitaa asian. Asian X vastuuhenkilö ei välttämättä siis tee asiaa itse, vaan varmistaa että se tulee tehdyksi.

Pitäkää ohjelma koko ajan toimintakykyisenä. On erittäin huono idea koittaa saada viikon aikana eri ihmisten koodaamat tuotokset integroitua tunti ennen asiakaspalaveria...

### Teknologisia vihjeitä

- Kokonaan uusien teknologioiden opettelu vie aina odotettua enemmän aikaa
- **Mahdollisten ulkoisten kirjastojen käyttöönotto, testien tekeminen ja CI:n konfigurointi tulee viemään ainakin alussa todella paljon aikaa**
- Komentoriviltä toimiva sovellus on teknologioiden suhteen riskittömin vaihtoehto
  - **HUOM:** Komentoriviltä toimivat sovellukset on syytä tehdä siten, että niiden IO-operaatiot eli tulostaminen ja syötteen lukeminen on eriytetty omaan injektoitavaan luokkaan viikon 2 laskareissa käsitellyn [riippuvuuksien injektointi](/riippuvuuksien_injektointi_python/) -esimerkin tapaan. Jos näin ei toimita tulee sprintistä 2 alkaen tehtävä käyttöliittymän läpi tapahtuva testaus olemaan erittäin haastavaa
- Web-pohjais sovellusta ei suositella, ellei kaikilla ryhmän jäsenillä ole tästä kokemusta.
- Jos kuitenkin teette web-sovelluksen, niin tutustukaan tähän [Selenium -ohjeeseen](selenium/)
- Jos haluatte käyttää tietokantaa, on esim.  _SQLite_ hyvä vaihtoehto
  - SQLiten käyttöön Pythonilla löytyy ohjeita ainakin [Web-palvelinohjelmointi-kurssin](https://appro.mit.jyu.fi/ties4080/luennot/sqlite/) materiaalista
- Kolmansista laskareista kannattaa ottaa mallia Robot Frameworkilla tapahtuvaan storyjen testaamiseen (vaaditaan sprintistä 2 alkaen)
- Pythonin Tkinter-kirjastolla tehtyjen käyttöliittymien automatisoitu testaaminen hankalaa ja sen takia kannattaanee välttää kirjaston käyttöä

### Työn arvostelu

Arvosteluperusteet löytyvät [täältä](/miniprojektin_arvosteluperusteet/)