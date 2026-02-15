# Estructura Hexagonal

![[Figuras.png]]

En este caso se obtendrán los indices de miller de una estructura hexagonal siguiendo estos pasos: 
1) Obtener los indices de Miller como si fuera una celda con forma de prisma romboidal 
2) Realizar la conversión coordenadas 

Para poder obtener los indices de Miller, solo se considerará el rombo generado por el eje x, y y c; esto da como resultado las siguientes coordenadas de inicio y fin: 


|     | Inicio | Fin | Resultado |
| :-: | :----: | :-: | :-------: |
|  x  |   0    | 1/2 |    1/2    |
|  y  |   0    |  1  |     1     |
|  c  |   0    | 1/2 |    1/2    |

Con estas coordenadas podemos encontrar que el indices de Miller sería $[121]$, con estos datos debemos de aplicar las siguientes formulas: 
$$
\begin{gather}
[U'V'W'] \rightarrow [UVTW] \\
U = \frac{n}{3}(2U'-V') \\
V = \frac{n}{3}(2V'-U') \\
T = -(U'+V') \\
W = nW'
\end{gather}
$$
En este caso la constante "$n$" es un número que se debe encontrar al terminar de realizar los cálculos. Aplicando las formulas al ejemplo anterior obtenemos lo siguiente: 
$$
\begin{gather}
U = \frac{n}{3}(2(1)-(2)) = 0 \\
V = \frac{n}{3}(2(2)-(1)) = n \\
T = -((1)+(2)) = -3 \\
W = n(1) = n
\end{gather}
$$
La constante "$n$" se obtiene buscando un número que pueda simplificar las posibles generadas en $U$ y $V$, como en este caso no se obtuvo ninguna fracción, se obtiene lo siguiente: 
$$
\begin{gather}
[121]\rightarrow[01\bar{3}1]
\end{gather}
$$
# Estructura cúbica
![[Cubica.png]]