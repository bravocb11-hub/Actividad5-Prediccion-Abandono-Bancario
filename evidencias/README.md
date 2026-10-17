# Evidencias de ejecución

Esta carpeta reúne las evidencias generadas durante la ejecución del proyecto académico de predicción de abandono bancario, correspondiente a la Actividad 5 de Gestión de Proyectos de Inteligencia Artificial.

## Archivo principal

**Actividad5_evidencias_final.zip**

Este archivo contiene los resultados experimentales, los registros de seguimiento y los artefactos generados durante el entrenamiento y la evaluación de los modelos de clasificación.

## Contenido de las evidencias

- **MLflow:** base de datos `mlflow.db`, registros de ejecuciones y artefactos asociados.
- **Modelos:** archivos serializados de Regresión Logística y Random Forest.
- **Datos:** conjuntos originales y procesados utilizados en el experimento.
- **Resultados:** métricas de evaluación, matrices de confusión, comparaciones entre algoritmos y resultados de optimización de hiperparámetros.
- **Visualizaciones:** gráficas de calidad de datos, desempeño de modelos, análisis de umbrales e importancia de variables.
- **Trazabilidad:** manifiesto de archivos y resumen de experimentos.

## Resultados principales

| Modelo | Accuracy | F1 | ROC-AUC |
|---|---:|---:|---:|
| Regresión Logística | 0.7135 | 0.4987 | 0.7772 |
| Random Forest | 0.8365 | 0.6246 | 0.8614 |

En esta ejecución, Random Forest presentó el mejor desempeño global en las métricas analizadas.

## Consulta y reproducción

Para revisar las evidencias, descarga y descomprime `Actividad5_evidencias_final.zip`. El procedimiento de entrenamiento puede consultarse en el notebook disponible en `../notebooks/`.

Los resultados corresponden a una ejecución académica con datos públicos. No representan predicciones operativas sobre clientes reales.
