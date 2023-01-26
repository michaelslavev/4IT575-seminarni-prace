# Pohled umístění
Tento pohled mapuje softwarové prvky na hardware pomocí diagramu nasazení.

---

## Primary presentation
### UML
![Diagram nasazení](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/a639e43ee656512c83023e5d2e2e88c45b5c2c3e/SOA/assets/Diagram%20nasazen%C3%AD-SOA.drawio.png "Diagram nasazení")

### Vysvětlivka diagramu
- **Node** - Jedná se o hardwarový (device node) nebo softwarový prvek (execution environment node), který spouští jednu nebo více komponent nebo spustitelných souborů.

![Node](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/SOA/assets/prvky-diagram%C5%AF/Node.png "Označení Node")

- **Artifact** - Jedná se o konkrétní prvky, které vznikly procesem softwarového vývoje.

![Artifact](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/SOA/assets/prvky-diagram%C5%AF/Artifact.png "Označení Artifactu")

- **Database** - Databáze jsou součástí Systému řízení báze dat a představují jakákoli data uložená nasazeným systémem.

![Database](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/SOA/assets/prvky-diagram%C5%AF/Database.png "Označení Database")

---

## Element catalog
- **Počítač uživatele**
    - Představuje zařízení studenta, zástupce školy, administrátora nebo účetního, přes které bude přistupovat na webový server. Zařízení plní roli tenkého klienta.
- **Webový prohlížeč**
    - Jedná se o softwarový produkt nainstalovaný na Počítači uživatele, přes které je přistupováno do systému pomocí protokolu HTTPS.
- **HTML 5**
    - Je verze značkovacího jazyka sloužícího k vytváření a zobrazování webových stránek přes Webový prohlížeč.
- **Webový server**
    -  Fyzické zařízení, na kterém je nastaven Apache a jsou v něm uloženy veškeré potřebné části pro správný chod systému registrací a plateb.
- **Apache**
    - Softwarový webový server s podporou pro všechny operační systémy.
- **Modul správy kurzů**
    - Představuje službu přes kterou jsou spravovány kurzy.
- **Modul plateb**
    - Představuje službu která zajišťuje komunikaci se Serverem platební brány.
- **Modul fakturací**
    - Představuje službu, která generuje a zasílá faktury uživatelům.
- **Modul správy uživatelů**
    - Představuje službu, přes kterou lze spravovat uživatele.
- **Modul administrace**
    - Představuje službu určenou pro veškeré operace administrace.
- **Databázový server**
    - Fyzické zařízení, na kterém je spuštěné MySQL a jsou zde uložena všechna data. Jako komunikační protokol s Webovým serverem využívá ODBC.
- **MySQL**
    - Otevřený systém řízení báze dat určený pro relační databáze.
- **Databáze registrací**
    - Obsahuje veškerá data soiuvisející s registracemi.
- **Server platební brány**
    - Fyzické zařízení, které je na straně poskytovalete platební brány a zprostředkovává platby za registrace.
- **REST API**
    - API, které umožňuje uživateli platit za registrace do kurzů.

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
- [Pohled modulů](../moduly/README.md "Přejít na pohled modulů")

- [Pohled komponent](../komponenty/README.md "Přejít na pohled komponent")

[< Zpět](../../ "Zpět do adresáře SOA")
