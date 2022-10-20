@startuml
[*] -> AntesPartido
AntesPartido --> InicioPrimeraParte: PitidoInicial
InicioPrimeraParte --> BalonJugado : PitidoSaque
BalonJugado --> BalonParado : Pitido
BalonParado --> BalonJugado : Saque
BalonParado --> FinPrimeraParte : PitidoFinal
FinPrimeraParte --> InicioSegundaParte : Descanso
InicioSegundaParte--> BalonJugado : PitidoSaque
BalonParado --> FinSegundaParte : PitidoFinal
FinSegundaParte --> [*] : PitidoFinal
@enduml
