# TFM: Análisis de modelos de Deep Learning mediante SHAP values



## Resumen 

El Deep Learning o Aprendizaje Profundo se aplica cada vez más en la toma de decisiones y problemas analíticos. Como consecuencia, existe una demanda creciente por la capacidad de interpretar la predicción de modelos. Una técnica de explicación es la basada en los valores de Shapley como medida de agregación para determinar la influencia de las características individuales en la predicción del modelo colectivo. Las SHAP values presentan propiedades muy ventajosas en el análisis de este tipo de modelos, pues usan nociones de teoría de juegos para medir la influencia de las diferentes características en el resultado final del modelo. A lo largo de este trabajo, desarrollaremos y programaremos herramientas que nos permitan interpretar modelos de Deep Learning usando las SHAP values, dándonos una mejor interpretación de los factores en los que se basa el modelo a la hora de tomar una decisión u otra.

Comenzaremos con un modelo sencillo, con el que introduciremos los conceptos básicos de las SHAP values y aprenderemos a implementarlas en un entorno \textit{Python}. A continuación, desarrollaremos, de la forma más profesional posible, un estudio de interpretabilidad de un modelo de caja negra, sacando el máximo provecho a los resultados de la explicación del modelo. Finalmente, ejemplificaremos y probaremos la efectividad de la SHAP values en la interpretación de arquitecturas de reconocimiento visual profundo. 

Palabras clave: Aprendizaje Automático, Aprendizaje Profundo, Explicabilidad, Inteligencia Artificial, Valores SHAP.

## Abstract 

Deep Learning is increasingly applied in decision making and analytical problems. As a consequence, there is a growing demand for the ability to explain model prediction. One explanation technique is through the use of Shapley values as a measure of aggregation to determine the influence of individual characteristics on the prediction of the collective model. SHAP values have very advantageous properties in the analysis of this type of model, since they use notions of game theory to measure the influence of the different features on the final result of the model. Throughout this work, we will develop and program a tool that allows us to interpret Deep Learning models using SHAP values, giving us a better interpretation of the factors on which the model is based when making one decision or another. 

We will start with a simple model, with which we will introduce the basic concepts of SHAP values and learn to implement them in a \textit{Python} environment. Next, we will develop, in the most professional way possible, an interpretability study of a black box model, making the most of the model explanation results. Finally, we will exemplify and test the effectiveness of SHAP values in the interpretabilty of deep visual recognition architectures.

Keywords:  Machine Learning, Deep Learning, Explainability, Artificial Intelligence, SHAP Values.

## Descripción de los archivos y documentos.

* datasets: Ficheros .csv con los datasets empleados.

* python: Programas .ipynb con la implementación de los modelos y las SHAP values. Tendremos tres programas:
  * SimpleModel-Iris: Programa para el modelo sencillo del dataset Iris.
  * ComplexModel-CensusIncome: Programa para el modelo complejo del dataset Census Income.
  * ImageModel-VGG16: Programa para el modelo clasificador de imágenes VGG16.

* Memoria TFM: Documento .pdf con la memoria final del TFM, que recopila todas las etapas del proyecto.


