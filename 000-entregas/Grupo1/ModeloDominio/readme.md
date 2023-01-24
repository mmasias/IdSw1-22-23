## Glosario

| Clase                           | Descripción                                                                                             |
| ------------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Alumno**                      | Estudiante que cursa un máster.                                                                         |
| **Máster**                      | Titulación académica impartida por una universidad                                                      |
| **Plataforma**                  | Página con la que los alumnos interaccionan.                                                            |
| **SistemaGestionUniversitario** | Plataforma administrativa de la universidad en la que se registran los alumnos                          |
| **Sistema**                     | Representacion de la solucion desarrollada                                                              |
| **RecopiladorDeDatos**          | Entidad externa al sistema que recopila los datos de la plataforma y sistema de gestión y los normaliza |
| **ProcesadoDeDatos**            | Entidad que se encarga de solicitar datos al recopilador y procesarlos                                  |
| **Intérprete**                  | Analiza los datos procesados y saca conclusiones de estos.                                              |
| **Acción**                      | Realiza acciones que el intérprete ha ofrecido como enviar un correo, reunirse con el alumno, etc.      |
| **Clúster**                     | Conjunto de alumnos que tienen características comunes                                                  |
<hr>

## Diagramas

<details>
  <summary>Diagrama de clases</summary>
  
|Diagrama de clases
|:-:
|![](01-DiagramaDeClases/Clases.png)

</details>

<details>
  <summary>Diagrama de objetos</summary>
  
|Diagrama de objetos
|:-:
|![](02-DiagramaDeObjetos/Objetos.png)

</details>

<details>
  <summary>Diagrama de estados</summary>

  <div align="center">

| Estado                     | Descripción                                                                   |
| -------------------------- | ----------------------------------------------------------------------------- |
| **Alumnos Interactuando**  | El alumno interactúa con la plataforma o el sistema de gestión y genera datos |
| **Procesamiento Datos**    | Se procesan los datos generados por los alumnos                               |
| **Alumno Bajo Engagement** | Alumno con baja interacción y compromiso                                      |
| **Alumno Alto Engagement** | Alumno con alta interacción y compromiso                                      |
| **Abandono**               | Alumno deja la institución                                                    |

</div>
  
|             Diagrama de estados alumno              |             Diagrama de estados sistema              |
| :-------------------------------------------------: | :--------------------------------------------------: |
| ![](03-DiagramaDeEstados/DiagramaEstadosAlumno.png) | ![](03-DiagramaDeEstados/DiagramaEstadosSistema.png) |


</details>

<hr>

[Atrás](../readme.md)
