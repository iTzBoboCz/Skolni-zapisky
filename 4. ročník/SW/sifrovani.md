## steganografie

- schování informace do souboru (např. obrázku)
- vložení informace navíc
- [ukázka](https://github.com/Ge0rg3/StegOnline)


# Šifrování

- každá šifra je prolomitelná, je to pouze otázka času
- metody: substituce, transpozice

## Symetrické

- 1 klíč
- např. Enigma
- využití:
  - např. chatovací aplikace

### Monoalfabetická

- po znacích
- nejstarší
- můžeme přečíst (ne rozšifrovat) i bez klíče
  - jazyk
    - každý jazyk má nejpoužívanější písmena a slova
      - index koincidence
- Caesarova šifra
  - posun písmen
    - substituce
- z dnešního pohledu není bezpečná
- používané do konce 1. SV

- DŮ: zašifrovat monoalfabeticky text a spočítat četnost (písmen po zašifrování) a rozkodovat alespoň 1 slovo
  - mít 1 srovnatelný text nešifrovaný (stejné téma)
  - anglicky
  - nějaký článek jako text
  - závěr - postup, úspěch/neúspěch

### Polyalfabetická

- po řetězcích
- bezpečnější než monoalfabetické šifry

## Asymetrické

- 2 klíče
  - public
  - private
- klíče vznikají současně
- od ~1976
- bezpečnější než symetrické šifry
- šifrování trvá déle
- certifikáty
  - standardizovaný formát X.509
  - atributový
- elektronické podpisy
  - kvalifikovaný
    - certifikát můžeme skladovat na počítači
    - identifikátor chůchod. pojištění
    - ekvivalent běžného podpisu
  - kvalifikovaný založený na kvalifikovaném certifikátu
    - certifikát skladovat např. na šifrovaném USB
    - úřední podpis
- kryptoanalýza
- hash je také asymetrický
- prvním všeobecně známým šifrovacím strojem je ENIGMA

### jednotlivé algoritmy

- **DES** (1977?-2001)
- IDEA (1992)
- BLOWFISH
- RC5
- **RSA**
