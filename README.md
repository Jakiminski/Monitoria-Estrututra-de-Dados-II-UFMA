# Monitoria Estrututra de Dados II-UFMA
## Introdução
- Implemente o algoritmo de ordenação no arquivo algoritmosDeOrdenacao.py
- Instruções básicas de como fazer a implementação estão inicio do arquivo algoritmosDeOrdenacao.py

## algoritmosDeOrdenacao.py
- Implementar algoritmo de ordenação que receba uma colecão
- A coleção é uma lista de arestas
- Para comparar o peso as arestas entre dois item da coleção basta usar a chave 'weight' (peso)

## Exemplos:
- Modo convencional
  - colecao[i] [operador de comparacao] colecao[j]
  - colecao[i] < colecao[j]

- Modo que você vai usar
  - int(colecao[i]['weight']) [operador de comparacao] int(colecao[j]['weight'])
  - int(colecao[i]['weight']) < int(colecao[j]['weight'])
  - É nescessário converter o valor pra Interger no momento da comparação a fim de evitar erros
