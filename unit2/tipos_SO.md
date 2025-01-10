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

## 4. Sistemas Operativos Monousuario y Multiusuario

### Ventajas e inconvenientes:

- **Monousuario:**
  - **Ventajas:**
    - Simplicidad de diseño y uso.
    - Menores requerimientos de hardware.
    - Ideal para dispositivos personales.
  - **Inconvenientes:**
    - Limitación en la colaboración y el acceso compartido.
    - Menor eficiencia en el uso de recursos si solo una tarea es ejecutada.

- **Multiusuario:**
  - **Ventajas:**
    - Permite que múltiples usuarios trabajen simultáneamente, optimizando recursos.
    - Soporte para redes y sistemas centralizados.
    - Adecuado para empresas o entornos académicos.
  - **Inconvenientes:**
    - Mayor complejidad en su administración.
    - Posibles problemas de seguridad y gestión de conflictos entre usuarios.

[Fuente](https://airnavas.wordpress.com/monousuario-y-multiusuario)

### Aplicaciones típicas de cada tipo:

- **Monousuario:**
  - Computadoras personales.
  - Dispositivos específicos como kioscos digitales o cajeros automáticos.
- **Multiusuario:**
  - Servidores empresariales.
  - Sistemas académicos y de investigación.

---

## 5. Sistemas Operativos Según su Arquitectura

### Sistemas Operativos de Red:
- **Características:** Diseñados para gestionar recursos y servicios en una red, permitiendo acceso remoto a archivos y dispositivos.
- **Ejemplos:** Windows Server, Linux Server, Novell NetWare.
- **Aplicaciones:** Empresas con múltiples equipos conectados en red.

### Sistemas Distribuidos:
- **Características:** Permiten que múltiples computadoras trabajen juntas como un solo sistema lógico. Los recursos están distribuidos físicamente pero son accesibles de forma transparente.
- **Ejemplos:** Google File System, Hadoop, sistemas de computación en la nube.
- **Aplicaciones:** Big Data, procesamiento paralelo, y computación científica.

### Sistemas en Tiempo Real:
- **Características:** Responden a eventos en un tiempo predefinido, crucial en aplicaciones críticas donde los retrasos pueden ser catastróficos.
- **Ejemplos:** VxWorks, QNX, RTLinux.
- **Aplicaciones:** Control de robots, aviación, sistemas médicos, automóviles.

[Fuente](https://universodigital.org/introduccion-sistemas-operativos)

---

## 6. Sistemas Operativos Según su Interfaz de Usuario

### Sistemas Operativos Basados en CLI (Command Line Interface):
- **Características:** Interactúan mediante comandos escritos en texto.
- **Ventajas:**
  - Más ligeros en recursos.
  - Flexibles y potentes para usuarios avanzados.
- **Inconvenientes:**
  - Curva de aprendizaje pronunciada para principiantes.
- **Ejemplos:** DOS, Bash en Linux.

### Sistemas Operativos con GUI (Graphical User Interface):
- **Características:** Interactúan mediante interfaces gráficas, como ventanas y botones.
- **Ventajas:**
  - Intuitivos y fáciles de usar.
  - Mejor experiencia visual para usuarios comunes.
- **Inconvenientes:**
  - Mayor consumo de recursos.
- **Ejemplos:** Windows, macOS, GNOME en Linux.

[Fuente](https://www.muycomputer.com/2019/11/09/interfaces-graficas-mejores-linea-comandos)

---

## 7. Sistemas Operativos para Dispositivos Móviles

### Características específicas:
- Diseñados para hardware de baja potencia (batería, CPU).
- Soporte para pantallas táctiles y sensores (acelerómetros, GPS).
- Tiendas de aplicaciones integradas.
- Seguridad optimizada para redes móviles.

### Ejemplos:
- **Android:** Basado en Linux, ampliamente usado, personalizable y compatible con muchas marcas.
- **iOS:** Exclusivo para dispositivos Apple, cerrado y optimizado para su hardware.
- **HarmonyOS:** De Huawei, diseñado para integración entre dispositivos IoT.

[Fuente](https://www.newsbytesapp.com/news/science/how-huawei-s-harmonyos-is-different-from-android-ios/story)


# 8. Sistemas Operativos para Servidores

## Requisitos de los Servidores

### 1. Hardware Compatible
- Procesadores con soporte para múltiples núcleos y virtualización.
- Gran cantidad de memoria RAM (preferiblemente ECC para corregir errores).
- Discos de alta capacidad y velocidad, con soporte para RAID.
- Interfaces de red de alta velocidad, como Ethernet Gigabit o superiores.

### 2. Capacidades del Sistema Operativo
- Administración eficiente de recursos, incluida la gestión de procesos, memoria y almacenamiento.
- Soporte para multiusuario y multitarea.
- Seguridad avanzada, con opciones de firewall, cifrado y autenticación.
- Tolerancia a fallos y alta disponibilidad (clústeres y respaldo).
- Escalabilidad para adaptarse a cambios en la carga de trabajo.

### 3. Compatibilidad de Software
- Soporte para servicios web, bases de datos y aplicaciones empresariales.
- Herramientas para virtualización y contenedores (como Docker o Kubernetes).
- Compatibilidad con protocolos estándar (TCP/IP, HTTP, FTP, SSH, etc.).

### 4. Actualizaciones y Soporte
- Ciclo de vida prolongado con soporte a largo plazo (LTS).
- Disponibilidad de parches de seguridad y actualizaciones.

---

## Ejemplos de Sistemas Operativos para Servidores

### 1. **Windows Server**
- **Características destacadas**:
  - Interfaz gráfica familiar similar a Windows.
  - Soporte nativo para servicios como Active Directory, DNS, DHCP e Hyper-V.
  - Herramientas de administración avanzada como Windows Admin Center.
- **Ventajas**:
  - Fácil integración en entornos Microsoft (Office 365, Exchange, Azure).
  - Amplia compatibilidad de aplicaciones empresariales.
- **Ideal para**:
  - Pequeñas y medianas empresas, especialmente aquellas que usan productos Microsoft.

### 2. **Linux (CentOS, Ubuntu Server)**
- **CentOS**:
  - Diseñado para entornos empresariales, derivado de Red Hat Enterprise Linux (RHEL).
  - Enfocado en estabilidad y seguridad.
- **Ubuntu Server**:
  - Compatible con una amplia variedad de hardware y aplicaciones.
  - Ciclos de soporte flexibles, con ediciones LTS.
- **Características generales de Linux**:
  - Sistema de código abierto con amplia personalización.
  - Gran comunidad y soporte.
- **Ventajas**:
  - Gratuito y altamente configurable.
  - Alto rendimiento incluso en hardware más antiguo.

### 3. **Unix**
- **Ejemplos**: IBM AIX, HP-UX, Solaris (Oracle).
- **Características**:
  - Diseñado para grandes sistemas empresariales con alta demanda de rendimiento.
  - Extrema estabilidad y fiabilidad.
- **Ventajas**:
  - Soporte técnico específico de los proveedores.
  - Robusto y seguro para servidores críticos.
- **Ideal para**:
  - Bancos, telecomunicaciones y empresas con aplicaciones personalizadas.

---

## 9. ¿Qué son los sistemas operativos embebidos?

Un sistema operativo embebido (SO embebido) es un software especializado diseñado para gestionar los recursos de hardware de un dispositivo específico y ofrecer funcionalidades específicas según los requisitos del sistema. A diferencia de los sistemas operativos genéricos (como Windows o Linux), los SO embebidos son compactos, de propósito específico, y están optimizados para tareas concretas.

### Características principales
1. **Tiempo real (RTOS, Real-Time Operating System)**:
   - Garantizan tiempos de respuesta predecibles.
2. **Ligereza y modularidad**:
   - Ocupan menos espacio en memoria y son configurables.
3. **Alta confiabilidad y disponibilidad**:
   - Funcionan ininterrumpidamente durante largos periodos.
4. **Especialización**:
   - Diseñados para realizar tareas específicas.

### Usos comunes
- **Automóviles**: Controladores de motores, frenos ABS, sistemas de infotainment.
- **Electrodomésticos**: Lavadoras, microondas, termostatos.
- **Electrónica de consumo**: Smart TVs, cámaras.
- **Industria y automatización**: Robots, PLCs, sistemas SCADA.
- **Dispositivos médicos**: Marcapasos, máquinas de diagnóstico.
- **Aeroespacial**: Sistemas de guiado, drones, satélites.

### Ejemplos destacados
1. **FreeRTOS**:
   - Compatible con arquitecturas como ARM y x86.
   - Ligero, escalable y ampliamente usado en IoT.
2. **VxWorks**:
   - Confiable y diseñado para sistemas críticos en aviación y automoción.

---

## 10. Comparativa entre Software Propietario y Open Source

| **Característica**       | **Software Propietario**                 | **Open Source**                             |
|--------------------------|------------------------------------------|---------------------------------------------|
| **Definición**            | Código fuente cerrado, controlado por una entidad. | Código fuente abierto, accesible y modificable. |
| **Licencia**              | Requiere pago o permisos específicos.   | Generalmente gratuito; licencias como GPL. |
| **Costo inicial**         | Puede ser elevado.                      | Gratuito o con costos bajos.               |
| **Control del usuario**   | Limitado.                               | Completo.                                  |
| **Soporte**               | Proporcionado por la empresa.           | Comunidad o empresas relacionadas.         |
| **Innovación y desarrollo** | Dirigido por la empresa.               | Evoluciona con la comunidad global.        |
| **Seguridad**             | Gestión central, menos transparente.    | Permite auditorías públicas.               |
| **Ejemplo de aplicaciones** | Microsoft Office, Photoshop.           | LibreOffice, GIMP.                         |

---

## Ejemplos de Sistemas Operativos

### 1. **Windows (Propietario)**
- Desarrollado por Microsoft.
- Popular en entornos domésticos y corporativos.
- Coste por licencia.

### 2. **macOS (Propietario)**
- Exclusivo para hardware Apple.
- Estable, con buena integración de hardware y software.

### 3. **Linux (Open Source)**
- Distribuciones populares: Ubuntu, Fedora, Debian.
- Altamente personalizable y gratuito.

### 4. **FreeBSD (Open Source)**
- Basado en Unix, ideal para sistemas de red y servidores.
- Licencia BSD más permisiva.

# **11. Sistemas Operativos en la Historia**

## **Evolución histórica de los sistemas operativos**  
Los sistemas operativos han pasado por varias etapas de evolución, adaptándose a las necesidades de los usuarios y los avances tecnológicos.

- **Década de 1950:**  
  Los primeros sistemas operativos eran muy básicos y específicos para cada máquina.  
  Ejemplo: *GM-NAA I/O*. Se enfocaban en tareas simples, como gestionar entradas y salidas en computadoras mainframe.  
  ![Computadora mainframe de los 50s](https://www.channelbiz.es/wp/wp-content/gallery/0-anos-ibm-mainframe/01-an-ibm-system360-in-use-at-volkswagen-1964.jpg)

- **Década de 1960:**  
  Aparece la multiprogramación, permitiendo la ejecución simultánea de varios programas.  
  Sistemas como *CTSS* y *Multics* marcaron el inicio de características modernas.  
  En 1969, *Unix* revolucionó el diseño de sistemas operativos por su modularidad y portabilidad.  
  ![Unix en 1969](https://assets.sutori.com/user-uploads/image/0aabe691-5aea-4e92-b14d-530658cdc652/1969-unix.png)

- **Década de 1980:**  
  Los sistemas operativos llegan al mercado masivo.  
  *MS-DOS* dominó las computadoras personales, mientras que *Mac OS* popularizó la interfaz gráfica amigable.  
  *Unix* se consolidó en entornos empresariales.  
  ![MS-DOS](https://arabitec.com/wp-content/uploads/2019/10/ms-dos.jpg)

- **Década de 1990:**  
  *Windows 95* combinó *MS-DOS* con una interfaz gráfica avanzada, marcando un estándar en el mercado de PC.  
  En 1991, *Linux* introdujo el código abierto, cambiando la forma en que se desarrollan y distribuyen sistemas operativos.  
  ![Windows 95](https://i1.wp.com/farm5.static.flickr.com/4119/4907877345_2f132bb924_b.jpg)

- **Década de 2000 en adelante:**  
  Surgen los sistemas operativos móviles, como *Android* e *iOS*, y se adaptan los tradicionales para computación en la nube y virtualización.  
  ![Android e iOS](https://th.bing.com/th/id/OIP.LiNH8dYklGzVpjUBx7VxrAHaEK?w=274&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7)

### **Hitos clave**
- **Unix (1969):** Sentó las bases de los sistemas operativos modernos.  
- **DOS (1981):** Dominó las PCs de los años 80.  
- **Windows (1985):** Introdujo una interfaz gráfica para usuarios finales.  
- **Linux (1991):** Código abierto, ideal para servidores y aplicaciones personalizadas.

---

# **12. Tendencias y Futuro de los Sistemas Operativos**

## **Virtualización y contenedores**  
La virtualización permite ejecutar múltiples sistemas operativos en el mismo hardware, mientras que los contenedores como *Docker* optimizan la portabilidad y ejecución de aplicaciones.  
![Contenedores Docker](https://www.javiergarzas.com/wp-content/uploads/2015/07/docker1.png)

## **Sistemas operativos para computación en la nube**  
Diseñados para soportar infraestructuras escalables y distribuidas.  
Ejemplos: *Google Cloud OS* y sistemas de *Microsoft Azure*.  
![Computación en la nube](https://cdn.shopify.com/s/files/1/0229/0839/files/cloud_computing.jpg?v=1640214502)

## **Inteligencia artificial y sistemas operativos adaptativos**  
Los sistemas operativos modernos integran IA para optimizar recursos, mejorar la seguridad y adaptarse a los hábitos del usuario.  
Ejemplo: *Fuchsia OS* de Google, diseñado para ser adaptable a cualquier dispositivo.  
![Fuchsia OS](https://th.bing.com/th/id/OIP.fqEyzoTITb-fpHJeib3VpgAAAA?rs=1&pid=ImgDetMain)

---

# **13. Comparativa de Sistemas Operativos Populares**

## **Windows**  
- **Ventajas:**  
  Fácil de usar, amplio soporte para hardware y software, ideal para juegos y aplicaciones empresariales.
- **Desventajas:**  
  Vulnerable a malware, requiere licencias pagas.  
  ![Windows](https://lh6.googleusercontent.com/proxy/7Cw6Q8c5dfJ0Cdb3S0PMAWX4Hwao1aRGyH5Fc6xkvfH7nBHiv_WPp2AelVaiI0FzAjAxa0nJu9VXM8t_QA8-hNj458_4yZoztm2o1jp57hA26EhIeK1G4HM=s0-d)

## **Linux**  
- **Ventajas:**  
  Gratuito, seguro, personalizable y ampliamente utilizado en servidores.
- **Desventajas:**  
  Curva de aprendizaje alta, menor compatibilidad con ciertos programas comerciales.  
  ![Linux]([https://www.extremetech.com/wp-content/uploads/2012/05/Linux-logo-without-version-number-banner-sized.jpg](https://th.bing.com/th/id/OIP.Fr3NJxHUxk9FO8H1UHEPpgHaEF?rs=1&pid=ImgDetMain))

## **macOS**  
- **Ventajas:**  
  Interfaz intuitiva, excelente rendimiento en diseño y multimedia, optimizado para dispositivos Apple.
- **Desventajas:**  
  Costoso y limitado al ecosistema de Apple.  
  ![macOS]([https://cdn.goconqr.com/uploads/media/image/13591348/desktop_e4471000-c28c-4714-8c59-f700ee6ec058.jpg](https://img.php.cn/upload/article/000/000/024/5ebb9e5c92b59336.jpg))

## **Usos más comunes**
- **Windows:** Uso general, software empresarial y juegos.  
- **Linux:** Servidores, programación y supercomputadoras.  
- **macOS:** Diseño gráfico, edición multimedia y usuarios de dispositivos Apple.


