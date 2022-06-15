## 2. Feladat: Hogwarts express jegyautomata

A Hogwarts express nemrég rájött, hogy érdemes lenne önkiszolgálóvá tenni a jegykiállító rendszert a hallgatók
vasútvonalán. Lehet, hogy drágák a baglyok.

Itt találod az önkiszolgáló webes applikáció prototípusát: http://selenium.oktwebs.training360.com/sl10_proba_zarovizsga/hogwarts.html

Feladatod, hogy automatizáld selenium webdriverrel a jegyautomata által kiadott jegyek tesztelését.


### 1. Teljes kitöltés esete:
    * név: Harry Potter
    * indulás napja: 2022. szeptember 1.
    * indulás időpontja: délelőtt tíz óra
    * A jegyen minden adat megjelenik , ill. az ellenőrző szelvényen az idő adatok is.

### 2. Részleges kitöltés esete:
    * név: 
    * indulás napja: 2022. szeptember 1.
    * indulás időpontja: délelőtt tíz óra
    * Minden megadott adat megjelenik a jegyen, ill. az ellenőrző szelvényen. 

### 3. Hiányos kitöltés esete:
    * név: Harry Potter
    * indulás napja: 2022. 
    * indulás időpontja: délelőtt tíz óra
    * Sikertelen a jegy kibocsátás, nem jelenik meg semmilyen megadott adat a jegyen.


A nyelvi beállítások befolyásolják a megjelenített időt! Neked a saját beállításaidhoz passzoló nyelven kell az ellenőrzéseket elvégezni!
Az ellenőrzésekhez __NEM__ kell teszt keretrendszert használnod (mint pl. a pytest), viszont fontos, hogy `assert` összehasonlításokat használj!


### A megoldás beadása
* A megoldásodat `hogwarts.py` néven, a hf-tesztelo-strk2-halado szervezet alá létrehozott vezeteknev_keresztnev privát github repodban egy `proba_zarovizsga` nevű mappába helyezd el!
* A lokálisan kidolgozott megoldásokat előbb commitold `git commit`, majd ne felejtsd el a `git push` segítségével a github szerverre is felküldeni! 
* Ne felejtsd el, hogy pontokat ér a szintaktikai legjobb praktikák megvalósítása! (`ctlr`+`alt`+`l`)
* Akkor is add be megoldásod, ha nem vagy benne biztos, mert részpontokat érhet minden, a tárgyhoz kötődő kód.
* A megoldás fájlba írj kommentet, amiben elmagyarázod, hogy mit akartál csinálni. Ne vidd túlzásba, de ne is legyen komment nélkül leadott fájlod.
* Nem beadott, vagy üres fájl formájában beadott feladat megoldás `0` pontot ér :(