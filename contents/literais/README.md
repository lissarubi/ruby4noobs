# Literais
Em Ruby, temos também os literais, que são basicamentes objetos que podem ser usado em seu código. São alguns deles:

- Symbols
- Arrays
- String

Symbols
----
Como visto já anteriormente, você podem criar um objeto da classe symbol, adicionando o prefixo `:` a uma string, como por exemplo: `:simbolo_bonito` ou `:"simbolo bonito"`.
Porém você pode usar os literais para criar como por exemplo, uma array de símbolos, no caso:
```ruby
array_de_simbolos = %i[cada elemento sera do tipo symbol a cada espaco]
#=> [:cada, :elemento, :sera, :do, :tipo, :symbol, :a, :cada, :espaco]
```
Também há outra forma de definir um simbolo usando `%s(simbolo_bonito)`

Arrays
----
Arrays são basicamente uma lista de elementos, e com elas conseguimos acessar seus elementos. Você também pode definir uma array de palavras utilizando um literal:
```ruby
array_de_palavrass = %w[cada elemento vai ser convertido em string a cada espaco]
=> ["cada", "elemento", "vai", "ser", "convertido", "em", "string", "a", "cada", "espaco"]
```
Semelhante ao array de símbolos.

String
----
String são uma cadeia de caracteres, e em Ruby, você consegue definir uma string com aspas simples e duplas, como em: `"string"` ou `'string'`, porém você também consegue criar strings de múltiplas linhas usando um literal, como por exemplo:

```ruby
string = %q{
String literal
de multiplas
linhas
}
```

ou então:
```ruby
string = <<~FOO
tambem pode ser definido assim
no caso isso é chamado de HEREDOC
FOO
```

Você pode ver mais sobre literais [aqui](https://docs.ruby-lang.org/en/2.0.0/syntax/literals_rdoc.html)
