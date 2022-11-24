@startuml
Profesor *- PeticionViaje : Solicita >
PeticionViaje : RazonViaje
PeticionViaje --* Destino
PeticionViaje --* Fechas
PeticionViaje -> Viaje
Destino : Pais
Destino : Ciudad
Destino : Provincia
Fechas : Fecha Ida
Fechas : Fecha Retorno
Gestion --> Viaje : Tramita
Viaje -o ocurrencias
ocurrencias - Factura : genera
Dieta o--- ocurrencias
Transporte o--- ocurrencias
Transporte : Distancia
Transporte : Medio: Avion|Tren|Coche
Transporte : Disponibilidad: Particular|Universidad
Morada o---  ocurrencias
Morada : Tipo: Familiar|Hotel|Airbnb
Morada : Financiamiento: Personal|Universidad 
@enduml
