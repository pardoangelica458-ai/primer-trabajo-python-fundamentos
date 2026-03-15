# Laboratorio 1 - Fundamentos de Python

## Descripción
Este laboratorio consiste en crear un programa en Python que solicite un número al usuario y determine si es mayor que 10 o menor o igual.

## Objetivo
Practicar los siguientes conceptos de Python:

- Entrada de datos con `input()`
- Conversión de datos con `int()`
- Condicionales `if` y `else`

## Código del programa

```python
numero = int(input("Ingrese numero: "))

if numero > 10:
    print("Mayor a 10")
else:
    print("Menor o igual")
