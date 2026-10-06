# UD1. Ejercicios: Estructuras de control en Python

> **Módulo:** 5099. Estructuras de control en Python  
> **Unidad Didáctica:** UD1. Estructuras de control en Python  
> **RA trabajados:** RA1, RA2 y RA3  
> **Nivel:** Curso de Especialización en Desarrollo de Aplicaciones en Python

---

## 📑 Índice

- [1. Recomendaciones](#1-recomendaciones)
- [2. Ejercicios de secuencia](#2-ejercicios-de-secuencia)
- [3. Ejercicios de selección](#3-ejercicios-de-selección)
- [4. Ejercicios de estructuras condicionales](#4-ejercicios-de-estructuras-condicionales)
- [5. Ejercicios de bucles](#5-ejercicios-de-bucles)
- [6. Ejercicios combinando estructuras](#6-ejercicios-combinando-estructuras)
- [7. Retos](#7-retos)
- [8. Proyecto final](#8-proyecto-final)

---

# 1. Recomendaciones

Los ejercicios están organizados de menor a mayor dificultad.

Se recomienda resolverlos utilizando únicamente los conocimientos trabajados en la UD1:

- Variables.
- Tipos de datos básicos.
- Entrada y salida de datos.
- Operadores aritméticos.
- Operadores de comparación.
- Operadores lógicos.
- `if`, `elif` y `else`.
- `for`.
- `while`.
- `range()`.
- `break`.
- `continue`.
- Estructuras anidadas.

> **Importante:** en estos ejercicios todavía no es necesario utilizar funciones definidas por el alumnado.

---

# 2. Ejercicios de secuencia

## Ejercicio 1. Datos personales

Crea un programa que solicite:

- Nombre.
- Apellidos.
- Edad.
- Ciudad.

Después debe mostrar una frase similar a:

```text
Hola, me llamo Ana García, tengo 20 años y vivo en Puertollano.
```

---

## Ejercicio 2. Área y perímetro

Solicita la base y la altura de un rectángulo.

Calcula y muestra:

- Área.
- Perímetro.

Ejemplo:

```text
Base: 10
Altura: 5

Área: 50
Perímetro: 30
```

---

## Ejercicio 3. Conversor de euros

Solicita una cantidad en euros y muestra su equivalente en dólares.

Utiliza un tipo de cambio almacenado en una variable.

```text
Euros: 100
Tipo de cambio: 1.08

Resultado: 108 dólares
```

---

## Ejercicio 4. Conversor de temperatura

Solicita una temperatura en grados Celsius y conviértela a Fahrenheit.

Fórmula:

```text
F = C × 9 / 5 + 32
```

---

## Ejercicio 5. Precio final

Solicita:

- Precio de un producto.
- Porcentaje de IVA.

Calcula:

- Importe del IVA.
- Precio final.

Ejemplo:

```text
Precio: 100
IVA: 21

IVA: 21 €
Precio final: 121 €
```

---

## Ejercicio 6. Tiempo

Solicita una cantidad de segundos y conviértela a:

- Horas.
- Minutos.
- Segundos.

Ejemplo:

```text
Segundos: 3672

1 hora
1 minuto
12 segundos
```

---

# 3. Ejercicios de selección

## Ejercicio 7. Mayor de edad

Solicita la edad de una persona.

Muestra:

```text
Eres mayor de edad
```

o:

```text
Eres menor de edad
```

---

## Ejercicio 8. Número positivo o negativo

Solicita un número e indica si es:

- Positivo.
- Negativo.
- Cero.

---

## Ejercicio 9. Número par o impar

Solicita un número entero e indica si es par o impar.

**Pista:** utiliza el operador `%`.

---

## Ejercicio 10. Mayor de dos números

Solicita dos números e indica:

- Cuál es mayor.
- Si son iguales.

Ejemplo:

```text
Número 1: 15
Número 2: 20

El segundo número es mayor.
```

---

## Ejercicio 11. Mayor de tres números

Solicita tres números y muestra cuál es el mayor.

No utilices `max()`.

---

## Ejercicio 12. Calificación

Solicita una nota entre 0 y 10.

Muestra:

| Nota | Resultado |
|---|---|
| < 5 | Suspenso |
| 5 - 6.9 | Aprobado |
| 7 - 8.9 | Notable |
| 9 - 10 | Sobresaliente |

Controla también que la nota esté dentro del rango válido.

---

## Ejercicio 13. Año bisiesto

Solicita un año e indica si es bisiesto.

Un año es bisiesto cuando:

- Es divisible entre 4.
- No es divisible entre 100, salvo que también sea divisible entre 400.

Ejemplos:

```text
2024 → Bisiesto
2025 → No bisiesto
2000 → Bisiesto
1900 → No bisiesto
```

---

## Ejercicio 14. Calculadora

Solicita:

- Primer número.
- Segundo número.
- Operación.

Las operaciones disponibles serán:

```text
+
-
*
/
```

Muestra el resultado correspondiente.

Controla la división entre cero.

---

# 4. Ejercicios de estructuras condicionales

## Ejercicio 15. Descuento en una tienda

Una tienda aplica los siguientes descuentos:

- Menos de 50 € → sin descuento.
- De 50 € a 99.99 € → 5%.
- De 100 € a 199.99 € → 10%.
- 200 € o más → 15%.

Solicita el precio y muestra:

- Descuento aplicado.
- Importe descontado.
- Precio final.

---

## Ejercicio 16. Acceso a una aplicación

Solicita:

```text
Usuario
Contraseña
```

Los datos correctos serán:

```text
Usuario: admin
Contraseña: python123
```

Si ambos son correctos:

```text
Acceso permitido
```

En caso contrario:

```text
Usuario o contraseña incorrectos
```

---

## Ejercicio 17. Acceso con condiciones

Para acceder a una instalación se deben cumplir las siguientes condiciones:

- Tener al menos 18 años.
- Tener entrada válida.

Solicita ambos datos y determina si puede acceder.

Ejemplo:

```text
Edad: 20
Entrada válida: si

Acceso permitido
```

---

## Ejercicio 18. Clasificación por edad

Solicita la edad e indica:

```text
0-12     → Niño/a
13-17    → Adolescente
18-64    → Adulto/a
65+      → Persona mayor
```

Controla valores negativos.

---

## Ejercicio 19. Horario de apertura

Solicita una hora entre 0 y 23.

El establecimiento está abierto:

```text
09:00 - 14:00
16:00 - 20:00
```

Indica si está abierto o cerrado.

---

## Ejercicio 20. Precio de entrada

Un museo tiene estas tarifas:

```text
Menores de 5 años → Gratis
5-12 años         → 5 €
13-17 años        → 8 €
Adultos           → 12 €
Mayores de 65     → 6 €
```

Solicita la edad y muestra el precio.

---

# 5. Ejercicios de bucles

## Ejercicio 21. Números del 1 al 100

Muestra por pantalla los números del 1 al 100 utilizando un `for`.

---

## Ejercicio 22. Números pares

Muestra todos los números pares entre 1 y 100.

Utiliza un bucle.

---

## Ejercicio 23. Números impares

Muestra todos los números impares entre 1 y 100.

---

## Ejercicio 24. Cuenta atrás

Solicita un número y realiza una cuenta atrás hasta llegar a cero.

Ejemplo:

```text
Número: 5

5
4
3
2
1
0
```

---

## Ejercicio 25. Tabla de multiplicar

Solicita un número y muestra su tabla de multiplicar del 1 al 10.

Ejemplo:

```text
Número: 7

7 x 1 = 7
7 x 2 = 14
...
7 x 10 = 70
```

---

## Ejercicio 26. Suma de números

Calcula la suma de los números del 1 al 100.

Resultado esperado:

```text
5050
```

---

## Ejercicio 27. Suma de pares

Calcula la suma de todos los números pares entre 1 y 100.

---

## Ejercicio 28. Contar múltiplos

Solicita un número y muestra todos sus múltiplos entre 1 y 100.

Ejemplo:

```text
Número: 7

7
14
21
28
...
98
```

---

## Ejercicio 29. Factorial

Solicita un número entero positivo y calcula su factorial.

Ejemplo:

```text
5! = 120
```

No utilices ninguna función de librería.

---

## Ejercicio 30. Potencias

Solicita una base y un exponente.

Calcula la potencia utilizando un bucle.

No utilices `**`.

Ejemplo:

```text
Base: 2
Exponente: 5

Resultado: 32
```

---

# 6. Ejercicios combinando estructuras

## Ejercicio 31. Adivina el número

El programa tendrá almacenado un número secreto.

El usuario debe intentar adivinarlo.

Después de cada intento se mostrará:

```text
El número secreto es mayor.
```

o:

```text
El número secreto es menor.
```

Cuando acierte:

```text
¡Correcto!
```

Cuenta también el número de intentos.

---

## Ejercicio 32. Contraseña con tres intentos

Solicita usuario y contraseña.

El usuario tendrá un máximo de tres intentos.

Si los datos son correctos:

```text
Acceso permitido
```

Si falla tres veces:

```text
Cuenta bloqueada
```

Utiliza un `while`.

---

## Ejercicio 33. Suma hasta cero

Solicita números al usuario hasta que introduzca `0`.

Al finalizar muestra:

- Cantidad de números introducidos.
- Suma.
- Media.

Ejemplo:

```text
Número: 10
Número: 20
Número: 30
Número: 0

Cantidad: 3
Suma: 60
Media: 20
```

---

## Ejercicio 34. Contar positivos y negativos

Solicita números hasta introducir `0`.

Al finalizar muestra:

```text
Positivos: X
Negativos: Y
```

Los ceros no deben contabilizarse.

---

## Ejercicio 35. Máximo y mínimo

Solicita números hasta que el usuario introduzca `0`.

Al finalizar muestra:

- Número mayor.
- Número menor.

No utilices `max()` ni `min()`.

---

## Ejercicio 36. Menú de operaciones

Crea un menú que se repita hasta seleccionar la opción `0`.

```text
===== CALCULADORA =====

1. Sumar
2. Restar
3. Multiplicar
4. Dividir
0. Salir
```

Cada opción debe solicitar los datos necesarios.

---

## Ejercicio 37. Cajero automático

Crea un pequeño cajero automático.

El saldo inicial será:

```python
saldo = 1000
```

El menú será:

```text
1. Consultar saldo
2. Ingresar dinero
3. Retirar dinero
4. Salir
```

Condiciones:

- No se puede retirar más dinero del disponible.
- No se pueden ingresar cantidades negativas.
- El menú debe repetirse hasta seleccionar `4`.

---

## Ejercicio 38. Registro de alumnos

Solicita el número de alumnos.

Para cada alumno pide:

- Nombre.
- Nota.

Al finalizar muestra:

- Número de aprobados.
- Número de suspensos.
- Nota media.
- Nota más alta.
- Nota más baja.

---

# 7. Retos

## Reto 39. Sistema de parking

Desarrolla un programa para gestionar un pequeño parking.

El programa tendrá:

```text
1. Registrar entrada
2. Registrar salida
3. Consultar plazas
4. Salir
```

El parking dispone de 20 plazas.

El programa debe:

- Aumentar las plazas ocupadas al registrar una entrada.
- Liberar una plaza al registrar una salida.
- Impedir entradas cuando el parking esté completo.
- Impedir salidas cuando no haya vehículos.
- Mostrar las plazas libres.

---

## Reto 40. Máquina expendedora

Simula una máquina expendedora.

Productos:

```text
1. Agua       1.00 €
2. Refresco   1.50 €
3. Café       1.20 €
4. Snack      1.80 €
```

El programa debe:

1. Mostrar el menú.
2. Solicitar producto.
3. Solicitar dinero.
4. Comprobar si es suficiente.
5. Calcular el cambio.
6. Mostrar un mensaje de compra.
7. Repetir el proceso hasta seleccionar salir.

---

## Reto 41. Sistema de votación

Crea un sistema de votación sencillo.

Las opciones serán:

```text
1. Python
2. Java
3. JavaScript
4. C++
0. Finalizar
```

Los usuarios podrán votar hasta seleccionar `0`.

Al finalizar muestra:

- Votos de cada opción.
- Total de votos.
- Opción ganadora.

---

## Reto 42. Juego de preguntas

Crea un pequeño concurso de preguntas.

El programa deberá realizar al menos cinco preguntas.

Por cada pregunta:

- Mostrar el enunciado.
- Mostrar varias opciones.
- Comprobar la respuesta.
- Incrementar la puntuación si es correcta.

Al finalizar:

```text
Puntuación: 4/5
```

---

# 8. Proyecto final

# 🚁 Proyecto: Control de vuelo simulado

En este proyecto vamos a aplicar las estructuras de control a un escenario relacionado con una de las aplicaciones que veremos posteriormente: la **programación de drones con Python**.

No será necesario disponer todavía de un dron físico.

El programa simulará el control básico de un dron.

## Requisitos

El programa deberá comenzar mostrando:

```text
=========================
     DRON PYTHON
=========================
```

Después mostrará un menú:

```text
1. Despegar
2. Avanzar
3. Retroceder
4. Girar a la derecha
5. Girar a la izquierda
6. Consultar batería
7. Aterrizar
0. Salir
```

## Condiciones

El dron comenzará con:

```python
bateria = 100
```

Y estará inicialmente en tierra.

El programa deberá controlar:

### Despegue

El dron solamente podrá despegar si:

```text
batería >= 20%
```

### Movimiento

Cada movimiento consumirá un porcentaje de batería.

Por ejemplo:

```text
Avanzar → -5%
Retroceder → -5%
Girar → -2%
```

### Batería

Cuando la batería sea inferior al 20%:

```text
ADVERTENCIA: batería baja
```

Cuando llegue al 0%:

```text
Batería agotada.
Aterrizaje de emergencia.
```

### Aterrizaje

El dron deberá estar en vuelo para poder aterrizar.

### Menú

El menú debe repetirse mediante un `while`.

### Condiciones

Utiliza `if`, `elif` y `else` para controlar las diferentes opciones.

### Repeticiones

Utiliza bucles cuando sean necesarios.

---

## Ejemplo de ejecución

```text
=========================
     DRON PYTHON
=========================

Batería: 100%
Estado: EN TIERRA

1. Despegar
2. Avanzar
3. Retroceder
4. Girar derecha
5. Girar izquierda
6. Consultar batería
7. Aterrizar
0. Salir

Opción: 1

Dron despegando...

Opción: 2

Avanzando...
Batería: 95%

Opción: 4

Girando a la derecha...
Batería: 93%

Opción: 6

Batería: 93%

Opción: 7

Aterrizando...

Opción: 0

Programa finalizado.
```

---

## ⭐ Ampliación

Para alumnado que termine antes:

1. Añade coordenadas `(x, y)` para representar la posición.
2. Haz que avanzar modifique la coordenada.
3. Permite girar 90 grados.
4. Registra los movimientos realizados.
5. Añade un modo de vuelo automático.
6. Permite introducir una ruta.
7. Comprueba que la batería sea suficiente antes de ejecutar una ruta.
8. Añade un límite de distancia.
9. Simula obstáculos.
10. Añade un aterrizaje automático cuando la batería sea baja.

---

# 📌 Relación con los RA

| Ejercicios | RA principal |
|---|---|
| 1-6 | RA1 – Secuencia |
| 7-20 | RA2 – Selección |
| 21-30 | RA3 – Iteración |
| 31-38 | RA1 + RA2 + RA3 |
| 39-42 | RA1 + RA2 + RA3 |
| Proyecto final | RA1 + RA2 + RA3 |

---

# 🎯 Objetivo final de la UD

Al finalizar estos ejercicios, el alumnado deberá ser capaz de:

- Comprender el flujo de ejecución de un programa.
- Utilizar estructuras secuenciales.
- Tomar decisiones mediante condiciones.
- Combinar condiciones utilizando operadores lógicos.
- Utilizar `if`, `elif` y `else`.
- Crear bucles `for` y `while`.
- Utilizar `range()`.
- Controlar bucles mediante `break` y `continue`.
- Combinar estructuras de control.
- Resolver problemas mediante algoritmos.
- Representar soluciones mediante diagramas de flujo.
- Aplicar las estructuras de control a problemas reales.
- Preparar programas que posteriormente puedan aplicarse al desarrollo web y a la programación de drones con Python.
