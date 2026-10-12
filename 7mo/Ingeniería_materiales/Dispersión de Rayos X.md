- Normalmente se utiliza cobre (K$\alpha$)
- También hay otras lamparas de molibdeno 

$$
E = \frac{hc}{\lambda}
$$
- La longitud de onda del cobre K$\alpha$ se puede descomponer en 2 tipos diferentes de onda 
	- k$\alpha_{1}$
	- k$\alpha_{2}$
- Difracción: Fenómeno de dispersión e interferencia de una radiación al interactuar con un arreglo ordenado de centros dispersores, cuyo espaciamiento es el mismo orden de magnitud de la longitud de onda incidente. 
- Para que se pueda dar se necesita: 
	- Cristales periódicos 
	- Longitud de rayos X debe ser del mismo orden de magnitud qque la distancia de separación entre átomo y átomo de la red cristalina 
	- Difracción de rayos X debe presentar una dispersión coherente. 
- Existe la interferencia destructiva 
	- Las ondas dispersadas llegan fuera de fase
	- Sus amplitudes se cancelan parcialmente o totalmente 
	- No se observa un máximo de difracción. 
- Interferencia constructiva: 
	- Las sondas dispersadas llegan en fase 
	- Sus amplitudes se suman y se refuerzan, no producen un máximo de difracción 
- Fuck, ya se de donde el doc saco el apunte 
- Todas las operaciones se van a terminar haciendo en radianes, entonces se tiene que convertir a esa madre 

# Interpretación de un difractograma

- Posición del pico 2$\theta$
	- Relacionada con la distancia interplanar hkl 
	- Menor 2$\theta$ es mayor d 
	- Mayor 2$\theta$ es menor d 
- Intensidad del pico 
	- Depende de la estructura cristalina y la distribución de los átomos 
	- Puede verse afectada por la orientación preferencial 
	- Un poco más intento no siempre es mayor calidad del material 
- Anchura del pico (FWHM)
 
	- Picos anchos: Cristales pequeños, micro deformación o defectos 
- Índices de miller (hkl)
	- Cada pico se asocia con una familia de planos cristalográficos 
	- Permite identificar la fase cristalina y su estructura 
	- Se asignan comparando con patrones de referencia.
- La indexación consiste en asignar a cada pico de difracción los indices de miller (hkl) correspondientes de planos cristalográficos que producen esa reflexión 
1) Medir la posición 
2) Calcular la distancia 
3) Relacionar D con la estructura cristalina 
4) Asignar los índices 
- Los patrones de difracción cuentan como una patente. 
- Mayor calidad es mejor 

$$
a = \frac{\lambda(h{^2}+k{^2}+l{^2})^{\frac{{1}}{2}}}{2\sin \theta}
$$
- Picos muy estrechos quiere decir un tamaño de cristal muy grande 

# Factores que afectan la intensiidad de los picos 

- Factores estructurales 
	- Factor de estructura 
	- Factor de dispersión 
	- Multiplicidad del plano 
	- Simetría cristalina 
- Factores de la muestra 
	- Orientación preferencial 
	- Fracción de fase 
	- grado de cristalinidad 
	- Absorción de rayos X 
	- Composición química 
	- Defectos y desorden estructural 
- Factores instrumentales
	- intensidad 
	- Longitud de onda 
	- tiempo de conteo 
	- tipo y eficiencia del detector
	- Alineación del equipo 
- Normalmente se tiene que extraer el error del equipo, esto se hace con un patrón de referencia 
- El error del equipo se mide dando un barrido muy lento a una muestra altamente cristalina 

$$
FWHM = \sqrt{ U\tan{^2} \theta + V\tan \theta +W }
$$

- Se mide el FWHM 
- Se mide el FWHM del equipo
- Se obtiene el corregido restando ambos 

Quitado todo el error instrumental se puede utilizar la siguiente ecuación para poder calcular el tamaño de un cristalito 

$$
D = \frac{K\lambda}{\beta_{\text{muestra}}\cos \theta}
$$
K = 0.9 = factor de forma 

Lo que cambia el ancho del pico principalmente es el tamaño del cristal (más pequeño es más ancho), efectos instrumentales, tensiones no uniformes (deslazamiento de los átomos de sus posiciones ideales), defectos: Dislocaciones y defectos puntuales. 
- Tamaño de cristal 
- Efecto instrumental 
- Tensiones de red 
- Si se aplica Scherrer se tiene que expresar el tamaño en radianes 

Ecuación de Williamson-Hall 

$$
\begin{gather}
D = \frac{k\lambda}{\beta \cos \theta} \\
\epsilon = \frac{B}{4 \tan \theta}
\end{gather}
$$
En ambos casos se multiplica por coseno y queda 
$$
B \cos \theta = \frac{k\lambda}{d} + 4\epsilon sen\theta
$$


$$
\begin{gather}
B \cos \theta = \frac{k\lambda}{d} +4 
\end{gather}
$$

En el primer ejercicio se tuvieron los siguientes valores iniciales: 

Con estos datos se pudo identificar que se tiene que utilizar la ley de Bragg para poder encontrar el tamaño del cristal presente, para esto se utilizó la ecuación 

Tarea W-H 


Planteamiento del problema: 

En este ejercicio se analizó un difractograma de una muestra de $SrTiO_{3}$ que fue sintetizada a través de una reacción de sol-gel. Para este caso se pueden utilizar dos métodos diferentes, el primero implica el uso de la ecuación presente en \ref{eq:Scherrer} y el segundo implica el uso de la ecuación \ref{eq:W-H}; se van a utilizar ambos métodos para poder encontrar encontrar el tamaño del cristal. 

En el primer análisis se puede considerar que se tienen los datos presentes en la tabla \ref{tab:Datos_iniciales};a partir de estos datos se puede realizar el cálculo de la corrección instrumental ($\beta$) y el cálculo del tamaño de cristal con la ecuación \ref{eq:Scherrer} haciendo uso de la ecuación \ref{eq:correccion_inst} y \ref{eq:correccion_inst} , a partir de los resultados obtenidos con estas ecuaciones se pueden obtener los datos presentes en la tabla \ref{tab:Datos_Scherrer}; cuando se tuvo la corrección del ancho, se decidió utilizar la ecuación \ref{eq:Scherrer} para poder obtener el tamaño de grano; gracias a esta información se logró determinar que el tamaño de cristal promedio es de 8.67315177633129 nm. 


Para realizar el segundo método se tiene que considerar la ecuación \ref{eq:W-H}, donde a partir del análisis propuesto en la tabla \ref{tab:Datos_Scherrer} se puede calcular X y Y para realizar una regresión lineal haciendo uso de las formulas \label{eq:X} y \label{eq:Y}. Los datos considerados para la regresión lineal se encuentran en la tabla \ref{tab:X_Y}. La gráfica resultante de se encuentra en la figura \ref{fig:regrecion}, esta presentó la ecuación presente en \ref{eq:Regresion}, lo que nos permite realizar el procedimiento para encontrar la deformación que se presenta en \ref{eq:epsilon} y el tamaño de cristal presente en \ref{eq:D}