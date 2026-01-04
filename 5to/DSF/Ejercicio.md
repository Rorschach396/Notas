Tenemos el siguiente sistema que se tiene que resolver: 

$$
\begin{gather}
\dot{x} = 10(x-y) \\
\dot{y} = x(28-z)-y \\
\dot{z} = xy - \frac{8}{3} z
\end{gather}
$$
Primero se tiene que encontrar los puntos en los que las ecuaciones se vuelven 0, esto igualando las ecuaciones a 0 y luego determinando los valores. 

$$
\begin{gather}
10(x-y) = 0 \rightarrow x=y \\
\text{si se tienque x = 0, se tiene la solucion trivial, entonces } \\
x(1)-y= 0 \rightarrow z = 27 \\
xy - \frac{8}{3}z \rightarrow x^2 - 72 = 0 \rightarrow x = \pm \sqrt{ 72 } \\
\text{Obtenemos el los siguientes puntos: } \\
(0,0,0), (\sqrt{ 72 },\sqrt{ 72 },27),(-\sqrt{ 72 },-\sqrt{ 72 },37)
\end{gather}
$$
Ahora obtenemos las diferentes funciones de las ecuaciones de la primera parte para obtener sus derivadas para realizar el jacobiano. 
$$
\begin{gather}
f_{1}(x,y,z) = 10(x-y) \\
f_{2}(x,y,z)= x(28-z)-y \\
f_{3}(x,y,z) = xy - \frac{8}{3} z
\end{gather}
$$
Consideramos que la jacobiana ahora seria: 
$$
J =\left[ \begin{matrix}
 \frac{\partial f_{1}}{\partial x} & \frac{\partial f_{1}}{\partial y} &\frac{\partial f_{1}}{\partial z}\\
 \frac{\partial f_{2}}{\partial x} & \frac{\partial f_{2}}{\partial y} &\frac{\partial f_{2}}{\partial z}\\ 
\frac{\partial f_{3}}{\partial x} & \frac{\partial f_{3}}{\partial y} &\frac{\partial f_{3}}{\partial z}
\end{matrix}\right] 
= 
\left[ \begin{matrix}
 10&-10 &0\\
 28-z & -1 &-x\\ 
y & x &-\frac{8}{3}z
\end{matrix}\right]
$$
Evaluamos en el punto $(\sqrt{ 72 },\sqrt{ 72 },27)$ : 
$$
\begin{gather}
A_{1} =
\left[ \begin{matrix}
 10&-10 &0\\
1 & -1 &-\sqrt{ 72 }\\ 
\sqrt{ 72 } & \sqrt{ 72 } &-72
\end{matrix}\right] \\
B_{2} =
\left[ \begin{matrix}
 10&-10 &0\\ 
28 & -1 &0\\ 
0 & 0 &0
\end{matrix}\right] \\
C_{3} = \left[ \begin{matrix}
 10&-10 &0\\
55 & -1 &\sqrt{ 72 }\\ 
-\sqrt{ 72 } & -\sqrt{ 72 } &72
\end{matrix}\right]
\end{gather}
$$

Ahora obtenemos los eigenvalores: 

$$
A_{1} =
\left[ \begin{matrix}
 10&-10 &0\\
1 & -1 &-\sqrt{ 72 }\\ 
\sqrt{ 72 } & \sqrt{ 72 } &-72
\end{matrix}\right] \\ 
-\left[
\begin{matrix}
 \lambda&0 &0\\
0 & \lambda &0\\ 
0 & 0 &\lambda
\end{matrix}
 \right]
$$


# Ejercicio 2 

$$
\begin{gather}
\dot{x_{1}} = x_{2} \\
\dot{x_{2}} = g - \frac{c}{m} \frac{x_{3}^2}{x_{1}} \\
\dot{x_{3}} = - \frac{R}{L} x_{3} + \frac{1}{L} u  \\
y = x_{1}
\end{gather}
$$