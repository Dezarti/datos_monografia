# Desarrollo de un sistema de inteligencia artificial para la detección de apendicitis sobre Ecografía de abdomen.

## Seminario de Analítica y Ciencia de Datos

## Estudiantes
Alejandro Martínez Hernández

Rafael Reyes

## Resumen
Se hizo uso de una base de datos pública proporcionada por el Hospital  St. Hedwig en Regensburg, Alemania. Esta base de datos fue creada a partir de un estudio que recopiló y organizó información sobre una cohorte de pacientes pediátricos que presentaban dolor abdominal entre 2016 a 2021. Se poseen dos set de datos los cuales corresponden a datos estructurados y no estructurados. Por lo anterior se tomó la decisión de analizarlos separadamente y por ello se crearon dos archivos '.ipynb'. En ellos encontrará explicaciones del proceso que se hizo de análisis.

Se aclara que en el archivo Procesamiento_de_imágenes.ipynb los códigos adentro se ejecutaron locamente para facilitar el manejo, limpieza y procesamiento de los datos.

## Contenido

- **Análisis_de_datos.ipynb:** Análisis de datos estructurados. Aquí se encuentra el código y las decisiones que se tomaron para elegir los datos estructurados de importancia. 
- **Procesamiento_de_imágenes.ipynb:** Se encuentra los códigos junto a su respectiva explicación sobre el poqué y el cómo de su procesamiento. Para que los códigos corran se recomienda realizarlo localmente en archivos separados, tener las librerías que allí se usan instaladas y crear una estruuctura de carpetas igual a la que se encuentra en 'procesadas' dentro de 'us_images'. 
- **structured_data:** Contiene los datos estructurados del proyecto
- **us_images (carpeta):** Posee 2 carpetas
    1. ***originales:*** contiene todas las imágenes originales del estudio sin ningún cambio.
    2. ***procesadas:*** contiene las carpetas con las rutas que se especifican en los códigos. **Si se desea ejecutar los códigos de Procesamiento_de_imágenes.ipynb, se deebn cambiar las rutas que están dentro de la carpeta a los códigos, adicionalmente TODAS las carpetas deben estar vacías, pues al ejecutar los códigos estás se están llenando y vaciando continuamente**

## Base de datos original
Si por algún motivo se desea ingresar a la base de datos original, se puede dirigir [AQUÍ](https://zenodo.org/records/7711412)