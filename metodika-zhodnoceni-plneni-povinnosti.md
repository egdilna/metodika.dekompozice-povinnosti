---
Title: Metodika zhodnocení plnění povinností a provádění Assessmentu EG povinností a jeho uudržování
---

DOPSAT titulku a kecy o diplomce


# KEKOREKTUŘE Úvod

Toto je metoedický a návodný dokument pro všechny úřady, které chtějí využít zhodnocení plnění EG povinností, či mají takovou povinnost v rámci přípravy a rozvoje své informační koncepce.

## Autoři a licence dokumentu

Tento dokument a veškerý jeho obsah je pod otevřenou licencí CC v souladu s licencí Národní architektury eGovernmentu uvedené na webu archi.gov.cz. Kdokoliv může tento dokument libovolně použít a upravit jej dle svého, je ale vždy povinen uvést zdroj dokumentu, kterým je EGdílna. Dokument je výstupem diplomové práce Miroslava Pavelky, Fakulta XXX, Česká zemědělská univerzita. Dokument je možno použít a publikovat samostatně bez nutnosti znát diplomovou práci.

DOPSAT fakultu a studijní obor a rok


Dokument (C) 2022-2023 EGdílna (www.egdilna.cz). Dokument vytvořen s asistencí a pro potřeby metodického kompetenčního centra.

Autoři dokumentu: Miroslav Pavelka, Michal Rada, Vladimír Dvořák, Jan Jakoubek 

Dokument je v otevřeném formátu spolu se všemi souvislostmi a zdroji na veřejném GIT repozitáři na adrese

DOPLNIT adresu GITu


## 🖋 Účel a použití metodiky

Tato metodika slouží pro poznání a návody, jak sledovat a zhodnotit plnění svých povinností k eGovernmentu. Díky tomuto dokumentu a zde uevedeným postupům úřad zvládne jednu z částí řízení ICT a služeb a tou je zhodnocení plnění EG povinností (assessment povinností) a také pochopí jeho přínosy a bude schopen získané znalůosti použít pro zvýšení efektivity úřadu.


## Historie změn

Toto je první verze metodiky.

## KEKOREKTUŘE Shrnutí metodiky

Dokument je rozdělen do tří na sebe vzájemně navazujících částí. První teoretická část [Úřad a Povinnosti] popisuje celý rámec povinností a jejich místo ve znalostech a architektuře úřadu a seznamuje s Mapou EG povinností a jejím využitím. Druhá praktická část [Tvorba zhodnocení plnění povinností (assessment povinností)] popisuje podrobně, jak si v úřadu zpracovat assessment povnností jako zdroj znalostí o stavu plnění a dodržování každé obecné povinnosti a jak poznatky z tohoto assessmentu dále využít v úřadu a jako základ pro projekty rozvoje ICT. Třetí část popisuje podrobněji, jak v assessmentu skutečně zhodnotit jednotlivou povinnost a podle čeho postupovat při posuzování míry splnění a stanovení nápravných kroků. 

Dokument mimo obsahu má i odkazy na externí zdroje, které budou dále v budoucích verzích udržovány funkční. Společně s těmito odkazyx a dalšími informacemi z oblasti koncepčního řízení ICT v úřadu je to ucelenou metodikou zahrnující vše, co bude úřad v oblasti assessmentu povinností potřebovat.

## Některé nové pojmy a jejich význam

Obecné pojmy týkající se eGovernmentu obsahuje [Slovník pojmů eGovernmentu](https://archi.gov.cz/slovnik_egov). 
Pro účely této metodiky do slovníku přidáváme následující pojmy:

DOPLNIT sem pojmy ze slovníku až budou schválené

S těmito pojmy metodika běžně pracuje a hovoříme-li tedy kupříkladu o "zodpovědném" v rámci assessmentu, máme tím na mysli právě zodpovědný útvar.

# Úřad a Povinnosti

## KEKOREKTUŘE Co jsou to povinnosti a jak to zakotvit v řízení a architektuře úřadu


### Povinnost

Úřad obecně funguje podle určitých mantinelů. Na obecné úrovni jsou těmito mantinely legislativa a agendy, v nichž působí. Na detailnější úrovni se jedná o rámec povinností, které úřad plní. Takže se dá vlastně říct, že úřad funguje podle povinností. Povinnosti musíme ale umět brát ve dvou rovinách:

1. Povinnost jako něco, co definuje právní předpis a my to musíme vždy naplnit a neporušovat tento základní princip
2. Povinnost jako něco, co umíme dobře uchopit a popsat a podle čeho jednáme ve své práci.

Pokud bychom k povinnosti přistupovali jen podle prvního bodu a budeme k tomu přistupovat jako k nutnému zlu, sice si uděláme rámec pro splnění zákonů, ovšem další pozitivní přínosy poznání plnění povinností z toho mít nebudeme. Pokud ale budeme k povinnosti přistupovat i podle druhého bodu jako k poznání aktuálního stavu, bude to pro nás znamenat cenný zdroj. Je tedy vhodné se na povinnosti a jejich plnění dívat pozitivně. Přistupujme k tomu tedy jako k příležitosti.

Co je to tedy ta povinnost? Lidsky řečeno, je to jedna konkrétní věc, kterou podle zákona musíme dělat. Definuje jí nějaký zákon a dokonce i konkrétní ustanovení (může jich být i víc) a pro nás to znamená nějakou práci v rámci našich procesů. Povinnost může přitom být zcela konkrétní a jedinečná, jako třeba "Sdělit konkrétně někomu něco" (sdílení jednoho údaje jinému OVM či klientovi), ale většinou jde o povinnost obecnou, jako "zaslat osvědčení o digitálním úkonu", nebo ještě obecnější "poskytovat naše agendové údaje". Čím obecnější povinnost je, tím se hůř chápe přes celý úřad, na druhou stránku ale každou povinnost můžeme zařadit do nějaké oblasti, kterou má v našem úřadu někdo nestarosti.


## KEKOREKTUŘE Povinnost a architektura úřadu

Povinnost tedy je něco, co děláme a víme, jestli a jak moc to děláme. Přestože by se tedy mohlo zdát, že povinnost je pro nás motivací, z pohledu architektury jde o byznysový prvek svázaný s daným předpisem a realizovaný v našich procesech. Z pohledu architektury je tedy důležité následující:

* Právní předpis určuje povinnost.
* Útvar zodpovídá za povinnost.
* Garant assessmentu zodpovídá za Assessment povinností
* Assessment povinností je assessmentem

Architekti si asi pokládají následující otázky:

1. Je vhodné do architektury modelovat povinnosti? Pokud jsou pro nás důležité a považujeme je za rozhodující zdroje poznání, tak ano. Pokud si udržujeme přehled povinností a stav jejich plnění v samostatném Assessmentu povinností a víme, jak je navázán na architekturu, pak jednotlivé povinnosti modelovat nemusíme.
1. Pokud chceme modelovat povinnosti v architektuře, tak jak? Povinnost je byznys objektem, má vždy povinně vazbu z právního předpisu jako kontraktu asociací na objekt povinnosti. Pokud je povinnost součástí schopnosti či procesu a je to pro nás důležité, zmodelujeme i takovou vazbu.
1. Co dodržovat při modelování povinností? Povinnosti si nevymýšlíme, ale využijeme připravené datové sady z Mapy EG povinností. Zde si vezmeme Kód povinnosti jako ID architektonického prvku, Název jako název prvku, Popis jako popis prvku a jako stereotyp použijeme "Povinnost" s využitím konceptu "BusinessObject" a vazbu na předpis podle názvu předpisu prvku Contract, k tomu využijeme vždy příslušné prvky metamodelu.
1. Zásadně neděláme zástupné prvky typu "povinnosti k datovkám", apod. Pokud chceme v architektuře udržovat a modelovat povinnosti, tak to děláme pro jednotlivé povinnosti.

DOPLNIT odkaz na prvky metamodelu na gitu 

### 🖋 Povinnosti jako zdroj informací pro řízení a zlepšování



## Dva druhy povinností

Povinnosti jako takové se defacto dají rozdělit do dvou forem/kategorií.

1. Povinnosti agendové: Jsou zaznamenány jako agendové činnosti v rámci ohlášení agendy v Registru práv a povinností. Pocházejí jako zcela konkrétní a víceméně jednoúčelové a jednoprocesní povinnosti z daného ustanovení agendového zákona.
1. Obecné povinnosti: Jde o obecné vždy povinně dodržované povinnosti platné nehledě na agendu, v níž se vykonávají činnosti. Takové povinnosti jsou pro zmapování složitěji, ale musí se uplatňovat vždy na úrovni celého úřadu. Tyto povinnosti jsou z pohledu digitalizace vedeny a mapovány v rámci Mapy EG povinností.

Tato metodika se dále věnuje pouze druhé skupině povinností, neboť co se týče plnění agendových služeb a činností, k tomu existují jiné metodiky a navíc se postup plnění liší agendu od agendy. My se budeme věnovat jen těm obecným a z toho si vybereme pro účely zmapování stavu úřadu ty povinnosti, které se týkají digitalizace a tedy tzv. EG zákonů.


## Mapa EG povinností a její použití

# Tvorba zhodnocení plnění povinností (assessment povinností)

# Vyhodnocení stavu plnění povinnosti a kroky k nápravě

Nejdůležitější částí assessmentu je právě zhodnocení u jednotlivých povinností, proto se celý assessment dělá. Ať už bude samotné zhodnocení veřejnou částí informační koncepce, či nikoliv, je nezbytné, abychom byly při vyhodnocování opravdu upřímní a pravdiví. Stavy vyhodnocení nám má sloužit pro lepší poznání a hlavně jako zdroj pro potřebné změny. Může se jednat o změny procesní, legislativní, technické či architektonické.

## Obecný postup při zhodnocení plnění povinnosti

1. Určíme si, které povinnosti jsou pro nás relevantní a které nnikoliv.
2. Určíme útvar (a pokud možno konkrétní osobu) zodpovědnou za plnění povinnosti napříč celou organizací.
3. Pravdivě zhodnotíme, jak moc danou povinnost plníme a to zapíšeme s podrobnostmi do assessmentu.
4. Musíme znát, jaké prostředky (zejména informační systémy a jejich integrace) k plnění povinnosti využíváme a v jakém jsou stavu.
5. Sepíšeme si, co se musí obecně stát, abychom povinnost řádně plnili a to zcela a vždy.
