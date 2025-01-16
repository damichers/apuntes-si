.La gestión de Entrada/Salida La gestión de Entrada/Salida (E/S) es responsable del 
movimiento de información entre el sistema informático y el exterior. Los dispositivos 
de E/S, como periféricos y memorias auxiliares, requieren una interfaz adecuada para 
que el usuario pueda conectarse con el sistema. El sistema operativo se encarga de 
gestionar las direcciones de memoria de E/S y las técnicas de gestión.

Técnicas de gestión de E/S:

1.	Controlada por programa (síncrona):
	  La CPU envía una orden al controlador del dispositivo y espera hasta que la operación de E/S termine.
	  La CPU comprueba periódicamente el estado del controlador.
	  Desventajas: pérdida de rendimiento debido al tiempo de espera y la atención exclusiva a un solo periférico.
2.	Controlada por interrupciones (asíncrona):
	  La CPU envía una orden al controlador y continúa con otros procesos, sin esperar a que termine la operación de E/S.
	  El controlador, al terminar, genera una interrupción que suspende el proceso actual de la CPU y le permite realizar la transferencia de datos.
	  La CPU es responsable de transferir datos entre la memoria y el controlador.
3.	Acceso directo a memoria (DMA):
	  Permite transferencias de datos sin intervención de la CPU.
	  Un controlador de DMA gestiona la transferencia de datos entre la memoria y el dispositivo, utilizando registros para gestionar la dirección y la cantidad de datos.
	  La CPU solo está involucrada al inicio y al final de la transferencia.

La gestión de E/S puede ser síncrona (controlada por la CPU), asíncrona (usando 
interrupciones) o mediante DMA, que optimiza la transferencia de datos sin la 
intervención continua de la CPU.


