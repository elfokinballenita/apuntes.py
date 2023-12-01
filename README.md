# apuntes.py
mis apuntes de python

## Print

La función `print()` se encarga de imprimir por pantalla

Por ejemplo:

```python
print("hola que tal")
print("hola","que tal")
```
## Input
La función `Input()`nos permite introducir información a traves del teclado
Podemos utilizarlo sin indicar nada entre paréntesis:

```python
input("introduce tu nombre")
```

## Variables
Las variables nos permiten guardas en ellas información. Hay muchos tipos de variables:

- **Enteros**: 5
- **Cadena de texto**:"Dani
- **Booleanos**: True, False

Las variables tienen un nombre que las identifica:

```python
Edad = 20
Nombre = "Dani"
print(nombre)
```

Ejemplo completo:

 ```python

nombre = input("dime tu nombre: ")
print(nombre)
```

Si queremos convertir los resultados de un input en un numero utilizamos la funció:
`int()`.

## Condicionales
Para decidir ejecutar o no un bloque de código eb fybción de si se cumple o no una condición utilizamos `if`.

```python
edad = 18
if edad >=18:
    print("tu eres mayor de edad")
else:
    print("eres menor de edad")
```
## Bucles
Los bucles nos permiten repetir un bloque de codigo más de una vez.

Un ejemplo es el bucle `for`.

```python
for numero un(0,5):
    print(numero)
```
También podemos recorrer una lista:
```python
alumnos = ["pepe","manolo","juan"]
for alumno in alumnos:
    print(alumnos)
```
## Funciones
Las funcione nos permiten guardar un bloque de código con un nombre para llamarlas cuando queramos. Las funciones terminan en paréntesis:
`sumar()`,`restar()`,etc.
