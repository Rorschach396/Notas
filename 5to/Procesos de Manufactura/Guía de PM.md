
# Conceptos Iniciales 

*Manufactura*: Derivada de manus (mano) factus (hacer); en otras palabras "hecho a mano". 

*Importancia de la manufactura*: 

- Transforma materia prima en bienes con valor agregado
- Es una de las principales motivaciones del desarrollo tecnológico, industrial y económico 
- Es fundamental en sectores como el automotriz, aeroespacial, salud y electrónica. 
- Puede ser fuente de empleo directo o indirecto 
- Permite la competencia a nivel global mediante eficiencia y calidad.

La manufactura permite poder obtener piezas que tengan dimensiones específicas y que tengan propiedades mecánicas adecuadas al uso que se le va ha dar, también permite obtener piezas con geometrías complejas  y mejora las propiedades de las piezas dependiendo del proceso que se le aplique para poder obtener la pieza. 

**Proceso Técnico y Económico**

1) Material de inicio: Es el metal o la materia prima que se utiliza para poder realizar un proceso
2) Proceso de manufactura: En este se modifica la materia prima inicial para poder obtener un valor agregado
	1) Scrap: Desechos producidos por la industria, en algunos casos se pueden reutilizar 
	2) Pieza procesada: Pieza que se va a vender 

**Clasificación de Procesos de Manufactura**

- **Conformado**: Forja, laminado, extrusión y embutido. 
- **Fundición**: Moldes por arena, cera perdida y colada continua. 
- **Maquinado**: Torneado y fresado.
- **Unión**: Soldadura, remachado y pegado 
- **Procesos Especiales**: Corte láser, plasma, chorro de agua y mecanizado por descarga eléctrica (EDM). 

# Esfuerzo y Deformación en Materiales 

Esfuerzo-deformación: Concepto que describe como un material se deforma bajo la acción de fuerzas externas, esto permite entender el comportamiento mecánico de los materiales para poder determinar donde se pueden utilizar. 

Esfuerzo: Fuerza aplicada por unidad de área. 
Deformación: Cambio relativo en las dimensiones del material, podemos encontrar que este tiene la siguiente formula: 
$$
\epsilon = \frac{\Delta L}{L_0}
$$

La curva de esfuerzo-deformación es una herramienta visual que muestra como un material responde al esfuerzo aplicado, en este grafico se coloca en el eje vertical (y) el esfuerzo y en el eje horizontal (x) la deformación, dando como resultado un grafico similar al siguiente: 

![[Pasted image 20250923200544.png]]


Donde podemos encontrar 3 zonas que descritas de forma muy sintetizada son las siguientes: 

- Zona elástica: Zona en la que, a pesar de que el material presente una deformación, cuando se le elimina el esfuerzo aplicado, la deformación también es eliminada. 
- Zona plástica/dúctil: Zona en la cual el material se deforma de forma plástica, es decir, se deforma permanente mente; generando que aunque se elimine el esfuerzo no se elimine la deformación.
- Límite de fractura: Es el punto en el esfuerzo aplicado genera que se rompa el material. 

Para poder predecir el comportamiento de un material se suelen utilizar ensayos donde se le coloca una carga al material y se observa su comportamiento, los ensayos más comunes son los siguientes: 

- Ensayo de tensión: Técnica donde a una muestra de un material se le somete un esfuerzo creciente hasta que la pieza falla, este ensayo produce la curva de esfuerzo-deformación, esta se encuentra descrita de forma más profunda en [[Ensayo de Tracción]]. 
- Ensayo de compresión: Ensayo donde se le coloca una carga compresiva a un material, hasta que el mismo falle, este tipo de ensayo es bastante útil en cerámicos como el concreto ya que permite comprender como es que se va a comportar bajo esfuerzos típicos para este material.
- Ensayo de flexión: Determina que tan resistente es un material a ser doblado, normalmente utilizado en cerámicos debido a la dificultad que tienen para poder realizar un ensayo de tensión (descrito en [[Ensayo de Flexión]]). 
- Ensayo dinámicos: Ensayos donde al material se le somete a diferentes esfuerzos los cuales son oscilatorios y se mide como el material va a ser afectado por los mismos. 

En el caso del ensayo de tensión, este permite obtener el modulo de elasticidad (también conocido como modulo de Young) el cual se calcula con la siguiente formula: 

$$
\begin{flalign}
E &= \frac{\sigma}{\epsilon}\\
\text{Donde:}\\
\sigma &= \text{Esfuerzo}\\
\epsilon &= \text{Deformaci\'on}\\
\end{flalign}
$$

# Fluencia

Concepto: Fenómeno por el cual un material experimenta deformaciones permanentes y progresivas bajo una carga constante a lo largo del tiempo, se puede dar en materiales metálicos, poliméricos y cerámicos cuando estos se encuentran bajo tensión a altas temperaturas. 

La fluencia se refiere al momento en el cual un material empieza a deformarse de forma plástica bajo una carga constante. 

***Límite de fluencia***: Punto específico en el que un material empieza a deformarse de forma permanente. 

En el caso de la fluencia, se puede utilizar el **criterio de Tresca** el cuál es una teoría de falla estática utilizada para ==predecir la fluencia o fractura de materiales dúctiles==, este se encuentra descrito por la siguiente formula: 
$$
\begin{flalign}
\tau_{max} &= \frac{\sigma_{max} - \sigma_{min}}{2} \geq \tau_{fluencia}\\
\text{Donde:}\\
\sigma_{max} &= \text{Esfuerzo principal mayor}\\
\sigma_{min} &= \text{Esfuerzo principal menor}\\
\tau_{fluencia} &= \text{Esfuerzo contante critico}
\end{flalign}
$$

El **Criterio de Von Mises** es un valor que se utiliza para determinar si un material dado cederá o se fracturará; normalmente se utiliza para materiales dúctiles como los metales, el criterio establece que si la ==tensión de Von Mises== de un material sometido a una carga es igual o ==mayor que el límite de la fluencia del mismo bajo tensión simple, el material cederá==, este se puede ver con la siguiente formula. 
$$
\sqrt{\frac{(\tau_z - \tau_t)^2+ (\tau_t -\tau_r)^2 + (\tau_r - \tau_z)^2}{2}} = \tau_v
$$

# Teoría Clásica de Plasticidad (TCP)

La TCP se centra en como se deforman los materiales de forma permanente, esta es la base para poder comprender como un material responde a fuerzas externas, las cuales las llevan a deformarse de manera irreversible bajo ciertas condiciones; esta se centra en poder desarrollar modelos matemáticos que puedan predecir la distribución de tensiones y deformaciones en cuerpos deformados permanentemente por algún medio. 

Características de plasticidad: Capacidad de los materiales para deformarse de forma permanente. 

- Deformación irreversible: Cuando el material entra al rango plástico y su forma cambia de forma permanente. 
- Límite elástico: El punto en el cual el material puede seguirse deformando de forma elástica. 
- Tiempo de fluencia: Velocidad a la que un material continúa deformándose bajo una carga constante. 
Hay muchos procesos que pueden utilizar estas propiedades de los materiales para poder realizar procesos de conformado, estos pueden ir desde el prensado de metales para poder obtener canaletas o formas similares hasta el extruido de metales donde el material es forzado a pasar por una abertura que le da la forma final al metal. 

## Aplicación del Modelado a los Procesos de Conformado Mecánico 

*Conformado Mecánico*: Procedimientos de obtención de piezas que se lleva a cabo a través de las deformaciones plásticas de los materiales, esto se logra gracias a la aplicación de fuerzas suficientemente grandes para poder lograr la deformación del material. 

Estos procesos se clasifican como **procesos de conformado sin eliminación de material**, esto debido a que durante su ejecución se pierde una cantidad ínfima (o directamente no se pierde) de material. 

Todo material que es sometido a fuerzas externas presenta diferentes esfuerzos y tensiones, las tensiones se pueden clasificar de la siguiente forma: 
- Tensiones normales: normalmente denotadas con la letra $\sigma$, producirán compresión o tracción axial, es decir están de forma perpendicular a las superficies donde se aplican. 
- Tensiones de Cizalladura: Tensiones denotadas por $\tau$ que tenderán a deslizar una sección plana sobre otra paralela, estas fuerzas son paralelas a la superficie a la que se aplica. 
Cuando estas tensiones superan un cierto valor, se produce una rotura la cual puede ser por cizallamiento o simplemente un despegue. 

## Deformación en Frío y en Caliente

Dependiendo de la temperatura a la cual se aplique la deformación del material, esta puede ser clasificada como en caliente o en frío. 

**Conformado en frío**: Este tipo de deformación se realiza a temperaturas inferiores a la de recristalización presente en el metal, a pesar de que se realiza a bajas temperaturas, esto no quiere decir que no se pueda utilizar energía térmica, se puede utilizar calor siempre y cuando este no provoque cambios en la estructura cristalina. En el caso de este tipo de conformado se puede ver que entre mayor sea la deformación producida mayor será la fuerza necesaria para poder continuar deformando el material, esto es *endurecimiento por deformación* y es utilizado para poder aumentar la resistencia de los materiales. El conformado en frío produce deformaciones en las piezas mecanizadas, lo que genera que sea complicado obtener piezas con tolerancias estrechas, genera esfuerzos superficiales de tracción que favorecen a la corrosión aumenta la dureza y la fragilidad. 

**Conformado en Caliente**: Proceso de deformación que se realiza a temperaturas superiores a las de recristalización, permitiendo de esta forma facilitar la deformación del metal. 

Los procesos de conformación en metales normalmente se clasifican en dos tipos principales: 

- Conformación Masiva:
	- Forja: Proceso de conformación plástica por el cual al metal se le someten fuerzas a veces de forma intermitente o de forma continua para poder obtener piezas determinadas
		- Este proceso permite eliminar las cavidades internas del meta. 
		- Permite afinar el grano debido a las deformaciones producidas en la pieza. 
		- Los principales materiales forjables son el aluminio, cobre, hierro, titanio y zinc. 
		- Sus principales fases son: calentamiento, deformación y enfriamiento 
		- Existen diversos tipos: 
			- Forja libre: El material solo se comprime, no se le intenta dar forma precisa, esta normalmente no es aplicable a producción a gran escala. 
			- Forja con estampa semicerrada: El material se comprime y se le da una forma, la cual es precisa pero da margen a que se formen rebabas. 
			- Forja con estampa cerrada: El material se deforma en una matriz que solo permite que adquiera una forma y no permite la formación de rebabas. 
			- Forja por recalado: Forjado que consiste en comprimir una pieza de metal para poder generar un alargamiento de su sección transversal en una zona específica
			- Forja en frío: Proceso en el cual se obtienen grandes cantidades de producción, solo requieren fuerza y un molde (opcional). 
- Conformación de Chapa Metálica:

En el caso de la forja se tiene que considerar que las relaciones presentes entre el alargamiento y ensanchamiento no pueden ser determinadas de forma analítica, por lo que se tiene que utilizar la relación de mordedura que se obtiene por la siguiente formula: 

$$
\begin{flalign}

\text{Relacion de mordedura} &= \frac{b}{W_0} \\
\text{Donde:}\\
W_0 &= \text{Ancho inicial de la pieza}\\
b &= \text{Longitud que va a ser deformada}\\
\end{flalign}
$$

Tanto el alargamiento como la extensión pueden ser definidos de la siguiente manera: 

$$
\begin{flalign*}
S &= \frac{\text{aumento del espesor}}{\text{disminicion del espesor}}\\
\text{Para: } 0.5 \leq m \leq 2\\
 S &= 0.183 + 0.3025m - 0.041m^2\\
 \text{Para: } m \geq 2 \quad m\leq 0.5\\
 S &= \frac{m}{1 + 1.065 m }\\
\text{donde:}\\
S&= 1 \rightarrow \text{Solo ensanchamiento}\\
S&= 0 \rightarrow \text{Solo alargamiento}
\end{flalign*}
$$


# Extrusión 

Se utiliza para poder dar forma a materiales, normalmente metales o polímeros, forzándolos a pasar por una matriz con una determinada forma; esto se logra a través de empujar el material, obteniendo así piezas continuas con la forma deseada. El principal problema que tiene este proceso es la lubricación, esto debido a las altas fricciones que se generan entre el material y la matriz. Este proceso puede ser realizado tanto en caliente como en frío, donde haciendo uso de un embolo o punzón se presiona el material obligándolo a fluir por compresión a través de la matriz dándole forma a la pieza; normalmente es más utilizada la extrusión en caliente debido a que permite eliminar los efectos del trabajo en frío. 

Ventajas: 
- Puede extruir una gran variedad de formas
- La estructura del grano y las propiedades de resistencia mejoran 
- Casi no generan desperdicio 
Desventajas 
- Tiene limitaciones geométricas 
- Tiene altos costos iniciales en cuestiones de herramientas y equipo 
- Requiere de una alta fuerza y energía para su funcionamiento 
Los principales metales que se pueden extruir en frío son el zinc, cobre, latón y las aleaciones de los mismos, mientras que los principales que se suelen extruir en caliente son el plomo, cobre aluminio y sus aleaciones y aceros con un contenido de carbono inferior al 1.5%. 

Las principales características que presentan estos materiales son: 
- Las piezas obtenidas pueden ser huecas o solidas pero siempre con superficies laterales paralelas 
- La longitud de la pieza no debe de ser más de 15 veces el diámetro de la pieza original. 

Tipos de extrusión: 
- Directa: El material se coloca en una matriz y por la acción del embolo se fuerza a salir por una matriz en el mismo sentido que la fuerza aplicada. 
- Inversa: El contenedor se encuentra cerrado en un extremo y, gracias a un embolo hueco, se permite el paso del metal a través de la matriz en el sentido opuesto al que la fuerza aplicada 
- Por impacto: Proceso de extrusión a gran velocidad y normalmente se utiliza para poder producir tubos de paredes finas. 
- Extrusión hidrostática: Extrusión que se realiza a través de una interfaz líquida entre el material a extruir y el contenedor, permite reducir la fricción gracias al líquido presente. 
# Estirado y Trefilado 

Trefilado: 

Proceso de conformación que se realiza a través de fuerzas de tracción que producen el alargamiento del material, estas se logran a través de orificios calibrados que reducen de forma progresiva la sección transversal.  Este se hace en frío lo que permite obtener los siguientes beneficios: 
- Mayor dureza del material procesado 
- Aumento significativo de la resistencia mecánica 
- Mejor acabado superficial y calidad 
- Reducción de tolerancias dimensionales 
- Eliminación de defectos superficiales

El principal objetivo del trefilado es obtener grandes reducciones a través de múltiples pasadas, normalmente se utilizan redondos laminados de 5-8 mm, permite obtener alambre de hasta 0.0025 mm. 

Estirado: 

Su principal objetivo es reducir la sección transversal para poder conseguir formas y calibres específicos, normalmente se utilizan barras de 4-6 metros y más de 10 mm de diámetro, normalmente todo el proceso es realizado en un solo paso.

Sus principales aplicaciones son el estirado de tubos para poder reducir el diámetro y espesor de la pared, obtener perfiles y barras con reducciones de hasta el 50%, además de permitir obtener productos con tolerancias bajas y con acabados superficiales bastante buenos. 

Proceso general: 
1) Decapado: Elimina cualquier contaminante de la superficie 
2) Estirado/trefilado: Se alarga el material utilizando lubricantes 
3) Acabado final: Se realizan tratamientos para mejorar sus propiedades 

Ventajas del proceso general: 
- Reducción de hasta el 90% 
- Puedes obtener hasta 0.0225 mm de diámetro 
- Reducción típica de hasta el 50%

# Extrusión
Se utiliza para dar forma a los materiales principalmente metales y plásticos, fosándolos a través de una matriz con una sección transversal específica. El material es empujado a través de la matriz para poder darles forma en diferentes formas como tubos, perfiles, láminas o películas. 

Dependiendo de la forma que tenga la matriz se podrá obtener una forma en específico. Uno de los inconvenientes que tiene este proceso es que requiere un proceso de lubricación, debido a que en el mayor numero de casos se genera demasiada fricción a la hora de realizar el empuje del material. 

Este proceso puede ser realizado en caliente o en frío, haciendo uso de un pistón a través de una matriz para poder obtener la forma deseada; normalmente es más usada la extrusión en caliente debido a que elimina las tensiones residuales que son generadas por el trabajo en frío. 

En este proceso es conveniente considerar las presiones (radial y axial) para poder obtener un material que pueda ser conveniente para su uso industrial 

Ventajas: 

- Pueden obtenerse una gran variedad de formas especialmente con la extrusión en cliente
- Mejoran su resistencia 
- Casi no se produce residuo
Desventajas: 

- Se tiene un alto costo en las herramientas necesarias para poder realizar los procedimientos
- Se tienen limitaciones relacionados con la geometría de las piezas
- Se requiere demasiada fuerza y energía, lo que aumenta su costo y el deterioro de las piezas si no se tienen las condiciones correctas. 

Normalmente los materiales que se utilizan para poder realizar estos procesos son los siguientes: 

En frío: 
- Estaño
- zinc 
- cobre
- latones 
- aluminio y sus aleaciones 
En caliente: 
- plomo 
- zinc 
- aceros 
Las piezas tienen que ser simétricas, debido a que si no se hace con las mismas dimensiones se pueden dar deformaciones a la hora de realizar el procedimiento, sumado a esto la pieza no debe de ser más de 15 veces más pequeña que la pieza original. 

## Tipos de extrusión 

Extrusión directa: El material a conformar se coloca en una matriz y por la acción de un émbolo se hace pasar el material por una matriz. Esta requiere una gran cantidad de trabajo pero puedes obtener una gran cantidad de figuras (como en I o en U)

Extrusión inversa: El contenedor está cerrado en un extremo y el metal se extrusión a través de la presión que es ejercida por un pistón hueco por donde sale el material, este normalmente se utiliza para poder producir envases, es bastante costosa a comparación de las demás debido a que se tiene que tener un mayor procesado del material. 

Extrusión por impacto: Se le pega con una gran velocidad que permite obtener una forma hueca. 

Extrusión hidrostática: En este caso el tocho se coloca en una matriz y se rodea de líquido 

# Fusión y Colada

Se basa en fundir el metal, vaciarlo en un molde y dejarlo enfriar. El metal fundido fluye por gravedad, lo que le permite entrar en el molde, sus principales aplicaciones son la fabricación de lingotes y piezas con formas particulares. 

Ventajas: 
- Geometrías complejas alcanzables 
- No requiere operaciones subsecuentes 
- Tamaños muy grandes 
- Todos los metales se funden 
- Económico para geometrías complejas
Desventajas
- Produce piezas porosas 
- Tienen propiedades mecánicas limitadas 
- Tiende a tener defectos de solidificación 
- Limitado a temperaturas de hasta 1750°C

Para poder realizar este proceso se requiere un molde el cual puede ser de uno de estos tipos: 

1) desechable: Solo se puede usar una vez y después se desecha 
2) Semipermanente: Puede ser utilizado varias veces pero luego se desecha, tiene mucha precisión 
3) Permanente: Dura más de 1000 operaciones, normalmente en producción en serie

El modelo en el que se va a basar el molde debe de considerar lo siguiente: 
- debe ser sobredimensionado por la contracción del metal  
- Ángulos de salida de 0.5 a 2 °
- Canales de alimentación y mazarotas 
- Cavidades para corazones 
Los principales métodos para moldeo son : 
- Arena Verde: Arena con arcillas activadas por humedad
- Procesos de CO2 y resinas : Arena secada con aglomerantes, presenta mayor resistencia mecánica. 
- Moldeo en cascara: Arena con resinas fenólicas que polimerizan a altas temperaturas 

El sistema de vaciado de los moldes consiste de: 

- Bebedero de colada: Entrada principal del metal 
- Canal de alimentación conduce a la cavidad 
- Copa de vaciado: Minimiza la turbulencia del metal 
- Mazarota: Compensa la contracción durante la solidificación. 

La preparación de un molde se lleva de la siguiente forma: 
1) Preparación: Compactación de la arena para poder crear el molde 
2) Ensamble: Se voltea y ensambla la semicaja para posicionar el sistema de alimentación
3) Acabado: Se retiran clavijas, se colocan los corazones y se extrae el modelo 
4) Vaciado: Se cierra el molde y se asegura para agregar el metal. 

El molde debe de poder cumplir con las siguientes propiedades: 

- Fácilmente replicable 
- Debe de poder mantener la forma 
- Debe de poder soportar el calor 
- Debe permitir el paso de gases a través del mismo