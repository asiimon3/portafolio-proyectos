# Mejora de Imágenes en Escenas de Baja Iluminación

Este proyecto explora diversas técnicas de procesamiento digital para mejorar imágenes capturadas en condiciones de baja iluminación. Se aplican transformaciones como ecualización de histograma, CLAHE, transformación logarítmica, corrección gamma y operador de multiplicación para optimizar la calidad visual y la utilidad de las imágenes. Además, se evalúan métricas objetivas para comparar el impacto de cada técnica

## Objetivo
Demostrar cómo diferentes técnicas de mejora de imágenes pueden aplicarse a escenas complejas para mejorar su interpretabilidad, utilizando herramientas de visión por computador y análisis cuantitativo.

## Archivos Incluidos
- `image_processing_notebook.ipynb`: Notebook que contiene el flujo completo del proyecto, incluyendo la implementación de las técnicas de mejora, cálculo y análisis de las métricas de calidad y visualización de los resultados.
- `image`: datasets (`The Dark Face`) de imágenes de baja iluminación procedente de la plataforma Kaggle.
- `metrics_table_with_multiplication.csv`: Tabla generada que contiene las métricas para cada técnica aplicada.

  ## Requisitos Previos
Para ejecutar este proyecto necesitas:
- **Python**: Versión 3.8 o superior.
- **Bibliotecas necesarias**: Instala las siguientes dependencias:
  ```bash
  pip install numpy pandas matplotlib scikit-image opencv-python
