Responder preguntas y marcar con el nombre de los integrantes

Integrantes: Juan Camilo Bonet 202022466 j.bonet@uniandes.edu.co Jesús Jiménez 202020431 j.jimenez21@uniandes.edu.co




OBSERVACIONES DEL LA PRACTICA
Estudiante 1 Juan Camilo Bonet Cod 202022466 
Estudiante 2 Jesús Jiménez Cod 202020431

Preguntas de análisis
1)	¿Qué relación encuentra entre el número de elementos en el árbol y la altura del árbol?
Entre más elementos, más alto el árbol, pero no es una relación proporcional. La relación es más o menos logarítmica. 

2)	¿Si tuviera que responder esa misma consulta y la información estuviera en tablas de hash y no en un BST, cree que el tiempo de respuesta sería mayor o menor? ¿Por qué?

Sería mayor. La ventaja de usar tablas ordenadas es que como su nombre lo indica, los elementos se encuentran ordenados dependiendo de la función de comparación, por lo que obtener valores en un rango será mucho más rápido que en una estructura de datos en el que los elementos no se encuentren ordenados. Como no está ordenada la tabla de hash, se necesita correr toda la tabla para encontrar todos los elementos en el rango, es decir, tiene un orden de crecimiento de O(n). El BST tiene un orden de crecimiento de O(log2N)

3)	¿Qué operación del TAD se utiliza para retornar una lista con la información encontrada en un rango de fechas?

La función valuesRange se encarga de obtener los elementos que se encuentran dentro del límite de fechas iniciales y finales indicadas por el usuario. Esta se basa en una función recursiva que repite el proceso hasta obtener todos los valores dentro del rango de fechas. Una vez finalizada, retorna una lista singlelinked con los elementos dentro del rango.
