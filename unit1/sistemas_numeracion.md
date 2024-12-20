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

2. Cambios de Base
A veces necesitamos convertir un número de un sistema a otro. 
De Binario a Decimal:
Para convertir de binario a decimal, multiplicamos cada bit por 2 elevado a su posición y luego sumamos.
De Decimal a Binario:
Para convertir de decimal a binario, dividimos el número entre 2, anotando los restos de cada división. Al final, los restos se leen de abajo hacia arriba.
De Decimal a Hexadecimal:
Similar a la conversión a binario, pero dividimos entre 16 y usamos letras para los números 10 a 15 (A=10, B=11, etc.).
De Hexadecimal a Decimal
Para convertir un número hexadecimal a decimal, seguimos estos pasos:
Escribimos el número hexadecimal.
Multiplicamos cada dígito por 16 elevado a la posición que ocupa, comenzando desde la derecha (posición 0).
Sumamos los resultados.

De Octal a Decimal
Para convertir de octal a decimal, seguimos el mismo proceso que con el binario y hexadecimal. Multiplicamos cada dígito octal por 8 elevado a la posición que ocupa, comenzando desde la derecha (posición 0), y luego sumamos los resultados. 

3. Operaciones Lógicas y Aritméticas Binarias
En los sistemas binarios, hacemos operaciones como en el sistema decimal, pero solo con 0s y 1s:
Operaciones Lógicas:
AND (Y): Da 1 solo si ambos bits son 1. Ejemplo: 1010 AND 1100 = 1000.
OR (O): Da 1 si al menos uno de los bits es 1. Ejemplo: 1010 OR 1100 = 1110.
NOT (NO): Invierte el valor de cada bit. Ejemplo: NOT 1010 = 0101.
XOR (O Exclusivo): Da 1 si los bits son diferentes. Ejemplo: 1010 XOR 1100 = 0110.
Operaciones Aritméticas:
Suma: Se hace bit a bit. Si la suma da 2 (que es 10 en binario), llevamos 1 al siguiente bit.
Ejemplo: 1101 + 1011 = 11000 (llevar 1).
Resta: Igual que la resta normal, pero con bits. Si necesitas restar 0 de 1, debes pedir un "préstamo" de la siguiente posición.
Ejemplo: 1101 - 1011 = 0100.
Multiplicación: Se hace igual que en decimal, pero usando reglas de binario.
Ejemplo: 101 × 11 = 1111.
División: Similar a la división normal, dividiendo sucesivamente entre 2.
Ejemplo: 10101 ÷ 10 = 1011.

4. Almacenamiento de la Información
Las computadoras almacenan todo como 0s y 1s. Aquí están las unidades básicas de almacenamiento:
Bit: Es el trozo más pequeño de información. Puede ser 0 o 1.
Byte: Es un conjunto de 8 bits. Un byte puede representar un número o un carácter.
Palabra: Son conjuntos de bits (generalmente 16, 32 o 64 bits). Las palabras representan datos más grandes, como números grandes o instrucciones para la computadora.
Los datos en la memoria de las computadoras son almacenados como secuencias de bits. Dependiendo de cuántos bits tengamos (como en una "palabra"), podemos representar cosas más complejas como números, letras o incluso imágenes. Sistemas como ASCII (para caracteres) y UTF-8 (para caracteres de todo el mundo) ayudan a almacenar y procesar textos.

