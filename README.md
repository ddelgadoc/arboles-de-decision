# arboles-de-decision
Tarea evaluativa(formato proyecto) vinculado a la asignatura: Bigdata de los Datos a las Decisiones del Máster en Ingeniería de la Organización de la Politécnica de Madrid

Nombre: "Aplicación del modelo de Machine Learning árboles de desición a la clasificación de marcas de jugos vendidas y la predicción del precio de los jugos"

Lenguaje de programación: R

Base de datos: Fichero txt contiene datos correspondientes a las ventas de zumos de frutas de dos marcas diferentes denominadas CH y MM, recoge información de 1070 ventas en diferentes supermercados de EEUU.

Variables:

choice- Marca elegida por el comprador
id.cust- Identificador del comprador
week - Identificador de la semana de compra
priceCH - Precio de la marca CH disponible para esa venta ($)
proceMM - Precio de la marca MM disponible para esa venta ($)
discountCH - Descuento de la marca CH disponible para esa venta ($)
discountMM - Descuento de la marca MM disponible para esa venta ($)
loyaltyCH - Indicador de fidelidad para la marca CH en compras previas del consumidor(fracción)
loyaltyMM - Indicador de fidelidad para la marca MM en compras previas del consumidor(fracción)
store - Identificador del supermercado donde se realizó la venta (5 niveles: 0,1,2,3,4,)

Descripción: 

-Primeramente se pretende encontrar el modelo que mejor clasifique las dos marcas para una nueva compra en función de las variables usando varios modelos de árboles de clasificación con varias librerías y de agrupación de árboles bajo aprendizaje supervisado.Se entrenan los modelos, se ajusta el parámetro de complejidad(CP) y se evaluan en la muestra test para determinar los mejores modelos que devuelvan los errores de mala clasificación más bajos.

-Segundo se toma en cuenta de los mejores modelos la importancia de variables para contruir un modelo de regresión logística que mejore o iguale los errores de un modelo logit base o que tenga menor complejidad con errores similares. 

-Tercero se pretende encontrar un modelo de árboles de regresión para predecir el valor del precio de las marcas para una nueva venta en función de las variables usando varios modelos de árboles de regresión con varias librerías y de agrupación de árboles bajo aprendizaje supervisado.
