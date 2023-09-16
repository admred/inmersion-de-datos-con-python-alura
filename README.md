# Ciencia de datos con Python

#### Este proyecto es sobre datos de una inmobiliaria de Colombia en relacion con su contexto demografico

---

#### Haciendo click en el siguiete enlace se puede acceder al Notebook de Jupyter

### >>> [Inmersion de datos con Python - Alura](https://github.com/admred/inmersion-de-datos-con-python-alura/blob/master/Inmersion_de_datos_con_python_Alura.ipynb) <<<

---

###  Procedimientos o explica

### 1. Tratamiento de datos y exposicion

1.1 Extraccion de datos

   - Los datos normalmente son extraidos de archivos .csv que pueden estar ubicados de manera remota como en github o google drive por ejemplo.

1.2. Paso es la exploracion de datos

   - Es entener como esta compuesta la planilla, la cantidad filas, columnas, y de que tipo son.
    
1.3. Saneamiento de datos

   - Esta etapa de debe elimnar las registros inválidos, vacios o con NaN
   - Los *Outliers* son valores extremos producen un sesgo en las estadísticas, son expuestos mediante el grafico boxplot. Luego son removidos.

1.4. Luego se procede al tratamiento de datos y/o exposicion

   - Explicar los datos mediantes numeros
   - Explicar los datos mediantes graficos


### 2. Machine Learning
   
   Basicamente se divide en 2 (o mas) ramas importantes
   
   - Supervisado
   - No supervisados
     
   En *supervisado* tenemos los modelos de
   
   - Clasificacion: ideal cuando los datos son string , por ej: color, pais, etc
   - Regresion: cuando los datos son numericos, por ej: edad, precio, etc
   - Y otros como SVM, Tree, entre otros.

2.1 Entrenaminto y se recompila los resultados

2.2 Optiminzando modelos

  Se trata de repetir 2.1 con distintas variantes, en general contra la *baseline* que son los resultados del primera prueba.
  
  - Metricas de precision de las predicciones: r2_score y median_absolute_error
  - Optimizacion:
    - Agregando o quitando columnas a nuestros datos de entrenamiento. Un grafico de correlacion o *heatmap* puede ayudar.
    - Mediante *hyper-parametros*, son paramentros que cambian comportamiento interno del entrenamiento.

---

## Tecnologias usadas
-  Python
-  Pandas
-  Seaborn
-  Matplotlib
-  Scikit-Learn
-  Google Colab
-  Datasets provistas por el curso de Alura
-  Github para hospedaje de este proyecto

---
