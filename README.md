# Somatologie

**Verze: 1.6.0**  
**Datum vydání: 22. 10. 2026**  
**Počet otázek: 350**

Mobilní procvičování somatologie v jednom samostatném HTML souboru. Obsahuje vysvětlení odpovědí, chytré opakování a ukládání pokroku v prohlížeči.

## Změny v této verzi

- Přidáno přesně 50 otázek, čísla 301–350: kapitola VIII otázky 30–49, kapitola IX otázky 1–19, kapitola X otázky 1–9 a kapitola XI otázky 1–2.
- Sada dokončuje trávení, zahrnuje celou kapitolu fyziologie výživy a termoregulace a začíná močový systém.
- Každá nová otázka má tři odstavce vysvětlení s logickými souvislostmi a pomůcku pro zapamatování.
- Všech 350 přiřazení odpovědí souhlasí s přepisem tištěných klíčů zdrojového PDF. Nové otázky, možnosti a klíče byly čteny přímo ze skenu bez internetu a bez přebírání ručních značek. Nově použité klíče: PDF strany 40, 43, 44 a 48 (tištěné strany 78, 84, 87 a 95).
- Sporné či zastaralé formulace mají poznámku „Pro přesnost“. Například rozlišujeme zásobní ferritin a transportní transferin, horečku a hypertermii nebo obecný ileus a jeho paralytickou formu. U problematické otázky o vodě je výslovně uvedeno, že A je biologicky správné, i když PDF hodnotí D.
- Původních 300 otázek včetně vysvětlení a identifikátorů zůstalo beze změny. Formát uloženého pokroku ani pravidla chytrého opakování se nemění.

## Co bylo ověřeno

- Celý náhodný test 350 různých otázek, zbarvení odpovědí, zobrazení vysvětlení, ochrana proti dvojímu započtení a výsledné skóre.
- Zachování všech polí pokroku při aktualizaci ze 300 na 350 otázek na stejné adrese: chyby, tipy, zvládnuté otázky i rozpracované starší kolo.
- Obnovení po skutečném zavření a znovuotevření testovacího prohlížeče před aktualizací i po ní.
- Pokračování v novém celém testu po obnovení stránky za hranicí 300 odpovědí.
- Chytré opakování: správný tip nezvyšuje zvládnutí, předčasná správná odpověď neposune úroveň a chyba se vrací po odstupu.
- Všech 350 otázek i vysvětlení při šířkách 320, 390, 768 a 1024 pixelů bez vodorovného přetékání. Tlačítka odpovědí mají nejméně 64 pixelů na výšku.
- Offline spuštění samostatného HTML a funkční náhradní chování při zablokovaném či poškozeném úložišti.
- Shoda zabaleného HTML se zdrojem, kontrola obsahu ZIP a jeho integrity.

## Spuštění a nahrání

Otevři `index.html` v prohlížeči. Stažený soubor funguje bez internetu.

Na GitHub nahraj **obsah této složky** do stejného místa jako dosud: `index.html` a `README.md`. Název vydané složky slouží pro archivaci; kvůli nové verzi není potřeba měnit adresu webu.

Pokrok se ukládá po každé odpovědi v konkrétním prohlížeči a jeho profilu, odděleně od HTML souboru. Nahrazení aplikace na stejném webu ho zachovává, pokud zůstala zachovaná data prohlížeče. Mezi zařízeními se nesynchronizuje; vymazání dat nebo ukončení anonymního režimu může pokrok odstranit. U místně otevřeného souboru může přesunutí do jiné složky znamenat jiné úložiště; pro pravidelné používání zachovej stejnou webovou adresu.

Rozpracované starší kolo (například test 300 otázek) si zachová původní délku. Nové otázky se zapojí do nově zahájeného kola a chytrého procvičování; dřívější znalost původních otázek zůstane uložená.

## Historie verzí

| Verze | Otázky | Hlavní změna |
| --- | ---: | --- |
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

- **1.7.0:** další rozšíření otázek nebo nová funkce.
- **1.6.1:** drobná oprava současné verze.
- **2.0.0:** zásadní přepracování aplikace.

Každé další vydání má vlastní složku a ZIP se stejným číslem verze a obsahuje `index.html` a aktualizované `README.md`. Při přidávání otázek se zachovají identifikátory dosavadních otázek a kompatibilita uloženého pokroku.
