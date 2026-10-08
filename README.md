# Modelo predictivo de demanda para la optimización de la planificación de producción e inventario en tres plantas de un grupo manufacturero

Proyecto Capstone — Maestría en Inteligencia de Negocios y Ciencia de Datos, Universidad de Las Américas (UDLA).

**Autora:** Brenda Nicole Reyes Vite · **Profesora:** María Isabel Mera Collantes · 2026

## Contenido

`ProyectoCapstone_Pronostico_Demanda.ipynb` — notebook de Google Colab (Python) con todo el flujo del estudio:

1. Limpieza, preprocesamiento y transformación de la Base madre de planificación y de la vista SAP.
2. Clasificación ABC (59 de 241 SKU, 90 % de la demanda) y anonimización de productos y plantas.
3. Identificación y visualización de variables (correlación de Spearman, línea base del proceso actual).
4. Modelado: LSTM, XGBoost (TimeSeriesSplit y GridSearchCV) y modelo híbrido LSTM-XGBoost.
5. Evaluación con MAE, RMSE, MAPE, WMAPE y MASE, por planta y por producto.

## Confidencialidad

Los datos de la organización **no se incluyen** en este repositorio. Los productos y plantas se presentan anonimizados (Producto 1…59, Planta 1…3).

## Herramientas

Python 3 · pandas · NumPy · scikit-learn · XGBoost · PyTorch · matplotlib · seaborn · SciPy · ydata-profiling
