# Actividad 5 — Predicción de abandono bancario y MLOps

Proyecto académico de clasificación binaria, con dataset público de Kaggle `shantanudhakadd/bank-customer-churn-prediction`. No contiene información de clientes reales de una institución identificada.

## Reproducción
1. Acceder a la carpeta `notebooks/` del repositorio y abrir el archivo `Actividad_5_Gestión_de_Proyectos_de_Inteligencia_Artificial.ipynb` en Google Colab para reproducir el procedimiento experimental.
2. Reiniciar el entorno y ejecutar las celdas secuencialmente; se requiere conexión para instalar dependencias y obtener el dataset de Kaggle.
3. Revisar los archivos exportados y los experimentos de MLflow.
4. Para conservar la trazabilidad completa, guardar el ZIP de evidencias que exporta el notebook, con `mlflow.db`, `mlartifacts`, `modelos` y `datos`.

## Resultados verificados
- Regresión logística: ROC-AUC 0.777165, F1 0.498688.
- Random Forest: ROC-AUC 0.861421, F1 0.624569.
- Validación cruzada estratificada de cinco particiones y GridSearchCV.

## Organización
- notebooks/: contiene el notebook ejecutado Actividad_5_Gestión_de_Proyectos_de_Inteligencia_Artificial.ipynb, que integra la preparación y limpieza de datos, entrenamiento de modelos de clasificación, optimización de hiperparámetros mediante GridSearchCV, validación cruzada, evaluación comparativa y seguimiento de experimentos con MLflow.
- `resultados/`: tablas y figuras derivadas de la ejecución.
- `docs/`: reporte técnico.

## Precauciones
Los umbrales exploratorios se calcularon sobre el conjunto de prueba: no constituyen una selección independiente del umbral operativo. Los modelos serializados pueden requerir las mismas versiones de bibliotecas; cargar archivos Joblib/Skops solo de fuentes confiables. No subir datos reales de clientes ni secretos al repositorio.

## Guía por directorio
Cada directorio incluye su propio `README.md`, con descripción, archivos e instrucciones. Se incluyen datos originales y depurados para facilitar la evaluación académica. Coloca el ZIP de evidencias renombrado en `evidencias/` si su tamaño permite subirlo a GitHub (límite web de 25 MiB por archivo); de lo contrario, conserva el ZIP fuera del repositorio y documenta su ubicación de entrega.

## Dependencias
Consultar `requirements.txt`; para reproducibilidad estricta, usar también las versiones registradas en los artefactos de MLflow de la ejecución.
