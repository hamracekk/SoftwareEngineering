# Student information system - Modul anket

Modul ankety slouží pro vytváření anket mezi studenty, k vyplňování anket studenty a prohlížení anonymizovaných výsledků anket. Každý semestr je automaticky vytvořena anketa ke studiu v rámci semestru. Tato anketa umožňuje hodnotit předmět a každého učitele v několika kritériích na stupnici 1 - 5. Dále pak umožňuje hodnotit předmět a každého učitele slovně. Číselné hodnocení je pak prezentováno v podobě různých agregovaných statistických ukazatelů spočítaných na základě jednotlivých číselných odpovědí. Slovní hodnocení je prezentováno jako seznam anonymizovaných odpovědí k předmětu nebo učiteli, kde je ke každému příspěvku uveden pouze ročník studenta. Výsledky jsou dostupné všem učitelům i studentům. Učitelé mohou vytvářet vlastní ankety pro studenty jejich předmětů. Anketa je vytvořena jako sada otázek dvojího druhu - se slovní odpovědí nebo s číselnou odpovědí na škále 1 - 5. Výsledky těchto anket jsou prezentovány obdobně jako výše popsané, ale jsou dostupné pouze učitelům a studentům daného předmětu.

---

## Functional Requirements
This section specifies the functional requirements.

### User requirements
---
##### STUDENT:
1. Jako student chci aby modul vytvářel semestrální ankety hodnotící předměty a jejich výuku.
v semestrálních anketách hodnotit učitele a předměty, protože chci poskytnout zpětnou vazbu pro budoucí studenty a učitele.
1. Jako student chci aby u mého hodnocení výuky byly anonymizovány osobní údaje, protože nechci aby případná kritika výuky/přístupu vyučujícího ovlivnila moje budoucí studijní výsledky.
1. Jako student chci mít možnost vyplňovat ankety vytvořené ostatními uživateli daného modulu anket, z dôvodu verejneho hodnocení a vytvárani statistickeho názoru na danú temu.
1. Jako student chci prohlížet výsledky semestrálních anket, protože chci znát názory předchozích studentů ohledně výuky předmětu a jeho vyučujících.
1. Jako student chci hodnotit ankety, jak číselně, tak slovně, protože tak poskytnu detailnější odpověď dalším studentům, které by měli o studium předmětu zájem.
1. Jako student chci aby výsledeky číselného hodnocení anket byly prezentovány v podobě různých agregovaných statistických ukazatelů spočítaných na základě těchto výsledků, z duvodu priehladneho a rýchleho poskytnutia releavntných a užitočných udajov uživatelom modulu.
1. Jako student chci aby výsledky slovního hodnocení anket byly prezentovány jako seznam těchto výsledků, protože chceme aby výsledky byly prezentované v přehledném, relevantním a uživatelsky příjemném formátě.
1. +? Jako student chci vytvářet vlastní (studentské) ankety, týkající se pro mě relevantních témat, např. získat doplňující informace ohledně výuky, které jsem se nedozvěděl v semestrálních anketách.
1. Jako student chci upravovat mnou vytvorené ankety, kdyby při tvorbě ankety došlo k chybě nebo z jiných důvodů.
---
##### UČITEL:
1. Jako učitel potřebuji vytvářet ankety pro studenty mých předmětů, abych dostal zpětnou vazbu k otázkám relevantním k výuce.
1. Jako učitel ale chci aby zůstali výsledky mých anket skryté pro veřejnost, protože se jedná o interní fungování předmětu.
1. Jako učitel potřebuji prohlížet a reagovat na hodnocení k výuce mých předmětů, protože se chci obhájit/poděkovat za konstruktivní kritiku.
1. Jako učitel potřebuji prohlížet výsledky semestrálních anket, protože chci znát názory studentů ohledně mojí výuky předmětu.
---
##### UŽIVATEL:
1. Jako (veřejný) uživatel chci prohlížet výsledky anket, abych si vytvořil představu o kvalitě výuky předmětů a vyučujících.
1. Jako uživatel chci prohlížet moje odpovědi na ankety.


### System requirements
[Document here your system requirements as use case diagrams.]

- #### Actors
  [Document here all actors from the use case diagrams. Make a subsection for each actor and their short description in each subsection.]

- #### Actors:
1. Students
1. Teachers
1. Public

- #### Use cases
  [Document here all use cases. Create a subsection for each use case diagram. If you have only one use case diagram, you do not need a special subsection]

- #### [Use case diagram title]
- #### [Use case diagram in PlantUML]
