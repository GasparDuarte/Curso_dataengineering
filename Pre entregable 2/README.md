Desafío del Proyecto

El desafío de este proyecto es cargar datos sobre criptomonedas desde una API externa a una base de datos en Amazon Redshift utilizando Python. El objetivo es mantener actualizados los datos de criptomonedas en la base de datos para su posterior análisis.

Pasos para Reproducir el Código

1)Descargar el Código: Descarga el código fuente del proyecto desde el repositorio.

2)Instalar las Dependencias: Asegúrate de tener Python instalado en tu sistema. Luego, instala las dependencias necesarias ejecutando el archivo Requirements.txt

3)Configurar las Variables de Entorno: Crea un archivo .env en el directorio del proyecto y define las variables de entorno necesarias para la conexión a la base de datos. Puedes seguir el ejemplo proporcionado en el archivo sample-dot-env.

4)Utilizar el Script SQL para Crear la Tabla: Utiliza el script creacion_tabla_crypto_data.sql para crear la tabla crypto_data en tu base de datos en Amazon Redshift.

5)Ejecutar el Script: Ejecuta el script Preentrega2.py en tu entorno de desarrollo utilizando Python.

6)Verificar los Datos: Accede a tu base de datos en Amazon Redshift para verificar que los datos se hayan cargado correctamente en la tabla crypto_data.
