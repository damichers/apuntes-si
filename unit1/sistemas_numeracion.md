4. De Decimal a Octal
Para convertir de decimal a octal, dividimos el número decimal entre 8 y registramos los restos. Luego leemos los restos de abajo hacia arriba.

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
