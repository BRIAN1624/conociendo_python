# Ejercicio 09 — Preguntar "¿Desea continuar? S/N"

Escribe un programa que realice la pregunta "¿Desea continuar S/N?" y que no
deje de hacerla hasta que el usuario teclee `N`.

## Ejemplo
¿Desea continuar S/N? S
¿Desea continuar S/N? s
¿Desea continuar S/N? x
¿Desea continuar S/N? N
Programa terminado.


## Pista

Normaliza la respuesta con `.upper()` para aceptar tanto `s`/`S` como `n`/`N`.
`while respuesta != "N":` y pide de nuevo dentro del bucle.

## Entrega

`entregas/<tu-usuario>/03_estructuras_ciclicas/ejercicio_09.py`