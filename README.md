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



These files correspond to a part of my Master’s Thesis in Big Data & Data Science (IL3–University
of Barcelona, 2025). I developed an LSTM model to predict mortality due to respiratory diseases (at
the provincial level in Spain, 2000–2019), using air pollution indicators (NO₂, O₃, PM10, SO₂, PM2.5)
as input features.

Key characteristics of the work:
- Computation performed using an NVIDIA RTX 3080 Ti GPU.
- Feature scaling applied using StandardScaler.
- Implementation of a Stacked LSTM architecture.
- Model training using cross-validation with multiple folds.
- Hyperparameter tuning and best model selection based on MAE and RMSE.
- Province-level error analysis.
- Generation of a final model for predictive purposes.
- Visualization of model performance through diagnostic plots.
- Identification of the most influential input variables.
