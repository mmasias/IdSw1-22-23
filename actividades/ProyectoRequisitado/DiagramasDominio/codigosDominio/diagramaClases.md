@startuml
Profesor *- PeticionViaje : Solicita >
Vicerrectorado --> PeticionViaje : Acepta / Deniega
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
Dieta : esViajeInternacional
Dieta : Presupuesto
Transporte o--- ocurrencias
Transporte : Distancia
Transporte : Medio: Avion|Tren|Coche
Transporte : Disponibilidad: Particular|Universidad
Morada o---  ocurrencias
Morada : Tipo: Familiar|Hotel|Airbnb
Morada : Financiamiento: Personal|Universidad 
@endum
