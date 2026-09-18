Cambios de flujo de calor, mide la entalpía
- Tanto el TGA como el DSC son análisis térmicos

| Técnica                             | Abreviatura | Magnitud medida              |
| ----------------------------------- | ----------- | ---------------------------- |
| Termogravimetría                    | TG          | Cambio de masa               |
| Análisis térmico diferencial        | DTA         | Diferencia de temperatura    |
| Calorimetría diferencial de barrido | DSC         | Flujo de calor               |
| Dilatometría                        | ----        | Cambio de longitud o volumen |
| Análisis termomecánico              | TMA         | Deformación                  |
| Análisis mecánico dinámico          | DMA         | Deformación                  |

- Pueden utilizarse crisoles de platino. 
- TMA mide propiedades mecánicas respecto a la temperatura 

| Evento térmico                | Reacción                                             | Flujo de calor | Cambio de masa |
| ----------------------------- | ---------------------------------------------------- | -------------- | -------------- |
| Transformación de fase sólida | A (sólido $\alpha$) $\rightarrow$ A (sólido $\beta$) | $\pm$          | No             |
| Transición vítrea             | Vidrio -> caucho                                     | No             | no             |
| Fusión                        | Sólido -> líquido                                    | +              | no             |
| Sublimación                   | Sólido -> gas                                        | +              | si             |
| Descomposición térmica        | Sólido -> sólido + gas                               | $\pm$          | si             |
El análisis térmico se realiza habitualmente a presión constante debido a esto el calor intercambiado entre la muestra y su entorno queda descrito íntegramente por el cambio en la entalpía: 
$$
\begin{gather}
\Delta U = Q-W \\
\Delta U = Q_{p} P\Delta V \\
H = U + PV  \\
\Delta H = \Delta U + P\Delta V  \\
\Delta H  = Q_{p}
\end{gather}
$$
Si se tienen eventos muy puntuales se tiene que tener una rampa de calentamiento muy baja para poder evitar una mala lectura. 

Variables que condicionan la reproducibilidad del ensayo: 
- Masa y dimensión 
- Velocidad de calentamiento 
- Atmósfera 
- Historia térmica y mecánica: Ida y vuelta para poder eliminar cualquier lectura errónea 
$$
\Delta T = T_{s} - T_{r}
$$
Mismo material para la referencia y para el análisis, dentro del análisis de DTA se busca poder analizar cuanto se calienta el blanco y cuanto se calienta la mezcla. 

DSC de flujo de calor
- Mide directamente la diferencia de temperatura entre muestra y referencia 
- Un algoritmo del programa informático convierte esa diferencia en una diferencia de flujo de calor 
- El factor de calibración depende de la temperatura y debe determinarse próximo al pico a medir 

DSC de compensación por potencia 
- Dispone de dos cámaras independientes cada una con su propio elemento calefactor 
- el equipo mantiene n todo momento el estado de nulidad térmica 
- Un evento endotérmico exige aumentar la potencia suministrada a la muestra, uno exotérmico reducirla 
- La variación de potencia equivale a la energía del flujo térmico que compensa la absorción o liberación. 

Se puede poner la etiqueta de hacia donde es endotérmico y donde es exotérmico 

- Cambio de pendiente es la transición vítrea, se debe de saber mas o menos donde es  
- En el punto de fusión se absorbe el calor latente 
- Cristalización: Pico exotérmico la muestra libera calor 
- Fusión Pico endotérmico absorción de calor 
- Oxidación: Desviación sostenida de la línea base a alta temperatura


| Criterio                 | DTA                                                                                | DSC                                                                                  |
| ------------------------ | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| Magnitud registrada      | Diferencia de temperatura                                                          | Diferencia de flujo de calor                                                         |
| Naturaleza termodinámica | Cualitativa: La diferencia de temperatura no aporta datos cuantitativos de energía | Cuantitativas el flujo de calor proporciona el cambio de entalpía del evento         |
| Intervalo térmico        | superior a 1500                                                                    | hasta 750                                                                            |
| Convención de la curva   | Evento endotérmico hacia abajo                                                     | Evento endotérmico hacia arriba                                                      |
| Idoneidad                | Materiales de elevada temperatura de fusión                                        | Determinación de entalpías, capacidad calorífica y transiciones de baja temperatura  |
