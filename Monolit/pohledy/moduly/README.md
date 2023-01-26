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
- [Pohled komponent](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/19bf0bf2c46f8c45aad208bd9a626ee965222b09/Monolit/pohledy/komponenty/README.md "Přejít na pohled komponent")

- [Pohled umístění](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/74ebf29c0f371a21b24e280cb6f087e10a45a93a/Monolit/pohledy/um%C3%ADst%C4%9Bn%C3%AD/README.md "Přejít na pohled modulů")

[< Zpět](../../ "Zpět do adresáře Monolit")
