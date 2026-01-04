
# Presentación 1 
# La máquina de Extrusión 

La extrusión es un proceso de conformado **continuo** en el cual un **polímero** en estado **fundido** es forzado a pasar con **presión y temperaturas** a través de un **orificio** de salida que le da **forma**. Este proceso suele constituir la fase previa de un proceso de conformado más complejo, donde la forma final es alcanzada tras procesos sucesivos post-extrusión. Normalmente el proceso de extrusión se encuentra compuesto por las siguientes partes: 

![[Pasted image 20251103222154.png]]

En el caso de la máquina de extrusión se puede encontrar que se tienen las siguientes partes: 
![[Pasted image 20251103222243.png]]

Esta máquina lleva en total 6 operaciones(antes de estas operaciones se llevan operaciones previas (como acondicionamiento  y dosificación) y después de estas se llevan a cabo operaciones posteriores (como calibración y refrigeración)) , las cuales son las siguientes: 
1) Transporta el polímero sólido 
2) Lo funde 
3) Lo bombea o impulsa 
4) Lo mezcla y homogeniza 
5) Lo desgasifica 
6) Lo conforma

## Tolva

- Es el deposito de pellets (pequeñas piezas de polímero).
- Alimentan gracias a la gravedad.
- El ángulo de reposo debe de ser < 45°.
- Para poder disminuir la fricción entre la tolva y los pellets (al igual que la fricción entre los pellets mismos) se pueden utilizar vibradores o tolvas especiales. 
- Existen de diferentes formas, entre las cuales se encuentran las cuadradas y las circulares, entre estas se suelen preferir las circulares debido a que tienen una transición gradual en la zona cónica de la tolva. También se pueden tener tolvas forzadas, las cuales utilizan un tornillo sin fin para poder mejorar el flujo de los pellets. 
- Su flujo puede ser en masa (materiales similares) o en embudo (materiales mixtos, que pueden ser gránulos, escamas, polvos, etc.)
- Se recomienda colocar imanes en la tolva para poder eliminar cualquier tipo de basura metálica que pueda interferir en el proceso. 
- Se recomienda agregar refrigeración a la garganta de la tolva para poder evitar que el polímero pueda llegar a derretirse en esa zona.  ^3e99fb
- Para poder ayudar a la limpieza de la máquina se puede incluir un sistema de cierre para la garganta de la tolva para poder facilitar la limpieza de la misma. 
![[Pasted image 20251104082029.png]]


| ![[Pasted image 20251104082043.png]] | ![[Pasted image 20251104082055.png]] |
| ------------------------------------ | ------------------------------------ |
## Camisa 

^a1c110

La camisa (también conocida como cilindro o cañón) es la parte que recubre al husillo; esta generalmente tiene un recubrimiento bimetálico de alta dureza para poder evitar el desgaste (normalmente se termina desgastando el husillo, pero este es mucho más fácil de cambiar). Al rededor de esta parte se coloca la calefacción. 

## Calefacción y refrigeración 

En las máquinas de extrusión se suelen utilizar bandas de calefacción (entre 3 y 8 bandas por máquina) para poder ayudar al husillo a derretir el polímero. A pesar de que se utiliza este tipo de calefacción, normalmente se suele acompañar con un sistema de enfriamiento utilizado para poder extraer el calor en ciertas partes del proceso (como se mencionó en la sección [[Guía Materiales Poliméricos#^3e99fb]]) además de que se ha visto que las máquinas tienen un mejor desempeño cuando casi toda la energía utilizada en el proceso proviene del husillo. 

## Husillo 

El husillo es el elemento principal para la extrusora, este consta de un cilindro largo con un filete helicoidal (como el de los tornillos) alrededor suyo, este gira en el interior del cilindro ajustado llamado camisa o cámara (mencionada en [[Guía Materiales Poliméricos#^a1c110]]); dependiendo del husillo se pueden tener variaciones en el proceso y en la calidad del producto extruido, por lo que todo el proceso depende del diseño del mismo. 

Este tiene las siguientes **funciones**: 
- **Transportar**
- **Calentar** 
- **Fundir** 
- **Mezclar** 
El husillo presenta un diámetro constante en el filete helicoidal, pero en el caso del núcleo este es variable: 
![[Pasted image 20251104084857.png]]

Para esto existe una relación entre el largo del husillo y el diámetro del mismo, esta relación determina la calidad del producto final (si es muy corta no se mezcla bien, si es muy larga se degrada el polímero), las longitudes más comunes suelen ser las siguientes: 

- 6D para husillos de transporte y procesado de cauchos 
- 25 - 30D normalmente utilizados en extrusoras industriales 
- 100D en casos muy especiales. 
En este caso se tiene una relación de compresión debido al cambio de volumen presente en el husillo (si se compara la parte inicial con la final). Esta relación permite hacer una clasificación de las zonas del husillo que sería de la siguiente forma: ![[Pasted image 20251104092005.png]]

- Zona de alimentación: Parte de transporte de los pellets donde se compactan, precalentándolos y transportándolos a la zona de compresión, el material se logra transportar gracias a la fricción que existe entre la camisa y el polímero, lo que permite que se presente un movimiento entre los dos. 
- Zona de compresión: En esta parte específica se produce la plastificación del material, donde el mismo se funde y homogeniza, en esta se puede tener dos tipos de fundido: 
	- Se forma una fina capa fundida entre la camisa y el lecho sólido dando como resultado el fundido del material que se mueve en el flanco activo, este presenta un mecanismo en el cual se arrastra nuevo material al lecho fundido mientras que la capa de fundido que se encuentra en contacto con la camisa permanece delgada  y se mantiene una alta velocidad de fusión. 
	- ![[Pasted image 20251104092727.png]]
	- Se da cuando las partículas sólidas son dispersadas en una matriz fuñida, con lo que se consigue una progresiva disminución de tamaño de las partículas sólidas (como disolver azúcar en café). 
	- En el caso de que la principal fuente de calor sean las bandas calefactoras se puede conseguir que el material fundido se mueva al lecho fundido gracias a la fricción entre el plástico y la camisa, generando que se derrita de forma homogénea, mientras que si se obtiene la fuente principal de calor de una zona diferente se puede disminuir su efecto debido a que el polímero actúa como aislante. 
	- Es importante controlar de forma precisa el calor que es suministrado a través de las bandas calefactoras, esto debido a que si se suministra una gran cantidad de calor a través de las mismas se puede llegar a eliminar el calentamiento por viscosidad, dando como resultado que no se logre derretir de forma eficiente el polímero. 
- Zona de dosificación: Esta zona ejerce presión sobre el material para dosificarlo hacia el cabezal, en esta zona es necesario reducir levemente la temperatura de la camisa para poder obtener un mejor resultado; esta fase es en la que se logra homogeneizar las propiedades de salida del polímero (temperatura, presión, etc.)
Para poder determinar el desgaste presente en el husillo se tiene que determinar la holgura ($\gamma$) que existe entre el husillo y la camisa, para luego relacionarla con la profundidad del canal (h). Se puede mejorar la eficiencia del proceso si se modifica el husillo, las principales modificaciones que se pueden realizar son las siguientes: 
- Cambio en el diseño del husillo 
- Aumentado de temperatura del husillo 
- Modificación del material a través de tratamientos térmicos (nitrurados)
Para poder tener un mejor control de las temperaturas presentes en la tolva se puede agregar un sistema de enfriamiento dentro del husillo para poder controlar de forma más precisa en esa parte (no se hace en todo el husillo por que compromete la resistencia del husillo). 

En el caso del husillo se tiene que tener en cuenta que las diferentes secciones tienen valores preferentes para poder obtener un buen funcionamiento de la máquina: 
- Alimentación: H óptimo = 15-20%, $\phi$ óptimo= 15-25°
- Compresión: L $\approx$ 5 - 10 D, $\phi$ óptimo = 20-30°, $\gamma$ = 0.1% D 
- Dosificación: L $\approx$ 10 D, H óptimo 5 - 10% D, $\phi$ óptimo= 20 - 30°
Durante el proceso de extrusión se puede dar la desgasificación del polímero en una sección específica del husillo, en esta se reduce levemente la presión para poder dejar escapar los gases presentes en el polímero, estos pueden ser: 
- Humedad 
- Monómero residual 
- Productos de la degradación 
- Productos de reacción 
![[Pasted image 20251104150024.png]]

## Plato Rompedor 

^af2377

Es una pieza metálica con agujeros que se encuentra al final del husillo, esta tiene la función de: 
- Evitar el flujo helicoidal inducido al plástico por el giro del husillo 
- Sujetar una serie de filtros o paquete de mallas 
- Aumentar la presión del polímero 
## Paquete de mallas

Su función principal (además de filtrar) es aumentar el grado de mezclado ya que impide el paso de pellets no fundidos, estas ultimas dos partes (plato rompedor y paquete de mallas) permiten obtener una mejor velocidad de producción debido a que permiten aumentar la presión, además de que dependiendo de la producción se puede saber si el polímero contenía una gran cantidad de impurezas. 

## Boquilla 

Se sitúa al final de extrusora con la misión de dar forma deseada al plástico, esta pueden clasificar de las siguientes formas: 
- Boquillas anulares para poder realizar tubos, tuberías y recubrimiento de cables 
- Boquillas planas para obtener planchas y películas 
- Boquillas circulares para obtener barras y fibras. 
## Cabezal de extrusión

Es el lugar de descarga del material, su función es dar forma al flujo de plástico en la forma deseada del producto extruido a través de un dado; este normalmente consta de una placa de acero perforado conocida como placa rompedora y juego de mallas (como se vio en [[Guía Materiales Poliméricos#^af2377]])
## Tipo de ejercicio 1

Para poder realizar el estudio del movimiento de un material viscoso en el husillo de una extrusora, se pueden simplificar los tipos de flujo en las siguientes categorías: 

- Caudal de arrastre: Se da por la fricción entre la camisa y el polímero en dirección del cabezal
- Caudal de presión: Generado por la diferencia de presiones entre el cabezal  y la tolva (en dirección a la tolva). 
- Caudal de pérdidas: Se da en la holgura entre el filete del tornillo y la camisa (en dirección a la tolva). 
Debido a la fricción presente entre el la camisa y el husillo se tienen las siguientes velocidades: 
![[Pasted image 20251104203015.png]]

El análisis de este flujo nos lleva a la siguiente fórmula: 

$$
\begin{gather}
Q = \frac{1}{2} \pi^2 D^2 NH\sin \phi \cos \phi - \frac{\pi DH^3\sin^2\phi}{12L} \frac{\Delta P}{\eta} \\
\end{gather}
$$
En esta ecuación podemos encontrar el siguiente significado en las variables: 

- D: diámetro del husillo 
- H: Distancia entre el husillo y la camisa 
- N: Revoluciones por minuto 
- $\phi$: Ángulo del filete del husillo
- L: Longitud del husillo 
- P: Presión (se debe de considerar que la presión atmosférica es 101325 Pa)
- $\eta$: Viscosidad del polímero 
- Q se encentra en $\frac{m^3}{hr}$ 

Para poder calcular el punto de operación se debe de considerar lo siguiente: 

$$
\begin{gather}
\text{Consideramos la descarga libre (Qmax):} \\
Q_{max} = \frac{1}{2}\pi^2D^2NH\sin \phi \cos \phi \\
\text{Consideramos el caudal nulo (Pmax):} \\
P_{max}= \frac{6\pi DLN\eta}{H^2\tan \phi}  \\
\text{Los valores de las variables de estas formulas se encuentran en la lista de arriba. }
\end{gather}
$$
Esto nos permite obtener una gráfica como la siguiente (se considera un posible valor móvil del N): 

![[Pasted image 20251104204901.png]]

Para poder encontrar el punto de operación se tiene que considerar el caudal a través de la boquilla para un fluido newtoniano, esto está dado por la siguiente formula: 

$$
\begin{gather}
Q= (K_{B})(\Delta P)
\end{gather}
$$
Donde: 
- $K_{B}$: Es un valor determinado por la geometría de la boquilla. 

En este caso esto da como resultado una recta que, al intersecar con las rectas presentes anteriormente nos da el punto de operación: 

![[Pasted image 20251104205339.png]]

Se tiene que considerar que estas líneas están algo "cuchareadas" debido a que en la vida real las líneas no serían completamente rectas. 

## Tipo de ejercicio 2 

Para este tipo de ejercicios normalmente se suele pedir que calculemos el número de devora para poder determinar si el polímero tendrá algún efecto residual a causa del proceso de extrusión. Para comenzar tenemos que calcular lo siguiente: 

$$
\begin{gather}
\dot{\gamma} = \frac{4Q}{\pi R^3} \left(\frac{3n+1}{4n}\right)
\end{gather}
$$
Donde: 
- Q es el caudal
- R es el radio de la boquilla 
- n es el índice de flujo a una determinada temperatura 
Con este valor y con ayuda de las siguiente grafica se puede obtener el valor de G y de $\eta$. 
![[Pasted image 20251104214029.png]]

Gracias a que con esta grafica se puede obtener el valor de G y $\eta$ podemos utilizar la siguiente formula para poder obtener el número de devora: 

$$

\begin{gather}
N_{De} = \frac{t_{rel}}{t_{proc}} \\
t_{rel}= \frac{\eta}{G} \\
\text{Podemos obtener el tiempo de proceso de la siguiente forma:} \\
v = \frac{Q}{\text{seccion}} \rightarrow v = \frac{L}{t} \rightarrow t_{proc} = \frac{L}{v} \\
\text{Obteniendo asi los valores para el numero de devora} \\
N_{De} = \frac{t_{rel}}{t_{proc}}
\end{gather}

$$
## Tipo de ejercicio 3

En este tipo de ejercicio se dan las dimensiones de una boquilla para extrusion, esto lo que permite obtener es: 

$$
\dot{\gamma} = \frac{6Q}{TH^2}
$$
Donde
- T es el perímetro del tubo 
- H es el espesor del tubo 

Con este valor se vuelve a utilizar la gráfica para poder encontrar el valor de G y $\tau$, con lo que encontramos la siguiente relación: 

$$
\begin{gather}
\gamma = \frac{\tau}{G}
\end{gather}
$$
Con este valor podemos utilizar la siguiente gráfica: 

![[Pasted image 20251104220435.png]]

Con estos valores se puede obtener el nuevo diámetro del tubo si se multiplica el $B_{st}$ por el diámetro y $B_{SH}$ multiplicado por el espesor del tubo nos da el nuevo espesor. 
