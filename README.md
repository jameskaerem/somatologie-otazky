# Biologie a somatologie

Verze 2.3.0 • 28. 10. 2026

Jedna webová stránka, dvě záložky: **Somatologie (630 otázek)** a **Biologie (200 otázek)**. Vše v samostatném `index.html`, který funguje i offline. Obsahuje vysvětlení, paměťové pomůcky, chytré procvičování, opakování chyb a tipů a náhodný test celé sady.

## Změny

- Obecný název „Biologie a somatologie“ v hlavičce, titulku stránky i dokumentaci. Bez osobního věnování a osobního jména v názvu balíčku.
- Přidány biologické otázky 151–200. Původních 150 biologických i všech 630 somatologických otázek zůstává beze změny, včetně ID, možností, správných odpovědí a vysvětlení.
- Zůstávají stejné klíče a formát úložiště. Uložený pokrok i starší rozpracovaná kola se zachovají; nové celé kolo obsahuje 200 otázek.

## Nahrání na současný web

Rozbal ZIP a nahraď stávající `index.html` novým souborem. Zachovej stejnou webovou adresu a prohlížeč, ve kterém je pokrok uložený. README slouží jako dokumentace. Tento balíček nebyl automaticky nahrán na veřejný web.

Každý předmět má samostatný pokrok a rozpracované kolo. Přepnutí záložky kolo neukončuje. Vymazání pokroku po potvrzení maže pouze právě vybraný předmět.

Pokrok je místní pro daný prohlížeč a webový původ. Jiná doména, jiný prohlížeč, soukromý režim nebo vymazání dat jej nepřenese. Stažené HTML a původní web nesdílejí automaticky stejné úložiště.

## Zdroj a rozsah biologie

Ivan Novotný, Michal Hruška: **Biologie člověka pro gymnázia**, Fortuna, 4. přepracované vydání, 2007, ISBN 978-80-7373-007-9. Zdrojový soubor: `623763327-biologie-cloveka.pdf`.

Jde o vlastní testy A–D vytvořené podle výkladu, nikoli přepis hotové testové banky nebo oficiálního klíče. Každá otázka má jednu správnou odpověď, číslo tištěné stránky, tři vysvětlující odstavce a paměťovou pomůcku. Zdroj byl přečten vizuálně ze skenu. Tištěná stránka a číslo stránky PDF se liší: PDF obsahuje převážně dvoustrany.

| Biologické otázky | Téma | Tištěné strany | PDF strany |
|---|---|---|---|
| 1–50 | Úvod, regulace, pojiva, kosti, klouby a kostra | 15–29 | 8–15 |
| 51–70 | Kosterní, srdeční a hladké svalstvo, mechanismus stahu | 30–35 | 16–18 |
| 71–80 | Oddíly tělesné vody, ionty, tkáňový mok, míza a výměna látek | 35–37 | 18–19 |
| 81–100 | Krev, krvinky, destičky, srážení, plazma/sérum, AB0 a Rh | 37–42 | 19–22 |
| 101–120 | Vrozená a adaptivní imunita, B/T-lymfocyty, protilátky, paměť a imunizace | 43–47 | 22–24 |
| 121–135 | Plicní a tělní oběh, vrátnice, tepny, žíly, kapiláry a žilní návrat | 48–51 | 25–26 |
| 136–150 | Srdeční cyklus, chlopně, ozvy, puls, tepový objem, koronární cévy, převod a EKG | 51–54 | 26–28 |
| 151–170 | Tlak, průtok, odpor, baroreflex a pojmy měření tlaku | 55–60 | 28–31 |
| 171–180 | Základní cévní pojmy: ateroskleróza, LDL/HDL, trombus, ischemie, infarkt, bypass a radikály | 60–62 | 31–32 |
| 181–190 | Mízní cesty, návrat tekutin, transport tuků, uzliny a slezina | 63–64 | 32–33 |
| 191–200 | Ventilace, metabolismus plynů, vodivé cesty, hltan, hrtan a průdušky | 65–67 | 33–34 |

Přehled popisuje použité zdroje, nikoli záruku, že každý odstavec těchto stran už má samostatnou otázku. Přesný celkový počet smysluplných testů nelze určit jen z počtu stran. Další dávka naváže čísly **201–250**, respirační částí dýchací soustavy od tištěné strany 68. Přehled každé nové dávky bude uveden také ve zprávě v chatu.

Problematická zobecnění zdroje se nepřebírají do testovaných správných odpovědí: například srdce má nervovou regulaci, přestože tvoří vlastní rytmus; tkáňový mok není zcela bez bílkovin; ne všichni tkáňoví makrofágové nutně vznikají z cirkulujících monocytů. Vysvětlení rozlišují školní model a jeho meze.

## Ověření

Automatické kontroly ověřují shodu všech původních otázek, zachování uložených dat z předchozích verzí obou předmětů, starší nedokončená kola, nová kola všech 630 a 200 otázek, hodnocení, ochranu před dvojím započtením, nezávislé přepínání a reset, chytré opakování, klávesové ovládání a fungování při poškozeném či blokovaném úložišti. Kontroluje se také absence osobního názvu a integrita ZIPu.

Testy vykonávají skutečný JavaScript aplikace s minimálním adaptérem DOM. Vizuální kontrola nové verze ani ověření ve skutečném prohlížeči nebyly provedeny; předchozí místní náhled nebyl dostupný. ZIP obsahuje pouze `index.html` a `README.md`, aplikace nevyžaduje externí knihovny.
