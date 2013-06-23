---
title: Rendszertervezés
desc: Hatékonyan és gyorsan
preface: A rendszertervezésnél szempont a modularitás, a könnyű módosíthatóság és az áttekinthetőség.
author: Pató István <istvan.pato@vanio.com>
date: 2013-05-13 08:53
state: ALFA
template: layout.jade
---

### Rendszertervezés

A rendszertervezés sokrétű feladat. Figyelembe kell venni az üzleti modelt, logikát, informatika biztosnságot, a megbízhatóságot és nyomonkövethetőséget is. Szakembereink tapasztalata és módszereink együttesen garantálják a megfelelő rendszerterv elkészítését.

### Hogyan tervezünk rendszert?

Az idő folyamán szakemebereink sok rendszer tervezésében résztvettek, sok rendszertervet bíráltak. Mindebből tanultunk. Tudjuk, hogy a rendszer áttekinthetősége kulcsfontosságú, hiszen egy rendszer kivitelezésénél rengeteg ember résztvesz. Nem csupán pontosan, hanem gyorsan is kell megérteni egy-egy rendszer működését, hiszen az idő pénz. Ezért a rendszerek tervezésénél rengeteg egyeztetés szükséges, hogy minél jobban megértsük és később megértessük a tervet. Egyik irányelvünk: **a kevesebb több.** Nincs felesleges információ, a lényeget fogjuk meg olyan mértékben, hogy az később a részletes tervezés és kivitelezés alapja legyen, ezt architektúra tervekben foglaljuk össze.

### Architektúra tervek
Sokféle típusú architektúra terv készíthető. Ezek közül - az üzleti alkalmazások esetén -, a szoftver architektúra és a telepítési architektúra terveket szoktuk kidolgozni. Ezek elkészítése iterációk folyamán történik, ahol folyamatosan egyeztetünk a szereplőkkel. Az architektúra tervekben mintákat (patterns) használunk, amelyek a rendszertervezés szokásain és szabványain alapulnak, valamint publikusan elérhetőek.

### Tervezési szempontok
A tervezési szempontok sokrétűek. Alapvetően az üzleti logika és elvárásai mentés készülnek a tervek. Néhány egyéb tervezési szempont:

* teljesítmény
* rendelkezésre állás
* biztonság
* költségek
* üzemeltethetőség
* rugalmas változtathatóság
* modularitás
* érthetőség
* változás követhetősége
* tesztelhetőség
* bevett gyakorlat és szabványok használata
* nyílt szabványok és szoftverek

A tervezés folyamán olyan alapelveket (lean és agilis fejlesztés) használunk, amellyel folyamatosan törekszünk a rendszerterv méretének csökkentésére, így javítjuk a módosíthatóságot és az átláthatóságot, valamint csökkentjük a komplexitást.