# Actores y Casos de uso

## Encontrar actores y casos de uso 

Se han identificado 6 actores y 24 casos de uso y se han clasificado en casos de uso relacionados con Sesión, Revista, Artículo, Volumen, Número.


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
<br/>
[Código](EncontrarCasosDeUso/articulo.puml)  

</details>

<details>
  <summary>Número</summary>
  
![](EncontrarCasosDeUso/images/Numero.png)
<br/>
[Código](EncontrarCasosDeUso/numero.puml)  

</details>

<details>
  <summary>Volúmen</summary>
  
![](EncontrarCasosDeUso/images/Volumen.png)
<br/>
[Código](EncontrarCasosDeUso/volumen.puml)  

</details>

<details>
  <summary>Revista</summary>
  
![](EncontrarCasosDeUso/images/Revista.png)
<br/>
[Código](EncontrarCasosDeUso/revista.puml)  

</details>

<details>
  <summary>Sesión</summary>
  
![](EncontrarCasosDeUso/images/Sesion.png)
<br/>
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
3. Volumen
4. Revista
5. Sesión

<hr>

## Detallar Casos de Uso

<details>
  <summary>Paquete Artículo</summary>

  <details>
    <summary>Ver Artículo</summary>
    
  ![](DetallarCasosDeUso/images/VerArticulo.png)
  <br/>
  [Código](DetallarCasosDeUso/VerArticulo.puml) 

  </details>

  <details>
    <summary>Revisar Artículo</summary>
    
  ![](DetallarCasosDeUso/images/RevisarArticulo.png)
  <br/>
  [Código](DetallarCasosDeUso/RevisarArticulo.puml) 

  </details>

  <details>
    <summary>Rechazar Artículo</summary>
    
  ![](DetallarCasosDeUso/images/RechazarArticulo.png)
  <br/>
  [Código](DetallarCasosDeUso/RechazarArticulo.puml) 

  </details>

  <details>
    <summary>Aprobar Artículo</summary>
    
  ![](DetallarCasosDeUso/images/AprobarArticulo.png)
  <br/>
  [Código](DetallarCasosDeUso/AprobarArticulo.puml) 

  </details>

  <details>
    <summary>Traducir Artículo</summary>
    
  ![](DetallarCasosDeUso/images/TraducirArticulo.png)
  <br/>
  [Código](DetallarCasosDeUso/TraducirArticulo.puml) 

  </details>

  <details>
    <summary>Modificar Articulo</summary>
    
  ![](DetallarCasosDeUso/images/ModificarArticulo.png)
  <br/>
  [Código](DetallarCasosDeUso/ModificarArticulo.puml) 

  </details>

  <details>
    <summary>Eliminar Artículo</summary>
    
  ![](DetallarCasosDeUso/images/EliminarArticulo.png)
  <br/>
  [Código](DetallarCasosDeUso/EliminarArticulo.puml) 

  </details>

  <details>
    <summary>Publicar Artículo</summary>
    
  ![](DetallarCasosDeUso/images/PublicarArticulo.png)
  <br/>
  [Código](DetallarCasosDeUso/PublicarArticulo.puml) 

  </details>

  <details>
    <summary>Postular Artículo</summary>
    
  ![](DetallarCasosDeUso/images/PostularArticulo.png)
  <br/>
  [Código](DetallarCasosDeUso/PostularArticulo.puml) 

  </details>

</details>

<br/>

<details>
  <summary>Paquete Número</summary>

  <details>
    <summary>Ver Número</summary>
    
  ![](DetallarCasosDeUso/images/VerNumero.png)
  <br/>
  [Código](DetallarCasosDeUso/VerNumero.puml) 

  </details>

  <details>
    <summary>Listar Números</summary>
    
  ![](DetallarCasosDeUso/images/ListarNumeros.png)
  <br/>
  [Código](DetallarCasosDeUso/ListarNumeros.puml) 

  </details>

  <details>
    <summary>Publicar número</summary>
    
  ![](DetallarCasosDeUso/images/PublicarNumero.png)
  <br/>
  [Código](DetallarCasosDeUso/PublicarNumero.puml) 

  </details>

  <details>
    <summary>Eliminar Número</summary>
    
  ![](DetallarCasosDeUso/images/EliminarNumero.png)
  <br/>
  [Código](DetallarCasosDeUso/EliminarNumero.puml) 

  </details>

  <details>
    <summary>Modificar Número</summary>
    
  ![](DetallarCasosDeUso/images/ModificarNumero.png)
  <br/>
  [Código](DetallarCasosDeUso/ModificarNumero.puml) 

  </details>

  <details>
    <summary>Crear Número</summary>
    
  ![](DetallarCasosDeUso/images/CrearNumero.png)
  <br/>
  [Código](DetallarCasosDeUso/CrearNumero.puml) 

  </details>

</details>

<br/>

<details>
  <summary>Paquete Volumen</summary>

  <details>
  <summary>Eliminar Volumen</summary>
  
  ![](DetallarCasosDeUso/images/EliminarVolumen.png)
  <br/>
  [Código](DetallarCasosDeUso/EliminarVolumen.puml) 

  </details>

  <details>
    <summary>Modificar Volumen</summary>
    
  ![](DetallarCasosDeUso/images/ModificarVolumen.png)
  <br/>
  [Código](DetallarCasosDeUso/ModificarVolumen.puml) 

  </details>

  <details>
    <summary>Crear Volumen</summary>
    
  ![](DetallarCasosDeUso/images/CrearVolumen.png)
  <br/>
  [Código](DetallarCasosDeUso/CrearVolumen.puml) 

  </details>

</details>

<br/>

<details>
  <summary>Paquete Revista</summary>

  <details>
    <summary>Leer Revista</summary>
    
  ![](DetallarCasosDeUso/images/LeerRevista.png)
  <br/>
  [Código](DetallarCasosDeUso/LeerRevista.puml) 

  </details>

  <details>
    <summary>Crear Revista</summary>
    
  ![](DetallarCasosDeUso/images/CrearRevista.png)
  <br/>
  [Código](DetallarCasosDeUso/CrearRevista.puml) 

  </details>

  <details>
    <summary>Modificar Revista</summary>
    
  ![](DetallarCasosDeUso/images/ModificarRevista.png)
  <br/>
  [Código](DetallarCasosDeUso/ModificarRevista.puml) 

  </details>

  <details>
    <summary>Eliminar Revista</summary>
    
  ![](DetallarCasosDeUso/images/EliminarRevista.png)
  <br/>
  [Código](DetallarCasosDeUso/EliminarRevista.puml) 

  </details>
  
</details>

<br/>

<details>
  <summary>Paquete Sesión</summary>

  <details>
    <summary>Iniciar Sesión</summary>
    
  ![](DetallarCasosDeUso/images/IniciarSesion.png)
  <br/>
  [Código](DetallarCasosDeUso/IniciarSesion.puml) 

  </details>

  <details>
    <summary>Finalizar Sesión</summary>
    
  ![](DetallarCasosDeUso/images/FinalizarSesion.png)
  <br/>
  [Código](DetallarCasosDeUso/FinalizarSesion.puml) 

  </details>

</details>

<hr>

[Atrás](../readme.md)