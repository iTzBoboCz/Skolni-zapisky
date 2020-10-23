# Struktury OS
- **Monolitická struk.**
    - nejjednodušší struktura používaná v jádrech OS nebo zařízeních
    - komunikace mezi jádrem a okolím
    - funkcionalitu rozšiřují moduly (knihovny)
- **Vrstvená struk.**
    - části systému uspořádány do vrstev
    - vstva používá služeb nižší vrstev
    - systém budován od vnitřních vrstev k vnějším
    - vrstva jádra (chráněný režim) a uživatelská
- **Virtuální počítače**
    - systém rozdělen do samostatných modulů
    - moduly nemohou zasahovat do ostatních (mohou, ale předávat data)
    - podsystémy systémů
    - mohou zde běžet starší aplikace
- **Abstraktní počítače**
    - systém rozdělen do částí
    - části mají svou specifickou funkci
    - mají přidělen výhradně pouze jediný prostředek
- **Modulární struktura**
    - systém členěn do modulů
    - ovladače, různé filtry, síťové protokoly ...
- **Model klient-server**
    - má co jejmenší jádro (minikernel)
    - obsahuje pouze základní funkce
    - ostatní funkce provádějí speciální systémové procesy (servery)
    - procesy, které spouští uživatel (klient)
    - vyšší stabilita systému
# MS-DOS a WIN do verze 3.x

<table>
  <tr>
    <td>aplikace Win16</td>
    <td>aplikace Win16</td>
    <td>aplikace Win16</td>
    <td rowspan="4">VM DOS 1</td>
    <td rowspan="4">VM DOS 2</td>
    <td rowspan="4">VM DOS 3</td>
  </tr>
  <tr><td colspan="3">správce programů, shell</td></tr>
  <tr><td colspan="3">konfigurační soubory (WIN.INI, SYSTEM.INI)</td></tr>
  <tr><td colspan="3">jádro Windows (KRNL389.EXE, USER.EXE, GDI.EXE)</td></tr>
  <tr><td colspan="6">DOS Extender, řadiče virtuálních strojů</td></tr>
  <tr><td colspan="6">bios, MS-DOS, řadiče</td></tr>
  <tr><td colspan="6">hardware</td></tr>
</table>

- windows grafická nadstavba
# WINDOWS s DOS jádrem 
<table>
    <tr>
        <td rowspan="2">Systémové procesy a shell</td>
        <td>aplikace win32</td>
        <td>aplikace win16</td>
        <td rowspan="3">VM DOS 1</td>
        <td rowspan="3">VM DOS 2</td>
        <td rowspan="3">VM DOS 3</td>
    </tr>
    <tr>
        <td>aplikace win32</td>
        <td>aplikace win16</td>
    </tr>
    <tr>
        <td colspan="2">jádro windows (KERNEL, USER, GDI)</td>
        <td colspan="1">registr</td>
    </tr>
    <tr>
        <td colspan="2">IFSM</td>
        <td colspan="2">správce konfigurace</td>
        <td colspan="2">VMM</td>
    </tr>
    <tr><td colspan="6">bios, ovladače</td></tr>
    <tr><td colspan="6">hardware</td></tr>
</table>
