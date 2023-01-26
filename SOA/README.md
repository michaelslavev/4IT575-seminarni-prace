# Dokumentace architektury - SOA

## Dokumentace / Struktura adresáře

- **ADR**:
    - [**01 - ADR o zvolené architektuře**](./ADR/01%20%20-%20ADR%20o%20zvolen%C3%A9%20architektu%C5%99e.md)
    - [**02 - ADR o platební metodě**](./ADR/02%20%20-%20ADR%20o%20platebn%C3%AD%20metod%C4%9B.md)
    - [**03 - ADR o platební bráně.**](./ADR/03%20-%20ADR%20o%20platebn%C3%AD%20br%C3%A1n%C4%9B.md)
    - [**04 - ADR o frameworku backendu.md**](./ADR/04%20-%20ADR%20o%20frameworku%20backendu.md)
    - [**05 - ADR o frameworku frontendu.md**](./ADR/05%20-%20ADR%20o%20frameworku%20frontendu.md)
- **pohledy**:
    - [**Pohled na komponenty**](./pohledy/komponenty)
    - [**Pohled na umístění**](./pohledy/umístění)
    - [**Pohled na moduly**](./pohledy/moduly)
- [**vyhodnocení**](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/84dd3a15746d35593c41020b64610e0e4ab01141/vyhodnocen%C3%AD.md)
- **assets**: V tomto adresáři jsou soubory dokumentace projektu



## Funkcionality

Funkcionlity systému jsou popsány níže jako případy užití:

- UC1: Registrace <Nepřihlášený uživatel> - Systém umožní nepřihlášenému uživateli registrovat nový účet
- UC2: Login <Nepřihlášený uživatel> - Systém umožní nepřihlášenému uživateli přihlásit se k již vytvořenému účtu
- UC3: Logout <Přihlášený uživatel> - Systém umožní přihlášenému uživateli odhlásit
- UC4: Prohlížení dostupných kurzů <Přihlášený uživatel> - Systém umožní přihlášenému uživateli zobrazit dostupné kurzy
- UC5: Prohlížení detailu kurzu <Přihlášený uživatel> - Systém umožní přihlášenému uživateli zobrazit detaily kurzu
- UC6: Přidání kurzu do košíku <Přihlášený uživatel> - Systém umožní přihlášenému uživateli přidat kurz do košíku
- UC7: Objednání kurzu z košíku <Přihlášený uživatel> - Systém umožní přihlášenému uživateli objednat kurzy přidané v košíku
- UC8: Provedení platby objednávky <Přihlášený uživatel> - Systém umožní přihlášenému uživateli provést platbu objednávky
- UC9: Platba platební kartou <Přihlášený uživatel> - Systém umožní přihlášenému uživateli zvolit platbu kartou
- UC10: Platba bankovním převodem <Přihlášený uživatel> - Systém umožní přihlášenému uživateli zvolit platbu bankovním převodem
- UC11: Platba hotovostí <Přihlášený uživatel> - Systém umožní přihlášenému uživateli zvolit platbu hotovostí
- UC12: Zobrazení platební historie <Přihlášený uživatel> - Systém umožní přihlášenému uživateli zobrazit platební historii provdenou na účtu
- UC13: Zobrazení registrovaných kurzů <Přihlášený uživatel> - Systém umožní přihlášenému uživateli zobrazit jeho registrované kurzy
- UC14: Vyžádání faktury/daňového dokladu <Přihlášený uživatel> - Systém umožní přihlášenému uživateli stažení elektronické faktury/daňového dokladu registrovaných kurzů
- UC15: Přidání kurzu <Administrator> - Systém umožní správci přidání nového kurzu
- UC16: Úprava kurzu <Administrator> - Systém umožní správci upravit detaily kurz
- UC17: Smazání kurzu <Administrator> - Systém umožní správci smazat kurz
- UC18: Zobrazení přehledu kurzů a plateb <Administrator> - Systém umožní správci zobrazit přehled kurzů a provedených plateb
- UC19: Aktualizace záznamu v centrálním registru <Systém> & \<Administrator> - Systém umožní správci aktualizovat záznam v centrálním registru
- UC20: Smazání záznamu v centrálním registru <Systém> & \<Administrator> - Systém umožní správci smazat záznam v centrálním registru
- UC21: Vytvoření záznamu v centrálním registru <Systém> & \<Administrator> - Systém umožní správci vytvořit záznam v centrálním registru
- UC22: Filtrování kurzů <Přihlášený uživatel> - Systém umožní přihlášenému uživateli vyhledávat kurzy podle různých kritérií, jako je název kurzu, předmět nebo instruktor.
- UC23: Přidání kurzu do košíku pro specifického uživatele <Přihlášený uživatel> - Systém umožní přihlášenému uživateli přidat kurz se specifickým uživatelem (jiným než je on sám)
- UC24: Zrušit registraci kurzu <Přihlášený uživatel> - Systém umožní přihlášenému uživateli zrušit registraci kurzu a získat zpět peníze (pokud je to možné).
- UC25: Zobrazit informace o instruktorovi <Přihlášený uživatel> - Systém umožní přihlášenému uživateli zobrazit informace o instruktorech kurzu, včetně jejich kvalifikace a zkušeností.
- UC26: Zapsat se na čekací listinu <Přihlášený uživatel> - Systém umožní přihlášenému uživateli zapsat se na čekací listinu kurzu, který je v současné době plný.
- UC27: Upozornit studenty na čekací listině <Systém> - Systém umožní systému automaticky upozornit studenty na čekací listině, když se uvolní místo v kurzu, na který jsou na čekací listině.
- UC28: Odeslat e-mail s potvrzením o platbě <Systém> - Systém umožní automaticky odeslat uživateli e-mail s potvrzením o platbě po úspěšné platbě.
- UC29: Správa uživatelských účtů <Administrator> - Systém umožní správci přidávat, upravovat nebo odstraňovat uživatelské účty.
- UC30: Generovat přehledy <Administrator> - Systém umožní správci generovat přehledy o údajích o registraci a platbách za kurzy.

Diagram případu užití:

![use-case](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/6f188c57ca5e7a84bcbd6ea0310543fdd197a59b/SOA/assets/diagram-use-case.png "Diagram případů užití")
