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

# 📄 Taller 4

## Pruebas de escritorio, Entrada y Salida de Variables
Programación I

:::{note}
Este Taller debe entregarse en formato `docx`, con sus respectivas pruebas de escritorio y diagrama de flujo realizado a mano y subido en forma de foto.

Los notebooks de Colaboratory (tanto Java como Python) deben tener su respectivo enlace en el `.docx` con los permisos en público.

Los ejercicios en PSeInt deben estar contenidos en una carpeta y deben nombrarse de las siguientes formas `ejercicio1`, `ejercicio-1` (no utilizar nombres como `ejercicioCalculadoraNumeros`, `calcularIVAeImpuestos`)
:::

### Ejercicio 1
Realizar un programa que calcule el sueldo de un trabajador. El programa va a solicitar el número de horas que has trabajado en un mes, las horas se pagan a 10€. (`PSeInt`, `Java` y `Python`)

### Ejercicio 2
Declara dos variables numéricas (con el valor que desees), muestra por consola la suma, resta, multiplicación, división y módulo (resto de la división). (`Java` y `Python`)

### Ejercicio 3
Realiza una aplicación que calcule el área de un círculo ($\pi \cdot r^2$). El radio se pedirá por teclado (usar `nextDouble()`). Usa la constante `PI` y el método `pow` de `Math`. (`Java`)

### Ejercicio 4
Lee un número por teclado e indica si es divisible entre 2 (resto = 0). Si no lo es, también debemos indicarlo. (`Java` y `Python`)

### Ejercicio 5
Lee un número por teclado y muestra por consola, el carácter al que pertenece en la tabla ASCII. Por ejemplo: si introduzco un `97`, me muestre una `a`. (`Java` y `Python`)

- **a.** Modifica el ejercicio anterior, para que en lugar de pedir un número, pida un carácter (char) y muestre su código en la tabla ASCII.

*Contexto:* El código ASCII ([ver código ASCII completo](https://www.google.com/url?q=https://elcodigoascii.com.ar/&sa=D&source=docs&ust=1693448792138024&usg=AOvVaw2v6IfNkNQ0Cwhv77GRDpHP)) es una forma de codificación tanto decimal como hexadecimal, que se utilizaba para codificar mensajes durante la guerra, también tuvo su aplicación en programación e incluso se utiliza en mensajes de codificación espacial debido a su simplicidad, a continuación un enlace con información más detallada.

### Ejercicio 6
Lee por teclado el precio de un producto (puede tener decimales) y calcule el precio final con IVA. El IVA será una constante que será del $18\%$. (`Java` y `Python`)

- **a.** Haga una lista de productos, pida al usuario el nombre del producto, el precio, genere una factura con el valor total del producto y el valor más el IVA.

### Ejercicio 7
Mediante la construcción de un algoritmo genere la decodificación del siguiente mensaje del binario a ASCII:

    01101101 01100101 00100000 01100111 01110101 01110011 01110100 01100001 00100000 01101100 01100001 00100000 01100011 01101100 01100001 01110011 01100101 00100000 01100100 01100101 00100000 01110000 01110010 01101111 01100111 01110010 01100001 01101101 01100001 01100011 01101001 01101111 01101110

### Ejercicio 8
Realiza un programa donde se pida por teclado al usuario que ingrese 8 valores diferentes (`A`, `B`, `C`, `D`, `E`, `F`, `G`, `H`) y realice las siguientes operaciones:

| Nombre Variables de Operaciones | Operaciones |
| ------------------------ | ----------- |
| operacion1 | <code> (A*B)/(C+H)^2 </code> |
| operacion2 | <code> B!=F </code> |
| operacion3 | <code> (C++)*E-G+(D--) </code> |
| operacion4 | Convierte a Hexadecimal, Octal y Binario el valor de la variable `E` |
| operacion5 | <code> (sqrt(A*B)/C+B)+E </code> |
| operacion6 | <code> ((H+B+C)*(G-C-E))/A </code> |
| operacion7 | Multiplica `G` por todos los valores, incluido el valor de `G` (debes tener 8 valores), luego realiza la sumatoria de estos valores y dividide la sumatoria entre `G` |
| operacion8 | Suma/agrega valores aleatorios a las 8 variables (ver método `.rand()`), luego realiza la sumatoria de los nuevos valores y dividelos por el promedio de los mismos nuevos valores|


