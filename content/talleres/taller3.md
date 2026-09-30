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

### Ejercicio 8

Evaluar las siguientes expresiones teniendo en cuenta que:

    boolean p = true;
    boolean q = true;
    boolean r = false;
    boolean s = true;

Recuerda el orden de precedencia: primero `!`, luego `&&`, y por último `||`.

|      Expresión     | Resultado |
| ------------------ | --------- |
| <code> (p && q) \|\| (r && !s) && (p \|\| s) </code> | |
| <code> !(p && q) \|\| (!r && s) \|\| (p && !q && r) </code> | |
| <code> (p \|\| q) && (r \|\| s) && !(q && s) </code> | |
| <code> ((p && !q) \|\| (r && s)) && (p \|\| r \|\| s) </code> | |

### Ejercicio 9

De las siguientes expresiones decir ¿cuáles son válidas?, ¿cuál es el resultado de su ejecución? y ¿de qué tipo de dato queda el resultado? Tenga en cuenta que:

    int a = 7;
    int b = 2;
    float f = 2.0f;
    int resultado;
    float resultadoF;

|          Expresión          | ¿Es válida? | Resultado | Tipo de dato |
| ---------------------------- | ----------- | --------- | ------------ |
| `resultado = a / b;`         |             |           |              |
| `resultado = a / f;`         |             |           |              |
| `resultadoF = a / b;`        |             |           |              |
| `resultadoF = a / f;`        |             |           |              |
| `resultado = (int)(a / f);`  |             |           |              |
| `resultadoF = (float)a / b;` |             |           |              |
| `resultado = a % b;`         |             |           |              |
| `resultadoF = f % a;`        |             |           |              |

```{admonition} Pista
:class: tip
Fíjate bien en `resultado = a / b;` comparado con `resultadoF = a / b;` — en los dos casos `a` y `b` son `int`, así que la división ocurre **primero** en enteros, y solo después el resultado se convierte al tipo de la variable donde se guarda. El orden importa.
```

### Ejercicio 10

Dado el siguiente pseudocódigo describa cuáles son los errores y reescriba el pseudocódigo de la manera correcta.

    Algoritmo AreaTriangulo
        Definir base, altura Como Entero
        Definir area Como Entero
        area <- base * altura / 2
        Leer base
        Escribir "El área es: ", area
        altura <- 6
    FinAlgoritmo

### Ejercicio 11

El siguiente pseudocódigo calcula el volumen de un cilindro. ¿Cuál es el resultado de la variable `volumen`? ¿Qué tipo de dato contiene?

* `radio = 3`
* `altura = 5.0`
* `PI = 3.1416`

```
    Algoritmo VolumenCilindro
      volumen = PI * (radio * radio) * altura
      Escribir "El volumen del cilindro es:", volumen
    FinAlgoritmo
```

