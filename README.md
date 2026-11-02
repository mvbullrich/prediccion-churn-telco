# Predicción de abandono de clientes (Churn)

Trabajo práctico de la materia Tecnología Digital VI: Inteligencia Artificial (UTDT, 2026).
Integrantes: María Bullrich, Candela Guinzburg y Victoria Iasillo.

## Objetivo
Identificar con anticipación qué clientes de una empresa de telecomunicaciones tienen mayor probabilidad de abandonar el servicio, para orientar acciones de retención.

## Qué hicimos
- Análisis exploratorio sobre 7.043 clientes (tasas de churn por antigüedad, cargos, contrato y servicios).
- Limpieza de datos y creación de nuevas variables a partir del análisis.
- Modelo KNN con selección de variables (Forward/Backward) y prevención explícita de data leakage.
- Evaluación con Balanced Accuracy por el desbalance de clases, y comparación contra un modelo naive.
- Oversampling: el Recall subió del 53% al 73%, a costa de más falsos positivos. Analizamos qué modelo conviene según el costo de cada error.
- Reformulación del problema para predecir la contratación de soporte técnico (venta cruzada).

## Tecnologías
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter.

## Datos
Dataset público "Telco Customer Churn" (no incluido en el repositorio). Para ejecutar, colocar `telco.csv` en la misma carpeta que el notebook.
