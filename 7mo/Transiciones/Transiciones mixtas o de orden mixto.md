# Definiciones
<mark style="background: #FF5582A6;"> Transiciones de orden mixto</mark>: Son transiciones de fase que muestran propiedades tanto de transiciones de primer orden como de segundo orden. Esto quiere decir que muestran un cambio abrupto en el parámetro de orden al mismo tiempo que muestran una desviación en la correlación de la longitud. 

<mark style="background: #ADCCFFA6;">Transiciones de primer orden</mark>: Surge de la clasificación de Ehrenfest, que fue hecha en 1933 por Paul Ehrenfest, en el caso de estas transiciones se presenta un cambio o "salto" en la entropía



$S=-\left( \frac{\partial{}G}{\partial{}T} \right)_{p}$


o en el volumen 

$v=\left( \frac{\partial{}G}{\partial{}p} \right)_{T}$ 

en el punto de transición.

<mark style="background: #ADCCFFA6;">Transiciones de segundo orden</mark>: No presentan un cambio en la entropía ni en el volumen al momento de pasar por el punto de transición (las primeras derivadas son continuas) pero si hay un cambio en la capacidad calorífica (

$c=\left( \frac{\partial^{2}G}{\partial{}T^{2}} \right)_{p}$

) o en alguna otra segunda derivada. 

![[Pasted image 20261116133640.png|531]]

<mark style="background: #ABF7F7A6;">Ejemplo del ADN</mark>: Este modelo surge de la forma en la que se desnaturaliza el ADN. Cuando el ADN se desnaturaliza el ADN se puede considerar que se separa en forma de burbujas o "loops" y en conexiones. Las propiedades del sistema se pueden comprender mejor a través del comportamiento de la distribución del las burbujas y el tamaño: 

$$
\begin{gather}
P(T,l) \propto \frac{e^{-l/\zeta(T)}}{l^{c}}  \\
\zeta \sim \frac{1}{|T-T_{c}|^{v}} \\
P(l)\propto \frac{1}{l^{c}}
\end{gather}
$$
En este caso se puede ver que la función tiene ambos comportamientos (tanto el de una transición de primer orden como de segundo orden), esto debido a que cuando c >2 (caso de la ecuación de p nomás con l) el valor promedio del tamaño de los bucles diverge. Además de esto en el caso de la ecuación de P con T y l esta se puede volver infinito cuando la ecuación de zeta tiende a infinito. Esto se puede ver muy similar a lo que sucede con el ==🔴*Condensado de Bose-Einstein*==, donde llegando a una determinada temperatura, se puede considerar que toda la cadena de ADN pasa a ser una sola burbuja. 

$$
\zeta \propto |T-T_{c}|^{-v}
$$
