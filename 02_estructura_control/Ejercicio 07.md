# Ejercicio 07 — Precio de lápices de colores

En una tienda se venden lápices de colores:

- Si se compran 10 o más, el costo unitario es de 80 centavos.
- Si se compran menos de 100 pero más de 50, el costo unitario es de $1.20.
- Si se compran de 30 a 50, el costo es de $1.50.
- Si se compran menos de 30, el costo por unidad es de $2.10.

Elabora un programa que permita calcular el costo de los lápices para cada caso.

> ⚠️ **Nota sobre el enunciado:** tal como está redactado, los rangos se
> solapan (por ejemplo, "10 o más" incluye 100, 50, 30…). En clase conviene
> discutir el orden de evaluación de los `if/elif` y decidir una
> interpretación consistente. Una lectura habitual es evaluar de mayor a
> menor cantidad:

| Cantidad | Precio unitario |
|----------|-----------------|
| 100 o más | $0.80 |
| más de 50 y menos de 100 | $1.20 |
| de 30 a 50 | $1.50 |
| menos de 30 | $2.10 |

## Ejemplo

Cantidad de lápices: 60
Total a pagar: 72.0 pesos


## Entrega

`entregas/<tu-usuario>/02_estructura_de_control/ejercicio_07.py`