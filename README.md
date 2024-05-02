# ML_Inflacion_Mexico
Estimación de la inflación en México utilizando técnicas clásicas de Aprendizaje de Máquina y con datos del INEGI y Banxico


## Versiones y librerías utilizadas:
- Python 3.10.2
- lightgbm 4.3.0
- matplotlib 3.5.1
- numpy 1.22.3
- pandas 1.4.2
- seaborn 0.11.2
- sklearn 1.1.2
- statsmodels 0.13.2
- xgboost 2.0.3

## Modelos entrenados:

- Regresión Lineal de Mínimos Cuadrados
- Regresión Ridge
- Regresión LASSO
- Árbol de Decisión
- Bosque Aleatorio
- XGBoost

## Descripción de archivos:

1. AprendizajeMaquina_Estimacion_InflacionMexico.ipynb: Jupyter Notebook que contiene el flujo completo del experimento realizado. Se incliyen los pasos de importación de insumos, tratamiento inicial de datos, optimización de hiperparámetros, entrenamiento de modelos optimizados, simulación de predicción y validación de resultados.

2. AprendizajeMaquina_Estimacion_InflacionMexico_EDA.ipynb: Jupyter Notebook que contiene el Análisis Exploratorio de datos de nuestro insumo de entrenamiento y prueba.

3. sabana_analitica.csv: Archivo plano que contiene la información tabular tanto de nuestras variables explicativas como de nuestra variable objetivo. Contiene información mensual desde febrero de 2005 hasta enero de 2020.
