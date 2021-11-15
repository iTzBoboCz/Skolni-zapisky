# Útoky

## Phishing

- podvodné zprávy (email, SMS,..)

### Znaky phishingového útoku

- žádost o osobní údaje
- falešný odkaz, podezřelá doména
- obecné nebo neformální oslovení
- špatná gramatika
- klikatelný obrázek

### Pravidla pro obranu

- neposkytovat citlivé údaje
- neposílat citlivá data pomocí nešifrovaného emailu
- neodpovídat na zprávy
- neklikat na odkazy v podezřelém emailu
- na stránkách nemít celý email (rozdělit - např. at místo @ nebo captcha nebo mít jako obrázek)

### Postup při podezření na phinshingový útok

1. nezadávat nikam žádné údaje
2. nahlásit útok opravdové firmě

## Spoofing

- zachytávání dat (paketů), případně i jejich změna
- falšování IP adresy příchozích paketů
- vydávání se za někoho jiného v síti
- Man-in-the-middle attack (MITM)
- GSM Spoofing - více SIM karet
- využití:
  - rozesílání emailů
  - anonymita
  - GPS Spoofing
    - získání kontroly nad navigací
  - DNS Spoofing
    - přesměrování uživatele
- útočník nedostává odpověď

### obrana

- šifrování

## DDoS

- přetížení služby dotazy
  - přetížení zdrojů
  - přetížení kapacity linky
- nemusí jít vždy o útok (např. žáci se připojí do IS a budou reloadovat stránku)

### typy
- Syn flooding
- Slowloris
  - http
- Ping flood
- Smurf attack

## SQL injection

- vsunutím kódu přes neošetřený vstup a vykonání vlastního pozměňujícího poškozujícího SQL příkazu

### zabezpečení hesla

- dlouhé heslo
- salting (solení)
  - aby dva uživatelé se stejným heslem neměli stejný hash

## Obrana

- aktivní
- pasivní
  - děje se automaticky
  - firewall
    - neodpovídat na požadavky z venku
