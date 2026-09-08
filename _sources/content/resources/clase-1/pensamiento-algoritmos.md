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

Una biblioteca presta libros a sus estudiantes. Cuando alguien lleva un libro al mostrador, el bibliotecario primero revisa si el libro está disponible o si ya está prestado. Si está disponible, revisa si el estudiante tiene préstamos vencidos de otras veces; si los tiene, no puede llevarse el libro hasta que los devuelva. Si no tiene préstamos vencidos, el bibliotecario mira si el libro pertenece a la sección de "solo consulta en sala" (libros de reserva, diccionarios, enciclopedias); esos nunca salen del edificio, sin importar quién los pida. Si el libro sí puede prestarse, se registra el préstamo y se le indica al estudiante la fecha de devolución.

### Ejercicio 7

En la recepción de un consultorio médico llegan pacientes durante toda la mañana. La recepcionista primero pregunta si el paciente tiene cita programada para ese día. Si no la tiene, pregunta si se trata de una urgencia; las urgencias pasan de inmediato donde el médico de turno, sin importar que haya otros pacientes esperando. Si no es urgencia y no tiene cita, se le ofrece agendar para otro día. Si el paciente sí tiene cita, la recepcionista verifica si llegó a tiempo o llegó tarde; si llegó más de 15 minutos tarde, pierde el turno y debe reprogramar; si llegó a tiempo, se confirma si está afiliado a una EPS o si es particular, porque eso cambia el formulario que debe diligenciar antes de pasar a la sala de espera.

### Ejercicio 8

Un mesero en un restaurante debe tomar el pedido de una mesa siguiendo un orden. Primero pregunta si algún comensal tiene alguna alergia o restricción alimentaria, porque eso determina qué platos del menú puede ofrecer. Luego toma el pedido de entradas, si la mesa desea alguna. Después pregunta si prefieren el plato fuerte servido de inmediato o esperar a que todos terminen la entrada antes de traerlo. Al final pregunta por bebidas, y si alguien pide una bebida alcohólica, el mesero debe confirmar que la persona sea mayor de edad antes de anotar ese pedido; si no puede confirmarlo, ofrece solo bebidas sin alcohol a esa persona.

### Ejercicio 9

Una veterinaria recibe mascotas que llegan sin cita. La recepcionista de la clínica pregunta primero qué tipo de animal es (perro, gato u otro), porque hay consultorios separados según el tipo. Luego pregunta si la mascota está sangrando, con dificultad para respirar, o inconsciente; cualquiera de esas señales hace que pase directamente a urgencias, saltándose la fila. Si no presenta ninguna de esas señales, se pregunta si es la primera vez que la mascota visita esa veterinaria; si es la primera vez, se debe abrir una historia clínica antes de pasar a consulta. Si ya tiene historia clínica, se pregunta el motivo de la visita (vacunación, control, o síntoma de enfermedad) para decidir a qué consultorio se dirige.

### Ejercicio 10

Una persona necesita organizar la basura de su casa antes de sacarla. Por cada objeto que va a botar, primero debe fijarse si está mojado o sucio con comida; si es así, va directo a la bolsa de orgánicos, sin importar de qué material esté hecho. Si está limpio y seco, debe identificar el material principal (papel/cartón, plástico o vidrio/metal) para saber a cuál bolsa de reciclaje va. Si el objeto es algo peligroso (pilas, medicamentos vencidos, bombillas rotas), no va en ninguna de las bolsas anteriores, sino que se aparta para llevarlo a un punto de recolección especial, incluso si está limpio y sería reciclable.

## Tarea

```{admonition} Para entregar
:class: important
Para cada ejercicio: identifica Entradas, Salida(s) y Proceso, escribe los pasos en orden (usando bifurcaciones donde el proceso se divida en caminos distintos) y dibuja el diagrama de flujo. Todavía no uses la sintaxis formal de PSeInt (`Si-Entonces-SiNo`) ni operadores lógicos (`Y`, `O`) — descríbelo con tus propias palabras, como en el ejemplo del pastel.
```

### Ejercicio 11

Un cajero de banco atiende clientes en ventanilla. Primero pide la cédula y verifica si la persona es cuentahabiente del banco. Si no lo es, solo puede hacer un giro o cambiar un cheque, nada más. Si es cuentahabiente, pregunta qué operación quiere hacer (retiro, consignación, o transferencia). En un retiro, revisa si hay fondos suficientes en la cuenta antes de entregar el dinero; si el monto es muy alto (más de cierto límite que el banco define), debe llamar al supervisor para que autorice antes de continuar.

### Ejercicio 12

Un profesor debe organizar la entrega de exámenes al final del semestre. Primero separa los exámenes por grupo (mañana o tarde). Dentro de cada grupo, revisa si el estudiante presentó el examen o no; si no lo presentó, aparta ese examen porque debe presentar uno especial después. Si sí lo presentó, revisa si la nota es reprobatoria; si es reprobatoria, aparta el examen en un montón distinto para citar al estudiante a una revisión. Los exámenes aprobados se organizan de mayor a menor nota antes de ser devueltos.

### Ejercicio 13

Una persona quiere organizar su clóset por temporada. Por cada prenda que saca, primero decide si es de temporada actual o no; si no lo es, la guarda directamente en una caja de almacenamiento. Si es de temporada, revisa si la prenda tiene alguna mancha o daño; si tiene daño, la separa para lavarla o repararla antes de guardarla en el clóset. Si está en buen estado, decide en qué sección del clóset va según el tipo de prenda (arriba, abajo, colgado).

### Ejercicio 14

Un semáforo peatonal inteligente decide cuándo cambiar de color. Normalmente el semáforo vehicular está en verde y el peatonal en rojo. Cuando un peatón presiona el botón, el sistema espera a que termine el ciclo actual del semáforo vehicular. Si en ese momento se acerca una ambulancia con la sirena encendida, el sistema cancela el cambio y mantiene el semáforo vehicular en verde hasta que la ambulancia pase. Si no hay ninguna emergencia, el semáforo vehicular cambia a rojo, el peatonal cambia a verde durante un tiempo fijo, y luego vuelve a la normalidad.

### Ejercicio 15

Una persona llega al aeropuerto para hacer el check-in de su vuelo. Primero el sistema revisa si el vuelo todavía admite check-in (algunos vuelos cierran el check-in cierto tiempo antes de salir); si ya cerró, la persona debe ir directamente al mostrador de atención especial. Si el check-in sigue abierto, se pregunta si el pasajero lleva equipaje para despachar; si lleva, se pesa la maleta y se revisa si excede el límite permitido, en cuyo caso debe pagar un excedente antes de continuar. Al final, si el pasajero pidió un asiento en una fila de salida de emergencia, se le pregunta si está en condiciones de ayudar en una evacuación; si dice que no, se le reasigna a otro asiento.

### Ejercicio 16

Un cajero automático (ATM) atiende una transacción. Primero pide la tarjeta y la clave; si la clave es incorrecta, da otra oportunidad, pero si falla tres veces seguidas, retiene la tarjeta y termina la operación. Si la clave es correcta, muestra las opciones (retiro, consulta de saldo, cambio de clave). En un retiro, pregunta el monto y revisa si el cajero tiene suficientes billetes de las denominaciones necesarias para entregar esa cantidad exacta; si no puede entregar el monto exacto, le pide a la persona que elija otro monto.

### Ejercicio 17

Una persona quiere regar las plantas de su casa. Por cada planta, primero toca la tierra para sentir si está seca o húmeda; si está húmeda, no la riega y pasa a la siguiente. Si está seca, revisa qué tipo de planta es, porque las sensibles al sol directo se riegan por la tarde y las demás se pueden regar en cualquier momento del día. Si al regar nota que el agua no se absorbe y se queda estancada en la superficie, revisa si la maceta tiene hueco de drenaje; si no lo tiene, aparta esa planta para cambiarla de maceta más tarde.

### Ejercicio 18

En un supermercado, la caja de autoservicio debe procesar los productos que el cliente va pasando. Por cada producto, el sistema identifica si requiere verificación de edad (como licor o cigarrillos); si la requiere, se enciende una luz para que un empleado se acerque a confirmar la edad del cliente antes de continuar. Si el producto es una fruta o verdura sin código de barras, el sistema espera a que el cliente la seleccione de una lista en pantalla y la pese en la báscula. Al finalizar, si el cliente tiene una tarjeta de puntos registrada, el sistema pregunta si quiere acumularlos o redimirlos por un descuento en esa misma compra.

### Ejercicio 19

Un socorrista de primeros auxilios debe decidir cómo actuar cuando llega a atender a una persona. Primero verifica si la persona está consciente. Si no responde, revisa si respira; si no respira, debe iniciar maniobras de reanimación de inmediato y pedir que alguien llame a emergencias. Si respira pero no responde, la ubica en posición de recuperación y espera ayuda. Si la persona está consciente, le pregunta qué le pasó y si tiene alguna herida visible, sangrado, o dolor fuerte en algún lugar, para decidir cómo atenderla mientras llega ayuda especializada.

### Ejercicio 20

Un profesor de laboratorio debe distribuir a los estudiantes en grupos de trabajo para una práctica. Primero revisa la lista de asistencia y separa a quienes llegaron tarde, porque ellos entran a un grupo aparte con instrucciones adicionales. A los que llegaron a tiempo, los organiza según si ya trabajaron juntos en una práctica anterior; si ya trabajaron juntos, intenta separarlos en distintos grupos para que conozcan otros compañeros. Si un grupo queda con un número impar de estudiantes al final, el profesor decide si agregarlo a otro grupo o dejarlo trabajar con uno menos, dependiendo de qué tan compleja sea la práctica de ese día.