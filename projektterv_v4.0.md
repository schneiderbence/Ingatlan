# UniHome Teljes körű ingatlan szolgáltatás
## Projektterv 2019

## 1. Összefoglaló 
A projekt célja a UniHome teljes körű ingatlan szolgáltatás online rendszerének kialakítása, ami lehetővé teszi a vevők számára az eladó és kiadó ingatlanok közötti keresést, ahol kiválaszthatják a számukra megfelelő ingatlan típusát illetve város, alapterület, ár vagy szobák alapján szűrni közöttük. Az ingatlankezelők pedig feltudják tenni az eladó lakásaikat, elérhetőségeiket és reklámokat meg híreket is tudnak létrehozni az oldalon. 

## 2. Verzió

| Verzió |    Szerző    |     Dátum    |     Státusz     |                      Megjegyzés                     |
|:------:|:------------:|:------------:|:---------------:|:---------------------------------------------------:|
|   0.1  | Köles Bálint |  2019-09-22  |     Tervezet    |                     Projektterv                     |
|   0.2  | Köles Bálint |  2019-09-22  |     Tervezet    |                    Gantt diagram                    |
|   0.3  | Köles Bálint |  2019-09-28  |     Tervezet    |                    Feladatok újraosztása            |
|   0.4  | Korom Richárd |  2019-10-02  |     Előterjesztés    |                    Apróbb módosítások            |
Státusz osztályozás:
 - Tervezet: befejezetlen dokumentum
 - Előterjesztés: a projekt menedzser bírálatával
 - Elfogadott: a megrendelő által elfogadva

## 3. A projekt bemutatása
Ez a projektterv a UniHome teljes körű ingatlan szolgáltatást mutatja be, mely 2019.09.05-től 2019.11.28-ig tart. A projekt célja egy ingatlan közvetítő oldal online rendszerének kialakítása, ami lehetővé teszi a vevők számára az eladó vagy kiadó ingatlanok vásárlását.

### 3.1. Rendszerspecifikáció
A vevők tudnak keresni az eladó vagy kiadó ingatlan között, ahol kiválaszthatják a számukra megfelelő ingatlan típusát illetve város, alapterület, ár vagy szobák alapján szűrni közöttük, és fel tudják venni a kapcsolatot az ingatlankezelőkkel. Ingatlankezelői oldalon lakások hirdetéseit fel tudják tenni az ingatlankezelők, ahol megadhatják a lakások adatait:  címét, típusát, árát, szobákat, állapotát, leírást, extrákat és az ingatlankezelőjét a lakásnak. Az új ingatlankezelők felvételét is megtudják tenni, az elérhetőségeiket megadni és reklámokat is tudnak létrehozni az oldalon. 

### 3.2. Funkcionális követelmények
A vevők számára lehetővé teszi az oldal az eladó ingatlanok közötti keresést, ahol kiválaszthatják a számukra megfelelő ingatlan típusát illetve város, alapterület, ár vagy szobák alapján szűrni közöttük. Az ingatlankezelők pedig menedzselni tudják az ingatlanok hirdetését, elérhetőségeiket feltenni és reklámokat létrehozni. A rendszer fejlesztése közben az egyszerűségre és az átláthatóságra törekedtünk, hogy mind a vevők illetve ingatlankezelők számára egyszerűen kezelhető legyen.

### 3.3. Nem funkcionális követelmények
•	Webes felületen való megvalósítás
•	Könnyen kezelhető
•	Gyors válaszidő
•	Stílusos, könnyen átlátható megjelenés

## 4. Költség- és erőforrás-szükségletek
Az erőforrásigényünk kb. 36 személynap.
A rendelkezésünkre áll 360 pont.

## 5. Szervezeti felépítés és felelősségmegosztás
A projekt megrendelője Dr. Kertész Attila. Az UniHome teljes körű ingatlan szolgáltatás projektet a projektcsapat fogja végrehajtani, amely az Ingatlan.

### 5.1 Projektcsapat
A projekt a következő emberekből áll:

|                                              |        Név        |   E-mail cím (stud-os) |
|:--------------------------------------------:|:-----------------:|:----------------------:|
|                  Megrendelő                  |Dr. Kertész Attila | keratt@inf.u-szeged.hu |
|               Projekt menedzser              |   Korom Richárd   |h878932@stud.u-szeged.hu|
|  Adatbázisért és adatkapcsolatokért felelős  |    Simon Péter    |h867487@stud.u-szeged.hu|
|       Felhasználói felületekért felelős      |   Hörömpő László  |h868520@stud.u-szeged.hu|
|    A rendszer működési logikájáért felelős   |     Géczi Ákos    |h863174@stud.u-szeged.hu|
|            Dokumentációért felelős           |    Köles Bálint   |h454712@stud.u-szeged.hu|
|            Prezentációért felelős            |   Schneider Bence |h774110@stud.u-szeged.hu|

## 6. A munka feltételei
### 6.1. Munkakörnyezet
A projekt a következő munkaállomásokat fogja használni a munka során:

A projekt alatt 6 db PC-t használunk, amelyeken Windows fut. A projektet Java-ban fogjuk létrehozni és a fejlesztéséhez a IntelliJ IDEA, Eclipse, Sublime-ot illetve Notepad++ fogjuk használni, továbbá az ingyenes Apache webkiszolgálót. Adatbázisnak a MySQL relációs adatbázis-kezelő szoftvert, amit XAMPP alatt fogunk futtatni.

### 6.2. Rizikómenedzsment

•	Technológiához való nem értés (nagy) – Előfordulható tudáshiány, melynek pótlása több időt is igénybe vehet. 2-3 személynap.
•	Munkaidő rosszul becslése – Tapasztalat hiányában, az egyes feladatokra szükséges idő alulbecslése. A csúszás a feladat komplexitásától függ.
•	Hardver hiba (közepes) – A csapat munkájához 6db PC áll rendelkezésre, ezek közül valamelyik meghibásodása legfeljebb 1-2 személynap csúszást okozhat. 
•	Betegség (közepes) – Tag feladataiban besegítés, esetleg teljes átvállalása/elosztása. 1 személynap
•	Projekthiba (közepes) – Programozási hiba mindig előfordulhat és ezen hibák felderítése akár 1 személynapot is igénybe vehet.
•	Dolgozat (kis) – Tag feladataiban besegítés.
•	Adatvesztés (kis) – A projekt több számítógépen is megtalálható, továbbá felhőben is tárolva van így nem várható jelentős csúszás.

## 7. Jelentések
### 7.1. Munka menedzsment
A munkát Korom Richárd menedzseli. Feladata a megrendelővel a kapcsolat fenntartása, a megrendelő igényeinek kielégítése. Továbbá a csapattagok munkáinak kiosztása, határidők figyelése, a munkafolyamat szemmel tartása. Rendszeres csapatgyűlések megszervezése, bármiféle esetlegesen felmerülő probléma leggyorsabban történő megoldása.

### 7.2. Csoportgyűlések
A projekt hetente ülésezik, hogy megvitassák az azt megelőző hét problémáit, ill. megbeszéljék a következő hét feladatait. A megbeszélésről minden esetben a GitLabon Wiki készül, mely tartalmazza a következőket:
•	jelenlévők listája
•	megbeszélés helye, ideje
•	megbeszélt tevékenységek
•	felmerült kérdések, igények
Ezen kívül online kapcsolattartás is lesz TeamSpeak 3 segítségével.

### 7.3. Minőségbiztosítás
Az elkészült terveket a terveken nem dolgozó csapattársak közül átnézik, hogy megfelel-e a specifikációnak és az egyes diagramtípusok összhangban vannak-e egymással. A meglévő rendszerünk helyes működését a prototípusok bemutatása előtt a tesztelési dokumentumban leírtak végrehajtása alapján ellenőrizzük és összevetjük a specifikációval, hogy az elvárt eredményt kapjuk-e. További tesztelési lehetőségek: unit tesztek írása az egyes modulokhoz vagy a kód közös átnézése (code review) egy, a vizsgált modul programozásában nem résztvevő csapattaggal. Szoftverünk minőségét a végső leadás előtt javítani kell a rendszerünkre lefuttatott kódelemzés során kapott metrikaértékek  és szabálysértések figyelembevételével.
Az alábbi lehetőségek vannak a szoftver megfelelő minőségének biztosítására:
- Specifikáció és tervek átnézése (kötelező)
- Teszttervek végrehajtása (kötelező)
- Unit tesztek írása (választható)
- Kód átnézése (választható)

### 7.4. Átadás, eredmények elfogadása
A projekt eredményeit Dr. Kertész Attila fogja elfogadni. A projektterven változásokat csak Dr. Kertész Attila írásos kérés esetén Dr. Kertész Attila engedélyével lehet tenni. A projekt eredményesnek bizonyul, ha specifikáció helyes és határidőn belül készül el. Az esetleges késések pontlevonást eredményeznek. Az elfogadás feltételeire és beadás formájára vonatkozó részletes leírás Dr. Kertész Attila fő gyakorlatvezető honlapján olvasható.

### 7.5. Státuszjelentés
Minden leadásnál a projektmenedzser jelentést tesz a projekt haladásáról, és ha szükséges változásokat indítványoz a projektterven. Ezen kívül a megrendelő felszólítására a menedzser 3 munkanapon belül köteles leadni a jelentést. A gyakorlatvezetővel folytatott csapatmegbeszéléseken a megadott sablon alapján emlékeztetőt készít a csapat, amit a következő megbeszélésen áttekintenek és felmérik az eredményeket és teendőket. Továbbá gazdálkodnak az erőforrásokkal és szükség esetén a megrendelővel egyeztetnek a projektterv módosításáról.

## 8. A munka tartalma
### 8.1. Tervezett szoftverfolyamat modell és architektúra
A projekt fejlesztése során Vízesés modellt alkalmazunk, ami során a tervezésre és specifikációra nagy hangsúlyt fektetünk az elején és ezáltal a későbbi fázisokban minimalizáljuk a tervezési időket a projekt során. Biztosítja a követelmények rögzítését ezáltal strukturáltságot biztosít a fejlesztők számára. A megvalósításhoz PHP 7.3.9-es és Javascript nyelveket választottuk.

### 8.2. Átadandók és határidők
A főbb átadandók és határidők a projekt időtartama alatt a következők:

| Szállítandó |                 Neve                |   Határideje  |
|:-----------:|:-----------------------------------:|:-------------:|
|      D1     |       Projektterv és útmutató       |  2019-10-03   |
|    P1+D2    | UML és adatbázis tervek és bemutató |  2019-10-17   |
|    P1+D3    |      Prototípus I. és bemutató      |  2019-10-31   |
|    P2+D4    |      Prototípus II. és bemutató     |  2019-11-28   |

## 9. Feladatlista
Az UniHome teljes körű ingatlan szolgáltatás 2019. szeptember 05-én indult. A következőkben a tervezett feladatok részletes összefoglalása található:

### 9.1. Projektterv (1. mérföldkő)
Ennek a feladatnak a célja, hogy megbeszéljük, megtervezzük és dokumentáljuk, a követelmények által felállított feladatokat, elvárásokat. Kiosszuk a terveket a csapat tagjainak.
Felelősök: Köles Bálint
Tartam: 3 nap
Erőforrásigény: 3 személynap

### 9.2. UML és adatbázis tervek (2. mérföldkő)
Ennek a feladatnak az a célja, hogy a program működését, egyes moduljait és a köztük lévő kapcsolatokat is bemutassuk részletesebben.
Részfeladatai a következők:

#### 9.2.1. Use Case diagram
Felelősök: Simon Péter, Hörömpő László
Tartam: 1 nap
Erőforrásigény: 1 személynap

#### 9.2.2. Class diagram
Felelősök: Géczi Ákos
Tartam: 1 nap
Erőforrásigény: 1 személynap

#### 9.2.3. Sequence diagram
Felelősök: Köles Bálint, Schneider Bence
Tartam: 1 nap
Erőforrásigény: 1 személynap

#### 9.2.4. Egyed-kapcsolat diagram adatbázishoz
Felelősök: Simon Péter, Korom Richárd
Tartam: 3 nap 
Erőforrásigény: 3 személynap

#### 9.2.5. Package diagram
Felelősök: Hörömpő László
Tartam: 1 hét
Erőforrásigény: 1 személyhét

#### 9.2.6. Képernyőtervek
Felelősök: Hörömpő László
Tartam: 1 hét
Erőforrásigény: 1 személyhét

#### 9.2.7. Tesztesetek, teszttervek
Felelősök: Géczi Ákos
Tartam: 1 hét
Erőforrásigény: 1 személyhét

#### 9.2.8. Bemutató elkészítése és bemutatása
Felelősök: Schneider Bence, Korom Richárd
Tartam: 3 nap
Erőforrásigény: 3 személynap

### 9.3. Prototípus I. (3. mérföldkő)
Ennek a feladatnak az a célja, hogy a választott programozási nyelven, elkészítsük a projektünk első prototípusát. A tervek szerint ekkorra meg lesz valósítva az ingatlanok közötti keresés, kapcsolatfelvétel a ingatlankezelőkkel, ingatlankezelői oldalon pedig az ingatlanok hirdetéseinek és híreinek feltevése, és ekkorra meglesz az adatbázis is. Továbbá a grafikus felhasználói felület első prototípusa is. 
Részfeladatai a következők:

#### 9.3.1. Backend és Frontend összekötése
Felelősök:  Schneider Bence, Géczi Ákos
Tartam: 3 nap
Erőforrásigény: 3 személynap

#### 9.3.2. Bejelentkezés/Kijelentkezés megvalósítása
Felelősök: Géczi Ákos
Tartam: 2 nap
Erőforrásigény: 2 személynap

#### 9.3.3. Új Ingatlanügynökök felvételének a megvalósítása
Felelősök: Simon Péter
Tartam: 2 nap
Erőforrásigény: 2 személynap

#### 9.3.4. Új Ingatlanok felvételének a megvalósítása
Felelősök: Hörömpő László
Tartam: 2 nap
Erőforrásigény: 2 személynap

#### 9.3.5. Hirdetések megvalósítása
Felelősök: Schneider Bence
Tartam: 2 nap
Erőforrásigény: 2 személynap

#### 9.3.6. Adatbázis megvalósítása
Felelősök: Korom Richárd, Simon Péter
Tartam: 5 nap
Erőforrásigény: 5 személynap

#### 9.3.7. Ingatlanügynökök adatlapjainak a létrehozása
Felelősök: Simon Péter
Tartam: 2 nap
Erőforrásigény: 2 személynap

#### 9.3.8.  Ingatlan adatlapjainak a létrehozása
Felelősök: Schneider Bence
Tartam: 2 nap
Erőforrásigény: 2 személynap

#### 9.3.9.  Ingatlanok törlésének a megvalósítása
Felelősök: Hörömpő László
Tartam: 2 nap
Erőforrásigény: 2 személynap

#### 9.3.10.  Időpontok foglalásának a megvalósítása
Felelősök: Köles Bálint
Tartam: 2 nap
Erőforrásigény: 2 személynap

#### 9.3.11.  Weblap létrehozása
Felelősök: Hörömpő László
Tartam: 2 nap
Erőforrásigény: 2 személynap

#### 9.3.12.  Ingatlanok közötti keresés megvalósítása
Felelősök: Géczi Ákos
Tartam: 2 nap
Erőforrásigény: 2 személynap

#### 9.3.13. Tesztelési dokumentum
Felelősök:  Köles Bálint
Tartam: 3 nap
Erőforrásigény: 3 személynap

#### 9.3.14. Bemutató elkészítése és bemutatása
Felelősök: Schneider Bence, Géczi Ákos
Tartam: 3 nap
Erőforrásigény: 3 személynap

### 9.4. Prototípus II. (4. mérföldkő)
Ennek a feladatnak az a célja, hogy a program első prototípusában fellelt hibák kijavításra kerüljenek, illetve egyes programrészek továbbfejlesztése. Esetleges később felmerülő további funkciók megvalósítása.
Részfeladatai a következők:

#### 9.4.1. Dokumentációk, tervek új funkciókkal
Felelősök: Köles Bálint, Schneider Bence
Tartam: 1 nap
Erőforrásigény: 1 személynap

#### 9.4.2. Javított minőségű prototípus új funkciókkal
Felelősök: Géczi Ákos, Korom Richárd
Tartam: 3 hét
Erőforrásigény: 3 személyhét

#### 9.4.3. Tesztelési dokumentum új funkciókhoz
Felelősök: Simon Péter, Hörömpő László
Tartam: 3 nap
Erőforrásigény: 3 személynap

#### 9.4.4. Bemutató elkészítése és bemutatása
Felelősök: Korom Richárd, Köles Bálint
Tartam: 3 nap
Erőforrásigény: 3 személynap

## 10. Részletes időbeosztás
![Gantt diagram](https://lh3.googleusercontent.com/YMf4OyfWo1jfIEJZy6-zwUwwhBU1X-3KoQa0gRnHchIILGPXpNhaXmepDDTQ-IATr8t2MPeS7cd_PphlQbcCUg4CViPGy6H6w5B8hmU-6oSKiv6b0PdeXgHLqP5TJEM136ecTpN4oQZPR-wcAiePRn9BivZRxCTqm_oXT1-WX7c-RnV2HQ4QMri5mvEVvDh32fWIIZhVk2_14gaom-dchU8GZowNoqtO56xB8bR2BRqujbDGtfjSalBOYxKrAa-CWAmab18BTul1h1Q4hwKNGKeXz4HsTko3X84DeO21XedMee0eoA-sV_aimOHGSI9bv-2u7SKp_8eMz_t9M0OdqqpY6SdDIkcT5U_CL7z2GtYtAcJ1imjIAlqEhxCbaLx1ch9irgDXAQoOh3nXCf-VjcHk-o_cc4l3llm7dEU1KAdlYkNStW2E30_hD1aqLfJCjU1QRF43tL_fKHEG1tj3Wbe_xn_HEaTU0jZb2SYeD973MeJPE1D6oCy5AFiibgzHsRFz_O0yclj561vFx02xENjGM6mSaIdrObD0x4FxfSHCy8LcHaD4RDucqE8FPEU1yM66LnzYwn3WcDHAFLWU3OoE8Rcp9V9-IT-MEFN67oiJLGEL0d4oPPC0TkbZjNrKqZC7p05qFOXRDxY2RM0d6QEmhJuyzd7_8sJAg_6iUOLubgyh_zA=w1660-h484-no "Projektterv-Gantt")
![Gantt diagram](https://photos.app.goo.gl/gLLMa6J1mH9LkRg78 "Projektterv-Gantt")

## 11. Projekt költségvetés
### 11.1. Részletes költségvetés

|                     Név                    | 1. leadás - Projektterv | 2. leadás - UML és adatbázis | 3. leadás - Prototípus I. | 4. leadás - Prototípus II. | Összesen |
|:------------------------------------------:|:----------------------:|:--------------------------:|:-----------------------:|:------------------------:|:--------:|
| Min. és max. kapható  pontszám százalékban |          5-10%         |           15-40%           |          20-40%         |          20-40%          |          |
|              Korom Richárd                 |            4           |             17             |           22            |            17            |    60    |
|              Köles Bálint                  |            6           |             9              |           23            |            22            |    60    |
|              Schneider Bence               |            6           |             10             |           21            |            23            |    60    |
|              Géczi Ákos                    |            3           |             11             |           22            |            24            |    60    |
|              Hörömpő László                |            3           |             14             |           21            |            22            |    60    |
|              Simon Péter                   |            3           |             17             |           19            |            21            |    60    |

### 11.2. Átvétel
A projektet a megrendelő a következő eredménnyel vette át:

|                     Név                    | 1. leadás - Projektterv | 2. leadás - UML és adatbázis | 3. leadás - Prototípus I. | 4. leadás - Prototípus II. | Összesen |
|:------------------------------------------:|:----------------------:|:--------------------------:|:-----------------------:|:------------------------:|:--------:|
|              Korom Richárd                 |                        |                            |                         |                          |    60    |
|              Köles Bálint                  |                        |                            |                         |                          |    60    |
|              Schneider Bence               |                        |                            |                         |                          |    60    |
|              Géczi Ákos                    |                        |                            |                         |                          |    60    |
|              Hörömpő László                |                        |                            |                         |                          |    60    |
|              Simon Péter                   |                        |                            |                         |                          |    60    |

Szeged, 2019. szeptember 28.

#### &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Az átadó részéről &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Az átvevő részéről 

 

