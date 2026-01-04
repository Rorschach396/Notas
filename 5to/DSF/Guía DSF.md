# Conocimientos Previos
## Transformadas de Laplace 

Las esenciales para poder realizar los ejercicios son las siguientes: 

$$
\begin{gather}
\mathcal{L}\{f(t)\} = F(s)\\
\mathcal{L}\{\dot{f}(t)\} = sF(s) - f(0)\\
\mathcal{L}\{\ddot{f}(t)\} = s^2F(s) - sf(0)- \dot{f}(0)
\end{gather}
$$

Las transformadas de Laplace esenciales para poder realizar los ejercicios presentes en esta guía son las siguientes: 
$$
\begin{gather}
1 \rightarrow \frac{1}{s} \\
t^n \rightarrow \frac{n!}{s^{n+1}} \quad n \in \mathbb{R}\\
e^{at} \rightarrow \frac{1}{s-a}\\
t^ne^{at} \rightarrow \frac{n!}{(s-a)^{n+1}}\\
\sin (kt) \rightarrow \frac{k}{s^2+k^2}\\
\cos (kt) \rightarrow \frac{s}{s^2+k^2}
\end{gather}
$$
## Fracciones Parciales

Las fracciones parciales son una forma de poder reescribir una fracción para poder facilitar su solución, esta parte es esencial para poder obtener resultados que puedan ser reducibles a identidades de transformadas inversas de Laplace. 

Podemos hacer la siguiente clasificación de fracciones parciales: 


| Factor en el denominador | Termino en fracciones parciales                                                                                               |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| $ax + b$                 | $\frac{A}{ax + b}$                                                                                                            |
| $(ax + b)^k$             | $\frac{A_1}{ax+b} + \frac{A_2}{(ax+b)^2}+ \dots + \frac{A_3}{(ax+b)^k} \quad k=1,2,3,\dots$                                   |
| $ax^2 + bx +c$           | $\frac{Ax+b}{ax^2 +bx+c}$                                                                                                     |
| $(ax^2 + bx +c)^k$       | $\frac{A_1x + B_1}{ax+bx +c} + \frac{A_2x + B_2}{(ax+bx + c)^2}+ \dots + \frac{A_3x +B_3}{(ax+bx + c)^k} \quad k=1,2,3,\dots$ |

Esto se puede ejemplificar con los siguientes dos ejemplos: 

Supongamos que tenemos la siguiente fracción: 

$$
\frac{3x + 11}{x^2 - x -6}
$$

Esta fracción se puede separar en dos términos en el denominador de la siguiente forma: 
$$
\begin{flalign}
x^2 - x - 6 = (x-3)(x+2)
\end{flalign}
$$

De esto podemos realizar el siguiente procedimiento para obtener dos expresiones mas simples: 

$$
\begin{gather}
\frac{3x + 11}{x^2 - x - 6}= \frac{A}{x-3} + \frac{B}{x + 2}\\
\text{Resolviendo la sumatoria obtenemos:}\\
\frac{A(x+2) + B(x - 3)}{(x+3)(x-2)} \\
\text{Si resolvemos la parte superior:}\\
Ax + Bx + 2A -3B = 3x + 11 \\
\text {Que se representa en la siguiente matriz:}\\
\begin{bmatrix}
A & B & 3 \\
2A & -3B & 11
\end{bmatrix}\\
\text{Con los resultados:}\\
A =- 1 \quad B = 4
\end{gather}
$$

# Función de Transferencia

Los ejercicios a resolver en esta parte siguen los siguientes pasos: 

1) Obtenemos las ecuaciones diferenciales que describen un sistema
2) Realizamos las transformadas de Laplace a los sistemas 
3) Obtenemos la función de transferencia 
4) Revisamos la estabilidad del sistema

Las ecuaciones diferenciales del sistema normalmente nos las dan de forma automática, en caso de que no se tiene que realizar el análisis del sistema haciendo analogías con sistemas de los que se conozca el comportamiento. 

Cuando se tienen las transformadas de Laplace del sistema que se está analizando, se pueden encontrar polinomios de base s; los cuales pueden ser utilizados para poder obtener la función de transferencia que se ve de la siguiente forma: 

$$  
G(s) = \frac{p(s)}{q(s)} = \frac{p(s)}{(s+s_1)(s+s_2)\dots(s+s_n)}=\frac{b_ns^n + \dots+b_3s^3+b_2s^2+b_1s+b_0}{a_ns^n + \dots+a_3s^3+a_2s^2+a_1s+a_0}
$$

En el caso de analizar el sistema se puede encontrar que $Y(s)$ es la respuesta del sistema  y su respuesta esta dada por la siguiente ecuación: 

$$
Y(s) = G(s)X(s) = \frac{p(s)}{q(s)}X(s)
$$

Donde $X(s)$ es la transformada de Laplace de la entrada del sistema. 

%%En esta parte pondré mas acerca del tipo de ejercicios, como interpretar su resultado, un ejemplo y analizar su estabilidad%%

Suponiendo que se tienen las ecuaciones necesarias para poder realizar el ejercicio, ya se aplicaron las transformadas de Laplace y se tiene en una forma de polinomio se puede llegar a una expresión similar a la que se tiene en el siguiente ejemplo: 
```smiles 
Cn1cn(c)c2N(c)C=Nc2c(=o)1

CNC(C)Cc1ccccc1.

```
$$

$$
