---
layout: page
title: Miniprojektin arvosteluperusteet
inheader: no
permalink: /miniprojektin_arvosteluperusteet/
---

- [Valmistautuminen ensimmäiseen tapaamiseen](/miniprojektin_arvosteluperusteet#valmistautuminen-ennen-ensimmaista-sprinttia)
- [Ensimmäisen sprintin arvosteluperusteet](/miniprojektin_arvosteluperusteet#ensimmäisen-sprintin-arvosteluperusteet)
- [Toisen sprintin arvosteluperusteet](/miniprojektin_arvosteluperusteet#toisen-sprintin-arvosteluperusteet)
- [Kolmannen sprintin arvosteluperusteet](/miniprojektin_arvosteluperusteet#kolmannen-sprintin-arvosteluperusteet)

<!--
Miniprojektista saa maksimissaan 11 kurssipistettä seuraavien kriteereiden ja periaatteiden mukaan (kurssin eri osioista saatavat pisteet skaalataan ennen kokonaisarvosanan muodostamista)
-->
- Jokaisesta sprintistä on jaossa **ryhmälle** 2.5 kurssipistettä
  - Ensisijainen arvostelukriteeri on prosessin seuraaminen, tasainen eteneminen ja ohjelmaan toteutettujen ominaisuuksien laatu
  - Toteutettujen ominaisuuksien määrän merkitys arvostelussa on aika pieni mutta ei toki nolla, eli jotain koodiakin tulee tehdä
  - Tarkemmat sprinttikohtaiset arvosteluperusteet alla
- Henkilökohtainen suoriutumisesta on jaossa -1p ... 1, poikkeustapauksissa -2p tai 2p on mahdollinen
  - Henkilökohtaisen suoriutumisen pisteet perustuvat lopussa tehtävään vertaisarvioon sekä ryhmän repositoriosta ja backlogeilta näkyvään "digitaaliseen jalanjälkeen"
  - Henkilökohtaista suoriutumista arvioidessa arvostetaan seuraavia asioita:
    - Fyysistä ja henkistä läsnäoloa
    - Aktiivista otetta
    - Luotettavuutta
    - Ryhmätyön sujuvuutta
    - Työskentelyn tasaisuutta
    - Kontribuutiota ryhmän tuotoksiin (koodi, testit, deployment pipeline, backlogit)
      - [varmista, että committisi näkyvät githubissa oikein](/miniprojektin_arvosteluperusteet#varmista-että-commitisi-näkyvät-githubissa-oikein)
  - **Sankarikoodauksella ei voi kompensoida muuten puutteellista ryhmätyöskentelyä**
  - Kannattaa myös ottaa tosissaan noin 6 tunnin sprinteittäinen työaika. Työajan reilu ylitys ei tuo "lisäpisteitä" vaan pikemminkin päinvastoin.

Perusteeton osallistumattomuus johonkin sprinttiin johtaa miniprojektisuorituksen hylkäämiseen.

Alla olevat sprinttien arvosteluperusteet ovat suuntaa antavia ja arvotelussa pyritään ottamaan huomioon ennen kaikkea kokonaisuus. 

### Valmistautuminen ennen ensimmäistä sprinttiä

Ennen ensimmäistä sprinttiä pyri huolehtimaan seuraavista

- Ryhmällä on yhteinen repositorio, jonne kaikilla on pääsy. Repositoriossa on vähintään README tiedosto, jonne sprinteissä tarvittavat tiedot voidaan myöshemmin litäsä (esim. ajankäytön seuranta).
- Ryhmällä on yhteinen viestintäkanava ja ryhmä on sopinnut työtavoistaan.
- Ryhmällä on alustava backlog
  - Backlogit voi toteuttaa esim. Google Docs -spreadsheetinä, mallia voi ottaa seuraavista:
    - erään ohtuprojektin [backlogit](https://docs.google.com/spreadsheets/d/13RzIZI2NFFuV0zdRjrrfoC-CrootK8AZNuHS571Wlxo/edit#gid=1)
    - <http://www.mountaingoatsoftware.com/scrum/sprint-backlog> (tämä on sikäli huono, että siitä eivät ilmene taskin tekijät)
  - Backlogit voi tehdä Google Docsin sijaan myös johonkin backlogien ylläpitämiseen tarkoitettuun työkaluun
    - kannattaa varmistaa, että työkalu kuitenkin tukee edellä lueteltuja vaatimuksia


### Ensimmäisen sprintin arvosteluperusteet

Jokaisen ryhmäläisen on oltava rekisteröitynyt projektiin viimeistään ensimmäisen sprintin lopuksi pidettävässä asiakastapaamisessa.

Linkit projektin backlogeihin ja muihin dokumentteihin, ja GitHub Actionsiin (tai muuhun käytössä olevaan CI-palveluun) tulee laittaa projektin GitHub-repositorion README:hen!

Pisteitä kertyy seuraavista asioista:

- (0.25p) product backlog
  - Backlog on DEEP (storyjä ei tarvitse estimoida)
- (0.5p) sprintin 1 backlog
  - Sprintiin valitut user storyt jaettu teknisen tason taskeiksi
  - Päivittäinen jäljellä oleva työmäärä arvioitu taskeittain
  - Sprintin burndown-käyrä olemassa
  - Jokaiseen taskiin on merkitty sen tekijä(t)
  - Taskin status on näkyvissä (esim. todo, doing, done)
- (0.25p) sprintiin 1 valittujen user storyjen hyväksymiskriteerit kirjattu
- (0.25p) testaus
  - Toteutettua koodia on yksikkötestattu kohtuullisella tasolla
- (0.25p) jatkuva integraatio
  - Koodi GitHubissa
  - GitHub Actions (tai jokin muu CI-palvelu) suorittaa yksikkötestit ja ne menevät läpi
- (0.25p) toteutus
  - Ainakin _yksi_ sprintin tavoitteeseen sovituista storyista toteutettu _definition of donen_ mukaisella tasolla
- (0.25p) työtä tehty tasaisesti
  - Kaikki työ ei saa olla yhtenä päivänä tehty
- (0.25p) GitHub README:
  - README:sta löytyy linkki backlogeihin (ja niihin on _kaikilla_ lukuoikeudet)
  - Definition of done kirjattu eksplisiittisesti
  - Linkki sovellukseen jos kyse web-sovelluksesta
  - Jos kyse työpöytäsovelluksesta: ohjelman asennus- ja käyttöohje
- (0.25p) sprintin katselmointiin on valmistauduttu asiallisesti
  - Katselmoinnin pitäjä on sovittu ja tarvittavat esivalmistelut on tehty etukäteen
  - Katselmoinnin aikana asiakkaalle demonstroidaan ne sprinttiin valitut user storyt jotka on toteutettu hyväksymiskriteerien mukaisesti

Sprintin maksimi on 2.5 pistettä.

### Toisen sprintin arvosteluperusteet

Pisteitä kertyy seuraavista asioista:

- (0.25p) product backlog
  - Backlog on DEEP (storyjä ei tarvitse estimoida)
- (0.25p) sprintin 2 backlog
  - Sprintiin valitut user storyt jaettu teknisen tason taskeiksi
  - Päivittäinen jäjellä oleva työmäärä arvioitu taskeittain
  - Burndown-käyrä olemassa
  - Jokaiseen taskiin on merkitty sen tekijä(t)
- (0.25p) sprintiin 2 valittujen storyjen hyväksymisehdot kirjattu
- (0.25p) kattavahko automatisoitu testaus yksikkötasolla
- (0.25p) ainakin osa storeista testattu storytasolla (Robot-frameworkilla)
- (0.25p) jatkuva integraatio
  - CI-palvelu suorittaa testit
  - main-branch ei ole hajonnut
- (0.125p) GitHubin README:stä linkki testikattavuusraporttiin
- (0.25p) projektille määritelty järkevät Pylint-säännöt jotka tarkistetaan CI:n toimesta
- (0.25p) suurin osa sprintin user storyistä toteutettu definition of donen mukaisella tasolla
- (0.125p) toimivasta, demossa näytettävästä versiosta on luotu GitHubiin [release](https://help.github.com/articles/creating-releases/).
- (0.25p) sprintin katselmointiin on valmistauduttu asiallisesti
  - Katselmoinnin pitää eri henkilö, kuin edellisessä katselmoinnissa
  - Katselmoinnin pitäjä on sovittu ja tarvittavat esivalmistelut on tehty etukäteen
  - Katselmoinnin aikana asiakkaalle näytetään, että jokainen sprinttiin valittu user story on toteutettu hyväksymiskriteerien mukaisesti
- **Pitäkää sprintin päätteeksi retrospektiivi**, pisteet retrospektiivista annetaan sprintin 3 arvostelussa, ks ohje alta

Sprintin maksimi on 2.5 pistettä.

#### Retrospektiivi

- Sprintin 2 päätteeksi tulee pitää retrospektiivi
- Muutama ohje retrospektiivin pitämiseen [täällä](/tehtavat4/#5-retrospektiivitekniikat)
- Retrospektiivista tulee kirjoittaa lyhyet muistiinpanot projektin repositorion juureen laitettavaan tiedostoon `retro.md`
- Retrospektiivissa havaituista asioista tulee identifioida vähintään kaksi _kehitystoimenpidettä_, eli asiaa joissa tiimi yrittää parantaa toimintaa seuraavassa sprintissä
  - kehitystoimenpiteet pitää kirjata retrospektiivin muistiinpanoihin

### Kolmannen sprintin arvosteluperusteet

Pisteitä kertyy seuraavista asioista:

- (0.25p) product backlog
  - Backlog on DEEP (storyjä ei tarvitse estimoida)
  - Backlogiin ei jää sinne kuulumatonta roskaa, storyjen statukset on kirjattu oikein, jne...
- (0.25p) sprintiin 3 valittujen storyjen hyväksymisehdot kirjattu Robot Framework -tiedostoihin
  - Hyväksymisehtoja **ei kirjoteta erikseen backlogiin**, vaan backlogista on linkki hyväksymistestin tiedostoon
- (0.25p) sprintin 3 backlog
  - Vaatimukset kuten edellisissä sprinteissä
- (0.25p) kattavahko testaus yksikkötasolla
- (0.25p) kattavahko testaus storytasolla
  - testit toimivat vähintään lokaalisti suoritettaessa
- (0.25p) jatkuva integraatio
  - CI-palvelu suorittaa yksikkö- ja storytestit ja PyLintin
  - main-branch ei ole hajonnut kuin korkeintaan noin 25% sprintin commiteista 
- (0.125p) GitHubin README:stä linkki testikattavuusraporttiin
- (0.25p) [Retrospektiivi](/miniprojektin_arvosteluperusteet/#retrospektiivi) on pidetty sprintin 2 lopussa ja siitä on tehty asialliset muistiinpanot
- (0.25p) suurin osa sprintin user storyistä toteutettu definition of donen mukaisella tasolla
- (0.125p) toimivasta, demossa näytettävästä versiosta on luotu GitHubiin [release](https://help.github.com/articles/creating-releases/) ja ohjelmalle on valittu sopiva lisenssi, ja määritely se repositorioon
  - Lue [täältä](/lisenssit/) enemmän ohjelmistolisensseistä
- (0.25p) loppudemoon on valmistauduttu asiallisesti (valmistautuminen arvioidaan sen perusteella miten demo menee)
  - Kone osataan kytkeä videotykkiin nopeasti (5 sekunnissa) siten, että näyttö on konfiguroitu oikein
  - Sovittu etukäteen kuka tekee mitäkin
  - Mietitty mitä esitetään
    - Kannattaa esitellä tärkein toiminnallisuus, aikaa demossa on vähän joten ei kannata rönsyillä
  - Testidata on järkevää
    - tietokanta ei saa olla etukäteen tyhjä
    - tietokannassa oleva data ja demottaessa käytettävät syötteet järkeviä, eli _ei_ esimerkiksi _12345_, _asdf_, _nimi1_, _nimi2_
  - **Lue viimeinen bullet uudelleen** jostain syystä se jää 25% huomaamatta...



Sprintin maksimi on 2.5 pistettä.

<!--
### Neljännen sprintin arvosteluperusteet

Pisteitä kertyy seuraavista asioista:

- (0.25p) product backlog
  - Backlog on DEEP (storyjä ei tarvitse estimoida)
  - Backlogiin ei jää sinne kuulumatonta roskaa, storyjen statukset on kirjattu oikein, jne...
- (0.25p) sprintiin 4 valittujen storyjen hyväksymisehdot kirjattu Robot Framework -tiedostoihin
  - Hyväksymisehtoja ei kirjoteta erikseen backlogiin, vaan backlogista on linkki hyväksymistestin tiedostoon
- (0.25p) sprintin 4 backlog
  - Vaatimukset kuten edellisissä sprinteissä
- (0.25p) kattavahko testaus yksikkötasolla
  - kattavuusraportti README-tiedostossa
- (0.25p) kattavahko testaus storytasolla
  - testit toimivat vähintään lokaalisti suoritettaessa
- (0.25p) jatkuva integraatio
  - CI-palvelu suorittaa yksikkö- ja storytestit sekä Pylintin
  - main-branch ei ole hajonnut kuin korkeintaan noin 25% sprintin commiteista 
- (0.25p) suurin osa sprintin user storyistä toteutettu definition of donen mukaisella tasolla
- (0.25p) [Retrospektiivi](/miniprojektin_arvosteluperusteet/#retrospektiivi) on pidetty sprintin 3 lopussa, toimintaa kehitetty
  - edellisestä retrospektiivistä on tehty asialliset muistiinpanot
  - tiimi on kehittänyt toimintaansa, parantamalla edellisessä retrospektiivissa identifioituja ongelmakohtia 
- (0.25p) Koodin sisäinen laatu on kohtuullisella tasolla
  - koodi on jaoiteltu järkevästi tiedostoihin ja hakemistoihin
  - koodissa käytetään järkevää nimentää 
  - koodissa ei ole liikaa ilmeistä copypastea
  - koodissa ei ole sinne kuulumatonta roskaa, esim. pois kommentoitua koodia
- (0.25p) loppudemoon on valmistauduttu asiallisesti (valmistautuminen arvioidaan sen perusteella miten demo menee)
  - Kone osataan kytkeä videotykkiin nopeasti (5 sekunnissa) siten, että näyttö on konfiguroitu oikein
  - Sovittu etukäteen kuka tekee mitäkin
  - Mietitty mitä esitetään
    - Kannattaa esitellä tärkein toiminnallisuus, aikaa demossa on vähän joten ei kannata rönsyillä
  - Testidata on järkevää
    - tietokanta ei saa olla etukäteen tyhjä
    - tietokannassa oleva data ja demottaessa käytettävät syötteet järkeviä, eli _ei_ esimerkiksi _12345_, _asdf_, _nimi1_, _nimi2_
  - **Lue viimeinen bullet uudelleen** jostain syystä se jää 25% huomaamatta...

Sprintin maksimi on 2.5 pistettä.
-->

### Lopputoimenpiteet

#### Loppudemo ja sprintin 4 päättyminen

Loppudemot pidetään 17.12. luennolla. Demossa on aikaa max 15 minuuttia per ryhmä. Demon lopussa ryhmä kertoo lyhyesti kokemuksistaan: mikä onnistui hyvin ja mihin jäi parantamisen varaa.


#### Vertaispalaute

- Arvosteluperusteiden alussa mainittu henkilökohtainen pisteytys perustuu mm. vertaispalautteeseen
- Jokaisen ryhmäläisen tulee antaa **vertaispalaute viimeistään 20.12. klo 23:59**
  - Vertaispalautteen antaminen on _pakollista_. Jos vertaispalaute puuttuu, ovat miniprojektin henkilökohtaiset pisteet -1.5p
- Vertaispalautteen antaminen tapahtuu Timin kautta
  - Ryhmäläiset eivät näe toistensa vertaispalautteita

#### Raportti

Vertaispalautteen lisäksi ryhmä laatii projektin kulusta pienen raportin (noin 1 sivu)

- Kerrataan jokaisen sprintin aikana kohdatut ongelmat (prosessiin-, projektityöskentelyyn- ja teknisiin asioihin liittyvät)
- Mikä sujui projektissa hyvin, mitä pitäisi parantaa seuraavaa kertaa varten
- Mitä asioita opitte, mitä asioita olisitte halunneet oppia, mikä tuntui turhalta
- Jos raportti puuttuu, vähennetään ryhmältä 2 pistettä
- Raportti palautetaan lisäämällä raporttiin linkki projektin GitHubin README:hen
- Raportista tulee ilmetä jokaisen projektiin osallistuneen nimi
- **Raportin deadline on 20.12. klo 23:59** Raportin voi kuitenkin palauttaa jo 3. sprintin aikana, kurssin viineisellä viikolla

### Varmista, että commitisi näkyvät GitHubissa oikein

Koska Githubiin tehtävien commitien määrä (ja laatu) vaikuttaa henkilökohtaisiin pisteisiin, varmista, että olet konfiguroinit email-osoitteesi Gitiin (ks. [viikon 1 laskareiden tehtävä 2](/tehtavat1#2-githubiin-versionhallinta)), ja että commitatessasi ryhmäsi repositorioon tunnuksesi näkyy oikein repositorion commit-listalla. On suositeltavaa, että jokainen tekee (omalta koneeltaan) heti alussa yhden testicommitin ja tarkastaa, että Git on konfiguroitu oikein.

### Pariohjelmointi ja commitit

Jos pariohjelmoit (se kannattaa!) saat commitit näkyviin molemmille
[tämän ohjeen](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors) mukaan.

### Commitit kadoksissa

Jos committisi yhteydessä näkyy (Gitin email-osoitteen konfiguroinnista huolimatta) harmaa symbooli kuten seuraavista alempi

![](https://raw.githubusercontent.com/mluukkai/ohtu2017/master/images/commit1.png)

Klikkaa harmaan commitin nimeä katso mikä on email-osoite, joka commitiin liittyy mutta mitä GitHub ei tunnista osoitteeksesi.

![](https://raw.githubusercontent.com/mluukkai/ohtu2017/master/images/commit2.png)

Lisää osoite _settings_-valikosta:

![](https://raw.githubusercontent.com/mluukkai/ohtu2017/master/images/commit3.png)
