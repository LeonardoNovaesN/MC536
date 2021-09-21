# Aluno
* `220142`: `Leonardo Novaes do Nascimento`

## Tarefa de Cypher sobre Marcadores e Taxonomia

## Tarefa 1

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, sem considerar as categorias subordinadas.

### Resolução
~~~cypher
MATCH (n:Marcador) -[:Pertence]->(m:Categoria {id: 'Serviçoes'})
RETURN n
~~~

## Tarefa 2

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, considerando as categorias subordinadas.

### Resolução
~~~cypher
(escreva aqui a resolução em Cypher)
~~~
