# Predicción de Retrasos de Vuelos con Spark

Este proyecto utiliza Apache Spark para analizar y predecir retrasos en vuelos utilizando el dataset de historial de vuelos. La finalidad es demostrar cómo manejar grandes volúmenes de datos y aplicar técnicas de aprendizaje automático para resolver problemas reales.

El análisis se llevó a cabo en un entorno de **Google Cloud**, utilizando:
- Un **bucket** de Google Cloud Storage para almacenar el dataset de vuelos.
- Un **cluster** de Apache Spark creado en Google Cloud Dataproc para realizar el procesamiento distribuido de los datos.
  
## Archivos incluidos

- **`spark_flight_delay_prediction.ipynb`**: Notebook que contiene el preprocesamiento, análisis y modelo predictivo. Así como una guía explicativa de los pasos realizados a lo largo de todo el proyecto.
- **`flights.csv`**: Dataset utilizado en el análisis.

## Requisitos previos

Para ejecutar el proyecto necesitas:

1. **Python**: Versión 3.8 o superior.
2. **Apache Spark**: Instalado y configurado en tu sistema.
3. **Bibliotecas adicionales**: Instálalas con el siguiente comando:
   ```bash
   pip install pyspark 

