# Somatologie

**Verze: 1.5.0**  
**Datum vydání: 20. 10. 2026**  
**Počet otázek: 300**

Mobilní procvičování somatologie v jednom samostatném HTML souboru. Obsahuje vysvětlení odpovědí, chytré opakování a ukládání pokroku v prohlížeči.

## Změny v této verzi

- Přidáno přesně 50 otázek, čísla 251–300: kapitola VII otázky 14–34 a kapitola VIII otázky 1–29.
- Nová sada dokončuje dýchací systém a přidává ústa, zuby, polykání, jícen, žaludek, pankreas a začátek střevního trávení.
- Každá nová otázka má tři odstavce s vysvětlením souvislostí a pomůcku pro zapamatování.
- Všech 300 přiřazení odpovědí souhlasí s přepisem tištěných klíčů PDF. Nové otázky, možnosti a klíče byly čteny přímo ze skenu bez internetových zdrojů; nové klíče jsou na PDF stranách 34 a 40 (tištěné strany 67 a 78).
- Sporné, zastaralé nebo nejednoznačné formulace mají poznámku „Pro přesnost“. V této sadě například rozlišujeme začátek výměny mléčného chrupu od jejího dokončení, aktivní enzym od jeho předstupně a problematický údaj o chymosinu člověka. Hodnocení zůstává podle tištěného klíče.
- Původních 250 otázek včetně vysvětlení a identifikátorů zůstalo beze změny. Formát ukládání a pravidla chytrého opakování jsou zachované.

## Co bylo ověřeno

- Celý náhodný test 300 různých otázek, okamžité zbarvení odpovědí, vysvětlení, ochrana proti opakovanému započítání a správné výsledné skóre.
- Zachování všech polí pokroku při aktualizaci z 250 na 300 otázek na stejné adrese: chyby, tipy, zvládnuté otázky i rozpracované starší kolo.
- Obnovení po skutečném zavření a znovuotevření testovacího prohlížeče před aktualizací i po ní.
- Pokračování po obnovení stránky v novém celém testu za hranicí 250 odpovědí.
- Chytré opakování včetně odloženého návratu chyby, označení tipu a neposouvání úrovně při příliš časném opakování.
- Všech 300 otázek i vysvětlení při šířkách 320, 390, 768 a 1024 pixelů bez vodorovného přetékání. Tlačítka odpovědí mají nejméně 64 pixelů na výšku.
- Spuštění samostatného HTML bez internetu a funkční náhradní chování při zablokovaném či poškozeném úložišti.
- Kopie HTML v balíčku je shodná se zdrojem a ZIP prošel kontrolou integrity i porovnáním obsahu.

## Spuštění a nahrání

Otevři `index.html` v prohlížeči. Stažený soubor funguje bez internetu.

Na GitHub nahraj **obsah této složky** do stejného místa jako dosud: `index.html` a `README.md`. Název vydané složky slouží pro archivaci; kvůli nové verzi není potřeba měnit adresu webu.

Pokrok se ukládá po každé odpovědi v konkrétním prohlížeči a jeho profilu, odděleně od HTML souboru. Nahrazení aplikace na stejném webu ho zachovává, pokud zůstala zachovaná data prohlížeče. Mezi zařízeními se nesynchronizuje; vymazání dat nebo ukončení anonymního režimu může pokrok odstranit. U místně otevřeného souboru může přesunutí do jiné složky znamenat jiné úložiště; pro pravidelné používání zachovej stejnou webovou adresu.

Rozpracované starší kolo (například test 250 otázek) si zachová původní délku. Nové otázky se zapojí do nově zahájeného kola a chytrého procvičování; dřívější znalost původních otázek zůstane uložená.

## Historie verzí

| Verze | Otázky | Hlavní změna |
| --- | ---: | --- |
| 1.5.0 | 300 | Dalších 50 otázek: dokončení dýchacího systému a začátek trávení; vysvětlení, kontrola klíčů a kompatibilita pokroku. |
| 1.4.0 | 250 | Dalších 50 otázek: dokončení krve, celý krevní oběh a začátek dýchacího systému; ověřené klíče, vysvětlení a kompatibilita pokroku. |
| 1.3.0 | 200 | Dalších 50 otázek o krvi a imunitě; kontrola klíčů, vysvětlení, mobilního zobrazení a zachování pokroku. |
| 1.2.0 | 150 | Dalších 50 otázek; kontrola klíčů a zachování pokroku po restartu; balíček s README. |
| 1.1.0 | 100 | Dalších 50 otázek; kontrola proti PDF a kompatibilita uloženého pokroku. |
| 1.0.0 | 50 | Rozšíření banky, chytré opakování, označení tipů a ukládání pokroku. |
| 0.1.0 | 10 | První funkční prototyp s vysvětleními a mobilním vzhledem. |

Čísla verzí před 1.2.0 byla při zavedení tohoto přehledu přiřazena zpětně podle skutečně dodaných verzí.

## Číslování dalších vydání

- **1.6.0:** další rozšíření otázek nebo nová funkce.
- **1.5.1:** drobná oprava současné verze.
- **2.0.0:** zásadní přepracování aplikace.

Každé další vydání má vlastní složku a ZIP se stejným číslem verze a obsahuje `index.html` a aktualizované `README.md`. Při přidávání otázek se zachovají identifikátory dosavadních otázek a kompatibilita uloženého pokroku.
