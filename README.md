# Proyecto Ingeniería de Software

Repositorio para el proyecto de la asignatuea

## Rodrigo Zaldaña Calles (Cliente)

# Resumen

- Se desarrolla el modelo del dominio de una problemática propuesta por un cliente, la cual es, poder conocer el estado de un dispositivo conectado a una red, mediante una aplicación que sea capas de listar los dispositivos y las subredes en las que se encuentras estos y notificar al usuario cuando la red, las subredes y los dispositivos pierdan conexión.

# Introducción

- Gestionar la conexión de los dispositivos y VLans que componen una red perteneciente a una empresa u organización.

# Glosario

| Entidad     | Definición                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Usuario     | Todo aquel que interactúe con la aplicación, ya sea como administrador para gestionarla o como un usuario tecnico que desee ver información de las redes.                                                                 |
| Wan         | Es la entidad principal, es quien relaciona al resto de entidades. Una Wan se compone por proveedor, router, firewall, switch como elementos propios. Es gestionada por un usuario y los dispositivos se conectan a esta. |
| Ubicación   | Es el lugar físico en donde se encuentra la red.                                                                                                                                                                          |
| Router      | Dispositivo que provee a la red de conexión a internet también llamada Modem.                                                                                                                                             |
| Proveedor   | Compañía que presta el servicio de internet a la red se le puede conocer como "líniea fija" el cual tiene un número de referencia y un contrato.                                                                          |
| Firewall    | Dispositivo de seguridad que gestiona, es decir admite o no, el tráfico de información mediante la red e internet.                                                                                                        |
| Switch      | Es el dispositivo que reparte el tráfico de red a los dispositivos y que además crea VLans                                                                                                                                |
| VLan        | Son las redes locales en la cuales se dividen los dispositivos, dando ciertos accesos en la red a distintos dispositivos.                                                                                                 |
| Dispositivo | Hardware que al usuario le interesa conocer su estado, entre estos se encuentran: antenas, cámaras de vigilancia, lector de huellas, servidores, impresoras, teléfonos VoIP, Router y en casos muy puntuales móviles.     |

# Partes que componen una Red

- Proveedor
- Red
- Firewall
- Switch
- Dispositivos conectados

</br>

# Modelo de Dominio

|           Modelo de Dominio           |
| :-----------------------------------: |
| ![Imagen](images/ModeloDeDominio.png) |

# Diagrama de Objetos

|           Diagrama de Objetos           |
| :-------------------------------------: |
| ![Imagen](images/DiagramaDeObjetos.png) |

# Diagrama de Estados de una Notificación

- Diagrama de estados por las que pasa una Notificación

|                Diagrama de Estados                 |
| :------------------------------------------------: |
| ![Imagen](images/DiagramDeEstadosNotificacion.png) |

## Actores y Casos de Uso

# Actores

| Actor                 | Descripción                                    |
| --------------------- | ---------------------------------------------- |
| **Administrador**     | Gestiona redes, proveedores y usuarios         |
| **Técnicos internos** | Gestionan redes y proveedores                  |
| **Técnicos externos** | Ven redes                                      |
| **Tiempo**            | Notifica cuando la parte de una Red está caida |

# Casos de Uso

- Notificación:
  El sistema hace peticiones cada cierto tiempo a las partes de una Red para verificar su estado.
  Si un dispositivo está desconectado lanza una Notificación con la información del dispositivo

|                     |                        |
| ------------------- | ---------------------- |
| Nueva red           | Nuevo dispositivo      |
| Actualizar red      | Actualizar dispositivo |
| Eliminar red        | Eliminar dispositivo   |
| Listar redes        | Listar dispositivos    |
| Nuevo router        | Nuevo proveedor        |
| Actualizar router   | Actualizar proveedor   |
| Eliminar router     | Eliminar proveedor     |
| Listar routers      | Listar proveedores     |
| Nuevo firewall      | Nuevo usuario          |
| Actualizar firewall | Actualizar usuario     |
| Eliminar firewall   | Eliminar usuario       |
| Listar firewalls    | Listar usuarios        |
| Nuevo switch        | Obtener usuario        |
| Actualizar switch   | Notificación           |
| Eliminar switch     | Perfil                 |
| Listar switchs      |
| Nueva vlan          |
| Actualizar vlan     |
| Eliminar vlan       |
| Listar vlanes       |

|           Casos de Uso           |
| :------------------------------: |
| ![Imagen](images/casosDeUso.png) |

|          Casos de Uso Wan           |
| :---------------------------------: |
| ![Imagen](images/casosDeUsoRed.PNG) |

# Diagrama de Contexto

|           Diagrama de Contexto           |
| :--------------------------------------: |
| ![Imagen](images/diagramaDeContexto.PNG) |

# Especificacion Casos de Uso

|                  Login                   |
| :--------------------------------------: |
| ![Imagen](images/Especificacion_CdU.png) |

|                        Wan                         |
| :------------------------------------------------: |
| ![Imagen](images/EspecificacionCDU-Listar_Wan.png) |

|                         Router                         |
| :----------------------------------------------------: |
| ![Imagen](images/EspecificacionCDU2-Listar_Router.png) |

|                          Firewall                          |
| :--------------------------------------------------------: |
| ![Imagen](images/EspecificacionCDU2-Listar%20Firewall.png) |

|                         Switch                         |
| :----------------------------------------------------: |
| ![Imagen](images/EspecificacionCDU2-Listar_Switch.png) |

|                         Vlan                         |
| :--------------------------------------------------: |
| ![Imagen](images/EspecificacionCDU2-Listar_Vlan.png) |

|                        Dispositivos                         |
| :---------------------------------------------------------: |
| ![Imagen](images/EspecificacionCDU2-Listar_Dispositivo.png) |

|                Diagrama Principal                 |
| :-----------------------------------------------: |
| ![Imagen](images/EspecificacionCDU2-Pagina-1.png) |

# Prototipos de Interfaz de Usuario

|   Prototipo de Interfaz de Usuario    |
| :-----------------------------------: |
| ![Imagen](images/InterfazUsuario.png) |

</br>

## A continuación se presentan los prototipos de interfaz restantes que pertenecen a cada interfaz representada en la imagen anterior:

|                               Inicio                               |
| :----------------------------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/qmp7cvw1AAJAURXn51YuQ2.png) |

</br>

|                            Proveedores                             |
| :----------------------------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/f6C1B32qWcrCW12trXJmqd.png) |
| ![Imagen](https://share.balsamiq.com/c/tzaRYRHJo9fPx3Aqorr5hC.png) |
| ![Imagen](https://share.balsamiq.com/c/58BeanW9cqhcWJDJkMjHu2.png) |

</br>

|                               Redes                                |
| :----------------------------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/tw2FvaJL3JyDnXdU158sdp.png) |
| ![Imagen](https://share.balsamiq.com/c/d1f4wZAJrvThphGT7bWtX9.png) |
| ![Imagen](https://share.balsamiq.com/c/kzzvMU2JJkCyUs5Yj9eJ4C.png) |

</br>

|                       Parte de Red - Router                        |
| :----------------------------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/91h1J55qAteUKtMWJgAPVP.png) |
| ![Imagen](https://share.balsamiq.com/c/47f1kaTukKVyMJyq3thR7V.png) |
| ![Imagen](https://share.balsamiq.com/c/9x4eZFirKabLfa9uktNPPS.png) |

</br>

|                      Parte de Red - Firewall                       |
| :----------------------------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/9EW9Yu2XsDt3TEUNTwzzu7.png) |
| ![Imagen](https://share.balsamiq.com/c/wC9nMjo8hmXoB51CXCewFD.png) |
| ![Imagen](https://share.balsamiq.com/c/7FBgbTMYtrMgGYpqAyeyK5.png) |

</br>

|                       Partes de Red - Switch                       |
| :----------------------------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/eAN3QMb9mHtZ4JT2xM2aHY.png) |
| ![Imagen](https://share.balsamiq.com/c/s9BcouQXTTqPXRurwasLH5.png) |
| ![Imagen](https://share.balsamiq.com/c/ao54V5mATsWqSJXmXJHA7i.png) |

</br>

|                      Partes de una Red - Vlan                      |
| :----------------------------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/izjphcMMKoHt18NZvNi1No.png) |
| ![Imagen](https://share.balsamiq.com/c/vozNTvCz64x2oL5f7bRGGv.png) |
| ![Imagen](https://share.balsamiq.com/c/xftbNVJesjCBqmHUe99adZ.png) |

</br>

|                  Partes de una Red - Dispositivo                   |
| :----------------------------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/cMmCWpzKhGdCBvNEUxkvup.png) |
| ![Imagen](https://share.balsamiq.com/c/aQxmkefmJGZza48CN4Ajn9.png) |
| ![Imagen](https://share.balsamiq.com/c/vqXbY7ZVDETsZiA7aDKdYs.png) |

</br>

|                              Usuarios                              |
| :----------------------------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/72UcL2PLaJWuQ9SVwEVyCr.png) |
| ![Imagen](https://share.balsamiq.com/c/aVbAZ4sRHhfj5y2P6DRkbK.png) |
| ![Imagen](https://share.balsamiq.com/c/szEJ8Vdkya5mxb1TBzKXJ6.png) |

</br>

|                         Perfil de Usuario                          |
| :----------------------------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/6if66SbVvvhdRJPrR8iUgh.png) |
