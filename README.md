# Somatologie

**Verze: 1.12.0**  
**Datum vydání: 27. 10. 2026**  
**Počet otázek: 630 — kompletní sada dodaného PDF**

Mobilní procvičování somatologie v jediném samostatném HTML souboru. Obsahuje logická vysvětlení, chytré opakování a ukládání pokroku v prohlížeči.

## Změny v této verzi

- Přidáno posledních 30 otázek, čísla 601–630 (XVII/5–34). Požadovaných dalších 50 již v tomto PDF nezbývalo: dokument končí otázkou XVII/34, celkově otázkou 630.
- Dokončen vývoj dítěte: novorozenecké orgány a reflexy, spánek, věková období, kojenec, batole, chrup, puberta a dospívání.
- Každá nová otázka má tři odstavce vysvětlení souvislostí a pomůcku pro zapamatování. Přiřazovací otázka obsahuje legendu, dvojice tvrzení jsou oddělené.
- Otázky a možnosti byly přečteny ze skenu PDF stran 76–79 (tištěné strany 150–156). Hodnocení je zkontrolované proti tištěnému klíči XVII na PDF straně 79 (tištěná 156), nikoli podle ručních značek. Nebyly použity internetové zdroje.
- Všech 630 odpovědí odpovídá přepisu tištěných klíčů. Původních 600 otázek včetně identifikátorů a všech obsahových polí zůstalo beze změny.
- Zachován klíč úložiště `somatologie-learning-v2`, formát dat i pravidla chytrého opakování. Jedna správná odpověď ještě neznamená zvládnutí; označený tip se za zvládnutí nepočítá.

## Přesnost a zjednodušení zdroje

Hodnocení sleduje tištěný klíč. Vysvětlení výslovně upozorňují na nepřesnosti zdroje a odlišují školní odpověď od přesné fyziologie.

- XVII/12: rychlé provzdušnění plic při zahájení dýchání není totožné s úplným okamžitým odstraněním plicní tekutiny.
- XVII/13 a XVII/16: část vedlejších nosních dutin je založena již při narození; relativní velikost ledvin a přítomnost nefronů neznamenají dospělou funkční zralost.
- XVII/19 (615): tělesný tuk skutečně také chrání před tepelnými ztrátami, přesto klíč vybírá jinou pravdivou odpověď. Přibližně 35 °C není běžný cílový údaj tělesné teploty novorozence.
- XVII/20 (616): somatostatin tvoří v pankreatu delta buňky; jeho místní účinek se odlišuje od úlohy hypotalamického somatostatinu při řízení růstového hormonu.
- XVII/22: novorozenec bolest vnímá. Ochranný slzný film není totéž co nápadně viditelné slzy při pláči.
- XVII/23 (619): klíč přijímá oba výroky, ale 20 hodin není jednotná potřeba spánku všech kojenců a vývoj mozkové kůry není při narození plně dokončený. Tyto nepřesnosti jsou výslovně opraveny.
- XVII/24, XVII/33 a XVII/34: věkové hranice puberty a dospělosti jsou orientační; adolescence může v širším významu zahrnovat i pubertu.
- XVII/28 a XVII/29: základy řeči a jemná motorika se rozvíjejí již během prvního roku; výlučně mléčná výživa nevystihuje celý kojenecký věk. Některé alternativy tak podle výkladu částečně platí. Stoličky se obvykle prořezávají později, s individuálním rozptylem.
- XVII/31: kojenecké období končí prvními narozeninami, nikoli dosažením přesné hmotnosti nebo ukončením kojení.

Upozornění z předchozích verzí zůstávají u dotčených otázek přímo v aplikaci.

## Co bylo ověřeno

- Celý náhodný test 630 různých otázek: zbarvení odpovědí, vysvětlení, ochrana před dvojím započtením, dokončení a skóre.
- Aktualizace z 600 na 630 otázek na stejné adrese zachovává všechna uložená pole: chyby, tipy, zvládnuté otázky i rozpracované starší kolo o 600 otázkách.
- Skutečné zavření a znovuotevření testovacího prohlížeče před aktualizací i po ní; obnovení nového kola po 611 odpovědích.
- Chytré opakování, plánované odstupy, nezapočítání tipů jako zvládnutí a návrat chybné otázky po dalších odpovědích.
- Všech 630 otázek a vysvětlení při šířkách 320, 390, 768 a 1024 pixelů bez vodorovného přetékání; tlačítka nejméně 64 pixelů vysoká.
- Offline spuštění jediného HTML, náhradní chování při blokovaném úložišti a zotavení po poškozených uložených datech.
- Shoda zabaleného HTML s aktuálním souborem, přesně dva soubory v balíčku a integrita ZIP.

## Spuštění a nahrání

Otevři `index.html` v prohlížeči. Stažený soubor funguje bez internetu.

Na GitHub nahraj **obsah této složky** do stejného místa jako dosud: `index.html` a `README.md`. Název vydané složky slouží pro archivaci; kvůli nové verzi není potřeba měnit adresu webu.

Pokrok se ukládá po každé odpovědi v konkrétním prohlížeči a jeho profilu, odděleně od HTML souboru. Nahrazení aplikace na stejném webu ho zachovává, pokud zůstala zachovaná data prohlížeče. Mezi zařízeními se nesynchronizuje; vymazání dat nebo ukončení anonymního režimu může pokrok odstranit. U místně otevřeného souboru může přesunutí do jiné složky znamenat jiné úložiště; pro pravidelné používání zachovej stejnou webovou adresu.

Rozpracované starší kolo (například test 600 otázek) si zachová původní délku. Nové otázky se zapojí do nově zahájeného kola a chytrého procvičování; dřívější znalost původních otázek zůstane uložená.

## Historie verzí

| Verze | Otázky | Hlavní změna |
| --- | ---: | --- |
| 1.12.0 | 630 | Posledních 30 otázek XVII/5–34: dokončena celá sada PDF, kontrola klíče a zachování pokroku. |
| 1.11.0 | 600 | Dalších 50 otázek: dokončení pohlavního systému, těhotenství a porod, první čtyři otázky o novorozenci; kontrola klíčů i zachování pokroku. |
| 1.10.0 | 550 | Dalších 50 otázek: dokončení nervového řízení, všechny smysly a začátek pohlavního systému; kontrola klíčů i zachování pokroku. |
| 1.9.0 | 500 | Dalších 50 otázek nervového řízení: neurony, glie, CNS, reflexy a nervy; kontrola klíče i zachování pokroku. |
| 1.8.0 | 450 | Dalších 50 otázek: dokončení kůže, celé hormonální řízení a začátek nervového systému; kontrola klíčů a zachování pokroku. |
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

- **1.13.0:** nová funkce nebo obsah z dalšího zdroje. Původní PDF je již kompletní.
- **1.12.1:** drobná oprava současné verze.
- **2.0.0:** zásadní přepracování aplikace.

Každé další vydání má vlastní složku a ZIP se stejným číslem verze a obsahuje `index.html` a aktualizované `README.md`. Při přidávání otázek se zachovají identifikátory dosavadních otázek a kompatibilita uloženého pokroku.
