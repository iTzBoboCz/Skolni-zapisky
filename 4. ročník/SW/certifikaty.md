# Certifikáty

- v EU směrnice eiDAS

## formáty

- atributové certifikáty
- DV certifikáty
- X.509
  - nejčastější typ
  - kvalifikované certifikáty se vážou na email, tzn. je možné je odeslat pouze z daného emailu

- DER, BER? ASN.1

## autority

- certifikační autorita (CA)
  - generuje certifikáty
  - třídy CA
    - třída 1
      - žadatel -> www form přes https -> cert.
    - třída 2
      - jako předchozí + CA kontroluje totožnost uživatele
    - třída 3
      - jako předchozí, ale vydané certifikáty jsou určeny výhradně pro konkrétní aplikaci (komerční certifikát)
      - soukromý klíč je uchováván v bezpečném hardware

- správní autorita (SA)
  - udržuje adresář vydaných certifikátů
  - zodpovídá za publikované údaje
  - zajišťuje dostupnost certifikátů přes internet (LDAP)
- registrační autorita (RA)
  - komunikuje se žadatelem
  - ověřování totožnosti
- časová razítka
  - např. kdy bylo pdf podepsané
  - musí být získáno od autority, protože na počítači je možné si změnit čas
  - obdobnou službu může zajistit i notář
  - ohlídat si oficiální dokumenty od úřadníků, že jsou podepsané

## použití klíče

- dig. podpis
- neodvolatelnost
