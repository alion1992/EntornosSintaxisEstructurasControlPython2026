# Ejercicios de Python: entrada de datos y operaciones

## Ejercicio 1. Presupuesto de reparación de un coche

Desarrolla un programa en Python que solicite al usuario los siguientes
datos:

-   Nombre.
-   Apellido.
-   Precio del aceite de coche.
-   Precio de los inyectores.
-   Precio de las bujías.
-   Precio del filtro del habitáculo.

Cuando el usuario haya introducido todos los datos, el programa debe
mostrar por pantalla:

1.  El nombre y el apellido del usuario.
2.  El precio total de todos los productos, sin IVA.
3.  El precio total con el IVA del 21 % incluido.

**Importante:** Los precios deben poder introducirse con decimales.

### Ejemplo orientativo

``` text
Introduce tu nombre: Ana
Introduce tu apellido: López
Precio del aceite de coche: 45.50
Precio de los inyectores: 120
Precio de las bujías: 32.90
Precio del filtro del habitáculo: 18.60

Cliente: Ana López
Precio total sin IVA: 217.00 €
Precio total con IVA (21 %): 262.57 €
```

*Los valores del ejemplo son orientativos. Tu programa debe calcular los
resultados a partir de los datos introducidos por el usuario.*

------------------------------------------------------------------------

## Ejercicio 2. Compra en el supermercado

Imagina que tienes **200 euros** en tu cuenta corriente y vas a hacer la
compra en el supermercado.

Desarrolla un programa en Python que:

1.  Inicialice el saldo de la cuenta corriente en **200 euros**.
2.  Pregunte el precio de los siguientes cuatro productos:
    -   Una docena de huevos.
    -   Una caja de helados.
    -   Una barra de pan.
    -   Un racimo de uvas.
3.  Reste del saldo inicial el precio de cada producto.
4.  Cuando el usuario haya introducido el precio del último producto,
    muestre el **saldo final** que queda en la cuenta corriente.

**Importante:** Los precios pueden contener decimales. Para este
ejercicio, puedes suponer que hay saldo suficiente para pagar todos los
productos.

### Ejemplo orientativo

``` text
Saldo inicial: 200.00 €
Precio de una docena de huevos: 3.20
Precio de una caja de helados: 5.50
Precio de una barra de pan: 1.10
Precio de un racimo de uvas: 4.80

Saldo final en la cuenta corriente: 185.40 €
```

*Los valores del ejemplo son orientativos. El programa debe calcular el
saldo final utilizando los precios introducidos por el usuario.*

??? tip " Ampliación del ejercicio 2: IVA por producto"

    Cuando termines el ejercicio básico, añade una mejora al programa.

    Aplica los siguientes tipos de IVA:

    | Producto | IVA |
    |---|---:|
    | Una docena de huevos | 10 % |
    | Una caja de helados | 21 % |
    | Una barra de pan | 10 % |
    | Un racimo de uvas | 21 % |

    **Nuevos requisitos:**

    1. Añade un menú para elegir si se quiere calcular la compra con IVA.
    2. Calcula el precio de cada producto con su IVA incluido.
    3. Muestra el importe total de la compra.
    4. Calcula el saldo final después de pagar.

# Ejercicio 3. Entradas para un parque de atracciones

## Enunciado

Un parque de atracciones quiere crear un programa para calcular cuánto
debe pagar una persona por su entrada.

El programa debe pedir los siguientes datos:

-   Nombre del visitante.
-   Edad del visitante.
-   Si quiere añadir un menú de comida. El usuario responderá `s` si
    quiere menú o `n` si no lo quiere.

El precio de la entrada depende de la edad:

-   Menores de 4 años: entrada gratuita.
-   Desde los 4 hasta los 12 años, ambos incluidos: descuento del 30 %
    sobre el precio normal.
-   Mayores de 12 años y menores de 65: pagan el precio normal.
-   Personas de 65 años o más: descuento del 20 % sobre el precio
    normal.

El precio normal de la entrada es de **30 €**.

Si el visitante quiere menú, se añadirán **8 €** al importe final. El
precio del menú no tiene descuento.

### Requisitos del programa

1.  Solicita el nombre y la edad del visitante.
2.  Calcula el precio de la entrada según la edad.
3.  Pregunta si quiere añadir un menú.
4.  Si responde `s`, añade 8 € al precio calculado.
5.  Si responde `n`, no añade ningún importe.
6.  Muestra el nombre del visitante, el precio de la entrada, el coste
    del menú y el importe total que debe pagar.

**Condiciones:** resuelve las decisiones utilizando únicamente `if` y
`else`. No utilices `elif`. Puedes utilizar condicionales anidados, es
decir, escribir un `if` dentro de un `else`.

Para este ejercicio, puedes suponer que el usuario introduce una edad
válida y responde `s` o `n` cuando se le pregunta por el menú.

------------------------------------------------------------------------

## Ejemplo orientativo 1

``` text
Introduce tu nombre: Lucía
Introduce tu edad: 10
¿Quieres añadir un menú por 8 euros? (s/n): s

Visitante: Lucía
Precio de la entrada: 21.00 €
Precio del menú: 8.00 €
Total a pagar: 29.00 €
```

## Ejemplo orientativo 2

``` text
Introduce tu nombre: Manuel
Introduce tu edad: 70
¿Quieres añadir un menú por 8 euros? (s/n): n

Visitante: Manuel
Precio de la entrada: 24.00 €
Precio del menú: 0.00 €
Total a pagar: 24.00 €
```



------------------------------------------------------------------------

??? tip " Ampliación opcional"

    Añade una pregunta para saber si el visitante quiere comprar una foto de recuerdo por **5 €**.

    - Si responde `s`, añade 5 € al total.
    - Si responde `n`, no añadas nada.

    Actualiza el resumen final para mostrar el precio de la foto y el nuevo total.

    
    