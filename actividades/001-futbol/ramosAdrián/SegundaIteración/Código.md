@startuml

class Partido 
class Equipo 
class Jugador 
class CuerpoTécnico 
class Campo 
class Reglamento 
class Árbitro 
class Balon 
class Gol 
class Marcador
class Tiempo
class Personal

Partido --> Personal : Forman parte directa
Partido "1" --> "1" Campo : Se produce en
Partido "1" --> "1" Reglamento : Tiene
Partido "1" <-- "Varios" Árbitro : Revisa 
Partido "1" <-- "1" Marcador : Determina resultado
Personal <-- Reglamento : Vincula a
Personal --> "2" Equipo : Incluye
Personal --> Árbitro : Incluye
Personal <-- "1" Campo : Contiene
Equipo "1" --> "11" Jugador : Incluye
Equipo "1" --> "1" CuerpoTécnico : Incluye
Partido "1" -- "Muchos" Balon : Se juega con 
Jugador "11" <-- "1" CuerpoTécnico : Apoya a 
Jugador --> Gol : Marca 
Gol --> "1" Marcador : Cambia
Partido --> Tiempo : Tiene duración

@enduml
