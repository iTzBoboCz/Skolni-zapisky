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

## firewall

- filtrujeme s pomocí pravidel
- nestavový
  - obsahuje tabulku s povolenými kombinacemi zdrojů a cílů
  - funguje jako whitelist, pokud neexistuje pravidlo, klienta nepustí dál
- stavový
  - dokáže sledovat provoz i na základě parametrů spojení
  - stavy
    - NEW
    - ESTABLISHED
    - RELATED
      - pouze u TCP
    - INVALID
- aplikační
  - proxy brány
- topologie
  - dvounohý firewall
    - nejběžnější typ firewallu
    - odděluje dvě nebo více sítí
  - demiliratizovaná zóna
    - izoluje podnikovou infrastrukturu od vnější sítě
    - z vnitřní sítě není možné zaútočit na serverovou strukturu
- netfilter
  - 4 tabulky
    - filter
    - nat
    - mangle
    - raw
- firewall je možné řešit v síti nebo i na jednotlivých zařízeních

## VPN

- oproti proxy jsou data zabezpečená
- možné použít zařízení v síti cíle (lokální)
- vytváří tzv. tunel
- tunel je vždy mezi routery
- k přenášeným paketům se přidává hlavička GRE (Generic Routic Encapsulation) s cílovou adresou routeru na druhém konci tunelu, cílový router ji odstraňuje
