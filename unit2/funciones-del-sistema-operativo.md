Archivos en el sistema operativo

Los archivos se utilizan para toda la entrada y salida (E/S) de información del sistema operativo, para estandarizar el acceso al software y al hardware.
La entrada se produce cuando se modifica el contenido de un archivo o se graba en él. 
La salida se produce cuando se lee el contenido de un archivo o se transfiere a otro archivo. Por ejemplo, para crear una copia impresa de un archivo, 
el sistema lee información del archivo de texto y graba esa información en el archivo que representa la impresora.


Tipos de archivo en el sistema operativo:

Tenemos 3 tipos de Archivos en un sistema operativo.

1.Sistema Regular. Los archivos regulares son los archivos más comunes y se utilizan para contener datos . 
Los archivos regulares tienen la forma de archivos de texto o archivos binarios: Archivos de texto. 
Los archivos de texto son archivos regulares que contienen información almacenada en formato de texto ASCII y son legibles por el usuario. 
Puede visualizar e imprimir estos archivos.

2.Archivos Directorio: Es un tipo de archivo único que contiene únicamente la información necesaria para acceder a archivos u otros directorios .
 Como resultado, un directorio ocupa menos espacio que otros tipos de archivos. 
Los sistemas de archivos constan de grupos de directorios y los archivos dentro de los directorios

3.Archivos Especiales: Los archivos especiales definen dispositivos para el sistema o son archivos temporales creados por procesos.
 Los tipos básicos de archivos especiales son FIFO (primero en entrar, primero en salir), de bloques y de caracteres. Los archivos FIFO también se denominan conductos.

Administracion de archivos

Es el software responsable de crear, borrar, modificar y controlar el acceso a los archivos, 
así como también de administrar los recursos usados por los archivos.

Enlaces de archivo

Los enlaces son conexiones entre un nombre de archivo y un número de referencia de nodo de índice (número de inodo),
la representación interna de un archivo. Puesto que las entradas de directorio contienen nombres de archivos emparejados con números de inodo, cada entrada de directorio es un enlace.

inodo:es el registro en el disco, este registro contiene la información sobre el archivo o carpeta como su peso, propietario, etc., excepto el contenido.


Tipos de enlace

Tenemos dos tipos de enlace:

Enlace Fijo:

Permite el acceso a los datos de un archivos desde un nombre de archivo nuevo. Los enlaces fijos garantizan la existencia de un archivo
Cuando se elimina el último enlace fijo, se suprimen el número de inodo y sus datos. Sólo pueden crearse enlaces fijos entre archivos que se encuentran en el mismo sistema de archivos

Enlace Simbolico:

Permite el acceso a datos de otros sistemas de archivos desde un nombre de archivo nuevo
El enlace simbólico es un tipo especial de archivo que contiene un nombre de vía de acceso
Cuando un proceso encuentra un enlace simbólico, puede que el proceso busque en dicha vía de acceso. Los enlaces simbólicos no protegen a un archivo para evitar su supresión del sistema de archivos.

Mandatos para archivos:

Los mandatos para archivos son instrucciones o comandos dados a un sistema informático para realizar operaciones específicas en archivos, como crear, modificar, mover o eliminar.

Ejemplos de mandatos : mkadir , cd , nano...

Seguridad de sistemas operativos

La finalidad de la seguridad del sistema consiste en proteger la información que se almacena en el sistema.
Con la seguridad de la información se pretende lograr los objetivos siguientes:



Integridad :

El valor de toda la información depende de su exactitud. Si se efectúan cambios no autorizados en los datos, éstos pierden algo o todo su valor.
 busca garantizar que sólo las personas autorizadas a ello podrán acceder a información privilegiada de la empresa. 


Disponibilidad :

La disponibilidad de un sistema es un indicador utilizado en el mantenimiento para medir la cantidad de tiempo.
Para ser considerado «disponible» un activo debe cumplir con las siguientes tres condiciones:

-garantizar una correcta funcionalidad, es decir, no estar fuera de servicio por trabajos de inspección o reparación;

-garantizar la operatividad normal, operando en las condiciones previstas (por ejemplo, a una velocidad determinada) para alcanzar el objetivo preestablecido;

-ser fácilmente utilizable cuando sea necesario para no interrumpir los programas de producción.

Confidencialidad:

La confidencialidad es el principio que garantiza que a la información solo pueden acceder las personas que dispongan de autorización
la cual se basa en la necesidad de conocer los datos necesarios para el desempeño de la actividad laboral.

se utilizan códigos especiales de identificación. Es decir en lugar de utilizar el nombre y apellidos reales, o incluso el registro de la institución, se asignan otros códigos para su identificación.


