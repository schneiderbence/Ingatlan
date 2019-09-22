# `MINTA` Projektterv 2019

## 1. Összefoglaló 
`Ide írd le tömören, hogy miről szól a projekt, amit a gyakorlatvezetőtől kaptatok. Mik a fő célok, miért van rá szükség. A dokumentumban a pirossal kiemelt szövegeknek két jelentése van: (a) sablon szöveg, amit le kell cserélni, pl. gyakorlatvezető neve; (b) segítő/magyarázó szöveg. Az átadott dokumentumban nem szerepelhetnek pirossal kiemelt részek! A feketével írt részek maradhatnak, azok közösek.`
A projekt célja az UniHome ingatlan közvetítő oldal online rendszerének kialakítása,
 ami lehetővé teszi a vevők számára az eladó vagy kiadó ingatlanok vásárlását, az ingatlanok típusának kiválasztását illetve város, alapterület, ár vagy szobák alapján szűrni közöttük.
 Az ingatlankezelők pedig feltudják tenni a lakásaikat és menedzselni tudják az időpontjaikat a vevőkkel. 
## 2. Verzió


| Verzió |    Szerző    |     Dátum    |     Státusz     |                      Megjegyzés                     |
|:------:|:------------:|:------------:|:---------------:|:---------------------------------------------------:|
|   0.1  | Köles Bálint |  2019-09-22  |     Tervezet    |                     Projektterv                     |

Státusz osztályozás:
 - Tervezet: befejezetlen dokumentum
 - Előterjesztés: a projekt menedzser bírálatával
 - Elfogadott: a megrendelő által elfogadva

## 3. A projekt bemutatása
Ez a projektterv az UniHome ingatlan közvetítő oldalt mutatja be, mely 2019.09.05-től 2019.11.28-ig tart. A projekt célja egy ingatlan közvetítő oldal online rendszerének kialakítása,
 ami lehetővé teszi a vevők számára az eladó vagy kiadó ingatlanok vásárlását.

### 3.1. Rendszerspecifikáció
`Ide írd le részletesen, hogy mit fog tudni a rendszer (funkcionalitás, célok), amit a projekt keretében megvalósítotok. Mik a megrendelő és a felhasználók igényei? Miért van szükség a projektre? (5-7 mondat)`
Vevők regisztrációja, bejelentkezés, kijelentkezés, felhasználói adatok módosítása, ingatlanok közötti keresés. Adminisztrációs felületen regisztrált felhasználók kezelése, ingatlankezelők
felvétele, ingatlankezelők időpontjainak a kezelése.
### 3.2. Funkcionális követelmények
`Ide kerülnek a rendszerrel szemben támasztott funkcionális igények: mit kell a rendszernek tudnia`
A vevőknek lehetősége van böngészni az ingatlanok között ár, terület, város és szobák alapján. Regisztráció után a vevőknek lehetősége van időpontot foglalni az ingatlankezelőknél
és akár megvásárolni az ingatlant. Az ingatlankezelők pedig menedzselni tudják az időpontjaikat és ingatlanaik hirdetését feltenni. A rendszer fejlesztése közben az egyszerűségre és az átláthatóságra törekedtünk, hogy mind a vevők illetve ingatlankezelők számára 
egyszerűen kezelhető legyen.
### 3.3. Nem funkcionális követelmények
`A rendszer nem funkcionális követelményei, pl.: milyen környezetben fusson, milyen teljesítményt kell produkálnia, milyen megjelenéssel kell rendelkeznie`
•	Webes felületen való megvalósítás
•	Könnyen kezelhető
•	Gyors válaszidő
•	Stílusos, könnyen átlátható megjelenés
## 4. Költség- és erőforrás-szükségletek
Az erőforrásigényünk kb. 36 személynap.
A rendelkezésünkre áll 360 pont.
`(Becsült sarokszámok, a rendelkezésre álló erőforrás fejenként 8-10 személynap)`

## 5. Szervezeti felépítés és felelősségmegosztás
A projekt megrendelője Dr. Kertész Attila. Az UniHome ingatlan közvetítő oldal projektet a projektcsapat fogja végrehajtani, amely a 3-as.

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
 - `Milyen és hány gépet használ a projekt, milyen szoftverkörnyezetben, stb.`
A projekt alatt 6 db PC-t használunk, amelyeken Windows fut. A Java és Javascript alapú projekt fejlesztéséhez az Eclipse IDE, ingyenesen letölthető,
 platform független szoftverkeretrendszert használjuk, továbbá az  Apache, szintén ingyenes, webkiszolgálót. Adatbázisnak a MySQL relációs 
 adatbázis-kezelő szoftvert, amit XAMPP alatt fogunk futtatni.
### 6.2. Rizikómenedzsment
 - `Rizikótényező (hatás):
(Leírni, mit jelent, megbecsülni a besorolást (valószínűség/hatás), ami lehet kis, közepes és nagy). (pl. betegség, szoftver-hardver probléma, stb..)`
•	Technológiához való nem értés (nagy) – Előfordulható tudáshiány, melynek pótlása több időt is igénybe 
vehet. 2-3 személynap.
•	Munkaidő rosszul becslése – Tapasztalat hiányában, az egyes feladatokra szükséges idő alulbecslése. A csúszás a feladat komplexitásától függ.
•	Hardver hiba (közepes) – A csapat munkájához 6db PC áll rendelkezésre, ezek közül valamelyik meghibásodása legfeljebb 1-2 személynap csúszást okozhat. 
•	Betegség (közepes) – Tag feladataiban besegítés, esetleg teljes átvállalása/elosztása. 1 személynap
•	Projekthiba (közepes) – Programozási hiba mindig előfordulhat és ezen hibák felderítése akár 1 személynapot is igénybe vehet.
•	Dolgozat (kis) – Tag feladataiban besegítés.
•	Adatvesztés (kis) – A projekt több számítógépen is megtalálható, továbbá felhőben is tárolva van így várható jelentős csúszás.

## 7. Jelentések
### 7.1. Munka menedzsment
`A munkát xy menedzseli…
(Ki menedzseli a munkát (általában a project menedzser). Le kell írni, hogy mik a feladatai, és azokat hogyan hajtja végre.)`
A munkát Korom Richárd menedzseli. Feladata a megrendelővel a kapcsolat fenntartása, a megrendelő igényeinek kielégítése. 
Továbbá a csapattagok munkáinak kiosztása, határidők figyelése, a munkafolyamat szemmel tartása. Rendszeres csapatgyűlések megszervezése, 
bármiféle esetlegesen felmerülő probléma leggyorsabban történő megoldása.
### 7.2. Csoportgyűlések

`A projekt hetente ülésezik, hogy megvitassák az azt megelőző hét problémáit, ill. megbeszéljék a következő hét feladatait. A megbeszélésről minden esetben MEMO készül, mely tartalmazza a következőket: jelenlévők listája, megbeszélés helye és ideje, megbeszélt tevékenységek, felmerült kérdések, igények, azaz hogy betekintést kapjunk hogyan szerveződnek, zajlanak a csoportgyűlések)`
A projekt hetente ülésezik, hogy megvitassák az azt megelőző hét problémáit, ill. megbeszéljék a következő hét feladatait. A megbeszélésről minden esetben MEMO készül, mely tartalmazza a következőket:
•	jelenlévők listája
•	megbeszélés helye, ideje
•	megbeszélt tevékenységek
•	felmerült kérdések, igények
Ezen kívül online kapcsolattartás is lesz TeamSpeak 3 segítségével.

### 7.3. Minőségbiztosítás
Az elkészült terveket a terveken nem dolgozó csapattársak közül átnézik, hogy megfelel-e a specifikációnak és az egyes diagramtípusok összhangban vannak-e egymással.
 A meglévő rendszerünk helyes működését a prototípusok bemutatása előtt a tesztelési dokumentumban leírtak végrehajtása alapján ellenőrizzük és összevetjük a specifikációval,
 hogy az elvárt eredményt kapjuk-e. További tesztelési lehetőségek: unit tesztek írása az egyes modulokhoz vagy a kód közös átnézése (code review) egy, a vizsgált modul
 programozásában nem résztvevő csapattaggal. Szoftverünk minőségét a végső leadás előtt javítani kell a rendszerünkre lefuttatott kódelemzés során kapott metrikaértékek 
 és szabálysértések figyelembevételével.
Az alábbi lehetőségek vannak a szoftver megfelelő minőségének biztosítására:
- Specifikáció és tervek átnézése (kötelező)
- Teszttervek végrehajtása (kötelező)
- Unit tesztek írása (választható)
- Kód átnézése (választható)

### 7.4. Átadás, eredmények elfogadása
A projekt eredményeit Dr. Kertész Attila fogja elfogadni. A projektterven változásokat csak  Dr. Kertész Attila írásos kérés esetén Dr. Kertész Attila engedélyével lehet tenni.
 A projekt eredményesnek bizonyul, ha specifikáció helyes és határidőn belül készül el. Az esetleges késések pontlevonást eredményeznek.
Az elfogadás feltételeire és beadás formájára vonatkozó részletes leírás Kertész Attila fő gyakorlatvezető honlapján olvasható.

### 7.5. Státuszjelentés
Minden leadásnál a projektmenedzser jelentést tesz a projekt haladásáról, és ha szükséges változásokat indítványoz a projektterven.
 Ezen kívül a megrendelő felszólítására a menedzser 3 munkanapon belül köteles leadni a jelentést. A gyakorlatvezetővel folytatott csapatmegbeszéléseken
 a megadott sablon alapján emlékeztetőt készít a csapat, amit a következő megbeszélésen áttekintenek és felmérik az eredményeket és teendőket. 
 Továbbá gazdálkodnak az erőforrásokkal és szükség esetén a megrendelővel egyeztetnek a projektterv módosításáról.

## 8. A munka tartalma
### 8.1. Tervezett szoftverfolyamat modell és architektúra
`Milyen szoftverfolyamat modellt követve állítja elő a csapat a specifikációnak megfelelő prototípusokat? Miért ezt választja? (gyakorlatvezetővel megbeszélve)
A gyakorlatvezetővel egyeztetve a csapat milyen architektúrát választ a projekt megvalósításához? Milyen nyelven? Milyen rétegek (logikai, adat, GUI)?`
A projekt fejlesztése során Vízesés modellt alkalmazunk, ami során a tervezésre és specifikációra nagy hangsúlyt fektetünk az elején és ezáltal a későbbi fázisokban 
minimalizálja a tervezési időket a projekt során. Biztosítja a követelmények rögzítését ezáltal strukturáltságot biztosít a fejlesztők számára. A megvalósításhoz Java nyelvet választottuk.
### 8.2. Átadandók és határidők
A főbb átadandók és határidők a projekt időtartama alatt a következők:

| Szállítandó |                 Neve                |   Határideje  |
|:-----------:|:-----------------------------------:|:-------------:|
|      D1     |       Projektterv és útmutató       |  2019-10-03   |
|    P1+D2    | UML és adatbázis tervek és bemutató |  2019-10-17   |
|    P1+D3    |      Prototípus I. és bemutató      |  2019-10-31   |
|    P2+D4    |      Prototípus Ii. és bemutató     |  2019-11-28   |

## 9. Feladatlista

Az UniHome ingatlan közvetítő oldal 2019. szeptember 05-én indult. A következőkben a tervezett feladatok részletes összefoglalása található:

### 9.1. Projektterv (1. mérföldkő)
Ennek a feladatnak a célja, hogy megbeszéljük, megtervezzük és dokumentáljuk, a követelmények által felállított feladatokat, elvárásokat. Kiosszuk a terveket a csapat tagjainak,
Felelősök: Köles Bálint
Tartam: 3 nap
Erőforrásigény: 3 személynap

### 9.2. UML és adatbázis tervek (2. mérföldkő)
Ennek a feladatnak az a célja, hogy a program működését, egyes moduljait és a köztük lévő kapcsolatokat is bemutassuk részletesebben.
Részfeladatai a következők:

#### 9.2.1. Use Case diagram
Felelősök: Köles Bálint
Tartam: 1 nap
Erőforrásigény: 1 személynap`

#### 9.2.2. Class diagram
Felelősök: Schneider Bence
Tartam: 1 nap
Erőforrásigény: 1 személynap`

#### 9.2.3. Sequence diagram
Felelősök: Simon Péter
Tartam: 1 nap
Erőforrásigény: 1 személynap`

#### 9.2.4. Egyed-kapcsolat diagram adatbázishoz
Felelősök: Géczi Ákos
Tartam: 1 nap
Erőforrásigény: 1 személynap`

#### 9.2.5. Package diagram
Felelősök: Simon Péter
Tartam: 1 hét
Erőforrásigény: 1 személyhét`

#### 9.2.6. Képernyőtervek
Felelősök: Hörömpő László
Tartam: 1 hét
Erőforrásigény: 1 személyhét`

#### 9.2.7. Tesztesetek, teszttervek
Felelősök: Korom Richárd
Tartam: 1 hét
Erőforrásigény: 1 személyhét`

#### 9.2.8. Bemutató elkészítése és bemutatása
Felelősök: Schneider Bence
Tartam: 1 hét
Erőforrásigény: 1 személyhét

### 9.3. Prototípus I. (3. mérföldkő)
`Ennek a feladatnak az a célja, hogy… `
Ennek a feladatnak az a célja, hogy a választott programozási nyelven (JAVA), elkészítsük a projektünk első prototípusát. A tervek szerint ekkorra meg lesz valósítva a regisztráció,
bejelentkezése, ingatlanok közötti keresés, időpont foglalás a ingatlankezelőknél és ekkorra meglesz hozzá az adatbázis is. Továbbá a grafikus felhasználói felület első prototípusa is. 
Részfeladatai a következők:

#### 9.3.1. Prototípus
Felelősök: Korom Richárd, Köles Bálint, Schneider Bence, Géczi Ákos, Simon Péter, Hörömpő László
Tartam: 9 nap
Erőforrásigény: 9 személynap`

#### 9.3.2. Tesztelési dokumentum
Felelősök: Korom Richárd, Hörömpő László
Tartam: 3 hét
Erőforrásigény: 3 személyhét`

#### 9.3.3. Bemutató elkészítése és bemutatása
Felelősök: Schneider Bence, Géczi Ákos
Tartam: 3 hét
Erőforrásigény: 3 személyhét`

### 9.4. Prototípus II. (4. mérföldkő)
`Ennek a feladatnak az a célja, hogy… `
Ennek a feladatnak az a célja, hogy a program első prototípusában fellelt hibák kijavításra kerüljenek, 
illetve egyes programrészek továbbfejlesztése. Esetleges később felmerülő további funkciók megvalósítása.
Részfeladatai a következők:

#### 9.4.1. Dokumentációk, tervek új funkciókkal
Felelősök: Köles Bálint, Schneider Bence
Tartam: 1 nap
Erőforrásigény: 1 személynap`

#### 9.4.2. Javított minőségű prototípus új funkciókkal
Felelősök: Köles Bálint, Géczi Ákos
Tartam: 1 hét
Erőforrásigény: 1 személyhét`

#### 9.4.3. Tesztelési dokumentum új funkciókhoz
Felelősök: Simon Péter, Hörömpő László
Tartam: 3 nap
Erőforrásigény: 3 személynap`

#### 9.4.4. Bemutató elkészítése és bemutatása
Felelősök: Korom Richárd
Tartam: 2 nap
Erőforrásigény: 2 személynap`

 `(Részletesebb leírás minden egyes számozott feladatról, feltüntetve hogy ki a felelőse. Ha az eredmény egy átadandó, akkor azt fel kell tüntetni. Részfeladatokat is fel lehet sorolni egy listában. Meg kell hogy feleljen az esetleges Gantt-chartban szereplőkkel.)`

## 10. Részletes időbeosztás
`(Szöveges: feladat sorszáma, mettől-meddig. Ide kell berakni a Gantt chartot pl.:`)

## 11. Projekt költségvetés
### 11.1. Részletes költségvetés
`(Az egyes leadások alkalmával teljesíthető pontszámot kell beírni minden emberre külön-külön.)`

|                     Név                    | 1. leadás - Projektterv | 2. leadás - UML és adatbázis | 3. leadás - Prototípus I. | 4. leadás - Prototípus II. | Összesen |
|:------------------------------------------:|:----------------------:|:--------------------------:|:-----------------------:|:------------------------:|:--------:|
| Min. és max. kapható  pontszám százalékban |          5-10%         |           15-40%           |          20-40%         |          20-40%          |          |
|              Korom Richárd                 |            4           |             14             |           23            |            19            |    60    |
|              Köles Bálint                  |            6           |             9              |           20            |            25            |    60    |
|              Schneider Bence               |            6           |             10             |           22            |            22            |    60    |
|              Géczi Ákos                    |            3           |             9              |           23            |            25            |    60    |
|              Hörömpő László                |            3           |             14             |           22            |            21            |    60    |
|              Simon Péter                   |            3           |             17             |           21            |            19            |    60    |

### 11.2. Átvétel
A projektet a megrendelő a következő eredménnyel vette át:

|                     Név                    | 1. leadás - Projektterv | 2. leadás - UML és adatbázis | 3. leadás - Prototípus I. | 4. leadás - Prototípus II. | Összesen |
|:------------------------------------------:|:----------------------:|:--------------------------:|:-----------------------:|:------------------------:|:--------:|
|                                            |                        |                            |                         |                          |    60    |
|                                            |                        |                            |                         |                          |    60    |
|                                            |                        |                            |                         |                          |    60    |
|                                            |                        |                            |                         |                          |    60    |
|                                            |                        |                            |                         |                          |    60    |

Szeged, 2019. szeptember 22.

#### &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Az átadó részéről &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Az átvevő részéről 

 