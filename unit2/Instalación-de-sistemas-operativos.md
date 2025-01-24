# Instalación de Sistemas Operativos.

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

### Preparación del Equipo para la Instalación.

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
