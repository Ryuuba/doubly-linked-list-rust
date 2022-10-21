# Lista doblemente ligada

En este repositorio se almacena una biblioteca que contiene la implementación de una lista doblemente ligada realizada por los alumnos de Sistemas Distribuidos, grupo CG02C, de la UAM - Cuajimalpa.

Si bien este proyecto no tienen relación con el contenido de la UEA de Sistemas Distribuido, su realización es utilidad para alcanzar el objetivo de la materia porque el sistema distribuido que se realizará como proyecto final de la materia estará escrito en Rust. Siendo así, el objetivo de la realización de este trabajo es familiarizar a los alumnos con el lenguaje Rust mediante la implementación de una lista doblemente ligada.

## Funcionamiento de la lista

Los métodos de acceso a a lista doblemente ligada son los siguientes:

- size: devuelve el tamaño de la lista.
- empty: verifica si la lista está vacía, devolviendo verdadero de ser así.
- clear: elimina todos los nodos de la lista.
- insert: inserta un nodo en la posición indicada por el usuario, regresa un iterador al nodo insertado.
- erase: elimina el nodo de la posición indicada por el usuario, regresa un iterador nodo que sigue después del eliminado.
- push_back: inserta un nodo al final de la lista.
- pop_back: elimina el nodo del final de la lista, regresa el objeto eliminado.
- push_front: inserta un nodo al inicio de la lista.
- pop_front: elimina un nodo al inicio de la lista, regresa el objeto eliminado.
- find: encuentra un objeto en la lista, regresa un iterador al elemento buscado si este se encuentra.

