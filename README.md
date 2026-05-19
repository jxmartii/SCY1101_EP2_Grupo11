# SCY1101_EP2_Grupo11

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jxmartii/SCY1101_EP2_GRUPO11)

## Estructura del Proyecto

El repositorio está organizado bajo estándares profesionales de desarrollo de software y reproducibilidad científica:

* **data/**: Contiene los sets de datos en formato CSV (datos base y datos con etiquetas de clústeres).
* **models/trained_models/**: Almacena los modelos predictivos finales entrenados y serializados en formato `.pkl` (Decision Tree y Random Forest).
* **notebooks/**: Cuadernos interactivos de Jupyter ordenados secuencialmente por fases experimentales (desde el análisis exploratorio hasta la optimización avanzada).
* **results/**: Carpeta destinada a los entregables y salidas automáticas del sistema:
  * **metrics/**: Evaluaciones numéricas y tablas comparativas de rendimiento en formato CSV.
  * **plots/**: Visualizaciones gráficas, importancia de variables y matrices de confusión exportadas.
  * **reports/**: Espacio oficial donde se almacena el **Informe Técnico Académico** definitivo del proyecto en formato PDF.
* **src/**: Módulos de código auxiliar y funciones de Python (`.py`) para asegurar la modularización y limpieza del proyecto.