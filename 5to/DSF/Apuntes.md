
$$
\begin{gather} \\
 


SNL \rightarrow
\begin{cases}
\dot{x} &= Ax + Bu \\ 
y &= Cx + Du
\end{cases} 

\end{gather}
$$

## Sistemas No Lineales 

$$
\text{Sistema no lineal} \rightarrow ml \ddot{\Theta} = -mg\sin(\Theta)-k_{f}l \dot{\Theta}
$$
El sistema se puede linealizar para poder analizarlo, esto se puede hacer realizando los siguientes pasos: 
- Obtener los puntos de equilibrio ($x^*$)
- Obtener el jacobiano del sistema (J)
- Evaluar el jacobiano en los puntos de equilibrio (J($x^*$))

$$
\dot{x} =\left[ \begin{matrix}
0 & 1 \\
0& \frac{-k_{f}}{m}
\end{matrix}\right] +\left[ \begin{matrix}
0 \\
\frac{-g}{l}\sin(x_{1})
\end{matrix}\right]
$$
Debido a el sistema que tenemos (un péndulo) solo se pueden tener valores específicos de pi, estos se tienen que obtener de aquí: $x_{1} = n\pi \quad n\in \mathbb{R}$  

Jacobiana 

$$
J =\left[ \begin{matrix}
 \frac{\partial f_{1}}{\partial x_{1}} & \frac{\partial f_{1}}{\partial x_{2}} \\
 \frac{\partial f_{2}}{\partial x_{1}} & \frac{\partial f_{2}}{\partial x_{2}}
\end{matrix}\right]
$$

## Primer Examen 
%% wtf si se paso el examen %%
$$
\begin{gather}
(I + ml^2)\ddot{\phi}-mgl\phi = ml \ddot{x} \rightarrow \text{pendulo} \\  
(M+m)\ddot{x} + b\dot{x} - ml \ddot{\phi} = u \rightarrow \text{carrito}\\
\text{ Sea }B= I + ml^2, \quad \eta = M + m \\
B \ddot{\phi} - mgl \phi = ml \ddot{x} \\
\eta \ddot{x} + b\dot{x} - ml \ddot{\phi} = \eta \\
\text{obtenemos la laplaciana de las ecuaciones que con las C.I. = 0 obtenemos:}  \\
B s^2 \Phi(s) - mgl\Phi(s) = mls^2 X(s) \rightarrow 1 \\
\eta s^2 X(s) + b sX(s) - mls^2\Phi(s) = U(s) \rightarrow 2 \\
\text{Despejamos de X(s) de 1 } \\
X(s) = \frac{Bs^2\Phi(s)-mgl\Phi(s)}{mls^2} \rightarrow 3 \\
\text{Sustituimos 3 en 2:} \\
X(s)[\eta s^2 + bs]-mls^2\Phi(s)=U(s) \\
\frac{\Phi[Bs^2-mgl]}{mls^2}[\eta s^2+bs]-mls^2\Phi(s)=U(s) \\
\Phi(s)\frac{[Bs^2 -mgl][\eta s^2+bs]-m^2l^2s^3}{mls} = U(s) \\
\Phi(s)\frac{B\eta s^3 - bBs^2-mgl\eta s - mglb - m^2l^2s^3}{mls}=U(s) \\
 \text{Obtenemos la funcion de transferencia:} \\
Gs(s) = \frac{mls}{s^3(B\eta - m^2l^2)-bBs^2-mgl\eta s - mglb} \\
\text{A partir de esto obtenemos los polos y ceros de la funcion para poder} \\
\text{determinar la estabilidad del sistema.}
\end{gather}
$$

# Ecuación del Péndulo 

$$
\begin{gather}
\dot{x_{1}}= x_{2} \\
\dot{x_{2}} -\frac{g}{l}\sin(x_{1})-\frac{k_{f}}{m}x_{2} \\
\text{Esto se puede transformar en los siguiente} \\
-\dot{x_{2}} - \frac{g}{l}\sin(x_{1}) = \frac{k_{f}}{m}x_{2} \\
- \frac{m}{x_{2}}\dot{x_{2}}-\frac{gm}{lx_{2}}\sin(x_{1}) = kf  \\
\text{Para poder encontrar cual es el valor de $x_{2}$ se tiene que utilizar matlab} \\

\end{gather}
$$
- Seguimiento 
- Regulación
- Controlable -> Controles
- Observable -> Observadores

$$
\begin{gather}
\text{Oscilador Armónico forzado y amortiguado: } \\
m \ddot{x} + c\dot{x} + kx = F(t) \\
\text{Sistema de masas acopladas con fuerzamiento externo: } \\
m_{1} \ddot{x_{1}} = -k_{1}x - k(x_{2}-x_{1})\\
m_{2} \ddot{x_{2}} = -k_{2}(x_{2}-x_{1}) - k_{3}x_{2}+F(t) \\
\text{Metodo Tai Lung:} \\
m = -\frac{b}{2} \\
u = \sqrt{ m^2-c } \\
x_{1} = m - u  \\
x_{2} = m + u
\end{gather}
$$
# Resumen del curso

```smiles
c1ccccc1

```

$$
\begin{gather}
\lambda^4 - A\lambda^3 - \beta \lambda^2 - \beta(\alpha-A)\lambda = 0 
\end{gather}
$$

$$
\begin{gather}
J \ddot{\theta} + b \dot{\theta} = ki \\
L \frac{di}{dt} + Ri  = v - k \dot{\theta} \\
\end{gather}
$$
$$
\dot{x} = \left[
\begin{matrix}
\dot{\theta }\\
\ddot{\theta} \\
\dot{L}
\end{matrix}
\right ] = 
\left[
\begin{matrix}
0 & 1 & 0  \\
0 & -\frac{b}{j} & \frac{k}{j} \\
0 & -\frac{k}{L} & -\frac{R}{L}
\end{matrix} \right] 
\left[
\begin{matrix}
\theta \\
\dot{\theta} \\
i
\end{matrix} \right]
+ \left[
\begin{matrix}
0 \\
0 \\
\frac{1}{L}
\end{matrix} 
\right]v

$$
$$
y = \left[
\begin{matrix}
1 \\
0 \\
0
\end{matrix}
\right]
\left[
\begin{matrix}
\theta \\
\dot{\theta} \\
i
\end{matrix}
\right]
$$
también puede ser: 
$$
y = \left[
\begin{matrix}
1 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 0
\end{matrix}
\right]
\left[
\begin{matrix}
\theta \\
\dot{\theta} \\
i
\end{matrix}
\right]
$$


