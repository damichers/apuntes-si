# 1. Introducción a los Sistemas Operativos

## ¿Qué es un sistema operativo?

**Un sistema operativo (SO) es un conjunto de programas que actúa como intermediario entre el usuario y el hardware** de una computadora. Su función principal es gestionar los recursos del sistema, como la CPU, la memoria y los dispositivos de entrada y salida, para facilitar la ejecución de aplicaciones y proporcionar una interfaz amigable al usuario. Sin un sistema operativo, sería extremadamente complejo para los usuarios interactuar con el hardware de manera eficiente.

"![Imágen con diferentes Sistemas Operativos del mercado](https://images.vexels.com/content/71168/preview/software-operating-system-company-logos-64c057.png "Imágenes de SO's")"


## Funciones principales de un sistema operativo

- **Gestión de procesos**: El sistema operativo se encarga de crear, planificar y finalizar procesos. Esto incluye la asignación de tiempo de CPU a las aplicaciones en ejecución y la gestión de la concurrencia entre múltiples procesos.
- **Gestión de memoria**: Supervisa la asignación y liberación de memoria RAM para las aplicaciones, asegurando que cada proceso disponga del espacio necesario y evitando conflictos entre ellos.
- **Gestión de dispositivos**: Controla y facilita la comunicación entre el hardware (como teclados, ratones, impresoras) y el software, garantizando que los dispositivos funcionen correctamente y puedan ser utilizados por las aplicaciones.
- **Gestión de archivos**: Proporciona una estructura organizada para almacenar y recuperar datos en discos y otros medios de almacenamiento, permitiendo operaciones como creación, lectura, escritura y eliminación de archivos.
- **Seguridad y protección**: Implementa mecanismos para proteger la información y los recursos del sistema contra accesos no autorizados, estableciendo permisos y autenticaciones para los usuarios.
- **Interfaz de usuario**: Ofrece medios para que los usuarios interactúen con el sistema, ya sea a través de una interfaz gráfica (GUI) o una interfaz de línea de comandos (CLI), facilitando la ejecución de tareas y aplicaciones.


---

# 2. Clasificación de los Sistemas Operativos

## Criterios de clasificación

Los sistemas operativos pueden clasificarse según diversos criterios, entre los cuales destacan:

### Por la gestión de tareas:
- **Monotarea**: Permiten ejecutar una sola tarea o proceso a la vez. Una vez que se inicia una tarea, el sistema no puede comenzar otra hasta que la primera haya finalizado.
- **Multitarea**: Capaces de manejar múltiples tareas simultáneamente, asignando recursos de manera que varias aplicaciones puedan ejecutarse al mismo tiempo.

### Por la gestión de usuarios:
- **Monousuario**: Diseñados para ser utilizados por un solo usuario en un momento dado. No permiten que múltiples usuarios accedan simultáneamente al sistema.
- **Multiusuario**: Permiten que varios usuarios accedan y utilicen los recursos del sistema de manera concurrente, gestionando adecuadamente los permisos y la seguridad.

### Por la gestión de recursos:
- **Centralizados**: Los recursos se gestionan en una única máquina, y todas las operaciones se realizan en ese sistema central.
- **Distribuidos**: Los recursos y procesos se distribuyen entre múltiples máquinas conectadas en red, trabajando de manera coordinada para realizar tareas complejas.

## Sistemas operativos según su propósito

- **Sistemas operativos de propósito general**: Diseñados para manejar una amplia variedad de tareas y aplicaciones, utilizados en computadoras personales y servidores. Ejemplos incluyen Windows, macOS y diversas distribuciones de Linux.
- **Sistemas operativos de tiempo real**: Utilizados en entornos donde es crucial que las operaciones se realicen en tiempos específicos y predecibles, como en sistemas de control industrial, equipos médicos o sistemas de navegación.
- **Sistemas operativos embebidos**: Implementados en dispositivos con funciones específicas, como electrodomésticos, automóviles o dispositivos IoT, donde el sistema operativo está integrado y optimizado para tareas particulares.

---

# 3. Sistemas Operativos Monotarea y Multitarea

## Definición y diferencias

### Sistemas Monotarea
Son aquellos que solo permiten la ejecución de una tarea o proceso en un momento dado. Una vez iniciada una tarea, el sistema no puede comenzar otra hasta que la primera haya concluido. Este tipo de sistemas eran comunes en las primeras etapas de la informática, donde las capacidades de hardware y las necesidades de los usuarios eran limitadas.

### Sistemas Multitarea
Permiten la ejecución concurrente de múltiples tareas o procesos. El sistema operativo gestiona los recursos de manera que varias aplicaciones puedan funcionar simultáneamente, mejorando la eficiencia y la productividad. La multitarea puede implementarse de diferentes maneras, como la multitarea cooperativa, donde las aplicaciones ceden el control voluntariamente, o la multitarea con asignación de prioridades, donde el sistema asigna tiempo de CPU según la prioridad de las tareas.

## Diferencias clave:

| Característica           | **Monotarea**            | **Multitarea**         |
|--------------------------|--------------------------|------------------------|
| Procesos simultáneos      | Solo uno a la vez        | Varios al mismo tiempo  |
| Eficiencia               | Limitada                 | Mayor aprovechamiento de recursos |
| Interactividad           | Baja                     | Alta                   |
| Complejidad              | Menor                    | Mayor, debido a la gestión de múltiples procesos |

## Ejemplos de sistemas monotarea y multitarea

### Monotarea:
- **MS-DOS**: Sistema operativo utilizado en los primeros computadores personales, donde solo se podía ejecutar un programa a la vez.

### Multitarea:
- **Windows 10**: Permite ejecutar aplicaciones como navegadores web, editores de texto y programas multimedia de manera simultánea.
- **Linux**: Popular en servidores y entornos de desarrollo debido a su alta capacidad multitarea y estabilidad.
