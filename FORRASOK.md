# Az SWF-animációk forrásai

Ellenőrzés: 2026. október 29. A fájlok több különböző projektből származnak. Nem állítható biztosan, hogy a kolléga közvetlenül ezekről töltötte le őket; köztes gyűjtőoldal is lehetett. A helyi „letöltési oldal linkje.docx” csak az Adobe Flash Player letöltési linkjét tartalmazta.

## 1. Kentucky Egyetem: a legerősebb találat

Gyűjtemény: https://ees.as.uky.edu/educational-materials

Az oldal 14 animációt sorol fel, az eredeti készítőt Smoothstone-ként, a kiadót Houghton Mifflin Company-ként jelöli (2001–2002). A gleccserfájl tartalmát SHA-256 összehasonlítással ellenőriztem: a szerverről olvasott `module13swf.swf` és a helyi, 2 106 103 bájtos fájl teljesen azonos. A gyűjtemény további négy fájlneve megegyezik a már feldolgozott anyagokéval.

| Modul | Téma | Magyar változat |
|---|---|---|
| module01swf.swf | Felszín alatti vizek | Kész |
| module02swf.swf | Metamorf kőzetek | Új jelölt |
| module03swf.swf | Magmás kőzetek | Új jelölt |
| module04swf.swf | Lemeztektonika | Kész |
| module05swf.swf | Kőzetkörforgás | Új jelölt |
| module06swf.swf | A Föld szerkezete és szeizmikus hullámok | Új jelölt |
| module07swf.swf | Mállás | Új jelölt |
| module08swf.swf | Üledékes kőzetek | Új jelölt |
| module09swf.swf | Ásványok | Új jelölt |
| module10swf.swf | Vetők és redők | Új jelölt |
| module11swf.swf | Lejtős tömegmozgások | Kész |
| module12swf.swf | Árvizek | Kész |
| module13swf.swf | Gleccserek | Kész; fájlegyezés igazolva |
| module14swf.swf | Tengerpartok | Új jelölt |

A fájlok címe: `https://ees.as.uky.edu/sites/default/files/elearning/` + a táblázat fájlneve. A 9 új jelölt az oldalon szereplő linkek alapján azonosított; működésüket és magyarításukat külön kell elvégezni. A régi Flash-fájlokat önmagukban a böngészők általában nem játsszák le.

## 2. Nebraska Egyetem – NAAP / ClassAction

Gyűjtemény: https://astro.unl.edu/animationsLinks.html

Az eredeti fájllista: https://astro.unl.edu/naap/motion3/animations/

Ezen szerepel a helyi `sunmotions.swf` fájlnév. A teljes lista többek között napjárás-, koordináta-, holdfázis-, bolygópálya-, árapály- és exobolygómodelleket tartalmaz. A honlap Ruffle emulációt is használ. A fájlnév és a projekt egyezése igazolt, bináris azonosságot nem állítok: a helyi Python HTTPS-tanúsítvány-ellenőrzése ezt a szervert nem fogadta el.

## 3. PhET – My Solar System

Eredeti Flash-változat adatlapja: https://phet.colorado.edu/en/simulations/legacy/my-solar-system

Korszerű szimuláció: https://phet.colorado.edu/en/simulations/my-solar-system

A helyi `my-solar-system.swf` a PhET projektje. A University of Colorado Boulder gyűjteményében további föld- és űrtudományi modellek is vannak.

## 4. La main à la pâte – Les saisons

https://fondation-lamap.org/ressource-multimedia/les-saisons

A helyi `saisons.swf` eredeti francia projektje; az adatlap a Föld keringését, a dátum, a nézőpont és a nagyítás változtatását írja le. A honlapon éghajlati és más természettudományos anyagok is vannak.

## 5. További, nagy földtani gyűjtőhely

https://www.doganaydal.com/Egitim/DersNotlarim/96

Doğan Aydal oktatási oldalán számos földtani SWF és MP4-másolat érhető el. Nem igazolt, hogy innen származna a kolléga csomagja; további modulok felkutatásához viszont hasznos találat. A videómásolatok nem őrzik meg az interaktivitást.

## 6. További nyomok, részlegesen azonosítva

- `Seasons_Nav.swf` és `Eclipses_Nav.swf`: McGraw Hill csillagászati interaktív anyagok. Régi hivatkozási útvonal: `highered.mheducation.com/sites/dl/free/0072482621/78778/`. A mai gyűjteményoldalt nem sikerült megbízhatóan ellenőrizni.
- `23_WeatherPat.swf`: régi Palomar oktatási hivatkozásokban szerepel. Ebből még nem állapítható meg biztosan az eredeti szerző vagy a kolléga letöltési helye.
- `VolcanoTypes.swf`, `Religion.swf`, `nap_delelesi_szoge.swf`, `ocean_circulation.swf`: a pontos eredeti adatlap további ellenőrzést igényel; ezeket nem jelöltem biztos találatként.
