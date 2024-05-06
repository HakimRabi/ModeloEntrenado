Predicción de Consumo de Energía en Subestaciones

Características del Proyecto:
- Preprocesamiento de datos: Scripts para limpiar y transformar datos.
- Entrenamiento del modelo: Script para entrenar el modelo utilizando los datos proporcionados.
- Evaluación del modelo: Script para evaluar la precisión y el rendimiento del modelo.
- Modelo final: El modelo entrenado para realizar predicciones de consumo de energía.

En la gestión eficiente y segura de la red eléctrica, la predicción precisa del consumo de energía es fundamental. Esto permite a los operadores anticipar la demanda y tomar medidas apropiadas para garantizar un suministro confiable y evitar posibles sobrecargas o interrupciones. En el contexto del Sistema Eléctrico Nacional (SEN), la necesidad de pronósticos precisos se vuelve aún más crucial debido a la diversidad geográfica y climática de las diferentes áreas del país.

Este proyecto se centra en desarrollar un modelo desagregado para prever el consumo de electricidad en tres zonas específicas del SEN: la zona central, la zona norte grande y la zona sur. Estas zonas abarcan desde Santiago en el centro hasta Iquique y Antofagasta en el norte, y desde Valdivia hacia el sur, respectivamente.

La construcción de un modelo detallado de datos de consumo de energía para cada una de las tres zonas del SEN, desagregado por barras. Esto implica recopilar y estructurar datos históricos de consumo, así como datos relevantes como las temperaturas y el tipo de día.

Seleccionar, a través de una revisión exhaustiva del estado del arte, un algoritmo de Aprendizaje Automático o Aprendizaje Profundo multivariable que sea más apropiado para prever el consumo, considerando el modelo de datos definido. Este algoritmo debe ser capaz de manejar múltiples variables de entrada, como el consumo por barra, las temperaturas y el tipo de día.

Evaluar el rendimiento del modelo de predicción comparando sus predicciones con los pronósticos actualmente utilizados por el Coordinador del SEN. Esto se realizará aplicando métricas de error apropiadas para evaluar la precisión y confiabilidad de las predicciones.

Este proyecto utiliza aprendizaje automático para predecir el consumo de energía en subestaciones eléctricas. El modelo final entrenado se incluye en este repositorio, junto con scripts necesarios para generar y evaluar predicciones a partir del conjunto de datos proporcionado.


Para poder ocuparlo se debe descargar el CSV.rar que se encuentra subido y descomprimirlo en la carpeta raiz del proyecto. 
Csv_trasformacion_y_Entrenamiento_1.ipynb - Se ocupa para ordenar el csv y crear nuevas columnas, ademas se empieza a modelar y entrenar con RNN, ademas se crea otro csv de datos de prueba para verificar la precisión del modelo.
Entrenamiento2.ipynb - Se termina de entrenar el modelo con RNN y se compara con los demas modelos.
Test Shap.ipynb - Se prueba el test de SHAP.






