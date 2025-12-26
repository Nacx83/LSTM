# LSTM

Estos archivos corresponden a una parte de mi TFM de Big Data & Data Science (IL3-UB, 2025).
He creado una LSTM para intentar predecir las muertes por enfermedades respiratorias (a nivel provincial
en España 2000-2019) a partir de los niveles de contaminación del aire (NO2, O3, PM 10, SO2, PM 2.5).

Características del trabajo:
- Se usó una RTX 3080 Ti para la computación.
- Escalado de variables con StandardScaler.
- Implementación de una arquitectura Stacked LSTM.
- Entrenamiento con validación cruzada, folds.
- Ajuste de hiperparámetros y selección del mejor modelo con MAE y RMSE.
- Evaluación de errores por provincia.
- Generación de un modelo para predicciones.
- Gráficas para la visualización del rendimiento del modelo.
- Identificación de las variables con mayor influencia.
