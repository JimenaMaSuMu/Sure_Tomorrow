# Sure_Tomorrow
Análisis y Modelado de Datos para Sure Tomorrow
Descripción del Proyecto
La compañía de seguros Sure Tomorrow busca aplicar técnicas de machine learning para resolver cuatro tareas clave: encontrar clientes similares, predecir la probabilidad y cantidad de beneficios de seguro, y proteger los datos personales de los clientes mediante técnicas de enmascaramiento. Este proyecto aborda estas tareas, garantizando que los resultados sean precisos y seguros.

Objetivos del Proyecto
Tarea 1: Encontrar clientes similares a uno determinado.

Implementar técnicas de análisis de similitud para ayudar en campañas de marketing.
Tarea 2: Predecir la probabilidad de que un cliente reciba beneficios.

Comparar el rendimiento de un modelo de predicción entrenado con un modelo dummy.
Discutir si un modelo entrenado puede funcionar peor que un modelo dummy.
Tarea 3: Predecir la cantidad de beneficios de seguro que recibirá un cliente.

Usar un modelo de regresión lineal para realizar esta predicción.
Tarea 4: Proteger los datos personales de los clientes.

Implementar un algoritmo de enmascaramiento de datos que mantenga la calidad del modelo de machine learning.
Descripción de los Datos
El conjunto de datos se encuentra en el archivo insurance_us.csv y contiene las siguientes columnas:

Sexo: Género de la persona asegurada.
Edad: Edad de la persona asegurada.
Salario: Salario de la persona asegurada.
Número de familiares: Cantidad de familiares dependientes.
Beneficios: Número de beneficios de seguro recibidos por la persona asegurada en los últimos cinco años (variable objetivo).
Metodología
1. Preparación de los Datos
Carga y limpieza de datos.
Identificación y manejo de valores faltantes y extremos.
Normalización y codificación de variables según sea necesario.
2. Tarea 1: Encontrar Clientes Similares
Implementar métricas de similitud como:
Distancia Euclidiana.
Distancia Coseno.
Construir un sistema que permita identificar clientes similares a un cliente dado.
3. Tarea 2: Predecir Probabilidad de Beneficio
Entrenar un modelo de clasificación para predecir si un cliente recibirá beneficios.
Comparar el modelo con un modelo dummy:
Calcular métricas como exactitud, precisión, y F1-score.
Evaluar si un modelo entrenado puede ser peor que un modelo dummy.
4. Tarea 3: Predecir Cantidad de Beneficios
Entrenar un modelo de regresión lineal para predecir la cantidad de beneficios.
Evaluar el rendimiento del modelo con métricas como RMSE y 𝑅2

 .
5. Tarea 4: Enmascaramiento de Datos
Implementar un algoritmo de enmascaramiento para proteger los datos personales.
Asegurar que la calidad de los modelos no se vea afectada tras la transformación.
