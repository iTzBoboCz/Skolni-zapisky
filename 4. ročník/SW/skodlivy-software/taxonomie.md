# Klasifikace/taxonomie/zařazení virů

- řazení podle způsobu infiltrace

## trojské koně
## červi
  - šíří se sám
  - šíření např. pomocí zpráv
  - 
## backdoory (zadní vrátka)
  - nezašifrované sociální sítě
  - šifrované
    - právo nevypovídat
## viry
  - antivir
    - cílené vs obecné protilátky
  - napadá spustitelné soubory (binární)
### dělení podle umístění v paměti
#### paměťově rezidentní viry
  - zůstává zavedený v paměti
  - podle 
  - boot viry
    - při zavádění do systému (boot)
    - např. vypnutí antiviru
    - MBR tabulka
  - souborové viry
    - při spuštění souboru 
    - oblast napadení
      - přepisovací viry
        - celý soubor přepíše
        - nezachová funkce
      - parazitické viry
        - obsah cílového souboru nepoškodí
        - zachová funkce
      - multipartitní viry
        - mix předchozích
        - např. známý virus OneHalf
      - makro viry
        - tvořené pomocí maker
        - Stealth
          - kódované viry (crypted viruses)
            - znepřehladnění kódu 
          - polymorfní (mutační) viry
            - vytváří během replikace kopie, které jsou funkčně ekvivalentní, ale kód se podstatně liší
          - metamorfní viry
            - napadený soubor obsahuje kompilátor a zdrojový kód viru
            - kompilátor vytváří vždy odlišnou verzi
        - Retro viry
          - vypínají ochranu
        - multipartitiní
          - dokáže se šírit více způsoby
        - multiplatformní
#### nerezidentní viry
- nemnoží se
- přímá akce
- fast infector
  - infikuje i soubory, kterými je manipulováno (kopírování, archivace,..)
  - zpomaluje PC
- slow infector
  - infikuje pouze program, do kterého je právě zapisováno
