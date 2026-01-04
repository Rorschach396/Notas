Se dispone de un modelo simplificado del maquinado que desprecia muchas de las complejidades geométricas y describe la mecánica de los procesos con buena precisión; se llama modelo de corte ortogonal. 
Usa una herramienta de corte en forma de cuña el cual tiene un borde perpendicular a la dirección de corte, en este caso se forman dos ángulos: 
- Ángulo de inclinación = $\alpha$
- Ángulo de incidencia/ángulo de plano de corte /ángulo de claro = $\phi$ 
Durante el corte se coloca un poco por debajo de la superficie original de trabajo, la relación entre el espesor antes de formación de la viruta y después de generar la viruta se le conoce como r y se calcula así, este valor siempre debe de ser menor a 1: 
$$
r = \frac{t_{0}}{t_{c}}
$$
además de t0 se tiene una dimensión de anchura, este muestra la relación entre espesor de viruta, ángulo de inclinación y ángulo de plano de corte: 

$$
r = \frac{l_{s}\sin (\phi)}{l_{s}\cos(\phi - \alpha)} = \frac{\sin(\phi)}{\cos(\phi-\alpha)} \rightarrow \tan(\phi) = \frac{r\cos(\alpha)}{1-r\sin(\alpha)} 
$$

## Deformación cortante

$$
\gamma = \frac{AC}{BD} = \frac{AD+DC}{BD} = \tan(\phi - \alpha) + \cot(\phi)
$$
La formula anterior es la definición de deformación cortante para corte de metales. 

![[Pasted image 20251007170943.png]]

$\gamma$ = deformación cortante 

# Formación de la Viruta 

- Viruta discontinua: Cuando se maquinan materiales frágiles o a bajas velocidades; no se obtienen rollitos, nomás se tienen pequeños trozos. 
- Viruta continua: Cuando se maquinan materiales dúctiles a altas velocidades y profundidades pequeñas, esto genera como resultado virutas largas y continuas.
- Virutas continuas con acumulación en el borde cuándo se maquinan materiales dúctiles a velocidades bajas o medias de corte, la fricción entre la herramienta y la viruta tiende a causar la adhesión de proporciones del material de trabajo de la herramienta cerca del filo cortante. 

## Relaciones de fuerza y la Ecuación de Merchant 

Se cundieran las fuerzas que actúan en la viruta durante el corte ortogonal, en este caso solo se pueden medir las fuerzas presentes en la herramienta. Las fuerzas se pueden clasificar de la siguiente forma: 

- Fuerza de fricción(F): Fuerza que resiste el flujo de la viruta a lo largo de la cara inclinada de la herramienta. 
- Fuerza normal a la fricción (N): Es perpendicular a la fuerza de fricción estos dos componentes se pueden utilizar para definir el coeficiente de fricción $\mu$ 
- $$
\mu = \frac{F}{N} = \tan (\beta)
$$
Donde $\beta$ es el ángulo de fricción. 

- Fuerza cortante(Fs): Es la fuerza que causa la deformación de corte que ocurre en el plano de corte. 
- Fuerza normal a la cortante(Fn): normal a la fuerza cortante
- Esfuerzo cortante: 
- $$
\begin{gather}
\tau = \frac{F_{s}}{A_{s}}\\
\text{Donde $\tau$ es la resistencia cortante}\\
A_{s} = \frac{t_{o}w}{\sin(\phi)}
\end{gather}
$$
```smiles


```
Fuerzas del material
- Fuerza cortante (Fc): que va en la dirección de corte
- Fuerza de empuje (Ft): Perpendicular a la fuerza de corte 
- R": Fuerza resultante de las dos anteriores. 

$$
\begin{gather}
F = F_{c}\sin(\alpha)+F_{t}\cos(\alpha) \\
N = F_{c}\cos(\alpha)-F_{t}\sin(\alpha) \\
F_{s} = F_{c}\cos(\phi)-F_{t}\sin(\phi) \\
F_{n}= F_{c}\sin(\phi) + F_{t}\cos(\phi)
\end{gather}
$$
$$
\begin{gather}
\phi_{M} = \frac{\pi}{4}+\frac{\alpha-\beta}{2} \\
\alpha = \text{\'angulo de filo} \\
\beta = \text{\'angulo de fricci\'on} = \mu = \tan(\beta)\\

\end{gather}
$$