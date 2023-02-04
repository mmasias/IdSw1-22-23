# Actores y Casos de uso

## Encontrar actores y casos de uso 

Se han identificado 6 actores y 24 casos de uso y se han clasificado en casos de uso relacionados con Sesión, Revista, Artículo, Volúmen, Número.


### Actores
<div align="center">

| Actor         | Descripción                                                                     |
| ------------- | ------------------------------------------------------------------------------- |
| **Usuario**   | Persona registrada con cualquier tipo de rol de los permitidos por el programa. |
| **Gestor**    | Usuario con capacidades de gestión y moderación de la editorial y revistas.     |
| **Autor**     | Usuario que postula un artículo para su publicación.                            |
| **Traductor** | Usuario que puede traducir los artículos a castellano, inglés o portugués.      |
| **Revisor**   | Usuario que determina si un artículo postulado podrá ser publicado o no.        |
| **Editor**    | Usuario que da formato al artículo postulado una vez que ha sido aprobado.      |

</div>


### Casos de uso Identificados

<div align="center">

|                   |                    |                   | 
| ----------------- | ------------------ | ----------------- |
| Iniciar sesión    | Finalizar sesión   | Postular artículo |
| Publicar artículo | Modificar artículo | Eliminar artículo |
| Aprobar artículo  | Rechazar artículo  | Revisar artículo  |
| Traducir artículo | Ver artículo       | Modificar Volumen |
| Eliminar Volumen  | Crear Volumen      | Listar Números    |
| Modificar número  | Eliminar número    | Publicar número   |
| Crear número      | Ver Numero         | Ver Revista       |
| Eliminar Revista  | Modificar Revista  | Crear Revista     |

</div>


### Casos de Uso Por paquetes

<details>
  <summary>Artículo</summary>
  
![](EncontrarCasosDeUso/images/Articulo.png)
[Código](EncontrarCasosDeUso/articulo.puml)  

</details>

<details>
  <summary>Número</summary>
  
![](EncontrarCasosDeUso/images/Numero.png)
[Código](EncontrarCasosDeUso/numero.puml)  

</details>

<details>
  <summary>Volúmen</summary>
  
![](EncontrarCasosDeUso/images/Volumen.png)
[Código](EncontrarCasosDeUso/volumen.puml)  

</details>

<details>
  <summary>Revista</summary>
  
![](EncontrarCasosDeUso/images/Revista.png)
[Código](EncontrarCasosDeUso/articulo.puml)  

</details>

<details>
  <summary>Sesión</summary>
  
![](EncontrarCasosDeUso/images/Sesion.png)
[Código](EncontrarCasosDeUso/sesion.puml) 

</details>


### Diagrama de contexto

<div align="center">

|Diagrama de contexto
|:-:
|![](EncontrarCasosDeUso/images/DiagramaDeContexto.png)
|[Código](EncontrarCasosDeUso/DiagramaDeContexto.puml)

</div>

<hr>

## Priorizar Casos de Uso

1. Artículo
2. Número
3. Volúmen
4. Revista
5. Sesión

<hr>

## Detallar Casos de Uso

<hr>



[Atrás](../readme.md)