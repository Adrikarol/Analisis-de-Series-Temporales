# Proyecto de Análisis de Series Temporales

Este repositorio contiene el código y los análisis realizados para el proyecto de análisis de series temporales relacionadas con datos de pedidos de taxis. El objetivo principal es comprender y predecir la demanda de taxis a lo largo del tiempo, utilizando diversas técnicas y modelos.

## Contenido del Proyecto

El proyecto se divide en varias secciones, cada una abordando aspectos específicos del análisis de series temporales y la construcción de modelos predictivos. A continuación, se presenta un resumen de las secciones clave:

### Preparación de Datos
Se carga y procesa el conjunto de datos original, realizando operaciones como la carga de datos, verificación del orden cronológico, remuestreo por hora y análisis de tendencias y estacionalidad.

### Entrenamiento de Modelos
Se exploran y comparan varios modelos de regresión para predecir el número de pedidos de taxis. Se utilizan modelos como Regresión Lineal, Árbol de Decisión, Bosque Aleatorio, LightGBM, CatBoost, XGBoost y Prophet.

### Creación de Características
Se diseñan y agregan características relevantes al conjunto de datos, como año, mes, día, día de la semana y hora. Además, se incorporan características de desfase y una media móvil para observar la tendencia general.

### División de Conjuntos
El conjunto de datos se divide en conjuntos de entrenamiento y prueba utilizando la técnica TimeSeriesSplit para mantener el orden temporal de los datos.

### Prueba de Cordura
Se evalúa la capacidad predictiva del modelo utilizando una prueba de cordura, donde se comparan las predicciones con un enfoque ingenuo que utiliza los valores anteriores.

### Entrenamiento y Evaluación de Modelos
Se entrenan varios modelos de regresión y se evalúan en el conjunto de prueba utilizando métricas como la raíz del error cuadrático medio (RECM).

## Estructura del Repositorio
- `src/`: Contiene los scripts y notebooks de código fuente utilizados para realizar el análisis y entrenar los modelos.
- `data/`: Almacena el conjunto de datos original.
- `README.md`: Este archivo, que proporciona una guía detallada sobre el proyecto, sus objetivos y la estructura del repositorio.
