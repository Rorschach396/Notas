Esto es la ruta crítica, el cual determina cuales son las actividades que se tienen que ir realizando para poder  terminar un determinado proyecto 


| Actividad | Predecesora | Tiempo |
| --------- | ----------- | ------ |
| A         |             | 3      |
| B         | A           | 2      |
| C         |             | 5      |
| D         | B,C         | 2      |

En el caso de las actividades predecesoras, son las actividades que se tienen que realizar antes de realizar esas actividades. Se tiene que ir haciendo la sumatoria de los tiempos que toma cada actividad, considerando que se tienen 2 rutas de entrada a una determinada actividad (como en el caso de D) se considera la mayor cantidad de tiempo posible. 

Holgura = 0 se tiene una ruta critica (la holgura se obtiene restando el tiempo del final a los tiempos que tiene cada actividad), las holguras son la cantidad máxima de tiempo que nos podemos atrasar con la entrega de una determinada actividad. 