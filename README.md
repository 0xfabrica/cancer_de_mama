# Predicción de Cáncer de Mama

Este proyecto tiene como objetivo desarrollar un modelo de aprendizaje automático para predecir el diagnóstico de cáncer de mama (benigno o maligno) utilizando un conjunto de datos clínicos.

## Descripción

El modelo se construyó utilizando el algoritmo RandomForestClassifier de la biblioteca scikit-learn en Python. Se entrenó con un conjunto de datos que contiene información sobre características de tumores de mama. El objetivo es predecir si un tumor es benigno o maligno con la mayor precisión posible.

## Características

*   Preprocesamiento de datos: limpieza y preparación del conjunto de datos.
*   Ingeniería de características: selección y transformación de variables relevantes.
*   Entrenamiento del modelo: utilizando RandomForestClassifier.
*   Evaluación del modelo: utilizando métricas como precisión, recall y F1-score.
*   Función de predicción: permite predecir el diagnóstico para nuevos datos.
*   Visualizaciones: gráficos para explorar los datos y los resultados del modelo.


## Requisitos

*   Python 3.x
*   Pandas
*   NumPy
*   Scikit-learn
*   Matplotlib


## Instalación

1.  Clona este repositorio: `git clone [URL del repositorio]`
2.  Instala las bibliotecas necesarias: `pip install -r requirements.txt`
3.  Descarga el conjunto de datos "data\_cancer\_teta.csv" y colócalo en la carpeta del proyecto.


## Uso

1.  Abre el notebook `cancer_prediction.ipynb` en Google Colab o Jupyter Notebook.
2.  Ejecuta las celdas para preprocesar los datos, entrenar el modelo y evaluar su rendimiento.
3.  Utiliza la función `predecir_cancer()` para realizar predicciones sobre nuevos datos.
4.  Explora las visualizaciones para comprender mejor los datos y los resultados del modelo.


## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún error o tienes alguna sugerencia, por favor, crea un issue o envía un pull request.
