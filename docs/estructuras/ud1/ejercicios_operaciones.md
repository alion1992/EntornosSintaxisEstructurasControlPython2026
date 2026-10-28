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

    