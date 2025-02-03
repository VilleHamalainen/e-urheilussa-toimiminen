---
layout: default
title: E-urheilutapahtuman toteuttaminen
permalink: /e-urheilutapahtuman-toteuttaminen/

---

# E-urheilutapahtuman toteuttaminen

---

## Sisällysluettelo

- [Roolit ja tehtävät tapahtuman aikana](#roolit-ja-tehtavat-tapahtuman-aikana)  
  - Tapahtumien onnistunut toteuttaminen vaatii huolellista suunnittelua ja monia rooleja, jotka ovat usein yleisöltä piilossa.  
  - Vaikka valmistelut olisivatkin perusteellisia, tekniset ongelmat ovat yleisiä.  
  - Suunnitteluvaiheen kertaaminen auttaa hahmottamaan toteutuksen laajuuden.  

- [Mahdolliset ongelmat](#mahdolliset-ongelmat)  
  - [Yhteysongelmat](#yhteysongelmat): Internet-katkokset voivat estää osallistumisen.  
  - [Laitteistoviat](#laitteistoviat): Rikkoutuneet laitteet voivat aiheuttaa viivästyksiä.  
  - [Pelipalvelinongelmat](#pelipalvelinongelmat): Palvelimen kaatumiset voivat häiritä aikatauluja.  
  - [Pelin kaatuminen tai bugit](#pelin-kaatuminen-tai-bugit): Pelin sisäiset ongelmat voivat aiheuttaa viivästyksiä.  
  - [Aikavyöhykkeiden erot](#aikavyohykkeiden-erot): Kansainvälisissä turnauksissa voivat aiheuttaa sekaannusta.  
  - [Säännöistä poikkeaminen](#saannoista-poikkeaminen): Huijaaminen ja muut sääntörikkomukset vaativat nopeita ratkaisuja.  
  - [Pelaajien väsymys](#pelaajien-vasymys): Pitkät turnaukset voivat uuvuttaa pelaajia.  
  - [Sääntömuutokset](#saantomuutokset): Viime hetken päivitykset voivat sekoittaa pelaajia.  
  - [Lähetyksen katkeaminen](#lahetyksen-katkeaminen): Tekniset ongelmat heikentävät katselukokemusta.  
  - [Pelaajien poissaolot](#pelaajien-poissaolot): Viisumiongelmat ja muut syyt voivat aiheuttaa pelaajien poissaoloja.  
  - [Yleisöongelmat](#yleisoongelmat): Ongelmat tilojen, turvallisuuden tai hallinnan kanssa.  
  - [Sponsoriongelmat](#sponsoriongelmat): Jos tavoitteita ei saavuteta, sponsorit voivat menettää kiinnostuksensa.  

- [Avainroolit e-urheilutapahtumien hallinnassa](#avainroolit-e-urheilutapahtumien-hallinnassa)  
  - [Tapahtuma- ja pelimanagerit](#tapahtuma-ja-pelimanagerit): Toimivat tuomareina ja varmistavat reilun pelin.  
  - [Tekninen henkilöstö](#tekninen-henkilosto): Hallinnoi laitteistoja, verkkoja ja suoratoistoa.  
  - [Tapahtuman juontajat](#tapahtuman-juontajat): Toimivat pääpuhujina ja viihdyttäjinä.  
  - [Selostajat](#selostajat): Tarjoavat analyysiä ja tulkitsevat pelitapahtumia.  
  - [Viestintä](#viestinta): Keskittyy tapahtuman mainostamiseen ja suhteisiin.  
  - [Tapahtuman järjestäjät](#tapahtuman-jarjestajat): Hoitavat suunnittelun ja logistiikan.  
  - [Muu henkilöstö](#muu-henkilosto): Vastaavat turvallisuudesta, myynnistä ja siivouksesta.  
  - [Tapahtuman jälkityö](#tapahtuman-jalkityo): Data-analyytikot ja palautetiimi.  

- [Turnauksen aikainen ja jälkeinen muistilista](#turnauksen-aikainen-ja-jalkeinen-muistilista)  
  - **[Turnauksen aikana](#turnauksen-aikana):** Tiimin valmistelu, viestinnän tarkistaminen, aikataulun hallinta, tuomareiden varmistaminen, tiimiroolien määrittely, pisteiden ilmoittaminen, tilastojen valmistelu, keskustelujen moderoiminen, pelaajien tukeminen, tiedotusten jakaminen ja lähetettävien otteluiden valinta.  
  - **[Turnauksen jälkeen](#turnauksen-jalkeen):** Juhliminen, palautteen kerääminen, raportin laatiminen, palkintojen jaon valvonta, sosiaalisen median julkaisut, palkintojenjakotilaisuus, datan analysointi ja tulosten jakaminen.  

- [E-urheilutapahtuman toimintasuunnitelma ja avainroolit](#e-urheilutapahtuman-toimintasuunnitelma-ja-avainroolit)  
  - **[Juontaminen ja selostaminen](#juontaminen-ja-selostaminen)**  
    - [Juontajat](#juontajat): Esittelevät joukkueet, ilmoittavat aikataulut, haastattelevat pelaajia.  
    - [Selostajat](#selostajat): Tarjoavat pelianalyysiä ja välittävät jännitystä.  
  - **[Lähetyskanavan valvonta ja moderointi](#lahetyskanavan-valvonta-ja-moderointi)**  
    - [Moderaattorit](#moderaattorit): Valvovat chatia ja puuttuvat häiriökäyttäytymiseen.  
    - [Lähetyksen valvojat](#lahetyksen-valvojat): Varmistavat lähetyksen sujuvuuden ja ratkaisevat teknisiä ongelmia.  

- [Teknisten ongelmien hallinta](#teknisten-ongelmien-hallinta)  
  - **[Verkko-ongelmat](#verkko-ongelmat)**  
    - Yleisimmät ongelmat ovat viivepiikit, pakettihäviö ja DDoS-hyökkäykset.  
    - Valmistautumiseen kuuluu nopeiden yhteyksien käyttö ja verkon valvontatyökalut.  
  - **[Laitteistoviat](#laitteistoviat)**  
    - Yleisiä ongelmia ovat tietokoneiden kaatumiset ja oheislaitteiden toimintahäiriöt.  
    - Valmistautumiseen kuuluu laadukkaat testatut laitteet, varaosat ja jäähdytys.  

- [Oman osaamisen kehittäminen e-urheilussa](#oman-osaamisen-kehittaminen-e-urheilussa)  
  - **[Pelillinen kehittyminen](#pelillinen-kehittyminen)**  
    - E-urheilu vaatii taitoa, strategiaa ja henkistä kanttia.  
    - Pelityylit vaihtelevat eri pelien välillä, mutta monet periaatteet ovat samat.  
    - Esimerkiksi Counter-Strike vaatii ampumistaitojen lisäksi karttatuntemusta ja pelimekaniikan ymmärrystä.  
    - [Kommunikaatio](#kommunikaatio) on tärkeää joukkuepeleissä, ja joukkueilla voi olla omat "koodikielet".  
  - **[Pelin ulkopuolinen toiminta](#pelin-ulkopuolinen-toiminta)**  
    - [Tiimikokoukset](#tiimikokoukset): Säännölliset tapaamiset ovat tarpeen strategioiden ja heikkouksien käsittelyyn.  
    - [Vertaispalaute](#vertaispalaute): Rakentava palaute on tärkeää ilman syyllistämistä.  
    - [Retrospektiivit](#retrospektiivit): Viikoittaiset arvioinnit voivat auttaa kehittymään.  
    - [Tiimitekeminen](#tiimitekeminen): Tiimipelit ja aktiviteetit voivat parantaa yhteistyötä.

---

## Tapahtuman aikana olevat roolitukset ja tehtävät

E-urheilutapahtumaa (oikeasti mikä tahansa tapahtuma) seuratessa ei tule useinkaan mietittyä mitä kaikkea onnistuneen tapahtuman toteuttaminen vaatii. Ja parhaassa tapauksessa tausta olevat toimenpiteet on suunniteltu niin hyvin, että katsojan ei niitä tarvitsekaan miettiä. Usein kuitenkin kaikesta valmistumisesta huolimatta jotain menee pieleen ja tämä on erityisen totta tapahtumissa, joissa on mukana tietoteknisiä laitteita. Kerrataanpa mitä kaikka turnauksen suunnitteluvaiheessa piti ottaa huomioon. Miettikää pienissä ryhmissä ennen kuin avaatte alla olevan listan.

<details>
  <summary>Mitä kaikkea tulee ottaa huomioon?</summary>

| **Ongelmakategoria**                    | **Kuvaus**                                                                                                                                           |
|-----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Yhteysongelmat**                      | Internet-yhteyksien katkeaminen tai heikko yhteys voi estää pelaajia, tiimejä tai katsojia osallistumasta tapahtumaan.                                 |
| **Laitteistoviat**                      | Pelitietokoneiden, näytönohjainten tai muiden pelilaitteiden rikkoutuminen voi aiheuttaa viivästyksiä tai keskeyttää tapahtuman.                       |
| **Pelipalvelinongelmat**                | Pelin palvelinten kaatuminen tai viiveet voivat sekoittaa aikataulut ja vaikuttaa kaikkiin turnauksessa oleviin sekä katsojiin.                        |
| **Pelin kaatuminen tai bugit**          | Peli voi kaatua tai sisältää isoja bugeja, jotka aiheuttavat viivästyksiä ja lisähaasteita tapahtuman hallinnoinnissa.                                 |
| **Viivästykset**                        | Viivästykset pelissä tai tapahtumassa voivat venyttää aikatauluja ja vaikuttaa sekä pelaajiin että katsojiin.                                          |
| **Aikavyöhykkeiden ero**                | Kansainvälisissä turnauksissa aikavyöhykkeiden erot voivat aiheuttaa sekavuutta ja myöhästymisiä.                                                     |
| **Säännöistä poikkeaminen**             | Kilpailijoiden sääntörikkomukset tai huijaaminen voivat johtaa kiistoihin, joita on ratkaistava nopealla aikataululla.                                 |
| **Pelaajien fyysinen ja henkinen väsymys** | Pitkät turnaukset voivat johtaa pelaajien uupumukseen, vaikuttaen suoritukseen ja mahdollisesti aiheuttaen loukkaantumisia (esim. rasitusvammoja).     |
| **Peliin liittyvät sääntömuutokset**    | Peliin tulleet päivitykset juuri ennen tapahtumaa voivat aiheuttaa sekaannusta, jos pelaajat eivät ole ehtineet tutustua niihin.                      |
| **Lähetyksen katkeaminen**              | Live-streamin tai muun lähetyksen tekniset ongelmat heikentävät katselukokemusta.                                                                     |
| **Pelaajien poissaolot tai myöhästelyt**| VISA-ongelmat, huolimattomuus tai muut syyt voivat johtaa siihen, että pelaajat myöhästyvät tai eivät pääse paikalle.                                  |
| **Katsomo- ja yleisöongelmat**          | Paikan päällä järjestettävissä tapahtumissa voi ilmetä ongelmia tilojen, turvallisuuden tai yleisön hallinnan kanssa.                                  |
| **Sponsoriongelmat**                    | Jos tapahtuma ei saavuta tavoitteitaan, sponsorit voivat menettää kiinnostuksensa tuleviin tapahtumiin.                                               |


</details>


Tapahtuman järjestämisessä on paljon mietittävää, on turnauksessa useita erilaisia rooleja, joista katsoja ei välttämättä ole tietoinen. Alla olevaa roolilistaa voi käyttää hyväksi kun mietitään, mitä rooleja kullekin opiskelijalle tulee ja mitkä kaikki kategoriat ovat tarpeellisia järjestettävissä tapahtumissa.

<details>
<summary>Avainroolit e-urheilutapahtumien hallinnassa</summary>

| **Kategoriat**                 | **Roolit**                                                                                                   |
|--------------------------------|-------------------------------------------------------------------------------------------------------------|
| **Tapahtuma-/pelimanagerit**   | Tuomarit, sääntöjen kiistojen ratkaisut, reilun pelin ylläpito, turnauksen sujuvuuden varmistaminen           |
| **Tekninen henkilöstö**        | Tietokoneet, konsolit, verkot, näyttölaitteet, teknisten ongelmien vianmääritys, streamaus, kamerat, ääni jne.|
| **Tapahtuman juontajat**       | Pääpuhujat, joukkueiden esittely, palkintojen jako, yleisön osallistaminen                                   |
| **Selostajat/casterit**        | Kommentaattorit, pelin tapahtumien tulkitseminen, entiset pelaajat, syvällinen pelitieto                     |
| **Viestintä (PR)**             | Tapahtumatiedon levitys, osallistujien houkuttelu, tapahtuman profiilin nosto, median ja sponsorien yhteistyö |
| **Tapahtuman järjestäjät/komitea**     | Tutkimus, Kokonaissuunnittelu, logistiikka, aikataulutus,  markkinointi, koordinointi                         |
| **Tapahtuman muu henkilöstö**  | Järjestyksenvalvojat, myyntihenkilöstö, siivoojat, turvallisuushenkilöstö, lipunmyyjät                        |
| **Tapahtuman jälkityö**        | Data-analyytikot, asiakaspalvelu, palautetiimi                                                              |

</details>





Alla oleva lista on tuttu jo  osiosta.e-urheilutapahtuman suunnittelumoduulista. Tässä listassa on mukana kertauksen vuoksi vain turnauksen aikana ja sen jälkeen tapahtuvat toimenpiteet.
<details>
<summary>Turnauksen aikana</summary>

| Vaihe  | Määräaika | Valmis |
|--------|-----------|--------|
| 1. Valmistele tiimi | | | |
| 2. Tarkista pelaajien viestintäkanavat | | | |
| 3. Hallinnoi turnauksen aikataulua | | | |
| 4. Tarkista tuomareiden tilit | | | |
| 5. Määrittele tiimiroolit | | | |
| 6. Ilmoita pisteet ja tulokset otteluiden välillä | | | |
| 7. Valmistele päivittäiset turnaustilastot | | | |
| 8. Moderoi keskustelua | | | |
| 9. Tarjoa tukea turnauspelaajille | | | |
| 10. Jaa päivän lopputiedotteet | | | |
| 11. Valitse lähetettävät ottelut | | | |
| 12. Ole valmiina otteluiden alkaessa | | | |

</details>

<details>
<summary>Turnauksen jälkeen</summary>

| Vaihe  | Määräaika | Valmis |
|--------|-----------|--------|
| 13. Juhli tiimin ja ehkä myös pelaajien kanssa | | | |
| 14. Kerää pelaajapalautetta | | | |
| 15. Valmistele tapahtumaraportti | | | |
| 16. Seuraa palkintojen jakoa | | | |
| 17. Jaa turnauksen jälkeiset sosiaalisen median julkaisut | | | |
| 18. Järjestä palkintojenjakotilaisuus | | | |
| 19. Analysoi data | | | |
| 20. Lähetä data asianomaisille toimijoille | | | |
</details>

Muistilistan laatimisessa on hyödynnetty Foundational Guide for Esports Tournaments -dokumenttia, joka on julkaistu 4.0 Creative Commons -lisenssillä Dell Technologiesin ja Advanced Learning Partnersin toimesta.



<div align="center">
  <a href="https://www.youtube.com/watch?v=_d5C75pLDKs&ab_channel=UniversityofStaffordshire" title="Inside an esports event">
    <img src="http://img.youtube.com/vi/_d5C75pLDKs/0.jpg" alt="Inside an esports event" style="width: 100%; height: auto; max-width: 100%; margin: 0 auto;; height: auto;">
  </a>
  </div>
  <p style="max-width: 100%; margin: 0 auto;">
    Video hieman isomman opiskelijoiden e-urheilutapahtuman järjestämisestä ja siihen liittyvistä haasteista ja onnistumisista. 
  </p>


---

<div align="center">
  <a href="https://www.youtube.com/watch?v=8JR_YMksuOQ&ab_channel=22WestTelevision" title="Inside Smash Bros console gaming event">
    <img src="http://img.youtube.com/vi/8JR_YMksuOQ/0.jpg" alt="Inside Smash Bros console gaming event" style="width: 100%; height: auto; max-width: 100%; margin: 0 auto;; height: auto;">
  </a>
  </div>
  <p style="max-width: 100%; margin: 0 auto;">
    Videokuvaa Smash Bros konsoliturnauksesta, jossa tuotanto ym. ovat hieman pienemmässä mittakaavassa kuin aikaisemmalla videolla.
  </p>


---

<div align="center">
  <a href="https://www.youtube.com/watch?v=qe5jqnv1dlU&ab_channel=MyWhoosh" title="Biking esports event">
    <img src="http://img.youtube.com/vi/qe5jqnv1dlU/0.jpg" alt="Biking esports event" style="width: 100%; height: auto; max-width: 100%; margin: 0 auto;; height: auto;">
  </a>
  </div>
  <p style="max-width: 100%; margin: 0 auto;">
    Video hieman erilaisesta e-urheilutapahtumasta. Videon tarkoituksena herätellä ajattelemaan myös perinteisiä lajeja ja e-urheilun yhdistämistä.
  </p>

---
## E-urheilutapahtuman toimintasuunnitelma ja avainroolit  

Tämä ohje tarjoaa kattavat tiedot e-urheilutapahtuman toteutuksesta, avainrooleista ja käytännön esimerkeistä. Lisäksi mukana on hyödyllisiä resursseja jatkotutkimusta varten.

---

## **1. Juontaminen ja selostaminen**  
### **Roolin kuvaus:**  
- **Juontajat:** Tapahtuman kasvoina ja viihdyttäjinä juontajat esittelevät joukkueet, tiedottavat aikatauluista, vetävät haastatteluja ja pitävät yleisön tunnelman korkealla.  
- **Selostajat (casterit):** Tarjoavat syväanalyysia otteluista, selittävät pelistrategioita ja välittävät kilpailun jännityksen yleisölle.  

### **Tapahtuman aikana:**  
- **Juontajat:**  
  - Esittelevät joukkueet ja pelaajat sekä kertovat heidän taustoistaan.  
  - Suorittavat livehaastatteluja pelaajien ja voittajien kanssa.  
  - Järjestävät yleisöaktiviteetteja, kuten kilpailuja taukojen aikana.  
- **Selostajat:**  
  - Analysoivat pelistrategioita reaaliajassa ja tulkitsevat tapahtumia yleisölle.  
  - Selittävät pelimekaniikkoja uusille katsojille ja pitävät tunnelman korkealla.  

### **Esimerkki:**  
"Seuraavaksi lavalle astuu Team Apex, joka on hallitseva mestari! He ovat pelanneet 20 ottelua tappiotta, mutta pystyvätkö he pitämään ennätyksensä tänään? Katsotaan, mitä heidän kapteenillaan, Alexilla, on sanottavaa!"  

### **Resursseja:**  
- [Toastmasters International - Äänenkäytön ja esiintymistaidon kehittäminen](https://www.toastmasters.org/)  
- [Esports Insider - Selostusopas](https://esportsinsider.com/2023/06/art-of-the-broadcast-esports-2022)  

---

## **2. Lähetyskanavan valvonta ja moderointi**  
### **Roolin kuvaus:**  
- **Moderaattorit:** Valvovat online-chatin keskustelua ja puuttuvat häiritsevään käytökseen.  
- **Lähetyksen valvojat:** Vastaavat lähetyksen sujuvuudesta ja ratkovat teknisiä ongelmia.  

### **Tapahtuman aikana:**  
- Moderaattorit seuraavat aktiivisesti chat-keskusteluja Twitchissä, YouTubessa, Discordissa tai muilla alustoilla.  
- He käyttävät automatisoituja työkaluja, kuten chattibotteja, estämään häiriökäyttäytymistä.  
- Vastaavat yleisön kysymyksiin, kuten aikatauluihin tai sääntöihin liittyen.  

### **Esimerkki:**  
"Katsoja: Milloin finaali alkaa ja milloin palkinnot jaetaan?  
Moderaattori: Finaali alkaa klo 18:00. Muista pysyä linjoilla, sillä palkintojenjako suoritetaan heti ottelun jälkeen!"  

### **Resursseja:**  
- [Twitch Moderator Academy](https://www.twitch.tv/creatorcamp/)  
- [Streamlabs Academy - Teknisen valvonnan oppaat](https://streamlabs.com/)  
- [OBS:n tukisivut](https://obsproject.com/help)  

---

## **3. Tuomarointi ja järjestyksenvalvonta**  
### **Roolin kuvaus:**  
- **Tuomarit:** Varmistavat pelisääntöjen noudattamisen, ratkaisevat riitatilanteet ja estävät huijaamisen.  
- **Järjestyksenvalvojat:** Vastaavat tapahtumapaikan turvallisuudesta ja yleisestä järjestyksestä.  

### **Tapahtuman aikana:**  
- **Tuomarit:**  
  - Valvovat pelien sääntöjen noudattamista ja tarkastavat mahdolliset sääntörikkomukset.  
  - Ratkaisevat pelaajien välisiä riitoja neutraalisti ja nopeasti.  
- **Järjestyksenvalvojat:**  
  - Tarkastavat osallistujien kulkuluvat ja ohjaavat yleisöä.  
  - Hallitsevat hätätilanteita ja puuttuvat häiriökäyttäytymiseen.

### **Esimerkki:**  
"Pelaajalla on teknisiä ongelmia tietokoneensa kanssa ja hän väittää menettäneensä pisteitä sen takia. Tuomari tarkistaa pelitallenteen ja tekee päätöksen: ongelma ei vaikuttanut ratkaisevasti pelin lopputulokseen."  

### **Resursseja:**  
- [ESL:n kilpailusäännöt](https://pro.eslgaming.com/)  
- [FACEIT:n tuomariopas](https://support.faceit.com/hc/en-us/categories/360003095600)  
- [Event Safety Alliance - Turvallisuusohjeet](https://eventsafetyalliance.org/)  

---

## **4. Myynti ja markkinointi**  
### **Roolin kuvaus:**  
- **Myyntitiimi:** Hoitaa sponsorointia, lipunmyyntiä ja varmistaa tapahtuman taloudellisen kannattavuuden.  
- **Markkinointitiimi:** Vastaa tapahtuman näkyvyydestä, mainonnasta ja yleisön sitouttamisesta.  

### **Tapahtuman aikana:**  
- **Myyntitiimi:**  
  - Koordinoi sponsorien kanssa logojen ja mainosvideoiden sijoittelua.  
  - Valvoo VIP-alueita ja tarjoaa sponsorien edustajille erityiskohtelua.  
- **Markkinointitiimi:**  
  - Tekee reaaliaikaisia päivityksiä sosiaaliseen mediaan, kuten kuvia ja lyhyitä videoita otteluista.  
  - Järjestää yleisöaktiviteetteja, kuten liveäänestyksiä ja kilpailuja.  

### **Esimerkki:**  
"Markkinointitiimi twiittaa: *'Jännitystä ilmassa! Team Apex vs. CyberStorm alkaa juuri nyt! Kuka voittaa? Kommentoi alle!'* Samalla myyntitiimi järjestää VIP-alueella sponsorien verkostoitumistapahtuman."  

### **Resursseja:**  
- [Canva - Visuaalisen sisällön suunnittelu](https://www.canva.com/)  


---

## **5. Mediatuotanto ja striimaus**  
### **Roolin kuvaus:**  
Mediatiimi vastaa lähetyksen teknisestä toteutuksesta ja visuaalisista elementeistä, kuten grafiikoista ja videoista.  

### **Tapahtuman aikana:**  
- **Visuaaliset elementit:** 
  - Lisäävät grafiikat, kuten overlayt, tulostaulut ja sponsorilogot, reaaliaikaisesti lähetykseen.  
  - Käyttävät highlight-videoita yleisön sitouttamiseen.  
- **Kuvaus ja ohjaus:**  
  - Varmistavat oikeat kuvakulmat ja sujuvat siirtymät lähetyksen aikana.  

### **Esimerkki:**  
"CyberStorm nappaa ratkaisevan voiton – mediatiimi zoomaa riehaantuneeseen yleisöön ja lisää lähetykseen voittajagrafiikan. Pian tämän jälkeen haastattelu CyberStormin kapteenin kanssa näytetään suorana."  

### **Resursseja:**  
- [StreamScheme - Striimauksen oppaat](https://www.streamscheme.com/)  
- [Canva - Overlayt ja grafiikat](https://www.canva.com/)  

---

## **6. Viestintä ja PR**  
### **Roolin kuvaus:**  
Viestintätiimi rakentaa tapahtuman mainetta ja välittää tietoa median sekä yleisön suuntaan.  

### **Tapahtuman aikana:**  
- Koordinoivat median haastatteluja pelaajien, järjestäjien ja sponsoreiden kanssa.  
- Julkaisevat reaaliaikaisia tiedotteita ja päivittävät tapahtuman virallisia kanavia.  

### **Esimerkki:**  
"Median edustajat haastattelevat Team Apexin kapteenia. Viestintätiimi huolehtii, että haastattelu tapahtuu suunnitellusti erillisessä mediapisteessä."  

### **Resursseja:**  
- [Pressitt - PR-työkalut ja mediaviestintä](https://pressitt.com/)  
- [Hootsuite - Sosiaalisen median hallinta](https://hootsuite.com/)  

---

## **Yhteenveto**  
- **Juontajat ja selostajat:** Yleisön osallistaminen ja tapahtuman selostaminen, esim. haastattelut ja kilpailuanalyysit.  
- **Moderaattorit:** Chatin hallinta ja yleisön kysymyksiin vastaaminen, esim. aikatauluja koskevat kysymykset.  
- **Tuomarit ja järjestyksenvalvojat:** Pelisääntöjen valvonta ja tapahtuman turvallisuuden takaaminen, esim. huijausyritysten estäminen.  
- **Myynti- ja markkinointitiimi:** Sponsoreiden koordinointi ja sosiaalisen median kampanjat, esim. livekilpailut katsojille.  
- **Mediatiimi:** Ammattimaisen striimin tuottaminen ja visuaalisten elementtien hallinta, esim. grafiikat ja highlight-koosteet.  

Näillä ohjeilla ja resursseilla e-urheilutapahtuman toteuttaminen on tehokasta ja osallistujille mieleenpainuva kokemus.



## Teknisten ongelmien hallinta e-urheilutapahtumissa

Tässä osiossa tutustutaan erilaisiin teknisiin haasteisiin e-urheilutapahtumissa sekä strategioita niiden ennaltaehkäisyyn ja ratkaisuun. Sisältö on jäsennelty käsittelemään **verkko-ongelmia**, **laitteistovikoja**, **ohjelmistovirheitä**, **audiovisuaalisia ongelmia** ja **sähköön liittyviä ongelmia**. Jokainen osio sisältää ennaltaehkäiseviä toimenpiteitä, ratkaisuja ja käytännön sovelluksia.

---

## 1. Verkko-ongelmat

### Yleiset ongelmat:
- **Viivehuiput**: Äkilliset ping-arvon nousut häiritsevät pelaamista ja luovat epäreiluja etuja.
- **Pakettihäviö**: Datapakettien katoaminen aiheuttaa nykimistä tai yhteyskatkoksia.
- **DDoS-hyökkäykset**: Palvelunestohyökkäykset häiritsevät toimintaa.

### Valmistautuminen:
- Perusta **omistettuja nopeita internetyhteyksiä** varayhteyksillä.
- Käytä kehittyneitä **verkon valvontatyökaluja** ongelmien havaitsemiseen ja ratkaisemiseen reaaliajassa.
- Tee yhteistyötä internetpalveluntarjoajien kanssa varmistaaksesi **priorisoitu liikenne** ja tuki tapahtuman aikana.
- Ota käyttöön tehokkaat **palomuurit ja DDoS-suojausjärjestelmät**.

### Ratkaisut:
- Sijoita paikalle verkkoasiantuntijoita ratkaisemaan viive- tai pakettihäviöongelmia.
- Käytä VPN:iä tai erikoistuneita peliverkkoja reitityksen optimoimiseksi.
- DDos hyökkäykset voivat pilata koko turnauksen. Jos pelipalvelimet ovat verkossa voi niihin kohdistua hyökkäyksiä. Yhtenä ratkaisuna on tarjota lookaalisti pelattava peliversio (ks. [Ddos hyökkäys isossa turnauksessa] (https://www.insurancebusinessmag.com/us/risk-management/news/how-ddos-attacks-are-shaping-esports-security-and-risk-management-516320.aspx).

---

## 2. Laitteistoviat

### Yleiset ongelmat:
- **Tietokoneiden kaatuminen**: Järjestelmän epävakaus tai ylikuumeneminen aiheuttaa keskeytyksiä.
- **Oheislaitteiden toimintahäiriöt**: Ongelmat hiirissä, näppäimistöissä tai kuulokkeissa vaikuttavat pelaajien suorituskykyyn.
- **Näyttöongelmat**: Välkkyminen tai kuolleet pikselit haittaavat pelaajien näköä.

### Valmistautuminen:
- Käytä suorituskykyisiä, stressitestattuja laitteita, jotka on suunniteltu kilpapelaamiseen.
- Ylläpidä varastoa varatietokoneista, -oheislaitteista ja -näytöistä.
- Asenna asianmukaiset jäähdytysjärjestelmät laitteiden ylikuumenemisen estämiseksi.

### Ratkaisut:
- Kouluta henkilökunta vaihtamaan vialliset laitteet nopeasti varalaitteisiin.
- Standardoi prosessit pelaajien asetusten siirtämiseksi uusiin koneisiin.
- Suorita rutiininomaisia tarkastuksia kaikille laitteille otteluiden välillä.

---

## 3. Ohjelmistovirheet

### Yleiset ongelmat:
- **Pelivirheet**: Odottamattomat virheet voivat antaa epäreilua etua tai haittaa pelaajille.
- **Asiakasohjelmakaatuminen**: Pelin asiakasohjelman epävakaus aiheuttaa ottelukeskeytyksiä.
- **Päivitysten yhteensopimattomuus**: Viime hetken päivitykset voivat olla ristiriidassa turnausversioiden kanssa.

### Valmistautuminen:
- Käytä vakaita, ennalta testattuja turnauksille räätälöityjä peliversioita.
- Tee yhteistyötä pelikehittäjien kanssa tunnettujen virheiden tunnistamiseksi ja korjaamiseksi ennen tapahtumaa.
- Testaa kaikki ohjelmistokokoonpanot perusteellisesti ennen tapahtumaa.

### Ratkaisut:
- Luo selkeät protokollat otteluiden uudelleenkäynnistämiseen tai palautukseen peliä rikkovia virheitä kohdattaessa.
- Ylläpidä offline-varmuuskopioita pelien asiakasohjelmista ja päivityksistä nopeaa uudelleenasennusta varten.
- Palkkaa kokeneita turnausylläpitäjiä tekemään päätöksiä ohjelmistoihin liittyvissä ongelmissa.

---

## 4. Audiovisuaaliset ongelmat

### Yleiset ongelmat:
- **Striimausongelmat**: Koodaus- tai lähetysongelmat häiritsevät katsojakokemusta.
- **Äänen epätahdistus**: Epätahdissa oleva ääni ja kuva hämmentävät katsojia ja selostajia.
- **Lavavarusteiden toimintahäiriöt**: Ongelmat näytöissä tai äänijärjestelmissä vaikuttavat paikan päällä olevaan yleisöön.

### Valmistautuminen:
- Käytä ammattilaistason AV-laitteita varajärjestelmien kanssa.
- Suorita kattava testaus striimausasetuksille, mukaan lukien äänen synkronointitarkistukset.
- Valmistele varakoodauskoneet ja vaihtoehtoiset striimausalustat.

### Ratkaisut:
- Kouluta henkilökunta siirtymään saumattomasti varajärjestelmiin ensisijaisten järjestelmien pettäessä.
- Valvo striimauksen laatua reaaliajassa diagnostiikkatyökalujen avulla.
- Pidä AV-teknikot paikan päällä välitöntä vianmääritystä varten.

---

## 5. Sähköön liittyvät ongelmat

### Yleiset ongelmat:
- **Sähkökatkot**: Sähkön menetys pysäyttää koko tapahtuman.
- **Riittämätön virransyöttö**: Puutteellinen jakelu johtaa laitteiden sammumiseen.

### Valmistautuminen:
- Käytä keskeytymättömiä virtalähteitä (UPS) kriittisille järjestelmille kuten tietokoneille ja palvelimille.
- Hanki varavoimageneraattoreita, jotka pystyvät tukemaan koko tapahtuman virrantarvetta.
- Suorita tapahtumapaikalla sähköauditointi varmistaaksesi, että kapasiteetti vastaa vaatimuksia.

### Ratkaisut:
- Toteuta hätätilanteen virranhallinsuunnitelma, joka priorisoi kriittiset järjestelmät.
- Kouluta henkilökunta turvallisiin sammutustoimenpiteisiin sähkökatkojen aikana laitteiden eheyden suojelemiseksi.
- Pidä sähköasentajat paikan päällä virranjakelun ongelmien nopeaa ratkaisua varten.

---


## Keskeiset opit

1. Tekninen valmistautuminen on olennaista - investoi laadukkaisiin laitteisiin, ohjelmistotestaukseen ja vahvaan verkkoinfrastruktuuriin.  
2. Varaudu yllätyksiin - varajärjestelmät laitteille, internetyhteyksille ja sähkölle varmistavat minimaalisen käyttökatkon vikatilanteissa.  
3. Yhteistyö asiantuntijoiden kanssa - kumppanuudet internetpalveluntarjoajien, pelikehittäjien ja AV-asiantuntijoiden kanssa parantavat tapahtuman luotettavuutta.  
4. Reaaliaikainen valvonta - diagnostiikkatyökalujen käyttö auttaa havaitsemaan ongelmat ennen kuin ne eskaloituvat suuriksi häiriöiksi.  
5. Henkilökunnan koulutus - nopeat toimintaprotokollat minimoivat teknisten vikojen aiheuttamat viivästykset.


## Harjoitellaan "käytännössä"!

Ladatkaa koneellenne [Steam](https://store.steampowered.com/about/), jos sitä ei vielä ole ja asentakaa [ilmainen esports peli!](https://store.steampowered.com/app/3217120/Esports_History_Prologue/)

---

## Seraava aihe

- [Oman osaamisen kehittäminen e-urheilussa](https://villehamalainen.github.io/e-urheilussa-toimiminen/oman-osaamisen-kehittäminen-e-urheilussa/)

## Edellinen aihe

- [E-urheilutapahtuman toteuttaminen](https://villehamalainen.github.io/e-urheilussa-toimiminen/e-urheilutapahtuman-toteuttaminen/)

---
