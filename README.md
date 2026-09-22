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

