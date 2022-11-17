# Concessionaria

### Table of Contents
1. [Problema](#1-problema)
2. [Orientações](#2-orientacoes)
3. [Entrega](#3-entrega)
4. [Avaliação](#4-avaliacao)

# 1. Problema

Implemente um programa em C++ que atenda aos seguintes critérios:

1. Uma Concessionária pode comercializar diversos tipos de veículos: automóveis, motos e caminhões. Cada Concessionária possui um nome, CNPJ e número de veículos no estoque.
2. Todo Veículo possui os seguintes campos: marca, preço, número do chassi e data de fabricação. Apenas Automóveis possuem um atributo relativo ao tipo de motor (gasolina ou elétrico); apenas Motos possuem um atributo relativo ao modelo (clássico ou esportivo); apenas Caminhões possuem um atributo relativo ao tipo de carga (comum ou perigosa).
3. O programa deverá permitir criar uma concessionária.
4. O programa deverá permitir que se adicione um veículo, seja ele um automóvel, moto ou caminhão, a uma concessionária e não deve permitir adicionar um veículo que já tenha sido anteriormente adicionado, sendo neste caso exibida uma mensagem de erro. Os veículos de uma concessionária deverão ser mantidos em um único array, vector1 ou list2, ou ainda alguma outra estrutura de dados que você considere conveniente. 
5. A concessionária deve possuir um atributo relativo à sua Propriedade, que pode ser de uma pessoa física ou de uma pessoa jurídica. Uma Propriedade é caracterizada por dois nomes. Pessoas físicas possuem como primeiro e segundo nomes uma string, enquanto que pessoas jurídicas utilizam um número de 9 dígitos como primeiro nome e um número de 4 dígitos como segundo nome.
6. A concessionária deve possuir um atributo para o registro de todos os chassis dos seus veículos. O programa deve permitir que se realize uma busca por número de chassi. Caso o veículo pertença à concessionária, o programa deve exibir na tela seus atributos.
7. O programa deverá permitir escrever em um arquivo de texto todo o estoque de uma concessionária, incluindo os atributos comuns e particulares de cada veículo.
8. O programa deverá permitir criar uma concessionária à partir de um arquivo de texto no formato descrito no item g.
9. O programa deve possuir uma função para listar os proprietários de concessionárias, a frota total de cada tipo de veículo e o valor total dos veículos.
10. O programa deverá permitir listar os dados de todos os veículos de uma concessionária, sobrecarregando-se o operador de inserção em stream (<<).
11. O programa deverá permitir que seja dado um aumento de X% ao preço de todos os veículos de uma determinada concessionária.
12. O programa deverá permitir listar os dados de todos os veículos de uma concessionária que foram produzidos há menos de 90 dias considerando a data corrente.
13. O programa deverá permitir listar a média de veículos por concessionária. O cálculo deve ser realizado a partir de atributos estáticos das próprias classes (Concessionária e Veículo). (Dica: para isso, seu programa deverá criar, como exemplo, algumas concessionárias contendo alguns Veículos).

# 2. Orientações

# 3. Entrega

## 3.1 A base de dados de DNA

# 4. Avaliação


## Authorship

**Original problem: Silvio Sampaio**

**Current adaptation: Renan Moioli, [renan.moioli@imd.ufrn.br](mailto:renan.moioli@imd.ufrn.br)**


