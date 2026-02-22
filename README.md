Oppimispäiväkirja

Git-versionhallinta - SOF013AS2A-3002

Tekijä: Joona Koskinen

Tämä on kurssin "Git-versionhallinta - SOF013AS2A-3002" tehtävien päiväkirja yhdistelmä palautus.

# Oppimispäiväkirja: Paikallinen git

[Päiväkirja 1](git-oppimispaivakirja/paivakirja1.md)

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Kirjoita tähän vastauksesi
En kokenut että mikään tehtävistä olisi ollut vaikea, oma lukivaikeus vain aiheutti pari töyssyä. Muuten tehtäväohjeet ja kurssimateriaalit olivat hyvät ja niistä oppi hyvin. 

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git --version | näyttää git version |
| git init | perustaa repositorin |
| git clone | Kloonaa toisen repon |
| git status | näyttää git tilan |
| git add | lisää tiedoston talletukseen |
| git commit | tekee varsinaisen talletuksen |
| git log | näyttää commit talletukset |
| git rm | poistaa valitun tiedoston |
| git mv | muuttaa tiedoston nimen tai sijainnin |
| git tag | lisää talletukseen tunnisteen |
| git reset | peruuttaa add talletuksen tiedosto lisäyksen |
| git restore | peruuttaa työtilaan tehdyn muutoksen ennen talletusta |
| git revert | palauttaa edellisen commit talletuksen |
| git branch | tekee uuden haaran |
| git switch | vaihtaa valittuun haaraan |
| git merge | yhdistää valitun haaran master haaraan |

# Oppimispäiväkirja: Hajautettu git

[Päiväkirja 2](git-oppimispaivakirja/paivakirja2.md)

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Mielestäni kaikki tehtävässä oli helppoa, ohjeet olivat selvät sekä kurssi materiaali selkeää. Esteitä ei ollut.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git remote add origin https://github.com/motorpengus/git_versionhallinta.git | lisää remote repositorin |
| git remote -v | näyttää remote repot |
| git push origin master | lisää paikallisen repon sisällöt etärepoon |
| git fetch | hakee etäreposta sisällöt paikallisrepoon |
| git checkout origin/master | vaihtaa branchin demottavaan etärepon ja paikallisrepon branch yhdistelmään |
| git merge origin/master | yhdistää demottavan branchin ja master branchin |

# Oppimispäiväkirja: Git projektissa

[Päiväkirja 3](git-oppimispaivakirja/paivakirja3.md)

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

asioita voisi testata ennen kuin niitä lisäisi lopullisesti käyttöön

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

muokkauksia voidaan tehdä samanaikaisesti, sekä ongelmia on helpompi ratkoa

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

1. Älä koodaa koskaan Main haaraan
2. hae aina etäreposta päivitykset
3. luo uudeet haarat
4. kommentoi loogisesti commitit

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Opintojakso oli mielestäni hyvä, kurssin tehtävistä oppi hyvin git versionhallinnasta, kurssi materiaalit olivat selkeät, niissä ei ollut liikaa tietoa mutta ei myöskään liian vähän. 
