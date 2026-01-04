
17-1) 
$$
\begin{gather}
\text{Tenemos lo siguiente:} \\
Q(T,B_{z}) = e^{\beta \hbar \gamma B_{z}/2}+e^{-\beta \hbar \gamma B_{z}/2} \\
\text{Sabemos que:} \\
\cosh(x) = \frac{e^x-e^{-x}}{2} \\
\text{Por lo que podemos reescribir Q como lo situiente:} \\
Q(T,B_{z}) = 2\cosh(\beta \hbar \gamma B_{z}/2) = 2\cosh\left( \frac{\hbar \gamma B_{z}}{2k_{B}T} \right) \\
\text{Luego podemos encontrar que: } \\
E = - \frac{\hbar \gamma B_{z}}{2}\left(\frac{e^{\beta \hbar \gamma B_{z}/2}-e^{-\beta \hbar \gamma B_{z}/2}}{e^{\beta \hbar \gamma B_{z}/2}+e^{-\beta \hbar \gamma B_{z}/2}}\right) \\
\text{Y tenemos la siguiente igualdad: } \\
\tanh (x) = \frac{e^x-e^{-x}}{e^x+e^{-x}} \\
\text{Por lo que podemos escribir lo siguiente:} \\
E =  - \frac{\hbar \gamma B_{z}}{2}\tanh(\frac{\beta \hbar \gamma B_{z}}{2}) = - \frac{\hbar \gamma B_{z}}{2}\tanh(\frac{ \hbar \gamma B_{z}}{2k_{B}T})
\end{gather}
$$
17-6)

$$
\begin{gather}
\text{Tenemos en el ejemplo anterior que E es igual a un multiplo de tanh}  \\
\text{cuando esta es evaluada en el siguiente limite se obtiene el siguiente valor:}\\
\lim_{ x \to \infty } \tanh(x) = 1 \\
\text{Por lo que podemos decir que el valor de la evaluacion cuando T tiende a 0 es:} \\
 E = - \frac{\hbar \gamma B_{z}}{2} \\
\text{Cuando se tiene un valor de T que tiende a infinito, entonces el valor total de la division es} \\
\text{0, por lo que se puede decir que se tendria que evaluar la tanh en 0} \\
\text{, que nos da un valor de 0, por lo tanto:} \\
E = 0
\end{gather}
$$
17-7)

$$
\begin{gather}
\text{Para un núcleo con espín s=1s=1, los números cuánticos magnéticos posibles son m=−1,0,1m=−1,0,1. La energía de cada estado en un campo magnético BzBz​ está dada por Em=−ℏγBzmEm​=−ℏγBz​m. La función de partición QQ se calcula como la suma sobre todos los estados:} \\
Q = 1 + 2\cosh(\beta \hbar \gamma B_{z})\\
\text{La energía promedio ⟨E⟩se obtiene de:} \\
 E = \frac{-2\hbar \gamma B_{z}\sinh(\beta \hbar \gamma B_{z})}{1 + 2\cosh(\beta \hbar \gamma B_{z})}\\
\text{Límite de baja temperatura (T→0T→0, β→∞β→∞):  
Cuando β→∞β→∞, x=βℏγBz→∞x=βℏγBz​→∞. Se tiene sinh⁡(x)≈cosh⁡(x)≈12exsinh(x)≈cosh(x)≈21​ex, por lo que:} \\
E \sim -\hbar \gamma B_{z} \\
\text{En el caso del limite de alta temperatura se obtiene que T tiende a infinito y beta tiende a 0, por lo que:} \\
E \sim -\frac{2}{3} \frac{(\hbar \gamma B_{z})^{2}}{k_{b}T} \\

\end{gather}
$$


17-8)