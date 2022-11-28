@startuml
object "viaje: Viaje" as viaje {
}
object "ocurrencias: Ocurrencias" as ocurrencias{
}
object "factura: Factura" as factura{
}
object "dieta: Dieta" as dieta{
	esViajeInternacional: true
	presupuesto: 100
}
object "transporte: Transporte" as transporte{
	medio: Coche
	distancia: 400
	disponibilidad: Universidad
}
object "morada: Morada" as morada{
	tipo: Hotel
	Financiamiento: Universidad
}
object "gestion: Gestion" as gestion{
}
object "peticionViaje: PeticionViaje" as peticionViaje{
        RazonViaje: Concurso de Debate
}
object "destino: Destino" as destino{
        Pais: España
        Provincia: Comunidad de Madrid
        Ciudad: Madrid    
}
object "fechas: Fechas" as fechas{
        Fecha Ida: 10-11-2022
        Fecha Vuelta: 11-11-2022
}
object "profesor: Profesor" as profesor{

}
object "vicerrectorado: Vicerrectorado" as vicerrectorado{

}
vicerrectorado --> peticionViaje : Acepta / Deniega
viaje -o ocurrencias
ocurrencias - factura : Genera
dieta o--- ocurrencias
transporte o--- ocurrencias
morada o--- ocurrencias
gestion --> viaje : Tramita
peticionViaje -> viaje
peticionViaje --* destino
peticionViaje --* fechas
profesor *- peticionViaje : Solicita >
@enduml

