# Pontozólap

Kozma Zsófia - ELPIMX

A projektemben könyveknek és sorozatoknak az értékeléseit lehet vezetni. Lehet csinálni felhasználói fiókot, így személyenként vannak az értékelések. 

Itt egy videó, amin a programomat és a weblapomat mutatom be: 


# Windows Forms Application

## User Interface

-   `1x2p`  Az alkalmazásból a  **kilépés csak megerősítő kérdés után**  lehetséges.
    
-   `3x1p`  **Többablakos alkalmazás**  legalább két felugró ablakkal. Minden Form-nak saját osztályon kell alapulnia, és funcionalitással kell rendelkeznie. Az ablakok nyílhatnak gombokkal vagy felső menüből is.
    
-   `1x2p`  **Anchorok alkalmazása**: az alkalmazás egészében meg van oldva, hogy az ablak átméretezésekor ki legyen használva a rendelkezésre álló terület.
    

## Tábla adatainak megjelenítése  `ListBox`-ban.

-   `1x2p`  Adatok megjelenítése
-   `1x2p`  Ha az adatok tetszőleges módszerrel, pl.  `TextBox`-on keresztül szűrhetőek.
-   `1x2p`  Ha a tábla adatforrása saját osztály.

## Tábla adatainak megjelenítése  `DataGridView`-ban

-   `1x2p`  Adatok megjelenítése
-   `1x2p`  Ha a tábla adatforrása saját osztály.

## Adatkötés  `BindingSource`  -on keresztül

-   `1x2p`  Működő  `BindingSource`

## Új rekord rögzítése

-   `1x2p`  Ha csak az idegen kulcsok vannak felvéve
-   `1x1p`  Ha legalább egy nem kulcs mező, pl.  _Mennyiség_  is fel van véve
-   `1x2p`  Ellenőrzéshez kötött adatfelvitel (egyszerű validáció pl:  `String.IsNullOrEmpty()`)
-   `1x2p`  Felugró ablakon keresztül történik  _Ok_  és  _Mégse_  gombbal
-   `1x2p`  Ha az űrlap legördülő dobozon vagy listán keresztül beállítható idegen kulcsot is tartalmaz
-   `1x1p`  A kitöltési hiba  `ErrorProvider`-en keresztül kerülnek köközlésre a felhasználóval, hibás kitöltés esetén nem enged rányomni az  _Ok_  gombra
-   `1x1p`  Hibás kitöltés esetén nem lehet megynomni az  _Ok_  gombot.

## Rekord törlése

-   `1x2p`  Sikeres törlés
-   `1x2p`  Megerősítéshez kötött törlés


# ASP .NET

ASP .NET alkalmazás, melyet lehet a Forms alapú projekttel közös solution-ben létrehozni.

-   `1x2p`  `program.cs`  beállítása  `wwwroot`  mappában tárolt statikus tartalmak megosztására

## API végpontok

-   `1x3p`  Teljes SQL tábla adatainak szolgáltatása API végponton keresztül
-   `2x2p`  SQL tábla egy választható rekordjának szolgáltatása API végponton keresztül
-   `1x3p`  SQL tábla egy választható rekordjának törlése
-   `1x5p`  Új rekord felvétele  `HttpPost`  metóduson keresztül SQL táblába
-   `1x3p`  Rekord módosítása  `HttpPost`  metóduson keresztül SQL táblában

# Hozott anyagok

## Saját Adatbázis

SQL script formájában, de legjobb Azure SQL szerveren hosztolni

-   `2x1p`  Az alkalmazásban használt táblánként pont
-   `1x1p`  Az adatbázis tartalmaz Constraint-eket (min 2)
-   `1x1p`  Az adatbázis adatainak forrásmegjelölése értsd: miből készült és hogyan
*(-- Adatbázis forrásmegjelölése:
-- 1. A 'Users' tábla adatai fiktívek, kitalált nevekkel.
-- 2. A 'Items' tábla híres könyveket és sorozatokat tartalmaz.
-- 3. A 'Ratings' tábla értékelései és kommentjei kitaláltak, de tükrözik a tartalmak általános megítélését.)*
-   `1x2p`  Az adatbázis saját Azure SQL szerveren van

## Weboldal

Itt csak azok az elemek számíthatóak be, amelyeknek meg van a ZH alatt felépített API végpontja.

-   `1x1p`  A weboldalnak van egy értelmezhető struktúrája
-   `1x1p`  A weboldal dinamikus tartalommal tölthető fel adatbázison keresztül
-   `1x1p`  A weboldal használ legalább 20 sor értelmes css-t
-   `1x1p`  A weboldal javascriptet használ API végpont által szolgáltatott adatok betöltésére, hozott anyagként
-   `1x1p`  A weboldal javascriptje más funkciót is ellát, mint az adatok betöltése

# Egyéb,  extra

-   `2x1p`  `Scaffold-DbContext`  használata (ajándék)

# ~66p
