Conseguiu descobrir as diferenças? :nerd:

Falamos  que `and` só retorna `True` quando ambos booleanos são `True`. Por outro lado, para que `or` seja verdadeiro basta que pelo menos um dos booleanos sejam. Ou seja, ambas condições devem ser falsas para que retorne `False`. Por exemplo em...

``` python
ム str.upper("mumuki") == "Mumuki" or "amor" in "romance"
```

... tanto `str.upper("mumuki") == "Mumuki"` como `"amor" in "romance"` retornam `False`. Se testamos com os booleanos veremos que:

```python
ム False or False
False
ム True or False
True
ム False or True
True
ム True or True
True
```

