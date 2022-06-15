## 3. Feladat: Film register 

Készíts egy python applikációt (egy darab python fájlt), ami selenium-ot használ.  

A program töltse be a Film register app-ot a http://selenium.oktwebs.training360.com/sl10_proba_zarovizsga/film_register.html oldalról.

Feladatod, hogy automatizáld selenium webdriverrel a Film register app tesztelését.

### 1. Teszteld le, hogy betöltés után hány film jelenik meg az alkalmazásban! (24 db)

### 2. Teszteld le, hogy milyen módokon lehet a megjelent filmeket sorbarendezni! (három módon lehet)

### 3. Teszteld le, hogy fel lehet-e venni az alábbi adatokkal egy új filmet:
    * Film title: Black widow
    * Release year: 2021
    * Chronological year of events: 2020
    * Trailer url: https://www.youtube.com/watch?v=Fp9pNPdNwjI
    * Image url: https://m.media-amazon.com/images/I/914MHuDfMSL._AC_UY327_FMwebp_QL65_.jpg
    * Film summary: https://www.imdb.com/title/tt3480822/




Az ellenőrzésekhez __NEM__ kell teszt keretrendszert használnod (mint pl. a pytest), viszont fontos, hogy `assert` összehasonlításokat használj!

### A megoldás beadása
* A megoldásodat `film_register.py` néven, a `hf-tesztelo-strk2-halado` szervezet alá létrehozott `vezeteknev_keresztnev` privát github repodban egy `proba_zarovizsga` nevű mappába helyezd el!
* A lokálisan kidolgozott megoldásokat előbb commitold `git commit`, majd ne felejtsd el a `git push` segítségével a github szerverre is felküldeni! 
* Ne felejtsd el, hogy pontokat ér a szintaktikai legjobb praktikák megvalósítása! (`ctlr`+`alt`+`l`)
* Akkor is add be megoldásod, ha nem vagy benne biztos, mert részpontokat érhet minden, a tárgyhoz kötődő kód.
* A megoldás fájlba írj kommentet, amiben elmagyarázod, hogy mit akartál csinálni. Ne vidd túlzásba, de ne is legyen komment nélkül leadott fájlod.
* Nem beadott, vagy üres fájl formájában beadott feladat megoldás `0` pontot ér :(