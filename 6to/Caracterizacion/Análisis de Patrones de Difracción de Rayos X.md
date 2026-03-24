## Objetivo

La difracción de rayos x es un método de caracterización que permite identificar que substancias componen a una determinada muestra e inclusive permite conocer que fases se encuentran presentes dentro de la misma. En este caso se analizaron 5 muestras, las cuales tenían diferentes características y procedencias, estos cambios podían llegar a influir tanto en su composición como en las fases presentes, por lo que al momento de realizar un patrón de difracción de rayos x se buscaba poder encontrar información relacionada con la composición de las muestras. 
## Metodología 

Para comenzar se realizó un patrón de difracción de rayos X de cinco muestras, dos de sulfato de cobre ($CuSO_{4}$) y tres de sulfato de calcio($CaSO_{4}$). Las muestras provenían de un  mismo proveedor de productos de limpieza, la principal diferencia entre las mismas es que una fue sometida a un proceso de purificación conocido como *recristalización* el cual se teorizaba que aumentaría su pureza. 

En el caso de las muestras de sulfato de cobre, estas provenían de diferentes etapas de un proceso de reconstitución del mismo. La primera muestra es del material inicial, el cual es sulfato de cobre que fue sometido a un proceso de rehidratación y se encuentra completamente fraguado. La segunda muestra es un yeso que fue sometido a un proceso de desecado, donde se eliminó el agua que fue utilizada para realizar el proceso de fraguado, esto para poder ser reutilizado en el futuro. La tercera muestra es una muestra control de un yeso comercial que es químicamente idéntico al yeso que fue utilizado en las otras muestras. 

Para poder realizar el proceso de difracción  de rayos X las muestras fueron sometidas a un procesamiento previo antes de ser colocadas dentro del difractómetro; este proceso consistió en triturar las muestras para poder obtener un polvo relativamente fino para facilitar su análisis. En el caso de la muestra de sulfato de cobre comercial y del sulfato de calcio comercial no se tuvo que realizar ningún proceso previo a su análisis, esto debido a que ya se encontraban en polvo. Para las muestras de sulfato de cobre recristalizado, sulfato de calcio fraguado y sulfato de cobre reconstituido se tuvo que realizar un proceso de molido que varió en su rigurosidad; para el sulfato de cobre se utilizo un mortero que fue previamente lavado y secado mientras que para el sulfato de calcio se utilizó un martillo y una bolsa de plástico debido a que se tenía una mayor cantidad de material, una fracción del material molido inicial fue analizada mientras que otra fracción fue desecada para ser analizada posteriormente. 
![[Pasted image 20260323223421.png|Figura 1: Proceso de molido del sulfato de cobre.|275]]

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
![[Pasted image 20260316201119.png|Figura 2: Resultados obtenidos del sulfato de cobre recristalizado.]]
En un intento de poder reducir más los valores de GoF y $\chi^2$ se busco realizar todo el proceso dentro de Profex para poder evitar cualquier interferencia entre los softwares, esto dio como resultado lo siguiente: 
![[Pasted image 20260322181803.png|Figura 3: Resultados obtenidos con la segunda metodología para el sulfato de cobre recristalizado.]]
Estos mismos procedimientos fueron realizados para las muestras que no fueron recristalizadas, dando como resultado los siguientes valores: 

| Primera metodología                                                                                  | Segunda metodología                                                                                   |
| ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| ![[Pasted image 20260322184244.png]]                                                                 | ![[Pasted image 20260322184305.png]]                                                                  |
| Figura 4: Resultados obtenidos con <br>la primera metodología para el sulfato<br>de cobre comercial. | Figura 5: Resultados obtenidos con <br>la segunda metodología para el sulfato <br>de cobre comercial. |
Debido a que se obtuvieron valores altos tanto en GoF como en $\chi^2$ se cree que existe una tendencia en el acomodo de los planos de ambas muestras; esto se puede deber a muchos motivos, los cuales van desde la forma en la que se colocó la muestra dentro de los aparatos de medición como posibles crecimientos anormales debido al proceso de recristalización. 

### Sulfato de Calcio ($CaSO_{4}$)

En el caso del sulfato de calcio se tuvieron 3 muestras, las cuales tuvieron diferentes procesos de refinamiento y análisis dentro de los softwares presentados anteriormente. La primera muestra es un sulfato de cobre fraguado, el cual fue triturado al aire libre y luego fue almacenado para su posterior análisis. La segunda muestra es un sulfato de cobre que fue sometido a un proceso de desecado a 200°C por 2 horas, esto para poder reconstituirlo y obtener así un producto similar al comercial. La tercera muestra es un sulfato de calcio comercial, el cual no fue sometido a ningún procedimiento previo. 

En el caso de la primera muestra de sulfato de calcio se eliminó la aportación de K-alpha dentro del software de Origin para luego ser analizada dentro del software de Profex, esto dio como resultado el los siguientes valores dentro del software: 
![[Pasted image 20260316202331.png|Figura 6: Resultados obtenidos para la primera metodología en el sulfato de calcio fraguado.]]

Estos valores son bastante buenos, pero se encuentran un poco elevados (en el caso de Rwp y Rexp), por lo que se intentó reducirlos y obtener un valor correcto solo aplicando filtros dentro de Profex, esto dio como resultados los siguientes valores obtenidos: 
![[Pasted image 20260322193542.png|Figura 7: Resultados obtenidos con la segunda metodología en el sulfato de calcio fraguado.]]

Para las siguientes muestras solo se trabajo dentro de Profex debido a que se lograban obtener valores bastante buenos, además de que se obtuvieron prácticamente los mismos resultados con ambas muestras, lo que remarca que se logó obtener un reactivo bastante bueno a través del proceso de recuperación. En este caso se lograron obtener los siguientes resultados dentro del software de Profex al aplicarle solo un filtro de Smooth: 

| Muestra 1-1                                                                                                | Muestra 2-2                                                                                           |
| ---------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| ![[Pasted image 20260322193831.png]]                                                                       | ![[Pasted image 20260322193846.png]]                                                                  |
| Figura 8: Resultados obtenidos con <br>la segunda metodología para el <br>sulfato de calcio reconstituido. | Figura 9: Resultados obtenidos con la<br>segunda metodología para el sulfato de <br>calcio comercial. |
## Resultados 

Al utilizar el software de Profex se logró poder comparar los patroness de difracción de difracción de rayos x con diferentes bases de datos, esto permitió obtener los siguientes resultados en relación a la fase presente en las muestras. Estos resultados permitieron a su vez poder encontrar las tarjetas cristalográficas pertenecientes a la base de datos "Crystallography Open Database", con la cual se obtuvieron los planos relativos de cada uno de los picos considerados. 

| Tarjeta     | Sistema Cristalino | Grupo Espacial | Parámetros de celda                           | Nombre       | Muestra relacionada                         |
| ----------- | ------------------ | -------------- | --------------------------------------------- | ------------ | ------------------------------------------- |
| 00-901-4405 | Triclínico         | P-1            | 6.12; 10.7; 5.97  <br>82.27; 107.43; 102.67   | Chalcanthite | Sulfato de cobre comercial y recristalizado |
| 00-230-0258 | Monoclínico        | C12/c1         | 6.28689; 15.2131; 6.52996  <br>90; 127.43; 90 | Gypsum       | Sulfato de calcio fraguado                  |
| 00-901-2211 | Monoclínico        | I 1 2 1        | 11.9845; 6.9292; 12.7505  <br>90; 90; 90      | Bassenite    | Sulfato de calcio recuperado                |
| 00-901-2209 | Monoclínico        | I 1 2 1        | 12.0317; 6.9269; 12.6712  <br>90; 90.27; 90   | Bassenite    | Sulfato de calcio comercial                 |
A partir de esta información se pudo obtener el tamaño de grano y el esfuerzo; para esto se realizó un análisis Williamson-Hall. Dentro de este análisis se utilizó Origin para poder extraer los datos del patrón de difracción y que de esta forma se pudiera obtener information más precisa y fácil de manejar. Para poder realizar el cálculo de los esfuerzos presentes en el cristal se consideró que el sulfato de calcio ($CaSO_{4}$) tiene un modulo de Young de $40~\text{GPa}$ y el sulfato de cobre ($CuSO_{4}$) de $76.86~\text{GPa}$, esto permitió obtener los siguientes resultados:

| Muestra                         | Tamaño de Cristal   | Ecuaciones H-W                                  | Esfuerzos            |
| ------------------------------- | ------------------- | ----------------------------------------------- | -------------------- |
| Sulfato de cobre recristalizado | $48.59~\text{nm}$   | $-2.0\times 10^{-3}\text{x}+4.9\times 10^{-3}$  | $23.5192~\text{Mpa}$ |
| Sulfato de cobre comercial      | $52.85~\text{nm}$   | $-0.185\text{x}+0.271$                          | $23.5192~\text{MPa}$ |
| Sulfato de Calcio Fraguado      | $53.3635~\text{nm}$ | $2.69\times 10^{-4}\text{x}+2.7\times 10^{-3}$  | $10.76~\text{MPa}$   |
| Sulfato de Calcio Recuperado    | $84.19 ~ \text{nm}$ | $2.68\times 10^{-3}\text{x}+1.72\times 10^{-3}$ | $107.2~\text{MPa}$   |
| Sulfato de Calcio Comercial     | $84.19 ~ \text{nm}$ | $2.68\times 10^{-3}\text{x}+1.72\times 10^{-3}$ | $107.2~\text{MPa}$   |

## Conclusiones 

Gracias a el proceso de caracterización que se realizó a las muestras se pudo obtener su composición y las fases que tiene presente, en ambos casos logó comprobar que había habido un cambio entre el material inicial y el material procesado; esto es de suma importancia por que permite comprobar que se mejoró la calidad de los reactivos utilizados en esa prueba. 

## Discusión de Resultados 

Las muestras de sulfato de cobre presentan un valor tanto de $\chi^2$ como de GoF relativamente elevado; este valor no pudo ser reducido con ayuda de las herramientas presentes en los softwares utilizados sin tener un comprometimiento de la fiabilidad de los datos. Estos valores pueden ser altos debido a la presencia de un acomodo preferencial de los planos presentes en los cristales. El acomodo preferencial de los planos puede surgir por la forma en la que se colocó la muestra dentro del difractómetro, esto debido a que se pudo llegar a presionar generando un acomodo preferencial en ciertos planos, dando como resultado mayor dificultad para poder analizarlo en el software. Otro posible factor que puede alterar los resultados son la forma en la que se obtuvo la muestra de sulfato de cobre recristalizado, esto debido a que fue recristalizado en una caja Petri, lo que generó que tuviera un crecimiento preferencial en solo dos dimensiones, generando que se amplificaran picos que evitaran poder reducir de forma satisfactoria esos picos. 

![[Pasted image 20260324091032.png|Figura 10: Crecimiento bidimensional del sulfato de cobre.|299]]
