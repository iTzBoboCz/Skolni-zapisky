# Bezpečnostní politiky

- zásady a předpisy
- fyzická ochrana až po ochranu osobních dat
- zálohování dat (např. před povodněmi)
- příklady
  - větší zabezpečení při přihlašování z externí sítě
  - do serverovny může jen personal

## Ochrana osobních údajů v EU

- šifrování hesel
- zpracovatelé velkého rozsahu (např. i škola) musí mít ověřence
- pokuta za nenahlášení úniku
- v ČR je úřad pro ochranu osobních údajů

## BP vymezuje

- co vyžaduje ochranu
- proti jakým hrozbám budujeme ochranu
- jak budeme ochranu realizovat

## typy bezpečnostní politiky

- celková
  - vymezuje, co se musí zabezpečit
- systémová
  - jak mám zabezpečit
  - doporučení (nejnovější šifry,..)
  - u rozsáhlého IS se vypracovává zvlášť:
    - fyzická systémová bezpečnost
      - ochrana místností, budov,..
    - personální systémová bezpečnost
      - ochrana před zákazníky, hackery, zaměstnanci,..
      - nenechávat si hesla na papírku
    - komunikační systémová bezpečnost
      - ochrana přenosu dat, telefonů, dopisů
      - šifrování
    - provozní systémová bezpečnost
      - školení, jak postupovat při útoku, havárii
      - zálohování dat

## Zajistit
- důvěrnost ochrany soukromých dat
  - řízení přístupu k datům (přístup mají pouze oprávnění uživatelé)
  - šifrování
  - firewall
- integritu
  - změnu může provést jen oprávněný uživatel
  - data drží pohromadě
  - např. vypočítání kontrolního součtu přílohy emailu 
  - kryptografické kontrolní součty
- autentičnost
  - musí být jasné, s kým komunikujeme
  - hesla, el. podpisy
- nepopiratelnost
  - nikdo nemůže popřít, co někdo udělal při používání např. el. podpisu (např. transakci)
  - loguji každou akci
- dostupnost
  - umožnění oprávněným uživatelům přistupovat k datům
- spolehlivost
  - služba by neměla padat
  - uptime

## Úrovně:
- promiskuitní
  - minimální nebo vůbec žádná bezpečnost
  - osoba mi řekne, abych něco nedělal
  - nízké náklady
- liberální
  - každý může dělat vše až na explicitně zakázené
  - princip blacklistu
  - stále nízké náklady
- opatrná (racionální)
  - zakazuje dělat vše, co není explicitně povoleno
  - princip whitelistu
  - nákladnější
- paranoidní
  - zakazuje vše, co by mohlo být potenciálně nebezpečné
  - kontroluje vše
  - nejvyšší zabezpečení
