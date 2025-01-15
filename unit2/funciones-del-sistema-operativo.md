## 3.- Funciones del Sistema Operativo


El sistema operativo es el encargado de realizar las tareas más fundamentales del sistema informático, como gestionar los recursos, ejecutar las aplicaciones del usuario y ofrecer a este una interfaz adecuada para que pueda utilizarlo de manera eficaz.
Dentro de las funciones se diferencian las siguientes:


## 3.1.- Gestión de Procesos:


Los procesos son programas en ejecución. Cada proceso tiene asignados recursos (CPU, memoria, etc.), y el sistema operativo asegura que estos recursos sean gestionados de manera eficiente y sin conflictos.


- ## **Estructura del proceso:**
  - **Bloque de Control de Proceso (BCP)**: Contiene información como:
  - **PID** (identificador único del proceso).
  - **Estado del proceso** (nuevo, listo, ejecutándose, bloqueado, terminado).
  - **Recursos asignados** (memoria, dispositivos de E/S, etc.).
  - **Propietario y permisos del proceso.**
- ## **Estados**:


| Nuevo                | Listo                     | En Ejecución       | Bloqueado                                | Terminado                    |
| -------------------- | ------------------------- | ------------------ | ---------------------------------------- | ---------------------------- |
| Creación del proceso | Espera para ser ejecutado | Uso actual del CPU | Espera de un recurso externo (e.g., E/S) | Finalización de la ejecución |


- ## Planificación :
  - **Objetivo** : Determinar el orden de ejecución de los procesos.
- ## Tipos :
  - **Planificación a corto plazo**: Asigna la CPU a procesos listos.
  - **Planificación a largo plazo**: Controla cuántos procesos entran al sistema.
  - **Algoritmos**: FIFO, SJF, SRTF, Round Robin, por prioridades (expulsiva y no expulsiva).
  - **Cambios de contexto**: Proceso mediante el cual la CPU pasa de ejecutar un proceso a otro, almacenando y restaurando el estado del BCP.
- ## Ejemplos de Algoritmos :


  - **FIFO**: First in, Firts out.
    ![FIFO](imagenesSOA\png\FIFO.png)


  - **SJF**: Sort Job First.
    ![SJF](imagenesSOA\png\SJF.png)


  - **SRTF**: Sort Remaining Time First.



  - **RR**: Round Robin.
    ![RR](imagenesSOA\png\RR.png)


  - **Algoritmo por prioridad no expulsiva**:
    ![NoExpulsivo](imagenesSOA\png\NoExpulsivo.png)


  - **Algoritmo por prioridad expulsiva**:
    ![Expulsivo](imagenesSOA\png\Expulsivo.png)


## 3.2.- Gestión de Memoria:


- **Definición**: Coordina el uso de la memoria para garantizar que múltiples procesos puedan ejecutarse eficientemente.
- ## **Tipos de direcciones**:
  - **Lógicas**: Generadas por la CPU y convertidas a direcciones físicas mediante la MMU (Unidad de Manejo de Memoria).
  - **Físicas**: Ubicaciones reales en la memoria principal.
- ## **Técnicas de gestión**:


  - **Paginación**: Divide la memoria en bloques (marcos) y los procesos en páginas del mismo tamaño, eliminando la fragmentación externa.
  - **Segmentación**: Divide la memoria en segmentos lógicos como código, datos, y pila, con flexibilidad para estructuras no contiguas.


- ## **Particiones**:


  - **1.-Fijas**: Memoria dividida en bloques de tamaño fijo, lo que puede causar fragmentación interna.
  - **2.-Dinámicas**: Particiones creadas según el tamaño del proceso, evitando fragmentación interna pero generando fragmentación externa.
  - **3.-Memoria virtual**:
    Permite ejecutar procesos que exceden la memoria principal.
    Utiliza un área de intercambio (swap) en el disco para almacenar temporalmente datos no activos.
  - **4.-Tareas clave**:
    Proteger la memoria entre procesos.
    Compartir memoria entre procesos colaborativos.
