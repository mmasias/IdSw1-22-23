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

# Requisitado Sesión 1

|   Partes que conforman una Red    |
| :-------------------------------: |
| ![Imagen](images/ContieneRed.PNG) |

| Roles de Usuarios que se necesitan  |
| :---------------------------------: |
| ![Imagen](images/RolesUsuarios.PNG) |

# Requisitado Sesión 2

|          Que es una red           |
| :-------------------------------: |
| ![Imagen](images/ContieneRed.PNG) |

|  Definicion flujo de una red   |
| :----------------------------: |
| ![Imagen](images/QueEsRed.PNG) |

# Diagramas

|           Modelo de Dominio           |
| :-----------------------------------: |
| ![Imagen](images/ModeloDeDominio.png) |

|           Diagrama de Objetos           |
| :-------------------------------------: |
| ![Imagen](images/DiagramaDeObjetos.png) |

|           Diagrama de Estados           |
| :-------------------------------------: |
| ![Imagen](images/DiagramaDeEstados.png) |

|           Casos de Uso           |
| :------------------------------: |
| ![Imagen](images/casosDeUso.png) |

## Actores

<div align="center">

| Actor                 | Descripción                            |
| --------------------- | -------------------------------------- |
| **Administrador**     | Gestiona redes, proveedores y usuarios |
| **Técnicos internos** | Gestionan redes y proveedores          |
| **Técnicos externos** | Ven redes                              |

</div>

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

# Mockups

|                  Inicio                  |
| :--------------------------------------: |
|   ![Imagen](mockups/inicioUsuario.PNG)   |
| ![Imagen](mockups/ContrasenaUsuario.png) |

|            Listar Proveedores             |
| :---------------------------------------: |
| ![Imagen](mockups/ListadoProveedores.png) |

|            Crear Proveedor            |
| :-----------------------------------: |
| ![Imagen](mockups/NuevoProveedor.png) |

|            Listar Redes             |
| :---------------------------------: |
| ![Imagen](mockups/ListadoRedes.png) |

|             Routes de una Red             |
| :---------------------------------------: |
| ![Imagen](mockups/PartesDeRed-Router.png) |

|             Firewall de una Red             |
| :-----------------------------------------: |
| ![Imagen](mockups/PartesDeRed-Firewall.png) |

|             Switch de una Red             |
| :---------------------------------------: |
| ![Imagen](mockups/PartesDeRed-Switch.png) |

|             Vlan de una Red             |
| :-------------------------------------: |
| ![Imagen](mockups/PartesDeRed-Vlan.png) |

|             Dispositivos de una Red             |
| :---------------------------------------------: |
| ![Imagen](mockups/PartesDeRed-Dispositivos.png) |

|          Crear una Red          |
| :-----------------------------: |
| ![Imagen](mockups/NuevaRed.png) |

|                  Crear Router                  |
| :--------------------------------------------: |
| ![Imagen](mockups/PartesDeRed-NuevoRouter.png) |

|                  Crear Firewall                  |
| :----------------------------------------------: |
| ![Imagen](mockups/PartesDeRed-NuevoFirewall.png) |

|                  Crear Switch                  |
| :--------------------------------------------: |
| ![Imagen](mockups/PartesDeRed-NuevoSwitch.png) |

|                  Crear Vlan                  |
| :------------------------------------------: |
| ![Imagen](mockups/PartesDeRed-NuevoVlan.png) |

|                 Crear Dispositivos                  |
| :-------------------------------------------------: |
| ![Imagen](mockups/PartesDeRed-NuevoDispositivo.png) |

|            Listar Usuarios             |
| :------------------------------------: |
| ![Imagen](mockups/ListadoUsuarios.png) |

|            Crear Usuario            |
| :---------------------------------: |
| ![Imagen](mockups/NuevoUsuario.png) |

|          Perfil de Usuario           |
| :----------------------------------: |
| ![Imagen](mockups/PerfilUsuario.png) |
