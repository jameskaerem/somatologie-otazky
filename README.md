# Kvíz pro Markét

Verze 2.0.0 • 27. 10. 2026

Jedna webová stránka, dvě záložky: **Somatologie (630 otázek)** a **Biologie (50 otázek)**. Mobilní rozvržení, vysvětlení po každé odpovědi, chytré procvičování, opakování chyb a tipů, náhodný test celé sady. Aplikace je v jediném samostatném `index.html` a funguje i offline.

## Nahrání na současný web

1. Rozbal ZIP.
2. Nahraď na stávajícím webu soubor `index.html` novým souborem. README je dokumentace.
3. Zachovej stejnou webovou adresu a prohlížeč, ve kterém byl původní pokrok uložený.
4. Po načtení stránky vyber záložku nahoře. Rozpracované kolo zůstává dostupné přes „Pokračovat v kole“.

Tento balíček není automaticky nahraný na veřejný web. Je připravený k nahrazení předchozí verze na stejné adrese.

## Zachování somatologie

- Všech 630 otázek, jejich ID, možnosti, odpovědi a vysvětlení se přesně shodují s původní verzí 1.12.0.
- Zachovaný klíč úložiště `somatologie-learning-v2`, verze dat 2, pravidla opakování a migrace nejstarší desetio­tázkové verze.
- Původní pokrok i rozpracované kolo se načítají bez převodu. Přepnutí záložky kolo neukončuje.
- Biologie používá samostatný klíč `biologie-learning-v2`. Výsledky, tipy, chyby, termíny a kola se mezi předměty nemíchají.
- Vymazání pokroku maže pouze vybraný předmět a vyžaduje potvrzení. Druhý předmět ponechá.
- Volbu poslední záložky si aplikace pamatuje samostatně.

Pokrok je místní pro konkrétní prohlížeč a webový původ. Přechod na jinou doménu, jiný prohlížeč, anonymní režim nebo vymazání dat jej nepřenese. Otevření staženého HTML není totéž úložiště jako původní web.

## Biologie: první sada

Zdroj: Ivan Novotný, Michal Hruška, **Biologie člověka pro gymnázia**, Fortuna, 4. přepracované vydání, 2007, ISBN 978-80-7373-007-9. Dodaný soubor: `623763327-biologie-cloveka.pdf`.

Otázky 1–50 jsou nově vytvořené testy A–D podle výkladu na **tištěných stranách 15–29, PDF stranách 8–15**. Nejde o přepis hotové testové banky nebo oficiálního klíče: kniha obsahuje výklad a otevřené studijní otázky. Každý test má jednu správnou odpověď, odkaz na tištěnou stránku, tři vysvětlující odstavce a paměťovou pomůcku. Texty knihy byly vizuálně přečteny ze skenu; nevyužívá se neověřený OCR přepis.

Témata: organizace těla a homeostáza; řízení tělesných soustav; vazivo, chrupavka a kost; kostní buňky, mineralizace, dřeň a růst; kloubní spojení; páteř a hrudník; lebka; pletenec a kosti končetin. Testy se vyhýbají nepřesným zobecněním zdroje, například klasifikaci skloviny jako pojiva. Biologické otázky jsou ověřené proti příslušnému výkladu, nikoli proti neexistujícímu tištěnému klíči A–D.

Další dávka má pokračovat ID 51–100. Doplnit lze zbývající učivo o kostře a následně svalstvo od tištěné strany 30. Zachovat prvních 50 ID i jejich obsah a oba klíče úložiště.

## Ověření

- Přesná strojová shoda všech 630 původních otázek.
- Načtení dat vytvořených původním řadičem, včetně přerušeného kola a tipu, bez změny uložených dat.
- Celé kolo 630 otázek somatologie a 50 otázek biologie; hodnocení, zbarvení tříd odpovědí, vysvětlení a ochrana před dvojím započtením.
- Přepínání předmětů, samostatná kola, obnovení při opětovném načtení, oddělený reset, chytré opakování a migrace staré verze pouze do somatologie.
- Náhradní fungování při blokovaném úložišti, zotavení po poškozených datech a neplatném názvu záložky.
- Ovládání záložek klávesami vlevo/vpravo, Home a End.

Testy spouštějí skutečný JavaScript aplikace s minimálním adaptérem DOM. **Nejde o test ve skutečném prohlížeči:** místní HTTP náhled se v dostupném prohlížeči nenačetl a přímé otevření souboru blokovala jeho bezpečnostní politika. Vizuální vykreslení a skutečné prohlížečové úložiště nové verze proto nebyly ověřeny. Rozvržení vychází z původní aplikace s přidanými responzivními záložkami.
