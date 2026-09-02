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

# 📄 Taller 3

## Operadores, Expresiones y Pseudocódigo
Programación I

:::{note}
Este Taller debe entregarse en formato `docx`, con sus respectivas pruebas de escritorio y diagrama de flujo realizado a mano y subido en forma de foto, a partir de este taller los siguientes deben entregarse desde Colaboratory, con un enlace con los permisos en público o el notebook adjunto, mil gracias.
:::

### Ejercicio 1

Evaluar las siguientes expresiones teniendo en cuenta que:

    boolean i = true;
    boolean j = false; 
    boolean k = true;

|      Expresión     | Resultado |
| ------------------ | --------- |
| <code> (i && j) \|\| (i && k) </code> | |
| <code> (i \|\| !j) && (!i \|\| k) </code> | |
| <code> i \|\| j && k </code> | |
| <code> !(i \|\| j) && k </code> | |

### Ejercicio 2

De las siguientes expresiones decir ¿cuáles son válidas?, ¿cuál es el efecto de su ejecución o resultado? y ¿de qué tipo deben ser las variables?

|  Expresión   | ¿Es válida? | Resultado | Tipo de dato |
| ------------ | ----------- | --------- | ------------ |
| ``` a = (2 > 1) ```  |             |           |              |
| `b = (b + 1)`  |             |           |              |
| `value = 7866` |             |           |              |
|   `‘s’ = ‘t’`  |             |           |              |
|    `s = ‘t’`   |             |           |              |
|     `m = n`    |             |           |              |

### Ejercicio 3

Agregue los paréntesis necesarios a las siguientes expresiones de modo que el resultado siempre sea true. Tenga en cuenta que:

    int i = 10;
    int j = 19;
    boolean k = true;
    boolean m = false;

|  Expresión Original  | ¿Es válida? |
| -------------------- | ----------- |
| <code> i = j \|\| k <code> | |
| <code> i ≥ j \|\| i ≤ j && k </code> | |
| <code> !k \|\| k </code> | |
| <code> !m && m </code> | |

### Ejercicio 4

Dadas las siguientes expresiones, indicar si son válidas o no, y su respectivo resultado. Tenga en cuenta que:

    final int MAX = 1000;
    float t = 0f;
    int a = 3;
    int b = 4;
    int c = 0;

|        Expresión        | ¿Es válida? | Resultado | Tipo de dato |
| ----------------------- | ----------- | --------- | ------------ |
|  ``` c = (990 - MAX) / 4; ```   |             |           |              |
|       `c = b / 0;`        |             |           |              |
|   `c = a % (MAX - 990);`  |             |           |              |
|   `c = (MAX - 990) % a;`  |             |           |              |
|      `c = 3.14f * a;`     |             |           |              |
|        `t = a / b;`       |             |           |              |
|     `t = a % (a / b);`    |             |           |              |
|       `c = a / b;`        |             |           |              |

### Ejercicio 5

Diseñar un algoritmo (en pseudocódigo) que realice un descuento a un producto y muestre el resultado del precio final.

* El algoritmo debe tener una variable para el valor (porcentaje) de descuento y otra variable para el precio original del producto. 
* Para las operaciones necesarias puede declarar las variables que desee.
* Puede ayudarse con PSeInt.

### Ejercicio 6

 Dado el siguiente pseudocódigo describa cuales son los errores y reescriba el pseudocódigo de la manera correcta.

    Algoritmo taller_1
        Escribir "Este es mi resultado", result
        result <-- numero_1 + numero_2
        numero_1 <-- 2
    FinAlgoritmo

### Ejercicio 7

El siguiente pseudocódigo calcula la fuerza gravitatoria (fórmula establecida y descrita por Isaac Newton), ¿Cuáles son los resultados de las variables m1, m2, d1 y F? ¿Qué tipo de dato contiene F?

* `m1 = (45 + 3) % 2`
* `m2 = 2 + 3 * 4 * 0.5`
* `d1 = (3 % 2) - (3 / 2)`
* `G = 9.8`


```
    Algoritmo taller_1
      F = (G * m1 * m2) / (d1 * d1)
      Escribir "La fuerza gravitacional es:", F
    FinAlgoritmo
```

