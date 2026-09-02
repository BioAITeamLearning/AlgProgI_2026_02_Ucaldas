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

# 📄 Taller 8

## Funciones
Programación I

:::{note}
Este taller puede entregarse en Google Colab (enlace al notebook en un `.docx` con los permisos en público) o en archivos `.java`.

Si el notebook no tiene los permisos en público, no será evaluado el taller.
:::

### Ejercicio 1
Desarrolla un programa que mediante el uso de un menú utilizando `switch-case` implemente $5$ funciones diferentes, donde la **primera** debe generar un círculo, la **segunda** debe generar un triángulo, la **tercera** debe generar un rectángulo, la **cuarta** un corazón, y la **quinta** pedirle al usuario los datos de compra de $5$ personas, todo ello dentro de un `while` que solo termina cuando al final de cada uso del `switch-case` le pregunta si desea volver a usar el menú.

### Ejercicio 2
Desarrolla funciones para dar solución a los siguientes problemas:

- Verificar si un bebé sigue dormido. La función debe recibir y retornar un variable booleana.
- Encontrar qué velocidad entre 8 posibles opciones es la más alta / máxima. La función debe retornar un valor decimal y recibir 6 números decimales.
- Usar la formula general para hallar las raíces de funciones con la forma $ax^2 + bx + c$ (ecuación de segundo orden). Formula general:

$$x = \dfrac{-b\pm\sqrt{b^2 -4ac}}{2a}$$

$\hspace{0.8cm}$ La función debe imprimir los dos posibles valores para `x` (raíces), y el usuario debe ingresar los valores `a`, `b`, `c`.

### Ejercicio 3
Realice una función que reciba tres argumentos de tipo entero. La función debe imprimir los números comprendidos entre los dos primeros números y debe tener un paso correspondiente al tercer número. Es decir, los dos primeros argumentos son el rango, y el tercer argumento el paso. Adicionalmente debe retornar la cantidad de números impresos en pantalla.

### Ejercicio 4
Realice una función que reciba una frase y retorne la frase traducida a “lenguaje hacker” (conocido realmente como “leet”). Solo debe reemplazar las vocales de la frase ingresada con cualquier carácter alfanumérico de la sección “Leet Speak Alphabet” de la página web [L33T SP34K CH34T SH33T](https://www.gamehouse.com/blog/leet-speak-cheat-sheet/).

Por ejemplo, la vocal `A` puede equivaler a: `4`, ``/\``, ``@``, ``/-\``, ``^``, ``aye``, ``(L``, ``Д``

***Nota.** Puede ser útil transformar todas las letras de la frase a mayúsculas o minúsculas.*

### Ejercicio 5
Realice una función que reciba un número entero y devuelva el número de divisores primos que tiene. La función también debe imprimirlos.

***Nota.** Se debe crear una función que verifique que un número es primo.*

### Ejercicio 6
Realice una función que reciba como argumento las horas y minutos de dos instantes de tiempo y devuelva el número de minutos que hay de diferencia entre ambos instantes.

Por ejemplo, si ingreso `(1, 30, 0, 30)` debe volver `30`.

***Nota.** En total la función recibe 4 argumentos.*

### Ejercicio 7
Realice una función que muestre por consola una serie de números aleatorios enteros. La función recibe la cantidad de números aleatorios y los valores mínimo y máximo que pueden tomar dichos números.

Adicionalmente, la función debe devolver la cantidad de números impares.

***Nota.** Para generar números aleatorios utiliza la clase* `Math.random()` *y busca cómo limitar su rango.*



