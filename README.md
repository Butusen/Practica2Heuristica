# Practica2Heuristica

1. ¿Qué variable representa la lista ABIERTA? openSet
2. ¿Qué variable representa la función g?gScore
3. ¿Qué variable representa la función f?fScore
4. ¿Qué método habría que modificar para que la heurística representara la distancia aérea entre vértices? Hay que utilizar el método heuristicCostEstimate que devuelve 1 que sería ideal, pero habría que cambiar el valor 1 que devuelve, por la distancia aérea.
5. ¿Realiza este método reevaluación de nudos cuando se encuentra una nueva ruta a un determinado vértice? Justifique la respuesta.
En el caso en el que no esté expandido, se realizará una reevaluación de nudos, ya que habrá un nuevo neighbor con una ruta más corta como vemos que se realiza en el código de la siguiente imagen. En caso de que esté expandido, no realizará reevaluación, ya que sigue un único camino y no evalua los nuevos vecinos.
