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

# 📄 Taller en clase — Python

## Variables, operadores y condicionales
Programación I

:::{note}
Este taller se resuelve en clase con Python, en un notebook de Colaboratory. Los ejercicios están ordenados de menor a mayor dificultad: empieza por el calentamiento y avanza hasta donde te alcance el tiempo.
:::

## Guía rápida de Python

**Variables.** En Python no se declara el tipo; la variable toma el tipo del valor que se le asigna. Con `type()` puedes ver el tipo.

    nombre = "Laura"      # str
    edad = 19             # int
    estatura = 1.65       # float
    es_estudiante = True  # bool

**Entrada de datos.** `input()` siempre devuelve texto (`str`), así que hay que convertirlo si necesitas un número.

    edad = int(input("Edad: "))
    precio = float(input("Precio: "))

**Operadores.**

| Tipo | Operadores | Ejemplo |
| --- | --- | --- |
| Aritméticos | `+` `-` `*` `/` `//` `%` `**` | `17 / 5` es `3.4`, `17 // 5` es `3`, `17 % 5` es `2`, `2 ** 3` es `8` |
| Relacionales | `==` `!=` `<` `>` `<=` `>=` | `edad >= 18` |
| Lógicos | `and` `or` `not` | `edad >= 18 and edad < 65` |

**Condicionales.** Python no usa llaves: el bloque que depende del `if` se marca con los dos puntos `:` y la **sangría** (4 espacios).

    if nota >= 3.0:
        print("Aprobó")
    elif nota >= 2.0:
        print("Habilita")
    else:
        print("Reprobó")

**Ciclos.**

    for i in range(1, 6):      # i toma los valores 1, 2, 3, 4, 5
        print(i)

    while condicion:           # se repite mientras la condición sea verdadera
        ...

    while True:                # ciclo infinito; se sale con break
        ...
        if salir:
            break

## Calentamiento

### Ejercicio 1

Crea cuatro variables: tu nombre (texto), tu edad (entero), tu estatura en metros (decimal) y si eres estudiante (`True` o `False`). Imprime cada variable junto con su tipo usando `type()`. Por ejemplo:

    Laura <class 'str'>
    19 <class 'int'>
    1.65 <class 'float'>
    True <class 'bool'>

### Ejercicio 2

Sin ejecutar el código, escribe qué imprime cada línea. Después ejecútalo en Python y explica cualquier diferencia con lo que habías predicho.

    a = 17
    b = 5
    print(a / b)
    print(a // b)
    print(a % b)
    print(a ** 2)
    print(a > b and b > 10)
    print(a > b or b > 10)
    print(not (a == 17))
    print("a + b = " + str(a) + str(b))
    print("a + b =", a + b)

## Condicionales

### Ejercicio 3

Pide un número entero e imprime si es **par** o **impar**. Además, e independientemente de lo anterior, imprime si es **positivo**, **negativo** o **cero**.

Prueba con `7`, `-4` y `0`.

### Ejercicio 4

Un supermercado aplica un descuento según el valor de la compra:

| Valor de la compra | Descuento |
| --- | --- |
| Menos de $\$50.000$ | $0\%$ |
| De $\$50.000$ a menos de $\$100.000$ | $5\%$ |
| De $\$100.000$ a menos de $\$200.000$ | $10\%$ |
| $\$200.000$ o más | $15\%$ |

Pide el valor de la compra e imprime el descuento y el total a pagar. Por ejemplo, para una compra de $\$120.000$ el descuento es $\$12.000$ y el total es $\$108.000$.

### Ejercicio 5

Pide un año e indica si es bisiesto. Un año es bisiesto si es divisible entre $4$, excepto los divisibles entre $100$ que no lo sean también entre $400$.

Prueba con `2024`, `1900`, `2000` y `2023`.

### Ejercicio 6

Pide los tres lados de un triángulo. Primero verifica que se pueda formar: todos los lados deben ser positivos y la suma de cualquier par de lados debe ser mayor que el tercero. Si se puede, indica si es **equilátero** (tres lados iguales), **isósceles** (dos iguales) o **escaleno** (los tres distintos). Si no se puede, imprime `No forma un triángulo`.

Prueba con `3 3 3`, `3 3 5`, `3 4 5` y `1 2 3`.

### Ejercicio 7

Un cine cobra el boleto a $\$16.000$. Los menores de $12$ años y las personas de $60$ años o más pagan la mitad. Los miércoles, quienes no tienen el descuento por edad pagan con un $30\%$ de descuento. Los descuentos no se acumulan.

Pide la edad y el día de la semana (`1` = lunes, ..., `7` = domingo) e imprime el precio del boleto. Por ejemplo, un niño de $8$ años paga $\$8.000$ y una persona de $25$ años un miércoles paga $\$11.200$.

### Ejercicio 8

Un sensor de temperatura entrega una lectura en grados Celsius. Clasifícala así:

| Lectura | Mensaje |
| --- | --- |
| Menor a $0$ | `Congelación` |
| De $0$ a $15$ | `Frío` |
| Mayor a $15$ y hasta $25$ | `Agradable` |
| Mayor a $25$ y hasta $35$ | `Calor` |
| Mayor a $35$ | `Alerta` |

Pero si la lectura está fuera del rango posible del sensor ($-50$ a $60$), debes imprimir `Lectura inválida` sin clasificarla. Piensa en qué orden debes preguntar las condiciones.

## Ciclos (si te sobra tiempo)

### Ejercicio 9

Pide un número e imprime su tabla de multiplicar del $1$ al $10$ con un ciclo `for`. Por ejemplo, para `7`:

    7 x 1 = 7
    7 x 2 = 14
    ...
    7 x 10 = 70

### Ejercicio 10

Juego de adivinar. El programa elige un número aleatorio entre $1$ y $50$ y el usuario intenta adivinarlo. Después de cada intento debe decir si el número secreto es mayor o menor, y cuando el usuario acierte debe mostrar en cuántos intentos lo logró.

**Tip.** Para elegir el número aleatorio:

    import random
    secreto = random.randint(1, 50)

## Reto

### Ejercicio 11

Pide un número $n$ e imprime todos los números de $1$ a $n$ que son múltiplos de $3$ **o** de $5$, pero **no de ambos a la vez**. Al final imprime cuántos son. Por ejemplo, con $n = 15$:

    3 5 6 9 10 12
    Cantidad: 6
