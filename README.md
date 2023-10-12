# spamdemensajes
Este proyecto tiene como objetivo la clasificación de mensajes SMS como spam o legítimos (ham). Se utilizó el conjunto de datos "SMS Spam Collection", que consta de 5,574 mensajes en inglés etiquetados como spam o ham.
Librerías Utilizadas

    pandas
    numpy
    nltk
    re
    sklearn

Procedimiento
1. Carga y Preprocesamiento de Datos

El conjunto de datos fue cargado usando pandas. Se seleccionaron las columnas relevantes ('messages' y 'label') y se renombraron para mayor claridad.
2. Limpieza de Texto

Se realizó una limpieza de texto para preparar los mensajes para su procesamiento. Esto incluyó la conversión a minúsculas, eliminación de caracteres especiales y espacios extra, y la eliminación de stopwords (palabras comunes que no aportan mucho significado).
3. División de Datos

Los datos se dividieron en características (X) y etiquetas (y).
4. Entrenamiento del Modelo

Se implementaron varios algoritmos de clasificación, incluyendo Regresión Logística, Naive Bayes, SVM y Random Forest. Para cada algoritmo, se creó un pipeline que incluye la vectorización de texto y la transformación TF-IDF.
5. Evaluación del Modelo

Se evaluaron los modelos utilizando métricas como precisión, recall y f1-score. Los resultados se presentaron para cada algoritmo.
Resultados

Los modelos fueron evaluados con los siguientes resultados de precisión:

    Regresión Logística: 96.84%
    Naive Bayes: 96.70%
    SVM: 98.28%
    Random Forest: (Ingresar el resultado)

Consideraciones

El énfasis de este proyecto estuvo en la precisión de las predicciones y no en el diseño visual. Seaborn no se utilizó en este proyecto, ya que se centró en la funcionalidad de los algoritmos de clasificación de texto.

Nota: Para completar la sección "Random Forest", por favor ingresa el resultado obtenido al ejecutar el modelo RandomForestClassifier.
