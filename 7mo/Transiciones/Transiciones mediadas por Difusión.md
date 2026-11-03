# Eccepción Espinodal 

La descomposición espinodal ocurre espontáneamente sin barrera de nucleación. Se produce cuando pequeñas fluctuaciones de composición reducen directamente la energía libre total del sistema-no se requiere superar ninguna barrera energética 
- Fluctuaciones de composición: Reducción inmediata de energía libre 
- Contrasta con nucleación y crecimiento: Núcleos de composición muy diferente a la matriz 
- Relevancia práctica: Formación de microestructuras moduladas en aleaciones de alta resistencia 
- Se da por pequeñas fluctuaciones en las concentraciones presentes, lo que da el crecimiento 


| Sistema/material                | Componentes Clave                  | Comportamiento en la descomposición                                                                                                            |
| ------------------------------- | ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Vidrios de borosilicato         | Óxido de silicio y óxido de boro   | Al enfriarse, se dividen uniformemente en una fase rica en boro y otra rica en sílice                                                          |
| Aleaciones metálicas Binarias   | hierro- cromo o Manganeso- cobre   | El sistema se separa de forma natural en islas ricas en un metal dentro de una matriz rica en el otro, alterando sus propiedades estructurales |
| Aleaciones con memoria de forma | Cobre-Aluminio-Manganeso           | El envejecido térmico induce precipitados que alteran y controlan de forma directa la transfomración martensítica del metal                    |
| Soluciones Poliméricas          | Mezclas de polímeros incorpatibles | Experimentan una separación rápida debido a fluctuaciones infinitesimales de densidad y composición química                                    |

# Condición Termodinámica para la descomposición espinoidal 

La condición fundamental es: 

$$
\frac{d^{2}G}{dX^{2}} <0
$$

Esto define que la región entre dos puntos de la inflexión de la curva G(x). 
Las fluctuaciones en el gradiente de concentración generan un cambio 

$$
\tau = -\frac{\lambda{^2}}{2\pi{^2}D}
$$

Energía libre química de la fluctuación de composición 

Expresión matemática: 
$$
\Delta G_{c} = \frac{1}{2} \frac{d{^{2}}G}{dX{^2}}(\Delta X){^2}
$$
Si los átomos A y B tienen tamaños diferentes, las diferencias de composición generan defromaciones de coherencia. La energía de deformación elastica es la siguiente: 
$$
\Delta G_{s} = \eta{^2}(\Delta X){^2}E'V_{m}
$$
Donde el parámetro de desajuste reticular es: 
$$
\eta = \frac{1}{a} \left( \frac{da}{dX} \right)
$$
Con $E' = \frac{E}{1-v}$ donde v es la razón de Poisson y Vm es el volumen molar 

$$
-\frac{d{^2}}{dX{^2}} > \frac{2K}{\lambda{^2}}+2\eta{^2}E'V_{m}
$$

Si se despeja la longitud de onda ($\lambda$) se puede encontrar cual es la longitud de onda mínima 

![[Pasted image 20261020113457.png]]


# Efecto Gibbs-thompson: Motor del engrosamiento 

- Se generan gradientes de concentración en la matriz entre las partículas de diferente tamaño 
- El soluto difunde desde las partículas pequeñas (alta concentración adyacente) hacia las grandes 
- Las nanopartículas pequeñas se disuelven, las grandes crecen 
- Resultado neto: Disminución del número total de partículas y aumento del radio medio $\bar{r}$. 
- Síntesis por alicuotas, se agarran de pocos átomos para poder evitar la aglomeración 
- Ley de lifshitz-Slyozov-Wagner: Asumiendo que la difusión volumétrica como factor controlante se puede encontrar que se obtiene una línea recta: 
- $(\bar{r}){^3}-r_{0}{^3} = kt$
- Donde 
	- $\bar{r}$: Radio medio en el tiempo t
	- $r_{0}$: Radio medio en el tiempo 0
	- k: Constante de engrosamiento 
- $k\propto D\gamma X_{e}$
- Donde 
	- D: Coeficiente de difusión del soluto en la matriz 
	- $\gamma$: Energía interfacial precipitado matriz 
	- $X_{e}$: Solubilidad de equilibrio en partículas de radio muy grande 
- Derivación de la tasa de engrosamiento: $\frac{d\bar{r}}{dt} \propto \frac{k}{\bar{r}{^2}}$
- Implicaciones prácticas de esto: 
	- Distribuciones de precipitados pequeños engrosan mucho más rápidamente 
	- Explica por que los materiales sobre envejecidos pierden propiedades rápidamente al inicio 
	- A medida que las partículas crecen la tasa de engrosamiento disminuye progresivamente
	- Una vez que las partículas son grandes, el engrosamiento se vuelve muy lento, la microestructura se estabiliza 
	- Tiene implicaciones para el diseño de tratamientos térmicos de estabilización 
- Estas formulas también tienen una dependencia en la temperatura
	- $D\propto \exp\left( -\frac{Q}{RT} \right), \quad X_{e}\propto \exp\left( -\frac{\Delta H}{RT} \right)$
	- Esto tiene las siguientes consecuencias: 
		- Materiales para alta temperatura deben de minimizar el producto de $D\gamma X_{e}$ ^20a8c3
		- El engrosamiento es el mecanismo dominante de degradación de propiedades en servicio prolongado 
		- La temperatura del servicio determina qué precipitados son estables a largo plazo 
		- Pequeños aumentos de temperatura generan grandes aumentos en la taza de engrosamiento 
- Principales causas de desviaciones
	- Cortos circuitos de difusión: Dislocaciones y fronteras de grano, aceleran el transporte de soluto. El coeficiente no varía, pero debido a ciertos defectos en el material se altera la 
	- Control por interfaz: Si la relación en interfaz es más lenta que la difusión 
- Se pueden optimizar los 3 factores presentes en [[Transiciones mediadas por Difusión#^20a8c3]] 
	- Mejorar las fases coherentes con otros átomos 
	- Disminuir la solubilidad agregando partículas muy estables (dispersión de óxidos)
	- 