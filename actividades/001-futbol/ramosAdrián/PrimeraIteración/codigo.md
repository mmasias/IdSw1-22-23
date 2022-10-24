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

Partido "1" *-- "1" Campo : Localizacion
Partido "1" *-- "1" Reglamento : Regula
Partido "1" *-- "Varios" Árbitro : Revisa
Partido "1" *-- "1" Marcador : Determina
Partido "1" *-- "2" Equipo : Da lugar
Equipo "2" --* "1" Campo : Está en
Equipo "1" *-- "11" Jugador : Pertenece
Equipo "1" *-- "1" CuerpoTécnico : Pertenece
Reglamento "1" *-- Árbitro : Hace cumplir
Reglamento "1" *-- "2" Equipo : Sujeto a
Jugador "22" --* "1" Balon : Juega con
Jugador "11" *-- "1" CuerpoTécnico : Apoya a
Jugador --* Gol : Marca
Gol --* "1" Marcador : Cambia

@enduml
