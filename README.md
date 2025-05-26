# 🧠 Construcción de una Red Neuronal para Predecir Precios de Viviendas 🏠



Este proyecto tiene como finalidad aplicar conocimientos prácticos de *Machine Learning* para predecir precios de viviendas a partir de múltiples variables del entorno utilizando técnicas de **regresión lineal** y **redes neuronales artificiales**. Se desarrolló en Python y se apoya en herramientas como **TensorFlow/Keras**, **Scikit-learn**, **Pandas**, **Matplotlib** y **GitHub** para gestión de versiones.



Está orientado a estudiantes, profesionales o entusiastas de la ciencia de datos que deseen comprender cómo construir modelos predictivos con distintas técnicas y evaluarlas comparativamente.



---



## 🎯 Objetivo General



Desarrollar y comparar modelos de aprendizaje automático capaces de estimar el valor de una vivienda usando datos históricos y características estructurales o socioeconómicas de su entorno.



---



## 📌 Objetivos Específicos



- Aplicar una **regresión lineal simple** para predecir el precio de una vivienda utilizando una sola variable.

- Construir una **red neuronal artificial multivariable** con Keras para mejorar la precisión del modelo.

- Visualizar los resultados obtenidos mediante gráficos y métricas cuantitativas.

- Utilizar herramientas como **GitHub** para documentar, versionar y compartir el desarrollo del proyecto.



---



## 🔍 Metodología



### 1. Investigación Teórica

Se elaboró una base conceptual sólida sobre redes neuronales, regresión lineal, TensorFlow/Keras y control de versiones con GitHub.



### 2. Preparación del Entorno

- Se instalaron los paquetes requeridos: `tensorflow`, `keras`, `scikit-learn`, `matplotlib`, `numpy` y `pandas`.

- Se inicializó un repositorio GitHub (`red_neuronal`) con un archivo `README.md` para documentar el desarrollo.



### 3. Carga y Preprocesamiento del Dataset

- Se utilizó el conjunto de datos **California Housing** de Scikit-learn.

- Se normalizaron los datos con `StandardScaler` para mejorar el rendimiento del modelo neuronal.



### 4. Modelado

- Se implementó una **regresión lineal simple** usando `LinearRegression` de Scikit-learn, prediciendo en base a una sola variable (`AveRooms`).

- Se entrenó una **red neuronal** secuencial con varias capas densas y técnicas como *Dropout* y *EarlyStopping* para optimizar el aprendizaje.



### 5. Evaluación de Resultados

- Se graficaron los resultados de ambos modelos.

- Se utilizaron métricas como el **error cuadrático medio (MSE)** y el **coeficiente de determinación R²** para comparar el desempeño.



---



## 📊 Resultados Obtenidos



| Modelo        | MSE (Error Medio) | R² (Precisión) |

|----------------------|------------------|----------------|

| Regresión Lineal   | 1.233      | 0.075     |

| Red Neuronal (Keras) | 0.267      | 0.796     |



- El modelo de regresión lineal mostró un rendimiento muy limitado, explicando apenas el 7.5% de la variabilidad.

- La red neuronal ofreció una mejora significativa, alcanzando casi un 80% de precisión con menor error.



---



## 📌 Conclusiones



- Las **redes neuronales** presentan una gran ventaja en problemas multivariables y no lineales.

- **Regresión lineal** sigue siendo útil como punto de partida, pero tiene limitaciones con datos complejos.

- El uso de herramientas como **GitHub** es clave para documentar, controlar versiones y presentar proyectos profesionales.

- Este proyecto representa una introducción completa al flujo de trabajo en proyectos de ciencia de datos: análisis, modelado, validación y presentación.



---



## 💻 Tecnologías Utilizadas



- [Python 3.12](https://www.python.org/)

- [TensorFlow](https://www.tensorflow.org/) / [Keras](https://keras.io/)

- [Scikit-learn](https://scikit-learn.org/)

- [Matplotlib](https://matplotlib.org/)

- [Pandas](https://pandas.pydata.org/)

- [Git + GitHub](https://github.com/)

