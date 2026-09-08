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

### Ejercicio 6

Un carpintero corta tres listones de madera para armar un marco triangular. Antes de cortar quiere saber, dadas las tres longitudes de los listones, si en verdad pueden formar un triángulo (recuerda: la suma de cualquier par de lados debe ser mayor que el tercero). Si sí es posible, debe indicar si el triángulo es **equilátero** (los 3 lados iguales), **isósceles** (2 lados iguales) o **escaleno** (todos distintos). Si las longitudes no pueden formar un triángulo, debe informarle al carpintero que el corte no es válido.

### Ejercicio 7

El supermercado "La Economía" aplica descuentos según el monto total de la compra y el tipo de membresía del cliente (Ninguna, Plata, Oro):

- Sin membresía: 5% de descuento si la compra supera $150.000, si no, sin descuento.
- Membresía Plata: 10% de descuento si la compra supera $100.000, si no, 5%.
- Membresía Oro: 15% de descuento sobre cualquier monto, y si además la compra supera $200.000, se suma un 5% adicional (20% en total).

Dado el monto de la compra y la membresía del cliente, calcular el valor final a pagar.

### Ejercicio 8

Un parqueadero cobra por tiempo de permanencia y tipo de vehículo (carro o moto). Los primeros 15 minutos son gratis. Después de eso:

- Carro: $100 por cada 10 minutos adicionales (o fracción).
- Moto: $60 por cada 10 minutos adicionales (o fracción).

Si el cliente tiene abono mensual, paga solo el 50% del valor calculado, sin importar el tiempo. Dado el tiempo total de permanencia (en minutos), el tipo de vehículo y si tiene o no abono mensual, calcular el valor a pagar.

### Ejercicio 9

Un estudiante tiene 3 notas de un curso con distintos pesos: Examen 1 (30%), Examen 2 (30%) y Proyecto Final (40%). Calcular la nota definitiva (sobre 5.0). Con esa nota:

- Si la definitiva es menor a 3.0, el estudiante pierde el curso.
- Si es mayor o igual a 3.0, aprueba.
- Además, entra a "cuadro de honor" únicamente si la definitiva es mayor o igual a 4.5 **y** ninguna de las tres notas individuales fue menor a 3.5 (aunque el promedio dé alto, una sola nota baja lo descalifica del cuadro de honor).

### Ejercicio 10

Una persona quiere elegir el plan de telefonía más barato entre tres opciones, según cuántos minutos y cuántos GB de datos usa al mes:

- Plan Básico ($30.000): incluye hasta 100 minutos y 2 GB. Si se pasa de cualquiera de los dos límites, no sirve para ese usuario.
- Plan Intermedio ($50.000): incluye hasta 300 minutos y 6 GB. Si se pasa de cualquiera de los dos límites, no sirve.
- Plan Ilimitado ($80.000): sin límites de minutos ni datos.

Dado el consumo mensual de minutos y GB de una persona, el programa debe recomendar el plan **más barato** que le sirva (revisando en orden Básico → Intermedio → Ilimitado), o indicar que necesita el plan Ilimitado si ninguno de los otros dos alcanza.

## Tarea

```{admonition} Para entregar
:class: important
Para cada ejercicio: identifica Entradas, Salida(s) y Proceso, diseña el pseudocódigo en PSeInt y dibuja el diagrama de flujo.
```

### Ejercicio 11

A partir del peso (kg) y la estatura (m) de una persona, calcular su Índice de Masa Corporal ($IMC = peso / estatura^2$) y clasificarlo en Bajo peso (<18.5), Normal (18.5–24.9), Sobrepeso (25–29.9) u Obesidad (≥30).

### Ejercicio 12

Dado un año, determinar si es bisiesto. Un año es bisiesto si es divisible por 4, excepto los divisibles por 100, salvo que también sean divisibles por 400 (por eso 2000 sí fue bisiesto, pero 1900 no).

### Ejercicio 13

Un taxi cobra una tarifa base de $4.500 más $1.300 por kilómetro recorrido. Si el viaje inicia entre las 10pm y las 5am, se suma un recargo nocturno del 30% sobre el total. Si además el día es festivo, se suma un recargo adicional del 15% (los dos recargos se pueden acumular). Calcular el valor final del viaje.

### Ejercicio 14

Dados los tres lados de un triángulo válido, determinar si es rectángulo, acutángulo u obtusángulo comparando el cuadrado del lado mayor con la suma de los cuadrados de los otros dos (Teorema de Pitágoras generalizado). Ojo: primero hay que identificar cuál lado es el mayor.

### Ejercicio 15

Una casa tiene sensores de puerta, ventana y movimiento, y un modo de sistema (Armado / Desarmado). La alarma debe sonar solo si el sistema está armado **y** al menos uno de los tres sensores se activó. Además, si se activa el sensor de movimiento estando armado, debe mostrar un mensaje de "Alerta alta prioridad" en vez del mensaje normal.

### Ejercicio 16

Dado el rendimiento del carro (km por galón), la cantidad de combustible actual en el tanque (galones) y la distancia del viaje (km), determinar si el carro llega sin reabastecer. Si no llega, calcular cuántos galones adicionales se necesitan y, si esos galones cuestan más de $60.000 en total, mostrar una advertencia de presupuesto.

### Ejercicio 17

El precio de una boleta de cine depende de la edad (Niño <12, Adulto 12–59, Adulto mayor ≥60) con tarifas de $8.000, $14.000 y $9.000 respectivamente. Si el día de la compra es miércoles, aplica una promoción 2x1 (se cobra una sola boleta por cada dos). Calcular el valor a pagar por una persona.

### Ejercicio 18

Dado un número entero, indicar si es positivo, negativo o cero; si es par o impar; y si es múltiplo de 3 y de 5 al mismo tiempo, mostrar un mensaje especial adicional ("¡Múltiplo de 15!"). Un mismo número puede activar varios mensajes a la vez.

### Ejercicio 19

Un banco aprueba un préstamo si el historial crediticio es "Bueno" y la relación deuda/ingreso (deudas mensuales ÷ ingresos mensuales) es menor al 40%. Si el historial es "Malo", se rechaza sin importar el resto. Si el historial es "Regular", se aprueba solo si la relación deuda/ingreso es menor al 20% **y** el ingreso mensual supera $3.000.000.

### Ejercicio 20

Una tienda ajusta el monto de una compra según el método de pago: efectivo (-5%), débito (sin cambio), o crédito (+3% si el monto es menor a $100.000, +1.5% si es mayor o igual). Si el cliente es afiliado al programa de lealtad, se resta un 2% adicional al total, sin importar el método de pago. Calcular el monto final.