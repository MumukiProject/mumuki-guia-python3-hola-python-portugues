Descobriu o padrão? :grimacing:

Para que `and` retorne `True` é necessário que ambas condições sejam verdadeiras. Por isso...

``` python
ム 8 < 10 and 8 > 9
```

... retorna `False`, porque 8 é menor que 10 mas não é maior que 9. Ou seja, `8 < 10` é `True` mas `8 > 9` é `False`. No entanto, ao tentar...

``` python
ム str.startswith("caracol", "cara") and str.endswith("caracol", "col")
```

... obtemos `True`, dado que ambas condições são verdadeiras. Em resumo:

```python
ム False and False
False
ム True and False
False
ム False and True
False
ム True and True
True
```


