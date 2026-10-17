# Registro de cambios

## v1.2 — Evidencia final
- Ejecución de ambos modelos y registro MLflow con SQLite.
- Exportación de modelos Joblib y artefactos Skops en ZIP de evidencias.
- Análisis exploratorio de umbrales e importancia por permutación.
- Reporte y estructura de repositorio preparados a partir de resultados reales.

## v1.1
- Correcciones de serialización e indentación.

## v1.0
- Preparación de datos, GridSearchCV y comparación inicial.

## Versión de documentación — 2026-10-17
- Se agregaron README específicos a cada directorio y subdirectorio de datos.
- Se incorporaron datos originales/depurados y un resumen exportado de MLflow.
- Se documentó la diferencia entre resumen de MLflow y respaldo completo de artefactos.

### v1.3 — Consolidación de la entrega final (2026-10-17)

- Se sustituyó el notebook anterior por la versión final ejecutada en Google Colab, conservando las salidas y visualizaciones del experimento.
- Se actualizó el archivo `notebooks/README.md` para identificar correctamente el notebook definitivo y explicar su procedimiento de reproducción.
- Se incorporó `Actividad5_evidencias_final.zip` como respaldo de los experimentos, modelos serializados, datos procesados, resultados y artefactos de MLflow.
- Se eliminó el archivo ZIP anterior para evitar duplicidades en la carpeta `evidencias/`.
- Se actualizó `evidencias/README.md` con la descripción del respaldo y los resultados comparativos de los modelos.
- Se revisó la coherencia de las métricas documentadas con los archivos exportados de la ejecución final.
