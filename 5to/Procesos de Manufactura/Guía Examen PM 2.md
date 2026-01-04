# Análisis Básico de los Procesos de Maquinado 

Las máquinas/herramientas tienen la principal función de **arrancar material** para poder darle **forma al material** que se quiere mecanizar, estas normalmente se pueden clasificar de la siguiente forma: 
- Máquinas/herramientas de movimiento circular: Estas máquinas/herramientas son más utilizadas normalmente en la industria debido a que pueden realizar un mayor arranque de material, haciendo así que tengan un mayor rendimiento y producción.
	- Con el movimiento de corte en la pieza: Torno (vertical o paralelo). 
	- Con el movimiento de corte en la herramienta: Fresadora, taladradora y mandrinadora 
- Máquinas/herramientas de movimiento rectilíneo: Cepillo, mortajadora y brochadora.

Ambos tipos de máquinas se pueden controlar de las siguientes formas: 
- Por un operario si las máquinas son manuales.
- De forma neumática, hidráulica o eléctrica.
- Mecánicas (con levas o un sistema similar).
- Por computadora (control numérico).

Para poder hacer que las máquinas le puedan dar forma a una pieza es necesario que se tengan **movimientos de trabajo** con una determinada **velocidad**, este movimiento se puede encontrar en la pieza, en la herramienta o en ambas al mismo tiempo. Los principales movimientos de trabajo necesarios para que se pueda tener el corte de material son los siguientes: 
- Movimiento de corte (Mc): Movimiento relativo entre la pieza y la herramienta, es paralelo a la nueva superficie creada por el mismo. 
- Movimiento de penetración (Mp): Es el movimiento que acerca la herramienta a la pieza que se esta trabajando, este determina la profundidad del corte. 
- Movimiento de avance (Ma): Movimiento que va poniendo nuevo material para poder arrancarlo con la herramienta. 
![[Pasted image 20251110215429.png]]

También se pueden tener los siguientes casos de movimientos de las maquinarias convencionales: 
- Movimiento de torno 
- Movimiento de fresadora
- Movimiento de taladradora 
- Movimiento de rectificadora 
Estos movimientos se deben de ver complementados con la **velocidad de corte** que es la velocidad de los puntos de la pieza respecto a la herramienta (o de la herramienta respecto a la pieza), esta está medida en m/min, esta (al igual que muchos otros parámetros que se verán más adelante) depende de: 
- Material de la pieza a trabajar 
- Material del filo de la herramienta 
- Refrigerante usado 
- Tipo de operación a realizar 
- Profundidad y avance del corte
La velocidad de corte normalmente ya está dada en tablas dependiendo del material y de la herramienta, pero esta guarda una estrecha relación matemática con la **velocidad de giro** y con el diámetro de la herramienta: 
$$
V_{c} = \frac{\pi d N}{1000} \rightarrow N = \frac{1000V_{c}}{\pi d}
$$
Donde: 
- $V_{c}$ = Velocidad de corte (m/min)
- d = Diámetro de la pieza o de la herramienta (mm)
- N = Velocidad de giro (rpm)

Complementando a la velocidad de corte se tiene el avance, que se puede estudiar de dos formas diferentes: 
- **Velocidad de avance ($a_{min}$)**: Longitud de desplazamiento de la herramienta respecto a la pieza (o de la pieza respecto a la herramienta) por unidad de tiempo (normalmente por cada minuto). 
- **Avance($a_{v}$)**: Es la distancia que se mueve la herramienta respecto a la pieza (o de la pieza respecto a la herramienta) en una sola vuelta o pasada. 
Estas dos formas de estudio guardan la siguiente relación matemática: 
$$
a_{v} = \frac{a_{min}}{N} \rightarrow a_{min} = a_{v}N
$$
Donde: 
- $a_{v}$ = Avance por vuelta
- $a_{min}$ = Avance por minuto
- N = Velocidad de giro en rpm 

En el caso del fresado, se expresa de diferente forma la velocidad de avance y el avance: 

$$
a_{v} = a_{z}Z \quad a_{min}= a_{v}N = a_{z}ZN
$$

Donde: 
- Z = Numero de dientes cortantes de la fresa 
- $a_{z}$ = Avance por diente de la fresa 
- $a_{v}$ = Avance por vuelta de la fresa 
- $a_{min}$ = Avance por minuto de la fresa

En el caso del fresado el avance depende de los siguientes factores: 
- Acabado que se quiera obtener 
- Potencia de la maquina 
- Sujeción de la herramienta o de la pieza 
- Rigidez de la maquina 
- Relación con la profundidad de pasada 

La formula para poder calcular  la potencia consumida es la siguiente: 
$$
\dot{W} = w \dot{z}=wbdf
$$
Donde: 

- w = Energía específica 
- b = Ancho del corte 
- d = Profundidad del corte 
- f = Velocidad de avance de la pieza 
- $\dot{z}$ = Volumen total de material eliminado por unidad de tiempo
- $\dot{W}$ = Potencia consumida

La formula para el tiempo de mecanizado es la siguiente 
$$
%%por que ves esto bro??, acaso no tienes la extencion de latex o estas moviendo mi fomula
\begin{gather}
t = l+\frac{2L_{c}}{f} \\
\text{Donde:} \\
l = \text{Longitud de corte} \\
L_{c} = \text{Longitud de la fresa hasta que toma contacto con la pieza}
\end{gather}
$$
La **profundidad de pasada** es la longitud que penetra la herramienta (obviamente en la pieza) en cada pasada, esta depende de lo siguiente: 
- Material de la pieza 
- Material del filo de la herramienta 
- Refrigerante 
- Tipo de operación 
- Avance
El concepto de profundidad de pasada puede adquirir ciertas particularidades dependiendo de la operación que se realice: 
- Torneado (Cilindrado): Es la diferencia de radios que hay al inicial y al terminar la pasada. 
- Fresado: Profundidad de pasada, está relacionado con el tipo de fresa empleada y el ancho de la pasada. 
- Torneado (Refrenado): Distancia (proyectada sobre el eje de rotación) entre las superficies planas iniciales y finales. 
- Torneado (coneado): Diferencia de cota antes y después de la pasada. 
- Torneado (Tronzado y ranurado): Profundidad de pasada, coincide con el ancho de la herramienta. 
- Taladrado: Profundidad de pasada en el taladro, coincide con el radio de la broca. 

Desde el punto de vista del corte, podemos clasificar las operaciones en dos categorías: 
- Operaciones de desbaste: Es el tipo de operación donde no se exige (en la superficie mecanizada) ningún tipo de tolerancia ni acabado superficial. 
- Operaciones de acabado: Es cuando se quiere obtener una medida exacta entre dos cotas bien definidas; cuando se quiere conseguir una calidad superficial determinada. 

# Teoría de Maquinado de Metales 

En el caso del maquinado, este es darle forma a un determinado material gracias al arranque de material conseguido con una herramienta de corte. Esta actividad involucra la deformación cortante a través del material de trabajo para poder formar virutas, al removerse la viruta se genera una nueva superficie. 

En el caso de las herramientas de corte, estas cuentan con uno o más filos cortantes, el cual debe de estar hecho de un material más duro que el material de trabajo. Cada filo tiene dos superficies determinadas: 
- Cara inclinada: Dirige el flujo de la viruta resultante, se orienta en cierto ángulo (conocido como ángulo de inclinación), el cual se mide respecto a un plano perpendicular a la superficie de trabajo. 
- Flanco de la herramienta: Provee un claro entre la herramienta y la superficie de trabajo recién generada, esto permite tener un mejor acabado; la superficie de flanco o de incidencia se orienta en un ángulo llamado *ángulo de incidencia o de relieve*. 
![[Pasted image 20251110225717.png]]

También se pueden tener diferentes tipos de herramientas: 
- De una sola punta (normalmente utilizadas para operaciones como el torneado)
- De múltiples puntas 

## Condiciones de corte

$$
R_{MR} = vfd
$$
Donde: 
- $R_{MR}$ = Tasa de remoción de material (mm^3/min)
- v = velocidad de corte (mm/seg)
- f = avance (mm)
- d = profundidad de corte

En el caso de las operaciones de maquinado, estas se dividen normalmente en dos categorías: 
- Cortes para desbaste primario: Se usan para poder remover grandes cantidades de material lo más rápido posible, pero se deja un excedente en la pieza para una operación posterior de acabado. 
- Cortes de acabado: Se usan para completar la pieza y alcanzar dimensiones finales, tolerancias y acabados. 

El modelo de corte ortogonal nos permite establecer una relación entre el espesor de la viruta, el ángulo de inclinación y el ángulo de plano de corte: 

$$
\begin{gather}
\text{Relacion de grueso de la viruta:} \\
r = \frac{t_{0}}{t_{c}} \\
t_{0} = \text{espesor de la viruta antes de su formacion} \\
t_{c} = \text{espesor de la viruta despues de su formacion} \\
r = \frac{l_{s}\sin (\phi)}{l_{s}\cos(\phi - \alpha)} = \frac{\sin(\phi)}{\cos(\phi-\alpha)} \rightarrow \tan(\phi) = \frac{r\cos(\alpha)}{1-r\sin(\alpha)}  \\
\text{Ángulo de inclinación} = \alpha\\
\text{Ángulo de incidencia/ángulo de plano de corte /ángulo de claro} = \phi\\ 
\gamma = \frac{AC}{BD} = \frac{AD+DC}{BD} = \tan(\phi - \alpha) + \cot(\phi) \\
\gamma = \text{Deformacion cortante para metales}
\end{gather}
$$
En el caso de la formación de la viruta se pueden tener diferentes casos: 

- Viruta discontinua: Cuando se maquinan materiales relativamente frágiles a bajas velocidades
- Viruta continua: Cuando se cortan materiales de trabajo dúctiles a velocidades altas con avances y profundidades pequeños 
- Viruta continua con acumulación en el borde: Cuando se maquinan materiales dúctiles a bajas velocidades 

Ecuación de Merchant 

$$
\begin{gather}
\varphi = \frac{\pi}{4}+\frac{\alpha-\beta}{2} \\
\alpha = \text{\'angulo de filo} \\
\beta = \text{\'angulo de fricci\'on} \rightarrow \mu = \tan(\beta)\\
\end{gather}
$$
Las fuerzas cortantes son las fuerzas que aplica la herramienta contra la viruta, se pueden separar en dos componentes: 
- Fuerza de fricción (F): Fuerza que resiste el flujo de la viruta a lo largo de la cara inclinada de la herramienta 
- Fuerza normal a la fricción (N): Es perpendicular a la fuerza de fricción, estos dos componentes se pueden utilizar para definir el coeficiente de fricción $\mu$ entre la herramienta y la viruta: 
$$
\mu = \frac{F}{N} = \tan ( \beta)
$$
Donde $\beta$ es el ángulo de fricción, también se puede calcular el esfuerzo cortante: 

$$
\tau = \frac{F_{s}}{A_{s}} \qquad A_{s}=\frac{t_{0}w}{\sin(\phi)}
$$
Donde :
- Fs es la fuerza cortante (fuerza causada por la deformación cortante)
- As es el área del plano de corte
También se tienen las siguientes relaciones: 

$$
\begin{gather}
F = F_{c}\sin(\alpha)+F_{t}\cos(\alpha) \\
N = F_{c}\cos(\alpha)-F_{t}\sin(\alpha) \\
F_{s} = F_{c}\cos(\phi)-F_{t}\sin(\phi) \\
F_{n}= F_{c}\sin(\phi) + F_{t}\cos(\phi)
\end{gather}
$$

Una operación de producción en el maquinado requiere potencia, la fuerza de corte en una operación de maquinado puede exceder 1000N, las velocidades típicas de corte son de varios metros por minuto, para calculas la potencia se utiliza: 
$$
\begin{gather}
P_{c} = F_{c}v \\
\text{ donde:} \\
P_{c } = \text{Potencia de corte} \\
F_{c} = \text{Fuerza de corte} \\
v = \text{Velocidad de corte}
\end{gather}
$$
Las unidades en el sistema de estados unidos:
$$
\begin{gather}
HP_{c} = \frac{F_{c}v}{33000} \\
HP_{c} = \text{potencia de corte en caballos de fuerza}
\end{gather}
$$
La potencia bruta requerida para poder realizar el corte es mas grande que la real, esto debido a las perdidas mecánicas en el motor. 
$$
P_{g} = \frac{P_{c}}{E} \rightarrow HP_{g} = \frac{HP_{c}}{E}
$$
Donde E es la eficiencia mecánica 

Es útil convertir la potencia en potencia por unidad de volumen de corte del metal, esta es la potencia unitaria: 

$$
P_{u} = \frac{P_{c}}{R_{MR}} \rightarrow HP_{u} = \frac{HP_{C}}{R_{RM}}

$$

La tasa de remoción de material se puede calcular como el producto de vt0w, la potencia unitaria también se conoce como la energía especifica U. 
$$
U = P_{u} = \frac{F_{C}V}{vt_{c}w}= \frac{F_{c}}{t_{0}w}
$$

