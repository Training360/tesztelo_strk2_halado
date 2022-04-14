## P16 Feladat: Python függvény tesztelése

A feladatot külön python fájlban oldd meg! A feladat tartalmazza az elvárt fájlnevet! Csak ezen a néven fogadható el a megoldás.

Készíts egy függvényt `ticket_counter(base, age, distance)` szignatúrával (a szignatúra a függvény neve és a paraméter listájának a közös elnevezése). A `base` a 100 km-re fizetendő összeg, az `age` az utazó életkora és a `distance` az utazási távolság. A vasúti szabályzat szerint 6 éves kor alatt és 65 év felett ingyen utazik, 6 és 18 éves kor között féláron utazik, egyébként teljes árat fizet.
A jegyár a következőképpen képződik: 
Minden megkezdett 100 km-re az utas `base` forintot fizet. A függvény számolja ki az életkor és a megadott utazási távolság alapján a tényleges jegyárat, és ezt adja vissza! 

A függvényt tesztelni is fogjuk. Ehhez írjuk meg a `pytest` által megkövetelt formájú teszteseteket. Külön tesztesetben vizsgáljuk a nyugdíjas által fizetendő jegyárat, a reguláris jegy árát és a diákok által fizetendő jegyárat (6 és 18 év között).
Egy teszteset szignatúrája például a következő lehet: `test_ticket_counter_regular()` 

> A megoldást egy `test_ticket_counter_P16.py` nevű fájlban kell beadnod!
    
### Feladat beadása
A fent említett python fájlt és benne a megoldásodat a `hf-tesztelo-strk2-halado` szervezet alá létrehozott `vezeteknev_keresztnev` privát github repodban egy `python1_hf` nevű mappába helyezd el!