@startuml Objetos

object "Partido : Partido" as Partido {
   Nombre = "España-Alemania"
   Fecha = "27/11/2022"
}
object "Al Bayt : Estadio" as Campo
object "España : Equipo" as EquipoEspaña
object "Alemania : Equipo" as EquipoAlemania
object "Árbitro : Árbitro" as Árbitro {
   Función = "Principal"
}
object "Árbitro2 : Árbitro" as ÁrbitroLínea {
   Función = "Juez de Línea"
}
object "Árbitro3 : Árbitro" as ÁrbitroLínea2 {
   Función = "Juez de Línea"
}
object "Árbitro4 : Árbitro" as ÁrbitroVar {
   Función = "Asistente de Vídeo VAR"
}
object "Marcador : Marcador" as Marcador {
   Resultado = "1:1"
}
object "Jugador1 : JugadorEspaña" as JugadorEspaña1 {
   Identificador = "Busquets"
   Titularidad = "Sí"
}
object "Jugador2 : JugadorEspaña" as JugadorEspaña2 {
   Identificador = "Morata"
   Titularidad = "No"
}
object "Jugador1 : JugadorAlemania" as JugadorAlemania1 {
   Identificador = "T. Müller"
   Titularidad = "Sí"
}
object "Jugador2 : JugadorAlemania" as JugadorAlemania2 {
   Identificador = "Hofmann"
   Titularidad = "No"
}



Partido -r- Campo : "> Ocurre en"
Partido -d- EquipoEspaña : "< Juega"
Partido -- EquipoAlemania : "< Juega"
Partido -l- Árbitro : "< Dirige"
Partido -u- Marcador
Árbitro -u- ÁrbitroLínea : "< Ayuda"
Árbitro -d- ÁrbitroLínea2 : "< Ayuda"
Árbitro -l- ÁrbitroVar : "< Ayuda"
EquipoEspaña -- JugadorEspaña1
EquipoEspaña -- JugadorEspaña2
EquipoAlemania -- JugadorAlemania1
EquipoAlemania -- JugadorAlemania2

@enduml
