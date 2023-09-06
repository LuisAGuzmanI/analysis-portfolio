# SMA0401A - Retroalimentación

Trabajo realizado para el entregable: Momento de Retroalimentación: Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.

## Trabajo realizado

En este trabajo se emplea el [Student Marks Dataset](https://www.kaggle.com/datasets/yasserh/student-marks-dataset) disponible en Kaggle y publicado por el Ing. M Yasser H, que incluye registros del tiempo dedicado semanalmente al estudio por alumnos, la cantidad de cursos que cursan en el momento, y las calificaciones que los mismos optienen. Con esto se busca generar un modelo predictivo que pronostique las calificaciones de los alumnos basandose en el tiempo dedicado al estudio y su carga de cursos actual.

En el script se analiza el sesgo, varianza y ajuste de diferentes modelos de regresión polinomial con la finalidad de contrar el modelo que mejor se ajuste a las observaciones, sin caer en underfitting ni en overfitting.

## Contenidos 

* Student_Marks_Regression.ipynb: Archivo de Jupyter Notebook que contiene la implementación de 2 técnicas de ML haciendo uso de un framework para su evaluación.
* Student_Marks.csv: Archivo .csv que contiene el dataset necesario para correr el archivo previamente mencionado.