Predicción de Precios de Itaú y Rotación de Clientes Bancarios

Este repositorio contiene dos proyectos de Machine Learning desarrollados como parte de un
trabajo de regresión y clasificación:

Modelo de Regresión — Precio de la acción de Itaú

Predicción del precio de cierre del día siguiente de la acción de Itaú (serie de tiempo 2002-2026), usando el precio de apertura, máximo, mínimo, volumen y cierre como variables predictoras. Se implementaron y compararon:
- Regresión por Mínimos Cuadrados Ordinarios (OLS), univariada y multivariada
- Gradiente descendiente para regresión polinomial, con una malla de valores variando el
  grado del polinomio y la tasa de aprendizaje
  

Modelo de Clasificación — Rotación de clientes bancarios (Churn)

Predicción de la deserción de clientes de un banco mediante Regresión Logística, a partir de variables como puntaje crediticio, edad, antigüedad, saldo, número de productos, actividad del cliente y salario estimado. El pipeline incluye:
- Análisis exploratorio de datos (EDA), matriz de correlación y detección de outliers
- Validación cruzada estratificada (K-Folds)
- Entrenamiento con `class_weight='balanced'`, priorizando el Recall sobre la Precision
  para minimizar la pérdida de clientes en riesgo

Tecnologías:

Python, NumPy, Pandas, scikit-learn, Matplotlib
