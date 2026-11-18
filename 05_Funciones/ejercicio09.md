# Ejercicio 09 — Función `contar_vocales(texto)`

Crea una función `contar_vocales` que reciba una cadena de texto y retorne
cuántas vocales contiene (contando mayúsculas y minúsculas). Pide una frase
al usuario y muestra el resultado.

## Ejemplo
Introduce una frase: Hola Mundo
La frase contiene 4 vocales.


## Pista

Convierte el texto a minúsculas con `.lower()` y recorre cada carácter.
Considera las vocales `a, e, i, o, u` (la `y` no se cuenta).

```python
def contar_vocales(texto):
    return sum(1 for c in texto.lower() if c in "aeiou")
```

## Entrega
entregas/<tu-usuario>/05_funciones/ejercicio_09.py