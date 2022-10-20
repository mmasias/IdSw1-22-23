# Modelo del dominio de un partido de fútbol

Vamos a ir poniendo aquí los trabajos. Creamos cada uno (en esta carpeta) una carpeta llamada apellidosNombre y dentro de ella nuestros avances


El pull request a su propia rama



@startuml
class campo
class equipo
class tiempo
class arbitro
class jugador
class partido

campo *-- partido : Se juega en un
equipo --* partido : Juega un
tiempo --* partido : Define un
jugador --* equipo : Pertenece a un
arbitro --* tiempo : Controla el

@enduml
