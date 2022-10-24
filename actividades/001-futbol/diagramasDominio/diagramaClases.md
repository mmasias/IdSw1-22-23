@startuml
class Partido

Partido -- Lugar
Partido -- Fecha
Partido -- Balon
Partido -- Equipo
Partido -- CuerpoArbitral

Equipo -- Jugador
Equipo -- CuerpoTecnico
Equipo -- Directiva

Jugador -- Portero

CuerpoTecnico -- Entrenador
CuerpoTecnico -- Ayudantes

CuerpoArbitral -- ArbitroCampo
CuerpoArbitral -- ArbitroVar

Lugar : NombreEstadio
Lugar : Capacidad
Lugar : Ciudad
Lugar : Pais
Lugar : UsoHorario

Fecha : Año
Fecha : Mes
Fecha : Dia
Fecha : Hora
Fecha : Minuto

Balon : Marca

Equipo : Nombre
Equipo : Escudo
Equipo : PrimeraEquipacion
Equipo : SegundaEquipacion

Jugador : Nombre
Jugador : Apellido
Jugador : Dorsal
Jugador : ¿Titular,Convovado o no?
Jugador : Altura
Jugador : Peso
Jugador : Sueldo

Portero : TipoGuante

Entrenador : Nombre
Entrenador : Apellido
Entrenador : Sueldo

Ayudantes : TipoAyudante
Ayudantes : Nombre
Ayudantes : Apellido
Ayudantes : Sueldo

Directiva : Nombre
Directiva : Apellido
Directiva : Sueldo
Directiva : Rol

ArbitroCampo : Nombre
ArbitroCampo : Apellido
ArbitroCampo : Sueldo
ArbitroCampo : FuncionCampo

ArbitroVar : Nombre
ArbitroVar : Apellido
ArbitroVar : Sueldo
ArbitroVar : FuncionVar
@enduml
