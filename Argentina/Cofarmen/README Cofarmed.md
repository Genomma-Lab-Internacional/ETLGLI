# Datos Personales 

## Responsables del código

- Persona que desarrolló el código:

    | Nombres | Correos |
    |---------|---------|
    | Julio Ricardo Velazquez Hernandez | julio.velazquez@genommalab.com |

- Fecha de creación: *16-05-2021* <br>
- Desarrollado en Python 3.8.3


## Solicitantes

- Área que solicita: *Business Intelligence Argentina* <br>

- Personas que solicitan:

    | Nombres | Correos |
    |--------|--------|
    | Armando Martinez Gonzalez | armando.martinez@genommalab.com |
    | Francisco Jose Delfino | francisco.delfino@genommalab.com |

- Fecha de solicitud: *04-05-2021*


# Resumen

Proceso para transformar los datos de ventas y stock que nos comparte el cliente *Cofarmen* (ARG) al formato utilizado por ISV.
- Se leen los archivos de la carpeta compartida por Franciso Delfino, los nombres tienen el siguiente formato:
  - **AAAA_SS_Cofarmen_MDZA.xls**
  - **AAAA_SS_Cofarmen_SANJ.xls**

- Con los datos cargados se hace la tranformación y validación de datos para obtener un formato final.

- El formato final se escribe en un archivo excel:
  - Nombre: **Formato No B2B Cofarmen Sem {No. semana ejecutada}.xlsx**

# Código

## Cofarmen.ipynb
- Ubicación: 
- Archivo: **Cofarmen.ipynb**

## Parámetros Principales

- *file_names*: Es el nombre de los archivos a cargar, en una lista.