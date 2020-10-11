# TQS-Buscamines
## Aleix Saus Mestres - 1458353
## Albert Romero Diví - 1425095


Plantejament buscamines

Classes:
Joc:
    Boolean victoria
    Casella = new casella()
    Bucle del joc ( while (casella != mina || victoria) {} 
        -Escollir casella 
        -Marcar casella (bomba segura / interrogant)
        -Es mira el contingut de la mina
    If (casella == mina) → perdre
    If (victoria) → Guanyar

Taluer
    Inicialitzar tauler → inicialitzar a zeros
    Posar mina → Posar la mina amb un random de fila i columna
    Posar valor a la casella propera a la mina (si hi ha mina passar a la següent)
        int cont;
        Veure les 6 caselles adjacents
        Si casella adjacent es mina cont ++
    Desvetllar casella
        
Casella
    Agregació:      
    - Casella buida (si es prem les buides al voltant també s’obren)
    - Casella amb mina (perdre)
    - Casella amb número
