## Objetivos del curso
- Comprender qué es la inteligencia artificial (IA) y sus principales definiciones.
- Conocer los campos de aplicación de la IA.
- Aplicar los conceptos base de la inteligencia artificial:
    - Agentes y sus habilidades para: 
    * Representación de conocimiento
    * Razonamiento computacional
    * Aprendizaje automático
    * Resolución de problemas
    * Procesamiento del lenguaje natural.

## ¿Qué es inteligencia?
- Inteligencia: Capacidad de adquirir y usar conocimiento.

La Inteligencia Artificial es dar a las máquinas la capacidad de
- Almacenar el conocimiento y usarlo para razonar
- Buscar soluciones
- Aprender individual y colectivamente
- Comunicarse y percibir imitando a los humanos


# Unidad 1: Agentes

## 1. Introducción a la IA

La inteligencia artificial (IA) es un campo de estudio dentro de las ciencias de la computación que busca crear sistemas capaces de realizar tareas que normalmente requieren inteligencia humana. Estas tareas incluyen razonamiento, aprendizaje, percepción y toma de decisiones.

Nos llamamos a nosotros mismos Homo Sapiens "El hombre Sabio". Porque nuestra inteligencia es muy importante para nosotros.

Hemos tratado de entender cómo pensamos y actuamos, es decir, cómo nuestro cerebro puede percibir, comprender, predecir y manipular un mundo mucho más grande y complicado que él mismo.

A partír de lo anterior, el ser humano a llegado al campo de la inteligencia artificial. Donde se busca construir entidades inteligentes: Máquinas que puedan calcular cómo actuar de manera efectiva en diversas situaciones.

“El impacto de la IA será mayor que cualquier cosa en la historia de la humanidad”. Kai-Fu Lee (Científico informático, Taiwanés, Con gran trayectora en el mundo de la IA)

### ¿Qué es la IA?

#### La IA se puede definir desde varias perspectivas:

- Sistemas que piensan como humanos: El enfoque de modelo cognitivo
    Para afirmar que un programa piensa como un humano, es necesario comprender cómo piensan los humanos.
    - Introspección: Intentar capturar nuestros propios pensamientos mientras ocurren.
    - Experimentos psicológicos: Observar a una persona en acción para analizar su comportamiento y procesos mentales.
    - Imágenes cerebrales: Observar el cerebro en funcionamiento mediante tecnologías como la resonancia magnética funcional (fMRI) o electroencefalografía (EEG), para correlacionar las actividades mentales con patrones de actividad cerebral.
    
    El enfoque del modelado cognitivo busca desarrollar **programas que no solo produzcan resultados correctos, sino que también lo hagan de manera similar al pensamiento humano**. Esto implica replicar los procesos mentales humanos en sistemas computacionales, utilizando modelos basados en teorías psicológicas y neurológicas. Si el comportamiento de entrada-salida del programa coincide con el comportamiento humano correspondiente, esto es evidencia de que algunos de los mecanismos del programa también podrían estar operando en los humanos.

- Sistemas que actuan como humanos: El enfoque del test de Turing (1950)
    - Imitar procesos cognitivos, como el razonamiento y la toma de decisiones.
    - Ejemplo: Redes neuronales que simulan el cerebro humano. 
    
        Este enfoque fue concebido como un experimento mental para responder a la pregunta: "**¿Puede una máquina pensar?**".
        El test se enfoca en que un interrogador humano, tras realizar preguntas escritas, no puede distinguir si las respuestas provienen de una persona o de una máquina.
        La máquina necesitaría desarrollar las siguientes capacidades:
        * Procesamiento del lenguaje natural: Para comunicarse eficazmente en un idioma humano.
        * Representación del conocimiento: Para almacenar la información que conoce o escucha.
        * Razonamiento automatizado: Para responder preguntas y llegar a nuevas conclusiones.
        * Aprendizaje automático: Para adaptarse a nuevas circunstancias y detectar y extrapolar patrones. 

        Se llegó a que el propósito principal de la IA no es simplemente replicar el comportamiento humano, sino comprender y construir sistemas inteligentes basados en principios fundamentales, que puedan ser aplicados de maneras únicas y efectivas, incluso si estas no imitan directamente las capacidades humanas.


- Sistemas que piensan racionalmente: El enfoque de las “leyes del pensamiento”
    - Aplican principios de lógica para razonar.
    - Ejemplo: Algoritmos que optimizan rutas o decisiones financieras.
    
    El filósofo griego Aristóteles fue uno de los primeros en intentar codificar el “pensamiento correcto”, es decir, los procesos de razonamiento irrefutables. Busca proporcionar patrones para estructuras argumentativas que siempre produzcan conclusiones correctas cuando se parte de premisas correctas. El ejemplo clásico comienza con Sócrates es un hombre y todos los hombres son mortales, concluyendo que Sócrates es mortal. 
    
    Se suponía que estas leyes del pensamiento debían gobernar el funcionamiento de la mente; su estudio dio origen al campo llamado lógica.

    La lógica, tal como se entiende convencionalmente, requiere un conocimiento del mundo que sea certero, una condición que, en la realidad, rara vez se logra. Simplemente no conocemos las reglas de, por ejemplo, la política o la guerra, de la misma manera en que conocemos las reglas del ajedrez o la aritmética. La teoría de la probabilidad llena este vacío, permitiendo un razonamiento riguroso con información incierta.


- Sistemas que actúan racionalmente: El enfoque del agente racional
    - Maximizan las probabilidades de éxito al tomar decisiones.
    
    Un agente es simplemente algo que actúa. Por supuesto, todos los programas de computadora hacen algo, pero se espera que los agentes computacionales hagan más: operen de manera autónoma, perciban su entorno, persistan durante un período prolongado, se adapten a los cambios y creen y persigan metas. Un agente racional es aquel que actúa para lograr el mejor resultado o, cuando hay incertidumbre, el mejor resultado esperado.

    En el enfoque de las “leyes del pensamiento” de la inteligencia artificial, el énfasis estaba en las inferencias correctas. Hacer inferencias correctas es, a veces, parte de ser un agente racional, ya que una forma de actuar racionalmente es deducir que una acción determinada es la mejor y luego actuar en consecuencia. Por otro lado, hay formas de actuar racionalmente que no implican inferencias. Por ejemplo, retroceder de inmediato al tocar una estufa caliente es una acción refleja que suele ser más exitosa que una acción más lenta tomada después de una deliberación cuidadosa.
    
    Todas las habilidades necesarias para superar el Test de Turing también permiten que un agente actúe racionalmente. La representación del conocimiento y el razonamiento permiten a los agentes tomar buenas decisiones. Necesitamos generar frases comprensibles en lenguaje natural para desenvolvernos en una sociedad compleja. Necesitamos aprendizaje, no solo para adquirir conocimientos, sino también porque mejora nuestra capacidad de generar comportamientos efectivos, especialmente en circunstancias nuevas.

    El enfoque del agente racional en la inteligencia artificial tiene dos ventajas sobre otros enfoques. Primero, es más general que el enfoque de las “leyes del pensamiento”, porque la inferencia correcta es solo uno de varios mecanismos posibles para lograr la racionalidad. Segundo, es más adecuado para el desarrollo científico. El estándar de racionalidad está matemáticamente bien definido y es completamente general. A menudo, podemos trabajar desde esta especificación para diseñar agentes que demuestren alcanzar dicha racionalidad, algo que es en gran medida imposible si el objetivo es imitar el comportamiento humano o los procesos de pensamiento.

    Por estas razones, el enfoque del agente racional ha prevalecido durante la mayor parte de la historia del campo de la inteligencia artificial. En las primeras décadas, los agentes racionales se construyeron sobre bases lógicas y formaron planes definidos para lograr objetivos específicos. Más tarde, los métodos basados en la teoría de la probabilidad y el aprendizaje automático permitieron la creación de agentes que podían tomar decisiones bajo incertidumbre para alcanzar el mejor resultado esperado. En resumen, la inteligencia artificial se ha centrado en el estudio y la construcción de agentes que hacen lo correcto. Lo que cuenta como "lo correcto" está definido por el objetivo que proporcionamos al agente. Este paradigma general es tan generalizado que podríamos llamarlo el modelo estándar. Prevalece no solo en la inteligencia artificial, sino también en la teoría de control, donde un controlador minimiza una función de costo; en la investigación operativa, donde una política maximiza una suma de recompensas; en la estadística, donde una regla de decisión minimiza una función de pérdida; y en la economía, donde un tomador de decisiones maximiza la utilidad o alguna medida de bienestar social.
    

#### Principales Características de la IA
- Percepción: Capacidad de captar información del entorno a través de sensores o datos.
- Razonamiento: Procesar información para tomar decisiones lógicas.
- Aprendizaje: Adaptarse y mejorar su rendimiento con experiencia.
- Actuación: Realizar acciones basadas en los datos y el razonamiento.

#### Ejemplos de IA en la Vida Diaria
- Aplicaciones móviles de traducción automática.
- Sistemas de recomendación en plataformas como Netflix y Amazon.
- Vehículos autónomos que navegan de forma segura.


#### Reflexiones para la Clase
¿Qué ejemplos de IA conoces y cómo crees que funcionan?



### La Historia de la Inteligencia Artificial

Hitos en la historia de la inteligencia artificial (ganadores del Premio Turing): 
- Marvin Minsky (1969) y John McCarthy (1971) por definir los fundamentos del campo basados en la representación y el razonamiento.
- Ed Feigenbaum y Raj Reddy (1994) por desarrollar sistemas expertos que codifican el conocimiento humano para resolver problemas del mundo real.
- Judea Pearl (2011) por desarrollar técnicas de razonamiento probabilístico que abordan la incertidumbre de manera rigurosa.
- Yoshua Bengio, Geoffrey Hinton y Yann LeCun (2019) por hacer del “aprendizaje profundo” (redes neuronales multicapa) una parte fundamental de la informática moderna.


***Nota: Puede ser una actividad de lectura corta y socialización***


***Nota: Machine learning is a subfield of AI that studies the ability to improve performance based on experience.***


## 2. Definiciones y tipos de agentes

### Agentes Inteligentes
Definición: Un agente es una entidad que percibe su entorno y actúa sobre él para alcanzar objetivos.

- Un agente es cualquier cosa que pueda considerarse como capaz de percibir su entorno a través de sensores y actuar sobre ese entorno mediante actuadores. 

- Un agente humano tiene ojos, oídos y otros órganos como sensores, y manos, piernas, tracto vocal, etc., como actuadores. Un agente robótico podría tener cámaras y detectores de rango infrarrojo como sensores, y varios motores como actuadores. 

- El entorno podría ser cualquier cosa ¡el universo entero! En la práctica, se trata solo de esa parte del universo cuyo estado nos importa al diseñar este agente, la parte que afecta lo que el agente percibe y que es afectada por las acciones del agente.


- Usamos el término percepto para referirnos al contenido que los sensores de un agente están percibiendo. La secuencia de perceptos de un agente es el historial completo de todo lo que el agente ha percibido hasta el momento. En general, la elección de acción de un agente en un instante dado puede depender de su conocimiento incorporado y de toda la secuencia de perceptos observada hasta ese momento, pero no de nada que no haya percibido. 




### Buen comportamiento: El concepto de racionalidad
Un agente racional es aquel que hace lo correcto. Obviamente, hacer lo correcto es mejor que hacer lo incorrecto, pero ¿qué significa hacer lo correcto?

#### Medidas de desempeño
La filosofía moral ha desarrollado varias nociones diferentes de lo que significa "hacer lo correcto", pero la inteligencia artificial generalmente se ha adherido a una noción llamada consecuencialismo: evaluamos el comportamiento de un agente según sus consecuencias. Cuando un agente es colocado en un entorno, genera una secuencia de acciones según los perceptos que recibe. Esta secuencia de acciones hace que el entorno pase por una secuencia de estados. Si la secuencia es deseable, entonces el agente ha tenido un buen desempeño. 

#### Racionalidad
Lo que es racional en un momento dado depende de cuatro cosas:

- La medida de desempeño que define el criterio de éxito.
- El conocimiento previo del agente sobre el entorno.
- Las acciones que el agente puede realizar.
- La secuencia de perceptos del agente hasta el momento.

#### La naturaleza de los entornos
Los entornos de tarea, son esencialmente los “problemas” para los cuales los agentes racionales son las “soluciones”. 


#### Propiedades de los entornos.
La gama de entornos de tarea que pueden surgir en inteligencia artificial es, obviamente, muy amplia. Sin embargo, podemos identificar un número relativamente pequeño de dimensiones según las cuales los entornos de tarea pueden categorizarse. Estas dimensiones determinan, en gran medida, el diseño adecuado del agente y la aplicabilidad de cada una de las principales familias de técnicas para la implementación de agentes. 

1. TOTALMENTE OBSERVABLE VS. PARCIALMENTE OBSERVABLE
Si los sensores de un agente le dan acceso al estado completo del entorno en cada momento, decimos que el entorno de tarea es totalmente observable. Un entorno de tarea es efectivamente totalmente observable si los sensores detectan todos los aspectos relevantes para la elección de una acción; la relevancia, a su vez, depende de la medida de desempeño. Los entornos totalmente observables son convenientes porque el agente no necesita mantener ningún estado interno para hacer un seguimiento del mundo.

Un entorno puede ser parcialmente observable debido a sensores ruidosos o inexactos, o porque partes del estado simplemente están ausentes de los datos del sensor. Por ejemplo, un agente aspirador con solo un sensor local de suciedad no puede saber si hay suciedad en otros cuadrados, y un taxi automatizado no puede ver lo que otros conductores están pensando. Si el agente no tiene sensores en absoluto, entonces el entorno es no observable. Podría pensarse que en tales casos la situación del agente es desesperada, pero, como discutimos en el Capítulo 4, los objetivos del agente aún pueden ser alcanzables, a veces con certeza.

2. UN SOLO AGENTE VS. MULTIAGENTE
La distinción entre entornos de un solo agente y multiagente puede parecer lo suficientemente simple. Por ejemplo, un agente que resuelve un crucigrama por sí solo está claramente en un entorno de un solo agente, mientras que un agente que juega ajedrez está en un entorno de dos agentes. Sin embargo, hay algunos aspectos sutiles. Primero, hemos descrito cómo una entidad puede ser vista como un agente, pero no hemos explicado qué entidades deben ser vistas como agentes.

3. Determinista vs. No determinista
Si el siguiente estado del entorno está completamente determinado por el estado actual y la acción ejecutada por el agente, entonces decimos que el entorno es determinista; de lo contrario, es no determinista. 

4. EPISÓDICO VS. SECUENCIAL
En un entorno de tarea episódico, la experiencia del agente se divide en episodios atómicos. En cada episodio, el agente recibe un percepto y luego realiza una única acción. Lo crucial es que el siguiente episodio no depende de las acciones realizadas en episodios anteriores. Muchas tareas de clasificación son episódicas. Por ejemplo, **un agente que debe detectar piezas defectuosas en una línea de ensamblaje toma cada decisión basándose en la pieza actual, independientemente de las decisiones anteriores; además, la decisión actual no afecta si la próxima pieza será defectuosa.**

Por otro lado, en los entornos secuenciales, la decisión actual podría afectar todas las decisiones futuras. El ajedrez y la conducción de un taxi son ejemplos de entornos secuenciales: en ambos casos, las acciones a corto plazo pueden tener consecuencias a largo plazo. Los entornos episódicos son mucho más simples que los entornos secuenciales porque el agente no necesita pensar hacia adelante.

5. ESTÁTICO VS. DINÁMICO
Si el entorno puede cambiar mientras un agente está deliberando, entonces decimos que el entorno es dinámico para ese agente; de lo contrario, es estático. Los entornos estáticos son fáciles de manejar porque el agente no necesita seguir observando el mundo mientras decide una acción, ni preocuparse por el paso del tiempo.

Por otro lado, los entornos dinámicos están constantemente preguntando al agente qué quiere hacer; si aún no ha decidido, eso cuenta como decidir no hacer nada. 

6. DISCRETO VS. CONTINUO
La distinción entre discreto y continuo se aplica al estado del entorno, a la forma en que se maneja el tiempo y a los perceptos y acciones del agente. Por ejemplo, el entorno del ajedrez tiene un número finito de estados distintos (excluyendo el reloj). El ajedrez también tiene un conjunto discreto de perceptos y acciones.

Conducir un taxi es un problema de estado continuo y tiempo continuo: la velocidad y la ubicación del taxi y de otros vehículos pasan por un rango de valores continuos y lo hacen de manera suave a lo largo del tiempo. Las acciones al conducir un taxi también son continuas (ángulos de dirección, etc.). La entrada de cámaras digitales es discreta, estrictamente hablando, pero típicamente se trata como una representación de intensidades y ubicaciones que varían de forma continua.

#### Agentes reflexivos basados en modelos
La manera más efectiva de manejar la observabilidad parcial es que el agente realice un seguimiento de la parte del mundo que no puede ver en ese momento. Es decir, el agente debería mantener algún tipo de estado interno que dependa del historial de perceptos y que refleje, al menos, algunos de los aspectos no observados del estado actual.


- Sensores: Los sensores del agente perciben el entorno actual y recopilan información sobre "cómo es el mundo ahora".

- Estado: El agente mantiene un estado interno que representa lo que sabe sobre el entorno, incluyendo información que no puede observar directamente en el momento actual.
Este estado se actualiza en función de dos factores:

    - Cómo evoluciona el mundo: Basado en un modelo del entorno que describe cómo cambian las condiciones del mundo.
    - Qué hacen mis acciones: Un modelo del efecto que tienen las acciones del agente en el entorno.
    - Reglas de condición-acción: El agente utiliza estas reglas para decidir qué acción realizar basándose en el estado actual y en las percepciones del entorno.

- Acciones: El agente selecciona una acción con base en las reglas y su estado interno, y la ejecuta a través de los actuadores para interactuar con el entorno.
Entorno: El entorno se modifica según las acciones del agente y la evolución natural de las condiciones externas.

#### Agentes basados en objetivos
Conocer algo sobre el estado actual del entorno no siempre es suficiente para decidir qué hacer. Por ejemplo, en una intersección vial, el taxi puede girar a la izquierda, girar a la derecha o continuar recto. La decisión correcta depende de a dónde el taxi intenta llegar. En otras palabras, además de una descripción del estado actual, el agente necesita algún tipo de información sobre el objetivo que describa las situaciones deseables, por ejemplo, estar en un destino particular.

El programa del agente puede combinar esta información con el modelo (la misma información utilizada en el agente reflexivo basado en modelos) para elegir acciones que logren el objetivo. La Figura 2.13 muestra la estructura de un agente basado en objetivos.

- Sensores: Reciben información del entorno para determinar "cómo es el mundo ahora".

- Estado interno: El agente mantiene un estado interno que refleja el conocimiento del mundo, incluyendo información no observada directamente. Este estado se actualiza en función de:
    - Cómo evoluciona el mundo: Un modelo que describe cómo cambian las condiciones del entorno.
    - Qué hacen mis acciones: Un modelo que predice el impacto de las acciones del agente en el estado del mundo.

- Evaluación de acciones: El agente utiliza su modelo para prever "cómo será el mundo si realizo la acción A". Esto le permite considerar las consecuencias futuras de sus acciones.

- Objetivos: El agente mantiene un conjunto de objetivos que definen las situaciones deseables que debe alcanzar. Esta información se combina con las predicciones del modelo para seleccionar la acción más apropiada que lo acerque a cumplir esos objetivos.

- Acciones: Una vez que decide cuál es la mejor acción para avanzar hacia sus objetivos, la ejecuta mediante los actuadores.
Entorno: 
    - El entorno reacciona a las acciones del agente, proporcionando nuevas percepciones que actualizan el estado interno.

#### Agentes basados en utilidad
Los objetivos por sí solos no son suficientes para generar un comportamiento de alta calidad en la mayoría de los entornos. Por ejemplo, muchas secuencias de acciones pueden llevar al taxi a su destino (cumpliendo así el objetivo), pero algunas son más rápidas, seguras, fiables o económicas que otras.

Los objetivos solo proporcionan una distinción binaria y burda entre estados “felices” y “desafortunados”. Una medida de desempeño más general debería permitir la comparación de diferentes estados del mundo en función de cuán felices harían al agente. Dado que “feliz” no suena muy científico, los economistas y los científicos informáticos utilizan el término utilidad en su lugar.

- Sensores: Reciben información del entorno para determinar "cómo es el mundo ahora".

- Estado interno: El agente mantiene un estado interno que se actualiza constantemente y refleja el conocimiento del mundo. Este estado se basa en:
    - Cómo evoluciona el mundo: Un modelo que describe cómo cambian las condiciones del entorno.
    - Qué hacen mis acciones: Un modelo que predice el impacto de las acciones del agente en el entorno.

- Evaluación de acciones futuras: El agente utiliza su modelo para prever "cómo será el mundo si realizo la acción A". Esto le permite anticipar los resultados de diferentes acciones.

- Cálculo de utilidad: El agente evalúa "qué tan feliz estaría en ese estado" usando una función de utilidad que mide sus preferencias entre diferentes estados posibles del mundo. La utilidad se calcula para cada estado futuro probable, considerando tanto los beneficios como las probabilidades de los resultados.

- Selección de acción: Basándose en la utilidad esperada (calculada como el promedio ponderado de las utilidades de todos los posibles estados futuros, según sus probabilidades), el agente elige la acción que maximiza esta utilidad.

- Actuadores: La acción seleccionada se ejecuta en el entorno mediante los actuadores del agente.

- Entorno: El entorno responde a las acciones del agente, generando nuevas percepciones que actualizan su estado interno.

#### Agentes de aprendizaje
Hemos descrito programas de agentes con varios métodos para seleccionar acciones. Hasta ahora, no hemos explicado cómo se crean estos programas de agentes. En su famoso artículo temprano, Turing (1950) considera la idea de programar sus máquinas inteligentes a mano. Calcula cuánto trabajo podría tomar esto y concluye: “Parece deseable un método más expedito”.

El método que propone es construir máquinas de aprendizaje y luego enseñarles. En muchas áreas de la inteligencia artificial, este es ahora el método preferido para crear sistemas de última generación. Cualquier tipo de agente (basado en modelos, basado en objetivos, basado en utilidad, etc.) puede construirse como un agente de aprendizaje (o no).

- Componentes de un agente de aprendizaje

- Estándar de desempeño (Performance Standard): Define qué se espera del agente, es decir, los criterios que determinan si su desempeño es satisfactorio.

- Crítico (Critic): Evalúa las acciones del agente comparando su desempeño actual con el estándar definido. Proporciona retroalimentación (feedback) sobre el desempeño para informar al agente si sus acciones son adecuadas o necesitan mejoras.

- Elemento de aprendizaje (Learning Element): Recibe la retroalimentación del crítico y utiliza esta información para ajustar o mejorar el conocimiento y comportamiento del agente. Modifica el elemento de desempeño para optimizar sus capacidades futuras.

- Elemento de desempeño (Performance Element): Es el componente responsable de seleccionar y ejecutar las acciones basándose en el conocimiento actual. Representa lo que tradicionalmente se consideraba el programa completo del agente. Este elemento recibe datos de los sensores y actúa sobre el entorno mediante los actuadores.

- Generador de problemas (Problem Generator): Su función es proponer nuevas experiencias o desafíos al agente para fomentar el aprendizaje. Establece objetivos de aprendizaje adicionales y empuja al agente a explorar áreas que podrían mejorar su desempeño.

- Entorno (Environment): Es el sistema externo con el que interactúa el agente, proporcionando perceptos a través de los sensores y recibiendo las acciones ejecutadas mediante los actuadores.


### ¿Qué características tiene un agente inteligente?
- Lo que hace es apropiado para sus circunstancias y objetivos, teniendo en cuenta las consecuencias, a corto y largo plazo, de sus acciones.
- Es flexible para cambiar ambientes y objetivos.
- Aprende de la experiencia.
- Hace elecciones apropiadas de acuerdo a sus limitaciones perceptuales y computacionales.

“Un acoplamiento de percepción, razonamiento y actuación comprenden un agente. Un agente actua en un ambiente. El ambiente de un agente tambien puede incluir otros agentes. Un agente junto con su ambiente es llamado un mundo”.

“Los agentes intencionales tienen preferencias u objetivos. Ellos  prefieren algunos estados del mundo que otros estados, y actúan para tratar de alcanzar los estados que más prefieren. Los agentes 
no intencionales se agrupan y son llamados naturaleza”.


### Componentes:
- Percepción: Qué información recibe del entorno.
- Acción: Cómo responde a esa información.
- Objetivo: Lo que busca lograr.

### Tipos de agentes:
- Basados en reglas simples.
- Basados en búsqueda y planificación.
- Agentes que aprenden.


Agente: Sistema que percibe un entorno y actúa
Caracterizado por:
- Su estructura (arquitectura)
- Sus acciones (comportamiento)
- Arquitectura + programa


Sistemas multi-agente

- Interacción entre varios agentes
- Coordinación de interacciones

### Conceptos importantes
- TAREA: Se refiere a una actividad o problema específico que un agente debe resolver o ejecutar. La tarea define los objetivos que el agente debe alcanzar y puede implicar una serie de acciones que el agente debe llevar a cabo en su entorno para cumplir con esos objetivos.

- SOLUCIÓN DE TAREA:
    - Determinar que constituye una solución.
    - Representar la tarea de una forma que el computador pueda razonar sobre ella.
    - Usar el computador para calcular una salida que será presentada al usuario o una acción que debe ejecutar sobre el ambiente.
    - Interpretar la salida como una solución a la tarea.

- DOMINIO: campo dentro del cual un agente opera y para el cual está diseñado buscando la resolución de tareas. Este dominio incluye todos los elementos, reglas, hechos, y relaciones relevantes que el agente debe conocer y utilizar para llevar a cabo sus funciones de manera efectiva.

- CONOCIMIENTO: es la información sobre un dominio que puede ser usada para resolver tareas en ese
dominio. Ese conocimiento debe poderse representar en un computador.

- LENGUAJE DE REPRESENTACIÓN: Herramienta para la expresión del conocimiento que será usado por un
agente.

REPRESENTACIÓN DEL CONOCIMIENTO: la estructura particular de los datos usados para codificar el
conocimiento, de tal forma que pueda ser usado para razonar.

BASE DE CONOCIMIENTO: representación de todo el conocimiento que tiene almacenado un agente.

### Soluciones 

¿CUAL ES LA SOLUCIÓN?
Dada una descripción informal de una tarea, antes de considerar un computador, un diseñador de agentes debe determinar que constituiría una solución.

Una vez se consiga una buena especificación de la tarea, la siguiente cuestión es tener en cuenta si importa si la tarea esta incorrecta o incompleta.

- ÓPTIMA: La mejor de acuerdo a una medida de calidad.
- PROBABLE: Aunque no sea la solución definida, puede ser una solución.
- SATISFACTORIA: Suficientemente buena en el marco de acciones adecuadas.
- APROX. ÓPTIMA: Donde la medida de calidad es cercana a la solución óptima.

# Representaciones

Una vez que se tienen los requerimientos sobre la naturaleza de la solución, se debe representar la
tarea de tal forma que el computador la pueda resolver Las mentes de los computadores y las
personas son ejemplos de sistemas de símbolos físicos.

INTELIGENCIA
"La inteligencia puede ser representada mediante la manipulación de
símbolos." Newell & Herbert

Ejemplos de Símbolos Físicos
Palabras individuales como "gato", "casa", "feliz" que son analizadas y manipuladas en tareas
de comprensión y generación de lenguaje natural.
"El gato esta en la casa"


Ejemplo sencillo: el mundo del aspirador, que consiste en un agente robótico de limpieza en un mundo compuesto por cuadrados que pueden estar sucios o limpios. La Figura 2.2 muestra una configuración con solo dos cuadrados, A y B. El agente aspirador percibe en qué cuadrado se encuentra y si hay suciedad en ese cuadrado. El agente comienza en el cuadrado A. Las acciones disponibles son moverse a la derecha, moverse a la izquierda, aspirar la suciedad o no hacer nada.² Una función de agente muy simple es la siguiente: si el cuadrado actual está sucio, entonces aspira; de lo contrario, muévete al otro cuadrado. 