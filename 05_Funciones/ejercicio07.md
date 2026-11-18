# Ejercicio 07 — Función `es_primo(n)`

Crea una función `es_primo` que reciba un número entero y retorne `True` si es
primo y `False` en caso contrario. Pide un número al usuario e imprime si es
primo o no.

## Ejemplo

Introduce un número: 17
17 es primo.

Introduce un número: 18
18 no es primo.


## Pista

Un número es primo si solo es divisible entre 1 y él mismo (mayor que 1).
Basta con comprobar divisores hasta su raíz cuadrada:

```python
def es_primo(n):
    if n < 2:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True
```

## Entrega
entregas/<tu-usuario>/05_funciones/ejercicio_07.p
