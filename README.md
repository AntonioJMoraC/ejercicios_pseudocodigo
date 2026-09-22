# Ejercicios de pseudocódigo

## Datos personales
- Nombre: Antonio Jesús Mora Cabeza
- Iniciales: AJMC
- Asignatura: Programación
- Correo: nmorcab2106@iesrafaelalberti.es / nmorcab2106@g.educaand.es

## Ejercicios
### Ejercicio 1
Escribe un programa que pida el nombre del usuario para luego darle la bienvenida.
```text
Inicio
  Escribe "Introduce tu nombre: "
  Lee nombre
  Escribe "Hola, " + nombre
Fin
```
### Ejercicio 2
Escribe un programa para pedirle al usuario las horas de trabajo y el precio por hora y calcule el importe total del servicio.
```text
Inicio
  Escribe "Introduzca las horas trabajadas: "
  Lee horas
  Escribe "Introduzca el coste por hora: "
  Lee coste
  total = horas * coste
  Escribe "Importe total: " + total
Fin
```
### Ejercicio 3
Suponiendo que se han ejecutado las siguientes sentencias de asignación:
ancho = 17
alto = 12.0
Para cada una de las expresiones siguientes, intenta adivinar el valor de la expresión y su tipo sin ejecutarlas en el intérprete:

1. ancho / 2
2. ancho // 2
3. alto / 3
4. 1 + 2 * 5

```text
Inicio
  ancho = 17
  alto = 12.0
Fin
```
### Ejercicio 4
Escribe un programa que le pida al usuario una temperatura en grados Celsius, la convierta a grados Fahrenheit e imprima por pantalla la temperatura convertida.
```text
Inicio
  Escribe "Introduce una temperatura en grados Celsius: "
  Leer celsius
  conversion = celsius * 1,8 + 32
  Escribe "La temperatura es " + conversion
Fin
```
### Ejercicio 5
Escribe un programa que pida el importe sin IVA de un artículo y el tipo de IVA a aplicar y calcule e imprima por pantalla el precio final del artículo.
```text
Inicio
  Escribe "Introduce el precio sin IVA: "
  Lee precio
  Escribe "Introduce el tipo de IVA a aplicar: "
  Lee iva
  Si iva == 21 entonces
    total = precio * 1,21
  Sino Si iva == 10 entonces
    total = precio * 1,10
  Sino
    total = precio * 1,04
  FinSi
  Escribe "Precio final: " + total"
Fin
```
### Ejercicio 6
Escribe un programa que pida el importe final de un artículo y calcule e imprima por pantalla el IVA que se ha pagado y el importe sin IVA (suponiendo que se ha aplicado un tipo de IVA del 10%).
```text
Inicio
  Escribe "Introduce el importe final: "
  Lee importe_final
  importe_pagado = importe_final / 1,10
  Escribe "El importe sin IVA es de: " + importe_pagado
  iva_pagado = importe_final - importe_pagado
  Escribe "El IVA pagado es de: " + iva_pagado
Fin
```
### Ejercicio 7
Escribe un programa que solicite tres números al usuario y calcule e imprima por pantalla su suma.
```text
Inicio
  Escribe "Introduce el primer número: "
  Lee num1
  Escribe "Introduce el segundo número: "
  Lee num2
  Escribe "Introduce el tercer número: "
  Lee num3
  suma = num1 + num2
  suma += num3
  Escribe "El total de la suma es de: " + suma
Fin
```
### Ejercicio 8
Escribir el programa del ejercicio 1.2.7 usando solamente dos variables diferentes.
```text
Inicio
  Escribe "Introduce el primer número: "
  Lee num1
  Escribe "Introduce el segundo número: "
  Lee num2
  num1 += num2
  Escribe "Introduce el tercer número: "
  Lee num2
  num1 += num2
  Escribe "El total de la suma es de: " + num1
Fin
```
### Ejercicio 9
¿Es posible escribir el programa del ejercicio 1.2.7 sin usar variables? Inténtalo.
```text
Inicio
  Escribe "Introduce el primer número: "
  Lee num1
  Escribe "Introduce el segundo número: "
  Lee num2
  num1 += num2
  Escribe "Introduce el tercer número: "
  Lee num2
  num1 += num2
  Escribe "El total de la suma es de: " + num1
Fin
```
### Ejercicio 10
Escribir un programa que muestre por pantalla el resultado de la siguiente operación aritmética
```
Inicio
  suma = 3+2
  multiplicacion = 2*5
  division = 6 / 10
  total = division * 2
  Escribe "El total es: " + total
Fin
```
### Ejercicio 11
Escribir un programa que lea un entero positivo, n, introducido por el usuario y después muestre en pantalla la suma de todos los enteros desde 1 hasta n. La suma de los n primeros enteros positivos puede ser calculada de la siguiente forma:
```
Inicio
  Escribe "Introduce un entero positivo: "
  Lee entero
  suma = entero * (entero + 1) / 2
  Escribe "La suma de los " + entero + "primeros enteros es de: " + suma
Fin
```
### Ejercicio 12
Escribir un programa que pida al usuario su peso (en kg) y estatura (en metros), calcule el índice de masa corporal y lo almacene en una variable, y muestre por pantalla la frase Tu índice de masa corporal es donde es el índice de masa corporal calculado redondeado con dos decimales.
```text
Inicio
  Escribe "Introduzca su peso en kg: "
  Lee peso
  Escribe "Introduzca su estatura en metros: "
  Lee estatura
  imc = peso / (estatura * 2)
  Escribe "Tu índice de masa corporal es " + imc
Fin
```
### Ejercicio 13
Escribir un programa que pida al usuario dos números enteros y muestre por pantalla lo siguiente: "la división de n entre m da un cociente c y un resto r", donde n y m son los números introducidos por el usuario, y c y r son el cociente y el resto de la división entera respectivamente. Trata también la división entre cero.
```text
Inicio
  Escribe "Introduce un número entero: "
  Lee num1
  Escribe "Introduce otro número entero: "
  Lee num2
  cociente = num1 / num2
  resto = num1 - (cociente * num2)
  Escribe f"La división de $num1 entre $num2 da un cociente de $cociente y un resto de $resto"
Fin
```
### Ejercicio 14
Una juguetería tiene mucho éxito en dos de sus productos: payasos y muñecas. Suele hacer venta por correo y la empresa de logística les cobra por peso de cada paquete así que deben calcular el peso de los payasos y muñecas que saldrán en cada paquete a demanda. Cada payaso pesa 112 g y cada muñeca 75 g. Escribir un programa que lea el número de payasos y muñecas vendidos en el último pedido y calcule el peso total del paquete que será enviado.
```text
Inicio
  Escribe "Numero de payasos vendidos: "
  Lee payasos
  Escribe "Numero de muñecas vendidas: "
  Lee muñecas
  peso_payasos = payasos * 112
  peso_muñecas = muñecas * 75
  total = peso_payasos + peso_muñecas
  Escribe f"El peso total es de: $total g"
Fin
```
### Ejercicio 15
Imagina que acabas de abrir una nueva cuenta de ahorros que te ofrece el 4% de interés al año. Estos ahorros debido a intereses, que no se cobran hasta finales de año, se te añaden al balance final de tu cuenta de ahorros. Escribir un programa que comience leyendo la cantidad de dinero depositada en la cuenta de ahorros, introducida por el usuario. Después el programa debe calcular y mostrar por pantalla la cantidad de ahorros tras el primer, segundo y tercer años. Redondear cada cantidad a dos decimales.

Calcula el interés: capital * (1 + interés)
```text
Inicio
  Escribe "Introduce la cantidad de dinero depositada: "
  Lee cantidad
  primeraño = cantidad * (1 + 0.04)
  segundoaño = primeraño * (1 + 0.04)
  terceraño = segundoaño * (1 + 0.04)
  Escribe "La cantidad de ahorros del primer año es de " + primeraño
  Escribe "La cantidad de ahorros del segundo año es de " + segundoaño
  Escribe "La cantidad de ahorros del tercer año es de " + terceraño
Fin
```
### Ejercicio 16
Una panadería vende barras de pan a 3.49€ cada una. El pan que no es el día tiene un descuento del 60%. Escribir un programa que comience leyendo el número de barras vendidas que no son del día. Después el programa debe mostrar el precio habitual de una barra de pan (establecido en el programa como una constante), el descuento que se le hace por no ser fresca y el coste final total de todas las barras no frescas.
```text
Inicio
  Escribe "Introduce el numero de barras vendidas que no son del dia: "
  Leer pan
  BARRAS = 3.49
  precio_final = (BARRAS * pan) * 0,40
  Escribe "El precio habitual es de $BARRAS €"
  Escribe "El descuento que se le hace por no ser fresca es del 60%"
  Escribe "El coste final es de $precio_final"
Fin
```
