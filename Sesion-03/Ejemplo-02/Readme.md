🏠 [**Inicio**](../../Readme.md) ➡️ / 📖 [**Sesión 03**](../Readme.md) ➡️ / 📝 `Ejemplo 02: Tuplas y sus métodos`

## 🎯 Objetivo

Explorar los métodos y funciones esenciales de las tuplas en Python para manipular datos.


## 🚀 Introducción

Las tuplas en Python son estructuras de datos inmutables, lo que significa que una vez definidas no pueden ser modificadas aun en tiempo de ejecución. Esto las hace ideales para asegurar que los datos no sean cambiados a lo largo de un programa.

### 🔦 **Sintaxis básica de tuplas:**

```python
# Declaración de tuplas, con o sin elementos.
tupla_vacia = ()
tupla_vacia = tuple()
numeros = (1, 2, 3, 4, 5)
elementos = (1, 'hola', True, 3.1416)
```
### 🔦 **Acceso a elementos:**

```python
# Acceso mediante índice, que comienza en 0
numeros = (10, 20, 30, 40, 50)
print(numeros[0])  # Salida: 10
print(numeros[2])  # Salida: 30
```
### 🧰 **Métodos Comunes de Tuplas:**

| Método                | Descripción |
|-----------------------|-------------|
| `count(x)`            | Cuenta las apariciones de `x` en la tupla. |
| `index(x)`            | Devuelve el primer índice de `x` en la tupla. |

### 🔦 **Ejemplos de métodos comunes de tuplas:**

1. **`count()`** - Contar ocurrencias de un elemento:
   ```python
   elementos = (1, 2, 2, 3, 4, 2)
   cuenta = elementos.count(2)
   print(cuenta)  # 3
   ```

2. **`index()`** - Encontrar el primer índice de un elemento:
   ```python
   elementos = (1, 2, 3, 4, 5)
   indice = elementos.index(3)
   print(indice)  # 2
   ```

---

### 🍰 **Slicing en Tuplas:**

El slicing permite acceder a subconjuntos de elementos en una tupla mediante rangos.

```python
# Subtuplas mediante slicing.
# Sintaxis: tupla[inicio:fin:incremento], el rango es [inicio, fin).

numeros = (10, 20, 30, 40, 50, 60, 70, 80)
subtupla = numeros[2:5]
print(subtupla)  # (30, 40, 50)
```

---

### 💡 **Sabías que...**

La función `len()` también puede ser utilizada para obtener la longitud de una tupla, la cual es equivalente al número de elementos que contiene.

```python
numeros = (10, 20, 30, 40, 50)
longitud = len(numeros)
print(longitud)  # 5
```

También podemos obtener la longitud de otros tipos de datos como listas, diccionarios, cadenas, esto es especialmente útil cuando no conocemos el tamaño de los datos con los que estamos trabajando.

---

⬅️ [`Anterior`](../Readme.md) | [`Siguiente`](../Reto-01/Readme.md) ➡️
