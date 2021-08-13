# Datos Personales 

## Responsables del código

- Persona que creó el código:

    | Nombres | Correos |
    |---------|---------|
    | Julio Ricardo Velazquez Hernandez | julio.velazquez@genommalab.com |

- Fecha de creación: *04-05-2021* <br>
- Desarrollado en Python 3.8.3


## Solicitantes

- Área que solicita: Business Intelligence Argentina

- Personas que solicitan:

    | Nombres | Correos |
    |---------|---------|
    | Armando Martinez Gonzalez | armando.martinez@genommalab.com |
    | Francisco Jose Delfino | francisco.delfino@genommalab.com |

- Fecha de solicitud: 10-05-2021


# Resumen

- Proceso para transformar los datos de ventas y stock que nos comparte el cliente *Sumed* (ARG) al formato utilizado por ISV.
- Se leen los archivos de la carpeta compartida por Franciso Delfino, los nombres tienen el siguiente formato:
  - **AAAA_SS_Sumed_SO.xls**

- Con los datos cargados se hace la tranformación y validación de datos para obtener un formato final.

- El formato final se escribe en un archivo excel:
  - Nombre: **Formato No B2B Sumed Sem {No. semana ejecutada}.xlsx**

# Código

## Sumed.ipynb

- Ubicación: 
- Archivo: **Sumed.ipynb**
## Parámetros Principales

- *file_names*: Es el nombre de los archivos a cargar, en una lista.