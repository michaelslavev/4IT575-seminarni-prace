# Pohled moduly
Tento pohled vyobrazuje jednotlivé moduly systému.

---

## Primary presentation
### UML
![Diagram modulů](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/main/SOA/assets/moduly-soa.png "Diagram modulů")

### Vysvětlivka diagramu
- **Package** - Package reprezentuje modul systému.

![Package](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/main/SOA/assets/prvky-diagram%C5%AF/package.png "Označení Package")

- **Directory** - Directory reprezentuje adresář plnící dílčí funkcionalitu v rámci package.

![Artifact](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/main/SOA/assets/prvky-diagram%C5%AF/directory.png "Označení Artifactu")

---

## Element catalog
- **Back-end aplikace**
    - Balíček zastřešující komponenty plnící logickou vrstvu aplikace

-   *REST API*
    - Interface pro výměnu dat s Front-end aplikací

- *Správa kurzů*
    - Komponenta plnící funkcionalitu správy kurzů

- *Platby*
    - Komponenta plnící funkcionalitu plateb

- *Fakturace*
    - Komponenta plnící funkcionalitu fakturací

- *Správa uživatelů*
    - Komponenta plnící funkcionalitu správy uživatelů

- *Administrace*
    - Komponenta plnící funkcionalitu administrace

- **Front-end aplikace**
    - Balíček zastřešující komponenty plnící prezentační funkcionalitu aplikace

-   *commons*
    - adresář obsahující sdílené assety (css, js)

- *Routes*
    - Adresář obsahující jednotlivé cesty (stránky webové aplikace)

- *Features*
    - Adresář obsahující sdílené komponenty napříč routes

- **DB**
    - Balíček reprezentující databázi

- *Tabulky*
    - Adresář obsahující databázové tabulky

- *Indexy*
    - Adresář obsahující databázové indexy

- *Catalog*
    - Adresář obsahující jiné databázové prvky jako jsou metadata

- **Testy**
    - Package zastřešující testovací komponenty

- *Unit testy*
    - Adresaář obsahující jednotkové testy

- *API testy*
    - Adresaář obsahující testy funkcionality API

---
## Context diagram
N/A

---
## Variability guide
N/A

---

## Rationale
N/A

---

## Related Views
[Pohled umístění](../umístění/README.md "Pohled umístění")

[Pohled modulů](../komponent/README.md "Pohled modulů")

[< Zpět](../../ "Zpět do adresáře SOA")
