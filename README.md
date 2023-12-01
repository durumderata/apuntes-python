# apuntes-python

Mis apuntes de python

## Print

La función `print()` se encarga de imprimir por pantalla

por ejemplo:

```python
print("hola que tal")
```
Podemos concatenar cadenas de caracteres.
```python
print("hola", "que tal")
print("hola"+ "que tal")
```
## Input
La función `input()` nos permite introducir información a traves del teclado.
Podemos utilizarlo sin indicar nada entre paréntesis:

```python
print("introduce tu nombre")
input()
```
si escribimos dentro de los paréntesis, podemos mostrar información antes de escribir:
```python
input("introduce tu nombre")
```
## Variables
Las variables nos permiten guardar en ellas información. Hay muchos tipos de variables:

- **Enteros**: 5
- **Cadenas de texto**: ""Dani
- **Booleanos**: True, False

Las variables tienen un nombre que las identifíca. Por ejemplo:

```python
Edad = 20
Nombre = "Dani"
Vivo = True
```
Para imprimir una variable indicamos su nombre sin comillas:
```python
nombre = "Dani"
print(nombre)
```
El signo igual asigna un valor a la variable.

Un ejemplo completo:

```python
nombre = input("dime tu nombre")
print(nombre)
```
Si queremos convertir el resultado de un input en un número utilizamos la función `int()`

```python
edad = int(input("dime tu edad"))
print(edad + 5)
```
## Condicionales
Para decidir ejecutar o no un bloque de código en función de si se cumple o no una condición
utilizamos el `if()`
```python 
edad = 18
if edad >= 18:
    print("mayor de edad")
else:
    print("eres menor de edad")
```
## Bucles
Los bucles nos permiten repetir un bloque de código más de una vez.  
De ejemplo usaremos `for`
```python
for numero in (0,5):
    print(numero)
```
También podemos recorrer una lista:
```python
alumnos = ["pepe", "manolo", "juan"]
for alumno in alumnos:
    print(alumno)
```