@startuml

State Partido {
  [*] --> Inicio
  State elección <<choice>>
  State QuedaTiempo 
  State Inicio
  State Gol
  State Tiempo {
    Saque --> EnJuego
    EnJuego --> Detenido
    Detenido --> Saque    
  }

Inicio --> Tiempo
Tiempo --> elección 
QuedaTiempo -d-> [*] : Se termina el partido
QuedaTiempo -l-> Inicio : Seguir
elección --> QuedaTiempo 
elección -r-> Gol
Gol --> Inicio : Continúa el partido
}

@enduml
