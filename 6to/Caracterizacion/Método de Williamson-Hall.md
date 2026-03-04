Este método es para poder determinar el tamaño de los cristales. Cuando se hace un patron de dispersión de rayos x normalmente se pueden llegar a tener ciertas modificaciones a la hora de analizar los picos, esto se puede deber a ciertos factores. En este método se analiza el ancho de los perfiles de difracción a una altura media (FWHM) el cual puede llegar a variar dependiendo de fallas de apilamiento, deformaciones o ensanchamiento. Hay ciertas funciones que permiten obtener el FWHM que son: 
- Voight 
- Lorentz 
- Gauss 

En este caso el método de Williamson-Hall se enfoca en poder graficar la amplitud de los picos con el ángulo de Bragg, en este caso la pendiente de la gráfica da información de la deformación y la ==intersección con el eje vertical proporciona información sobre el tamaño de cristal.== 

$$
\begin{gather}
\text{Ecuación de Scherrer} \\
\beta = \frac{K\lambda}{D\cos(\theta)}
\end{gather}
$$

El método de Williamson-Hall se basa en lo siguiente: 
$$
\begin{gather}
\beta_{total} = \beta_{instrument} + \beta_{sample} \\
\beta_{instrument} = \frac{K\lambda}{D\cos(\theta)} \\
\beta_{sample} = 4 \epsilon \tan(\theta) \\
\text{Recontruido} \\
\beta_{total}\cos(\theta) = \frac{K\lambda}{D} + 4\epsilon \sin(\theta) \\
\text{Factor de forma} = \frac{K\lambda}{D}
\end{gather}
$$

Índice de cristalinidad 

$$
X_{c} = \frac{\text{area cristalina}}{\text{area total}}\text{x}100
$$
Area total = Area cristalina + Area amorfa 

El area cristalina es igual a el area que se encuentra justo abajo de los picos, el area amorfa es el area que esta abajo de todas las zonas que no son picos. Para poder calcular el índice de cristalinidad es necesario tener un perfil completo de XRD y tener identificación del halo amorfo. 

## Análisis de microestructura por difracción de rayos X (tamaño de cristal y micro deformación)

### Método de Scherr 
Estimar el tamaño promedio de los cristalitos asumiendo que todo el ensanchamiento del puco se debe únicamente al tamaño pequeño. Este se se basa en la siguiente formula: 
$$
D = \frac{k\lambda}{\beta \cos(\theta)} 
$$
### Método de Williamson - Hall 
Este se vio ayer en clase y esta en la parte superior, por si acaso, este se basa en la siguiente formula: 

$$
\beta_{total}\cos(\theta) = \frac{K\lambda}{D} + 4\epsilon \sin(\theta)
$$

### Método de deformación uniforme

La deformación (epsilon) es la misma en todas las direcciones cristalográficas. 

$$
\beta \cos(\theta) = \frac{k\lambda}{d} + 4 \epsilon \sin \theta
$$

### Modelo de deformación por esfuerzo uniforme

La deformación no es algo que se mida directamente en el material, sino que es una consecuencia de un esfuerzo aplicado. Se usa la lay de Hooke para sólidos elásticos 
$$
\sigma = Y \epsilon
$$

### Modelo de deformación por esfuerzo uniforme

Existe un esfuerzo uniforme en el material y la deformación se relaciona con el mediante la ley de Hooke. 

$$
\beta \cos \theta = \frac{k\lambda}{D} + \frac{4\sigma\sin\theta}{Y_{hkl}}
$$

Pendiente = esfuerzo 
$\frac{k\lambda}{D}$ = tamaño 

### Modelo de densidad de energía de deformación uniforme 

En este modelo se trabaja con la densidad de energía de deformación (u). Teniendo esto en cuenta la energía elástica almacenada por unidad de volumen en un material deformado se puede relacionar de la siguiente forma: 
$$
u = \frac{\epsilon^2Y}{2} = \frac{\sigma^2}{2Y}
$$
Se tiene que considerar la siguiente ecuación: 

$$
\beta_{hkl} \cos(\theta) = \frac{KY}{D} + 4\sin(\theta)\left( \frac{2u}{Y_{hkl}} \right)^{1/2}
$$
