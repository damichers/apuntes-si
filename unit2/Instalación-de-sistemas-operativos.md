# Instalación de Sistemas Operativos

## Introducción
La instalación de un sistema operativo (S.O.) es uno de los pasos fundamentales para configurar un equipo informático. Un sistema operativo es el software que permite la interacción del usuario con el hardware de la computadora, gestionando recursos como el procesador, la memoria y el almacenamiento. Este proceso implica una serie de pasos técnicos que deben cumplirse con precisión para asegurar un funcionamiento eficiente del equipo.

Antes de realizar la instalación, es necesario verificar que el equipo cumpla con los requisitos técnicos del sistema operativo a instalar. Esto incluye revisar el hardware disponible, asegurarse de que el sistema operativo sea compatible y preparar adecuadamente el equipo para evitar problemas durante el proceso de instalación.

## Comprobación de Requisitos Técnicos de Sistemas Operativos

### Verificación de Hardware

Una de las primeras comprobaciones antes de instalar un sistema operativo es asegurarse de que el hardware del equipo cumpla con los requisitos mínimos y recomendados por el sistema operativo. El hardware debe ser compatible con los componentes necesarios, como el procesador, la memoria RAM, el almacenamiento y la tarjeta gráfica. Si el equipo no cumple con estos requisitos, la instalación puede fallar o, en su lugar, el rendimiento del sistema operativo puede ser deficiente.

### Compatibilidad del Equipo con el Sistema Operativo

Además de los requisitos de hardware, es crucial verificar que el equipo sea compatible con el sistema operativo que se desea instalar. Cada sistema operativo requiere ciertos controladores y configuraciones para interactuar correctamente con el hardware, como la tarjeta de red, los dispositivos de entrada y salida, y la tarjeta gráfica. Es importante asegurarse de que el sistema operativo elegido tenga soporte para los controladores necesarios, especialmente cuando se opta por usar Linux en lugar de Windows, ya que las compatibilidades pueden variar.

### Requisitos Mínimos y Recomendados de Windows y Linux

Cada sistema operativo tiene una lista de requisitos mínimos y recomendados para garantizar su instalación y buen funcionamiento. Es importante conocer estos requisitos para tomar decisiones informadas al elegir el sistema operativo y garantizar que el equipo esté preparado para la instalación.

- **Windows 10:** Los requisitos mínimos incluyen un procesador de 1 GHz o superior, 2 GB de RAM y 20 GB de espacio en disco. Para un rendimiento óptimo, se recomienda un procesador de 1.5 GHz o superior, 4 GB de RAM y 64 GB de espacio en disco.
  
- **Linux (por ejemplo, Ubuntu):** Los requisitos mínimos incluyen un procesador de 2 GHz, 2 GB de RAM y 25 GB de espacio en disco. Las versiones más ligeras de Linux, como Lubuntu o Xubuntu, tienen requisitos más bajos y son adecuadas para equipos con hardware limitado.

### Preparación del Equipo para la Instalación

Antes de instalar el sistema operativo, se debe preparar adecuadamente el equipo para evitar la pérdida de datos y facilitar una instalación exitosa. Algunas de las acciones clave en esta fase incluyen:

1. **Realizar copias de seguridad (backups):** Es fundamental realizar copias de seguridad de los datos importantes para evitar pérdidas durante el proceso de instalación, especialmente si se formatea el disco duro.

2. **Gestionar las particiones del disco:** La partición del disco duro es un paso clave para organizar el almacenamiento y, en algunos casos, permitir la instalación de más de un sistema operativo (arranque dual). Asegúrate de que las particiones estén configuradas de manera adecuada.

3. **Verificar la configuración de la BIOS/UEFI:** Asegúrate de que el equipo esté configurado para arrancar desde el medio de instalación, ya sea un USB o un disco óptico. Además, comprueba si la virtualización está habilitada, en caso de que se desee utilizar máquinas virtuales.

# Instalación de Sistemas Operativos Linux: Una Guía Concisa

## ¿Por qué instalar Linux?

Linux ofrece una alternativa gratuita, personalizable y segura a los sistemas operativos comerciales. Es ideal para quienes buscan un mayor control sobre su sistema, una comunidad activa de desarrolladores y una amplia variedad de software libre.

## Antes de Empezar

- **Elige una distribución**: Existen numerosas distribuciones de Linux, cada una con sus propias características y enfoques. Algunas de las más populares son Ubuntu, Fedora, Debian y Linux Mint. Investiga cuál se adapta mejor a tus necesidades y nivel de experiencia.
- **Crea un medio de instalación**: Generalmente se utiliza una unidad USB booteable. Herramientas como Rufus o Etcher facilitan este proceso.
- **Realiza una copia de seguridad**: Antes de instalar Linux, asegúrate de tener una copia de seguridad de tus datos importantes, ya que el proceso de instalación puede sobrescribir tu disco duro.

## Proceso de Instalación

1. **Inicio desde el medio de instalación**: Reinicia tu computadora y configura la BIOS para que arranque desde el dispositivo USB.
2. **Idioma y distribución del teclado**: Selecciona el idioma y la distribución de teclado que prefieras.
3. **Tipo de instalación**: Elige entre una instalación estándar (recomendada para la mayoría de los usuarios) o una instalación personalizada para un mayor control sobre la partición del disco.
4. **Partición del disco**: Aquí decidirás cómo se dividirá tu disco duro. Puedes optar por una instalación junto a Windows, una instalación completa de Linux o una configuración más avanzada.
5. **Usuario y contraseña**: Crea un usuario principal y establece una contraseña segura.
6. **Selección de software**: Durante la instalación, se te ofrecerá la posibilidad de seleccionar los paquetes de software que deseas instalar.
7. **Inicio de la instalación**: Una vez que hayas configurado todos los parámetros, inicia la instalación. Este proceso puede tardar varios minutos.

## Consideraciones Adicionales

- **Drivers**: La mayoría de los hardware modernos son detectados automáticamente por Linux. Sin embargo, puede que necesites instalar algunos drivers adicionales para dispositivos específicos.
- **Software**: Linux viene con una amplia variedad de software preinstalado. Puedes instalar aplicaciones adicionales desde los repositorios oficiales o desde fuentes de terceros.
- **Actualizaciones**: Es importante mantener tu sistema Linux actualizado para corregir errores y mejorar el rendimiento.


# Instalación de Windows
## Requisitos previos
- Un equipo compatible con el sistema Windows
- Un dispositivo de almacenamiento USB con al menos 8 GB de capacidad o CD
- Un archivo de imagen ISO de Windows
## Pasos a seguir
#### 1. Preparar el CD o USB:
+ **USB:**
    + Descarga [Rufus](https://rufus.ie/es/) u otra herramienta similar.
    + Ejecuta la herramienta y sigue las instrucciones para crear un USB booteable.
    
+ **CD** 
    + Graba el archivo ISO de Windows en un DVD usando [ImgBurn](https://www.imgburn.com/) o similar.
#### 2. Configura la BIOS/UEFI:
+ Reinicia el ordenador y entra al menú de la BIOS/UEFI presionando F2, F12, DEL o ESC durante el arranque del mismo.
+ En la sección boot de la BIOS selecciona el USB/DVD como unidad de arranque.
#### 3. Arranca desde el medio elegido:
+ Insterta en el equipo el USB/DVD con el archivo .ISO
+ EL ordenador debería arrancar desde el medio elegido. Si no lo hace automáticamente, asegúrate de haber configurado correctamente la BIOS.
#### 4. Inicia la instalación de Windows:
+ Al arrancar desde el medio, selecciona el idioma y la configuración regional.
+ Haz clic en "Instalar ahora".
#### 5. Introduce la clave de producto (si es necesario):
+ En algunos casos, te pedirá ingresar una clave de producto. Si no tienes una, puedes seleccionar "No tengo clave de producto" y activar Windows más tarde.
#### 6. Configura como será instalación:
+ Elige el tipo de instalación:

    + **Instalación Rápida:** Es la instalación mas cómoda, conserva tus archivos, configuraciones y algunos programas durante la instalación. No formatea ni borra la unidad.
    + **Instalación personalizada:** Te permite un mayor control sobre elegir una partición (o disco) donde instalar Windows. Puedes formatear la partición antes de instalar, lo que eliminará todos los datos previos en esa unidad.
#### 7. Instala Windows:
+ El instalador copiará los archivos y configurará el sistema automáticamente. Este proceso puede tardar un tiempo, dependiendo de la velocidad del equipo.
+ El ordenador se reiniciará varias veces durante la instalación.
#### 8. Configura Windows:
+ Una vez instalado, Windows te pedirá configurar aspectos como:
    + Red Wi-Fi (si es necesario).
    +  Cuenta de Microsoft (puedes usar una cuenta en línea o una cuenta local).
    + Preferencias de privacidad y personalización.
#### 9. Instala controladores y actualizaciones:
+ Una vez en el escritorio, Windows normalmente descargará e instalará automáticamente los controladores necesarios.
+ Puedes ir a Configuración > Actualización y seguridad > Buscar actualizaciones para asegurarte de que tu sistema esté completamente actualizado.
#### 10. Instala tus programas y restaurar tus archivos.
+ Ahora que Windows está instalado y configurado, puedes instalar tus aplicaciones y restaurar tus archivos desde una copia de seguridad si es necesario.


# Comparación entre Linux y Windows


## 1. Origen y Filosofía

### Linux:
- **Origen:** Linux es un sistema operativo basado en Unix creado por **Linus Torvalds** en 1991. Es un software libre y de código abierto, lo que significa que su código fuente es accesible para cualquier persona, y puede ser modificado y distribuido de acuerdo con las licencias del proyecto.
- **Filosofía:** El modelo de desarrollo de Linux es colaborativo y comunitario. La comunidad de usuarios y desarrolladores crean y mejoran continuamente el sistema. El software de Linux es gratuito.

### Windows:
- **Origen:** Windows es un sistema operativo propietario creado por **Microsoft**, lanzado inicialmente en 1985. A diferencia de Linux, su código fuente no está disponible y se distribuye bajo licencias comerciales.
- **Filosofía:** Windows está diseñado principalmente con la simplicidad y accesibilidad para el usuario. Microsoft prioriza la facilidad de uso. Los usuarios deben pagar por las licencias del sistema operativo.

## 2. Interfaz de Usuario

### Linux:
- **Interfaz gráfica (GUI):** Linux es conocido por su uso en entornos de línea de comandos (CLI), cuenta con diversas interfaces gráficas de usuario (GUI), como GNOME, KDE, Xfce, entre otras. Estas interfaces son altamente personalizables, lo que permite que los usuarios adapten su entorno de trabajo según sus preferencias.
- **Accesibilidad y personalización:** Linux ofrece una mayor flexibilidad en cuanto a personalización de la interfaz. Los usuarios pueden modificar desde la apariencia hasta el comportamiento del sistema.

### Windows:
- **Interfaz gráfica (GUI):** Windows tiene una interfaz gráfica de usuario moderna y estandarizada que está orientada al usuario promedio. Windows ha evolucionado para ser intuitivo, con menús gráficos, ventanas de fácil navegación y un diseño amigable.
- **Accesibilidad y personalización:** Aunque la personalización es posible, Windows no es tan flexible como Linux en términos de modificación de la interfaz.

## 3. Uso

### Linux:
- **Usuarios avanzados:** Linux está dirigido principalmente a usuarios con conocimientos más técnicos o avanzados. La mayor parte de la interacción ocurre a través de la terminal o línea de comandos, lo que le da un gran poder a los usuarios para controlar el sistema.
- **Distribuciones:** Linux tiene una variedad de distribuciones (distros) como Ubuntu, Fedora, Debian, y muchas otras, que permiten elegir una versión adecuada según las necesidades del usuario, desde versiones orientadas al escritorio hasta sistemas de servidor.

### Windows:
- **Usuarios generales:** Windows es conocido por su facilidad de uso. Su interfaz gráfica está diseñada para ser intuitiva, lo que permite que la mayoría de los usuarios no técnicos puedan usar el sistema con facilidad.
- **Software compatible:** Windows es el sistema operativo más utilizado en entornos domésticos y de oficina. Casi todas las aplicaciones comerciales están diseñadas para Windows, lo que facilita la instalación de software y su compatibilidad.

## 4. Seguridad

### Linux:
- **Seguridad avanzada:** Linux es conocido por ser un sistema operativo más seguro debido a su arquitectura de permisos y a la naturaleza de código abierto, lo que permite a la comunidad identificar y corregir vulnerabilidades rápidamente. Además, las actualizaciones de seguridad suelen ser rápidas y fáciles de implementar.
- **Menos malware:** Aunque no está exento de amenazas, Linux tiene menos software malicioso en comparación con Windows.

### Windows:
- **Seguridad y vulnerabilidades:** Aunque Windows ha mejorado significativamente en términos de seguridad en versiones recientes, sigue siendo un objetivo frecuente de malware, virus y ataques debido a su alta cuota de mercado.
- **Antivirus y protección:** Los usuarios de Windows suelen necesitar software adicional de antivirus y firewall para proteger su sistema, ya que el sistema operativo no es tan seguro de forma predeterminada.

## 5. Compatibilidad de Software

### Linux:
- **Software libre y de código abierto:** Linux tiene una amplia gama de software libre y gratuito disponible, lo que es ideal para usuarios que prefieren el código abierto.


### Windows:
- **Software comercial:** Windows tiene una gran ventaja en términos de compatibilidad con software comercial, especialmente aplicaciones empresariales y juegos. La mayoría de las aplicaciones de pago, como Microsoft Office. Tiene facilidad de instalación y la mayoría de las aplicaciones están diseñadas con asistentes gráficos para facilitar la instalación.

## 6. Costos

### Linux:
- **Gratis:** Linux es completamente gratuito. Los usuarios pueden descargar e instalar cualquier distribución sin coste alguno. Además, la mayoría del software que se utiliza en Linux también es gratuito.


### Windows:
- **Licencias:** Windows requiere la compra de una licencia para su uso, lo que puede representar un costo significativo. El precio varía según la edición del sistema operativo (Home, Pro, Enterprise, etc.).

 En algunas versiones de Windows, las actualizaciones y el soporte pueden tener costos adicionales, especialmente en entornos empresariales.

## 7. Actualizaciones

### Linux:
- **Actualizaciones constantes:** Linux recibe actualizaciones regulares de seguridad y mejoras, a menudo de manera centralizada a través de los gestores de paquetes. Estas actualizaciones son generalmente rápidas y no interrumpen el flujo de trabajo del usuario.
- **Control sobre las actualizaciones:** Los usuarios tienen un control más directo sobre cuándo y cómo aplicar las actualizaciones.

### Windows:
- **Actualizaciones automáticas:** Windows realiza actualizaciones automáticas de manera periódica, lo que puede ser inconveniente para algunos usuarios. Las actualizaciones, a veces, pueden consumir mucho tiempo y recursos del sistema.
- **Control limitado:** Aunque los usuarios pueden retrasar o posponer algunas actualizaciones, en general, Windows tiene un enfoque más rígido en cuanto a actualizaciones.

## 8. Comunidad y Soporte

### Linux:
- **Comunidad activa:** Debido a su naturaleza de código abierto, Linux tiene una comunidad activa de desarrolladores y usuarios que proporcionan soporte.
- **Soporte profesional:** Las distribuciones comerciales como Red Hat y Ubuntu ofrecen soporte profesional a empresas que lo necesiten.
### Windows:
- **Soporte oficial:** Windows cuenta con un soporte oficial de Microsoft, lo que incluye actualizaciones, parches de seguridad y atención al cliente, aunque este servicio generalmente tiene un costo.
- **Comunidad:** Aunque la comunidad de usuarios es activa, el soporte formal es el pilar en Windows, especialmente para usuarios domésticos.
