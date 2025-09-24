# Introducción al análisis de datos de gobierno con Python-Pandas
### Dra. Mariana Esther Martínez Sánchez ([INER](http://iner.gob.mx/))

En este tutorial, trabajaremos con el conjunto de datos Bitácoras Históricas del Servicio Médico Forense del Distrito Federal (SEMEFO-DF), que ha sido sistematizada por la Comisión Nacional de Búsqueda (CNB). Este conjunto de datos se obtuvo a través de una solicitud de acceso a la información disponible en el Portal de Transparencia del Instituto Nacional de acceso a la Información (INAI) en noviembre de 2023 y existe una copia en el portal ciudadano datamx de Codeando México. Utilizando este conjunto de datos aprenderas de manerá practica cómo explorar, limpiar, análizar y visualizar un conjunto de datos reales usando Python y Pandas.


## Requisitos:
* Saber usar R, SAS, STATA o Excel intermedio.
* Tener [anaconda](https://www.anaconda.com/distribution/) instalado.
* Acceso a internet.


## Índice

1. [Instalación e inicio con Anaconda](./CP1-Instalacion.md)
- a) Instalación de anaconda
- b) Entornos (environments)
- c) Instalación de librerias
- d) Sobre la documentación
- e) Google Colab
- f) Github
- g) Resumen

2. [Introducción a python](./CP2-Introduccion.ipynb)
- a) Python y Jupyter Notebooks
- b) Valores, variables y tipos
- c) Operaciones y funciones
- d) Comentarios y errores
- e) Resumen

3. [Descarga y exploración de datos](./CP3-Exploracion.ipynb)
- a) Estructura de un proyecto de datos
- b) Obtención del conjunto de datos
- c) Cargar los datos en Python
- d) Conjuntos de datos ordenados
- e) Exploración básica con profiles
- f) Opciones avanzadas de profiling
- g) Resumen


4. [Indexación y selección de DataFrames](./CP4-Seleccion.ipynb)
- a) Estructura de una tabla 
- b) Slicing
- c) Únicos y conteo
- d) Ordenar
- e) Subsetting
- f) Guardar datos
- g) Resumen


5. [Remodelación de datos](./CP5-Remodelacion.ipynb)
- a) Estructuras de datos 
- b) Diccionario de datos
- c) Tablas pivote: relacionar variables
- d) Melt: transformar a tidy data
- e) Concat: Unir tablas uno a uno
- f) Merge: Unir tablas muchos a uno
- g) Ejemplo: Reportes de adopción DIF
- f) Resumen


6. [Limpieza de datos](./CP6-Limpieza.ipynb)
- a) Estrategia de limpieza
- b) Valores faltantes y duplicados
- c) Eliminación
- d) Limpieza de texto
- e) Limpieza de categóricos
- f) Limpieza de números
- g) Limpieza de fechas
- h) Ordenar y guardar datos
- i) Resumen


7. [Teoría de la visualización de datos](./CP7-Visualizacion.pdf)
- a) Visualización exploratoria vs. explicativa.
- b) Elementos y codificación de un gráfico.
- c) Criterios para elegir un gráfico.
- d) Jerarquía de elementos visuales.
- e) Uso del color y paletas recomendadas.
- f) Cómo representar datos faltantes.
- g) Principios de diseño para visualizaciones.
- h) Ejemplos de diferentes tipos de gráficos.
- i) Resumen.


8. [Graficación y visualización de datos](./CP8-Graficas.ipynb)
- a) Pandas plot
- b) Opciones de figura
- c) Distribución
- d) Gráficos múltiples 
- e) Heatmaps y clustermaps
- f) Normalización
- g) Resumen


9. [Data Wrangling](./CP9-DataWrangling.ipynb)
- a) División-aplicación-combinación
- b) Agrupar
- c) Agregar
- d) Transformar
- e) Filtrar
- f) Ventanas
- g) Resumen


10. [Estadística básica](./CP10-Estadistica.ipynb)
- a) Frecuencia
- b) Distribuciones estadísticas
- c) Promedio, mediana y moda
- d) Asimetría
- e) Desviación estándar y desviación mediana absoluta
- f) Valores atípicos
- g) Pruebas de distribución
- h) Resumen


11. [Ciencia de datos](./CP11-CienciaDatos.ipynb)
- a) Conjunto de datos
- b) Correlaciones
- c) Pruebas de hipótesis múltiple
- d) PCA (Análisis de Componentes Principales)
- e) Selección de variables
- f) Regresión logística
- g) Resumen


12. [Mapas con GeoPandas](./CP12-Mapas.ipynb)
- a) Formatos de archivo geoespaciales
- b) Marco geoestadístico y catálogo de localidad
- c) Información geoespacial 
- d) Mapas
- e) Mapa con datos propios
- f) Temas adicionales
- g) Resumen



## Recursos útiles
* Programación básica en Python
    * [Think like a computer scientist](https://greenteapress.com/wp/think-python/)
    * [Introducción a la programación en Python I]( https://www.coursera.org/learn/aprendiendo-programar-python)

* Programación intermedia en python
    * [Guia estilo PEP8](https://pep8.org/)
    * [Docstrings numpy](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_numpy.html)
    * The Hacker's Guide to Python, Julien Danjou
    * Computer Science Distilled, Wladston Ferreira Filho
    * [Estructuras de datos](https://classroom.udacity.com/courses/ud513)

* Visualización
    * Selección de colores [Colorbrewer](http://colorbrewer2.org/)
    * [Fundamentals of Data Visualization](https://serialmentor.com/dataviz/)
    * [Visualización de datos y D3](https://classroom.udacity.com/courses/ud507)
    * How To Lie With Maps - Mark Monmonier 

* Estadística
    * Estadistica para Dummies, Deborah J Rumsey
    * Understanding Advanced Statistical Methods,  Peter H. Westfall & Kevin S. S. Henning
    * [TileStats, Andreas Tilevik](https://www.tilestats.com/videos/)

* Machine learning
    * [Machine Learning with Python: A Practical Introduction](https://www.edx.org/course/machine-learning-with-python-a-practical-introduct)
    * [Data Feminism](https://data-feminism.mitpress.mit.edu/), Catherine D'Ignazio y Lauren F. Klein 

* Aprendizaje 
    * [Aprendiendo a aprender](https://www.coursera.org/learn/learning-how-to-learn)
