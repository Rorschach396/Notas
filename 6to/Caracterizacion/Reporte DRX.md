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
- QualX: Este software fue utilizado para poder realizar una búsqueda en la base de datos POW_COD, esto para poder encontrar la identificación de las tarjetas asociadas a un determinado patron de difracción. 

Estos softwares fueron utilizados de diferentes escenarios y permitieron obtener diferentes resultados dependiendo de la forma y el orden en el que se utilizaron; debido a esto se intentó utilizar una metodología general para poder obtener un resultado más repetible y no comprometiera la fiabilidad de los datos obtenidos. 

### Sulfato de Cobre ($CuSO_{4}$)

En el caso del sulfato de cobre se obtuvieron dos muestras, una de las muestras no tenía ningún proceso de purificación o de refinamiento, mientras que la segunda muestra presentaba un proceso de recristalización que aumentaba su porcentaje de pureza. Estas dos muestras fueron analizadas siguiendo dos metodologías diferentes:
- Primera metodología: En la primera metodología se realizó un filtro Savitzky Golay con una apertura de 55 puntos dentro del software de Origin para luego ser analizado en Profex para poder encontrar que fase estaba presente en la muestra. 
- Segunda metodología: En esta metodología se utilizó solo el software de Profex para poder realizar el proceso de Smooth, utilizando un algoritmo de "Simple Moving Averages" o SMA de 13 puntos. 

En el caso de la primera metodología se lograron obtener los siguientes resultados al momento de realizar la búsqueda de fases utilizando parámetros bases de un Rigaku Miniflex (datos presentes en Profex): 
![[Pasted image 20260316201119.png]]
En un intento de poder reducir más los valores de GoF y $\chi^2$ se busco realizar todo el proceso dentro de Profex para poder evitar cualquier interferencia entre los softwares, esto dió como resultado lo siguiente: 
![[Pasted image 20260322181803.png]]
Estos mismos procedimientos fueron realizados para las muestras que no fueron recristalizadas, dando como resultado los siguientes valores: 

| Primera metodología                  | Segunda metodología                  |
| ------------------------------------ | ------------------------------------ |
| ![[Pasted image 20260322184244.png]] | ![[Pasted image 20260322184305.png]] |
Debido a que se obtuvieron valores altos tanto en GoF como en $\chi^2$ se cree que existe una tendencia en el acomodo de los planos de ambas muestras; esto se puede deber a muchos motivos, los cuales van desde la forma en la que se colocó la muestra dentro de los aparatos de medición como posibles crecimientos anormales debido al proceso de recristalización. 

### Sulfato de Calcio ($CaSO_{4}$)

En el caso del sulfato de calcio se tuvieron 3 muestras, las cuales tuvieron diferentes procesos de refinamiento y análisis dentro de los softwares presentados anteriormente. La primera muestra es un sulfato de cobre fraguado, el cual fue triturado al aire libre y luego fue almacenado para su posterior análisis. La segunda muestra es un sulfato de cobre que fue sometido a un proceso de desecado a 200°C por 2 horas, esto para poder reconstituirlo y obtener así un producto similar al comercial. La tercera muestra es un sulfato de calcio comercial, el cual no fue sometido a ningún procedimiento previo. 

En el caso de la primera muestra de sulfato de calcio se eliminó la aportación de K-alpha dentro del software de Origin para luego ser analizada dentro del software de Profex, esto dio como resultado el los siguientes valores dentro del software: 
![[Pasted image 20260316202331.png]]

Estos valores son bastante buenos, pero se encuentran un poco elevados (en el caso de Rwp y Rexp), por lo que se intentó reducirlos y obtener un valor correcto solo aplicando filtros dentro de Profex, esto dio como resultados los siguientes valores obtenidos: 
![[Pasted image 20260322193542.png]]
Para las siguientes muestras solo se trabajo dentro de Profex debido a que se lograban obtener valores bastante buenos, además de que se obtuvieron prácticamente los mismos resultados con ambas muestras, lo que remarca que se logó obtener un reactivo bastante bueno a través del proceso de recuperación. En este caso se lograron obtener los siguientes resultados dentro del software de Profex al aplicarle solo un filtro de Smooth: 

| Muestra 1-1                          | Muestra 2-2                          |
| ------------------------------------ | ------------------------------------ |
| ![[Pasted image 20260322193831.png]] | ![[Pasted image 20260322193846.png]] |
## Resultados 

En este caso se obtuvieron los siguientes tamaños de grano y esfuerzos : 

| Muestra                         | Tamaño de Cristal   | Ecuaciones H-W                                  | Esfuerzos            |
| ------------------------------- | ------------------- | ----------------------------------------------- | -------------------- |
| Sulfato de cobre recristalizado | $48.59~\text{nm}$   | $-2.0\times 10^{-3}\text{x}+4.9\times 10^{-3}$  | $23.5192~\text{Mpa}$ |
| Sulfato de cobre comercial      | $52.85~\text{nm}$   | $-0.185\text{x}+0.271$                          | $23.5192~\text{MPa}$ |
| Sulfato de Calcio Fraguado      | $53.3635~\text{nm}$ | $2.69\times 10^{-4}\text{x}+2.7\times 10^{-3}$  | $10.76~\text{MPa}$   |
| Sulfato de Calcio Recuperado    | $84.19 ~ \text{nm}$ | $2.68\times 10^{-3}\text{x}+1.72\times 10^{-3}$ | $107.2~\text{MPa}$   |
| Sulfato de Calcio Comercial     | $84.19 ~ \text{nm}$ | $2.68\times 10^{-3}\text{x}+1.72\times 10^{-3}$ | $107.2~\text{MPa}$   |
Sumado a esto se logró encontrar que las muestras estaban relacionadas con las siguientes tarjetas cristalográficas de "Crystallography Open Database" o COD: 

| Tarjeta     | Sistema Cristalino | Grupo Espacial | Parámetros de celda                           | Nombre       | Muestra relacionada                         |
| ----------- | ------------------ | -------------- | --------------------------------------------- | ------------ | ------------------------------------------- |
| 00-901-4405 | Triclínico         | P-1            | 6.12; 10.7; 5.97  <br>82.27; 107.43; 102.67   | Chalcanthite | Sulfato de cobre comercial y recristalizado |
| 00-230-0258 | Monoclínico        | C12/c1         | 6.28689; 15.2131; 6.52996  <br>90; 127.43; 90 | Gypsum       | Sulfato de calcio fraguado                  |
| 00-901-2211 | Monoclínico        | I 1 2 1        | 11.9845; 6.9292; 12.7505  <br>90; 90; 90      | Bassenite    | Sulfato de calcio recuperado                |
| 00-901-2209 | Monoclínico        | I 1 2 1        | 12.0317; 6.9269; 12.6712  <br>90; 90.27; 90   | Bassenite    | Sulfato de calcio comercial                 |


