ARQUITECTURA EN SISTEMAS OPERATIVOS

Carrio Biagetti, Lautaro
			
Trabajo Practico Nº3

Punto nº1		
A: El uso de hilos para cada tarea hace que su tiempo de ejecución sea menor, ya que trabajan en paralelo. En el caso de "sinhilos.py" se ejecuta la tarea1 y hasta que esta no termine no se ejecuta la tarea2 sumando asi los timesleep() dando como resultado 5,1 seg aproximadamente. En cambio en "conhilos.py" tiene la misma cantidad de tareas pero al iniciar en paralelo los time sleep() suceden al mismo tiempo y se superponen haciendo dando como resultado 4,1 seg aproximandamente. Es predecible pero depende del código y de la velocidad de la computadora
			
B: El tiempo depende de los componentes de cada computadora
			
C: Al ejecutar el código antes de borrar los comentarios, este da como resultado 0 porque ambas funciones modifican la misma cantidad de veces la variable acumulador (+5 – 5), por lo que este va a ser siempre 0. En cambio cuando borramos el “#” de los comentarios estamos agregando un segundo bucle, lo que hace impredecible el resultado, ya que los hilos no corren a la misma velocidad, entran en una condición de “carrera” donde el resultado depende del hilo que llega primero.

Puntoº2
A:
![imagen](https://github.com/lautarocarrio/ASO2024TPs/assets/166873623/1d42c9d5-a7b8-4123-8bbc-c6d0a18892c0)



![imagen](https://github.com/lautarocarrio/ASO2024TPs/assets/166873623/fbdc1a71-672a-4a89-ac37-34dc9f12ec1e)


Parcial, Punto 11
https://www.youtube.com/watch?v=P_DDb-fP9GY
