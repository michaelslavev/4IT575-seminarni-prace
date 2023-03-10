# Zadání seminární práce z předmětu 4IT575 – Softwarové Architektury
Repozitář s dokumenty, které se týkají seminární práce v rámci předmětu 4IT575 - Softwarové architektury

Členové týmu: Daniel Davidík, Michael Slavev, Petr Müller, Jan Novák.


## Úkol:
1.	Na základě níže popsaných požadavků navrhněte dvě architektury vhodné pro implementaci dané aplikace.
2.	Navržené architektury zdokumentujte.
3.	V závěru zhodnoťte, která z vybraných architektur je výhodnější a proč.

Poznámka:
Pokud ze zadání přímo nevyplyne nějaká skutečnost, kterou potřebujete znát, domluvte se ve skupině, a sami ji dodefinujte, tak jako byste se na ni doptali zákazníka.

## Popis aplikace:
Místní vyšší odborná škola nyní kromě obvyklých kurzů pro absolventy a studenty nabízí i jedinečné kurzy pro širokou veřejnost a potřebuje systém registrace a plateb.

**Uživatelé:** studenti, zástupci školy, administrátor a účetnictví.

**Požadavky:**
- Stávající centrální registr studentů/tříd je neintegrovatelný – poskytuje pouze přístup přes webový formulář protokolem https.
- Přijímání plateb
- Sledování registrací
- Studenti jsou zařazeni do centrálního registru, pokud jejich platba proběhne úspěšně.
- Aktualizace/mazaní v centrálním registru se mohou dělat ručně, ale preferován je automatický proces.
- Platby lze provádět platební kartou, bankovním převodem, nebo v hotovosti.
- Předpoklady pro absolvování kurzu
- Studenti si mohou vyžádat fakturu/daňový doklad (který by měl být zaslán e-mailem)
- Jedním nákupem je možné zaregistrovat najednou několik studentů do několika kurzů.
- Administrátoři musí vidět seznamy kurzů, platby, ale ne osobní údaje studentů.
- Další souvislosti:
    - Velmi malý rozpočet na IT.
    - "Jak se registrovat a zaplatit?" byl po mnoho měsíců opomíjeným požadavkem.
    - Za 6 měsíců je nezbytně nutné, aby byla hotová registrace kurzů.

## Rozhodnutí o architektuře

- Monolit [ADR o zvolené architektuře](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/e33f98656b54a1713476a8afdddcdf8f25bde353/Monolit/ADR/01%20%20-%20%20ADR%20o%20zvolen%C3%A9%20architektu%C5%99e.md)
- SOA [ADR o zvolené architektuře](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/e33f98656b54a1713476a8afdddcdf8f25bde353/SOA/ADR/01%20%20-%20ADR%20o%20zvolen%C3%A9%20architektu%C5%99e.md)

## [Závěrečné vyhodnocení architektur](./vyhodnocení.md)
