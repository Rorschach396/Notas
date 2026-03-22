## Introducción 

El 8 de junio de 1912 Max von Laue presentó la primera imagen de difracción de rayos x, esta imagen era de un cristal de sulfato de cobre, el cual había sido obtenida gracias a una serie de esfuerzos conjuntos entre muchas personas y que había permitido obtener una nueva visión tanto de los rayos x como de la estructura de la materia. Sumado a este descubrimiento se logró obtener una mejor interpretación de los resultados gracias a William Lawrence Bragg, quien logró desarrollar una formula matemática para poder interpretar los resultados de los patrones de difracción de rayos x, esta formula es la siguiente: 

$$
n\lambda = 2d\sin \theta
$$

## Metodología 

Para comenzar se realizó un patrón de difracción de rayos x de 3 muestras, dos de sulfato de cobre y una de sulfato de calcio. En el caso de las muestras de sulfato de cobre la principal diferencia que había entre las dos muestras es que una fue sometida a un proceso de purificación conocido como recristalización, lo que permitió que se pudieran eliminar ciertas impurezas que generaban cambios en el patrón de difracción. 

Al momento de obtener estas muestras se pasó a su identificación, para esto se utilizaron principalmente 3 softwares:  
- Origin: Este software nos permitió realizar un smooth del patrón que obtuvimos, el cual permitió identificar mejor las muestras y obtener mejores datos. 
- Profex: Este software fue el principal que se utilizó para poder obtener una identificación de las fases presentes, además de esto se intentó utilizar ciertas funciones de búsqueda de la misma aplicación para poder encontrar algunas otras fases que estuvieran presentes.
- Match: Este software se utilizó para poder extraer cierto ruido del mismo análisis y para poder obtener un mejor resultado a la hora de utilizar profex. 

Estos softwares fueron utilizados en conjunto para poder identificar las diferentes fases presentes en nuestras muestras, para esto fue necesario seguir ciertas metodologías para obtener un resultado satisfactorio y que pudiera ser de ayuda para nuestra investigación. 

A la hora de procesar los datos se siguió una metodología relativamente simple, esta consistía en primero realizar un smooth en Origin, este proceso debía de realizarse con un filtro Savitzky Golay con una apertura de 55 puntos, para luego ser pasado a profex para poder realizar la búsqueda de posibles fases presentes, en este caso esta metodología fue aplicada al sulfato de cobre, con el cual se logró obtener el siguiente resultado: 

![[Pasted image 20260316201119.png]]

Donde las unica fase presente fue la chalcantita, la cual coincide con la información que se tenía originalmente. 

En el caso del sulfato de calcio solo se tuvo que cambiar ligeramente la forma en la que se limpiaron los datos, esto debido a que no se tuvo que  aplicar un filtro para poder procesar los datos, pero en cambio se tuvo que eliminar la aportación de K-alpha, esto fue realizado con ayuda del software Match, el cual permitió eliminar esta sección y así poder ser implementado en profex para poder obtener lo siguiente: 
![[Pasted image 20260316202331.png]]

## Resultados 

En este caso, se lograron obtener que, en el caso del sulfato de cobre, la unica fase presente es la chalcantita, mientras que en el caso del sulfato de calcio se obtuvo que la fase que se encuentra presente es yeso (sulfato de cobre di hidratado); estos resultados pueden ser debatidos en el caso del sulfato de cobre debido a que los valores obtenidos siguen siendo relativamente altos, pero a pesar de esto se puede argumentar que la relación que se tiene entre los picos más altos de la tarjeta de relación y el difracto grama coinciden bastante bien. 

![[Pasted image 20260316203024.png]]

En el caso de estos datos, se realizó el procedimiento de Williamson-Hall para poder calcular el tamaño de cristal y los esfuerzos de la muestra, para poder conseguirlo se decidió utilizar el software de Origin para poder extraer los picos y de esta forma poder analizarlos posteriormente en otro software para poder obtener las gráficas y las ecuaciones de tendencia. En este caso se lograron obtener los siguientes resultados: 


| Sulfato de Cobre Recristalizado      | Sulfato de Cobre                     | Sulfato de Calcio                    |
| ------------------------------------ | ------------------------------------ | ------------------------------------ |
| ![[Pasted image 20260317225006.png]] | ![[Pasted image 20260317225021.png]] | ![[Pasted image 20260317225041.png]] |

Estos resultados permitieron obtener los siguientes resultados: 


|                         | Sulfato de cobre recristalizado | Sulfato de cobre | Sulfato de calcio |
| ----------------------- | ------------------------------- | ---------------- | ----------------- |
| Tamaño de cristal       | 26.0045 nm                      | 14.5297 nm       | 469.84 nm         |
| Esfuerzos de la muestra |                                 |                  |                   |
Estos resultados se lograron obtener gracias a que se tiene una identificación de picos característicos de los patrones de difracción de rayos x; es importante que solo se seleccionen los picos característicos del patrón de difracción, ya que si no se tendrá una cantidad excesiva de ruido que generará una alteración en el resultado. 


| Tarjeta     | Sistema Cristalino | Grupo Espacial | Parámetros de celda                         | Nombre      |
| ----------- | ------------------ | -------------- | ------------------------------------------- | ----------- |
| 00-901-4405 | Triclínico         | P-1            | 6.12; 10.7; 5.97  <br>82.27; 107.43; 102.67 | Chalcantita |
|             |                    |                |                                             |             |
|             |                    |                |                                             |             |
