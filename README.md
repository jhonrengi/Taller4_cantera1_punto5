# Taller4_cantera1_punto5
En este taller hacemos usos de arreglos, con el fin de poder entender el funcionamiento de las matrices, específicamente las bidimensionales

Entendido esto, procedemos a realizar el siguiente taller:

![image](https://user-images.githubusercontent.com/122764419/213930410-3fd75e2a-8849-47e2-aa4d-567d5bea6d0a.png)

Lo primero que debemos que hacer, es observar la dimension que tiene la tabla, para lo cual es una 11x11(filas x columnas)

Dicho esto,definimos las varibales que usaremos para el diseño del programa.

En el apartado del proceso, lo llamare por el taller correspondiente y el punto de realizacion.

Declaro las varibales, matriz, filas y columnas, todas como enteros ya que ese es el tipo de dato que usaremos.

![image](https://user-images.githubusercontent.com/122764419/213930519-c1cbef9c-6726-42c8-ae80-ff75f70da512.png)

y dimensiono la matriz a lo que habiamos comentado anteriormente. (11x11).

como quiero que el usuario haga las consultas que desee, hago uso de un ciclo repetir, el cual dejara de funcionar hasta que la variable filas sea mayor a 11.

![image](https://user-images.githubusercontent.com/122764419/213930602-ec6d0142-3caa-4e49-8e84-4e47ab6f8242.png)

Realizado esto, procedemos a realizar la matriz con los datos que deben tener cada una de las posiciones, para no tener que asignar un valor a las 121 posiciones que tiene la matriz, hago uso de un ciclo para , el cual tiene la tarea de acumular un valor ascendete para la variable fila, que ira de la poscion 0 hasta 1, con paso de 1, que significa eso? que la varibale tendra el siguiente valor: 0,1,2,3,4,5,6...10. ahora, hago exactamente lo mismo con las comunas, para que tengan el mismo valor, de 0 a 1. y dentro de cada una de las posiciones, osea matriz[filas, columnas] le asignare el valor de la multiplicacion entre, el valor que tenga la fila con la columna.

![image](https://user-images.githubusercontent.com/122764419/213930799-a453d299-b14b-4eb0-9343-1ba263dda27b.png)

si ejecutamos el programa se vera de la siguiente forma:

![image](https://user-images.githubusercontent.com/122764419/213930848-ef7018bc-7b5d-45ac-bddd-06bfb8411197.png)

Aunque a tabla no se encuentre ordenada, cumple con los criterios de multiplicacion. y el valor es guardado en la matriz, para la seccion de filas y de columnas.

Ahora, tenemos que imprimir en pantalla la siguiente matriz.

![image](https://user-images.githubusercontent.com/122764419/213930935-bcb2eee8-e3a9-4f69-b6b3-6cd7d2ade506.png)

Para esto, hacemos el mismo procedimieneto que la matriz anterior, con la diferencia que ahora por cada posicion, no nos mostrara la multiplicacion entre las filas y la columnas, si no, el mensaje como tal de que ahi va la multiplicacion. por esto escribimos en pantalla: filas "x" columas; siendo x un string, y filas y columnas los valores correspondientes dentro del ciclo para.

![image](https://user-images.githubusercontent.com/122764419/213931026-4fde184b-b6f2-4527-b1e1-208e8de28dae.png)

Cabe aclarar que el condicional que asigno a ese clico unicamente tiene la labor de dimensionar la tabla y darle orden.

y por ultimo, simplemente le pedimos al usuario que digite el valor que desea ver dependiendo de la fila y columna que seleccione, para esto, hacemos los siguiente:

![image](https://user-images.githubusercontent.com/122764419/213931099-9963a49a-fc30-4456-8af8-37c61f9a7711.png)

lo que ejecutando el programa nos quedaria de la siguiente forma:

![image](https://user-images.githubusercontent.com/122764419/213931183-0c864fc6-7c45-4095-8dfa-ad58674bf054.png)



