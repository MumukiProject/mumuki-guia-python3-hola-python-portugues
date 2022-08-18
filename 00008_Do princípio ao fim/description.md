Como vimos, `in` pode nos dizer se uma string está incluída em outra. Existem dois casos particulares nessa operação: quando uma string começa, ou termina, com outra.

A sintaxe dessas operações é _apenas_ :ok_hand: diferente do que vínhamos fazendo: é necessário usar o prefixo `str.`. Por exemplo, a operação que retorna se uma `string` começa com outra é `str.startswith`, enquanto que a operação que nos diz se termina com outra é `str.endswith`. :eyes:

> Tente essas operações no console escrevendo:
>
>``` python
ムstr.startswith("Fundação e império", "Fundação")
```
>
>``` python
ムstr.endswith("Bom, e sim", "e sim")
```
>
>``` python
ムstr.endswith("Olá, tudo bem?", "Olá")
```
