# Pohled umístění
Tento pohled mapuje softwarové prvky na hardware pomocí diagramu nasazení.

---

## Primary presentation
### UML
![Diagram nasazení](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/Monolit/assets/diagram-nasazen%C3%AD-monolit.png "Diagram nasazení")

### Vysvětlivka diagramu
- **Node** - Jedná se o hardwarový (device node) nebo softwarový prvek (execution environment node), který spouští jednu nebo více komponent nebo spustitelných souborů.

![Node](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/Monolit/assets/prvky-diagram%C5%AF/Node.png "Označení Node")

- **Artifact** - Jedná se o konkrétní prvky, které vznikly procesem softwarového vývoje.

![Artifact](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/Monolit/assets/prvky-diagram%C5%AF/Artifact.png "Označení Artifactu")

- **Database** - Databáze jsou součástí Systému řízení báze dat a představují jakákoli data uložená nasazeným systémem.

![Database](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/1f893ee628bccc2657125208a845d7b6f3ee9685/Monolit/assets/prvky-diagram%C5%AF/Database.png "Označení Database")

---

## Element catalog
- **Počítač uživatele**
    - Představuje zařízení studenta, zástupce školy, administrátora nebo účetního, přes které bude přistupovat na webový server. Zařízení plní roli tenkého klienta.
- **Webový prohlížeč**
    - Jedná se o softwarový produkt nainstalovaný na Počítači uživatele, přes které je přistupováno do systému pomocí protokolu HTTPS.
- **HTML 5**
    - Je verze značkovacího jazyka sloužícího k vytváření a zobrazování webových stránek přes Webový prohlížeč.
- **Webový server**
    - Fyzické zařízení, na kterém je nastaven Apache a MySQL a jsou v něm uloženy veškeré potřebné části pro správný chod systému registrací a plateb.
- **Apache**
    - Softwarový webový server s podporou pro všechny operační systémy.
- **index.php**
    - Úvodní stránka systému registrací a plateb napsaná v jazyce PHP.
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

---

## Rationale

---

## Related Views
- [Pohled modulů](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/19bf0bf2c46f8c45aad208bd9a626ee965222b09/Monolit/pohledy/moduly/README.md "Přejít na pohled modulů")

- [Pohled komponent](https://github.com/michaelslavev/4IT575-seminarni-prace/blob/19bf0bf2c46f8c45aad208bd9a626ee965222b09/Monolit/pohledy/komponenty/README.md "Přejít na pohled komponent")
