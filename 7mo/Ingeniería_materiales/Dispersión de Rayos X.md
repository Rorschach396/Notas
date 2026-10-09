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