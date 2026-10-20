# Somatologie

**Verze: 1.4.0**  
**Datum vydání: 20. 10. 2026**  
**Počet otázek: 250**

Mobilní procvičování somatologie v jednom samostatném HTML souboru. Obsahuje vysvětlení odpovědí, chytré opakování a ukládání pokroku v prohlížeči.

## Změny v této verzi

- Přidáno přesně 50 otázek, čísla 201–250. Jde o kapitolu V otázku 60, kapitolu VI otázky 1–36 a kapitolu VII otázky 1–13.
- Nové otázky pokrývají krevní skupiny, cévy, srdce, mízu, slezinu a začátek dýchacího systému.
- Každá nová otázka má tři odstavce s vysvětlením souvislostí a pomůcku pro zapamatování.
- Všech 250 přiřazení odpovědí odpovídá přepisu tištěných klíčů PDF. Nové otázky a možnosti byly přečteny přímo ze skenu, bez internetových zdrojů. Použity klíče na PDF stranách 26, 31 a 34; ruční značky neurčují hodnocení.
- Sporné nebo zjednodušené formulace mají poznámku „Pro přesnost“. Ta například rozlišuje epikard od perikardu, vysvětluje nejednoznačné možnosti a vývojová stadia skokana v přiřazení dýchacích orgánů.
- Původních 200 otázek včetně vysvětlení a identifikátorů zůstalo beze změny. Ukládání pokroku a chytré opakování používají stejný formát jako dosud.

## Co bylo ověřeno

- Celý náhodný test 250 různých otázek; zbarvení odpovědí, vysvětlení, ochrana proti opakovanému započítání odpovědi a výsledné skóre.
- Zachování všech uložených polí při aktualizaci ze 200 na 250 otázek na stejné adrese, včetně chyb, tipů, zvládnutých otázek a rozpracovaného kola.
- Obnovení pokroku po skutečném zavření a znovuotevření testovacího prohlížeče před aktualizací i po ní.
- Pokračování v celém testu po obnovení stránky za hranicí 200 odpovědí.
- Chytré opakování: správný tip nezvyšuje zvládnutí, příliš časná odpověď neposouvá úroveň a chyba se vrací po odstupu.
- Všech 250 otázek i vysvětlení při šířkách 320, 390, 768 a 1024 pixelů bez vodorovného přetékání; tlačítka odpovědí mají nejméně 64 pixelů na výšku.
- Spuštění samostatného HTML bez internetu a fungování při zablokovaném či poškozeném úložišti.
- Kopie HTML v balíčku je shodná se zdrojovým souborem a ZIP prošel kontrolou integrity.

## Spuštění a nahrání

Otevři `index.html` v prohlížeči. Stažený soubor funguje bez internetu.

Na GitHub nahraj **obsah této složky** do stejného místa jako dosud: `index.html` a `README.md`. Název vydané složky slouží pro archivaci; kvůli nové verzi není potřeba měnit adresu webu.

Pokrok se ukládá po každé odpovědi v konkrétním prohlížeči a jeho profilu, odděleně od HTML souboru. Nahrazení aplikace na stejném webu ho zachovává, pokud zůstala zachovaná data prohlížeče. Mezi zařízeními se nesynchronizuje; vymazání dat nebo ukončení anonymního režimu může pokrok odstranit. U místně otevřeného souboru může přesunutí do jiné složky znamenat jiné úložiště; pro pravidelné používání zachovej stejnou webovou adresu.

Rozpracované starší kolo (například test 200 otázek) si zachová původní délku. Nové otázky se zapojí do nově zahájeného kola a chytrého procvičování; dřívější znalost původních otázek zůstane uložená.

## Historie verzí

| Verze | Otázky | Hlavní změna |
| --- | ---: | --- |
| 1.4.0 | 250 | Dalších 50 otázek: dokončení krve, celý krevní oběh a začátek dýchacího systému; ověřené klíče, vysvětlení a kompatibilita pokroku. |
| 1.3.0 | 200 | Dalších 50 otázek o krvi a imunitě; kontrola klíčů, vysvětlení, mobilního zobrazení a zachování pokroku. |
| 1.2.0 | 150 | Dalších 50 otázek; kontrola klíčů a zachování pokroku po restartu; balíček s README. |
| 1.1.0 | 100 | Dalších 50 otázek; kontrola proti PDF a kompatibilita uloženého pokroku. |
| 1.0.0 | 50 | Rozšíření banky, chytré opakování, označení tipů a ukládání pokroku. |
| 0.1.0 | 10 | První funkční prototyp s vysvětleními a mobilním vzhledem. |

Čísla verzí před 1.2.0 byla při zavedení tohoto přehledu přiřazena zpětně podle skutečně dodaných verzí.

## Číslování dalších vydání

- **1.5.0:** další rozšíření otázek nebo nová funkce.
- **1.4.1:** drobná oprava současné verze.
- **2.0.0:** zásadní přepracování aplikace.

Každé další vydání má vlastní složku a ZIP se stejným číslem verze a obsahuje `index.html` a aktualizované `README.md`. Při přidávání otázek se zachovají identifikátory dosavadních otázek a kompatibilita uloženého pokroku.
