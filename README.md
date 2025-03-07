# Analýza a návrh informačního systému

## 40: Jízdní řády MHD

Vaším úkolem je vývoj webové aplikace, která poskytne uživatelům informaci o spojení ze zadaného místa A do zadaného místa B prostředky městské hromadné dopravy – viz např. obdobná aplikace na stránkách MHD Brno.

## Cíl projektu

Cílem projektu je analyzovat požadavky a navrhnout část informačního systému dle zvoleného tématu. Použité modelovací techniky a diagramy musí odpovídat objektově-orientované analýze a návrhu pomocí modelovacího jazyka UML.

Na projekt předmětu AIS navazuje projekt v předmětu PIS (Pokročilé informační systémy), kde by návrh systému vytvořený v AIS mohl být skutečně implementován v prostředí nějakého programovacího jazyka.

Projekt se skládá ze dvou samostatně odevzdávaných a hodnocených částí:

1. **Prvotní analýza požadavků a plán projektu**:
   - Neformální specifikace
   - Prvotní analýza požadavků
   - Plán projektu
2. **Analýza a návrh v první iteraci + Finální analýza a návrh**:
   - Specifikace případů užití
   - Doménový model (DM)
   - Systémový diagram sekvence (SSD)
   - Kontrakty systémových operací (OCs)
   - Základní architektura (EAB)
   - Určení zodpovědnosti tříd (CRC)
   - Návrhový diagram tříd
   - Návrhové diagramy interakce
   - Přechody obrazovek uživatelského rozhraní
   - Akceptační testy



Na řešení projektu jsou kladeny dále následující požadavky (mimo instrukce k provedení uvedené v šabloně výše):

    - V plánu projektu budou alespoň tři iterace.
    - Specifikace případů použití, tj. diagramy případů použití a podrobnější specifikace, budou vytvořeny alespoň pro tři případy užití se složitějšími scénáři (tj. ne například pouhé zobrazení/úprava entit nějaké doménové třídy, tedy řádků tabulky databáze). Modely případů použití budou v první (zde jen jako UML diagramy analýzy požadavků) i ve druhé odevzdávané části v každé iteraci (vč. podrobnější specifikace případů užití).
    - Doménový model bude jeden společný pro všechny případy užití.
    - Bude popsán jeden systémový diagram sekvence pro určitý scénář z popsaných případů užití.
    - Kontrakty systémových operací budou popisovat všechny operace ze systémového diagramu sekvence a takové operace budou alespoň tři.
    - Návrh základní architektury systému bude využívat některého z architektonických vzorů a musí mít jasně určenu část s doménovými objekty (vrstvu domény či jinou jí ekvivalentní dle použitého návrhového vzoru).
    - Zodpovědnosti tříd budou určeny pro všechny popsané systémové operace a další jimi volané operace.
    - V návrhovém diagramu tříd musí být uvedeny operace řešící všechny popsané zodpovědnosti tříd s případnou vazbou na standardní třídy dostupné v daném vývojovém prostředí či použitém implementačním rámci (např. třídy/rozhraní pro kolekce, datum, atp.). Musí zde být třídy z doménové vrstvy (vizte předchozí bod) a musí zde být viditelně a vhodně použit alespoň jeden návrhový vzor.
    - Budou vytvořeny alespoň 3 návrhové diagramy interakce realizující všechny popsané systémové operace. Z těchto diagramů musí alespoň jeden být diagram sekvence a alespoň jeden musí být diagram komunikace. Systémový diagram sekvence není návrhovým diagramem interakce (je to artefakt analýzy požadavků).
    - Budou popsány přechody obrazovek vztažené alespoň k jednomu popsanému případu užití.
    - Bude popsán akceptační test vztažený alespoň k jednomu popsanému případu užití.
    - Pro tvorbu UML diagramů můžete využít např. Visual Paradigm for UML.

V rámci projektu se odevzdávají postupně dva výsledky a poté je závěrečná obhajoba projektu.

    - Obhajoby projektů budou probíhat v posledním týdnu semestru a prvním týdnu zkouškového období.
    - Studenti se přihlásí na jeden z termínů obhajoby, které budou vypsány v informačním systému. Za každý tým se na obhajobu přihlašuje pouze jeden student.
    - Obhajoba projektu by měla trvat přibližně 10 minut. Na obhajobě se musí podílet všichni členové řešitelského týmu (každý musí být připraven obhajovat některou z odevzdávaných částí projektu). Jedním z kritérií hodnocení projektu je připravenost na obhajobu a kvalita obhajoby. Pokud se během obhajoby prokáže, že studenti nerozumí odevzdávaným diagramům, mohou být za daný diagram uděleny i záporné body.
    - Součástí je také odevzdání vytištěné zprávy zahrnující výše uvedené součásti projektu na obhajobě.

Každý odevzdaný výsledek bude ohodnocen vyučujícím a za správné řešení můžete získat v případě prvního výsdledku až 5 bodů a v případě druhého až 29 bodů (tj. až 34 bodů za celý projekt).

    - vážnější chyby a nedostatky a neúplnost budou penalizovány snížením počtu bodů
    - vyšší hodnocení bude udělováno v případě nadprůměrných projektů, které se budou vyznačovat nadprůměrnou kvalitou provedení výše uvedeného rozsahu, vytvořením dalších (explicitně nepožadovaných) modelů, použitím dalších návrhových vzorů, kvalitní obhajobou apod.; takový projekt může získat nejen maximální hodnocení, ale i prémiové body navíc
    - je silně doporučeno udělat před odevzdáním v rámci týmu interní oponenturu, kde se všichni členové týmu snaží nalézt v řešení případné nedostatky a tyto později opravit
    - pokud dojde v průběhu řešení projektu k odpadnutí některých členů týmu (např. z důvodu zrušení zápisu předmětu či odstoupení od řešení), je potřeba to v týmu řešit co nejdříve nebo, pokud je problém, nahlásit situaci vyučujícímu; případní odpadlíci, nahlaste kolegům svou absenci co nejdříve, ať mají možnost projekt úspěšně dokončit
    - při hodnocení se bude přihlížet k velikosti řešitelského týmu; výše požadovaný obsah řešení (např. počty diagramů) platí pro dvoučlenný tým a u většího týmu se předpokládá řešení složitějšího systému (ne měřeno větším počtem jednodušších případů použití, ale s celkově širším "záběrem")

