@startuml
State Peticion {
  state c <<choice>>
  PeticionPendiente -> c  
  c --r> PeticionDenegada : No es aceptable
  c --l> PeticionAceptada : Es aceptable

  state c1 <<choice>>
  PeticionDenegada --> c1 
  PeticionPendiente <--- c1 : Se corrige Solicitud


  State Viaje{
    state c3 <<choice>>
    PeticionAceptada --> ViajePendiente

    State Gestion{
      ViajePendiente --> GestionEnTramite
      GestionEnTramite --> GestionTramitada
    }
    
    GestionTramitada -->  ViajeEnCurso

    State Factura{
      state c2 <<choice>>
      ViajeEnCurso ---r> c2
      c2 --> FacturaPendienteDeEnvio :se Genera factura
      c2 ----> c3 : no se genera factura
      FacturaPendienteDeEnvio -l> FacturaEnviada
    }
      
    FacturaEnviada --l> c3 
    ViajeEnCurso <r--- c3 : viaje continua
    c3 ---> ViajeFinalizado :viaje se termina  
  }
}
[*] --> PeticionPendiente
c1 --> [*] : No se corrige solicitud
ViajeFinalizado --> [*] 
@enduml