# Úvod do operačních systémů (2)

## funkce OS

- **správa paměti**
  
  - vede evidenci vnitřní paměti
  
  - správa virtuální paměti
  
  - řeší situace vznikajcí při nedostatku paměti

- **správa procesů**
  
  - "tabulka"
  
  - evidence spuštěních procesů
  
  - plánování přidělování procesoru
  
  - sledování stavu procesů
  
  - zajišťování komunikace mezi nimi

- **správa periferií**
  
  - vytváří rozhraní mezi I/O zařízeními a procesy
  
  - sledování stavu zařízení
  
  - přidělování zařízení procesům
  
  - řešení možných kolizí s tím souvisejících
    
    - především u starších OS

- **správa systému**
  
  - různé režimy práce
    
    - uživatelský
    
    - privilegovaný
      
      - údržba, instalace, konfigurace

- **správa souborů**
  
  - u vnějších paměťových zařízeních
  
  - jak budeme k souborům přistupovat (jednotný způsob)
  
  - kontrola práv
  
  - souborové systémy

- **správa uživatelů**
  
  - vede informace o uživatelích systému a jejich činnosti
  
  - zajíšťuje přihlašování a odhlašování

- **správa úloh**
  
  - úlohy a jejich průběh

- **uživatelské rozhraní** (UI)
  
  - rozhraní mezi uživatelem a systémem
  
  - sada programů, které slouží ke komunikaci mezi uživatelem a OS
  
  - u Linuxu shell

- **programové rozhraní** (API)
  
  - Application Programming Interface
  
  - rozhraní mezi procesy a výpočetním a operačním systémem
  
  - sada knihoven (.dll, .so)

## typy OS

- **podle počtu ovládaných procesů**
  - jednoprocesorové
    - Windows s DOS jádrem (verze 9x, ME)
  - víceprocesorové
    - UNIXové systémy (vč. Linuxu), Windows s NT jádrem
      - asymetrický multiprocessing (ASMP)  
        - jeden procesor je vyhrazen pro procesy systému a uživatelské procesy běží na ostatních procesorech   
      - symetrický multiprocessing (SMP)     
        - kterýkoli proces může běžet na kterémkoli procesoru
- **podle složitosti správy uživatelů**
  - jednouživatelské (DOS)
  - víceuživatelské
    - unixové systémy
- **podle počtu spuštěných programů**
  - jednoprogramové
  - víceprogramové
    - multitaskové systémy
- **podle míry specializace**
  - speciální
  - univerzální
    - Unix, Linux, Windows, MacOS
- **realtimové os**
  - pracují téměř v reálném čase
  - využití
    - vysoké požadavky na interaktivitu systému
    - např. řízení letadel, výrobní provoz, laboratoře, elektrárny
  - horní časová hranice
    - nejhorší maximální doba reakce
  - s multitaskem toto nelze zaručit
  - mikrojádro
  - **QNX**
    - v automobilech
    - mimořádná stabilita a rychlost
    - komerční systém
  - **RTLinux**
    - řízení robotů
    - samostatné linux jádro a realtime mikrojádro
  - **realtime Preemption patch**
  - **RTX**
    - modul rozšiřuje možnosti Windows s NT jádrem směrem k realtimových systémů
    - nadstavba