
# Capitulo 1 

- Problema de radiación de cuerpo negro: 
Problema que era inexplicable a través de la física que se tenía en ese momento, este problema surge por la radiación emitida por un cuerpo caliente, la cual al empezar a calentar el objeto, este cambia de emitir una radiación de baja frecuencia a emitir una radiación de alta frecuencia. En el caso de un cuerpo que absorbe y emite todo el rango de radiaciones, este es llamado *cuerpo negro* y subsecuentemente la radiación que emite este cuerpo negro es conocida como *radiación de cuerpo negro*. 

Debido a que la física de ese momento no podía explicar este fenómeno (esto debido a que si se intentaba realizar el calculo respectivo para bajas frecuencias, la formula que se tenía en aquel momento funcionaba, pero si se intentaba realizar con altas frecuencias la formula divergía como $v^2$, esto era posible verlo en el espectro ultravioleta, debido a que justo en ese punto la frecuencia empezaba a aumentar, a este fenómeno se le conoció como "la catástrofe ultravioleta") y no debido a una mala implementación de las formulas, si no debido a que no se tenían ciertas consideraciones y formulas que después serían consideradas. 

La resolución de este problema llegó con Planck quien se dio cuenta que, para poder resolver este problema, se tenía que considerar que la energía no tiene valores discretos que deben de ser proporcionales a la frecuencia, esto visto de forma matemática se puede ver con la siguiente formula: 

$$
E = nhv
$$
La cual presenta que la energía (E) es igual a un numero entero (n) multiplicado por una constante de proporcionalidad (h) y esto a su vez multiplicado por la frecuencia (v), a raíz de este planteamiento Planck logró llegar a la siguiente expresión para poder resolver el problema de la radiación de cuerpo negro: 

$$
dp (v,T) = p_v(T)dv = \frac{8\pi h }{c^3} \frac{v^3 dv}{e^{\frac{hv}{k_vT}}-1}
$$

En el caso de la constante de Planck (h) se obtuvo que su valor debía de ser 6.626 x $10^{-34}$ joules x segundo, esta ecuación no diverge a altos valores de frecuencia, por lo que se tomo como la ley de distribución para radiación de cuerpo negro. 

A pesar de que se logró explicar el fenómeno de la radiación de cuerpo negro, los científicos de la época creían que era algo muy arbitrario y que hasta cierto punto no explicaba de forma correcta el fenómeno; esto fue antes de que Einstein pudiera explicar el efecto fotoeléctrico haciendo uso de la misma suposición que utilizó Planck. 

- Efecto fotoeléctrico: 
En el caso del efecto fotoeléctrico es un fenómeno que se vio que sucedía cuando se le radiaba luz ultravioleta a un metal, este empezaba a emitir electrones de su superficie. Normalmente se pensaría (con la física que se tenía en aquel momento) que entre mayor fuera la frecuencia de la luz que se le suministra a la placa de metal, mayor sería la energía que tienen los electrones; pero esto resulto ser completamente contrario a lo que se vio de forma experimental, debido a que se encontró que era completamente independiente a la frecuencia que tenía la luz. 

En el caso de este experimento, se vio que para poder resolver se tenía que expandir el alcance de la hipótesis de Planck, donde gracias a que Einstein propuso que $\Delta E=hv$ siguiendo con la idea de Planck, se logro obtener que la radiación (en este caso la luz que se le estaba suministrando al metal) era discreta y estaba en pequeños paquetes de energía, los cuales se denominaron *fotones* estos a su vez fueron utilizados en un despeje de conservación de energías para poder obtener la siguiente formula: 
$$
KE = \frac{1}{2} m v^2 = hv - \phi
$$
Donde $\phi$ es llamada "función de trabajo" del metal y, en el caso de la ecuación, el lado izquierdo de la misma no puede ser negativo, por lo que hv >= $\phi$, por lo que se puede decir que la energía mínima requerida para poder expulsar un electrón es solo la energía necesaria para poder sobrepasar la función de trabajo del metal. 

- El átomo de hidrogeno: 
En el caso del átomo de hidrogeno, este ha estado presente en un gran numero de cálculos relacionados con la ecuación de onda; en este caso al momento de realizar un espectro de emisión del hidrógeno se puede ver que tiene un espectro compuesto de vaias líneas, las cuales pueden ser explicadas por la formula siguiente: 

$$
v = 8.2202 \text{x} 10^{14} (1 - \frac{4}{n^2})Hz
$$
Esta formula se caracteriza por la presencia de n, que como en los casos anteriores es un numero entero, esto predice que entre mayor es el numero n, más se van amontonando las frecuencias de emisión. 

En el caso de la luz, se tiene un gran dilema relacionado con la naturaleza de la luz, esto debido a que en ciertos casos la luz se comporta como una partícula mientras que en otros muchos casos parece ser solo un flujo de electrones; esto generó el termino "dualidad onda-partícula de la luz"; esto se puede ver con la siguiente ecuación donde se establece que la longitud de onda y el momento del foton estan relacionados por:
$$
\lambda = \frac{h}{p}
$$
Esto implica que la materia en si, tiene un comportamiento de partícula, esto debido a que el momento p es igual a la velocidad multiplicada por la masa, por lo que se predice que si un cuerpo de masa m se mueve a una velocidad v, este tengra una longitud de onda de Broglie representada por la siguiente ecuación: 
$$
\lambda = \frac{h}{mv}
$$
Es importante mencionar que si se considera el modelo atómico de bohr, se puede obtener la siguiente formula: 
$$
m_e v r = \frac{nh}{2\pi} \quad\text{que puede ser transfromada en}\quad m_e v r = n \hbar
$$
Atraves de esta formula podemos encontrar que los niveles de energia se encuentran cuantizados, esto dando como resultado que los niveles de energia se encuentran respresentados por la siguiente ecuacion: 

$$
E_n = -\frac{m_e e^4}{8 \epsilon_0^2 h^2} \frac{1}{n^2} \quad n = 1,2,3 \dots
$$
- Principio de incertidumbre de Heisenberg:
Debido a que el electron es una particula que tiene un momento denotado por p ($p=\frac{h}{\lambda}$) al momento en el que intentamos ubicar un electron en una determinada orbita se altera su trayectoria por el hecho de intentar ubicarlo (esto debido a que se esta utilizando una onda de luz o un foton, en cualquiera de los casos, su interaccion altera la trayectoria del electron) esto fue ejemplificado con la formula: 

$$
\Delta x \Delta p \geq h 
$$
Esto lo que quiere decir es que si intentamos encontrar el electron en un punto muy exacto se tendra un cierto desconocimiento y viceversa. 

# Capitulo 2 

## Ecuacion de onda clasica 

En el caso de la escuacion de onda clasica, esta esta descrita por la siguiente ecuacion diferencial parcial de segundo orden: 

$$
\frac{\partial^2 u(x,t)}{\partial x^2 } = \frac{1}{v^2} \frac{\partial^2 u(x,t)}{\partial t^2}
$$
La cual permite predecir el desplazamiento que va a tener una cuerda que se encuentra tensionada en sus extremos, en este caso las condiciones iniciales estan dadas por las siguientes ecuaciones, estas son necesarias para poder resolver de forma satisfactoria la ecuacion diferencial: 
$$ 
u(0,t) = 0 \quad \text{y} \quad u(l,t)
$$
Para poder resolver esta ecuacion se tiene que realizar separacion de variables, esto es importante y ya se llevo en otra materia, por lo que se obiara y se continuara al siguiente tema del capitulo, cualquier cosa que se necesite se puede regvisar el apendice de apuntes necesarios (que si me acuerdo pondre) para obtener las notas.  En este caso podemos encontrar que la solucion a esta ecuacion diferencial es igual a:
$$
u(x,t) = \sum_{n=1}^{\infty} A_n \cos (\omega_nt + \phi_n)\sin(\frac{n\pi x}{l}) = \sum_{n=1}^{\infty}u_n(x,t)
$$
Podemos encontrar que 
$$
v_n = \frac{\omega_n}{2\pi} = \frac{vn}{2l}
$$
De estas ecuaciones se puede obtener que el modo de vibracion de esta cuerda se encuentra compuesta de *modos normales* los cuales representan un movimiento armonico de la frecuencia; esto debido a que utilizamos $\omega_n=\beta v = \frac{n \pi v}{l}$. 

En el caso de las ecuaciones diferenciales, son posibles de aplicar en diferentes planos y dimensiones, por lo que se puede analizar de forma especifica el caso de una membrana que vibra haciendo uso de una ecuacion diferencial como la que descrivimos en la parte superior, solo que considerando que es bidimensional: 

$$
\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2u}{\partial y^2} = \frac{1}{v^2}\frac{\partial^2u}{\partial t^2}
$$
Esta EDP tendra unas condiciones iniciales como estas: 
$$
\begin{gather}
u(0,y) = u(a,y)=0 \\
u(x,0) = u(x,b) = 0
\end{gather}
$$
En el caso de esta EDP podremos encontra que la solucion que tiene este problema esta dada por la siguiente ecuacion: 

$$
u(x,y,t) = \sum_{n=1}^{\infty}\sum_{m=1}^{\infty}A_{nm}\cos(\omega_{nm}t + \phi_{nm})\sin\left(\frac{n\pi x}{a}\right)\sin\left(\frac{m\pi y}{b}\right)
$$
Podemos encontrar que: 
$$
\omega_{nm} = \frac{v\pi}{a}(n^2 + m^2)^{\frac{1}{2}}
$$
En este caso podemos encontrar que el resultado de $u_{12}(x,y,t) = u_{21}(x,y,t)$ esto es un caso de *degeneracion* que, en pocas palabras, es cuando en una ecuacion (en este caso la ecuacion de posicion de una cuerda que se encuentra tensionada, pero que mas adelante veremos que puede ser tambien energia) se obtiene que dos posibles valores tienen el mismo valor.  

# Capitulo 3

## Ecuación de Schrödinger

Con lo visto anteriormente acerca del comportamiento onda-partícula que tiene la materia, podemos encontrar que podemos describir la ecuación que describe sus propiedades como lo siguiente: 
$$
u(x,t) = \psi (x)\cos(\omega t)
$$
Esto nos permite encontrar lo siguiente: 

$$
\frac{d^2 \psi}{dx^2} + \frac{\omega^2}{v^2}\psi(x)= 0
$$
Aqui se puede utilizar la sustiucion de $\omega = 2\pi v$ y tambien $v\lambda = v$, cosa que se hara con el siguiente paso, el cual es considerar la energia total de una molecula, la cual es la suma de la energia cinetica y potencial de la particula, lo que es representado con la siguiente ecuacion: 

$$
E = \frac{p^2}{2m} + V(x)
$$
En este caso dejamos la energia potencial como V(x) y despejamos el momento para poder sustituirlo en las siguientes como se muestra en lo siguiente: 

$$
\begin{gather}
\lambda = \frac{h}{p} = \frac{h}{2m[E- V(x)]^{1/2}}\\
\text{Sustituyendo en la ecuacion de onda encontramos que:}\\
\frac{d^2 \psi}{dx^2} + \frac{2m}{\hbar^2}[E-V(x)]\psi(x)= 0\\
\text{Esta expresion se puede reformular de la siguiente forma}\\
-\frac{\hbar^2}{2m}\frac{d^2\psi}{dx^2} + V(x)\psi(x) = E\psi(x)
\end{gather}
$$
La penultima expresion obtenida es la ecuacion de schrodinger independiente del tiempo en una sola dimension y sus soluciones son llamadas *funciones de onda de estado estacionario*. 

En el caso de ciertas cantidades que son de interes para la fisica, estas se pueden representar como un operador lineal en mecanica cuantica; estos operadores se consideran lineales si cumplen la siguiente propiedad 

$$
\hat{A}[c_1f_1(x) + c_2f_2(x)] = c_1\hat{A}f_1(x) + c_2\hat{A}f_2(x)
$$

^01e1f9

En el caso de la mecanica cuantica, casi todos los problemas que se pueden resolver son problemas con *eigen funciones* las cuales son funciones las cuales al aplicarle un determinado operador dan la misma funcion multiplicada por un numero que se llamara *eigen valor* : 
$$
\hat{A}\phi (x) = a\phi (x)
$$

^9cc90d

Si retomamos la ecuacion de schrodinger independiente del tiempo podemos realizar la siguiente reestructuracion de la ecuacion para poder obtener un prblema de eigen valores: 

$$
\begin{gather} 
\left[-\frac{\hbar^2}{2m}\frac{d^2}{dx^2} + V(x)\right]\psi(x)=E\psi(x)\\
\text{Podemos denotar esta ecuacion de la siguiente forma:}\\
\hat{H} \psi(x) = E\psi(x)\\
\text{donde:}\\
\hat{H} = -\frac{\hbar^2}{2m}\frac{d^2}{dx^2}+V(x)
\end{gather}
$$
En este caso $\hat{H}$ es llamado *Operador Hamiltoniano* y esto genera que la energfuncion de onda sea una eigen funcion y la energia sea un eigen valor del operador hamiltoniano. Si consideramos que la energia potencial en el ejemplo anterior es 0, podemos decir que toda la energia es cinetica, por lo que podemos encontrar los siguientes operadores de la ecuacion anterior: 

$$
\begin{gather}
\hat{K}_x = -\frac{\hbar^2}{2m}\frac{d^2}{dx^2}\quad \text{energia cinetica}\\
\hat{P}^2_x = -\hbar^2 \frac{d^2}{dx^2}\quad \text{momento cuadrado}
\end{gather}
$$
Podemos encontrar que si analizamos el problema de una particula encerrada en una caja unidimensional, podemos encontrar la probabilidad de que se encuentre en un cierto punto haciendo uso de la funcion de scrhordinger multiplicada por su conjugado, esto se puede representar con lo siguiente: 

$$
\begin{gather}
\text{Si consideramos la siguiente ecuacion: }\\
\frac{d^2 \psi}{dx^2} + \frac{2mE}{\hbar}\psi(x) = 0 \quad 0\le x \le a\\
\text{Podemos encontrar que: }\\
\psi (x)^*\psi(x) = \text{probabilidad de encontrar la particula entre x y x+dx}
\end{gather}
$$

Si se realiza la solución de la ecuación anterior podemos encontrar que la energia se encuentra cuantizada por un numero entero, esto nos sirve para poder utilizar las siguientes ecuaciones: 

$$
\begin{gather}
\Delta E = \frac{h^2}{8m_ea^2}(\Delta n^2) \\
E_n = \frac{h^2n^2}{8m_ea^2} \quad n = 1,2,3,\dots \\
\tilde{v} = \frac{\Delta E}{hc} 
\end{gather}
$$

En el caso de la ecuacion de onda, esta debe de ser normalizada por beneficios fisicos, esto debido a que si se evalua en todo el espacio, la probabilidad debe ser 1, esto matematicamente hablando es lo siguiente: 

$$
\int_{0}^{a}\psi_n(x)^* \psi_n(x)dx = 1
$$
En el caso del momento se puede demostrar que el promedio del mismo es 0 y que: 

$$
\sigma_p \sigma_x > \frac{\hbar}{2}
$$
Donde: 
- $\sigma_p=\frac{n\pi \hbar}{a}$
y podemos encontrar que: 
$$
\sigma_x\sigma_p=\frac{\hbar}{2}(\frac{\pi^2n^2}{3}-2)^{\frac{1}{2}}
$$
lo que comprueba que $\sigma_x\sigma_p>\frac{\hbar}{2}$ 

Se puede realizar el mismo calculo en 3 dimensiones, donde las ecuaciones a considerar son algo diferentes y esto se puede  ver en lo siguiente: 

$$
\begin{gather}
-\frac{\hbar^2}{2m}\left(\frac{\partial^2 \psi}{\partial x^2}\frac{\partial^2 \psi}{\partial y^2}\frac{\partial^2 \psi}{\partial z^2}\right) = E\psi(x,y,z)\\
-\frac{\hbar^2}{2m}\nabla^2\psi=E\psi\\
\hat{H} =\hat{H_x} +\hat{H_y}+\hat{H_z}
\end{gather}
$$
# Capitulo 4

En este capitulo se tratan los postulados de la mecánica cuántica todos basados en las propiedades que deben de tener tanto los operadores como la función de onda. Al inicio del capitulo se aclara que todas las variables dinámicas como posición, momento, momento angular y energía son las variables que normalmente se tienen que considerar en mecánica clásica, en el caso de mecánica cuántica se puede obtener el siguiente postulado: 

> Postulado 1: El estado de un sistema cuantico-mecanico esta completamente especificado por la función $\psi(x)$ que depende de las coordenadas de la partícula. Toda la posible información del sistema puede ser obtenida a través de $\psi(x)$. Esta función es la función de onda y tiene la propiedad de que $\psi(x)^*\psi(x)dx$ es la probabilidad de encontrar la partícula en el intervalo dx en la posición x.

Esta propiedad puede ser trasladada a diferentes dimensiones, solo por simplicidad en este caso se esta utilizando la ecuación de onda en una sola dimensión; como ya se vio anteriormente, como el producto del conjugado de la función y la función tienen un sentido probabilista se tiene que cumplir la siguiente propiedad para que esta propiedad tenga sentido: 

$$
\int_{\text{T.E.}}\psi(x)^*\psi(x)dx = 1 \quad \text{T.E.}= \text{Todo el Espacio}
$$
Todo el espacio quiere decir que esta propiedad se debe de cumplir para todos los posibles valores de x, a esta propiedad se le conoce como normalización. 

> Postulado 2: Para cada obserbable (es decir, cualquier variable que pueda ser medida) en la mecanica clasica corresponde un operador lineal en mecanica cuantica.

Esta propiedad nos permite conocer que dependiendo de lo que se quiera estudiar de un sistema se tendra que aplicar un cierto operador, esto se puede ver en la tabla presente en la pagina 143 del libro que nos dieron al inicio de este curso (si me acuerdo lo pongo en el apendice del documento). Cada uno de estos operadores deben de cumplir la propiedad de ser lineal que se vio en el [[Guía PEM#^01e1f9]] donde se muestra matemáticamente como se ve la propiedad de linealidad en los operadores. 

> Postulado 3: En cualquier medición de una variable observable asociada con un operador $\hat{A}$ los únicos valores que van a ser observados son los eigenvalores $a_n$ que satisfacen la ecuación vista en [[Guía PEM#^9cc90d]]*

El postulado anterior se puede ver de forma mas clara en el caso de la ecuacion de onda clasica, donde tenemos lo siguiente: 

$$
\hat{H}\psi_n=\hat{E}_n\psi_n
$$
> Postulado 4: Si un sistema esta en un estado descrito por una funcion de onda normalizada $\psi$, entonces el valor observable promedio correspondiente a $\hat{A}$ esta dado por: 
> $$
 \langle a\rangle = \int_{\text{T.E.}}\psi^*\hat{A}\psi dx $$


Esto se pudo ver anteriormente donde se menciona que el valor promedio del momento p de una partícula es 0, esto denotado por la siguiente expresión matemática: $\langle p \rangle = 0$. 

> Postulado 5: La funcione onda, o función de estado, de un sistema evolucione respecto al tiempo siguiendo la ecuación de schrodinger dependiente del tiempo: 
> $$
\hat{H}\Psi(x,t) = i\hbar \frac{\partial \Psi(x,t)}{\partial t}$$


En este caso, este es el único teorema que no habíamos utilizado en el capitulo 3, pero a pesar de esto se pueden utilizar ciertas propiedades como la separación de variables necesaria para poder resolver esta ecuación diferencial; en este caso, si el operador hamiltoniano no contiene explícitamente el tiempo, este solo depende de las coordenadas de la partícula a analizar. 

Al analizar una eigenfuncion para el caso de mecánica cuántica, esta debe de cumplir con la siguiente característica: 

$$
\int_{-\infty}^{\infty} \psi_m^*(x)\psi_n(x)dx = 0 \quad m\neq n 
$$


Cuando la funcion es tanto normalizada como ortogonal (propiedad vista anteriormente) se le conoce como *ortonormal* y esto se puede representar con la delta de Kroenecker y se encuentra representada por: 

$$
\delta_{ij} = 
\begin{cases}
n = m \rightarrow 1\\
n\neq m \rightarrow 0
\end{cases}
$$
> Postulado 2': Para cada  variable observable en mecanica clasica corresponde un operador Hermitiano lineal en mecanica cuantica. 

Un operador Hermitiano es un operador que puede satisfacer la siguiente condicion: 

$$
\int_{T.E.} f^* (x) \hat{A}g(x)dx = \int_{T.E.} g(x)[\hat{A}f]^*(x)dx
$$
Para poder comprender ciertos puntos del libro es necesario ver que significa que un operador pueda ser conmutativo, esto matematicamente se puede representar de la siguiente forma: 

$$
\hat{A}\hat{B}f(x) = \hat{A}[\hat{B}f(x)]
$$
En este caso los dos operadores presentes ($\hat{A} \text{ y } \hat{B}$) son operadores conmutables, que normalmente se pueden representar de la siguiente forma (tambien se incluye como es la propiedad cuando no son iguales): 

$$
\begin{gather}
\hat{K}_x\hat{P}_x - \hat{P}_x\hat{K}_x = \hat{O}\\
[\hat{K}_x,\hat{P}_x]= \hat{O}\\
\hat{A}\hat{B}f(x)\neq \hat{B}\hat{A}f(x) \rightarrow \text{no conmutativos}
\end{gather}
$$
Debido a este fenomeno, es que no se puede concer de forma precisa el momento y la posicion de una particula, esto debido a que se tiene la siguiente propiedad para la posicion ($\hat{X}$) y el momento ($\hat{P}_x$): 

$$
[\hat{P}_x , \hat{X}] = -i\hbar \hat{I}
$$
# Capitulo 5

En el caso de este capitulo se considera un oscilador armonico, el cual tiene la siguiente ecuacion diferencial: 

$$
m\frac{d^2x}{dt^2} + kx = 0
$$
Esta ED permite que encontremos como se va a comportar el oscilador armonico que se encuentra representado por una masa unida a un resorte. 

Si deseamos pasar este modelo a un sistema similar a una molecula podemos considerar que la molecula seran dos esferas unidas con un resorte, dando como resultado un oscilador armonico que consiste en una masa reducida y en la aplicacion de la ecuacion diferencial anterior de la siguiente forma: 

$$
\begin{gather}
\text{Considerando las siguientes ecuaciones:}\\
m_1 \frac{d^2x_1}{dt^2} = k(x_2 -x_1-l_0)\\
m_2 \frac{d^2x_2}{dt^2} = -k(x_2 -x_1-l_0)\\
\text{Podemos encontrar la siguiente EDO}\\
\mu \frac{d^2}{dt^2} + kx = 0 \\ 
\text{Donde:}\\
\frac{1}{\mu} = \frac{m_1 + m_2}{m_1m_2} 
\end{gather}
$$
En este caso $\mu$ es la masa reducida del sistema, la cual permite estudiar el sistema por completo solo teniendo en consideración una masa. 

La ecuacion de schrodinger aplicada en una sola dimension para el oscilador armonico es la siguiente: 

$$
\frac{d^2\psi}{dx^2}+\frac{2\mu}{\hbar^2}(E-\frac{1}{2}kx^2)\psi(x) =0 
$$
Esta ecuacion diferencial nos permite encontrar que la energia en un cierto punto estara dada por la siguiente ecuacion: 

$$
\begin{gather}
E_n = \hbar (\frac{k}{\mu})^{1/2} (n +\frac{1}{2})\\
E_n = \hbar \omega (n +\frac{1}{2}) = hv (n +\frac{1}{2})\\
n = 1,2,3 \dots\\
\omega = (\frac{k}{\mu})^{1/2}\\
v = \frac{1}{2\pi}(\frac{k}{k})^{1/2}
\end{gather}
$$
En este caso, esta ecuacion nor permite obtener el comportamiento de una molecula diatomica. 

En el caso de la ecuacion asociada a la solucion de la ecuacion de schrodinger asociada al oscilador armonico presente en este capitulo, podemos encontrar que esta esta compuesta por *Polinomios Hermitianos* los cuales podemos encontrar gracias a las siguientes ecuaciones: 

$$
\begin{gather}
\psi_n(x) = N_n H_n(\alpha^{1/2}x)e^{\frac{-\alpha x^2}{2}}\\
\text{Donde:}\\
\alpha = (\frac{k\mu}{\hbar^2})^{1/2}\\
N_n = \frac{1}{(2^nn!)^{1/2}}(\frac{\alpha}{\pi})^{1/4}
\end{gather}
$$
Esta solucion nos da los polinomios hermitianos que se encuentran en la pagina 194 del libro (o en el apendice si me acuerdo de ponerlo). Los polinomios hermitianos podemos encontrar que son funciones que pueden ser o pares o impares dependiendo de donde surjan. 

Si ahora tomamos el ejemplo de un rotor rigido, podemos encontrar que este solo cuenta con energia cinetica, haciendo asi que se tengan que realizar ciertas consideraciones a la hora de realizar su analisis, pero podemos encontrar lo siguiente: 

$$
\begin{gather}
I = m_1r_1^2 + m_2r_2^2 = \mu r^2\\
L = I \omega \\
K = \frac{L^2}{2I}\\
\hat{H} = \hat{K} = -\frac{\hbar^2}{2\mu}\nabla^2 \\

\text{Esto con la ecuacion de onda(en coordenadas polares) siguiente:}\\

\sin(\theta)\frac{\partial}{\partial \theta}\left(\sin(\theta)\frac{\partial Y}{\partial \theta}\right) + \frac{\partial^2 Y}{\partial \phi^2} + (\beta \sin^2(\theta))Y=0\\
\text{Donde:}\\
\beta = j(j+1) \quad j = 0,1,2 \dots\\
\text{Con la energia siguiente:}\\
E_j = \frac{\hbar^2}{2I}j(j+1)
\end{gather}
%A.R.B.V%
$$
# Capitulo 6 

En el caso del átomo de hidrogeno podemos encontrar que podemos utilizar la ecuación del rotor rígido para poder encontrar un cierto valor, en este caso podemos encontrar que el operador Hamiltoniano es el siguiente: 

$$
\hat{H} = -\frac{\hbar^2}{2m_e}\nabla^2 - \frac{e^2}{4\pi\epsilon_0r}
$$
En este caso se esta utilizando el operador $\nabla^2$ el cual tendremos que representar en coordenadas esféricas debido a que son las mas útiles para el desarrollo de esta ecuación diferencial. El operador es expresado de la siguiente manera si lo aplicamos a la ecuación de schrodinger: 

$$
-\frac{\hbar^2}{2m_e}\left[\frac{1}{r^2}\frac{\partial}{\partial r }(r^2\frac{\partial \psi}{\partial r})+\frac{1}{r^2\sin(\theta)}\frac{\partial}{\partial\theta}(\sin(\theta)\frac{\partial\psi}{\partial \theta})+\frac{1}{r^2\sin^2(\theta)}\frac{\partial^2\psi}{\partial\phi^2}\right]-\frac{e^2}{4\pi\epsilon_0r}\psi(r,\theta,\psi)=E\psi(r,\theta,\psi)
$$

Con un par de trucos algebraicos podemos llevar a que la expresión que se encuentra en la parte superior se convierta en la siguiente ecuación: 

$$
\frac{1}{\Phi(\phi)}\frac{d^2\Phi}{d\phi^2}= -m^2
$$
Obteniendo así que la solución esta dada por las siguientes posibilidades: 

$$
\Phi_m(\phi)= A_me^{im\phi} \rightarrow m=0,\pm 1, \pm2 \dots
$$
Si se realiza el cambio de variable donde $x = \cos(\theta)$ podemos encontrar la siguiente ecuación diferencial que tiene los posibles resultados (es posible que me saltara algunos pasos claves, por lo que la pagina del libro en la que esta es la 219): 
$$
\begin{gather}
(1-x^2)\frac{d^2P}{dx^2}-2x\frac{dP}{dx}+\left[l(l+1)-\frac{m^2}{1-x^2}\right]P(x)=0\\
l = 0,1,2\dots \\
m=0,\pm1,\pm2\dots
\end{gather}
$$
Las soluciones que se obtienen a partir de esta ecuación son conocidas como polinomios de Legendre, debido a que existen ciertas complicaciones a la hora de medir L en todas sus componentes se tienen que realizar ciertas consideraciones a la hora de realizar cálculos relacionados con las mismas. 

Debido a que en este caso si se tienen degeneraciones debido a loas valores de l, m y n, se pueden obtener los orbitales dependiendo de los números cuantos l, m y n; esto solo es aplicable a los átomos similares al hidrogeno, aunque se puede realizar una generalización a átomos similares solo considerando su numero atómico, aunque (como se ha visto en casi todo el documento) esto siguió siendo una aproximación, esto se puede ver con el hecho de que no se puede resolver la ecuación relacionada con el átomo de helio. 


