# Notebook de entrenamiento y evaluación

Esta carpeta contiene el notebook final ejecutado de la Actividad 5 de Gestión de Proyectos de Inteligencia Artificial.

## Archivo principal

`Actividad_5_Gestión_de_Proyectos_de_Inteligencia_Artificial.ipynb`

## Descripción

El notebook desarrolla un proyecto académico de predicción de abandono bancario a partir de un conjunto de datos público de Kaggle.

Se documentan la preparación y limpieza de datos, el análisis exploratorio, la construcción de pipelines de preprocesamiento y el entrenamiento de dos modelos de clasificación: Regresión Logística y Random Forest.

La optimización de hiperparámetros se realiza mediante GridSearchCV y validación cruzada estratificada de cinco particiones.

## Evaluación de modelos

Los algoritmos se comparan mediante accuracy, precision, recall, F1 y ROC-AUC. También se incluyen matrices de confusión, análisis exploratorio de umbrales e importancia de variables por permutación.

## Seguimiento de experimentos

El notebook utiliza MLflow para registrar los parámetros, las métricas y los artefactos de los experimentos.

Las evidencias complementarias se encuentran en `../evidencias/` y los resultados exportados en `../resultados/`.

## Reproducción del experimento

1. Abrir el notebook en Google Colab.
2. Instalar las dependencias indicadas.
3. Ejecutar las celdas en orden.
4. Revisar las métricas, gráficas y registros de MLflow.
5. Descargar el ZIP de evidencias generado.

Los resultados corresponden a una ejecución académica y pueden variar si cambian los datos, las dependencias o la configuración del entorno.
