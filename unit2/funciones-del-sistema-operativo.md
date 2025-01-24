Funciones del sistema operativo :

-Gestion de Entrada y Salida (E/S):

 Es un componente crucial de los sistemas operativos y se encarga de la comunicación entre el sistema informático y los dispositivos externos
 como los periféricos (teclados, ratones, impresoras) y las memorias auxiliares (discos duros, unidades SSD).

 Esta gestión es fundamental para garantizar que los datos se muevan correctamente entre el sistema y los dispositivos, permitiendo que el usuario interactúe 
 con la máquina de manera eficiente.

 El sistema operativo juega un papel esencial en la gestión de los dispositivos de E/S, controlando los dispositivos de entrada y salida, gestionando las direcciones de memoria involucradas
 y supervisando las técnicas de gestión para optimizar el rendimiento y la eficiencia del sistema.

 Técnicas de Gestión de Entrada/Salida (E/S):
  
 Existen diversas técnicas para gestionar las operaciones de Entrada/Salida en un sistema. A continuación, se describen las más comunes:
 1. Controlada por programa (síncrona)

 En este enfoque, la CPU envía una orden al controlador del dispositivo y espera hasta que la operación de E/S haya finalizado antes de continuar con otras tareas.
 Durante este proceso, la CPU verifica periódicamente el estado del controlador para saber si la operación se ha completado.

 Ventajas:

 Simplicidad en la implementación.
 Es adecuada para operaciones de E/S que no requieren alta velocidad de transferencia.
 
  Desventajas:

  Pérdida de rendimiento: La CPU está bloqueada mientras espera la finalización de la operación, lo que reduce el tiempo disponible para otros procesos.
  Atención exclusiva a un solo periférico: La CPU está dedicada a un solo dispositivo durante la operación de E/S.

 Ejemplos : 
 
   -Lectura de un archivo desde el disco duro (sin interrupciones)
  Imagina que un programa necesita leer datos desde un archivo en un disco duro. El proceso se realiza de manera síncrona, lo que significa que la CPU espera activamente que el disco termine de leer antes de seguir con otros proceso
   Es decir que no hara nada hasta que termine este proceso.
   -Escritura en una impresora (sin interrupciones)
   En este caso, la CPU envía un trabajo de impresión a una impresora y espera a que el trabajo se complete antes de seguir con otros procesos.
  
  En resumen : 
 Se encarga de la gestion correcta para que los datos entre sistema y dispositos se haga correctamente esperando a que un proceso se complete y luego siga otro.
  
  2. Controlada por interrupciones (asíncrona)


 En este caso, la CPU envía una orden al controlador y continúa ejecutando otras instrucciones sin esperar a que la operación de E/S termine.
 Cuando el controlador termina la operación, genera una interrupción, que suspende el proceso actual de la CPU y le permite realizar la transferencia de datos entre el dispositivo y la memoria.

 Ventajas:
 Mejora el rendimiento al permitir que la CPU ejecute otras tareas mientras se espera la finalización de la operación de E/S.
 Desventajas:
 Requiere una gestión eficiente de interrupciones para evitar que el sistema se sobrecargue con solicitudes de interrupción.

 Ejemplos :
  -Dispositivos de almacenamiento (discos duros o SSD) :  cuando se realizan operaciones de lectura o escritura en discos duros (HDD) o unidades de estado sólido (SSD), no se requiere que la CPU espere a que la operación termine
  - Controladores de red (Ethernet, Wi-Fi) :  Cuando una computadora o dispositivo recibe paquetes de datos a través de una red (Ethernet o Wi-Fi), la CPU no tiene que estar continuamente verificando si los datos han llegado.

 En resumen :
 Se encarga de que el sistema tenga un buen funcionamiento constantemente.

 3. Acceso Directo a Memoria (DMA)

 La DMA permite transferir datos entre la memoria y los dispositivos sin la intervención directa de la CPU.Un controlador de DMA se encarga de gestionar las transferencias de datos entre el dispositivo y la memoria.
 utilizando registros para controlar la dirección y cantidad de datos a transferir. La CPU solo está involucrada en la configuración inicial y final del proceso de transferencia.

 
 Ventajas:
 Reducción del uso de la CPU: La CPU no necesita intervenir en cada operación de E/S, lo que mejora el rendimiento general.
 Permite transferencias de datos más rápidas al evitar la intervención de la CPU en cada paso de la transferencia.

 Desventajas: 
 Complejidad en el diseño: Requiere hardware adicional para gestionar las transferencias.
 Riesgo de conflictos: El uso compartido de la memoria entre la CPU y el controlador DMA puede generar conflictos si no se maneja adecuadamente.

 Ejemplos:
  Transferencia de datos de un disco duro a la memoria: En sistemas de computadoras, cuando se realiza una lectura de datos desde un disco duro o una unidad SSD hacia la memoria RAM, el controlador DMA
  permite que el disco transfiera bloques de datos directamente a la RAM sin que la CPU esté involucrada
  Reproducción de audio en un sistema de sonido: Cuando estás reproduciendo música o sonido en una computadora o dispositivo, los datos de audio se leen desde la memoria RAM 

   En Resumen :
   DMA es una técnica de transferencia de datos eficiente que permite que los dispositivos de E/S y la memoria principal interactúen sin la intervención constante de la CPU.


![Figura de control de excitación](imagenes/Figura-1-Estructura-general-del-control-de-excitacion-de-la-maquina-sincrona.png)


