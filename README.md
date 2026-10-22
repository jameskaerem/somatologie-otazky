# Somatologie

**Verze: 1.7.0**  
**Datum vydání: 22. 10. 2026**  
**Počet otázek: 400**

Mobilní procvičování somatologie v jednom samostatném HTML souboru. Obsahuje vysvětlení odpovědí, chytré opakování a ukládání pokroku v prohlížeči.

## Změny v této verzi

- Přidáno přesně 50 otázek, čísla 351–400: kapitola XI otázky 3–28 a kapitola XII otázky 1–24. Sada dokončuje močový systém a přidává kůži, její vrstvy, žlázy, laktaci a ochlupení.
- Každá nová otázka má tři odstavce vysvětlení souvislostí a pomůcku pro zapamatování.
- Všech 400 přiřazení odpovědí souhlasí s přepisem tištěných klíčů PDF. Nové otázky, možnosti a klíče byly přečteny přímo ze skenu bez internetu a bez přebírání ručních značek. Nově použité klíče: PDF strany 48 a 52, tištěné strany 95 a 102.
- Nejednoznačné nebo chybné formulace mají poznámku „Pro přesnost“. Hodnocení je nadále podle PDF, odborné vysvětlení výslovně uvádí potřebné opravy.
- Konkrétní zjevné rozpory: otázka 369 (XI/21) má chybnou lokalizaci řízení mikce; otázka 395 (XII/19) má jako největší kožní žlázy v klíči B – mazové, zatímco anatomicky je správně C – mléčné. Oba rozpory jsou přímo v aplikaci vysvětlené.
- Rozlišujeme například vznik ADH v hypothalamu od uvolnění v neurohypofýze, tvorbu mléka podporovanou prolaktinem od vypuzování řízeného oxytocinem a prenatální tvorbu kolostra od zvýšené poporodní sekrece.
- Původních 350 otázek včetně vysvětlení a identifikátorů zůstalo beze změny. Formát uloženého pokroku i pravidla chytrého opakování jsou zachované.

## Co bylo ověřeno

- Celý náhodný test 400 různých otázek, zbarvení odpovědí, vysvětlení, ochrana před dvojím započtením a výsledné skóre.
- Zachování všech polí pokroku při aktualizaci ze 350 na 400 otázek na stejné adrese: chyby, tipy, zvládnuté otázky a rozpracované starší kolo.
- Obnovení po skutečném zavření a znovuotevření testovacího prohlížeče před aktualizací i po ní.
- Pokračování v novém celém testu po obnovení stránky za hranicí 350 odpovědí.
- Chytré opakování včetně opatrného hodnocení tipů, nemožnosti posunout úroveň předčasným opakováním a návratu chyby s odstupem.
- Všech 400 otázek a vysvětlení při šířkách 320, 390, 768 a 1024 pixelů bez vodorovného přetékání. Tlačítka odpovědí mají výšku nejméně 64 pixelů.
- Offline spuštění jediného HTML a funkční náhradní chování při zablokovaném nebo poškozeném úložišti.
- Shoda zabaleného HTML se zdrojem, kontrola obsahu a integrity ZIP.

## Spuštění a nahrání

Otevři `index.html` v prohlížeči. Stažený soubor funguje bez internetu.

Na GitHub nahraj **obsah této složky** do stejného místa jako dosud: `index.html` a `README.md`. Název vydané složky slouží pro archivaci; kvůli nové verzi není potřeba měnit adresu webu.

Pokrok se ukládá po každé odpovědi v konkrétním prohlížeči a jeho profilu, odděleně od HTML souboru. Nahrazení aplikace na stejném webu ho zachovává, pokud zůstala zachovaná data prohlížeče. Mezi zařízeními se nesynchronizuje; vymazání dat nebo ukončení anonymního režimu může pokrok odstranit. U místně otevřeného souboru může přesunutí do jiné složky znamenat jiné úložiště; pro pravidelné používání zachovej stejnou webovou adresu.

Rozpracované starší kolo (například test 350 otázek) si zachová původní délku. Nové otázky se zapojí do nově zahájeného kola a chytrého procvičování; dřívější znalost původních otázek zůstane uložená.

## Historie verzí

| Verze | Otázky | Hlavní změna |
| --- | ---: | --- |
| 1.7.0 | 400 | Dalších 50 otázek: dokončení močového systému a kůže včetně žláz a ochlupení; kontrola klíčů a kompatibilita pokroku. |
| 1.6.0 | 350 | Dalších 50 otázek: dokončení trávení, výživa, termoregulace a začátek močového systému; kontrola klíčů a zachování pokroku. |
| 1.5.0 | 300 | Dalších 50 otázek: dokončení dýchacího systému a začátek trávení; vysvětlení, kontrola klíčů a kompatibilita pokroku. |
| 1.4.0 | 250 | Dalších 50 otázek: dokončení krve, celý krevní oběh a začátek dýchacího systému; ověřené klíče, vysvětlení a kompatibilita pokroku. |
| 1.3.0 | 200 | Dalších 50 otázek o krvi a imunitě; kontrola klíčů, vysvětlení, mobilního zobrazení a zachování pokroku. |
| 1.2.0 | 150 | Dalších 50 otázek; kontrola klíčů a zachování pokroku po restartu; balíček s README. |
| 1.1.0 | 100 | Dalších 50 otázek; kontrola proti PDF a kompatibilita uloženého pokroku. |
| 1.0.0 | 50 | Rozšíření banky, chytré opakování, označení tipů a ukládání pokroku. |
| 0.1.0 | 10 | První funkční prototyp s vysvětleními a mobilním vzhledem. |

Čísla verzí před 1.2.0 byla při zavedení tohoto přehledu přiřazena zpětně podle skutečně dodaných verzí.

## Číslování dalších vydání

- **1.8.0:** další rozšíření otázek nebo nová funkce.
- **1.7.1:** drobná oprava současné verze.
- **2.0.0:** zásadní přepracování aplikace.

Každé další vydání má vlastní složku a ZIP se stejným číslem verze a obsahuje `index.html` a aktualizované `README.md`. Při přidávání otázek se zachovají identifikátory dosavadních otázek a kompatibilita uloženého pokroku.
