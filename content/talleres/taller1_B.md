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

# 📄 Taller — Pruebas de Escritorio

Programación I

:::{note}
Este taller se resuelve a mano: construye la tabla de seguimiento completa para cada algoritmo, con los valores de entrada indicados. Sube una foto legible de tu solución.
:::

### Ejercicio 1 — Secuencial

```
Algoritmo EjercicioABC
	Definir a, b, c Como Entero
	a <- 5
	b <- 3
	c <- a + b
	a <- b
	b <- c - a
	c <- a * b
	Escribir a, " ", b, " ", c
FinAlgoritmo
```

Realiza la prueba de escritorio completa. No hay ningún contexto que te diga qué esperar — solo la tabla, instrucción por instrucción, te dirá los valores finales de `a`, `b` y `c`.

### Ejercicio 2 — Secuencial (varios pasos)

```
Algoritmo CalculoFactura
	Definir precio, cantidad, subtotal, iva, total Como Real
	Leer precio, cantidad
	subtotal <- precio * cantidad
	iva <- subtotal * 0.19
	total <- subtotal + iva
	Escribir total
FinAlgoritmo
```

Realiza la prueba de escritorio para `precio = 10000` y `cantidad = 3`.

### Ejercicio 3 — Con una decisión

```
Algoritmo ParImpar
	Definir num Como Entero
	Leer num
	Si (num MOD 2 = 0) Entonces
		Escribir "Par"
	SiNo
		Escribir "Impar"
	FinSi
FinAlgoritmo
```

Realiza **dos** pruebas de escritorio distintas: una para `num = 7` y otra para `num = 8`, de forma que quede recorrida cada una de las dos ramas.

### Ejercicio 4 — Con una decisión

```
Algoritmo AprobacionMateria
	Definir nota Como Real
	Leer nota
	Si (nota >= 3.0) Entonces
		Escribir "Aprobó"
	SiNo
		Escribir "Reprobó"
	FinSi
FinAlgoritmo
```

Realiza **dos** pruebas de escritorio: una para `nota = 2.5` y otra para `nota = 4.2`.

### Ejercicio 5 — Con un ciclo `Para`

```
Algoritmo Factorial
	Definir i, n, producto Como Entero
	Leer n
	producto <- 1
	Para i <- 1 Hasta n Con Paso 1 Hacer
		producto <- producto * i
	FinPara
	Escribir producto
FinAlgoritmo
```

Realiza la prueba de escritorio para `n = 4`, mostrando cada vuelta del ciclo como una fila de la tabla.

### Ejercicio 6 — Ciclo `Para` con una decisión adentro

```
Algoritmo ContarPares
	Definir i, contador Como Entero
	contador <- 0
	Para i <- 1 Hasta 10 Con Paso 1 Hacer
		Si (i MOD 2 = 0) Entonces
			contador <- contador + 1
		FinSi
	FinPara
	Escribir contador
FinAlgoritmo
```

Realiza la prueba de escritorio completa (10 vueltas del ciclo).

### Ejercicio 7 — Ciclo `Mientras`

```
Algoritmo Duplicar
	Definir valor, veces Como Entero
	Leer valor
	veces <- 0
	Mientras valor <= 50 Hacer
		valor <- valor * 2
		veces <- veces + 1
	FinMientras
	Escribir veces
FinAlgoritmo
```

Realiza la prueba de escritorio para `valor = 5`.

### Ejercicio 8 — Ciclo `Mientras` con centinela

```
Algoritmo SumaConCentinela
	Definir num, suma Como Entero
	suma <- 0
	Leer num
	Mientras num <> 0 Hacer
		suma <- suma + num
		Leer num
	FinMientras
	Escribir suma
FinAlgoritmo
```

Realiza la prueba de escritorio para la secuencia de entradas: `4, 6, 2, 0`.
