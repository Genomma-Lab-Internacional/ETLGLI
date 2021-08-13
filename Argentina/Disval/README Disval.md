# Datos Personales 

## Responsables del código

- Persona que desarrolló el código:

    | Nombres | Correos |
    |---------|---------|
    | Jesús Sabdiel Hernández Morales | jesus.hernandez@genommalab.com |

- Fecha de creación: *13-05-2021*

- Desarrollado en Python 3.8.10


## Solicitantes

- Área que solicita: *Business Intelligence Argentina* <br>

- Personas que solicitan:

    | Nombres | Correos |
    |--------|--------|
    | Armando Martinez Gonzalez | armando.martinez@genommalab.com |
    | Francisco Jose Delfino | francisco.delfino@genommalab.com |

- Fecha de solicitud: *04-05-2021*


# Resumen

El cliente *Disval* (ARG) le comparte su información de SO y Stock en archivos txt a Francisco Jose Delfino.

Francisco nos compartió las carpetas por OneDrive en donde guarda esta información.

Este código toma estos datos desde sus carpeta para su transformación a un formato estandarizado, para que después se envíe por correo al proveedor ISV.


# Código

## Nombre del script

Dónde podemos encontrar el código:

- Carpeta: 
- Archivo: **Disval.ipynb**

## Parámetros Principales
- *year*: Año de la información a procesar.
- *week*: Semana Genomma Lab de la información a procesar.
- *path*: Ruta de la carpeta compartida de Francisco.

## Conexiones e Importaciones

Se necesita permisos para la conexión a las siguientes bases de datos:

### Primera conexión
- Servidor: SFEDWH01
- Base de datos: Gnm_DWH
- Tabla: Dim_Tiempo

### Segunda conexión
- Servidor: SFEDWH01
- Base de datos: Gnm_MasterOp
- Tabla1: vw_EstructuraSucursalesTotal
- Tabla2: vw_EstructuraClientesSegPTVTotal
