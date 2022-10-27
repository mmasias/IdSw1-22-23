@startuml

class Campo
class Futbol
class Equipos
class Personal
class Arbitro 
class jugador
class Entrenador
class Persona


jugador *-- Persona : es
Arbitro *-- Persona : es 
Equipos *-- jugador : Formado por 
Equipos *-- Entrenador : tiene
Personal *-- Arbitro : Formado por 
Futbol *-- Arbitro : tiene
Futbol *-- Personal : tiene 
Campo *-- Futbol : tiene 

@enduml
