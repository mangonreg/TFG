# TFG

El presente documento pretende dar una breve explicación sobre los algoritmos incluidos dentro del archivo: CuadradosLatinos.ipynb
Para poder abrir el archivo se recomienda el uso de SageMath 9.2 Notebook

**********************
* Objetivo Principal *
**********************

El objetivo principal de este trabajo consiste en implementar un algoritmo que permita obtener el secreto para un protocolo de
compartición de secretos basado en cuadrados latinos y sus autotopismos, así como las posibles sombras a repartir entre los participantes.
Dicho secreto será un cuadrado latino y las sombras se obtendrán a partir de sus Theta-conjuntos críticos, siendo Theta un autotopismo del mismo. 

Como objetivo secundario se plantea realizar un estudio estadístico del tamaño de los Theta-conjuntos críticos de cuadrados 
latinos de orden seis con el fin de aplicarlos al sistema de compartición de secretos para mejorar su seguridad.

****************************
* Algoritmos desarrollados *
****************************

Los algoritmos principales desarrollados son dos:

1) comparticionSecretosMononivel(numeroDeParticipantes): Este algoritmo lleva a cabo la función propuesta en el objetivo principal 
explicado en la sección anterior. El único parámetro necesario que debemos introducir es el número de participantes del esquema de
compartición de secretos. El algoritmo retorna diversos datos, entre los que encontramos la clave o las sombras a repartir del esquema.

2) graficaEstudioEstadístico(cuadrado, autotopismo): Este algoritmo lleva a cabo la función propuesta en el objetivo secundario
explicado en la sección anterior. Los únicos parámetros que debemos introducir son el cuadrado latino y el autotopismo relativo cuyos conjuntos
críticos se desean estudiar. El algoritimo retorna una gráfica donde se indicará para qué tamaños de conjunto de entradas existen conjuntos críticos
de manera estadística.

*******************
* Recomendaciones *
*******************

A pesar de que el trabajo desarrollado quede resumido en estos dos algoritmos, estos se sostienen sobre diversas funciones auxiliares que recomendamos
encarecidamente que lea y estudie si desea comprender verdaderamente el funcionamiento de dicho programa. Todas estas funciones tienen anotaciones en el
código para facilitar su entendimiento. No obstante, si le surge cualquier duda, puede contactar con el desarrollador a través de la siguiente dirección de
correo: mangonreg@alum.us.es

