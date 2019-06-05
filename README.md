# Lab6

#Problema 1
------
- Corrección de nombre de variables e inclusión de fflush en funcion set_struct.
- Se definen 2 punteros, un que recorrer struct y otro usado como temporal "ptr1" en la modificacion de dimensión de memoria.
- Se utilizan ciclos while para selección entre malloc en primera corrida y realloc en las siguientes.
- Cada función se seleccióna con un switch.

#Impresiones
- Se definió información sobre el tamaño de la memoria al inicio y al ir re ejecutando programa.
- Se imprimen los datos incluidos en el struct.
- Se utiliza un puntero temp para castear puntero global ptr y así imprimirlo.

#Opciones del programa
- Al inicio, se pide cantidad de elementos.
- Al finalizar primera corrida del programa se solicita si se desea redimensionar memoria o salir del programa.

#Gestión de fallos.
- Al redimensionar memoria con realloc se utiliza puntero temporal ptr1 para evitar cualquier fallos que provoque pérdida de información.
- Esto mediante estructura if que en caso de reasignación satisfactoria, pasar datos al puntero global para continuar.


#Problema 2
- Usé un nuevo puntero del mismo tipo que ptr, se modificó mediante malloc y calloc luego se comparó con ptr.
