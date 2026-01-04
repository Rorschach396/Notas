Se toma un electrón que sería el electrón ij-esimo, se calcula la energía en este electrón y se cambia el spin de este electrón, se calcula la delta de la energía, teniendo el factor de Boltzmann. Si se encuentra que la delta de energía es menor que 0, se acepta inmediatamente, si es mayor que 0, entonces se tiene que elegir un numero aleatorio donde pueden suceder dos cosas: 

- si el numero aleatorio entre 0,1 es menor que el factor de Boltzmann se acepta 
- Si es mayor, se niega 

$$
\begin{gather}

\hat{H} = \sum_{<i,j>} -J \hat{\sigma_{i}}\hat{\sigma_{j}} + \sum_{j} h \hat{\sigma_{i}} \\

H = \sum_{<i,j>} -J \sigma_{i} \sigma_{j}
\end{gather}
$$

$$
\begin{gather}
\text{Si} \quad \Delta E \le 0 \rightarrow\text{Siempre se acepta} \\
\text{Si} \quad \Delta E \ge 0 \rightarrow \text{Se acepta probabilisticamente:} \\
P(\text{acetpar}) = e^{-\Delta E/k_{B}T}  \\
\text{Se acepta si: } r < P(\text{aceptar}) | r \in (0,1) \\
r \text{ es completamente aleatorio}
\end{gather}
$$