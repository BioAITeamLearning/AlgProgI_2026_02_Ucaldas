# 📝 Pruebas de Escritorio

Antes de tener una computadora para ejecutar un algoritmo, hay una forma de comprobar si funciona: simularlo a mano, línea por línea, anotando en una tabla cómo cambia cada variable. Eso es una **prueba de escritorio** (o tabla de seguimiento).

```{admonition} ¿Para qué sirve?
:class: note
Te permite encontrar errores de lógica antes de programar, y te obliga a entender exactamente qué hace cada instrucción — no lo que crees que hace.
```

## Cómo se construye la tabla

1. Una columna por cada variable del algoritmo (en el orden en que aparecen).
2. Una fila por cada instrucción que se ejecuta (no por cada línea escrita — si una línea no se ejecuta, no tiene fila).
3. Cuando una variable cambia de valor, se anota el nuevo valor en su columna; si no cambió, se repite el valor anterior o se deja igual.
4. Si el algoritmo tiene una decisión (`Si-Entonces-SiNo`), la tabla **solo sigue el camino que realmente se toma** según los valores de esa prueba — el otro camino no aparece.
5. Si el algoritmo tiene un ciclo, cada vuelta del ciclo es una fila (o un grupo de filas) nueva.

## Ejemplo 1 — Algoritmo secuencial

```
Algoritmo AreaCirculo
	Definir radio, area Como Real
	Leer radio
	area <- 3.1416 * radio^2
	Escribir "El área es: ", area
FinAlgoritmo
```

Prueba de escritorio para `radio = 5`:

| Instrucción | radio | area | Salida |
|---|---|---|---|
| Leer radio | 5 | — | |
| area <- 3.1416 * radio^2 | 5 | 78.54 | |
| Escribir area | 5 | 78.54 | El área es: 78.54 |

## Ejemplo 2 — Algoritmo con una decisión

Aquí no hay ningún contexto del mundo real que te dé pistas del resultado — solo puedes saberlo siguiendo la tabla con cuidado, instrucción por instrucción.

```
Algoritmo EjemploPQR
	Definir p, q, r Como Entero
	p <- 8
	q <- 3
	r <- p - q
	Si r > q Entonces
		p <- r
	SiNo
		p <- q
		q <- r
	FinSi
	r <- p + q
	Escribir p, " ", q, " ", r
FinAlgoritmo
```

Prueba de escritorio:

| Instrucción | p | q | r |
|---|---|---|---|
| p <- 8 | 8 | — | — |
| q <- 3 | 8 | 3 | — |
| r <- p - q | 8 | 3 | 5 |
| Si r > q (¿5 > 3?) → Verdadero | 8 | 3 | 5 |
| p <- r | 5 | 3 | 5 |
| r <- p + q | 5 | 3 | 8 |
| Escribir p, q, r | 5 | 3 | 8 |

```{admonition} Importante
:class: warning
Esta tabla solo prueba el caso donde `r > q` es verdadero (rama Entonces). Para confiar en que el algoritmo completo funciona, hace falta **otra** prueba de escritorio con valores iniciales donde la condición sea falsa, para recorrer también la rama SiNo — por ejemplo empezando con `p <- 2` y `q <- 6`.
```

## Ejemplo 3 — Algoritmo con un ciclo

```
Algoritmo SumaHasta5
	Definir i, suma Como Entero
	suma <- 0
	Para i <- 1 Hasta 5 Con Paso 1 Hacer
		suma <- suma + i
	FinPara
	Escribir "Suma: ", suma
FinAlgoritmo
```

Prueba de escritorio (cada vuelta del ciclo es una fila):

| Iteración | i | suma |
|---|---|---|
| Inicio | — | 0 |
| 1 | 1 | 1 |
| 2 | 2 | 3 |
| 3 | 3 | 6 |
| 4 | 4 | 10 |
| 5 | 5 | 15 |

Salida: `Suma: 15`

```{admonition} Siguiente paso
:class: tip
Ahora practica construyendo tú mismo estas tablas: [Taller — Pruebas de Escritorio](../../talleres/taller1_B.md).
```
