@startuml
class Competicion
Competicion : Nombre
Competicion  *--  Partido: Tiene
Competicion  *--  Equipo: Participan

Estadio : Pais
Estadio : Ciudad
Estadio : NombreEstadio
Estadio : Capacidad
CuerpoTecnico *--  Entrenador: Tiene
CuerpoTecnico  *--  Ayudante: Tiene
CuerpoTecnico  *--  Medico: Tiene
Partido  *--  Estadio: Lugar
Partido  *--  Fecha: EmpiezaCuando
Equipo : nombre
Entrenador : nombre
Jugador : nombre
Ayudante : nombre
Medico : nombre

Partido  *--  Marcador: MarcaTiemp
Jugador  *--  Plantilla: Tiene
Equipo  *--  Plantilla: Tiene
Equipo  *--  CuerpoTecnico: Tiene
Partido  *--  Equipo: Juega
Jugador -->  Titular
Jugador -->  Suplente

@enduml
