# Guía de Formato para Documentos

## Introducción
Este documento establece el formato y las pautas que deben seguirse al crear documentos relacionados con los apuntes de la unidad. El objetivo es garantizar la coherencia y la claridad en la documentación, facilitando su comprensión y mantenimiento.

## Estructura del Documento

### 1. Título
- El título debe ser claro y conciso, será el título del tema
- Usar el encabezado de nivel 1 (equivalente a h1 de html) (`# Título del Documento`).

### 2. Introducción
- Proporcionar un resumen del contenido y propósito del documento.
- Usar el encabezado de nivel 2 (`## Introducción`).

### 3. Formato de markdown (.md)
- Los puntos se ponen con guiones ( - ).
- Las líneas separadoras se escriben con almohadillas ( # ).

### 4. Secciones Principales
- Cada sección debe tener un título claro y estar numerada.
- Usar el encabezado de nivel 2 (`## 1. Nombre de la Sección`).

### 4.1. Subsecciones
- Usar encabezados de nivel 3 para subsecciones (`### 3.1. Nombre de la subsección`).
- Mantener el contenido breve y relevante.

### 5. Listas
- Usar listas numeradas para pasos o procedimientos.
- Usar listas con viñetas para enumerar elementos sin un orden específico.

### 6. Código
- Usar bloques de código para fragmentos de código o ejemplos. 
- Usar tres acentos graves (```) antes del bloque de código y especificar el lenguaje utilizado (ejemplo: java).
*(En teclados con 'ñ', el acento grave está situado a la derecha de la tecla 'P')

  ```java
  // Ejemplo de código en Java
  public class HelloWorld {
      public static void main(String[] args) {
          System.out.println("Hola, Mundo!");
      }
  }

### 7. Aclaratorias
- Usar un asterisco (*) cuando quieras aclarar fragmentos o palabras del texto, poniendo " * " después del fragmento o palabra y al final de la página una lista de asteriscos con el texto aclaratorio.

    Ejemplo:
    ```
    PalabraNueva*

    *PalabraNueva: -significado-

    Fin de hoja
    ```
  
### 8. Imágenes
- Imágenes centradas a no ser que se incluya texto a los lados.
- Utilizar un tamaño razonable de imagen, no es necesario que vaya de lado a lado de la hoja, ni tampoco que sea tan pequeña que no se pueda apreciar esta.
```
- "![Texto alternativo](ruta/de/la/imagen "Título opcional")"
```

Detalles:

- Texto alternativo: Una descripción breve de la imagen. Es útil para accesibilidad y aparece si la imagen no se carga.
- ruta/de/la/imagen: Puede ser una URL o una ruta local al archivo de imagen.
- Título opcional: Se mostrará como un cuadro emergente al pasar el ratón por la imagen (es opcional).

### 9. Tablas
- Las tablas se pueden crear usando pipes ( | ) para separar las columnas. Asegúrate de alinear correctamente los encabezados y el contenido de las celdas.
Usar guiones (-) para definir la línea del encabezado.

<div style="margin: auto; width: fit-content;">

| Encabezado 1 | Encabezado 2 | Encabezado 3 |
|---------------|---------------|---------------|
| Fila 1 Col 1  | Fila 1 Col 2  | Fila 1 Col 3  |
| Fila 2 Col 1  | Fila 2 Col 2  | Fila 2 Col 3  |
| Fila 3 Col 1  | Fila 3 Col 2  | Fila 3 Col 3  |

</div>

- Las tablas deben centrarse utilizando html:
``` <div style="margin: auto; width: fit-content;">


| Encabezado 1 | Encabezado 2 | Encabezado 3 |
|---------------|---------------|---------------|
| Fila 1 Col 1  | Fila 1 Col 2  | Fila 1 Col 3  |
| Fila 2 Col 1  | Fila 2 Col 2  | Fila 2 Col 3  |
| Fila 3 Col 1  | Fila 3 Col 2  | Fila 3 Col 3  |


```

### 10. Gráficos
Markdown no permite directamente la creación de gráficos, pero puedes incluir imágenes de gráficos que ya hayas creado.
Usa la misma sintaxis que para las imágenes. Si tienes gráficos generados como imágenes, simplemente colócalos en la sección correspondiente.

### 11. Estructura de directorios para un proyecto Markdown
```
/mi-proyecto
 /imagenes
   /imagenesDocumento1
        /png
        /jpg
        /gif
        /svg
    /imagenesDocumento2
        ...
/documentos
    documento1.md
    documento2.md
    README.md
```
