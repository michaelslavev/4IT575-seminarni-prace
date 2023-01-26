# Hodnocení zvolených architektur

## Metodika
Pro hodnocení charakteristik zvolených architektur bude využitá stupnice (zobrazena níže), přičemž bude pro hodnocení využito bodové hodnocení.

<div id="stupnice">

| Bodové ohodnocení  |
|--------------------|
| 5 - nejlepší                  |
| 4                  |
| 3                  |
| 2                  |
| 1 - nejhorší                  |

</div>

## Hodnocení

<div id="hodnoceni">
  
| **Charakteristika** | **SOA** | **Monolit** |
|---------------------|---------|-------------|
| Dostupnost          | 5       | 2           |
| Kontinuita          | 4       | 2           |
| Recoverability      | 4       | 3           |
| Škálovatelnost      | 4       | 2           |
| Instalovatelnost    | 1       | 5           |
| Lokalizace          | 5       | 5           |
| Autentizace         | 2       | 4           |
| Autorizace          | 2       | 4           |
| Podpora             | 2       | 2           |
| Zpřístupnění        | 5       | 5           |
| Archivovatelnost    | 5       | 5           |
| Zabezpečení         | 3       | 3           |
| Právní              | 5       | 5           |
| **Souhrn**          | **47**  | **47**      |

</div>

## Závěrečné zhodnocení
Z celkového pohledu vypadá, že obě řešení jsou stejně vhodné, není tomu tak, vzhledem k požadavkům na aplikaci jsou preferované požadavky na dostupnost, kontinuitu, škálovatelnost, recoverability, které všechny vítězí u architektury SOA, ale vzhledem k omezením projektu je třeba brát v potaz i náklady na realizaci a čas potřebný
k dokončení.

Vzhledem k vymezením vůči zadání jsme zvolili jako vhodnou architekturu řešení architekturu **monolit**.
