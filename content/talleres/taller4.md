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
Este taller se resuelve en Java, en un notebook de Colaboratory. Entrega el enlace al notebook con permisos de lectura públicos.

Para dos ejercicios a tu elección, adjunta además la prueba de escritorio hecha a mano (foto), con los valores de entrada que prefieras.
:::

### Ejercicio 1
Un monitor de la universidad trabaja varias horas al mes y le pagan \$12.500 por hora (el valor por hora debe ser una constante). Del pago bruto le descuentan el $4\%$ para salud y el $4\%$ para pensión.

Pide por teclado las horas trabajadas y muestra el pago bruto, cada descuento y lo que realmente recibe.

### Ejercicio 2
Un grupo de amigos termina de comer en un restaurante. Pide por teclado el valor total de la cuenta, el porcentaje de propina que quieren dejar y cuántas personas son.

Muestra el valor de la propina, el total a pagar y cuánto debe poner cada persona.

### Ejercicio 3
Un compañero te envía un mensaje secreto de cuatro letras, pero en lugar de letras te manda sus códigos ASCII. Pide por teclado los cuatro códigos y muestra el mensaje.

Prueba con `72`, `111`, `108` y `97`.

*Pista: si en pantalla ves números en vez de letras, revisa cómo se está evaluando el `+`.*

### Ejercicio 4
Un terreno tiene forma triangular y conoces la medida de sus tres lados. Pide los tres lados y muestra su perímetro, su área y la altura que corresponde al primer lado.

Para el área usa la fórmula de Herón, donde $s$ es el semiperímetro:

$$
s = \frac{a + b + c}{2} \qquad A = \sqrt{s(s-a)(s-b)(s-c)} \qquad h_a = \frac{2A}{a}
$$

Asume que los lados sí forman un triángulo. Recuerda que una raíz cuadrada es lo mismo que elevar a la $0.5$. Prueba con `13`, `14` y `15`.

### Ejercicio 5
Entrenar un modelo de *machine learning* tardó cierta cantidad de minutos (por ejemplo, `10000`). Pide los minutos totales y muestra ese tiempo expresado en días, horas y minutos.

### Ejercicio 6
En una materia la nota final se calcula con tres cortes: el primero vale $30\%$, el segundo $30\%$ y el tercero $40\%$. Ya tienes las notas de los dos primeros cortes.

Pide esas dos notas y calcula qué nota necesitas sacar en el tercer corte para que tu nota final sea exactamente $3.0$.

### Ejercicio 7
En una caja registradora hay billetes de \$50.000, \$20.000, \$10.000, \$5.000, \$2.000 y \$1.000. Pide el valor del cambio que hay que devolver (siempre es múltiplo de \$1.000) y muestra cuántos billetes de cada denominación se deben entregar, usando la menor cantidad de billetes posible.

Prueba con `187000`.

### Ejercicio 8
Una foto de un celular de $4000 \times 3000$ píxeles guarda 3 bytes por píxel (rojo, verde y azul), sin comprimir.

Pide el ancho, el alto y la capacidad de la memoria del celular en GB, y muestra cuántas fotos completas caben y cuántos MB de espacio sobran.

Prueba con `4000`, `3000` y `64`.

### Ejercicio 9
Una tienda en línea tuvo 12.000 visitas el mes pasado y 15.000 este mes. Pide ambas cantidades y muestra el porcentaje de crecimiento y cuántas visitas tendría dentro de tres meses si el crecimiento mensual se mantiene igual.

### Ejercicio 10
En ciencia de datos, para saber qué tan parecidos son dos clientes se calcula la "distancia" entre ellos. Cada cliente se describe con tres números: edad, ingreso mensual (en millones de pesos) y compras al mes. La distancia euclidiana entre $A = (a_1, a_2, a_3)$ y $B = (b_1, b_2, b_3)$ es:

$$
d = \sqrt{(a_1 - b_1)^2 + (a_2 - b_2)^2 + (a_3 - b_3)^2}
$$

Pide los datos de ambos clientes y muestra la distancia entre ellos. Prueba con $A = (25, 3.5, 8)$ y $B = (31, 4.0, 5)$.
