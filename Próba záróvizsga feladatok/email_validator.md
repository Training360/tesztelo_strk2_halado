## 1. Feladat: Email mező

Készíts egy python applikációt (egy darab python fájlt), ami selenium-ot használ. 

A program töltse be az Email mező app-ot a http://selenium.oktwebs.training360.com/sl10_proba_zarovizsga/email_validator.html oldalról.

Feladatod, hogy automatizáld selenium webdriverrel az Email mező app tesztelését.

A cél az email validáció tesztelése:

### 1. Helyes kitöltés esete:
    * email: teszt@elek.hu
    * Nincs validációs hiba	üzenet

### 2. Helytelen kitöltés esete:
    * email: teszt@
    * Please enter a part following '@'. 'teszt@' is incomplete. *vagy* Kérjük, adja meg a „@” utáni részt is. A(z) „teszt@” cím nem teljes.

### 3. Üres kitöltés esete:
    * email: <üres>
    * Please fill out this field. *vagy* Kérjük, töltse ki ezt a mezőt.


A nyelvi beállítások befolyásolják a megjelenített üzenetet! Neked a saját beállításaidhoz passzoló nyelven kell az ellenőrzéseket elvégezni!
Az ellenőrzésekhez __NEM__ kell teszt keretrendszert használnod (mint pl. a pytest), viszont fontos, hogy `assert` összehasonlításokat használj!

### A megoldás beadása
* A megoldásodat `email_validator.py` néven, a `hf-tesztelo-strk2-halado` szervezet alá létrehozott `vezeteknev_keresztnev` privát github repodban egy `proba_zarovizsga` nevű mappába helyezd el!
* A lokálisan kidolgozott megoldásokat előbb commitold `git commit`, majd ne felejtsd el a `git push` segítségével a github szerverre is felküldeni! 
* Ne felejtsd el, hogy pontokat ér a szintaktikai legjobb praktikák megvalósítása! (`ctlr`+`alt`+`l`)
* Akkor is add be megoldásod, ha nem vagy benne biztos, mert részpontokat érhet minden a tárgyhoz kötődő kód.
* A megoldás fájlba írj kommentet, amiben elmagyarázod, hogy mit akartál csinálni. Ne vidd túlzásba, de ne is legyen komment nélkül leadott fájlod.
* Nem beadott, vagy üres fájl formájában beadott feladat megoldás `0` pontot ér :(