# mit-AIS-project

AIS - Information Systems Analysis and Design

# Task

## Části projektu

projekt se skládá ze dvou samostatně odevzdávaných a hodnocených částí:
1. ''Plánování projektu'' - neformální specifikace, prvotní analýza požadavků vč. UML diagramu případu užití, plán projektu s nejméně dvěma iteracemi (ke každé UML diagram případů užití realizovaných v dané iteraci). Odevzdává se zpráva s názvem "Prvotní analýza a plán projektu" zahrnující výše uvedené.
2. ''Modely analýzy a návrhu z 1. iterace'' a ''Výsledné modely analýzy a návrhu'' - dvě oddělené sady UML modelů (jedna pro 1. iteraci a druhá pro poslední iteraci) kreslené ručně nebo použitím dostupného modelovacího nástroje (např. [https://www.fit.vutbr.cz/~rychly/private/vpapp/ Visual Paradigm s akademickou licencí]). Odevzdává se zpráva s podtitulkem "Modely 1. iterace" zahrnující modely 1. iterace a podtitulkem "Výsledné modely" zahrnující výsledné modely z poslední iterace, a to vždy včetně UML diagramu případu užití dané iterace a dalších upřesněných níže. Součástí odevzdání této zprávy je obhajoba.

### Požadovaný obsah řešení

- Model případů použití, tj. diagramy případů použití a podrobnější specifikace celkem alespoň tří případů použití (složitějších scénářů, tj. ne například pouhé zobrazení všech entit nějaké entitní třídy, tedy řádků tabulky). Diagramy případů použití budou v první odevzdávané části i ve druhé odevzdávané části, tj. ve výsledných modelech, a to vždy pro každou z iterací. Podrobnější specifikace případů použití stačí pouze v druhé odevzdávané části.
- Seznam výjimek vznikajících v rámci případů použití a požadované chování systému při jejich výskytu.
- Návrh architektury aplikace s využitím některého z architektonických vzorů.
- Systémový diagram sekvence pro určitý scénář z modelu případů užití.
- Model domény jako diagram tříd. Musí být korespondence mezi popisem případů použití, modelem domény (jména tříd, atributů atd.) a návrhem schématu databáze (diagram logického schéma).
- Strukturovaný popis zodpovědnosti tříd účastnících se sekvence popsané v systémovém diagramu sekvence pro určitý scénář z modelu případů užití. Pro každou přímo účastnící se třídu musí popis obsahovat zodpovědnost a název operace třídy (vč. parametrů), která ji řeší, a dále pak zdůvodnění, proč byla přiřazena odpovědnost právě dané třídě (možno využít princip GRASP avšak nestačí uvést pouze název, ale je nutno i stručně popsat proč) a seznam spolupracujících tříd. Např. je možno popsat tabulkou s pěti sloupci: zodpovědnost, operace, název třídy, zdůvodnění, seznam názvů spolupracujících tříd.
- Návrhový diagram tříd obsahující (mimo jiné) třídy a operace zmiňované ve strukturovaném popisu zodpovědnosti tříd a s případnou vazbou na standardní třídy dostupné v daném vývojovém prostředí či použitém implementačním rámci. Musí zde být viditelně použit alespoň jeden návrhový vzor.
- Rozdělení jednotlivých třídy návrhového diagramu do jednotlivých vrstev v návrhu architektury zvoleného architektonického vzoru s vyznačením komunikace mezi vrstvami.
- Alespoň 3 diagramy interakce realizující operace vybraných scénářů z modelu případů užití. Z těchto diagramů musí alespoň jeden být diagram sekvence popisující realizaci některé operace uvedené ve strukturovaném popisu zodpovědnosti tříd a alespoň jeden musí být diagram komunikace.
- Model ukazující návaznosti jednotlivých obrazovek, resp. případů použití, včetně přechodů mezi nimi, vyjádřený vhodným UML diagramem.
- Alespoň jeden strukturovaně popsaný přejímací test validující některý z případů použití. Popis musí obsahovat číslované kroky testu popisující, co se testuje, a popis stavu systému před započetím testu a po skončení testu (tj. počáteční podmínky a očekávaný výsledek po testu). Není potřeba uvádět konkrétní hodnoty, ale musí být jasné, že se např. do databáze nahrají nějaká data, která se potom při testování budou využívat, a jak se v jednotlivých krocích využijí.
