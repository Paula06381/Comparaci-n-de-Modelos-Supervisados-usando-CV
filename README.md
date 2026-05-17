# Trabajo Práctico 2 - Comparación de Modelos Supervisados

## Descripción del dataset utilizado

Para este trabajo se utilizó el dataset Breast Cancer Wisconsin, el cual contiene información sobre diagnósticos de cáncer de mama.  

La variable objetivo es `diagnosis`, donde:
- M = maligno
- B = benigno

El dataset contiene diferentes variables numéricas relacionadas con características de las células analizadas, como radio, textura, perímetro y área.  

Se realizó una limpieza básica eliminando columnas innecesarias y transformando la variable objetivo a valores numéricos.

---

## Objetivo del trabajo

El objetivo de este trabajo fue comparar diferentes modelos supervisados de clasificación utilizando validación cruzada para evaluar su desempeño y capacidad de generalización.

Se trabajó con los siguientes modelos:
- Logistic Regression
- KNeighborsClassifier
- DecisionTreeClassifier

La métrica utilizada para comparar los modelos fue ROC AUC.

---

## Principales hallazgos y conclusiones

- Logistic Regression fue el modelo que presentó resultados más estables entre entrenamiento, validación y test.

- Decision Tree obtuvo resultados altos en entrenamiento, pero presentó mayor variación en validación cruzada, lo que puede indicar overfitting.

- KNN también tuvo un buen desempeño, aunque dependía más de la partición de los datos.

- La validación cruzada permitió evaluar mejor el comportamiento de los modelos y comparar su capacidad para generalizar con datos nuevos.

- El resultado final en el conjunto de prueba fue similar al obtenido en cross validation, por lo que el comportamiento esperado del modelo se mantuvo.
