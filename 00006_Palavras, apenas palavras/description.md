Já conhecemos os números e os booleanos de Python, mas isso não é tudo!

Muitas vezes queremos escrever programas que trabalhem com texto :page_facing_up:: queremos saber quantas palavras há em um livro, ou modificar letras minúsculas para maiúsculas, ou saber em que parte de um texto está outro texto.

Para este tipo de problemas temos as _strings_, também chamadas _cadeias de caracteres_:

* `"Em 15 minutos estou pronto"`
* `'O nutriente ferro nos ajuda a brincar'`
* `"Olá Miguel!"`

Como é possível observar, todas as strings estão entre aspas simples ou duplas. Você pode usar qualquer uma delas! Mas seja coerente: por exemplo, se abriu com aspas duplas, precisa finalizar com aspas duplas. Além disso, uma string pode estar formada por (quase) qualquer caractere: letras, números, símbolos, espaços, etc.

E o que podemos fazer com as strings? Por exemplo, comparar elas como fazemos com qualquer outro valor:

```python
ム "olá" == "Olá"
False

ム "todo o mundo" == "todo o mundo"
True
```

e também concatená-las, isto é, obter uma string a partir da união de outras. :chains:

> Tente o seguinte no console:
>
> ```python
ム"guarda" + "pó"
```
>
> ```python
ム"Olá, " + "como você está?"
```
>
> ```python
ム"Me dê " + str(5)
```
>
> ```python
ム'Borbo' + 'leta'
```
