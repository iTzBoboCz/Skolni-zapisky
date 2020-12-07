# Jádro Linuxu

- chybí vrstva HAL
  
  ## Hardwarové zabezpečení systému
  
  - na x86 implementováno ve formě čtyř okruhů ( Ring 0,.. Ring 3)
  
  - každý proces běží v nějakém v těchto okruhů, to určuje jeho možnosti přístupu
  
  - většina OS používá pouze dva okruhy:
    
    - Ring 0 pro jádro systému
    
    - Ring 3 pro uživatelský režim
  
  - logicky vyplívá, že Ring 1 a 2 obvykle nejsou používány. Přesto je možné je použít pro další rozškálování přístupových oprávnění
  
  - S Ring 1 se setkáme u některých virtualizačních technik, zejména na serverech


