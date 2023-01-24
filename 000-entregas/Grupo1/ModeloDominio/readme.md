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
| **Alumnos Matriculado**    | El alumno esta matriculado en el máster                                       |
| **Alumno Tomando Curso**   | El alumno toma el curso mientras pasa el tiempo                               |
| **Alumno Bajo Engagement** | Alumno con baja interacción y compromiso                                      |
| **Alumno Alto Engagement** | Alumno con alta interacción y compromiso                                      |
| **Abandono**               | Alumno deja la institución                                                    |
| **Solicitando Datos**      | Sistema solicitando datos de alumnos                                          |
| **Procesando Datos**       | Sistema procesa los datos de los alumnos                                      |
| **Interpretando Datos**    | Sistema interpreta los datos procesados y los almacena en clústers            |
| **Solicitando Datos**      | Sistema solicitando datos a entidad externa                                   |
| **Realizando acciones**    | Sistema realiza acciones para que alumno no abandone, esto también puede realizarse fuera del sistema                          |

</div>
  
|             Diagrama de estados alumno              |             Diagrama de estados sistema              |
| :-------------------------------------------------: | :--------------------------------------------------: |
| ![](03-DiagramaDeEstados/DiagramaEstadosAlumno.png) | ![](03-DiagramaDeEstados/DiagramaEstadosSistema.png) |


</details>

<hr>

[Atrás](../readme.md)
