# Modelo para Apresentação do Lab05 - Marcadores e Taxonomia em Cypher

# Aluno
* `233895`: `Enrico Piovesana Fernandes`

## Tarefa de Cypher sobre Marcadores e Taxonomia

## Tarefa 1

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, sem considerar as categorias subordinadas.

### Resolução
~~~cypher
MATCH (node:Categoria {id:"Serviços"})<-[:Pertence]-(n)
RETURN n
~~~

## Tarefa 2

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, considerando as categorias subordinadas.

### Resolução
~~~cypher
MATCH (:Categoria {id:"Serviços"})<-[:Pertence*0..]-(n)
MATCH (:Categoria {id:"Serviços"})<-[:Superior*0..]-(m)<-[:Pertence*0..]-(p:Marcador)
RETURN p
~~~
