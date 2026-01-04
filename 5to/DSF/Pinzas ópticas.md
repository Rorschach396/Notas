}# Teoría general

En lo que normalmente se enfoca la el modelado de pinzas ópticas es en poder calcular las fuerzas en función de la posición, esto haciendo las consideraciones: 
- La partícula es esférica
- El torque presente en la partícula es 0 
- La orientación es irrelevante 
Esto da como resultado que las propiedades principales de las pinzas ópticas puedan ser encontradas a través de las siguientes 5 magnitudes: 

1) Fuerza de atrapamiento: Es la fuerza de restauración máxima más pequeña (o como lo pone en el texto "smallest maximum restoring force") que permite mantener la partícula dentro de las pinzas ópticas, esta está en contraste con la fuerza de dispersión (en resumen de esta, es la fuerza que tiende a sacar a la partícula de las pinzas ópticas). 
2) Fuerza radial de atrapamiento: Es el equivalente de la fuerza de atrapamiento pero para desplazamientos radiales desde la posición de equilibrio. 
3) Posición de equilibrio: Es la posición donde la fuerza óptica es cero, cabe remarcar que esta posición puede no existir en ciertos casos. 
4) Constante radial de resorte: Es que tanto va cambiando la fuerza de atrapamiento con un cambio en la posición radial, esta normalmente está determinada por la posición de equilibrio y se suele utilizar la ley de Hooke para calcularla ($F_{r} = -k_{r}r$) esta puede depender de las propiedades anisotrópicas del laser. 
5) Constante axial de resorte: Es el equivalente de la constante radial de resorte solo que aplicada a un desplazamiento axial; esta es la menos usada debido a que no se suele medir de forma experimental. 
Estas magnitudes normalmente se presentan como las eficiencias adimensionales de la fuerza (Q) y del torque ($\tau$) que pueden ser convertidas sin son multiplicadas por los siguientes términos: 

$$
\begin{gather}
\text{fuerza} \rightarrow \frac{nP}{c} \\
\text{Donde:} \\
P = \text{Potencia del laser} \\
n = \text{indice de refraccion del medio} \\
c = \text{velocidad de la luz} \\
\text{Torque} \rightarrow \frac{P}{\omega} \\
\text{Donde:} \\
\omega = \text{Furecuencia optica}
\end{gather}
$$


# Ray Optics 

Como tal, este es un método aproximado que (a pesar de ser aproximado) logra dar una aproximación bastante buena al fenómeno real; la eficiencia de este método está dada por el *parámetro de tamaño* de la partícula, este está definido de forma matemática de la siguiente forma: 
$$
\zeta = \frac{2\pi a n_{m}}{\lambda_{0}}
$$
donde: 
- a = es el tamaño de la partícula
- $\lambda_{0}$ = La longitud de onda del atrapamiento en el vacío 
- $n_m$ = Índice de refracción del medio donde se encuentra la partícula

En el caso de Ray Optics, este método es valido solo cuando $\zeta \gg 1$ y  su eficiencia es directamente proporcional al tamaño de la partícula; esto es de suma importancia a la hora de realizar modelados, esto debido a que la mayor parte de los modelos y teorías exactas para partículas no esféricas tienden a volverse imprácticas después de que se pasa un determinado umbral de tamaño (tamaño relativo entre la partícula y la longitud de onda). 

El análisis debemos de considerar que la partícula tiene un índice de refracción $n_{p}$ que se encuentra inmersa en un medio (homogéneo, no magnético y no dispersivo) con un índice de refracción $n_{m}<n_{p}$, esta estaría iluminada por un laser que, en el vacío, tiene una longitud de onda $\lambda_{0}$ y, por lo tanto, un número de onda igual a $k_{m} = \frac{2\pi n_{m}}{\lambda_{0}}$ en el medio que rodea a la partícula; para la teoría de ray optics, el campo óptico puede ser descrito como una colección de N haces de luz, cada uno de los cuales tiene un determinado $P_{i}$, que sería la energía de incidencia de cada haz de luz, dando como resultado que la energía total (cabe remarcar, en ingles lo colocan como "power" por lo que puede ser un error de traducción) se exprese de la siguiente forma: 
$$
P = \sum_{i} P_{i}
$$
y cada uno de los rayos tiene un momento dado por la formula $\frac{n_{m}P_{i}}{c}$. Para poder realizar el análisis se considera un modelo simplificado donde un solo rayo de luz que se llamará $r_{i}$ que golpea a una partícula esférica dieléctrica con un determinado ángulo de incidencia $\theta_{i}$, al momento en que $r_{i}$ choca con la partícula su energía se divide, dando como resultado un haz reflectado $r_{r,0}$ que tiene una pequeña cantidad de energía y un haz que contiene casi toda la energía, el cual es el haz transmitido $r_{t,0}$, este mismo rayo es capaz de atravesar la partícula hasta llegar al otro extremo de la misma, donde se vuelve a  separarse en dos rayos, uno transmitido ($r_{t,1}$) que contiene casi toda la energía y otro reflectado ($r_{r,1}$) que casi no contiene energía. En el caso del haz de luz $r_{r,1}$ este vuelve a separarse al momento que alcanza una de las paredes de la partícula; este proceso se repite hasta que la luz escapa totalmente de la partícula. En cada una de las dispersiones que se dan (proceso en el cual el haz de luz impacta con la partícula y se divide) el cambio de momento del rayo genera una reacción en el centro de masa de la partícula, los cuales al ser considerados, podemos calcular la fuerza óptica de la siguiente forma: 

$$
F_{ray} = \frac{n_{m}P_{i}}{c}\hat{r_{i}} - \frac{n_{m}P_{r}}{c}\hat{r_{r,0}} - \sum_{j=1}^{+\infty}\frac{n_{m}p_{t,j}}{c}\hat{r_{t,j}}
$$
Donde $\hat{r_{i}}$, $\hat{r_{r,0}}$ y $\hat{r_{t,j}}$ son los vectores unitarios que representan la dirección de incidencia de los haces de luz y los j-esimos haces deflactados, los cuales son calculados utilizando los coeficientes de reflexión y transmisión de Fresnel. En el caso de la fuerza $F_{ray}$ esta solo tiene fuerza en el plano de incidencia y puede ser descompuesto en dos componentes perpendiculares entre si, donde la componente que va en dirección de $\hat{r_{i}}$ representa la fuerza de dispersión ($F_{ray,s}$) que empuja la partícula en dirección del haz incidente. El componente perpendicular a esta fuerza es la fuerza de gradiente ($F_{ray,g}$); esta fuerza se encarga de jalar de forma perpendicular (respecto a la fuerza de dispersión) a la partícula. A partir de estas fuerzas se pueden obtener los índices de eficiencia de atrapamiento si se dividen por la taza de flujo de momento del haz incidente ($\frac{n_{i}P_{i}}{c}$): 
$$
\begin{gather} \\
% lil darkie - Humans and monsters
Q_{ray,s} = \frac{c}{n_{m}P_{i}}F_{ray,s} \\
Q_{ray,g} = \frac{c}{n_{m}P_{i}}F_{ray,g} \\
\text{Podemos obtener la eficiencia total de atrapamiento de la siguiente forma:} \\
Q_{ray} = \sqrt{ Q^2_{ray,s} + Q^2_{ray,g} }
\end{gather}
$$

La eficiencia de atrapamiento nos permite saber que tan bien se transmite el momento del haz de luz a la partícula, este puede tener un valor teórico máximo de 2, donde se reflejaría el haz de luz en forma normal a su dirección de incidencia. También se puede ver que el resultado de estos coeficientes es independiente al tamaño de la partícula. Estos coeficientes fueron derivados por un carnalito llamado Ashkin: 

$$
\begin{gather}
Q_{scat} = 1 + R \cos(2\theta_{i}) - T^2 \frac{\cos(2\theta_{i}-2\theta_{r})+R\cos(2\theta_{i})}{1 + R^2 + 2R\cos(2\theta_{r})} \\
Q_{grad} = R\sin(2\theta_{i}) - T^2 \frac{\sin(2\theta_{i}-2\theta_{r})+R\sin(2\theta_{i})}{1 + R^2 + 2R\cos(2\theta_{r})}
\end{gather}
$$
Donde R y T son coeficientes de reflexión y transmisión de Fresnel 
Modelo de sabana 
Mesh y surf 

# T matrix 

Al momento de utilizar el método de T matrix, los campos de incidencia, de dispersión e internos son expandidos en términos de vectores esféricos armónicos, la relación entre la expansión de estos términos (campo de dispersión y campo incidente) define la T matrix, esto genera que el problema de dispersión se simplifique a solo se tenga que calcular los coeficientes (esto se puede hacer a través de cualquier método). Este método tiene una muy buena eficiencia a la hora de trabajar con partículas muy simétricas (tanto en forma como en composición). 

Gracias a la linealidad de las ecuaciones de Maxwell y de las condiciones iniciales el proceso de dispersión se puede considerar en términos de un operador lineal $\mathbb T$ de tal forma que se cumpla la siguiente ecuación: 

$$
E_{s} = \mathbb T E_{i}
$$
Donde: 
- $E_{i}$ campo de incidencia 
- $E_{s}$ campo de dispersión
Si ahora suponemos que ambas E vistas anteriormente se pueden expandir en bases adecuadas (que no necesariamente deben de ser las mismas) se puede encontrar la matriz de transición (T matrix = $\mathbb T$) que esta relacionada con los coeficientes de la expansión, esta nos da toda la información acerca de la morfología y orientación de la partícula respecto al campo de incidencia. Como $E{i}$ esta dado en términos de múltiplos de Bessel J, podemos obtener la siguiente función: 

$$
E_{i}(r,\hat{r}) = E_{i} \sum_{l = 0}^{ \infty } \sum_{m = -l}^{l}W^{(1)}_{lm}J^{(1)}_{lm}(kr,\hat{r}) + W^{(2)}_{lm}J^{(2)}_{lm}(kr,\hat{r}) 
$$
Donde las W son las amplitudes y los números 1 y  2 se refieren a los componentes multipolares de carácter magnético o eléctrico. 

$$
Q_{NVT}^{id} = \frac{1}{N!} \frac{1}{h^{3N}}\int dp e^{-\chi/k_{b}T}
$$


# Teoría Mie 
$$
\begin{gather}
p = \mathbb Ta \\
\text{ Donde: } \\
p = \text{scattered waves} \\
a = \text{incident waves} \\
T = \text{T matrix}
\end{gather}

$$

# Formulas para el Brayan

Ecuación de Langevin: Describe el movimiento browniano, el movimiento browniano es el movimiento que sufre una partícula debido a las colisiones que sufre la misma con el líquido en el cual se encuentra suspendido. 

$$
m \frac{d^2x}{dt^2} = -\lambda \frac{ dx}{dt} + \eta(t)
$$

Donde: 
- x = posición de la partícula 
- m = masa de la partícula 
- $\eta$ = un término de ruido 
- $\lambda$ = coeficiente de amortiguamiento %% viscocidad%% del medio 

Ley de Hook: La ley de Hook nos permite conocer como es que existe una relación entre la longitud que es deformada un cierto objeto (debe de ser dentro de la zona elástica) y la fuerza requerida para poder realizar esta deformación. 
$$
F = -kx
$$
Donde: 
- F = fuerza 
- k = constante (en este caso del resorte)
- x = posición 

Teorema de equipartición: Afirma que en cualquier sistema en equilibrio térmico, la energía total del sistema se divide por igual entre todas sus diferentes formas o modos, esto implica que cada grado de libertad relacionado con la energía cinética del sistema contribuye en igual medida a la energía total. 
$$
E = \frac{1}{2}kT 
$$
Donde: 
- E = energía 
- T = temperatura
- k = constante de Boltzmann 

Distribución de Cauchy: Esta es una distribución de probabilidad continua famosa por tener colas cargadas, es decir, es probable que sucesos extremos sean probables (mínimo más que en la distribución normal).
$$
f(x;\theta,\sigma) = \frac{1}{\pi \sigma \left[1+\left( \frac{x-\theta}{\sigma} \right)^2 \right]} \quad \text{para }x \in \mathbb{R}
$$
Donde: 
- $\theta$ = Parámetro de localización donde se determina el pico o el centro de la distribución del eje x. 
- $\sigma$ = Parámetro de escala, con este se determina el grado de dispersión de la distribución.
Distribución normal: Es un concepto estadístico que describe cómo se distribuyen los datos alrededor de un valor promedio, donde el valor central es el valor más probable de poder conseguir, mientras que los valores extremos son más complicados de conseguir. 
$$
f(x) = \frac{1}{\sigma \sqrt{2\pi }}e^{-1/2\left( \frac{x-\mu}{\sigma}\right)^2}
$$
Donde: 
- f(x) = función de densidad de probabilidad 
- $\sigma$ = desviación típica 
- $\mu$ = media

Teoría MIE: Solución analítica exacta de las ecuaciones de Maxwell para la dispersión (o como lo ponen en los papers "scattering") y la absorción de una onda electromagnética plana por una esfera homogénea e isotrópica de cualquier tamaño que se encuentra sumergida en un medio homogéneo e infinito. 

$$
\begin{gather}
\left[
\begin{matrix}
E_{\parallel s} \\
E_{\perp s}
\end{matrix}
\right] =  
\frac{e^{ik(r-z)}}{-ikr}   
\left[ 
 \begin{matrix}
S_{2} & 0 \\
0 & S_{1}
\end{matrix}
\right]  
\left[
\begin{matrix}
E_{\parallel i} \\
E_{\perp i}
\end{matrix}
\right] \\
S_{1} = \sum^{\infty}_{n=1}\frac{2n+1}{n(n+1)}(a_{n}\pi_{n}+b_{n}\tau_{n}) \\
S_{2} = \sum^\infty_{n=1}\frac{2n+1}{n(n+1)}(a_{n}\tau_{n}+b_{n}\pi_{n}) \\
a_{n} = \frac{m\psi_{n}(mx)\psi'_{n}(x)-\psi_{n}(x)\psi'_{n}(mx)}{m\psi_{n}(mx)\xi'_{n}(x)-\xi_{n}(x)\psi'_{n}(mx)} \\
b_{n} = \frac{\psi_{n}(mx)\psi'_{n}(x)-m\psi_{n}(x)\psi'_{n}(mx)}{\psi_{n}(mx)\xi'_{n}(x)-m\xi_{n}(x)\psi'_{n}(mx)} \\
\pi_{n} = \left(\frac{2n-1}{n-1} \cos(\theta)\right)\pi_{n-1} - \frac{n}{n-1}\pi_{n-2} \\
\tau = (n\cos(\theta))\pi_{n} - (n+1)\pi_{n-1}
\end{gather}
$$

Donde: 
- $S_{j},j=1,2,\dots$ = Elementos de la matriz de dispersión de amplitud
- $\theta$ = ángulo polar de dispersión 
- $\phi$ = ángulo azimutal de dispersión 
- $E_{i}$ = onda incidente 
- $E_{s}$ = onda dispersada 
- $a_{n}$ y $b_{n}$ = coeficientes de MIE
- $\psi_{n}$ y $\xi_{n}$ = funciones de Riccati-Bessel 
- $\pi_{n}$ y $\tau_{n}$ = unciones dependientes del ángulo obtenidas por relaciones de recursión 
PSD: Es una función que nos permite conocer como se distribuye la potencia promedio de una determinada señal que varía en el tiempo en las diferentes frecuencias que la componen. 
$$
S(f) = \lim_{ T \to \infty } \frac{1}{T}[X(f)]^2
$$
Donde: 
- S(f) = PSD
- f = frecuencia de la señal 
- T = duración temporal de la observación 
- X(f) = transformada de Fourier de la señal 

PSF: Es la respuesta de un sistema de formación de imágenes a una fuente de luz puntual, esta describe como es que un sistema óptico puede "dispersar" un punto ideal de luz degradando la imagen final. 

$$
PSF(r) = \frac{2J_{1}(\pi rr_{0})^2}{\pi rr_{0}} \quad r_{0} = \frac{\lambda D}{2}
$$
Donde 
- $J_{1}$ = función de Bessel de primer orden 
- $r_{0}$ =factor de escalamiento 
- D = diámetro de apertura 
- $\lambda$ = longitud de onda de la luz