# Somatologie

**Verze: 1.3.0**  
**Datum vydání: 19. 10. 2026**  
**Počet otázek: 200**

Mobilní procvičování somatologie v jednom samostatném HTML souboru. Obsahuje vysvětlení odpovědí, chytré opakování a ukládání pokroku v prohlížeči.

## Změny v této verzi

- Přidáno přesně 50 otázek, čísla 151–200: kapitola V (Krev), otázky 10–59. Témata zahrnují krvinky, srážení, imunitu a krevní skupiny.
- Každá nová otázka má tři odstavce s vysvětlením souvislostí a pomůcku pro zapamatování.
- Všech 200 přiřazení správných odpovědí porovnáno s přepisem tištěných klíčů PDF. Nové otázky a jejich klíč byly zkontrolovány přímo ve skenu, bez internetových zdrojů a bez přebírání ručních značek.
- U nepřesných nebo zastaralých formulací je po odpovědi poznámka „Pro přesnost“. Hodnocení zůstává podle tištěného klíče; zejména u transfuze, tolerance a brzlíku vysvětlení upozorňuje na omezení nabídky.
- Původních 150 otázek, jejich identifikátory a formát ukládání pokroku zůstaly beze změny.

## Co bylo ověřeno

- Celý náhodný test všech 200 otázek, okamžité zbarvení odpovědí, vysvětlení a správné skóre.
- Zachování chyb, tipů, zvládnutých otázek i rozpracovaného 150otázkového kola při nahrazení staré verze na stejné adrese.
- Uložení a obnovení po skutečném zavření a znovuotevření testovacího prohlížeče před aktualizací i po ní.
- Pokračování v novém testu po obnovení stránky za hranicí 150 odpovědí.
- Chytré opakování: správný tip otázku neoznačí za zvládnutou; příliš časné opakování neposune úroveň; chyba se vrací s odstupem.
- Všech 200 otázek i jejich vysvětlení při šířkách 320, 390, 768 a 1024 pixelů bez vodorovného přetékání. Tlačítka odpovědí mají výšku nejméně 64 pixelů.
- Spuštění samostatného HTML bez internetu a fungování testu i při zablokovaném nebo poškozeném úložišti.

## Spuštění a nahrání

Otevři `index.html` v prohlížeči. Stažený soubor funguje bez internetu.

Na GitHub nahraj **obsah této složky** do stejného místa jako dosud: `index.html` a `README.md`. Název vydané složky slouží pro archivaci; kvůli nové verzi není potřeba měnit adresu webu.

Pokrok se ukládá po každé odpovědi v konkrétním prohlížeči a jeho profilu, odděleně od HTML souboru. Nahrazení aplikace na stejném webu ho zachovává, pokud zůstala zachovaná data prohlížeče. Mezi zařízeními se nesynchronizuje; vymazání dat nebo ukončení anonymního režimu může pokrok odstranit. U místně otevřeného souboru může přesunutí do jiné složky znamenat jiné úložiště; pro pravidelné používání zachovej stejnou webovou adresu.

Rozpracované starší kolo si zachová původní délku. Nové otázky se zapojí do nově zahájeného kola a chytrého procvičování; dřívější znalost původních otázek zůstane uložená.

## Historie verzí

| Verze | Otázky | Hlavní změna |
| --- | ---: | --- |
| 1.3.0 | 200 | Dalších 50 otázek o krvi a imunitě; kontrola klíčů, vysvětlení, mobilního zobrazení a zachování pokroku. |
| 1.2.0 | 150 | Dalších 50 otázek; kontrola klíčů a zachování pokroku po restartu; balíček s README. |
| 1.1.0 | 100 | Dalších 50 otázek; kontrola proti PDF a kompatibilita uloženého pokroku. |
| 1.0.0 | 50 | Rozšíření banky, chytré opakování, označení tipů a ukládání pokroku. |
| 0.1.0 | 10 | První funkční prototyp s vysvětleními a mobilním vzhledem. |

Čísla verzí před 1.2.0 byla při zavedení tohoto přehledu přiřazena zpětně podle skutečně dodaných verzí.

## Číslování dalších vydání

- **1.4.0:** další rozšíření otázek nebo nová funkce.
- **1.3.1:** drobná oprava současné verze.
- **2.0.0:** zásadní přepracování aplikace.

Každé další vydání má vlastní složku a ZIP se stejným číslem verze a obsahuje `index.html` a aktualizované `README.md`. Při přidávání otázek se zachovají identifikátory dosavadních otázek a kompatibilita uloženého pokroku.
