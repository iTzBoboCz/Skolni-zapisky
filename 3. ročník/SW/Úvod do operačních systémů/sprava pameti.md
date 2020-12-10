# Správa paměti

- část jádra
- přiděluje pamět procesům
- udržuje informace o paměti
- paměť, kterou proces uvolní, zařazuje k volné paměti
- odebírá paměť procesům
- ochrana paměti je v současných běžných OS zajišťována hardwarově
- **Adresy** slouží k přenosnému umístění operační paměti v různých částech HW
    - proces k paměti přistupuje přes paměti
    - **absolutní** na bit
    - **relativní** na blok a poté na bit
- **fyzický adresový prostor** - k dispozici fyzicky
- **logický adresový prostor** - k dispozici pro procesy
- **virtuální metody přidělování paměti** - pokud je logický větší než fyzický prostor
- **Metody přidělování paměti**
    - přidělení jedné souviské oblasti paměti
        - jednoduchost, nemožnost mít spuštění více procesů a velká nevyužitá část paměti