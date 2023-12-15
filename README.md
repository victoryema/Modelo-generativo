# Modelo Generativo para la Predicción de Géneros Musicales a partir de Letras de Canciones

## Descripción
Este proyecto implementa un modelo de Machine Learning utilizando la técnica de Naive Bayes para predecir el género musical de una canción basándose en su letra. Se realiza un análisis exploratorio de datos, se utiliza la técnica de CountVectorizer para generar una matriz de ocurrencias de palabras, y se entrena el modelo con un conjunto de datos de canciones.

## Instrucciones de Uso
- Clona este repositorio en tu máquina local.
- Asegúrate de tener las dependencias instaladas ejecutando pip install -r requirements.txt.
- Ejecuta el notebook Jupyter Genero_Canciones.ipynb para explorar el análisis y ejecutar el modelo.

## Dependencias
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter (para ejecutar el notebook)

## Estructura del Proyecto
- Genero_Canciones.ipynb: Notebook principal con el código y análisis.
- dump/: Carpeta que contiene los archivos CSV originales.
- dump_plus_pop/: Carpeta que contiene los archivos CSV con observaciones adicionales en la clase "pop".
- README.md: Documentación del proyecto.
- requirements.txt: Lista de dependencias y versiones.

## Conjunto de Datos
Se utiliza un conjunto de datos que incluye información sobre artistas, géneros, nombres y letras de canciones.

## Análisis Exploratorio de Datos (EDA)
Se realiza un análisis detallado, incluyendo visualizaciones sobre la cantidad de canciones por artista y género.

## Modelos Utilizados
Se implementa un modelo Naive Bayes utilizando CountVectorizer para representar las letras de las canciones como características. Se evalúa el rendimiento del modelo y se realiza una mejora específica en la clase "pop" mediante la adición de observaciones.

## Resultados
Se proporcionan detalles sobre el rendimiento del modelo antes y después de agregar más observaciones en la clase "pop".

## Autor
Víctor Urra

## Agradecimientos
Agradezco a las bibliotecas de código abierto utilizadas.
