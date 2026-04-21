La principal diferencia es lo que nos permite ver, en el caso de la microscopia normal son los fotones, en el caso de la microscopía electronica son los electrones. 

- Transmisión: Lentes electromagnéticas, resolución máxima de 0.1 nm y requiere muestras ultrafinas. 
- Barrido: Lentes electromagnéticas, resolución máxima de 1 nm y superficies 3D y volumen masivo (alta profundidad de campo).

Partes principales : 

- Cañón de electrones (cátodo/ánodo): Genera y acelera el haz inicial en alto vacío 
- Lentes condensadoras: Des magnifica el haz reduciendo el tamaño de la sonda 
- Bobinas de barrido: Desvía el haz magnéticamente para rear un patrón de trama sobre la muestra 
- Lente objetiva y apertura: Enfoca el haz final sobre la superficie de la muestra
- Camara de muestra y detectores: El volumen de interacción emite señales capturadas por detectores ET (electrones secundarios ) y de estado sólido (retro dispersados)

Existen dos formas de poder generar los electrones: 

- Emisión termiónica: No requiere un vacío muy alto, tiene un menor brillo pero la resolución es medio buena. Normalmente sus filamentos son de tungsteno o de Hexa boruro de lantano. 
	- Calienta extremo para vencer la barrera de trabajo
	- la resolución es estándar 
- Emisión de campo: Requiere un mayor vacío, tiene un brillo máximo y tiene una excelente resolución
	- Puede ser frio o de efecto Schottky
	- Un intenso campo magnético extrae electrones de una punta afilada 
	- Requiere un muy buen vacío pero gracias a esto tiene una excelente resolución. 

- El paradigma de la desmagnificación: A diferencia de la óptica tradicional las lentes condensadoreas del MEB reducen el tamño de la fuente electrónica original
- El efecto de la lente fuerte: Un campo magnético intenso crea un cruce focal corto, esto reduce drásticamente el diámetro final de la sonda mejorando la resolución pero sacrificando la corriente total del haz. 
Volumen de interacción:
- Zona 1: La superficie de 1 a 10 nm los electrones de baja energía son expulsados revelando la topología. 
- Zona 2: Los electrones primarios rebotan elásticamente revelando la composición, esto se da entre los 100 y los 300 nm. 
- Zona 3: Profundidad máxima de 1 a 5 $\mu m$, emisiones electromagnéticas profundas. Revela posibles huellas químicas elementales. 

Se puede modificar el voltaje de trabajo para poder obtener diferentes espesores en las diferentes zonas. 

Efecto de borde: Debido a que en ciertos casos se producen bordes afilados, se generan una gran cantidad de electrones que escapan de esas zonas, generando un mayor brillo gracias a que se generan una gran cantidad de electrones secundarios. 

Electrones retro dispersados: 
- Dispersión elástica: Los electrones del haz chocan con los núcleos atómicos de la muestra y rebotan como bolas de billar reteniendo alta energía. Bajo numero atómico genera menos rebotes. 
- Contraste composicional: Elementos pesados aparecen más brillantes que los ligeros. Esto permite diferenciar fases químicas visualmente en muestras pulidas sin necesidad de mapeo de rayos X. 

Voltaje de aceleración: 
- Alto kV: Mayor penetración y excelente para EDS 
- Bajo kV: Máxima sensibilidad superficial ideal para nanomateriales, pero tiene una señal débil 
Corriente de la sonda: 
- Spot pequeño: Alta resolución, imagen ultra nitid. Señal débil imagen granulada 
- Spot grande: Excelente relación señal ruido, necesario para mapeo EDS, pero la resolución óptica se degrada. 

Geometría y profundidad de campo: 

- Angulo de convergencia: Un ángulo más agudo mantiene el foco a través de variaciones extremas de altura topográfica 
- Apertura: Estrechar el diámetro aumenta masivamente la profundidad de campo pero sacrifica la cantidad de señal. 
- Distancia de trabajo: Alejar la muestra aplanada
	- Gran WD = profundidad 
	- Corto WD = resolución
Guía de operación 
- Aumento de voltaje: Mejor resolución pero se pierde detalle superficial y hay riesgo de carga.
- Aumentar el spot size: Hay mas ruido pero menor resolución espacial y se daña un chingo la muestra. 
- Aumentar distancia de trabajo: Profundidad de campo pero sin detalles pero con mucho campo de visión. 
- Disminuir la apertura: Profundidad de campo mejorada con una buena resolución pero se pierde el brillo. 

Preparación de la muestra: 
- Corte y montaje
- Desbaste y pulido 
- Ataque químico 
- Recubrimiento (sputtering)

Para muestras biológicas: 
- Fijación en glutaraldehído
- Deshidratación 
- Punto crítico: Se seca con CO2
- Recubrimiento metálico indispensable 

## Cañón de electrones

- Emisión termiónica: Un filamento de tungsteno se calienta hasta 2500°C, supera la función de trabajo del metal, el tamaño de fuente es grande, produce un menor brillo y es bastante económico y robusto. 
- Emisión de campo: Un campo eléctrico intenso arranca electrones de una punta ultra fina, tamaño de fuente diminuto, haz extremadamente coherente y tiene una ultra alta resolución. 

Debido a las fuerzas de atracción que existen entre los electrones con carga negativa y los nucleos positivos de los átomos del metal, los electrones requieren energía para salir de una superficie metálica, si un metal se calienta a una temperatura suficientemente alta, algunos electrones adquieren suficiente energía para que se puedan desprender. 

Principio de funcionamiento del camón de W 
- Se usa corriente eléctrica para poder calentar el W
- El filamento está rodeado por un cilindro de Wehnelt, que se conecta con una resistencia variable de auto polarización 
- Se genera una polarización negativa entre ambos 
- Tamaño de emisión de entre 100 y 150 $\mu m$
- El cilindro de Wehnelt ayuda a poder comprimir los electrones hacia el eje y evita que se sobrecaliente el filamento de W 

- Bias bajo: Enfoque deficiente y enfoque deficiente 
- Alto: El brillo se vuelve 0 
- Óptimo: los electrones emitidos desde los lados tienden a ser devueltos al filamento. 

No importa cuanta corriente le pongamos al filamento, llega a un punto en el que se alcanza la mayor cantidad de brillo y no se puede pasar de ahí. 

Las lentes electromagnéticas ayudan a reducir el diámetro inicial del haz, esto es realizado por la lente condensadora, la lente objetiva realiza el enfoque final justo antes de que el haz golpee la superficie. 

El detector EDS clasifica estos rayos X por su nivel de energía, permitiendo identificar y cualificar los elementos químicos presentes en un volúmen de pocos micrómetros. 
1) Llega el electron  y mueve a otro a un nivel superior 
2) El electrón baja y produce un rayo X característico 
3) Se clasifica este rayo y se produce un gráfico 

Hexa Boruro de lantano 

El emisor está hecho de LaB6, de color púrpura violet. Tiene un punto de fusión de 2210°C se utiliza por que su temperatura de función es bastante baja, gracias a esto permite tener una mayor emisión a temperaturas más bajas de alrededor de 1400-1600°C. Este tipo de emisor es bastante más brillante que el filamento de W, y es bastante más duradero, con hasta 10 veces más la vida util de un W.  La unica contra es que es también 10 veces más caro y requieren un chingo de vacio.



Cañones de emisión de campo

En este caso los cables de tungsteno están bastante afilados, por lo que cuando se le aplica un potencial negativo se concentra en la punta y se liberan electrones. A este fenómeno se le conoce como túnel cuántico. No requiere una gran des magnificación para producir un tamaño de sonda pequeño. 

Requiere menos lentes, lo que puede llegar a simplificar el diseño del microscopio, no requiere cross over. Tiene menos aberraciones cromáticas y menor tamaño de sonda. El brillo es 1000 veces mayor que el filamento de W, la dispersión es 4 veces menor y tiene una mayor durabilidad, pero también tiene un mayor costo y requiere de condiciones de vacío más rigurosas. 

Emisores de campo Frio

Solo produce electrones de la punta de un cable de W con ayuda de un campo eléctrico pero sin la ayuda de calor, este tiene una corriente de emisor es bastante pequeña, su brillo es bastante más alto que el filamento tradicional, la dispersión energética es mucho más bajo. De vez en cuando se tiene que realizar un flash con la punta para poder eliminar los gases absorbidos, esto se puede repetir bastante hasta que se acabe la punta. 

Emisor de campo tipo Shottky 

Es un cañón de emisión de campo asistido térmicamente en el que se hace uso del efecto Schottky donde se aplica al emisor una cierta cantidad de voltaje para poder calentarlo y así reducir su temperatura de funcionamiento. El Filamento de tungsteno de este tipo está recubierto con óxido de zirconia. La alta corriente de emisión disminuye el efecto de las vibraciones, este siempre se mantiene encendido para poder evitar la contaminación de la punta, no requiere mucho vacío ni que se le limpie la punta, normalmente aguantan hasta 2 años de servicio. 

Lentes electromagnéticas 

Cilindros que son análogos a las lentes convexas delgadas utilizadas para enfocar la luz visible en microscopía óptica, están hechas de bobinas de cu encerradas en carcasa de hierro que tiene piezas polares cilíndricas, la distancia focal de las lentes cambia dependiendo de la corriente de las bobinas. 

El campo electromagnético tiene una componente radial y una componente axial longitudinal. EL campo radial hace que los electrones fuera del eje  descienda en espiral por el eje óptico en una trayectoria helicoidal. La interacción entre los electrones que emanan del cañón y el campo magnético desvían los electrones hacia el eje. Los electrones alejados del eje óptico son desviados con mayor fuerza. 

Lente condensadora: Es una lente electromagnética que se coloca justo debajo del cañón de electrones, su trabajo es reducir el diámetro del haz, normalmente hay 2 o 3 lentes condensadoras en serie. Se debe  de des magnificar para poder tener una donde fina que nos permita ver realmente la superficie. Estas lentes se controlan con el spot size y al momento de cambiar este ajuste se cambia la corriente en todas las bobinas presentes en las lentes. 

Cuando se cambia la corriente de la lente se vuelve más potente, los electrones se dispersan más y chocan más con la apertura, generando que muy pocos electrones puedan llegar a la muestra generando una alta resolución pero muy oscura y con mucho ruido. Si la lente no tiene mucha corriente casi todos los electrones pasan y se tiene una sonda muy grande, esto genera que se tenga una zonda muy grande con mucho brillo, lo que es bueno para el análisis químico pero no sirve mucho para poder ver las cosas. 

Aperturas 

Permite evitar que los electrones fuera del eje puedan llegar a la muestra. Esto disminuye las aberraciones de la imagen. Si la superficie de la apertura está sucia se genera astigmatismo. El pinhole se utiliza para imágenes convencionales a aumentos relativamente bajos, permite muestras grande y grandes distancias de trabajo, esto da como resultado una alta profundidad de campo. 

Lente de inmersión: La muestra se coloca dentro del orificio de la lente. El campo magnético envuelve la muestra dando una distancia focal pequeña de 2-5 nm, la menor distancia de trabajo y distancia focal produce la menor aberración de la lente, el tamaño de sonda más fino y la mayor resolución de imagen. 

Lente snorkel: La muestra se coloca inmediatamente debajo de la lente objetivo, el campo magnético se extiende a la superficie de la muestra. Combina los beneficios de ambos tipos: permite imágenes de alta resolución mientras que permite examinar muestras relativamente grandes. 

Aberración esférica: El campo electromagnético es más fuerte cerca del borde de la lente y más débil cerca del eje óptico. Como resultado, los electrones cerca del borde son desviados más fuertemente que los electrones cercanos al eje. 


## Aberraciones de la Lente 

Aberración esférica: Se da por que el campo electromagnético es más fuerte cerca del borde de la lente y más débil cerca del eje óptico, esto produce que cerca del borde se desvían más fuertemente los electrones se desvíen más que los lejanos, esto produce diferentes puntos de enfoque según la parte de la lente por donde pasan los electrones, los rayos convergen formando un disco en lugar de un punto en el plano imagen (la imagen se ve borrosa). Para poder controlar este efecto se puede agregar una apertura pequeña  después de la lente objetivo, también se puede utilizar una lente de inmersión 

Aberración cromática: No todos los electrones del haz poseen la misma energía, los electrones de menor energía se enfocan más cerca de la lente mientras que los electrones con más energía se enfocan más lejos de la lente. Dependiendo del voltaje se pueden obtener diferentes efectos, normalmente genera que los contornos no se puedan ver tan bien, además de que se ven un poco más borrosas. FEG es ideal para microscopía de bajo voltaje, esto genera que no tengan mucha aberración cromática a bajos voltajes (Schottky y cold). 

Difracción en la apertura: Por la naturaleza ondulatoria los electrones tienden a difractar en el borde de la apertura pequeña  usada para reducir aberraciones. Se forma un patrón de difracción de Fraunhofer en forma de disco de Airy, este efecto aumenta cuando el ángulo de convergencia se hace más pequeño. 

Astigmatismo: Pequeñas imperfecciones en la construcción del lente, asimetría en los devanados de cobre o aperturas contaminadas forman dos focos lineales perpendiculares a dos distancias focales diferentes, la imagen se estira en una dirección en un lado del foco, este fenómeno se detecta como astigmatismo. Para poder corregir el astigmatismo se puede utilizar un estimator para poder generar el efecto inverso y eliminar las aberraciones. 



