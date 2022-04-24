## S13 Feladat: Hibakezelés megvalósítása

A feladatot külön python fájlban oldd meg! A feladat tartalmazza az elvárt fájlnevet! Csak ezen a néven fogadható el a megoldás.

Készíts egy Python alkalmazást, ami selenium-ot használ! Nyisson meg egy Chrome böngészöt és töltsön be egy tetszőleges weblapot az Internetről! Az oldalon próbáld megtalálni a `<div id="nemletezik"></div>` mezőt. A lényeg, hogy hibát dobjon a `driver.find_element(By.ID, " ")` függvény hívás. Feladatod, hogy kezeld le ezt a hibát és írj ki valami emberileg olvasható üzenetet. Extra feladatként készíts egy saját függvényt, ami bármilyen `find_element(By.ID)` lokátor hívásnál lekezeli a nemlétező elem típusú hibát! A megoldáshoz használj python `try` `except` struktúrát.
> A megoldást egy `S13_seleniumex.py` nevű fájlban kell beadnod!


### Feladat beadása
A fent említett python fájlt és benne a megoldásodat a `hf-tesztelo-strk2-halado` szervezet alá létrehozott `vezeteknev_keresztnev` privát github repodban egy `selenium1_hf` nevű mappába helyezd el!
