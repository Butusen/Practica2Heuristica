# Practica2Heuristica

1. ¿Qué variable representa la lista ABIERTA? openSet
2. ¿Qué variable representa la función g?gScore
3. ¿Qué variable representa la función f?fScore
4. ¿Qué método habría que modificar para que la heurística representara la distancia aérea entre vértices? Hay que utilizar el método heuristicCostEstimate que devuelve 1 que sería ideal, pero habría que cambiar el valor 1 que devuelve, por la distancia aérea.
5. ¿Realiza este método reevaluación de nudos cuando se encuentra una nueva ruta a un determinado vértice? Justifique la respuesta.
Sí, lo realiza en el if de la línea 84 en la que pregunta si no contiene vecinos que se añadan.
En otro caso que continue la búsqueda, con esto conseguimos que si encontramos un camino en el que la distancia sea menor que la rama principal, se modifique y, por tanto, se ponga como rama principal esa nueva con distancia menor.

