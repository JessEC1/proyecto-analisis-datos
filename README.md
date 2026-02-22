# Análisis Predictivo de California Housing
## **Objetivo del Proyecto**
Desarrollar un modelo de regresión para estimar el valor medio de viviendas en distritos de California utilizando variables socioeconómicas y geográficas, simulando un escenario de apoyo a decisiones en el sector inmobiliario.

## **Tecnologías utilizadas**
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn

## **Desarrollo**
- Carga del dataset desde sklearn.datasets.fetch_california_housing.
- Análisis Exploratorio de Datos (EDA) para evaluar distribución, correlaciones y comportamiento de variables.
- Identificación de multicolinealidad mediante matriz de correlación.
- Escalado de variables numéricas para optimización del modelo.

- Implementación de modelos de regresión: Linear Regression y Random Forest Regressor

- Evaluación del desempeño con: R² Score, Mean Squared Error (MSE) y Root Mean Squared Error (RMSE).

- Comparación de desempeño entre modelos.

## **Resultados**
- Random Forest mostró mejor desempeño predictivo frente a regresión lineal.
- Identificación de variables con mayor impacto en el precio:
MedInc (Ingreso medio) Latitude, Longitude y AveRooms
- El modelo permitió estimar valores inmobiliarios con margen de error controlado.

