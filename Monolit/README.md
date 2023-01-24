# Dokumentace architektury - Monolit

## Dokumentace / Struktura adresáře

- **ADR**: komentář
- **pohledy**: komentář
    - [**Pohled na komponenty**](./pohledy/komponenty): komentář
    - [**Pohled na umístění**](./pohledy/umístění): komentář
    - [**Pohled na moduly**](./pohledy/moduly): komentář
- **vyhodnocení**: komentář
- **assets**: komentář



## Funkcionality

Funkcionlity systému jsou popsány níže jako případy užití:

- UC1: Registrace <Nepřihlášený uživatel>
- UC2: Login <Nepřihlášený uživatel>
- UC3: Logout <Přihlášený uživatel>
- UC4: Prohlížení dostupných kurzů <Přihlášený uživatel>
- UC5: Prohlížení detailu kurzu <Přihlášený uživatel>
- UC6: Přidání kurzu do košíku <Přihlášený uživatel>
- UC7: Objednání kurzu z košíku <Přihlášený uživatel>
- UC8: Provedení platby objednávky <Přihlášený uživatel>
- UC9: Platba platební kartou <Přihlášený uživatel>
- UC10: Platba bankovním převodem <Přihlášený uživatel>
- UC11: Platba hotovostí <Přihlášený uživatel>
- UC12: Zobrazení platební historie <Přihlášený uživatel>
- UC13: Zobrazení registrovaných kurzů <Přihlášený uživatel>
- UC14: Vyžádání faktury/daňového dokladu <Přihlášený uživatel>
- UC15: Přidání kurzu <Administrator>
- UC16: Úprava kurzu <Administrator>
- UC17: Smazání kurzu <Administrator>
- UC18: Zobrazení přehledu kurzů a plateb <Administrator>
- UC19: Aktualizace záznamu v centrálním registru <Systém> & <Administrator>
- UC20: Smazání záznamu v centrálním registru <Systém> & <Administrator>
- UC21: Vytvoření záznamu v centrálním registru <Systém> & <Administrator>
- UC22: Filtrování kurzů <Přihlášený uživatel> - Umožňuje přihlášenému uživateli vyhledávat kurzy podle různých kritérií, jako je název kurzu, předmět nebo instruktor.
- UC23: Přidání kurzu do košíku pro specifického uživatele <Přihlášený uživatel> - Umožňuje přihlášenému uživateli přidat kurz se specifickým uživatelem (jiným než je on sám)
- UC24: Zrušit registraci kurzu <Přihlášený uživatel> - Umožňuje přihlášenému uživateli zrušit registraci kurzu a získat zpět peníze (pokud je to možné).
- UC25: Zobrazit informace o instruktorovi <Přihlášený uživatel> - Umožňuje přihlášenému uživateli zobrazit informace o instruktorech kurzu, včetně jejich kvalifikace a zkušeností.
- UC26: Zapsat se na čekací listinu <Přihlášený uživatel> - Umožňuje přihlášenému uživateli zapsat se na čekací listinu kurzu, který je v současné době plný.
- UC27: Upozornit studenty na čekací listině <Systém> - Umožňuje systému automaticky upozornit studenty na čekací listině, když se uvolní místo v kurzu, na který jsou na čekací listině.
- UC28: Odeslat e-mail s potvrzením o platbě <Systém> - Umožňuje systému automaticky odeslat uživateli e-mail s potvrzením o platbě po úspěšné platbě.
- UC29: Správa uživatelských účtů <Administrator> - Umožňuje správci přidávat, upravovat nebo odstraňovat uživatelské účty.
- UC30: Generovat přehledy <Administrator> - Umožňuje správci generovat přehledy o údajích o registraci a platbách za kurzy.

Diagram případu užití:

![use-case](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/6f188c57ca5e7a84bcbd6ea0310543fdd197a59b/SOA/assets/diagram-use-case.png "Diagram případů užití")
