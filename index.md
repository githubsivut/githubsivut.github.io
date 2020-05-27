---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
list_title: Materiaali
---
{%- assign course = site.data.data.course -%}



<h1 id="main-title">Tervetuloa Tietokone Työvälineenä -kurssin kotisivulle. </h1>

Tämä kurssi on Riverian tietojenkäsittelyn opiskelijoille. Kurssilla tutustutaan komentoriviin Unix-tyyppisissä järjestelmissä, opetellaan Git-versionhallintatyökalun käyttöä sekä hieman HTML ja CSS-kieliä. Tarkoituksena on oppia tietojenkäsittelytietelijän käytännön taitoja, ja käyttämään opinnoissa hyödyllisiä työvälineitä. Kurssilla harjoitellaan myös tiedon itsenäistä hakemista internetistä.

<h2>Kurssista</h2>

Jokaisen osan alussa on määritelty oppimistavoitteet. Opiskele aihealueita kurssimateriaalin ja omatoimisen opiskelun avulla siten että osaat vähintään määritellyt oppimistavoitteet.

## Välineet

Tehtävät on mahdollista tehdä millä tahansa Unix-tyyppisellä käyttöjärjestelmällä. Käytännössä tämä tarkoittaa useimmiten Linux- tai macOS-tietokoneita. 

[Windows ei kuulu Unix-tyyppisten käyttöjärjestelmien perheeseen](https://en.wikipedia.org/wiki/Unix-like). Kurssin suorittamiseksi Windows-koneella on kuitenkin useita vaihtoehtoja:



### **Windows Subsystem for Linux**

Windows 10 -käyttöjärjestelmässä voit asentaa Ubuntun Windowsiin ohjelmistona. Tällöin saat käyttöösi tehtävien suorittamiseen soveltuvan Linux-ympäristön ilman suurempia säätöjä. Ubuntu on yksi lukuisista Linux-jakeluversioista (tuttavallisemmin distro), josta muokattua versiota käytetään myös osaston koneilla.

Windows Subsystem for Linuxin asennus:

1. Avaa [Powershell järjestelmänvalvojana](https://www.thewindowsclub.com/how-to-open-an-elevated-powershell-prompt-in-windows-10) ja kopioi ilmestyvään tekstikenttään 
<br>*Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux*
<br>(Koodi asentaa ominaisuuden mikäli sitä ei ole asennettu. **Älä KOSKAAN suorita vierasta koodia koneellasi, jos et tiedä mitä se tekee**)
2. Asenna 'Ubuntu'-sovellus [Microsoft Storesta](https://www.microsoft.com/fi-fi/p/ubuntu/9nblggh4msv6?activetab=pivot%3Aoverviewtab).
3. Käynnistä Ubuntu-sovellus ja luo käyttäjä Ubuntua varten.

Tarkat ohjeet asentamiseen löydät [tästä linkistä](https://docs.microsoft.com/en-us/windows/wsl/install-win10).

Jos pelkkä tekstipohjainen käyttöliittymä vaikuttaa pelottavalta voit myös asentaa Ubuntun virtualisoituun ympäristöön käyttäen esimerkiksi alla esiteltyä VirtualBox-ohjelmistoa.

### **VirtualBox**

Varmista ennen asentamista, että sinulla on vähintään 512 Mt, mutta mieluiten 1 Gt [RAM-muistia](https://www.computerhope.com/issues/ch000149.htm) vapaana koneellasi.

VirtualBoxin asennus:

1. Lataa ja asenna VirtualBox [täältä](https://www.virtualbox.org/wiki/Downloads).
2. Lataa Ubuntu 20.04:n levykuva (.iso) [täältä](http://releases.ubuntu.com/focal/). Jos olet koskaan asentanut käyttöjärjestelmää CD:ltä, tämä .iso-tiedosto on tavallaan sen sisältö.
3. Seuraa [näitä ohjeita](http://www.psychocats.net/ubuntu/virtualbox) luodaksesi virtuaalikoneen.
4. Käynnistä virtuaalikone VirtualBoxista.

Kysy rohkeasti apua, mikäli kohtaat ongelmia, ja ilmoita, mikäli voimme parantaa materiaalia Windows-käyttäjiä ajatellen!

## Ennen materiaalin aloittamista

Kurssin suorittaminen vaatii muutaman ohjelman asentamista koneelle. Varmista, että sinulla on käyttämääsi järjestelmään asennusoikeus.

## Ohjeita materiaalin lukemiseen

Materiaali on rakennettu niin, että sitä voi seurata tehden esimerkit samalla. Suosittelemme tätä vahvasti.

## Kiitokset

Tämä materiaali on luotu Janne Lofjelmin rakentaman kurssin pohjalta. Alkuperäinen kurssi löytyy [täältä](https://tkt-lapio.github.io/) Suuret kiitokset alkuperäisen kurssin tekijälle!
