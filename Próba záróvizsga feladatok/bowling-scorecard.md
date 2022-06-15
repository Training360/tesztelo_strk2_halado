## 4. Feladat: Bowling eredménylap

Készíts egy python applikációt (egy darab python fájlt), ami selenium-ot használ.

A program töltse be a Bowling eredménylap app-ot a http://selenium.oktwebs.training360.com/sl10_proba_zarovizsga/bowling-scorecard.html oldalról.
Az app az egyes gurításokat, az azok alkalmával eldöntött bábuk számát, illetve az így előálló pontszámokat tartja nyilván.

Feladatod, hogy automatizáld selenium webdriverrel az alábbi funkcionalitásokat a Bowling eredménylap appban:

### 1. Üres eredmény kártya:
    * Mind a 10 gurítási mező üres.
    * Mind a 10 összegző mező üres.

### 2. Csak strike gurítások (egymás után 11 elsőre letaroljuk mind a tíz bábut):    
    * Ellenőrizzük, hogy ezek az összegek szerepelnek: [10,20,40,60,80,100,120,140,160,200]

### 3. Lehetetlen gurítások:
    * Előbb 6, majd 5 bábu ledöntését adminisztráljuk.
    * Ellenőrizzük, hogy a hibaüzenet ezt írja-e: `Invalid Roll - there are only ten pins!`


Az ellenőrzésekhez __NEM__ kell teszt keretrendszert használnod (mint pl. a pytest), viszont fontos, hogy `assert` összehasonlításokat használj!

### A megoldás beadása
* A megoldásodat `bowling.py` néven, a `hf-tesztelo-strk2-halado` szervezet alá létrehozott `vezeteknev_keresztnev` privát github repodban egy `proba_zarovizsga` nevű mappába helyezd el!
* A lokálisan kidolgozott megoldásokat előbb commitold `git commit`, majd ne felejtsd el a `git push` segítségével a github szerverre is felküldeni! 
* Ne felejtsd el, hogy pontokat ér a szintaktikai legjobb praktikák megvalósítása! (`ctlr`+`alt`+`l`)
* Akkor is add be megoldásod, ha nem vagy benne biztos, mert részpontokat érhet minden a tárgyhoz kötődő kód.
* A megoldás fájlba írj kommentet, amiben elmagyarázod, hogy mit akartál csinálni. Ne vidd túlzásba, de ne is legyen komment nélkül leadott fájlod.
* Nem beadott, vagy üres fájl formájában beadott feladat megoldás `0` pontot ér :(
