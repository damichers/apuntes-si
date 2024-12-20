# Sistemas de Numeración

## Introducción  
Este documento proporciona una explicación de los principales sistemas de numeración utilizados en matemáticas y computación. Se describen sus características, cómo se utilizan en distintos contextos y cómo se realizan las conversiones entre ellos.

## 1. Sistemas
Un sistema de numeración es solo una manera de representar los números. Dependiendo de cuántos símbolos usamos, tenemos diferentes tipos de sistemas:

### 1.1. Sistema Decimal (Base 10)  
- Es el sistema que usamos todos los días. Tiene 10 símbolos: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9.  
- Cada número tiene un valor dependiendo de su posición.  
- Por ejemplo, en el número 23, el 2 significa "dos decenas" y el 3 significa "tres unidades".

### 1.2. Sistema Binario (Base 2)  
- Es el sistema que usan las computadoras. Solo tiene 2 símbolos: 0 y 1.  
- Cada dígito en binario es una potencia de 2.  
- Por ejemplo, el número 101 en binario significa 1x2^2 + 0x2^1 + 1x2^0 = 5 en decimal.

### 1.3. Sistema Octal (Base 8)  
- Usa 8 símbolos: 0 a 7.  
- Es útil para hacer que números binarios largos sean más cortos y fáciles de leer.  
- Cada símbolo octal corresponde a tres dígitos binarios.

### 1.4. Sistema Hexadecimal (Base 16)  
- Usa 16 símbolos: 0-9 y A-F, siendo el 10 la A, el 11 la B… hasta la F que sería el 15.  
- Este sistema es muy usado en programación porque es más corto que el binario, pero cada símbolo hexadecimal equivale a 4 dígitos binarios.

## 2. Conversión de Bases

### 2.1. De Binario a Decimal
Para convertir de binario a decimal, multiplicamos cada bit por 2 elevado a su posición y luego sumamos los resultados.

### 2.2. De Decimal a Binario
Para convertir de decimal a binario, dividimos el número entre 2, anotando los restos de cada división. Al final, los restos se leen de abajo hacia arriba.

### 2.3. De Decimal a Hexadecimal
El proceso es similar al de la conversión a binario, pero en este caso dividimos entre 16 y utilizamos letras para representar los valores 10 a 15 (A=10, B=11, etc.).

### 2.4. De Hexadecimal a Decimal
Para convertir de hexadecimal a decimal, seguimos estos pasos:
- Escribimos el número hexadecimal.
- Multiplicamos cada dígito por 16 elevado a la posición que ocupa, comenzando desde la derecha (posición 0).
- Sumamos los resultados.

### 2.5. De Octal a Decimal
Para convertir de octal a decimal, multiplicamos cada dígito octal por 8 elevado a la posición que ocupa, comenzando desde la derecha (posición 0), y luego sumamos los resultados.

## 3. Operaciones Lógicas y Aritméticas Binarias

### 3.1. Operaciones Lógicas
En el sistema binario, se realizan las siguientes operaciones lógicas:

- **AND (Y)**: Da 1 solo si ambos bits son 1.  
  Ejemplo: `1010 AND 1100 = 1000`

- **OR (O)**: Da 1 si al menos uno de los bits es 1.  
  Ejemplo: `1010 OR 1100 = 1110`

- **NOT (NO)**: Invierte el valor de cada bit.  
  Ejemplo: `NOT 1010 = 0101`

- **XOR (O Exclusivo)**: Da 1 si los bits son diferentes.  
  Ejemplo: `1010 XOR 1100 = 0110`

### 3.2. Operaciones Aritméticas

- **Suma**: Se realiza bit a bit. Si la suma da 2 (que es 10 en binario), se lleva 1 al siguiente bit.  
  Ejemplo: `1101 + 1011 = 11000` (llevar 1)

- **Resta**: Igual que la resta normal, pero con bits. Si necesitas restar 0 de 1, debes pedir un "préstamo" de la siguiente posición.  
  Ejemplo: `1101 - 1011 = 0100`

- **Multiplicación**: Se hace igual que en decimal, pero utilizando las reglas de binario.  
  Ejemplo: `101 × 11 = 1111`

- **División**: Similar a la división normal, dividiendo sucesivamente entre 2.  
  Ejemplo: `10101 ÷ 10 = 1011`


## 4. Almacenamiento de la Información
### 4.1. Unidades de Almacenamiento
Los ordenadores almacenan toda la información en formato binario, utilizando las siguientes unidades básicas:

- **Bit**: El trozo más pequeño de información, que puede ser 0 o 1.
- **Byte**: Un conjunto de 8 bits. Un byte puede representar un número o un carácter.
- **Palabra**: Conjuntos de bits, típicamente 16, 32 o 64 bits, que representan datos más grandes o instrucciones para la computadora.

Los datos en la memoria de los ordenadores son almacenados como secuencias de bits. Dependiendo del número de bits, como en una "palabra", se pueden representar datos más complejos como números, letras o incluso imágenes.

### 4.2. Sistemas de Codificación
Existen sistemas como **ASCII** (para caracteres) y **UTF-8** (para caracteres internacionales) que ayudan a almacenar y procesar textos de manera eficiente.

