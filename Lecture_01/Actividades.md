
# Actividades

1. Identificando la IA en el día a día

Instrucciones:

En grupo, identificar 3 aplicaciones de IA que utilizan en su vida diaria.
Clasificar cada aplicación según las siguientes categorías:
- Piensa como humano
- Actúa como humano
- Piensa racionalmente
- Actúa racionalmente

Completar la tabla:

- Ejemplos:
    - Ejemplos por categoría de Inteligencia Artificial:
        1. Sistemas que piensan como humanos: Modelo cognitivo
        * Simuladores de procesos mentales.
        * Aplicación: Herramientas como Watson de IBM en investigación médica, que imitan el razonamiento humano para analizar síntomas y sugerir diagnósticos posibles.
        
        2. Sistemas que actúan como humanos: Test de Turing
        * Chatbots avanzados.
        * Aplicación: Asistentes virtuales como ChatGPT o Alexa que responden preguntas, realizan tareas y simulan conversaciones humanas.

        3. Sistemas que piensan racionalmente: Lógica y probabilidad
        * Algoritmos de optimización.
        * Aplicación: Algoritmos de planificación de rutas en Google Maps, que calculan el camino más eficiente basándose en datos de tráfico en tiempo real.
        4. Sistemas que actúan racionalmente: Agentes racionales
        * Vehículos autónomos.
        * Aplicación: Coches como los de Tesla, que toman decisiones racionales en tiempo real para evitar obstáculos y maximizar la seguridad en las carreteras.


2. Diseñando un agente basado en reglas

    Código Base: (Este se entrega a los estudiantes como punto de partida)
    ```py 
    def decidir_accion(entorno):
        if entorno == "amenaza":
            return "Defender"
        elif entorno == "recurso":
            return "Recolectar"
        else:
            return "Explorar"

    # Simulando entornos
    entornos = ["recurso", "amenaza", "desconocido"]
    for e in entornos:
        print(f"En el entorno '{e}', el agente decide: {decidir_accion(e)}")
    ```

- Tareas para los estudiantes:

    - Agregar nuevos entornos (por ejemplo, "aliado").
    - Modificar las decisiones del agente según las reglas dadas.
    - Probar el código y compartir los resultados.
    
    Preguntas de reflexión:

    - ¿Qué tan flexible es este agente?
    - ¿Cómo podrían hacerlo más sofisticado?


3. Crear un algoritmo sencillo en Python que permita identificar patrones básicos y entender el concepto de un agente simple basado en reglas.

- Actividad: Diseñar un agente que decida si debe cruzar una calle
El agente sigue las siguientes reglas: Si el semáforo está en verde y no hay autos en la intersección, cruza. Si el semáforo está en rojo o hay autos, no cruza.

    Pasos:
    1. Presentar el problema.
    2. Proporcionar un esqueleto del código para que los estudiantes lo completen:

    ```py
    def cruzar_calle(semaforo, hay_autos):
        if semaforo == "verde" and not hay_autos:
            return "Cruzar"
        else:
            return "No cruzar"

    # Ejemplo de uso:
    print(cruzar_calle("verde", False))  # Debe cruzar
    print(cruzar_calle("rojo", True))   # No debe cruzar
    ```


Propuesta creativa de uso de la IA

Instrucciones:

En grupos, piensen en un problema que podría resolverse con IA.
Completen el siguiente cuadro:

Problema	Descripción del problema
Ejemplo: Diagnóstico médico	La detección temprana de enfermedades requiere análisis rápidos.
Solución con IA	¿Qué tipo de IA usarían?	Ventajas	Limitaciones
Ejemplo: Análisis de imágenes médicas	Aprendizaje profundo para detectar anomalías en radiografías.	Diagnósticos rápidos y precisos.	Dependencia de datos médicos.

Presenten su caso al resto de la clase.





Impacto y Ética de la IA

Instrucciones:

Reflexionen en equipo sobre los siguientes temas:
Beneficios de la IA para la sociedad.
Riesgos y desafíos éticos de su implementac
Tema	Puntos clave
Beneficios	Ejemplo: Aumenta la eficiencia en procesos.
Riesgos o desafíos éticos	Ejemplo: Posible pérdida de empleos.

Compartir ideas con la clase.