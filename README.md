##H5

Tehtävänanto:

h5. Tee moduli git-varastoon ja kirjoita raportti sinne MarkDownilla.

(lähde: http://terokarvinen.com/2016/aikataulu-palvelinten-hallinta-ict4tn022-1-5-op-uusi-o$

##Tehtävän aloitus

Boottaan linuxin livetikulta ja avaan terminaalin. Ensimmäiseksi ajan komennot
* setxkbmap fi
* sudo apt-get update

Ja asennan gitin komennolla
* sudo apt-get install -y git

##Gitin käyttö

Tämän jälkeen teen kotihakemistooni _harjoitus_ nimisen kansion, johon kloonaan repositorion jonka loin GitHub sivustolle. Kopioin GitHubista repositorioni urlin ja syötän komennon 
* **git clone https://github.com/oonalinnea/asennus.git**.

Kloonaus onnistuu, joten tämän jälkeen menen _asennus_ kansioon, johon luon _README.md_ tiedoston. 

Kirjoitan tiedostoon hieman tätä kyseistä raporttia jonka jälkeen tallennan tiedoston. Ajan komennon **git add .** ja **git commit**, jonka jälkeen git pyytää antamaan sähköpostiosoitteeni ja nimeni, koska tämä on ensimmäinen kerta kun käytän gittiä. Syötän tiedot komennoilla **git config --global user.email "sähköpostiosoite"** ja **git config --global user.name "oma nimi"**. Tämän jälkeen ajan komennon **git pull** ja **git push**, joka vaatii githubin tunnuksen ja salasanan syöttämistä. Syötän tarvittavat tiedot, jonka jälkeen päivitän githubin ja _README.md_ on ilmestynyt sinne. Gitin käyttö siis onnistui ja toimii. Ajan myös tässä välissä komennon **git config --global credential.helper "cache --timeout=3600"**, jotta minun ei tarvitse jatkuvasti syöttää käyttäjänimeäni ja salasanaani. 

##Moduuli

Luon _asennus_ kansioon uuden kansion nimeltä _manifests_, johon luon tiedoston _init.pp_. Tiedostoon kopion moduulin edellisistä harjoituksistani, joka asentaa apachen. Tallennan tiedoston ja ajan taas komennot **git add . && git commit && git pull && git push**. Päivitän githubin ja kansio ja init.pp tiedosto ovat päivittyneet näkyville. 

##Yhteenveto
Tehtävä oli suhteellisen helppo, mutta sen avulla oppi hyvin gitin perusteet ja käytön. Katsoin myös vinkkejä http://www.markdowntutorial.com/ -sivulta siihen, miten Markdownilla pystyy muotoilemaan tekstiä, jotta saisin raportistani selkeämmän näköisen.

