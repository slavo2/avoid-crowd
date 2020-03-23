# avoid-crowd
Application to help people avoid crowds in shops etc.

For Czech description see below.

## English - description in English

## Czech - Popis česky

Aplikace má pomoct uživatelům vyhýbat se místem se zvýšenou koncentrací lidí
a tak omezit šíření kapénkové nákazy, jakou je i COVID-19.

Popis fungování aplikace:

### Získávání informací o zvýšeném výskytu lidí (davu) uživatelem

Pro získání informace uživatel nepotřebuje uživatelské konto ani instalaci aplikace.
Na příslušné webové stránce nebo v aplikaci (pokud ji má instalovanou) vyhledá příslušné místo
obchod, provozovnu, službu, ordinaci, úřad atd. na mapě, vyhledáváním podle adresy, textu nebo v seznamu svých oblíbených míst.

Poté se mu zobrazí informace o aktuálním stavu (ve smyslu hustoty lidí / přeplněnosti místa)
na daném místě (pokud jsou k dispozici)
a nabídnou se mu další informace (pokud jsou k dispozici)
- kdy byla informace o stavu naposledy aktualizována
- průměrná čekací doba ve frontách
- statistický přehled o předpokládáném stavu místa v průběhu týden
- otevírací hodiny a speciálně vyhrazené časy pro určité skupiny obyvatelstva (např. důchodce)
- další statické informace o místu
- odkaz na webové stránky místa
- dynamické ohlášení správce místa (například krátká oznámení prodejny určené veřejnosti)
- informace o dostupnosti jednotlivých druhů základního zboží, která můžou být důvodem návštěvy prodejny
(zda mají k dispozici dezinfekci (které druhy), toaletní papír, chléb, mléko, rýži, brambory, atd...)
- komentáře uživatelů

### Poskytování informací 

Pro poskytování informací potřebuje mít uživatel registrováno konto.
Z hlediska poskytování informací k danému místu se uživatelé dělí na 2 kategorie:
- běžný uživatel (například zákazník obchodu)
- oficiální zástupce místa (pověření zaměstnanci prodejny - může jich být více)

Běžní uživatelé do systému vkládají své aktuální (subjektivní) vnímání situace - navštíví dané místo a na (barevné a číselné) škále vyberou, jak moc (vnímají), že je místo plné: 
- 1 - jsem tam sám / 0 - 10% kapacity prodejny
- 2 - je tam jen pár lidí na rozlehlý prostor / 11% - 20% kapacity prodejny
- 3 - jsou tam nějací lidé, ale odstupy lze obvykle velmi dobře dodržovat / 21% - 35% kapacity prodejny
- 5 - je tam lidí "tak normálně" / 36% - 60% kapacity prodejny
- 6 - je tam hodně lidí / 60% - 80% kapacity prodejny
- 7 - je tam opravdu hodně lidí / 81% - 100% kapacity prodejny
- 8 - je tam narváno / Kapacita prodejny byla překročena
- 9 - nedá se tam pohnout / Kapacita prodejny byla značně překročena

případně speciální stav (zavřeno)

dále mohou indikovat, zda je dostupný určitý druh zboží
a přidat svůj komentář
mohou dále jakýkoli komentář označit za nerelevantní nebo chybný
(správci aplikace si vyhrazují právo jakýkoli komentář, o kterém usoudí, 
že není nápomocný k cílům aplikace (pomoct lidem si efektivně nakoupit s omezením šíření nemocí)
vymazat)

Oficiální zástupci místa (po verifikaci) vzhledem k rozsahu svých oprávnění mohou také:
Upravovat oficiální informace, otevírací a vyhrazené hodiny, kapacitu prodejny atd.
a také dynamické informace, jako oznámení prodejny, naplnění kapacity (přibližný počet zákazníků),
dostupnost určitých vybraných typů zboží...

Platnost dynamicky poskytovaných dat od uživatelů by byla časově omezena, postupně by ubývala na váze,
v lepším případě by byla nahrazována aktuálnější zkušeností.

Informace od oficiální zástupců místa by měla vyšší váhu / prioritu.

Dostupné informace by centrální server sbíral a statisticky vyhodnocoval - vytvářel křivku průměrného naplnění místa v různých dobách v týdnu.

