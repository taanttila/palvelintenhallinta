#h3 Versionhallinta

Tämä harjoitus on tehty osana Tero Karvisen palvelinten hallinta kurssia. Harjoitukset tehtiin VirtualBoxille asennetulla Debian 11 Bullseye virtuaalikoneella.

##z) Lue ja tiivistä

[Lähde](commonmark.org/help/)

- Artikkelissa kerrotaan markdownin käyttöön liittyvät tärkeät komennot.

- Tyhjä rivi tekee kappalejaon, nämä ranskalaiset viivat tulevat samalla tavalla kuin muuallakin, mutta myös *-merkkiä voi käyttää listojen tekemiseen.

- Nettisivun linkkaus tapahtuu 'Link'(nettisivun osoite)' komennolla, ja Linkin molemmin puolin asetetaan hakasulut ([]).

- Risuaita/Hashtag eli # luo otsikon, kaksi risuaitaa ## luo otsikko kakkosen.

- Sisennys luominen tabulaattorilla merkitsee koodin kirjoittamista.

- Otsikko jonka kirjoitin boldilla, onnistuu kirjoittamalla kaksi tähteä * bold sanan molemmille puolille.

**##a) MarkDown. Tee tämän tehtävän raportti MarkDownina. Helpointa on tehdä raportti GitHub-varastoon, jolloin md-päätteiset tiedostot muotoillaan automaattisesti. Tyhjä rivi tekee kappalejaon, risuaita '#' tekee otsikon, sisennys merkitsee koodinpätkän.**

Aloitin tehtävän teon luomalla uuden repositoryn githubiini nimellä **PalvHalH3** . Lisäsin sinne tiedoston nimellä **H3harjoitus.md**.

Tämän jälkeen asetin git config tiedostoon käyttäjänimekseni taanttila kuten GitHubissa, sekä sähköpostiosoitteeni komennoilla **git config --global user.name "taanttila"** sekä **git config --global user.email "sähköpostini"**.

Loin ssh-avaimet komennolla **ssh-keygen ecdsa** , jotta saisin yhteyden GitHubiin. Asetin luodun public keyn GitHubiin, ja kirjoitin komennon **git remote add origin git@github.com:taanttila/PalvHalH3.git** joka loi yhteyden.

Kirjoitin kotihakemistossani komennon **git clone https://github.com/taanttila/PalvHalH3.git** joka kopioi luomani repositoryn koneelleni.

Tämän jälkeen kirjoitin komennon git pull joka päivitti hakemiston tiedoilla, jotka ovat repositoryssani. Sen jälkeen aloin editoimaan H3harjoitus.md tiedostoa nano tekstieditorilla komennolla **nano H3harjoitus.md**.

Tähän asti kirjoittamani raportin tallensin, ja kirjoitin komennot **git add README.md** sekä **git commit**.


