# Concessionaria

### Table of Contents
1. [Problema](#1-problema)
2. [Orientações](#2-orientações)
3. [Entrega](#3-entrega)
4. [Avaliação](#4-avaliação)

# 1. Problema

Implemente um programa em C++ que atenda aos seguintes critérios:

1. Uma **Concessionária** pode comercializar diversos tipos de **Veículos**: **Automóveis**, **Motos** e **Caminhões**. Cada Concessionária possui um nome, CNPJ e número de veículos no estoque.
2. Todo Veículo possui os seguintes campos: marca, preço, número do chassi e data de fabricação. Apenas Automóveis possuem um atributo relativo ao tipo de motor (gasolina ou elétrico); apenas Motos possuem um atributo relativo ao modelo (clássico ou esportivo); apenas Caminhões possuem um atributo relativo ao tipo de carga (comum ou perigosa).
3. O programa deverá permitir criar uma concessionária.
4. O programa deverá permitir que se adicione um veículo, seja ele um automóvel, moto ou caminhão, a uma concessionária e não deve permitir adicionar um veículo que já tenha sido anteriormente adicionado, sendo neste caso exibida uma mensagem de erro. Os veículos de uma concessionária deverão ser mantidos em um único _array_, _vector_ ou _list_, ou ainda alguma outra estrutura de dados que você considere conveniente. 
5. A concessionária deve possuir um atributo relativo à sua Propriedade, que pode ser de uma pessoa física ou de uma pessoa jurídica. Uma Propriedade é caracterizada por dois nomes. Pessoas físicas possuem como primeiro e segundo nomes uma string, enquanto que pessoas jurídicas utilizam um número de 9 dígitos como primeiro nome e um número de 4 dígitos como segundo nome.
6. A concessionária deve possuir um atributo para o registro de todos os chassis dos seus veículos. O programa deve permitir que se realize uma busca por número de chassi. Caso o veículo pertença à concessionária, o programa deve exibir na tela seus atributos.
7. O programa deverá permitir escrever em um arquivo de texto todo o estoque de uma concessionária, incluindo os atributos comuns e particulares de cada veículo.
8. O programa deverá permitir criar uma concessionária à partir de um arquivo de texto no formato descrito no item 7.
9. O programa deve possuir uma função para listar os proprietários de concessionárias, a frota total de cada tipo de veículo e o valor total dos veículos.
10. O programa deverá permitir listar os dados de todos os veículos de uma concessionária, sobrecarregando-se o operador de inserção em stream (<<).
11. O programa deverá permitir que seja dado um aumento de X% ao preço de todos os veículos de uma determinada concessionária.
12. O programa deverá permitir listar os dados de todos os veículos de uma concessionária que foram produzidos há menos de 90 dias considerando a data corrente.

# 2. Orientações

- Utilize estritamente recursos da linguagem C++.
- Durante a compilação do seu código fonte, você deverá habilitar a exibição de mensagens de aviso (warnings).
- Aplique boas práticas de programação. Codifique o programa de maneira legível (com indentação de código fonte, nomes consistentes, etc.). Modularize e comente seu código.
- Garanta que seu programa funcione de forma correta e eficiente. Pense também nas possíveis entradas que poderão ser utilizadas para testar apropriadamente o seu programa e trate adequadamente possíveis entradas consideradas inválidas.
- A resolução da questão deve conter um arquivo makefile responsável pela compilação e ligação. 
- Quando não especificado, a modelagem das classes é livre, ou seja, inclua os atributos que você considerar importantes para resolver a questão. 

# 3. Entrega

Seu arquivo compactado deverá incluir também um arquivo texto README contendo: a identificação completa do aluno; a descrição de como compilar e rodar o programa, incluindo um roteiro de entradas e comandos que destaquem as funcionalidades (a)-(n); a descrição das limitações (caso existam) do programa e  quaisquer dificuldades encontradas. 

## 3.1 blablabla

# 4. Avaliação

O trabalho será avaliado sob os seguintes critérios: (i) utilização correta e abrangente dos conteúdos vistos anteriormente e nas aulas presenciais da disciplina; (ii) a corretude da execução do programa implementado, que deve apresentar saída em conformidade com a especificação e as entradas de dados fornecidas, e (iii) a aplicação correta de boas práticas de programação, incluindo legibilidade, organização e documentação de código fonte. A presença de mensagens de aviso (warnings) ou de erros de compilação e/ou de execução, a modularização inapropriada e a ausência de documentação são faltas que serão penalizadas. 

## Authorship

**Original problem: Silvio Sampaio**

**Current adaptation: Renan Moioli, [renan.moioli@imd.ufrn.br](mailto:renan.moioli@imd.ufrn.br)**


