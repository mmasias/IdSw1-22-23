@startuml

class Partido 
class Equipo 
class Jugador 
class CuerpoTécnico 
class Campo 
class Reglamento 
class Árbitro 
class Balón 
class Marcador
class Personal

class Partido {
 - Fecha
 - Duración
}
class Jugador {
 - Identificación : String
 - Titularidad : Boolean
}

Partido *--- Personal : Tiene >
Partido "1" o-l-- "1" Campo 
Partido *-- Reglamento : Tiene >
Partido "1" ---* "1" Marcador : Representa resultado <
Partido o-r-- "n" Balón : Jugado con >
Personal --- "2" Equipo : Incluye >
Personal --- "n" Árbitro : Incluye >
Árbitro .l.. Reglamento : Hace cumplir >
Equipo .r.. Reglamento : Cumple >
Equipo "1" *--- "11" Jugador 
Equipo "1" *--- "1" CuerpoTécnico  
Jugador "11" --- "1" CuerpoTécnico : Apoya <
Jugador --- Marcador : Produce cambios >

@enduml
