# Ejercicio 01 — Función `saludar(nombre)`

Crea una función llamada `saludar` que reciba un nombre como parámetro y
retorne el saludo `"Hola, <nombre>."`. Luego pide el nombre al usuario,
llama a la función e imprime lo que retorna.

## Ejemplo

Introduce tu nombre: Ana
Hola, Ana.


## Pista

```python
def saludar(nombre):
    return f"Hola, {nombre}."

if __name__ == "__main__":
    nombre = input("Introduce tu nombre: ")
    print(saludar(nombre))
```

entregas/<tu-usuario>/05_funciones/ejercicio_01.py