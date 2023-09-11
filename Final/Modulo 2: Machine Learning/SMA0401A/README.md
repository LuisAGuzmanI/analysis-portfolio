# SMA0401A - Retroalimentación

Trabajo realizado para el entregable: Momento de Retroalimentación: Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.

## Trabajo realizado

En este trabajo se emplea el [Student Marks Dataset](https://www.kaggle.com/datasets/yasserh/student-marks-dataset) disponible en Kaggle y publicado por el Ing. M Yasser H, que incluye registros del tiempo dedicado semanalmente al estudio por alumnos, la cantidad de cursos que cursan en el momento, y las calificaciones que los mismos optienen. Con esto se busca generar un modelo predictivo que pronostique las calificaciones de los alumnos basandose en el tiempo dedicado al estudio y su carga de cursos actual.

En el script se analiza el sesgo, varianza y ajuste de diferentes modelos con la finalidad de contrar el modelo que mejor se ajuste a las observaciones, sin caer en underfitting ni en overfitting. Para esto, se generan una variedad de modelos de **regresión polinomial** utilizando la librería de sci-kit learn, la cual implementa el método de **mínimos cuadrados ordinarios**.

## Contenidos 

* Analisis_de_desempeno.ipynb: Archivo de Jupyter Notebook que contiene la implementación de 2 técnicas de ML haciendo uso de un framework para su evaluación.
* Student_Marks.csv: Archivo .csv que contiene el dataset necesario para correr el archivo previamente mencionado.

## Modificiaciones respecto a la última entrega
*  Se incluyó un tercer subconjunto de datos para validación. Ahora el subconjunto de entrenamiento representa el 70% de los datos, validación el 15% y pruebas el 15% restante.
* Se utiliza el subconjunto de validación para la desición de hiperparamentros (orden polinomial) del modelo final.
* Se evalúan varianza, sesgo y ajuste únicamente sobre el modelo final, centrandose exclusivamente en el modelo polinomial de orden 2.
* Se incluye una sección sobre técnicas de regularización, aunque se llega a la conclusión que dado el algoritmo usado para generar el modelo (minimos cuadrados ordinarios) resulta innecesario aplicar dichas técnicas, ya que todos los componentes del modelo resultan necesarios, y la eliminación de los mismos resultaría en una reducción del desempeño del modelo.