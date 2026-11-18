# Ejercicio 10 — Función `calculadora(a, b, operacion="suma")`

Crea una función `calculadora` con **tres parámetros**: dos números y una
operación (`"suma"`, `"resta"`, `"multiplicacion"`, `"division"`). El tercer
parámetro debe tener `"suma"` como **valor por defecto**.

La función debe:
- Retornar el resultado de la operación.
- Si la operación no es válida, retornar `None`.
- Si se intenta dividir entre cero, retornar `None`.

Pide los datos al usuario (operación opcional) y muestra el resultado.

## Ejemplo 1 (usa el valor por defecto)

Primer número: 5
Segundo número: 3
Operación (suma/resta/multiplicacion/division) [suma]:
Resultado: 8


## Ejemplo 2

Primer número: 10
Segundo número: 0
Operación (suma/resta/multiplicacion/division) [suma]: division
No se puede realizar la operación.



## Pista

💡 Para leer la operación con valor por defecto:
op = input("Operación [...] [suma]: ") or "suma"
(si el usuario pulsa Enter, se queda con "suma").


## Entrega
entregas/<tu-usuario>/05_funciones/ejercicio_10.py