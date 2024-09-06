Este práctico es para hacer con Google Colab. Para esto van a tener que:

1. Entrar a google colab -> https://colab.research.google.com/  y crear un notebook con el nombre: tp2_<nombreyapellido>_2022.ipynb

2. En una celda importar el dataset con el comando:

 2.a. Opción 1 Insurance:  !wget https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv

 2.b. Opción 2 Water Potability: ingresar a Kaggle y descargar el dataset (csv). Luego deberán subirlo al notebook de Colab.

3. Una vez obtenido el archivo insurance.csv o water_potability.csv realizar un análisis exploratorio de las variables numéricas. Pueden quitar las variables no numéricas con la función dataframe.drop(columns=['nombrevar1','nombrevar2',...,'nombrevarn'])

4. Realizar un modelo de regresión simple lineal ó regresión multivariante lineal. Para esto deben escalar los datos, separarlos, entrenar y evaluar.

6. Realizar un modelo de regresión con SVR o DT. Para esto deben escalar los datos, separarlos, entrenar y evaluar.

7. Luego en la sección superior derecha del colab, aprietan en compartir, cambien los permisos para todos, copien en link y lo pegan en el texto en línea de la entrega de este práctico.

pd: pueden usar los colab que están la catedra como guía. 

Aclaración Dataset Insurance: se trata de un conjunto de datos que muestra como se calcula el valor del seguro medico ['charges'] en función de muchas variables como son la edad, el indice bmi, etc. Recomendación vean un mapa de calor para elegir aquellas variables que más se correlacionen para explicar la variable 'charges'.

Aclaración Dataset Water Potability: no utilizar la variable Potability, ya que es una variable del tipo binaria, para clasificación. La idea es que con las demás variables hagan un análisis exploratorio y decidan cual de todas explicar (debe ser continua) en función de otra u otras variables a elección según el análisis previos. Recuerden que es un práctico de regresión numérica ;).

Mucha suerte, confiamos en ustedes!