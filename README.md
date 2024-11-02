# Credit-Analysis
# Análisis de Riesgo Crediticio 

Este proyecto fue realizado como parte del curso de Data Science II: Machine Learning para la Ciencia de datos de CODERHOUSE. El objetivo de este proyecto es desarrollar un modelo de machine learning para predecir el riesgo de incumplimientos de préstamos, utilizando datos históricos de los solicitantes y características del préstamo. Este análisis permite identificar las características y patrones asociados con un mayor riesgo de incumplimiento, proporcionando a las instituciones financieras una herramienta valiosa para la gestión del riesgo crediticio. 

## Objetivo 
El objetivo principal es desarrollar un modelo predictivo que pueda identificar a los solicitantes de préstamos con mayor probabilidad de incumplimiento. Esto permite a la insituciones financieras:
1. Optimizar el proceso de evaluación de riesgo.
2. Reducir el número de clientes de alto riesgo.

## Datos 

Los datos utilizados en este proyecto provenien de **Kaggle** y contienen información sobre los solicitantes de préstamos y las características de los préstamos otorgados. Las variables clave incluyen:
* Información demgráfica del solicitante (edad, ingresos, etc.)
* Información del préstamo (monto, interés, duración, historial, etc.)
* Estado del préstamo (loan_status), que indica si el préstamo fue pagado o incumplido.

Puede descargar la base de datos desede Kaggle en el siguiente enlace: https://www.kaggle.com/datasets/laotse/credit-risk-dataset/data

## Modelos Utilizados

Se evaluaron y compararon tres modelos principales:
1. **Regresión Logística**
2. **Árbol de Decisión**
3. **Random Forest**

## Requisitos Previos

* Python 3.7 o superir
* Bibliotecas de Python: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`. 
