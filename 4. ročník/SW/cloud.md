# Cloud

- cloud computing
- co to je
  - databáze
  - výpočetní síla
  - uložiště
  - konektivita

## rozdělení zabezpečení

### provozovatel 

  - šifrování
  - antivirus
  - monitoring sítě (inspekce paketů)
    - automatická analýza v reálném čase
    - identifikace útoků, malware, potenciálních útoků dat
    - SNMP (Simple Network Management Protocol)
      - bez detailních informací
      - základní troubleshooting
      - pro menší sítě
      - kolik paketů, kolik dat
      - monitoring provozu v určitých uzlech sítě - ukládání do db - agent
      - sběr dat od agentů - manager
      - vzdálené řízení - reset, reboot, nastavení proměnných
    - flow control
      - detailní přehled o dění v síti
      - hlavičky paketů
      - obsah paketů není monitorován ani uchováván
      - kdo, s kým, co, jak dlouho
      - sledování trendů
      - za 1 den, při 1Gbps lince zatížené na 10%, flow monitoring zabere cca 2 GB
    - paketová analýza
      - velmi detailní, časově náročná
      - zachycení provozu v celém rozsahu
      - nástroje
        - tcpdump
        - wireshark
      - za 1 den, při 1Gbps lince zatížené na 10%, paketová analýza zabere cca 1 TB
  - struktura a charakter provozu
    - 10% uživatelů vygeneruje 90% provozu

### připojení

  - prohlížeč
    - pluginy
    - nastavení

### uživatel

- neposílat infikované soubory

## hrozby v cloudu

- únik dat
- zneužití výpočetní kapacity
- (D)DOS útoky

## obrana cloudu

- šifrovat
- logovat akce uživatelů
- šifrování přenosu
- školit zaměstnance
- monitorovat síť
- autentizovat uživatele
- vícefaktorová autentizace
