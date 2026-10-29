# Földrajzi segédanyagok

Magyar nyelvű, bővíthető földrajzi tananyagtár. 18 interaktív tananyag, Térképműhely és az eredeti források gyűjteménye.

Élő oldal: https://palgeri93.github.io/foldrajzi-segedanyagok/

## Bővítés

A `materials.json` `materials` listájához adj új objektumot, például:

```json
{
  "id": "uj-tananyag",
  "title": "Új tananyag címe",
  "category": "geology",
  "description": "Rövid magyar ismertető.",
  "url": "https://pelda.hu/tananyag/",
  "mode": "embed"
}
```

Az `id` legyen egyedi, ékezet és szóköz nélküli. A `category` a `categories` lista egyik azonosítója. Új kategória is hozzáadható. `embed` módban a tananyag az oldalon belül jelenik meg. Ha a céloldal tiltja a beágyazást, `navigate` módot használj; a `notice` mezőben megadható a magyarázat. Az eredeti gyűjtemények a `sources.json` fájlban bővíthetők.

A tananyagok száma automatikusan követi a listát. A gyűjtemény használata során egyszerre csak egy beágyazott tananyag töltődik be. A Térképműhely CSP-beállítása tiltja a beágyazást, ezért ugyanabban a böngészőlapon nyílik meg.

## Helyi előnézet

Statikus webszerverrel indítható, például `python -m http.server 8766 --directory foldrajzi-segedanyagok` a szülőkönyvtárból. Nem igényel fordítást vagy csomagtelepítést. Betűkészlet: Google Fonts; internet nélkül rendszerbetűt használ.

## Közzététel

A `main` ágra feltöltött változásokat a `.github/workflows/pages.yml` GitHub Pages munkafolyamat teszi közzé. A repó Pages forrása GitHub Actions.

## Forráskutatás

A kolléga pontos letöltési oldala nem bizonyított. A helyi `letöltési oldal linkje.docx` csak az Adobe Flash Player letöltési címét tartalmazta. Az igazolt gyűjteményeket és a bizonyítékokat a [FORRASOK.md](FORRASOK.md) foglalja össze.
