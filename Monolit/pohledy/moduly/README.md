# Pohled moduly
Tento pohled vyobrazuje jednotlivé moduly systému.

---

## Primary presentation
### UML
![Diagram modulů](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/main/Monolit/assets/diagram-modul%C5%AF-monilit.png "Diagram modulů")

### Vysvětlivka diagramu
- **Package** - Package reprezentuje modul systému.

![Package](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/main/Monolit/assets/prvky-diagram%C5%AF/package.png "Označení Package")

- **Directory** - Directory reprezentuje adresář plnící dílčí funkcionalitu v rámci package.

![Artifact](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/main/Monolit/assets/prvky-diagram%C5%AF/directory.png "Označení Artifactu")

---

## Element catalog
- **Server**
    - Balíček zastřešující komponenty plnící hlavní funkcionalitu aplikace

-   *Model*
    - Adresář obsahující vnitřní logiku aplikace

- *View*
    - Adresář obsahující prezentační vrstvu aplikace

- *Controller*
    - Adresář obsahující vrstvu reagující na změny provedené uživatelem


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

[Pohled komponent](../komponenty/README.md "Pohled komponent")

[< Zpět](../../ "Zpět do adresáře Monolit")
