# Proyecto Ingeniería de Software

Repositorio para el proyecto de la asignatuea

## Rodrigo Zaldaña Calles (Cliente)

# Descripción del Proyecto

- Se desarrolla el modelo del dominio de una problemática propuesta por un cliente, la cual es, poder conocer el estado de un dispositivo conectado a una red, mediante una aplicación que sea capas de listar los dispositivos y las subredes en las que se encuentras estos y notificar al usuario cuando la red, las subredes y los dispositivos pierdan conexión.

# Objetivo principal

- Gestionar la conexión de los dispositivos y VLans que componen una red perteneciente a una empresa u organización.

# Partes que componen una red

- Proveedor
- Red
- Firewall
- Switch
- Dispositivos conectados

# Glosario

| Entidad     | Definición                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Usuario     | Todo aquel que interactúe con la aplicación, ya sea como administrador para gestionarla o como un usuario tecnico que desee ver información de las redes.                                                                 |
| Red         | Es la entidad principal, es quien relaciona al resto de entidades. Una red se compone por proveedor, router, firewall, switch como elementos propios. Es gestionada por un usuario y los dispositivos se conectan a esta. |
| Ubicación   | Es el lugar físico en donde se encuentra la red.                                                                                                                                                                          |
| Router      | Dispositivo que provee a la red de conexión a internet también llamada Modem.                                                                                                                                             |
| Proveedor   | Compañía que presta el servicio de internet a la red se le puede conocer como "líniea fija" el cual tiene un número de referencia y un contrato.                                                                          |
| Firewall    | Dispositivo de seguridad que gestiona, es decir admite o no, el tráfico de información mediante la red e internet.                                                                                                        |
| Switch      | Es el dispositivo que reparte el tráfico de red a los dispositivos y que además crea VLans                                                                                                                                |
| VLan        | Son las redes locales en la cuales se dividen los dispositivos, dando ciertos accesos en la red a distintos dispositivos.                                                                                                 |
| Dispositivo | Hardware que al usuario le interesa conocer su estado, entre estos se encuentran: antenas, cámaras de vigilancia, lector de huellas, servidores, impresoras, teléfonos VoIP, Router y en casos muy puntuales móviles.     |


# Diagramas

|           Modelo de Dominio           |
| :-----------------------------------: |
| ![Imagen](images/ModeloDeDominio.png) |

|           Diagrama de Objetos           |
| :-------------------------------------: |
| ![Imagen](images/DiagramaDeObjetos.png) |

|           Diagrama de Estados de Notificación         |
| :-------------------------------------: |
| ![Imagen](images/DiagramDeEstadosNotificacion.png) |

|           Diagrama de Contexto           |
| :-------------------------------------: |
| ![Imagen](images/diagramaDeContexto.PNG) |


# Actores y Casos de Uso

## Actores
| Actor                 | Descripción                            |
| --------------------- | -------------------------------------- |
| **Administrador**     | Gestiona redes, proveedores y usuarios |
| **Técnicos internos** | Gestionan redes y proveedores          |
| **Técnicos externos** | Ven redes                              |
| **Tiempo** | Notifica cuando la parte de una Red está caida    |

## Casos de Uso

|                      |                      |
| -------------------- | -------------------- |
|       nueva red      |  nuevo dispositivo   |
|     actualizar red   |actualizar dispositivo|
|      eliminar red    | eliminar dispositivo |
|     listar redes     | listar dispositivos  |
|     nuevo router     |    nuevo proveedor   |
|   actualizar router  | actualizar proveedor |
|    eliminar router   |  eliminar proveedor  |
|    listar routers    |  listar proveedores  |
|    nuevo firewall    |    nuevo usuario     |
| actualizar firewall  |  actualizar usuario  |
|   eliminar firewall  |   eliminar usuario   |
|   listar firewalls   |   listar usuarios    |
|    nuevo switch      |        perfil        |
|  actualizar switch   |     notificación     |
|   eliminar switch    |
|    listar switchs    |
|      nueva vlan      |
|    actualizar vlan   |
|     eliminar vlan    |
|    listar vlanes     |

* Notificación:
El sistema hace peticiones cada cierto tiempo a las partes de una Red para verificar su estado.
Si un dispositivo está desconectado lanza una Notificación con la información del dispositivo


|           Casos de Uso           |
| :------------------------------: |
| ![Imagen](images/CasosDeUso.png) |
|![Imagen](images/CasosDeUsoRed.png)|

<!-- # Mockups

Enlace a los mockups en Balsamiq: <https://balsamiq.cloud/smsb541/pds9efr/rC71E>

|                  Inicio                  |
| :--------------------------------------: |
|   ![Imagen](https://share.balsamiq.com/c/wkkCjzvRoVbGHouhwBv9fP.png)   |
| ![Imagen](https://share.balsamiq.com/c/qmp7cvw1AAJAURXn51YuQ2.png) |

|            Proveedores             |
| :---------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/jurFUvf9twDWhXiyigdid4.png) |
| ![Imagen](https://share.balsamiq.com/c/f6C1B32qWcrCW12trXJmqd.png) |
| ![Imagen](https://share.balsamiq.com/c/tzaRYRHJo9fPx3Aqorr5hC.png) |
| ![Imagen](https://share.balsamiq.com/c/58BeanW9cqhcWJDJkMjHu2.png) |

|            Redes             |
| :---------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/91D4B9SqubVVaouMsbP91U.png) |
| ![Imagen](https://share.balsamiq.com/c/tw2FvaJL3JyDnXdU158sdp.png) |
| ![Imagen](https://share.balsamiq.com/c/d1f4wZAJrvThphGT7bWtX9.png) |
| ![Imagen](https://share.balsamiq.com/c/kzzvMU2JJkCyUs5Yj9eJ4C.png) |

|             Parte de Red - Router             |
| :---------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/1iFW9VbrNjUstZ4wLCAHEk.png) |
| ![Imagen](https://share.balsamiq.com/c/91h1J55qAteUKtMWJgAPVP.png) |
| ![Imagen](https://share.balsamiq.com/c/47f1kaTukKVyMJyq3thR7V.png) |
| ![Imagen](https://share.balsamiq.com/c/9x4eZFirKabLfa9uktNPPS.png) |

|             Parte de Red - Firewall             |
| :-----------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/vk8amV1FZwH96TaWbfwukK.png) |
| ![Imagen](https://share.balsamiq.com/c/9EW9Yu2XsDt3TEUNTwzzu7.png) |
| ![Imagen](https://share.balsamiq.com/c/wC9nMjo8hmXoB51CXCewFD.png) |
| ![Imagen](https://share.balsamiq.com/c/7FBgbTMYtrMgGYpqAyeyK5.png) |


|             Partes de Red - Switch             |
| :---------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/okU94FuTjH46QeJqCjwpoe.png) |
| ![Imagen](https://share.balsamiq.com/c/eAN3QMb9mHtZ4JT2xM2aHY.png) |
| ![Imagen](https://share.balsamiq.com/c/s9BcouQXTTqPXRurwasLH5.png) |
| ![Imagen](https://share.balsamiq.com/c/ao54V5mATsWqSJXmXJHA7i.png) |


|             Partes de una Red - Vlan             |
| :-------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/65G1xnmvHfAPw58scR4mtj.png) |
| ![Imagen](https://share.balsamiq.com/c/izjphcMMKoHt18NZvNi1No.png) |
| ![Imagen](https://share.balsamiq.com/c/vozNTvCz64x2oL5f7bRGGv.png) |
| ![Imagen](https://share.balsamiq.com/c/xftbNVJesjCBqmHUe99adZ.png) |

|             Partes de una Red - Dispositivo             |
| :---------------------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/uSYFmtqhTtUjwjuvSc5jt3.png) |
| ![Imagen](https://share.balsamiq.com/c/cMmCWpzKhGdCBvNEUxkvup.png) |
| ![Imagen](https://share.balsamiq.com/c/aQxmkefmJGZza48CN4Ajn9.png) |
| ![Imagen](https://share.balsamiq.com/c/vqXbY7ZVDETsZiA7aDKdYs.png) |


|          Usuarios          |
| :-----------------------------: |
| ![Imagen](https://share.balsamiq.com/c/2TXWKLEtjVCZnEsunCaqF6.png) |
| ![Imagen](https://share.balsamiq.com/c/72UcL2PLaJWuQ9SVwEVyCr.png) |
| ![Imagen](https://share.balsamiq.com/c/aVbAZ4sRHhfj5y2P6DRkbK.png) |
| ![Imagen](https://share.balsamiq.com/c/szEJ8Vdkya5mxb1TBzKXJ6.png) |


|          Perfil de Usuario           |
| :----------------------------------: |
| ![Imagen](https://share.balsamiq.com/c/6if66SbVvvhdRJPrR8iUgh.png) | -->
