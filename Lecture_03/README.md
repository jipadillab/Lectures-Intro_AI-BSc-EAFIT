# Problemas de busqueda

## Funciones Importantes

- Actions: Devuelve un conjunto finito de acciones que se pueden ejecutar en determinado estado.

```py
actions(s) = {'actions in the state s'}
```

- Result(Modelo de transición): Devuelve el nuevo estado que resulta de realizar la acción a en el estado  s.

```py
result(s, a) = s_
```

- Action cost: El costo numérico de aplicar la acción “a” en el estado  s para alcanzar el estado s_.

```py
action-cost(s, a, s_) = 'Valor númerico'
```

## Arboles de busqueda

Un árbol de búsqueda organiza los estados de un problema en una estructura jerárquica de nodos conectados por ramas.

### Componentes principales de un árbol de búsqueda:

- Nodos 🟢:  Representan los estados posibles del problema. Cada nodo contiene información como el estado actual, el costo acumulado y la acción que llevó a él. Un nodo puede tener uno o varios hijos, dependiendo de las acciones disponibles.

- Raíz 🌱: Es el nodo inicial del árbol, que representa el estado inicial del problema. Desde este nodo se generan los siguientes estados explorables.

- Ramas 🔗:  Representan las conexiones entre nodos, es decir, las acciones que permiten transitar de un estado a otro. Cada rama tiene un costo asociado en ciertos problemas, como la distancia en un mapa.

- Hojas 🍂: Son los nodos sin hijos, es decir, aquellos que no generan más estados.
En la búsqueda, pueden representar soluciones o estados donde no hay más movimientos posibles.

### Diferencia entre Estado y Nodo
- Estado 🏛️: Representa una configuración del problema en un momento dado.	En un laberinto, un estado es la posición actual del jugador.

- Nodo 🌳	Es una estructura dentro del árbol de búsqueda que representa un estado y almacena información adicional (como el costo, el padre y la acción que lo generó).	En el árbol de búsqueda, un nodo representa el estado y tiene una conexión con su nodo padre.

### Solving Performance

Estas cuatro propiedades (completitud, optimalidad de costo, complejidad de tiempo y complejidad espacial) son métricas clave para evaluar el rendimiento (solving performance) de un algoritmo de búsqueda en inteligencia artificial. 

