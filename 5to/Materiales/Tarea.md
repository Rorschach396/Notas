En esta tarea se tienen las siguientes medidas para la mesa, estas medidas se considerarán para poder obtener una relación entre el tamaño de las patas y el peso que deben poder soportar para poder desempeñar correctamente sus funciones: 

![[Pasted image 20251201003445.png]]

A pesar de que se menciona que se tienen un ancho de 12.7 mm en el ejercicio consideramos que la medida estándar de patas de una mesa es de 32 mm. Dentro del software del CES Edupack se consideró que el material tendría una relación su modulo de young y su densidad, esto para poder obtener un gráfico donde se pudieran aplicar los filtros que consideramos necesarios (en este caso dos rectas, una con pendiente 2 debido al cambio que tiene respecto a la esbeltez y una con pendiente 0 para poder eliminar materiales poco factibles). 

Dentro de los cálculos realizados consideramos que las patas tienen un volumen de 7.1684e-4 m^3
esto nos da como resultado lo siguiente tomando en consideración los datos presentados en el software: 

| Material                                            | Densidad (kg/m3) | Modulo de Young | Peso |
| --------------------------------------------------- | ---------------- | --------------- | ---- |
| Madera blanda                                       | 440              | 26.9            | 1.2  |
| Bambú                                               | 602              | 40.4            | 1.7  |
| Madera contrachapada                                | 700              | 12.3            | 2    |
| Madera dura                                         | 850              | 21.7            | 2.4  |
| Material compuesto (CFRP)                           | 1500             | 836             | 4.3  |
| Material compuesto de carburo de silicio y aluminio | 2660             | 167             | 7.6  |
Gracias a estos valores podemos encontrar que el material más factible para esta aplicación sería la madera blanda de pino para poder obtener la menor masa sin tener que limitar por completo el modulo de young. 

A la hora de realizar los calculos para poder minimzar el área, se vió que a pesar de que se consideraba una cantidad excesiva de peso (en teoría), todos los materiales pasaban sin ningun tipo de problema a la hora de realizar el calculo con un área transversal de la pata de 1e-4 m2. Debido a que no se pudieron eliminar materiales a través de este método se decidió aplicar un filtro adicional relacionado con el costo de cada uno de los materiales, esto permitió que se eliminaran una gran cantidad de materiales. 


| Material              | Precio por kg |
| --------------------- | ------------- |
| Madera blanda de pino | 26.4          |
| Bambú                 | 40.4          |
| Madera contrachapada  | 12.3          |
Gracias a este filtro se propone que las patas estén hechas de bambú, esto debido a que tienen una mejor apariencia, un modulo de young bastante bueno y debido a que normalmente están hechas las patas de este material. 
