# Análisis de Deforestación en el Bosque Nacional Jamanxim (Brasil)

En este proyeccto se analiza el aumento de la deforestación en el Bosque Nacional Jamanxim (Brasil) entre los años 2001 al 2019, a partir de imágenes satelitales. Con la implentención de un pipeline en varias etapas para realizar el procesamiento adecuado de las imágenes, tratando la eliminación de interferencias, segmentación de deforestación y calculo del área afectada.

## Objetivo

Estudiar diferentes técnicas de procesamiento de imágenes para realizar una segmentación apropiada a las condiciones presentes en las imágenes del Boseque Nacional Jamanxim, y comprobar análiticamente el deterioro.

## Archivos Incluidos

- `DeforestaciónAnálisis.ipynb`: Notebook que contiene el flujo del estudio, incluyendo la implementación del pipeline, el cálculo y análisis del área deforestada, así como una gruía explicativa de los pasos seguidos en el procesamiento. 
- `images.gif`: 20 imágenes en formato GIF del cambio en la deforestación entre el 2000 y el 2019.

## Requisitos Previos
Para ejecutar este proyecto necesitas:
- **Python**: Versión 3.8 o superior.
- **Bibliotecas necesarias**: Instala las siguientes dependencias:
  ```bash
  pip install numpy matplotlib PIL IPython os opencv-python
