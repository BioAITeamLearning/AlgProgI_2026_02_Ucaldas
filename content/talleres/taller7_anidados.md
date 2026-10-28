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

# 📄 Taller — Ciclos anidados

Programación I

:::{note}
Este taller puede entregarse en Google Colab (enlace en un `.docx` con los permisos en público) o en archivos `.py` o `.java`.

Si los notebooks de Colaboratory (tanto Java como Python) no tienen los permisos en público, no será evaluado el taller.
:::

### Ejercicio 1

Escribe un programa que pida el número de filas $n$ e imprima el siguiente triángulo de números. Por ejemplo, con $n = 4$:

    1
    1 2
    1 2 3
    1 2 3 4

### Ejercicio 2

Escribe un programa que pida un número de filas y un número de columnas, e imprima la tabla de multiplicar de ese tamaño (la fila $i$ y la columna $j$ contienen $i \times j$). Por ejemplo, con $3$ filas y $4$ columnas:

    1   2   3   4
    2   4   6   8
    3   6   9   12

### Ejercicio 3

Escribe un programa que imprima una pirámide de asteriscos de $n$ filas, centrada. Por ejemplo, con $n = 4$:

       *
      ***
     *****
    *******

### Ejercicio 4

Un profesor tiene varios estudiantes y cada uno tiene la misma cantidad de materias. El programa debe pedir cuántos estudiantes hay y cuántas materias tiene cada uno, y luego pedir las notas de cada estudiante.

Al final debe mostrar:

- El promedio de cada estudiante.
- Cuántos estudiantes aprobaron (promedio mayor o igual a $3.0$).
- El mejor promedio.

### Ejercicio 5

Una cadena de tiendas quiere analizar sus ventas. El programa debe pedir el número de sucursales y el número de días, y luego las ventas de cada día de cada sucursal.

Al final debe mostrar el total vendido por cada sucursal y cuál fue la sucursal que más vendió.

### Ejercicio 6

Escribe un programa que pida un número $n$ e imprima todos los números primos entre $2$ y $n$, y al final cuántos son. Un número es primo si solo es divisible entre $1$ y entre sí mismo. Por ejemplo, con $n = 30$:

    2 3 5 7 11 13 17 19 23 29
    Cantidad de primos: 10

### Ejercicio 7

Una persona tiene un presupuesto exacto y quiere comprar dos productos distintos, cuyos precios (en miles de pesos) están entre $1$ y $n$. El programa debe pedir $n$ y el presupuesto, e imprimir todas las parejas de precios $(a, b)$ con $a < b$ que suman exactamente el presupuesto. Por ejemplo, con $n = 10$ y presupuesto $11$:

    1 + 10 = 11
    2 + 9 = 11
    3 + 8 = 11
    4 + 7 = 11
    5 + 6 = 11

### Ejercicio 8 (reto)

Escribe un programa que imprima todos los números de $1$ a $n$ que son capicúas (se leen igual al derecho y al revés, como $121$ o $1331$). El usuario ingresa $n$.
