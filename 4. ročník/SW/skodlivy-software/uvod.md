# Škodlivý software

## Viry

- napadá hostitele, případně i jejich programy a soubory
- způsoby napadení
  1. appending
    - za
  2. prepending
    - před
  3. inserting
    - mezi
    - nejsložitější pro antivir detekovat

### antiviry

- zablokuje spuštění souboru (přidání do karantény)
  - popř. smaže
  - léčení
    - zkusí opravit
- rezidentní štít
  - kontroluje velikost spouštěných souborů vůči prvnímu spuštění
- vyhledávání virů
  - porovnává s databází škodlivých kódů
  - závisí na velikosti databáze
- kvalitu antiviru udává rychlost reakce od objevení nového viru

### Dělení virů podle

- způsob šíření
  - červ se replikuje
    - např. rozesílá zprávy s odkazy
- způsob útoku
  - co napadá a jak
  - bitlocker
  - malware
  - trojský kůň
    - schovává se za nějakou jinou činnost
  - spyware
  - adware
  - keylogger
  - ransomware
  - crackování
    - přepisuje a obchází registry
    - např. her
  - bootblock
- rozsah napadení
  - multiplatformní
    - existují viry i pro android a IoT

### prevence

- antivir
- nestahovat a nespouštět neznámé soubory
- sandboxing

### motivy k vytvoření virů

- peníze
- zábava
- získání informací
  - vir může nainstalovat i správce sítě na firemní zařízení

### Detekce virů

- skener
  - hledání charakteristických skupin instrukcí
  - paměťově rezidentní
    - kontroluje veškerů činnost uživatele se soubory
    - pokud zjistí, že je manipulováno s infikovaným programem - upozorní
  - na požádání
    - manuální skenování
    - uživatel definuje oblast
  - kontrola integrity
    - porovnání akt. stavu důležitých programů a oblastí na disku s informacemi, které si kontrolní program uložil při své instalaci
  - heuristická analýza
    - rozbor kódu
    - hledá postupy pro činnost virů nebo podezdřelé činnosti 