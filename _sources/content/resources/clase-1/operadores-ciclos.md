# 🔁 Operadores Lógicos y Ciclos

Hasta ahora resolviste problemas con pasos secuenciales y con una sola decisión (`Si-Entonces-SiNo`). Aquí se agregan dos herramientas que se van a usar todo el semestre: **operadores lógicos** para combinar varias condiciones en una sola, y **ciclos** para repetir instrucciones sin tener que escribirlas una y otra vez.

## Operadores lógicos

Un operador lógico combina dos condiciones (o invierte una) y el resultado siempre es Verdadero o Falso.

| Operador | Símbolo en PSeInt | Es verdadero cuando... |
|---|---|---|
| Y (AND) | `Y` | **ambas** condiciones son verdaderas |
| O (OR) | `O` | **al menos una** de las condiciones es verdadera |
| NO (NOT) | `NO` | invierte el valor: si la condición era verdadera, la vuelve falsa (y viceversa) |

**Tabla de verdad de Y:**

| A | B | A Y B |
|---|---|---|
| Verdadero | Verdadero | Verdadero |
| Verdadero | Falso | Falso |
| Falso | Verdadero | Falso |
| Falso | Falso | Falso |

**Tabla de verdad de O:**

| A | B | A O B |
|---|---|---|
| Verdadero | Verdadero | Verdadero |
| Verdadero | Falso | Verdadero |
| Falso | Verdadero | Verdadero |
| Falso | Falso | Falso |

### Ejemplo resuelto — Año bisiesto

Un año es bisiesto si es divisible entre 4, **excepto** los divisibles entre 100, **salvo** que también sean divisibles entre 400.

```
Algoritmo AnioBisiesto
	Definir anio Como Entero
	Definir esBisiesto Como Logico
	Leer anio
	esBisiesto <- (anio MOD 4 = 0) Y ((anio MOD 100 <> 0) O (anio MOD 400 = 0))
	Si esBisiesto Entonces
		Escribir anio, " es bisiesto"
	SiNo
		Escribir anio, " no es bisiesto"
	FinSi
FinAlgoritmo
```

Fíjate cómo la condición combina un `Y` con un `O` anidado entre paréntesis — así como en una expresión matemática, los paréntesis definen qué se evalúa primero.

## Contadores y acumuladores

Ambos son variables que cambian dentro de un ciclo, pero cumplen funciones distintas:

| | Contador | Acumulador |
|---|---|---|
| **Para qué sirve** | Contar cuántas veces pasa algo | Ir sumando (o multiplicando) valores |
| **Cómo cambia** | Siempre en pasos fijos: `contador <- contador + 1` | En pasos variables: `acumulador <- acumulador + numero` |
| **Valor inicial típico** | 0 | 0 (para sumas) o 1 (para productos) |
| **Ejemplo de pregunta que responde** | "¿Cuántos números pares hay?" | "¿Cuánto suman los números pares?" |

### Ejemplo resuelto — Contador y acumulador juntos

Recorrer los números del 1 al 20 y, de los que son pares, contar cuántos hay y sumarlos.

```
Algoritmo ContarYSumarPares
	Definir i, contador, acumulador Como Entero
	contador <- 0
	acumulador <- 0
	Para i <- 1 Hasta 20 Con Paso 1 Hacer
		Si (i MOD 2 = 0) Entonces
			contador <- contador + 1
			acumulador <- acumulador + i
		FinSi
	FinPara
	Escribir "Pares encontrados: ", contador
	Escribir "Suma de esos pares: ", acumulador
FinAlgoritmo
```

## Ciclo `Para` (se sabe cuántas veces se repite)

Se usa cuando de antemano sabes cuántas veces se debe repetir algo (por ejemplo, "del 1 al 20").

```
Para <variable> <- <inicio> Hasta <fin> Con Paso <incremento> Hacer
	...instrucciones...
FinPara
```

## Ciclo `Mientras` (se repite hasta que una condición deje de cumplirse)

Se usa cuando **no** sabes de antemano cuántas veces se repetirá — depende de una condición, típicamente algo que el usuario escribe (un **centinela**: un valor especial que le indica al programa que debe parar).

```
Mientras <condición> Hacer
	...instrucciones...
FinMientras
```

### Ejemplo resuelto — Suma con centinela

Sumar los números que el usuario vaya ingresando, hasta que ingrese un 0.

```
Algoritmo SumaConCentinela
	Definir num, suma Como Entero
	suma <- 0
	Escribir "Ingrese números (0 para terminar):"
	Leer num
	Mientras num <> 0 Hacer
		suma <- suma + num
		Leer num
	FinMientras
	Escribir "Suma total: ", suma
FinAlgoritmo
```

## Banco de ejercicios

Resuelve cada uno en PSeInt: identifica Entradas, Salidas y Proceso, escribe el pseudocódigo y su diagrama de flujo.

### Operadores lógicos

**1.** Lee tres lados de un triángulo y determina si son válidos (la suma de cualquier par de lados debe ser mayor que el tercero — necesitas combinar tres comparaciones con `Y`).

**2.** Lee la edad y el promedio de un estudiante. Es elegible para una beca si tiene menos de 25 años **Y** su promedio es mayor o igual a 4.0.

**3.** Lee un número y determina si está fuera del rango [10, 20] (usa `NO` sobre la condición de "estar dentro del rango", o usa `O` directamente).

**4.** Lee un carácter y determina si es una vocal (a, e, i, o, u), combinando comparaciones con `O`.

**5.** Lee el estrato socioeconómico (1 a 6) y si la persona tiene hermanos estudiando (Verdadero/Falso). Aplica a un subsidio si el estrato es menor o igual a 2 **O** tiene hermanos estudiando, **Y** además su estrato no es mayor a 4.

### Contadores

**6.** Cuenta cuántos múltiplos de 5 hay entre 1 y 100.

**7.** Lee 10 números y cuenta cuántos son negativos.

**8.** Lee un número y cuenta cuántas veces se puede dividir entre 2 (usando la parte entera) hasta llegar a 1.

### Acumuladores

**9.** Suma los primeros N números naturales, donde N lo ingresa el usuario.

**10.** Calcula el factorial de un número N (producto de 1 a N).

**11.** Suma únicamente los números impares entre 1 y 50.

**12.** Lee las notas de 5 estudiantes y calcula el promedio.

### Contador y acumulador combinados

**13.** Lee 10 números y, en el mismo ciclo: cuenta cuántos son positivos y súmalos por separado.

**14.** Lee 10 números y cuenta por separado cuántos son pares y cuántos son impares (dos contadores).

### Ciclo `Mientras` y centinelas

**15.** Suma los números que el usuario ingrese, hasta que ingrese un número negativo.

**16.** Un usuario tiene máximo 3 intentos para adivinar una contraseña fija. Cuenta los intentos y determina si acertó o si se quedó sin intentos.

**17.** Calcula cuántas veces hay que duplicar $1.000 para superar $1.000.000.

**18.** Simula un menú simple: mientras el usuario no ingrese "salir", sigue preguntando qué operación quiere hacer (solo simula la pregunta y la repetición, no hace falta implementar cada operación).
