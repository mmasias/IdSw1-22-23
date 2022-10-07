@startuml
class Competicion
Competicion : NombreCompeticion
Competicion "1" *-- "Muchos" Partido: Tiene
Competicion "1" *-- "Muchos" Equipo: Participan

Partido : Duracion
Partido "1" *-- "2" Equipo: CuentaCon
Equipo : Nombre
Equipo : Escudo
Equipo : 1Equipacion
Equipo : 2Equipacion
Equipo : Presupuesto
Partido "1" *-- "1" Estadio: TieneLugarEn
Partido "1" *-- "1" Fecha: EmpiezaA

Estadio : Pais
Estadio : Ciudad
Estadio : NombreEstadio
Estadio : Capacidad

Fecha : Dia
Fecha : Hora
Fecha : Minuto

Equipo "1" *-- "Muchos" Jugador: Tiene
Jugador : Nombre
Jugador : Edad
Jugador : Posicion
Jugador : Dorsal
Jugador : Altura
Jugador : Peso
Jugador : Salario
Jugador : ¿Lesionado?
Equipo "1" *-- "1" CuerpoTecnico: Tiene

Jugador --> "11" Titular
Jugador --> "7" Suplente
Jugador --> "Resto" Desconvocado

CuerpoTecnico "1" *-- "1" Entrenador: Tiene
CuerpoTecnico : Nombre
CuerpoTecnico : Salario
CuerpoTecnico "1" *-- "Varios" Ayudante: Tiene
CuerpoTecnico "1" *-- "Varios" Medico: Tiene
@enduml
