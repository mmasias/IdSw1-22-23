@startuml

[*] --> PrePartido
PrePartido --> InicioPartido
InicioPartido --> BalonParado : Saque
BalonParado --> BalonJuego : Saque
BalonJuego --> BalonParado : Pitido
BalonJuego --> FinPrimeraParte : PitidoFinal
FinPrimeraParte --> InicioSegundaParte
InicioSegundaParte --> BalonParado : Saque
BalonJuego --> FinSegundaParte : PitidoFinal
FinSegundaParte --> Prorroga
Prorroga --> InicioPrimeraParteProrroga
InicioPrimeraParteProrroga --> BalonParado : Saque
BalonJuego --> FinPrimeraParteProrrofa : PitidoFinal
FinPrimeraParteProrroga --> InicioSegundaParteProrroga
InicioSegundaParteProrroga --> BalonParado : Saque
BalonJuego --> FinSegundaParteProrroga : PitidoFinal
FinSegundaParteProrroga --> Fin
FinSegundaParteProrroga --> Penaltis
Penaltis --> Fin
FinSegundaParte --> Fin
Fin --> [*]

@enduml
