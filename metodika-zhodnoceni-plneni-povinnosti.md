---
Title: Metodika zhodnocení plnění povinností a provádění Assessmentu EG povinností a jeho udržování
subtitle: Metodický dokument pro OVM zpracovávající si přehled svých EG obecných povinností a jejich zhodnocení, obsahuje popisnou a praktickou část s uvedením jednotlivých kroků a procesů
---

DOPSAT titulku a kecy o diplomce


# KEKOREKTUŘE Úvod

Toto je metodický a návodný dokument pro všechny úřady, které chtějí využít zhodnocení plnění EG povinností, či mají takovou povinnost v rámci přípravy a rozvoje své informační koncepce.

## Autoři a licence dokumentu

Tento dokument a veškerý jeho obsah je pod otevřenou licencí CC v souladu s licencí Národní architektury eGovernmentu uvedené na webu archi.gov.cz. Kdokoliv může tento dokument libovolně použít a upravit jej dle svého, je ale vždy povinen uvést zdroj dokumentu, kterým je EGdílna. Dokument je součástí výstupu diplomové práce Miroslava Pavelky vedené na Katedře informačních technologií Provozně ekonomické fakulty České zemědělské univerzity v Praze. Dokument je možno použít a publikovat samostatně bez nutnosti znát diplomovou práci.

Provozně ekonomická fakulta České zemědělské univerzity v Praze,
obor Veřejná správa a regionální rozvoj, akademický rok 2022/2023

Dokument (C) 2022-2023 EGdílna (www.egdilna.cz). Dokument vytvořen s asistencí a pro potřeby metodického kompetenčního centra.

Autoři dokumentu: Miroslav Pavelka, Michal Rada, Vladimír Dvořák, Jan Jakoubek 

Dokument je v otevřeném formátu spolu se všemi souvislostmi a zdroji na veřejném GIT repozitáři na adrese

https://github.com/egdilna/metodika.dekompozice-povinnosti

Aktuální verze metodiky je vždy k dispozici na webu EG metodiky na adrese

https://egdilna.cz/metodiky



## KEKOREKTUŘE Účel a použití metodiky

Tato metodika slouží pro poznání a návody, jak sledovat a zhodnotit plnění svých povinností k eGovernmentu. Díky tomuto dokumentu a zde uvedeným postupům úřad zvládne jednu z částí řízení ICT a služeb, a tou je zhodnocení plnění EG povinností (assessment povinností), a také pochopí jeho přínosy a bude schopen získané znalosti použít pro zvýšení efektivity úřadu.

Metodika assessmentu eGovernment (EG) povinností, která se vám dostává do ruky, provede váš úřad kompletním procesem zhodnocení plnění EG povinností od určení Garanta assessmentu povinností přes identifikaci povinností vztahujících se na váš úřad, jejich zpracováním až po zhodnocení jejich plnění a přijetí případných nápravných opatření vedoucích k jejich plnění.

Příjemcem metodiky je vedení úřadu, architekti (byznys architekti, architekti informačních systémů, IT a ICT architekti atp.), primárně je však určena Garantovi assessmentu povinností, jehož role musí být úřadem obsazena v samém začátku celého procesu. Nejblíže je role Garanta právě architektům a není‑li v úřadu doposud obsazena, je vhodné do ní určit/jmenovat zkušeného architekta znalého celkové architektury úřadu.

Metodika je rozdělena do čtyř hlavních částí, a to „1. Příprava na assessment EG povinností“, „2. Prvotní zhodnocení plnění EG povinností“ a „3. Roční aktualizace plnění EG povinností“, „4. xxxxxxxxxxxx“.

* V první přípravné části jsou vysvětleny základní pojmy, zejména pak popis role Garanta assessmentu povinností, vysvětlení, co je to „povinnost“, „zhodnocení plnění povinností“, kde je a jak se používá Mapa EG povinností a stručně je popsána i „Znalostní architektura“.
* V druhé a třetí části jsou již praktické postupy pro identifikaci relevantních EG povinností vztahujících se na úřady, postupy, jak tyto povinnosti zpracovat a jak hodnotit jejich plnění. Obě tyto části jsou doplněny o procesní diagramy provázející Garanta assessmentu i ostatní aktéry krok po kroku celým procesem.
* Ve čtvrté části se podrobněji věnujeme faktickému určení skutečného stavu jako základu pro vyhodnocení plnění jednotlivé povinnosti

## ☑️ Historie změn

Toto je první verze metodiky.

## KEKOREKTUŘE Shrnutí metodiky

Dokument je rozdělen do tří na sebe vzájemně navazujících částí. První teoretická část [Úřad a Povinnosti] popisuje celý rámec povinností a jejich místo ve znalostech a architektuře úřadu a seznamuje s Mapou EG povinností a jejím využitím. Druhá praktická část [Tvorba zhodnocení plnění povinností (assessment povinností)] popisuje podrobně, jak si v úřadu zpracovat assessment povinností jako zdroj znalostí o stavu plnění a dodržování každé obecné povinnosti a jak poznatky z tohoto assessmentu dále využít v úřadu a jako základ pro projekty rozvoje ICT. Třetí část popisuje podrobněji, jak v assessmentu skutečně zhodnotit jednotlivou povinnost a podle čeho postupovat při posuzování míry splnění a stanovení nápravných kroků. 

Dokument mimo obsahu má i odkazy na externí zdroje, které budou dále v budoucích verzích udržovány funkční. Společně s těmito odkazy a dalšími informacemi z oblasti koncepčního řízení ICT v úřadu je to ucelenou metodikou zahrnující vše, co bude úřad v oblasti assessmentu povinností potřebovat.

## ☑️ Některé nové pojmy a jejich význam

Obecné pojmy týkající se eGovernmentu obsahuje [Slovník pojmů eGovernmentu](https://archi.gov.cz/slovnik_egov). 
Pro účely této metodiky do slovníku přidáváme následující pojmy:



* Zhodnocení plnění povinností (Assessment povinností) je Přehled a vyhodnocení stavu plnění jednotlivých obecných povinností v úřadu. Zpracovává se pro všechny relevantní povinnosti a obsahuje stav plnění v hodnotách dle závazného číselníku a také základní kroky pro nápravu. Je součástí znalostí architektury, řízení kvality a především Informační koncepce úřadu a slouží jako jeden ze zdrojů poznání pro potřeby rozvoje a úprav systémů a procesů. / definuje  metodika ke zhodnocení plnění povinností využívají eGovernment, veřejná správa
* Povinnost je Konkrétní povinnost definovaná legislativním rámcem určující závazné jednání či postup, které je nutno za splnění zákonných podmínek vykonat. / definuje  metodika ke zhodnocení plnění povinností využívají IT právo, eGovernment, veřejná správa
* Subjekt povinnosti (subjekt) je Ten, kdo má podle zákonného určení danou povinnost plnit. Jde tedy zejména o úřad, který je subjektem pro všechny jeho povinnosti. Tento termín je třeba nezaměňovat se subjektem povinnosti v rámci konceptuálních modelů agend, kdy subjektem povinnosti může být i klient. V Mapě EG povinností se subjekty klasifikují po jednotlivých skupinách subjektů. / definuje  metodika ke zhodnocení plnění povinností využívají IT právo, eGovernment, veřejná správa
* Garant assessmentu povinností (garant) je Role v úřadu, do které je určena konkrétní fyzická osoba. Koordinuje sestavení, vyplnění a aktualizování Assessmentu povinností a zprostředkovává a koordinuje spolupráci a komunikaci mezi jednotlivými zodpovědnými útvary. Tento garant také zodpovídá za zpracování assessmentu a udržuje si přehled o potřebných krocích v rámci architektury i v rámci realizace nápravných opatření . / definuje  metodika ke zhodnocení plnění povinností využívají oblast architektury eGovernmentu, veřejná správa
* Zodpovědný za plnění povinnosti (zodpovědný) je Určená role v úřadu, většinou shodná s rolí věcného gestora za danou oblast. Pro potřeby zpracovávání Assessmentu povinností jde o útvar nebo dokonce konkrétního zaměstnance, který v celé organizaci koordinuje a kontroluje dodržování dané povinnosti napříč všemi agendami a činnostmi a zodpovídá tak za její plnění. Také je odborně zodpovědný za správné vyhodnocení plnění a za nápravné kroky. / definuje metodika ke zhodnocení plnění povinností využívají eGovernment, veřejná správa

S těmito pojmy metodika běžně pracuje a hovoříme-li tedy kupříkladu o "zodpovědném" v rámci assessmentu, máme tím na mysli právě zodpovědný útvar.

# Úřad a Povinnosti

## KEKOREKTUŘE Co jsou to povinnosti a jak to zakotvit v řízení a architektuře úřadu


### KEKOREKTUŘE Povinnost

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



## KEKOREKTUŘE Dva druhy povinností

Povinnosti jako takové se defacto dají rozdělit do dvou forem/kategorií.

1. Povinnosti agendové: Jsou zaznamenány jako agendové činnosti v rámci ohlášení agendy v Registru práv a povinností. Pocházejí jako zcela konkrétní a víceméně jednoúčelové a jednoprocesní povinnosti z daného ustanovení agendového zákona.
1. Obecné povinnosti: Jde o obecné vždy povinně dodržované povinnosti platné nehledě na agendu, v níž se vykonávají činnosti. Takové povinnosti jsou pro zmapování složitěji, ale musí se uplatňovat vždy na úrovni celého úřadu. Tyto povinnosti jsou z pohledu digitalizace vedeny a mapovány v rámci Mapy EG povinností.

Tato metodika se dále věnuje pouze druhé skupině povinností, neboť co se týče plnění agendových služeb a činností, k tomu existují jiné metodiky a navíc se postup plnění liší agendu od agendy. My se budeme věnovat jen těm obecným a z toho si vybereme pro účely zmapování stavu úřadu ty povinnosti, které se týkají digitalizace a tedy tzv. EG zákonů.


## KEKOREKTUŘE Mapa EG povinností a její použití

Nejen pro soubor povinností úřadu a pro jejich poznání se má využívat Mapa povinností.

### KEKOREKTUŘE Co je to Mapa povinností

Mapa povinností je nástroj, kde jsou evidovány veškeré obecné EG povinnosti. Slouží tedy mimo jiné i jako zdroj povinností pro jejich zhodnocení v úřadu. Mapa povinností je zveřejněna na internetu a to jak formou webové aplikace umožňující procházení a hledání povinností, tak ve formě datové sady otevřených dat.

Vše o mapě včetně přístupu k jejím nástrojům najdete na adrese

Https://egdilna.cz/mapapovinnosti 

Na tomto webu je i související dokumentace a návody, jak s mapou pracovat.


### KEKOREKTUŘE Co se v mapě eviduje a jak

Následuje diagram konceptuálního datového modelu mapy povinností s přehledem vlastností a vazeb:

[Diagram KDM mapy povinností](https://github.com/egdilna/metodika.dekompozice-povinnosti/raw/main/mapapovinnosti-diagramy/mapapovinnosti-datovymodel.png)

O každé povinnosti se vedou následující údaje:

* Vlastnost Kód: Jednoznačný identifikátor povinnosti ve složení Kód, skládá se z označení P a čísla kódu povinnosti. Užívá se jako jednoznačný identifikátor z mapy EG povinností. ()
* Vlastnost Název povinnosti: Popisný název povinnosti, který se používá jako název v textech. Musí být stručný, ale výstižný, je pochopitelně jednoznačný a jedinečný. ()
* Vlastnost Popis povinnosti: Textový popis povinnosti, většinou založený na znění konkrétních ustanovení právních předpisů. ()
* Vlastnost Určuje: Konkrétní ustanovení právních předpisů určující danou povinnost. ()
* Vlastnost Typ: Typem je buď povinnost, nebo právo. ()
* Vlastnost Skupina: Jedna či více skupin povinností podle věcné oblasti. ()
* Vlastnost Subjekty povinnosti: Seznam skupin subjektů, jež mají danou povinnost naplňovat. Obsahuje jednu či více hodnot z číselníku. Vhodné pro třídění a formátování. ()
* Vlastnost Předpisy: Seznam právních předpisů, jichž se povinnost týká, respektive, které ji definují. Využije se kupříkladu pro přehledné filtrování či pro vazby v RPP. ()
* Vlastnost Verze: Číslo verze záznamu ()
* Vlastnost Aktualizace: Datum poslední verze ()
* Vlastnost Poznámky k verzi: Poznámky zadavatele a editora k povinnosti ()

Nejdůležitějšími číselníky jsou Subjekty a Skupiny povinností. Podrobnosti těchto číselníků jsou přehledně v konceptuálním datovém modelu mapy, který je na webu mapy. Podle těchto hodnot se dá v Mapě povinností skvěle filtrovat a hledat seznam relevantních povinností, což budeme potřebovat při sestavování assessmentu v úřadu.

👉 Příklad: Zde je ukázka jedné povinnosti týkající se zpřístupnění údajů v informačních systémech, jak je zapsána v Mapě povinností:

* Kód: P237
* Název: Poskytnout subjektu elektronický výpis z ISVS a údaje z ISVS o subjektu
* Popis: Správce informačního systému veřejné správy musí umožnit držiteli zaručené identity prostředkem zaručené identifikace výpis z informačního systému a údaje z informačního systému o ní vedené, nebo informaci, že informační systém takové údaje neobsahuje. Toto musí umožnit také prostřednictvím Portálu veřejné správy.
* Určuje: § 9 odst 4 zákona 365/2000
* Typ: Povinnost
* Skupina: Povinnosti k ISVS
* Subjekty: Orgány veřejné moci, Orgány veřejné správy, and Správci informačních systémů
* Předpisy: Zákon 365/2000
* Verze: 2


### 🖋 Jak s mapou pracovat pro účely poznání a zhodnocení v úřadu



# Tvorba zhodnocení plnění povinností (assessment povinností)

Dostáváme se k praktickým návodům, jak si v úřadu udělat správně zhodnocení stavu plnění povinností a jak ho využívat pro zlepšení.


## 🖋 Co je to Assessment povinností a jak má vypadat?

Cílem v úřadu je kvalitně řídit svoji činnost a zlepšovat se. Jedním ze zásadních zdrojů je právě zhodnocení toho, jak si úřad plní svoje povinnosti. Výsledkem toho je pak Assessment povinnností, což je soubor dat (dokument respektive tabulka respektive databáze) o jednotlivých povinnostech a jejich plnění v daném úřadu a o krocích pro zlepšení jejich plnění.



V assessmentu se vedou jednotlivé povinnosti a u nich se vedou podrobnosti jednak o povinnosti a jednak o jejím plnění a to v následující struktuře:

![Obecný datový model assessmentu povinností, Zdroj: Metodiky k EG povinnostem and EGdílna](https://github.com/egdilna/metodika.dekompozice-povinnosti/raw/main/mapapovinnosti-diagramy/assessment-povinnosti-datovy-model.png)


* Věc Plnění povinnosti: Údaje o vyhodnocení plnění jedné povinnosti. Obsahují z Mapy povinností údaje o samotné povinnosti, ale především stav plnění a potřebné informace k případné nápravě. 
	* Vlastnost Kód: Jednoznačný identifikátor povinnosti ve složení Kód, skládá se z označení P a čísla kódu povinnosti. Užívá se jako jednoznačný identifikátor z mapy EG povinností. (přebírá se z Mapy povinností)
	* Vlastnost Název povinnosti: Popisný název povinnosti, který se používá jako název v textech. Musí být stručný, ale výstižný, je pochopitelně jednoznačný a jedinečný. (přebírá se z Mapy povinností)
	* Vlastnost Popis povinnosti: Textový popis povinnosti, většinou založený na znění konkrétních ustanovení právních předpisů. (přebírá se z Mapy povinností)
	* Vlastnost Určuje: Konkrétní ustanovení právních předpisů určující danou povinnost. (přebírá se z Mapy povinností)
	* Vlastnost Skupina: Jedna či více skupin povinností podle věcné oblasti. (přebírá se z Mapy povinností)
	* Vlastnost Subjekty: Seznam skupin subjektů, jež mají danou povinnost naplňovat. Obsahuje jednu či více hodnot z číselníku. Vhodné pro třídění a formátování. (přebírá se z Mapy povinností)
	* Vlastnost Předpisy: Seznam právních předpisů, jichž se povinnost týká, respektive, které ji definují. Využije se kupříkladu pro přehledné filtrování či pro vazby v RPP. (přebírá se z Mapy povinností)
	* Vlastnost Verze: Číslo verze záznamu 
	* Vlastnost Stav plnění: Hodnota samotného vyhodnocení, jak si daný úřad určitou povinnost plní. Je jednou z hodnot závazného číselníku, znamená obecné vyhodnocení. Podle ní se dá filtrovat a dále třídit a je ukazatelem fit celého assessmentu. 
	* Vlastnost Zodpovědný: Uvedení jednoho konkrétního útvaru, který v úřadu zodpovídá za dohled a koordinaci k dané povinnosti. Nejedná se tedy o samotný útvar, který povinnost fakticky plní (ne vždy), ale o útvar, který má zajistit její plnění všude, kde je to nutné, napříč celým úřadem. Nejvhodnější je uvést útvar zodpovědný za realizaci dané schopnosti. 
	* Vlastnost Priorita nápravy: Určení interní priority k potřebě řešení nápravy stavu plnění povinnosti a k realizaci příslušných opatření. (Pochopitelně úřad musí plnit všechny povinnosti a tedy jsou si rovny, nicméně v praxi je prioritnější náprava plnění kupříkladu povinností vůči klientům a jejich právu, apod. Doporučuje se určit si priority 1 až 3 kdy 1 je nutná realizace ihned.)
	* Vlastnost Termín nápravy: Očekávaný či požadovaný termín nápravy, jde tedy také o nejzasší termín skončení realizace nápravných kroků. 
	* Vlastnost Popis nápravy: Textový popis toho, co se musí stát, aby se povinnost plnila zcela a beze zbytku. Slouží také jako základ motivace pro definici cílového stavu ICT a realizace jednotlivých projektů a opatření. 
	* Vlastnost Vyhodnocení nápravy: Textový popis, co se konkrétně změnilo pro nápravu předchozích nevyhovujících stavů. 
	* Vlastnost Aktualizace záznamu: Datum poslední aktualizace vyhodnocení, většinou se kryje s datumem vydání assessmentu, ale může být pochopitelně i průběžně s jednotlivými změnami. 



## 🖋Celkový přehled

Na následujícím přehledovém diagramu je vše pěkně pohromadě. Diagram může na první pohled být složitý, nicméně postupně si v dalších kapitolách vše podrobně projdeme.

[big picture Assessment povinností procesy](https://github.com/egdilna/metodika.dekompozice-povinnosti/raw/main/mapapovinnosti-diagramy/assessmentpovinnostibigpicture.png)

Stručně řečeno jde o sled činností, z nichž nejdůležitější jsou: Určení Garanta Assessmentu povinností, Koordinovat naplnění Assessmentu povinností, Výběr nástroje a způsobu zpracování Assessmentu, Výběr relevantních povinností, Určení zodpovědného útvaru, Vyhodnocení plnění povinnosti, Přijmout technicko-organizační opatření pro splnění kroků narovnání povinností a Promítnutí nápravných kroků do Informační koncepce úřadu

## ☑️ Důležité role - garant a zodpovědný a některé další

Nejdůležitější role v procesech okolo zhodnocení stavu plnění povinností jsou vesměs tři a to následující:

1. Vedení úřadu: Vedením úřadu myslíme kolektivní orgán, třeba poradu vedení, nebo poradu ředitele. Jde o orgán, který fakticky rozhoduje o řízení úřadu a především stanovuje jednotlivým vedoucím pracovníkům úkoly a vyhodnocuje jejich plnění. ()
1. Garant Assessmentu povinností: Garant assessmentu povinností (garant) je Role v úřadu, do které je určena konkrétní fyzická osoba. Koordinuje sestavení, vyplnění a aktualizování Assessmentu povinností a zprostředkovává a koordinuje spolupráci a komunikaci mezi jednotlivými zodpovědnými útvary. Tento garant také zodpovídá za zpracování assessmentu a udržuje si přehled o potřebných krocích v rámci architektury i v rámci realizace nápravných opatření . ()
1. Zodpovědný útvar: Zodpovědný za plnění povinnosti (zodpovědný) je Určená role v úřadu, většinou shodná s rolí věcného gestora za danou oblast. Pro potřeby zpracovávání Assessmentu povinností jde o tvar, nebo dokonce konkrétní zaměstnanec, který napříč celou organizací koordinuje a kontroluje dodržování dané povinnosti napříč všemi agendami a činnostmi a zodpovídá tak za její plnění. Také je odborně zodpovědný za správné vyhodnocení plnění a za nápravné kroky. ()


Jako každá aktivita ohledně řízení úřadu jde o věc průřezovou a proto níže uvádíme i další zainteresované, kteří mohou svými znalostmi přispět k co nejkvalitnéjšímu výstupu:

* Věcný gestor: Útvar v organizaci, který zcela zodpovídá za danou určitou oblast, agendu nebo schopnost. ()
* Útvar architektury úřadu: Útvar vytvářející a spravující architekturu úřadu, který ji řídí a sleduje a vyhodnocuje její realizaci. ()
* Útvar zodpovědný za Compliance s legislativou: Útvar v úřadu, který zodpovídá za sledování legislativních změn a za soulad činností s legislativou a realizuje související metody řízení a zásady z IKČR. Pokud není Garant určen z oblasti architektury, je zaměstnanec tohoto útvaru vhodným Garantem Assessmentu, neboť samotný Assessment je významným zdrojem poznání o souladu s předpisy. ()
* Zodpovědný útvar za tvorbu a uplatňování a vyhodnocování Informační koncepce úřadu: Útvar v úřadu, který je zodpovědný za tvorbu, vyhodnocování a zpracovávání aktualizací Informační koncepce úřadu a za soulad s IKČR. ()
* Útvar řízení kvality úřadu: Určený útvar či pracovník, který má v úřadu ve své gesci řízení a vyhodnocování kvality. ()
* Manažer kvality v úřadu: Role Manažera kvality obsazená na základě povinnosti sledovat a vyhodnocovat kvalitu v úřadu. Pro oblast zhodnocení plnění povinností a Assessmentu je důležitý, neboť pro něj Assessment znamená jeden ze základních vstupů stran poznání skutečné kvality služeb úřadu a také kvality v oblasti Compliance. ()"

Na obrázku níže je přehled co která role obecně dělá, respektive za co je zodpovědná.

[Přehled za co kdo zodpovídá](https://github.com/egdilna/metodika.dekompozice-povinnosti/raw/main/mapapovinnosti-diagramy/assessmentpovinnostikdoco.png)

## Fáze přípravy

To první, co se musí udělat, je celý proces tvorby nastartovat. Zde je rozhodující vedení úřadu, které musí učinit dva zásadní kroky:

* Rozhodnutí o vytvoření prvního Assessmentu povinností: Celá věc formálně začíná nějakým rozhodnutím o tom, že se Assessment vytvoří. Toto rozhodnutí by mělo učinit vedení, nebo ten, kdo zodpovídá za IK a celou věc pak koordinuje - jmenovaný garant. V případě projektového řízení ICT by se mělo jednat o interní projekt a rozhodnutí by mělo být formulováno jako úkol, jež koordinuje garant. (Důležité opravdu je, aby to vedení vzalo za své a nepovažovalo to za nutné zlo. Kde je architektonický board, měl by nad tím mít nějaký vrcholový pohled i board.)
* Určení Garanta Assessmentu povinností: Vedení určí/jmenuje Garanta Assessmentu povinností. Rovněž definuje jeho pravomoci a povinnosti. Garant Assessmentu povinností je osoba, která po celou dobu řídí (koordinuje, kontroluje) zpracování procesu Assessmentu EG povinností.  (Vhodným Garantem Assessmentu je specialista na legislativní Compliance. A pokud není, tak nejblíže k takové míře komplexnosti má architekt.)

Dále celé vytváření assessmentu řídí právě Garant. Před samotným zhodnocováním a vyplňováním čehokoliv, musíme mít, kam to vyplnit. Proto je důležité pečlivě připravit příslušné podklady.

* Činnost Příprava seznamu povinností pro zhodnocení: Jde o soubor činností, a to od vyhledání relevantních povinností v Mapě EG povinností, jejich výběr, až po přenesení v požadované struktuře do nástroje pro Assessment povinností. Výstupem je ucelený a snadno zpracovatelný přehled povinností sloužící k zhodnocení jejich naplňování. ()
	* Výběr nástroje a způsobu zpracování Assessmentu: Výběr vhodného nástroje a způsobu zpracování dat z Mapy EG povinností je na uvážení úřadu, resp. Garanta Assessmentu povinností. Vhodným nástrojem pro snadné a efektivní vyhodnocení plnění jednotlivých povinností může být běžný tabulkový procesor, např. MS Excel nebo Google Sheets. V nástroji budou zpracovávána data ve struktuře vyplývající z datového modelu pro Assessment povinností. (Jednou z alternativ je využít předpřipravený Template Assessmentu, který najdete na webových stránkách Mapy EG povinností na https://egdilna.cz/mapapovinnosti)
	*Vytvořit v nástroji podklad pro Assessment a přidat povinná pole: Ve vybraném nástroji je sestavena tabulka se sloupci či adekvátní datová struktura, a to podle datového modelu pro Assessment povinností. V takto vytvořeném nástroji si úřad povede informace o všech povinnostech a o stavu jejich plnění. (Jde zejména o sloupce Zodpovědný, Stav plnění a další, jak ukazuje datový model Assessmentu. Ten lze jako CDS šablonu najít na webových stránkách Mapy EG povinností. Pro usnadnění existuje i předpřipravený XLSX a ODS soubor s vytvořenými sloupci jako Template Assessmentu.)
	* Výběr relevantních povinností: Nejprve musíme vědět, které povinnosti se nás týkají, protože pro každou z nich budeme zpracovávat jejich vyhodnocení. Jde tedy o výběr relevantních povinností ze seznamu všech evidovaných povinností. (Zdrojem výběru je Mapa EG povinností a její filtrační funkce. Nutnou znalostí je dobře vědět, ve kterých rolích z Číselníku subjektů povinností se úřad nachází.)
		* Identifikace rolí podle Subjektů v Mapě EG povinností: Garant Assessmentu povinností sestaví přehled všech rolí, ve kterých se konkrétní úřad nachází a který bude přímo použitelný pro filtrování v Mapě EG povinností ve sloupci Subjekt. Použije přitom seznam rolí zakreslený v rámci architektury úřadu. Důležitý je nejen seznam rolí, ale především i seznam souvisejících hodnot v číselníku druhů subjektů a těmto hodnotám a jejich významu musí rozumět. ()
		* Vyfiltrování mých povinností podle Subjektů: V Mapě EG povinností jsou pomocí funkce filtr ve sloupci subjekty kumulovaně vyznačeny všechny role, ve kterých se příslušný úřad nachází, respektive, které byly identifikovány Garantem Assessmentu povinností. Po aktivaci filtru jsou zobrazeny povinnosti vztahující se k předmětnému úřadu. Těmto povinnostem říkáme relevantní, protože u ostatních platí, že jsou dle stavu nerelevantní. I nerelevantní povinnosti si úřad může v Assessmentu z nějakého důvodu vést, ale nejsou rozhodné pro zhodnocení. ()
		* Export či přenos relevantních povinností do nástroje či tabulky Assessmentu: Relevantní povinnosti vyfiltrované v Mapě EG povinností jsou přeneseny do připraveného nástroje k vyhodnocení jejich plnění. To se provede buď exportem datové sady a importem do tabulky či nástrojem pro Assessment, nebo s využitím rozhraní pro získání otevřených dat v Mapě EG povinností. (V určitých případech si úřad může chtít evidovat i pro něj nerelevantní povinnosti, pokud je třeba na nich závislý, proto si takové povinnosti může importovat, ale se stavem Není relevantní.)



## Fáze tvorby

Vytvoření Assessmentu povinností: Hlavním procesem je tvorba a zpracování samotného Assessmentu povinností jako zdroje dat o stavu plnění povinností a o nápravách identifikovaných nedostatků. Assessment se pak může užívat i k dalším věcem, je třeba vhodný pro řízení kvality apod. Vytvořením Assessmentu to tedy nekončí, ale bez něj se nedá obejít. ()

Určení zodpovědného útvaru: Pro každou povinnost je nutné určit zodpovědný útvar. Tím je útvar, který má ve své gesci koordinaci a dohled nad danou oblastí, nebo činnostmi, které povinnost zajistí. V případě neurčení útvaru se musí určit útvar či člen vedení vyšší úrovně, tedy kupříkladu náměstek. U některých příliš průřezových povinností lze jako zodpovědný útvar určit kupříkladu útvar architektury. (Určuje se pro každou povinnost. Vhodným zodpovědným útvarem je věcný gestor. Pochopitelně příbuzné a související povinnosti mají jednoho zodpovědného. Pokud v úřadu existuje Capability mapa či doménové rozdělení, je to dobrý základ pro určení zodpovědných.)

Ve spolupráci s garantem pak zodpovědný útvar pro každou povinnosti zhodnotí a vyplní potřebné informace:


* Vyhodnocení plnění povinnosti: Pro každou jednotlivou povinnost musí být zpracováno její vyhodnocení, tedy zda a jak se daná povinnost plní a co je případně nutné učinit, aby byla plněna. ()
	* Určit stávající skutečný stav naplnění povinnosti v celém úřadu: Hlavní věcí celého Assessmentu je skutečné uvedení stavu věcí. U každé povinnosti má zodpovědný útvar být schopen pravdivě a úplně zhodnotit, zda se taková povinnost v úřadu naplňuje, zda se naplňuje dostatečně a ve všech případech. Podle toho se pak tedy vyplní plnění povinnosti do Assessmentu. Zodpovědný útvar takovou znalost má, neboť je zodpovědný za oblast či činnost, která s povinností souvisí. Při nejistotě v míře a úplnosti naplnění je vhodné se podcenit, a pak být případně příjemně překvapen. Důležité je uvádět pravdu a uvědomit si, co musím udělat, abych to případně zlepšil. ()
	* Vyplnit hodnotu pro Stav plnění povinnosti dle číselníku stavů: K povinnosti se v daném řádku vyplní hodnota Stav, která je jednou z hodnot závazného číselníku. Tedy buď Plní zcela, Plní částečně nebo Dosud neplní. Pro nerelevantní povinnosti, které si z nějakého důvodu chceme evidovat ve svém přehledu, lze využít hodnotu Není relevantní. Hodnotu vyplníme dle určení skutečného stavu. V žádném případě nelžeme, tedy pokud si stoprocentně nejsme jisti a nemáme prokazatelné, že povinnost plním vždy, kdy se má, raději zapíšeme Plní částečně. Jde o skutečné přiznání. Tyto hodnoty se pak použijí pro souhrnné statistiky a také pro filtrování toho, co musíme řešit. ()
	* Stanovení základních kroků pro nápravu plnění: Součástí uvedení plnění povinnosti je sepsání alespoň základního popisu kroků, které se musí učinit v úřadu, aby se povinnost plnila zcela a ve všech případech. Jde jak o kroky organizační a procesní (včetně kontroly), tak ale i o kroky technické (úpravy systémů, vylepšení integrace apod.). Tyto kroky pak slouží jako základ pro záměry a opatření v IK pro zlepšení stavu. ()
	* Stanovení priority pro nápravu: Je pochopitelně nutné si plnit veškeré povinnosti, a to ve snaze o narovnání nedostatků vyplývajících z Assessmentu povinností. Je však nezbytné nastavit správně priority podle závažnosti důsledků z neplnění některých povinností. Největší důraz je kladen na povinnosti směřující ke klientům veřejné správy. Po provedení zhodnocení si tedy úřad rozdělí neplněné povinnnosti do skupin podle priorit. A ty proklientské a jinak závažné řeší přednostně. ()


## Fáze projednání a využití poznatků


Po řádném zpracování u všech povinností nastane událost Podklady v Assessmentu povinností jsou kompletní: Zodpovědní, a to ve spolupráci s Garantem Assessmentu povinností, doplnili u všech relevantních povinností stav plnění a další podrobnosti, a tím je daná aktualizace Assessmentu povinností hotová a připravena k projednání vedením. (Cílem je mít správně vyplněné plnění u všech povinností. Ale pokud u několika z nich v danou chvíli nejsme schopni určit třeba správně nápravné kroky či prioritu, můžeme i tak projednat a schválit Assessment s tím, že při jeho aktualizaci tyto nedostatky opravíme. Jde totiž o to se uměle nezdržovat, ale naopak, co nejrychleji z Assessmentu získat potřebné znalosti pro změny.)

Máme tedy zpracovaný podklad jako assessment, co teď?

* Projednání Assessmentu povinností: Po faktickém vytvoření Assessmentu je třeba zjištěné závěry projednat na úrovni vedení a také se zainteresovanými útvary. Půjde přitom především o pochopení nedostatků a o stanovení prioritizace jejich řešení. ()
	1. Schválení verze Assessmentu povinností: Vedení úřadu po projednání by mělo (kupříkladu v rámci schvalování) schválit také aktuální verzi Assessmentu povinností platnou jako zdroj poznání a základ pro potřebné kroky nápravy. Ty se také promítají do IK. ()
	1. Zařazení Assessmentu povinností k Informační koncepci úřadu: Závěry Assessmentu či dokonce celý Assessment je součástí IK třeba jako příloha. Jde o jeden ze čtyř základních zdrojů poznání skutečného stavu v úřadu a zdroj pro záměry sloužící k nápravě. To se pochopitelně týká i aktualizací IK a ročních aktualizací Assessmentu. ()
	1. Přijmout technicko-organizační opatření pro splnění kroků narovnání povinností: Vedení úřadu přijme soubor technicko-organizačních opatření vedoucích k celkovému legislativnímu souladu úřadu. Opatření budou vycházet z výsledků Assessmentu povinností a budou směřovat k narovnání stavu. Při navrhování a zavádění těchto opatření je nezbytné zohlednit priority a závažné nedostatky zejména u služeb směřujících ke klientům. (Toto je důležité. Není účelem si jen sepsat, co nás pálí, ale především si správně a pravdivě říci, co s tím budeme dělat.)
	1. Promítnutí nápravných kroků do Informační koncepce úřadu: Jedním z důvodů, pro který Assessment zpracováváme, je poznat skutečný stav naplňování jednotlivých povinností a především stanovit kroky, díky kterým napravíme plnění povinností tam, kde je neplníme zcela. Tyto nápravné kroky se musí promítnout ve formě záměru a opatření do Informační koncepce úřadu, a to zejména, pokud se týkají informačních systémů a ICT prostředků. Assessment nám slouží jako zdroj, ze kterého je jasné, co se má stát. Slouží tedy jako zdroj potřeb pro informační koncepci. Způsob promítnutí kroků do informační koncepce si dohodne garant se zodpovědným za IK. ()


# Tvorba Roční aktualizace Assessmentu povinností


# KEKOREKTUŘE Vyhodnocení stavu plnění povinnosti a kroky k nápravě

Nejdůležitější částí assessmentu je právě zhodnocení u jednotlivých povinností, proto se celý assessment dělá. Ať už bude samotné zhodnocení veřejnou částí informační koncepce, či nikoliv, je nezbytné, abychom byly při vyhodnocování opravdu upřímní a pravdiví. Stavy vyhodnocení nám má sloužit pro lepší poznání a hlavně jako zdroj pro potřebné změny. Může se jednat o změny procesní, legislativní, technické či architektonické.

## KEKOREKTUŘE Obecný postup při zhodnocení plnění povinnosti

1. Určíme si, které povinnosti jsou pro nás relevantní a které nnikoliv.
2. Určíme útvar (a pokud možno konkrétní osobu) zodpovědnou za plnění povinnosti napříč celou organizací.
3. Pravdivě zhodnotíme, jak moc danou povinnost plníme a to zapíšeme s podrobnostmi do assessmentu.
4. Musíme znát, jaké prostředky (zejména informační systémy a jejich integrace) k plnění povinnosti využíváme a v jakém jsou stavu.
5. Sepíšeme si, co se musí obecně stát, abychom povinnost řádně plnili a to zcela a vždy.

## KEKOREKTUŘE Jak určit zodpovědného za povinnost

Zcela klíčové je u každé povinnosti určit zodpovědný útvar. To je útvar, který má ve své gesci koordinaci či kontrolu dodržování povinnosti napříč celým úřadem. Kupříkladu u povinností týkajících se dokumentů je samozřejmě takovým útvarem ten, kdo zodpovídá za výkon spisové služby a její kontrolu v celém úřadu. U zodpovědného tedy nejde o útvary, které povinnost fyzicky vykonávají (v případě spisové služby defacto všichni), ale o toho, kdo zodpovídá skutečně za to, že se povinnost plní vždy a všude a v souladu s tím, co taková povinnost znamená.

👉 Příklad: Povinnosti ke spisové službě, ale třeba i povinnost Odesílat dokumenty do datové schránky (stanovená zákonem 300/2008) mají jako zodpovědný útvar právě útvar spisové služby. Zatímco u spisovky je to celkem jasné, týká se to ale také i odesílání dokumentů a práce s datovou schránkou, neboť jde o součást komplexní schopnosti správy a zacházení s dokumenty. 

Při určování odpovědných útvarů můžeme vycházet ze zpracovaného organizačního řádu, resp. z náplní jednotlivých útvarů v . Tím si mimochodem ověříme, jak dobrý máme vlastní organizační řád úřadu.

💡 TIP: I v Mapě povinností jsou jednotlivé povinnosti seskupeny do skupin podle jejich významu. Oproti tomu v úřadu jsou zastoupeny jednotlivé oblasti či domény svými řídícími útvary. Je dobrý nápad si povinnosti seskupit do celků, které pak mají jeden zodpovědný útvar (jako je to výše u povinností ke spisové službě a dokumentům). Platí, že čím méně zodpovědných útvarů bude, tím lépe se s nimi bude garantovi komunikovat.

V praxi se garant bude nejspíš setkávat s odmítáním zodpovědnosti za danou povinnost, a to zejména tam, kde nějaký útvar zodpovídá za celou skupinu povinností či oblast. To ovšem rozhodně nesmí znamenat, že některá povinnost nebude mít svůj zodpovědný útvar. V nejhorším případě je nutno celou věc řešit s příslušným nadřízeným útvarem a zodpovědnému útvaru tuto zodpovědnost prostě přikázat. To, že nějaký útvar Je zodpovědný za plnění povinnosti, v žádném případě neznamená nějakou pro něj novou práci anebo dokonce novou náplň v rámci jeho činnosti. Vyplývá to totiž vždy z existujících pravomocí a povinností daného útvaru. Také funkce zodpovědného útvaru rozhodně nemůže znamenat požadavek na navýšení personálních kapacit a i při komunikaci s garantem a zhodnocování povinnosti jde o klasický výkon práce v rámci dané pracovní náplně. Při komunikaci uvnitř úřadu je nutné také zdůraznit, že zodpovědný útvar nejen že vyplňuje aktuální stav plnění povinnosti, ale také navrhuje nápravné kroky a zodpovídá za související opatření, jejichž cílem je zlepšit plnění příslušné povinnosti. Pouhým uvedením stavu povinnosti do Assessmentu to pro zodpovědný útvar v žádném případě nekončí, ba naopak, jedná se o začátek širšího procesu nápravy protizákonného stavu.

💡 TIP: Existují i tak rozsáhlé a obecné povinnosti (jako je sdílení údajů mezi agendovými systémy), pro které se napříč úřadem bude obtížně hledat jeden zodpovědný útvar. Nesmí se ale určit více útvarů. V takovém případě je ideálním zodpovědným útvarem architektura, neboť má díky rozsahu svých znalostí ke koordinaci a sledování napříč úřadem asi nejblíže.


## ✏️ Jak reálně zhodnotit skutečný stav dané povinnosti

✏️ popsat co a jak

✏️ detailně vysvětlit hodnoty stavu a jejich význam

