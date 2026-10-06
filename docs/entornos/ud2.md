# UD2. Fundamentos y nomenclatura en Python

> **Módulo Profesional 5098: Entornos y sintaxis en Python**  
> **Resultado de aprendizaje:** RA2. Elementos de la programación en Python

---

## 📑 Índice

- [1. Introducción](#1-introducción)
- [2. Python como lenguaje de programación](#2-python-como-lenguaje-de-programación)
- [3. Estructura básica de un programa](#3-estructura-básica-de-un-programa)
- [4. Nomenclatura en Python](#4-nomenclatura-en-python)
- [5. Convenciones habituales](#5-convenciones-habituales)
- [6. Palabras reservadas](#6-palabras-reservadas)
- [7. Comentarios y documentación](#7-comentarios-y-documentación)
- [8. Errores y depuración](#8-errores-y-depuración)
- [9. Buenas prácticas](#9-buenas-prácticas)


---

# 1. Introducción

Un programa no solo debe funcionar: también debe ser **legible, mantenible y fácil de modificar**.

En esta unidad aprenderemos las características básicas de Python y las principales convenciones utilizadas para escribir código claro y profesional.

Prestaremos especial atención a la **nomenclatura**, ya que utilizar nombres adecuados será fundamental en todas las unidades posteriores.

---

# 2. Python como lenguaje de programación

Python es un lenguaje de programación:

- De alto nivel.
- Interpretado.
- De propósito general.
- Multiplataforma.
- Orientado a objetos.
- Con una sintaxis sencilla y legible.
- Con una gran cantidad de librerías y frameworks.

Un programa Python puede ejecutarse directamente mediante el intérprete:

```python
print("Hola, mundo")
```

En CPython, el código fuente se transforma internamente en **bytecode** antes de ejecutarse en la máquina virtual de Python.

---

# 3. Estructura básica de un programa

Un programa sencillo puede contener:

```python
# Datos
nombre_usuario = "Ana"
edad_usuario = 25

# Procesamiento
es_mayor = edad_usuario >= 18

# Resultado
print(nombre_usuario)
print(es_mayor)
```

Podemos distinguir:

1. **Datos de entrada.**
2. **Procesamiento.**
3. **Salida de información.**

---

# 4. Nomenclatura en Python

La **nomenclatura** establece cómo debemos nombrar variables, funciones, clases y otros elementos del programa.

Un buen nombre debe:

- Ser descriptivo.
- Ser fácil de entender.
- Evitar abreviaturas innecesarias.
- Mantener un criterio coherente.
- Reflejar el contenido que representa.

### Poco recomendable

```python
x = 25
a = "Juan"
p = 19.95
```

### Recomendable

```python
edad_usuario = 25
nombre_usuario = "Juan"
precio_producto = 19.95
```

---

# 5. Convenciones habituales

## 5.1. Variables y funciones: `snake_case`

En Python se utiliza habitualmente **snake_case**.

```python
nombre_usuario = "Ana"
numero_alumnos = 25
precio_total = 125.50
```

Para funciones:

```python
calcular_precio()
mostrar_resultado()
obtener_usuario()
```

## 5.2. Clases: `PascalCase`

Los nombres de las clases utilizan normalmente **PascalCase**.

```python
class Usuario:
    pass
```

Otros ejemplos:

```python
class CuentaBancaria:
    pass

class Producto:
    pass
```

## 5.3. Constantes: `UPPER_CASE`

Las constantes se suelen escribir en mayúsculas utilizando guiones bajos.

```python
MAX_INTENTOS = 3
PI = 3.14159
PRECIO_IVA = 0.21
```

Python no impide modificar una constante, pero esta nomenclatura indica que su valor no debería cambiar.

---

# 6. Palabras reservadas

Python dispone de palabras que tienen un significado especial y que no podemos utilizar como nombres de variables.

Algunos ejemplos:

```text
if
else
elif
for
while
class
def
return
import
from
try
except
True
False
None
```

Por ejemplo, esto no es correcto:

```python
class = "Python"
```

`class` es una palabra reservada.

Podemos consultar las palabras reservadas mediante Python:

```python
import keyword

print(keyword.kwlist)
```

---

# 7. Comentarios y documentación

Los comentarios permiten añadir información al código que no será ejecutada.

```python
# Calculamos el precio final
precio_final = precio + iva
```

También podemos escribir:

```python
precio = 100  # Precio inicial
```

Los comentarios deben utilizarse para **aclarar aspectos relevantes**, no para explicar cada línea evidente.

## Docstrings

Los docstrings permiten documentar funciones, clases y módulos.

```python
def calcular_iva(precio):
    """Calcula el IVA de un precio."""
    return precio * 0.21
```

---

# 8. Errores y depuración

Durante la programación podemos encontrarnos diferentes tipos de errores.

## 8.1. Error de sintaxis

El programa no cumple las reglas de Python.

```python
if edad >= 18
    print("Mayor")
```

Falta `:`.

## 8.2. Error durante la ejecución

El código puede ser sintácticamente correcto, pero producir un error al ejecutarse.

```python
numero = int("hola")
```

Python no puede convertir `"hola"` en un entero.

## 8.3. Error lógico

El programa se ejecuta, pero produce un resultado incorrecto.

```python
precio = 100
descuento = 20

precio_final = precio + descuento
```

El código funciona, pero el cálculo es incorrecto si el descuento debe restarse.

## 8.4. Depuración

La **depuración** consiste en localizar y corregir errores del programa.

Los IDE como PyCharm permiten:

- Ejecutar el programa paso a paso.
- Consultar variables.
- Establecer puntos de interrupción.
- Analizar el flujo de ejecución.
- Localizar errores.

---

# 9. Buenas prácticas

### Legibilidad

```python
precio_total = precio_producto + gastos_envio
```

### Coherencia

Evita mezclar estilos:

```python
nombre_usuario = "Ana"
edadUsuario = 25
```

Mejor:

```python
nombre_usuario = "Ana"
edad_usuario = 25
```

### Sencillez

Evita soluciones innecesariamente complejas.

### Documentación

Utiliza comentarios y docstrings cuando aporten información útil.

### Mantenibilidad

El código debe poder ser entendido y modificado fácilmente por otra persona.

---


> **Idea clave:** un buen programa no solo debe funcionar; también debe ser fácil de leer, entender y mantener.
