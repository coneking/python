# Python

Repo con información de Python para su uso desde cero.

## Variables

Espacio en memoria donde se almacena un valor que puede cambiar durante la ejecución de un programa. <br>
El tipo de variable se define por su contenedor, por ejemplo si declaramos una variable `numero=1`, esta variable será de tipo `int`. Para saber de qué tipo de dato es una variable usamos la función predefinida `type()`.<br>

Ejemplo tipo de variable:

```py
>>> numero=1
>>> type(numero)
<class 'int'>
```
>Nota: En el ejemplo al ejecutar `type(numero)` indicando que la variable es de tipo `int`.

<br>

Ejemplo suma de variables <br>

Creamos dos variables de tipo `int` e imprimimos la suma entre ellas.

```py
>>> numero1=30
>>> numero2=50

>>> print (numero1+numero2)
80
```

<br>

### Comillas triples

Las comillas triples sirven para usar cadenas de texto largo que puedan contener saltos de línea dentro de una variable. <br>

Ejemplo comillas triples <br>

```py
>>> cadena="""Esto es una cadena
... con varios saltos
... de línea"""

>>> print (cadena)
Esto es una cadena
con varios saltos
de línea
```

