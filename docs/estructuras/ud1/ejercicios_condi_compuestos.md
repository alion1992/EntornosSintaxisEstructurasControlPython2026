# Ejercicios: Operadores lógicos en Python

## Ejercicio 1. Acceso a una piscina

Una piscina municipal quiere crear un programa para controlar el acceso de sus visitantes.

El programa debe solicitar:

- Nombre del visitante.
- Edad.
- Si es socio de la piscina (`s` o `n`).

Las normas de acceso son las siguientes:

- Los menores de 12 años solamente pueden acceder si son socios.
- Las personas de 12 años o más pueden acceder independientemente de si son socias.

**Requisitos del programa:**

1. Solicita los datos del visitante.
2. Comprueba si puede acceder utilizando un operador lógico.
3. Muestra el nombre del visitante y si puede acceder o no.

**Pista:** necesitarás combinar `and` y `or`.

---

## Ejercicio 2. Descuentos en una tienda

Una tienda quiere crear un programa para calcular si un cliente tiene derecho a un descuento especial.

El programa debe solicitar:

- Nombre del cliente.
- Edad.
- Importe de la compra.

Las condiciones para obtener el descuento son:

- Los menores de 18 años tienen un descuento del 10 %.
- Las personas de 65 años o más también tienen un descuento del 10 %.
- Además, cualquier cliente que realice una compra superior a 100 € tiene un descuento del 15 %.

**Requisitos del programa:**

1. Solicita los datos del cliente.
2. Comprueba si tiene derecho a algún descuento.
3. Si tiene descuento por edad, aplica un 10 %.
4. Si su compra supera los 100 €, aplica un 15 %.
5. Si no cumple ninguna condición, no tiene descuento.
6. Muestra el importe inicial, el descuento aplicado y el importe final.

**Pista:** utiliza `or` para comprobar las condiciones de edad y `elif` para distinguir los descuentos.

---

## Ejercicio 3. Control de acceso a un gimnasio

Un gimnasio quiere controlar el acceso de sus clientes.

El programa debe solicitar:

- Nombre del usuario.
- Edad.
- Si tiene una cuota activa (`s` o `n`).
- Si tiene una autorización especial (`s` o `n`).

Las normas de acceso son:

- Para acceder normalmente es obligatorio tener una cuota activa.
- Los menores de 16 años no pueden acceder.
- Los usuarios que tengan una autorización especial pueden acceder aunque no tengan una cuota activa, pero siempre deben tener 16 años o más.

**Requisitos del programa:**

1. Solicita todos los datos.
2. Comprueba si el usuario puede acceder.
3. Muestra un mensaje indicando si tiene permitido el acceso.

**Pista:** necesitarás combinar `and`, `or` y paréntesis.

---

## Ejercicio 4. Sistema de concesión de becas 

Un centro educativo quiere desarrollar un programa en Python para determinar qué tipo de beca puede recibir un alumno.

El programa debe solicitar los siguientes datos:

- Nombre del alumno.
- Nota media del curso.
- Renta familiar anual.
- Porcentaje de asistencia a clase.
- Si pertenece a una familia numerosa (s o n).

El centro establece las siguientes condiciones:

1. Beca de excelencia

El alumno obtiene esta beca si cumple todas estas condiciones:  

- Tiene una nota media igual o superior a 9.
- Tiene una asistencia igual o superior al 90 %.
- Su renta familiar es inferior a 30.000 €.

2. Beca general

Si no cumple los requisitos de la beca de excelencia, podrá obtener la beca general si:  

- Tiene una nota media igual o superior a 6,5.
- Tiene una asistencia igual o superior al 80 %.
- Además, cumple al menos una de estas condiciones:  

  1. Su renta familiar es inferior a 20.000 €.
  2. Pertenece a una familia numerosa.

- Sin beca

Si no cumple ninguna de las condiciones anteriores, no obtiene ninguna beca.

Requisitos del programa:  

1. Solicita todos los datos al usuario.
2. Comprueba si tiene derecho a una beca de excelencia.
3. Si no cumple los requisitos, comprueba si puede obtener una beca general.
4. Si tampoco cumple esos requisitos, indica que no tiene derecho a ninguna beca.
5. Muestra el nombre del alumno y el tipo de beca obtenido.