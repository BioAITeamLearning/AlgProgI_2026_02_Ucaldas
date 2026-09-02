---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# 📄 Taller 5

## Condicionales
Programación I

:::{note}
Este Taller debe entregarse en formato `docx`, con sus respectivas pruebas de escritorio y diagrama de flujo realizado a mano y subido en forma de foto (en caso de pedirse).

Los notebooks de Colaboratory (tanto Java como Python) deben tener su respectivo enlace en el `.docx` con los permisos en público.
:::

### Ejercicio 1
Lea desde el teclado el Nombre, la Edad, el Sexo (`M` o `F`) y el Estado Civil (Soltero/a, Casado/a, Unión libre, Separado/a, Divorciado/a, Viudo/a) de una persona e imprima todos los datos solo si la persona es Soltera y mayor de edad, de lo contrario imprima solo el Nombre y la Edad.

### Ejercicio 2
Dado un número entero `n` (ingresado por teclado), realice las siguientes acciones condicionales:

- Si `n` es impar, imprima `Número Raro`
- Si `n` es par y está en el rango inclusivo de 2 a 5, imprima `No es Raro`
- Si `n` es par y está en el rango inclusivo de 6 a 20, imprima `Número Raro`
- Si `n` es par y mayor que 20, imprima `No es Raro`

Nota. El rango de números permitidos es 1 a 100.

Realiza una prueba de escritorio con `n = 24`

### Ejercicio 3
Lea dos números y calcule el cociente de dividir el primero por el segundo. Imprima el cociente. Si el segundo número leído es cero NO ejecute el cálculo e imprima un mensaje que diga `La división no es posible`.

### Ejercicio 4
Una frutería ofrece peras con descuento según la siguiente tabla:

| Precio | Porcentaje de Descuento |
| ------------------------ | ----------- |
| $\$2.000$ | $0\%$ |
| $\$3.500$ - $\$5.500$ | $7\%$ |
| $\$6.000$ - $\$8.000$ | $12\%$ |
| $\$15.000$ en adelante | $15\%$ |

Entrar por pantalla: número de peras compradas y valor de compra. Determinar cuánto pagará una persona que compre peras en esa frutería.

### Ejercicio 5
Determinar el precio de un pasaje de ida y vuelta por avión, conociendo la distancia a recorrer, el número de días de estancia y sabiendo que si la distancia es superior a $1000 Km$ y el número de días de estancia es superior a $7$, la línea aérea le hace un descuento del $30\%$. El precio por kilómetro es de $\$1.350$.

### Ejercicio 6
Entrar por pantalla los siguientes datos de un estudiante: `codigo`, `nombre`, `nota1`, `nota2`, `nota3`. Mostrar el código, nombre y el promedio de nota si el estudiante aprobó la materia, en caso contrario sacar un mensaje que indique que el estudiante perdió la materia.

### Ejercicio 7
Realizar un algoritmo que lea el valor de la unidad y el número de unidades vendidas por un empleado e imprima su comisión si se sabe que la comisión es del $15\%$ si vende más de $200$ unidades, del $10\%$ si vende entre $100$ y $200$ unidades, y el $5\%$ si vende menos de $100$ unidades sobre el valor total de la venta.

### Ejercicio 8
En un supermercado se hace una promoción, mediante la cual el cliente obtiene un descuento dependiendo de un número que se escoge al azar. Si el número escogido es menor que $74$ el descuento es del $15\%$ sobre el total de la compra, si es mayor o igual a $74$ el descuento es del $20\%$. Obtener cuanto dinero se le descuenta.

### Ejercicio 9
Realice un programa que solicite al usuario una fecha y muestre la fecha correspondiente al día siguiente.

- Se debe leer un día, mes y año
- Debe validarse que el día, mes y/o año sean correctos
- Realizar una prueba de escritorio con `day = 31`, `month = 12`, `year = 2023`

### Ejercicio 10
En una fábrica de computadoras se planea ofrecer a los clientes un descuento que dependerá del número de computadoras que compren.

- Si las computadoras son menos de cinco se les dará un $15\%$ de descuento sobre el total de la compra.
- Si el número de computadoras es mayor o igual a cinco pero menos de diez se le otorga un $25\%$ de descuento.
- Si son $15$ o más se les da un $30\%$ de descuento. 

Nota. El precio individual por computadora es de $\$18.000$

### Ejercicio 11
Leer cuatro valores por pantalla, imprima el mayor de todos. Suponga que todos son diferentes.

### Ejercicio 12
Realiza un programa que calcule la potencia de un número, dado este y su exponente. Pueden ocurrir tres casos:

- El exponente sea positivo: imprime el resultado en pantalla.
- El exponente sea 0, imprime el resultado es 1.
- El exponente sea negativo, imprime el resultado es 1, potencia con el exponente positivo.

### Ejercicio 13
Elaborar un algoritmo para que calcule la nota definitiva de un estudiante de lógica. Se debe leer las siguientes notas por pantalla: `seg` (seguimiento 60%), `parc1` (parcial uno $20\%$) y `parc2` (parcial dos $20\%$), al final debe imprimir un mensaje que indique si ganó o perdió la materia.

### Ejercicio 14
Lea las tres dimensiones de un bloque rectangular. Encuentre las tres diagonales de sus caras diferentes y determine si pudiera atravesar por un orificio circular de diámetro dado.

### Ejercicio 15
Un almacén de venta de ropa tiene las siguientes promociones para sus clientes las cuales consisten en lo siguiente:

- Para ventas menores o iguales a $\$100.000$ con pago en efectivo, se hace un descuento del $20\%$, con tarjeta de crédito se hace el $10\%$.
- Para ventas mayores a $\$100.000$ y menores o iguales a $\$200.000$, con pago en efectivo se hace un descuento del $30\%$, con tarjeta de crédito se hace el $15\%$.
- Para ventas mayores a $\$200.000$, con pago en efectivo se hace un descuento del $40\%$ y con tarjeta de crédito se hace el $20\%$.

### Ejercicio 16
En una escuela el costo de matrícula de los alumnos se determina según el número de materias que cursan. El costo de todas las materias es el mismo. Se ha establecido un programa para recompensar a los alumnos, el cual consiste en lo siguiente: 

- Si el promedio obtenido por un alumno en el último periodo es mayor o igual que $4$, se le hará un descuento del $30\%$ sobre la matrícula y no se le cobrará IVA.
- Si el promedio obtenido es menor que $4$ deberá pagar la matrícula completa, la cual incluye el $10\%$ de IVA.

Imprimir el promedio del estudiante, el descuento aplicado y el valor final de la matrícula (mensual y anual), el valor en bruto de la matrícula es de $\$2.500.000$ mensuales.

### Ejercicio 17
Diseñar un algoritmo que lea tres números y encuentre si uno de ellos es la suma de los otros dos, en este caso mostrar `Iguales` de lo contrario mostrar `Son distintos`.

### Ejercicio 18
Juan cuenta con una pequeña laptop que está muy desactualizada y no cuenta con la aplicación de calculadora, sin embargo, es un pelao muy fino y ve que el ordenador tiene instalado tanto un compilador de Java como de Python, entonces decide realizar una calculadora de forma manual, para esto Juan debe como mínimo cumplir con los siguientes requisitos:

- Leer mínimo dos números por teclado.
- Hacer sumas entre los dos números.
- Hacer restas entre los dos números.
- Hacer multiplicaciones entre los dos números.
- Hacer divisiones entre los dos números.
- Mostrar el resultado después de cada operación.

**Pista:** Se sugiere utilizar la estructura `switch case` en Java para mayor eficiencia y utilizar `elif` en Python.








