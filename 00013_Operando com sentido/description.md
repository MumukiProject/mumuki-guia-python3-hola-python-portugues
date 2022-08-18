Como acabamos de ver, em Python existem números, booleanos e strings:

|  Tipo de dado |  Representa         	|  Exemplo |  Operações               	|
|---------------|-------------------------|----------|--------------------------------|
|Números    	|quantidades           	| `4947`   | `+`, `-`, `*`, `/`, `<`, etc .  |
|Booleanos  	|valores de verdade    	| `True`   | `and`, `or`, etc.
|Strings    	|texto                	| `"olá Python!"` | `str.upper`, `str.startswith`, `len` |


Além disso, existem operações que servem para todos os _tipos de dados_, por exemplo:

* `==`: diz se duas coisas são iguais;
* `!=`: diz se duas coisas são diferentes.

**É importante usar as operações corretas com os tipos de dados corretos**, por exemplo, não faz sentido somar dois booleanos ou fazer operações booleanas com os números. **Se você usa operações que não correspondem, coisas muito estranhas podem acontecer**. :confounded:

> Tente no console o seguinte:
>
>``` python
ム5 + 6
```
>
>``` python
ム5 == "5"
```
>
>``` python
ム8 > 6
```
>
>``` python
ムFalse / True
```
>
>``` python
ム'olá' or 'tchau'
```
> Todas essas operações têm algum sentido?
