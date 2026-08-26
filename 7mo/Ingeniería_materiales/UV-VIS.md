También conocida como espectroscopía óptica, surge de la interacción entre la luz y la materia. Solo se puede ver el color que reflejan las cosas, no el color del que "son". 
La técnica de UV-VIS es una técnica que busca pasar un haz de luz que permite identificar que partes de la luz pueden atravesar la muestra y de esta forma poder identificar que colores está absorbiendo y rebotando. 

## Procedimiento 

En el caso de las máquinas de UV-VIS se tiene una fuente de luz que va cambiando con un determinado paso (entre más lento se va a tener un mejor resultado), esto permite que un detector obtenga la lectura de la luz que absorbe o emite la muestra. En el caso de las celdas que realizan la medición, estas pueden ser de vidrio, polímero o cuarzo. 
![[Pasted image 20260826082648.png]]
A pesar de que, en teoría se tiene que cambiar las celdas es muy común que se utilicen las mismas. 

## El blanco 

El blanco es el solvente mayoritario en el que se encuentra la muestra, este debe de ser traslucido preferentemente, esto para poder realizar una medición correcta y eliminar el ruido. Existe una tendencia lineal entre la concentración y la absorbancia. También se puede dar el caso de que el blanco sea el mismo aire. 

El blanco permite eliminar todo el ruido que existe entre el emisor y el receptor, esto permite obtener una mejor medición. Un error muy común que se tiene que evitar es el cambio de tipo de celda utilizada en el blanco y en las muestras, esto debido a que puede generar cambios en las mediciones. 

## La muestra

Lo que mide la máquina al momento de realizar el análisis es la relación entre la intensidad que sale de la muestra y la que se le da a la muestra, esto permite calcular la transmitancia: 

$$
T = \frac{I}{I_{0}}
$$
UV-VIS normalmente se grafica en absorbancia, la cual tiene la siguiente formula matemática: 
$$
A = -\log(T)
$$
## Ley de Lambert-Beer 

Esta ley se basa (además de la técnica) en el paso, es decir, la distancia que tiene que pasar la luz a través de la muestra. 

$$
A = \epsilon \cdot c \cdot d 
$$
Donde: 
- Concentración: C 
- longitud del camino: d 
- Coeficiente de extinción: $\epsilon$

Esta ley solo es valida en una absorbancia de 0 a 1, es posible que esta relación se pueda seguir conservando después de este límite, pero se tiene que evaluar para poder corroborarlo, esto debido a que es muy común que no se cumpla esta relación fuera de los límites. 

Esta ley es más utilizada realizando el despeje de la concentración, esto implica que se utilicen tablas para poder conocer el coeficiente de extinción y los demás datos se pueden obtener gracias al equipo, la formula final en este caso sería la siguiente: 
$$
c = \frac{A}{\epsilon \cdot d}
$$
El rango adecuado para poder realizar mediciones correctas es de A = 0.01 y 2.5, no se deben de utilizar valores más altos o más bajos debido a que se puede perder la proporcionalidad y esto nos puede dar valores erróneos. Depende mucho del equipo el rango que se puede utilizar para poder realizar las mediciones. 

Se debe de utilizar una concentración (preferentemente) de 0.01 M para poder obtener medidas óptimas. Las moléculas presentes en la solución pueden dar como resultado una mala medición, además de esto también afecta el índice de refracción. Se recomienda darle una "limpieza" a la muestra para poder eliminar todos los reactivos o agentes que no deban de estar presentes en la reacción para poder evitar que reaccionen o que den una mala lectura. Se pueden realizar lavados con diferentes solventes dependiendo que se quiera eliminar de la muestra. 

==Mayor absorbancia = Mayor concentración==

## Usos
- Permite identificar si hay algún colorante o nanopartícula 
- Permite cuantificar la cantidad de las substancias presentes 
- Dependiendo de la posición de los se puede conocer una posible composición (más que nada cualitativa) de la muestra 
- Puede indicar ciertas propiedades físicas de la muestra, como velocidad de reacción 
- La posición y el perfil de los picos permite determinar el ambiente macroscopic (concentración, dispersión, distribución bimodal o multimodal, tamaños y formas) de la muestra

Es recomendable utilizar este tipo de caracterización primero de forma cualitativa (si hay o no lo que buscas) y luego realizar una medición cuantitativa después de realzar una banda o curva de calibración. 

![[Pasted image 20260826091348.png|629]]

El $E^2$ debe de ser mayor al 95% 

### Tipos de espectrómetros
- Espectrofotómetro de barrido : En este caso se realiza un barrido en el cual se obtiene una lectura en cada una de las lecturas realizadas. 
- Espectrofotómetro de matriz: Primero llega todo el espectro y después se analiza cada uno  por separado.

## Configuración de caminos ópticos

- Un solo haz: Solo analiza la muestra, se tiene que analizar por aparte el blanco
- Doble haz: el haz se divide en una referencia y un haz de muestra, este compara la muestra y el blanco al mismo tiempo 
	- Simultanea en el tiempo 
	- Alternada en el tiempo: Se va intercalando entre la muestra de referencia y la muestra blanco
![[Pasted image 20260826092746.png]]

***==El Benceno absorbe en los 280 nm==***

Para determinar si una banda está formada por diferentes bandas empalmadas se puede utilizar la deconvolución para poder encontrar que bandas componen a la misma, también se pueden utilizar la primera y la cuarta derivada de los datos para poder encontrar el punto máximo, la cuarta derivada te dice donde está la banda o cual es la forma de la banda, para poder de esta forma realizar el proceso de deconvolución. 
