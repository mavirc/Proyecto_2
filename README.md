# Proyecto_2
Realizar análisis exploratorios de datos (EDA) inicial para al menos cuatro conjuntos de datos, diagnosticar y elegir una problemática específica para abordar (regresión, clasificación, clusterización, predicción). 

1. Encuesta de Uso de Tabaco Juvenil (YTS)
Ventajas: Tiene datos de comportamiento y demografía. Podría usarse para predecir si alguien usa tabaco (clasificación) o el nivel de consumo (regresión).
Problemas:
Si hay pocos usuarios de tabaco, puede ser difícil entrenar un modelo.
Podría haber datos incompletos.
Los datos muestran correlaciones, pero no necesariamente causas

3. Calificaciones de Calidad de Aerolíneas
Ventajas: Tiene datos numéricos y categóricos que podrían servir para predecir calificaciones (regresión) o clasificar si la calidad es alta o baja (clasificación).
Problemas:
Las calificaciones pueden ser subjetivas o tener sesgos.
Algunas aerolíneas o años podrían tener pocos datos.
Factores externos, como el clima, no siempre están incluidos.

5. Ventas de Walmart
Ventajas: Los datos tienen variables como ventas, precios de combustible, y días festivos, ideales para hacer predicciones de ventas. Es útil para modelos de series temporales (como predecir ventas semanales).
Problemas:
Hay que manejar la estacionalidad y los efectos de los días festivos.
Puede haber datos faltantes.
Algunas variables podrían estar relacionadas (multicolinealidad), lo que complica el modelo.

7. Datos de COVID-19 en Condados de EE.UU.
Ventajas: Incluye datos geográficos y temporales. Puede usarse para predecir casos o muertes (regresión) o encontrar patrones en los condados (agrupamiento).
Problemas:
Puede haber datos incompletos o erróneos en los códigos de condados (fips).
Algunos condados tienen pocos casos, mientras que otros tienen muchos.
Factores externos (como políticas de estado o vacunas) no siempre están en el conjunto de datos.

Mejor Opción: Ventas de Walmart
Por qué: Es un conjunto de datos bien estructurado, con tareas claras para resolver (como predecir ventas). Además, es útil para aplicaciones prácticas en el mundo real.

Como ejecitar este notebook
Crear tu entorno virtual (si no deseas trabajar localmente):

Abre tu terminal o consola.
Navega al directorio de tu proyecto.
Crea el entorno virtual usando el siguiente comando
python -m venv nombre_del_entorno

Activa el entorno virtual:
En Windows:
nombre_del_entorno\Scripts\activate

Instalar los paquetes necesarios:

Si tienes un archivo requirements.txt en tu proyecto, puedes instalar todas las dependencias de una vez con:

pip install -r requirements.txt

Ejecutar el notebook

Autores: Daniela Riveros
