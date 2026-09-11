# 🧠 Resolución de Problemas

Como ya debes saber un programa o algoritmo es una secuencia de instrucciones bien definidas, ordenadas y finitas, las cuales permiten encontrar la solución a un problema o necesidad.

Para resolver un problema debes analizar qué necesitas (ya sean objetos materiales o abstractos), dividir el problema en pequeñas partes, definir unos pasos (instrucciones secuenciales) que resuelvan estas partes y finalmente dar solución al problema. Por lo general, al solucionar el problema se espera un resultado (abstracto o material, dependiendo del tipo de problema)

```{admonition} Nota
:class: note
Para poder identificar, definir bien un problema y dar solución es conveniente responder a las siguientes preguntas
- ¿Qué entradas se requieren? (datos con los cuales se trabaja y cantidad).
- ¿Cuál es la salida deseada? (datos de los resultados y cantidad).
- ¿Qué método produce la salida deseada?
- Requisitos o requerimientos adicionales y restricciones a la solución.
```

## Ejemplo

Juan desea hornear un pastel muy sencillo, en su casa cuenta con horno, sartén, cucharas, y demás utensilios de cocina. Juan sabe que necesita algunos ingredientes y consiguió los siguientes:

- Huevos, Harina, Azucar, Mantequilla, Chocolate

Los pasos que su mamá le dice para prepararlo son los siguientes:

- Consiga un tazón
- Agregue harina
- Agregue cinco huevos
- Agregue azucar
- Agregue mantequilla
- Revuelva la mezcla hasta conseguir una consistencia sin grumos
- Agregue chocolate derretido
- Revuelva hasta mezclar todo el chocolate
- Agregue la mezcla en un molde
- Hornee a 250° por alrededor de 25 minutos

El resultado de seguir los pasos anteriores es un pastel de chocolate. 

:::{note}
Tenga en cuenta que entre más instrucciones o pasos tenga la resolución de un problema, más facil será de entenderlo y llevar a cabo su solución.

También puede crear bifurcaciones/divisiones dependiendo de los posibles resultados.
:::

## Ejercicios

### Ejercicio 1

Un cliente realiza un pedido a una fábrica. La fábrica siempre examina en su base de datos la ficha del cliente, si el cliente es solvente entonces la empresa acepta el pedido; en caso contrario, rechazará el pedido y le enviará una carta explicando la decisión.


### Ejercicio 2

Un grupo de cinco amigos decidió ir al cine y todos deciden reunirse en un parque para ir. Ellos quieren ver **Oppenheimer** pero no quieren sentarse juntos porque hablarían demasiado y se perderían detalles de la pelicula, sino está en cartelera entonces verán **El Niño y la Garza** pero solo la verán si todos los asientos se encuentran juntos, si ninguna de las dos peliculas está en cartelera comerán helado y regresarán al parque.


### Ejercicio 3

Sara construyó una pista de baile enorme en su casa con piso céramico (baldosa) y quiere saber el area total de su pista. Sara no quiere medir con un metro toda la pista asi que solo mide un lado de una baldosa, la cual mide 1.2 metros. Además sabe que la pista ocupa 1/3 del largo de su casa, la cual mide 45 metros de largo.

Tanto la pista como las baldosas son cuadradas.

### Ejercicio 4

Una persona decide abordar un autobús que cobra el pasaje dependiendo de cuantos pasajeros se bajan y abordan. La formula para determinar el costo del pasaje es:

$$
c = |\#\hspace{3pt}pasajeros\hspace{3pt}que\hspace{3pt}bajaron - \#\hspace{3pt}de\hspace{3pt}pasajeros\hspace{3pt}que\hspace{3pt}hay\hspace{3pt}en\hspace{3pt}el\hspace{3pt}bus| \cdot 4.5
$$

*Nota. El # de pasajeros que hay en el bus, se refiere al finalizar el recorrido, no al inicio.*

La persona sube y encuentra 8 pasajeros, luego se bajan 3, suben 10 pasajeros, vuelven a subir 5 pasajeros, bajan 6 pasajeros, sube 1 pasajero, y finalmente bajan 13 pasajeros.

El conductor del bus además le dice que si hay más de 10 pasajeros en el bus le hace un descuento del 20\% del costo total.

### Ejercicio 5

Se desea obtener **una tabla con las depreciaciones acumuladas y los valores reales de cada año**, de un automóvil comprado por 20.000 euros en el año 2005, durante los seis años siguientes suponiendo un valor de recuperación o
rescate de 2.000. Realizar el análisis del problema, conociendo la fórmula de la depreciación anual constante $D$ para cada año de vida útil.

$$
D = \frac{coste - valor\hspace{3pt}de\hspace{3pt}recuperación}{vida\hspace{3pt}útil}
$$

Intenta listar las Entradas, Salida(s) y Procesos. La tabla resultado debe ver asi:

<div style="justify-content: center; display: flex;">
    <img src="https://raw.githubusercontent.com/BioAITeamLearning/AlgProgI_2026_02_Ucaldas/main/content/imgs/img1-unid-1.png" alt="pensamiento1" width="600px"/>
</div>

### Ejercicio 6 — Mayoría de edad

Escribe un algoritmo que lea la edad de una persona y diga si es mayor o menor de edad (mayor de edad a partir de los 18 años).

### Ejercicio 7 — Sensación térmica

Escribe un algoritmo que lea una temperatura en grados Celsius, la convierta a Fahrenheit ($F = C \times 1.8 + 32$), y además diga si hace frío (menos de 15°C), clima templado (entre 15°C y 28°C), o calor (más de 28°C).

### Ejercicio 8 — Vuelto en una compra

Escribe un algoritmo que lea el valor total de una compra y el monto con el que el cliente paga en efectivo. Si el monto es suficiente, calcula y muestra el vuelto; si el monto no alcanza para cubrir la compra, muestra un mensaje indicando que el pago es insuficiente (nunca debe mostrar un vuelto negativo).

### Ejercicio 9 — ¿Aprobó la materia?

Escribe un algoritmo que lea la nota final de un estudiante (sobre 5.0) y diga si aprobó (nota ≥ 3.0) o reprobó. Si aprobó, muestra cuántos puntos sacó por encima de 3.0; si reprobó, muestra cuántos puntos le faltaron para llegar a 3.0.

### Ejercicio 10 — El mayor de dos números

Escribe un algoritmo que lea dos números y diga cuál de los dos es mayor, o si son iguales.

## Tarea

### Ejercicio 11 — Par o impar

Lee un número entero y di si es par o impar (usa el operador `MOD`: un número es par si el resto de dividirlo entre 2 es cero).

### Ejercicio 12 — Área y perímetro de un círculo

Lee el radio de un círculo y calcula su área ($A = \pi r^2$) y su perímetro ($P = 2 \pi r$). Este es puramente de cálculo, sin condicionales.

### Ejercicio 13 — Descuento por monto

Lee el precio de un producto. Si supera $100.000, aplica un descuento del 10%; si no, no aplica descuento. Muestra el precio final.

### Ejercicio 14 — Signo de un número

Lee un número y di si es positivo, negativo o cero.

### Ejercicio 15 — Conversión de distancia

Lee una distancia en kilómetros y conviértela a metros y a millas (1 km = 1000 m = 0.621 millas). Puramente de cálculo, sin condicionales.

### Ejercicio 16 — Promedio de dos notas

Lee dos notas de un estudiante, calcula su promedio, y di si aprueba (promedio ≥ 3.0) o no.

### Ejercicio 17 — Conversión de moneda

Lee una cantidad en dólares y la tasa de cambio del día (pesos por dólar), y calcula a cuántos pesos colombianos equivale. Puramente de cálculo, sin condicionales.

### Ejercicio 18 — El menor de tres números

Lee tres números y di cuál de los tres es el menor.

### Ejercicio 19 — Calculadora básica

Lee dos números y un operador (`+`, `-`, `*`, `/`) como carácter, y según el operador leído, realiza la operación correspondiente y muestra el resultado. Si el carácter leído no es ninguno de los cuatro, muestra un mensaje de "operador no válido".

### Ejercicio 20 — Cajero simple

Lee el saldo actual de una cuenta y el valor que el cliente quiere retirar. Si el saldo alcanza, muestra el nuevo saldo después del retiro; si no alcanza, muestra un mensaje de fondos insuficientes.

## Siguiente paso: ¿dónde viven las variables?

Ya escribiste `Definir edad Como Entero` muchas veces en estos ejercicios. La siguiente guía muestra qué hace la computadora por dentro cuando ejecuta esa línea: cómo se reserva espacio en la memoria RAM, qué es una dirección de memoria (y por qué se ve como `0x0010`), cuánto pesa cada tipo de dato, y cómo convertir entre binario, decimal y hexadecimal.

```{admonition} Siguiente lectura
:class: tip
[Memoria, Variables y Sistemas de Numeración](memoria-variables.md) — con animación paso a paso y conversores interactivos para practicar.
```