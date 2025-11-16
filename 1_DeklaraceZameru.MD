Deklarace záměru projektu – Informační systém cestovní kanceláře
Cestovní kancelář pořádá autobusové zájezdy, které jsou dnes spravovány pomocí tabulek v Excelu. Tento způsob je neefektivní, chybový a komplikuje správu přihlášek, plateb i komunikaci s účastníky. Cílem projektu je vytvořit jednoduchý webový informační systém, který umožní evidenci zájezdů, přihlašování účastníků, kontrolu plateb a informování klientů. Systém má řešit zejména události přihlášení na zájezd, zaplacení do termínu T_pay, odhlášení a případné zrušení zájezdu ze strany CK. Systém využívají tři role: účastník (registrace a přihlášení), pracovník CK (správa zájezdů a přihlášek) a administrátor (dohled nad systémem).




níže je stará verze, kterou zde uchováme pro případ potřeby
nová je dle sobotní přednášky stručnější

# SI_1. Úkol – Deklarace záměru (3 body)

Deklarace záměru projektu – Informační systém cestovní kanceláře
1.	Cíl a vize projektu
Cílem projektu je vytvořit webovou aplikaci pro správu autobusových zájezdů pořádaných cestovní kanceláří. Systém sjednotí evidenci zájezdů, přihlášky účastníků, platby a komunikaci s klienty, aby se snížila chybovost a administrativní zátěž.
Menší cestovní kanceláře často vedou agendu zájezdů a klientů pomocí tabulek v aplikaci Excel, což je nepřehledné, chybové a přináší riziko ztráty dat. Projekt nabídne centralizované webové řešení, které zajistí přehlednost, bezpečnost a snadnou správu dat.
2.	Kontext a události
Cestovní kancelář pořádá autobusové zájezdy (1 zájezd = 1 autobus). Systém musí pokrýt tyto události:
•	Přihlášení na zájezd – účastník rezervuje místo do termínu T_reg.
•	Zaplacení zájezdu – do termínu T_pay; po uplynutí systém rezervaci zruší.
•	Odhlášení ze zájezdu – účastník se může odhlásit do stanoveného termínu.
•	Zrušení zájezdu – pracovník CK zájezd zruší a systém informuje účastníky e-mailem.
3.	Uživatelské role
•	Občan – neregistrovaný uživatel, který prohlíží nabídku zájezdů (destinace, termín, cena, volná místa).
•	Účastník – registrovaný uživatel, který se přihlašuje nebo odhlašuje na zájezdy, provádí platby a sleduje historii přihlášek.
•	Pracovník CK – vytváří, upravuje a ruší zájezdy, kontroluje platby, rozesílá hromadné zprávy klientům.
•	Administrátor – spravuje systém, uživatele a generuje přehledy o zájezdech.
4.	Hlavní funkce systému
•	Vyhledávání a filtrování zájezdů podle destinace, data nebo ceny.
•	Registrace a přihlášení uživatele.
•	Tvorba, úprava a rušení přihlášek.
•	Evidence plateb a kontrola termínů T_pay.
•	Automatické notifikace e-mailem.
•	Správa uživatelů a přehledy o zájezdech.
5.	Použité technologie
Frontend: HTML5, CSS3, Bootstrap 5
Backend: PHP 8, MySQL
Vývojové prostředí: Visual Studio Code
Správa verzí: GitHub
6.	Tým a matice odpovědností
Jméno	Role	Odpovědnosti
Filip Papai	Vedoucí projektu	koordinace, návrh architektury, dokumentace, komunikace s vyučujícím
Antonín Čala	Backend vývojář	návrh databáze, implementace PHP logiky, testování API
Marek Maněk	Frontend vývojář	návrh uživatelského rozhraní, HTML/CSS, integrace Bootstrap, UX testy
Jiří Chromý	Tester a analytik	testování, analýza požadavků, tvorba UML diagramů
7.	Výstupy projektu
Výstupem projektu bude dokumentace (tým, plán, matice zodpovědností), textová specifikace systému a model vytvořený pomocí CASE nástroje.
8.	Závěr
Tým deklaruje záměr vyvinout Informační systém cestovní kanceláře, který bude realizován jako webová aplikace dle principů softwarového inženýrství. Projekt vzniká v rámci předmětu Softwarové inženýrství (SWI) na Vysoké škole polytechnické Jihlava pod vedením Ing. Karla Richty.


