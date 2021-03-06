# Regresion Robusta para estimar tiempo de respuesta de un servicio de emergencia

El presente repositorio se refiere a un curso sobre regresión robusta, impartido en colaboración con el [Colegio de Matemáticas Bourbaki](https://www.colegio-bourbaki.com/) 

Los datos fueron obtenidos de un Challenge en el que se pretende predecir el tiempo de respuesta y el tiempo de llegada de los bomberos de acuerdo a distintas 
características del incidente como por ejemplo la distancia, el tipo de vehículo utilizado, la altura del incidente (en caso de ser un edificio por ejemplo), etc.

Pueden consultar los detalles en el siguiente [link](https://paris-fire-brigade.github.io/data-challenge/challenge.html). 

Los datos se se encuentran además en [esta carpeta compartida](https://drive.google.com/drive/folders/1Q5O4kHjfwNxZ-ib8GQG04seCeBl2ywv4?usp=sharing).

La hipótesis sobre estos datos que nosotros planteamos es la siguiente: predecir el tiempo de respuesta a un incidente puede ser predicho utilizando una regresión 
(quizás polinomial) sin embargo con fines pedagógicos nos concentraremos en el sencillo caso de las regresiones lineales.

La variable que buscaremos predecir es el tiempo que tarda en llegar el equipo de rescate desde que sale el vehículo hasta la presentación en el lugar del siniestro (delta departure - presentation)

Esta predicción puede verse afectada gravemente por la presencia de outliers en nuestros datos, por ejemplo aquellos causados por huelgas, atentados o en general accidentes 
que dificulten la movilidad.


