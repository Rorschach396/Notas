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