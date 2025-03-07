### Analýza a návrh informačního systému

## 40: Jízdní řády MHD

Úkolem je vývoj webové aplikace, která poskytne uživatelům informaci o spojení mezi dvěma místy A a B prostředky městské hromadné dopravy. Příkladem podobné aplikace může být ta na stránkách MHD Brno.

## Cíl projektu

Cílem projektu je analyzovat požadavky a navrhnout část informačního systému dle zvoleného tématu. Při návrhu je nutné použít modelovací techniky a diagramy odpovídající objektově-orientované analýze a návrhu pomocí jazyka UML.

Projekt z předmětu AIS navazuje na projekt v předmětu PIS (Pokročilé informační systémy), kde by návrh systému vytvořený v AIS mohl být implementován v konkrétním programovacím jazyce.

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

Další požadavky pro řešení projektu (kromě instrukcí v šabloně výše):

- V plánu projektu budou alespoň tři iterace.
- Specifikace případů použití, tedy diagramy případů použití a podrobnější specifikace, budou vytvořeny alespoň pro tři případy užití se složitějšími scénáři (např. ne pouze zobrazení nebo úprava entit doménové třídy, tedy řádků tabulky databáze). Modely případů použití budou v první části (jako UML diagramy analýzy požadavků) i v druhé odevzdávané části každé iterace (včetně podrobnější specifikace).
- Doménový model bude společný pro všechny případy užití.
- Bude popsán jeden systémový diagram sekvence pro určité scénáře z popsaných případů užití.
- Kontrakty systémových operací budou popisovat všechny operace ze systémového diagramu sekvence a budou zahrnovat alespoň tři operace.
- Návrh základní architektury systému bude vycházet z architektonického vzoru a bude obsahovat jasně definovanou část s doménovými objekty (vrstva domény nebo jiná ekvivalentní vrstva dle zvoleného návrhového vzoru).
- Zodpovědnosti tříd budou určeny pro všechny popsané systémové operace a pro další volané operace.
- V návrhovém diagramu tříd budou uvedeny operace, které řeší všechny zodpovědnosti tříd, a to včetně vazby na standardní třídy dostupné v daném vývojovém prostředí (např. kolekce, datum apod.). Diagram bude obsahovat třídy z doménové vrstvy a alespoň jeden návrhový vzor.
- Budou vytvořeny alespoň tři návrhové diagramy interakce pro všechny popsané systémové operace. Z těchto diagramů bude alespoň jeden diagram sekvence a alespoň jeden diagram komunikace. Systémový diagram sekvence není návrhovým diagramem interakce, jde o artefakt analýzy požadavků.
- Budou popsány přechody obrazovek vztažené alespoň k jednomu popsanému případu užití.
- Bude popsán akceptační test vztažený alespoň k jednomu popsanému případu užití.
- Pro tvorbu UML diagramů můžete využít nástroj jako Visual Paradigm for UML.

Projekt se odevzdává postupně ve dvou výsledcích a následně probíhá závěrečná obhajoba:

- Obhajoby projektů probíhají v posledním týdnu semestru a prvním týdnu zkouškového období.
- Studenti se přihlásí na jeden z termínů obhajoby, které budou vypsány v informačním systému. Za každý tým se na obhajobu přihlašuje pouze jeden student.
- Obhajoba projektu by měla trvat přibližně 10 minut. Všichni členové týmu musí být připraveni obhajovat některou z odevzdávaných částí. Kvalita obhajoby a připravenost jsou hodnoceny. Pokud se během obhajoby prokáže, že studenti nerozumí odevzdávaným diagramům, mohou být uděleny záporné body.
- Součástí obhajoby je i odevzdání vytištěné zprávy, která zahrnuje výše uvedené součásti projektu.

Každý odevzdaný výsledek bude hodnocen vyučujícím a za správné řešení lze získat až 5 bodů za první výsledek a až 29 bodů za druhý výsledek (celkem až 34 bodů za celý projekt).

Další podmínky hodnocení:

- Vážné chyby a nedostatky, neúplnost budou penalizovány snížením počtu bodů.
- Vyšší hodnocení bude uděleno za nadprůměrné projekty, které vynikají kvalitou provedení, vytvořením dalších (explicitně nepožadovaných) modelů, použitím dalších návrhových vzorů, kvalitní obhajobou apod. Takový projekt může získat nejen maximální hodnocení, ale i prémiové body navíc.
- Silně se doporučuje provést interní oponenturu v týmu před odevzdáním, kde se všichni členové snaží nalézt případné nedostatky a tyto opravit.
- V případě odpadnutí některých členů týmu během řešení projektu (např. z důvodu zrušení zápisu předmětu nebo odstoupení) je potřeba tuto situaci co nejdříve řešit nebo nahlásit vyučujícímu.
- Při hodnocení se zohlední velikost týmu; požadavky na rozsah řešení platí pro dvoučlenný tým, a u většího týmu se očekává složitější systém s širším záběrem (ne pouze větší počet jednodušších případů užití).
