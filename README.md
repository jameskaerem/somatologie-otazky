# Somatologie

**Verze: 1.11.0**  
**Datum vydání: 26. 10. 2026**  
**Počet otázek: 600**

Mobilní procvičování somatologie v jediném samostatném HTML souboru. Obsahuje logická vysvětlení, chytré opakování a ukládání pokroku v prohlížeči.

## Změny v této verzi

- Přidáno přesně 50 otázek, čísla 551–600: XVI/25–70 a XVII/1–4. Sada dokončuje pohlavní systém včetně ovariálního a děložního cyklu, časného vývoje, placenty, těhotenství a porodu; navazuje čtyřmi otázkami o novorozenci.
- Každá nová otázka má tři odstavce vysvětlení souvislostí a pomůcku pro zapamatování. Přiřazovací úlohy mají legendu, dvojice tvrzení se zobrazují odděleně.
- Všech 600 hodnocených odpovědí souhlasí s přepisem tištěných klíčů PDF. Nová sada byla přečtena a kontrolována přímo ze skenu bez internetových zdrojů a bez přebírání ručních značek.
- Nové otázky: PDF strany 71–76 (tištěné strany 140–148 a 150). Použité klíče pro novou sadu: PDF strana 75 (tištěná 148) a PDF strana 79 (tištěná 156).
- Původních 550 otázek, jejich identifikátory, možnosti i vysvětlení zůstaly beze změny. Zachovány jsou klíč `somatologie-learning-v2`, formát uložených dat i pravidla chytrého opakování.
- V XVI/60 má originál dvě možnosti označené B. Obsah a pořadí jsou zachované, tlačítka jsou sjednocena na A–D; správná první možnost A se nemění.

## Přesnost a problematické formulace učebnice

Hodnocení nadále sleduje tištěný klíč. Vysvětlení odděluje shodu s klíčem od přesnosti originální formulace a závažné rozpory uvádí v poznámce „Pro přesnost“.

- XVI/26 (552): parametrium je okolní vazivo, nikoli totéž co perimetrium, zevní obal vlastní děložní stěny. Nadpis otázky směšuje vlastní vrstvy a okolí.
- XVI/27: hymen běžně úplně neuzavírá pochvu a nelze z něj spolehlivě určit sexuální historii.
- XVI/29 a XVI/40: nabídky obsahují další pravdivé výroky vedle jediné volby klíče. Žluté tělísko tvoří i estrogeny; k transportu vejcovodem přispívají svalové kontrakce i řasinky.
- XVI/35, XVI/37 a XVI/41: časové údaje jsou přibližné. Rozlišujeme krátké okno schopnosti oplození, ranou hormonální funkci žlutého tělíska a začátek implantace přibližně šestý až sedmý den po oplození.
- XVI/43: sekreční fáze nemusí zahrnovat rýhování zárodku; děje před menstruací nelze obecně redukovat na prosté uvolnění oxytocinu. Důležité jsou hormonální změny a místní mediátory včetně prostaglandinů.
- XVI/49–50 a XVI/59: vysvětlujeme rozdíl definice nidace, různých vymezení počátku těhotenství a užšího či širšího použití pojmu embryonální období.
- XVI/53, XVI/57 a XVI/60–63: krevní oběhy zůstávají za běžných podmínek oddělené, ale výměna látek probíhá; ochrana ani imunologická bariéra nejsou absolutní. Placentace souvisí už s probíhající implantací. Čas zachycení srdeční činnosti závisí na použité metodě.
- XVII/1 a XVII/4: procento tuku je proměnlivé a novorozenecká kostra už obsahuje kostní tkáň, přestože má významné chrupavčité struktury a dále dozrává.
- XVII/3 (599): zjevně chybná obecná hranice klíče C. Tvorba kostní tkáně nekončí ve dvanácti letech; růst pokračuje a obnova kostí probíhá během života. Hodnocení C je zachované podle PDF, vysvětlení tento omyl výslovně opravuje.

## Co bylo ověřeno

- Celý náhodný test 600 různých otázek: zbarvení odpovědí, vysvětlení, ochrana před dvojím započtením, dokončení a výsledné skóre.
- Zachování všech polí pokroku při aktualizaci z 550 na 600 otázek na stejné adrese, včetně chyb, tipů, zvládnutých otázek a rozpracovaného staršího kola o původních 550 otázkách.
- Obnovení po skutečném zavření a znovuotevření testovacího prohlížeče před aktualizací i po ní; pokračování nového kola po obnovení stránky po 561 odpovědích.
- Chytré opakování, nezapočítání tipů jako zvládnutí, dodržení plánovaných odstupů a návrat chybné otázky po dalších odpovědích.
- Všech 600 otázek i vysvětlení při šířkách 320, 390, 768 a 1024 pixelů bez vodorovného přetékání; tlačítka odpovědí mají výšku nejméně 64 pixelů.
- Offline spuštění jediného HTML, náhradní chování při blokovaném úložišti a zotavení při poškozených uložených datech.
- Shoda zabaleného HTML s aktuálním souborem, úplnost obsahu a integrita ZIP.

## Spuštění a nahrání

Otevři `index.html` v prohlížeči. Stažený soubor funguje bez internetu.

Na GitHub nahraj **obsah této složky** do stejného místa jako dosud: `index.html` a `README.md`. Název vydané složky slouží pro archivaci; kvůli nové verzi není potřeba měnit adresu webu.

Pokrok se ukládá po každé odpovědi v konkrétním prohlížeči a jeho profilu, odděleně od HTML souboru. Nahrazení aplikace na stejném webu ho zachovává, pokud zůstala zachovaná data prohlížeče. Mezi zařízeními se nesynchronizuje; vymazání dat nebo ukončení anonymního režimu může pokrok odstranit. U místně otevřeného souboru může přesunutí do jiné složky znamenat jiné úložiště; pro pravidelné používání zachovej stejnou webovou adresu.

Rozpracované starší kolo (například test 550 otázek) si zachová původní délku. Nové otázky se zapojí do nově zahájeného kola a chytrého procvičování; dřívější znalost původních otázek zůstane uložená.

## Historie verzí

| Verze | Otázky | Hlavní změna |
| --- | ---: | --- |
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

- **1.12.0:** další rozšíření otázek nebo nová funkce.
- **1.11.1:** drobná oprava současné verze.
- **2.0.0:** zásadní přepracování aplikace.

Každé další vydání má vlastní složku a ZIP se stejným číslem verze a obsahuje `index.html` a aktualizované `README.md`. Při přidávání otázek se zachovají identifikátory dosavadních otázek a kompatibilita uloženého pokroku.
