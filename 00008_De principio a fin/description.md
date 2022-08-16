Como vimos, `in` nos puede decir si un string está incluído en otro. Hay dos casos particulares de esta operación: cuando un string comienza, o termina, con otro. 

La sintaxis de estas operaciones es _apenitas_ :ok_hand: diferente de lo que venimos haciendo: hay que prefijarlas con `str.`. Por ejemplo, la operación que devuelve si un `string` comienza con otro es `str.startswith`, mientras que la que nos dice si termina con otro es `str.endswith`. :eyes:

> Probalas en la consola escribiendo:
>
>``` python
ムstr.startswith("Fundación e imperio", "Fundación")
```
>
>``` python
ムstr.endswith("Bueno, y sí", "y sí")
```
>
>``` python
ムstr.endswith("Hola, ¿qué tal?", "Hola")
```